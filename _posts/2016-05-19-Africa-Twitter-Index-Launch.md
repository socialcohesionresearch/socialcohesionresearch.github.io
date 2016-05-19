---
layout: public_reports
title: Africa Twitter Index 2015 Launched
subtitle: Unpacking Social Media in Africa
date: "2016-05-19 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "Better understand the biggest winners and losers on the African continent when it comes to Twitter. Find out who ranks number one on our African Twitter Index."
images: "images/blog-images/rise.jpg"
categories: public_research
published: true
---

<p>The Citizen Research Centre has just released its 2015 Africa Twitter Activity Index – studying twitter volume and activity levels in 52 of the 54 African states. The Index has been compiled in collaboration with Crimson Hexagon, a world leading social media monitoring platform.</p>

<h3>Volume</h3>

<p>According to the Citizen Research Centre, the top 4 countries in Africa accounted for 81% of all twitter volume on the continent.</p> 

<p>The Top 4 countries by volume of tweets were Egypt, South Africa, Nigeria and Kenya – sending out just over 1 billion tweets between them in 2015. The remaining 48 countries sent ‘just’ 232 million tweets.</p>

<div id="voltweets" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<p>The variance between the top and bottom countries is stark – Egypt sent out 344 397 013 tweets in 2015, with the bottom ranked country by volume – Equatorial Guinea – sending out just 7 470 tweets in the same period.</p>

<p>Even in the Top 5 countries by volume the fall off is dramatic.  The fourth highest country by volume – Kenya – sent 173 785 414 tweets in 2015.  The fifth highest country by volume – Ghana – sent less than a 5th of that number - 34 719 648.</p>  

<div id="voltweetstop" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<h3>Language</h3>
<div class="row">
<div class='medium-6 large-6 columns'>
<p>Of all tweets sent out by Africans in 2015, 58% were in English, 29% in Arabic, only 3.5 % in French and less than 1 percent in Portuguese. Crimson Hexagon does not ‘read’ any indigenous African languages, but we can assume that they comprise most of the 9% of tweets that could be characterised as ‘other’. These languages have grown in use from 2% of the conversation in 2011 to 9% in 2015.</p>
</div>
<div class='medium-6 large-6 columns'>
<div id="language" style="min-width: 310px; height: 400px; margin: 0 auto"></div>
</div>
</div>
<div class="row">
<div class='medium-6 large-6 columns'>
In terms of volume, North African countries are prominent in the top 15 – with all of Egypt (1st), Algeria (6th), Morocco (7th), Libya (8th) and Tunisia (11th) represented in the top 15 countries by volume. Highlighting the growth of social media in North African countries – Arabic has grown from comprising 9% of the total African conversation in 2013 to 29% of the total in 2015.
</div>
<div class='medium-6 large-6 columns'>
<div id="voltweetstopnorth" style="min-width: 310px; height: 400px; margin: 0 auto"></div>
</div>
</div>

<h3>Activity</h3>

Activity levels are different to volume levels in that they look at the number of tweets sent per member of the population. Here South Africa emerged as the most active African country on twitter, with South Africans sending 4.7 tweets per member of the population in 2015. Egypt ranked second with 3.9 and Kenya third with 3.7 tweets per citizen. 

Botswana, the Seychelles, Namibia and Mauritius all performed well on an activity level.  They ranked 4th, 5th, 7th and 8th respectively. All have populations under three million with relatively concentrated urban populations. All also have well developed tourist economies, which also helps explain their high levels of activity relative to their populations. Crimson Hexagon identifies where tweets come from, so any tweets sent by tourists while in these countries would register as tweets sent from that country.

The difference between viewing twitter by activity rather than volume is best illustrated by Nigeria – which ranks 3rd on volume, but given its huge population of 183 million ranks 9th on activity.

All of these numbers pale in comparison when compared to European figures.  The Citizen Research Centre will release its European Index shortly. But a sneak preview shows that the highest volume European country is the United Kingdom, which sent in excess of 5.5 billion tweets in 2015. This is a rate of 87 tweets per member of the population in 2015. This makes citizens in the UK almost 20 times as active as the most active African country (South Africa).

The Citizen Research Centre is an organisation dedicated to investigating our societies and providing accurate, meaningful data that can be used to effect change – through knowledge, understanding of ourselves and ‘the other’ and through policy. 

We run primary face-to-face research - both quantitative and qualitative - in 54 countries in Africa and the Middle East.

We run analytical research on social media globally through our partnership with Crimson Hexagon, arguably the best social media analysis platform in the world.

Go to the <a href="">Twitter Activity Index page</a> to view the data by country.

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
            name: 'Rest of Africa (46 Countries)',
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
                text: 'Volume of Tweets - Top 5 North Africa'
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