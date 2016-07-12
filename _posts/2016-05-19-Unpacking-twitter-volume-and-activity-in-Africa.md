---
layout: public_reports
title: Unpacking twitter volume and activity in Africa
subtitle: Volume & Activity 
date: "2016-05-19 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "Analysis on the top contributors to twitter conversation in Africa"
images: "images/sky.jpg"
categories: public_research
ogimage: sky.jpg
published: true
---
<div class="row">
	<div class='medium-2 large-2 columns'>
		<div class='spacing'></div>
	</div>
<div class='medium-8 large-8 columns'>
<p>The Citizen Research Centre has just released its 2015 Africa Twitter Activity Index – studying twitter volume and activity levels in 52 of the 54 African states. The Index has been compiled in collaboration with Crimson Hexagon, a world leading social media monitoring platform.</p>

<h3>Volume</h3>

<p>According to the Citizen Research Centre, the top 4 countries in Africa accounted for 81% of all twitter volume on the continent.</p> 

<p>The Top 4 countries by volume of tweets were Egypt, South Africa, Nigeria and Kenya – sending out just over 1 billion tweets between them in 2015. The remaining 48 countries sent ‘just’ 232 million tweets.</p>

<div id="voltweets" style="min-width: 275px; height: 400px; margin: 0 auto"></div>

<p>The variance between the top and bottom countries is stark – Egypt sent out 344 397 013 tweets in 2015, with the bottom ranked country by volume – Equatorial Guinea – sending out just 7 470 tweets in the same period.</p>

<p>Even in the Top 5 countries by volume the fall off is dramatic.  The fourth highest country by volume – Kenya – sent 173 785 414 tweets in 2015.  The fifth highest country by volume – Ghana – sent less than a 5th of that number - 34 719 648.</p>  

<div id="voltweetstop" style="min-width: 275px; height: 400px; margin: 0 auto"></div>

<h3>Language</h3>

<p>Of all tweets sent out by Africans in 2015, 58% were in English, 29% in Arabic, only 3.5 % in French and less than 1 percent in Portuguese. Crimson Hexagon does not ‘read’ any indigenous African languages, but we can assume that they comprise most of the 9% of tweets that could be characterised as ‘other’. These languages have grown in use from 2% of the conversation in 2011 to 9% in 2015.</p>

<div id="language" style="min-width: 275px; height: 400px; margin: 0 auto"></div>

<p>In terms of volume, North African countries are prominent in the top 15 – with all of Egypt (1st), Algeria (6th), Morocco (7th), Libya (8th) and Tunisia (11th) represented in the top 15 countries by volume.</p>

<div id="voltweetstopnorth" style="min-width: 275px; height: 400px; margin: 0 auto"></div>

<h3>Activity</h3>

<p>Activity levels are different to volume levels in that they look at the number of tweets sent per member of the population. Here South Africa emerged as the most active African country on twitter, with South Africans sending 4.7 tweets per member of the population in 2015. Egypt ranked second with 3.9 and Kenya third with 3.7 tweets per citizen.</p>

<p>Botswana, the Seychelles, Namibia and Mauritius all performed well on an activity level.  They ranked 4th, 5th, 7th and 8th respectively. All have populations under three million with relatively concentrated urban populations. All also have well developed tourist economies, which also helps explain their high levels of activity relative to their populations. Crimson Hexagon identifies where tweets come from, so any tweets sent by tourists while in these countries would register as tweets sent from that country.</p>

<div id="top10activity" style="min-width: 275px; height: 400px; margin: 0 auto"></div>

<p>The difference between viewing twitter by activity rather than volume is best illustrated by Nigeria – which ranks 3rd on volume, but given its huge population of 183 million ranks 9th on activity.</p>

<p>All of these numbers pale in comparison when compared to European figures.  The Citizen Research Centre will release its European Index shortly. But a sneak preview shows that the highest volume European country is the United Kingdom, which sent in excess of 5.5 billion tweets in 2015. This is a rate of 87 tweets per member of the population in 2015. This makes citizens in the UK almost 20 times as active as the most active African country (South Africa).</p>


<p>Go to the <a href="{{site.url}}/africa-twitter-index.html">Twitter Activity Index page</a> to view the data by country.</p>
</div>
<div class='medium-2 large-2 columns'>
	<div class='spacing'></div>
	</div>
</div>
<div class="row">
<div class='medium-2 large-2 columns'>
        <div class='spacing'></div>
    </div>
<div class='medium-8 large-8 columns'>
<div class='spacing'></div>
<h3>About The Citizen Research Centre</h3>
<p><a href="{{site.url}}" target="_blank">The Citizen Research Centre</a> is an organisation dedicated to investigating our societies and providing accurate, meaningful data that can be used to effect change – through knowledge, understanding of ourselves and ‘the other’ and through policy.</p><p>
We describe what we do as social research. This is research done in order to improve and expand on our knowledge of the world by providing decision makers in social policy and intervention projects with the best data possible.</p><p>
We run primary face-to-face research - both quantitative and qualitative - in 54 countries in Africa and the Middle East. <a href="where-we-work.html" target="_blank">Click here</a> for a list of countries in which we run face-to-face research.</p><p>
We run analytic research on social media globally through our partnership with <a href="http://www.crimsonhexagon.com/" target="_blank">Crimson Hexagon</a>, arguably the best social media analysis platform in the world. This and other reports are generated through mining and reporting on our social media data base, which currently holds almost 1 trillion pieces of social media data.</p><p>
We are committed to providing research on Citizens, and also research for Citizens – that reflect their own views back to them through social media analytics.
The nature of social media analysis is such that any topic can be rigorously explored.  If you would like to purchase in depth reporting on this or any other topic, please contact us</p>  <h3 style="text-align: center;"><a href="mailto:info@citizenresearchcentre.org">info@citizenresearchcentre.org</a></h3>
</div>
<div class='medium-2 large-2 columns'>
    <div class='spacing'></div>
    </div>
</div>

<script>
$(function () {
    $('#voltweets').highcharts({
        chart: {
            type: 'column'
        },
        title: {
            text: 'Volume of Tweets - Top 4 Countries vs Rest of Africa'
        },
        xAxis: {
            categories: [
                'Countries'
            ],
            crosshair: true
        },
        yAxis: {
            min: 0,
            title: {
                text: 'Volume of Tweets'
            }
        },
        tooltip: {
            valueSuffix: ''
        },
        plotOptions: {
            column: {
                pointPadding: 0.2,
                borderWidth: 0
            }
        },
        series: [{
            name: 'Egypt',
            data: [334497013],
            color: '#F9A61C'

        }, {
            name: 'South Africa',
            data: [250593472],
            color: '#333333'

        }, {
            name: 'Nigeria',
            data: [242840161],
            color: '#26B8EB'

        },
        {
            name: 'Kenya',
            data: [173785414],
            color: '#868686'

        },
        {
            name: 'Rest of Africa (48 Countries)',
            color: '#33ff71',
            data: [232224419]

        }]
    });
});
</script>
<script>
$(function () {
    $('#voltweetstop').highcharts({
        chart: {
            type: 'column'
        },
        title: {
            text: 'Volume of Tweets - Top 5 Countries'
        },
        xAxis: {
            categories: [
                'Countries'
            ],
            crosshair: true
        },
        yAxis: {
            min: 0,
            title: {
                text: 'Volume of Tweets'
            }
        },
        tooltip: {
            valueSuffix: ''
        },
        plotOptions: {
            column: {
                pointPadding: 0.2,
                borderWidth: 0
            }
        },
        series: [{
            name: 'Egypt',
            data: [334497013],
            color: '#F9A61C'

        }, {
            name: 'South Africa',
            data: [250593472],
            color: '#333333'

        }, {
            name: 'Nigeria',
            data: [242840161],
            color: '#26B8EB'

        },
        {
            name: 'Kenya',
            data: [173785414],
            color: '#868686'

        },
        {
            name: 'Ghana',
            color: '#33ff71',
            data: [34719648]

        }]
    });
});
</script>
<script>
  $(function () {
    $('#language').highcharts({
        chart: {
            plotBackgroundColor: null,
            plotBorderWidth: null,
            plotShadow: false,
            type: 'pie'
        },
        title: {
            text: 'Breakdown of Language - Africa Twitter (2015)'
        },
        tooltip: {
            pointFormat: '{series.name}: <b>{point.percentage:.2f}%</b>'
        },
        plotOptions: {
            pie: {
                allowPointSelect: true,
                cursor: 'pointer',
                dataLabels: {
                    enabled: true,
                    format: '<b>{point.name}</b>: {point.percentage:.1f} %',
                    style: {
                        color: (Highcharts.theme && Highcharts.theme.contrastTextColor) || 'black'
                    }
                }
            }
        },
        series: [{
            name: 'Languages',
            colorByPoint: true,
            data: [{
                color: '#F9A61C',
                name: 'English',
                y: 58
            }, {
                color: '#333333',
                name: 'Arabic',
                y: 29,
                sliced: true,
                selected: true
            }, {
                color: '#26B8EB',
                name: 'French',
                y: 3.5
            }, {
                color: '#868686',
                name: 'Portuguese',
                y: 0.6
            }, {
                color: '#33ff71',
                name: 'Indigenous or other languages',
                y: 8.96
            }]
        }]
    });
});
  </script>
  <script>
$(function () {
    $('#voltweetstopnorth').highcharts({
        chart: {
            type: 'column'
        },
        title: {
            text: 'Volume of Tweets - Top 5 North African Countries'
        },
        xAxis: {
            categories: [
                'Countries'
            ],
            crosshair: true
        },
        yAxis: {
            min: 0,
            title: {
                text: 'Volume of Tweets'
            }
        },
        tooltip: {
            valueSuffix: ''
        },
        plotOptions: {
            column: {
                pointPadding: 0.2,
                borderWidth: 0
            }
        },
        series: [{
            name: 'Egypt',
            data: [334497013],
            color: '#F9A61C'

        }, {
            name: 'Algeria',
            data: [25532709],
            color: '#333333'

        }, {
            name: 'Morocco',
            data: [22610106],
            color: '#26B8EB'

        },
        {
            name: 'Libya',
            data: [18566310],
            color: '#868686'

        },
        {
            name: 'Tunisia',
            color: '#33ff71',
            data: [11137350]

        }]
    });
});
</script>
 <script>
$(function () {
    $('#top10activity').highcharts({
        chart: {
            type: 'column'
        },
        title: {
            text: 'Twitter Activity per Person per Annum - Top 10 Africa Activity Index'
        },
        xAxis: {
            categories: [
                'Countries'
            ],
            crosshair: true
        },
        yAxis: {
            min: 0,
            title: {
                text: 'Tweets per Person per Annum'
            }
        },
        tooltip: {
            valueSuffix: ''
        },
        plotOptions: {
            column: {
                pointPadding: 0.2,
                borderWidth: 0
            }
        },
        series: [{
            name: 'South Africa',
            data: [4.685],
            color: '#F9A61C'

        }, {
            name: 'Egypt',
            data: [3.95],
            color: '#333333'

        }, {
            name: 'Kenya',
            data: [3.717],
            color: '#26B8EB'

        },
        {
            name: 'Botswana',
            data: [3.714],
            color: '#868686'

        },
        {
            name: 'Seychelles',
            color: '#33ff71',
            data: [3.173]

        },
        {
            name: 'Libya',
            data: [2.939]

        }, {
            name: 'Namibia',
            data: [2.091]

        }, {
            name: 'Mauritius',
            data: [1.597]

        },
        {
            name: 'Nigeria',
            data: [1.323]

        },
        {
            name: 'Ghana',
            data: [1.287]

        }]
    });
});
</script>