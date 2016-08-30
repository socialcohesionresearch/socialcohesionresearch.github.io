---
layout: public_reports
title: Hands Off Our Hair
subtitle: Detangling Social Media data on the Pretoria Girls High School Protest
date: "2016-05-19 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "Analysis on the top contributors to twitter conversation in Africa"
images: "images/sky.jpg"
categories: public_research
ogimage: sky.jpg
published: true
alt-image: "Lady on Mobile Phone"
---
<div class="row">
	<div class='medium-2 large-2 columns'>
		<div class='spacing'></div>
	</div>
<div class='medium-8 large-8 columns'>
    <h3>Overview</h3>
<p>On Saturday, 27 August, high school students from Pretoria Girls held a peaceful protest during the school’s annual Spring Fair. The march was organised by some of the year 8 students but was joined by Tuks students, old-girls from Pretoria Girls High and members of the public. In response, the school called on armed police, private security and a K9 unit - which saw the situation receive considerable traditional media and social media attention.
</p>
<p><img src="{{site.url}}/images/blog-images/ptagirls_volume.jpg" alt="Pretoria Girls Growth In Social Media Volume"></p>
<p>We analysed all South African social media from Friday 26 August to Monday 29 August and found 71,048 pieces of content related to the StopRacismAtPretoriaGirlsHigh issue - more than 99% of which were tweets.
</p>
<h3>Growth in Engagement</h3>
<p>The engagement was at it’s lowest on the day of the protest with only 94 tweets, compared to 185 the day before. The issue quickly drew and the volumes increased on Sunday to 16,673 and again on Monday with 54,096.
</p>
<p class="centered-text"><div id="growth" style="min-width: 275px; height: 400px; margin: 0 auto"></div></p>
<p><img src="{{site.url}}/images/blog-images/sentiment.jpg" alt="Sentiment towards Pretoria Girls Protest on Social Media"></p>
<p>The sentiment on Friday was mostly neutral, with only 16% being expressly positive and 27% negative. By Monday 29 August, the sentiment had shifted quite significantly to 22% positive and 44% negative.
</p>
<h3>Most Shared Tweets</h3>
</div>
<div class='medium-2 large-2 columns'>
        <div class='spacing'></div>
    </div>
    </div>
<div class="row">
    <div class='medium-2 large-2 columns'>
        <div class='spacing'></div>
    </div>
<div class='medium-4 large-4 columns'>
    <p><img src="{{site.url}}/images/blog-images/dailyvox.jpg" alt="Daily Vox Tweet"></p>
</div>
<div class='medium-4 large-4 columns'>
    <p><img src="{{site.url}}/images/blog-images/karabo_mokgoko.jpg" alt="Daily Vox Tweet"></p>
</div>
<div class='medium-2 large-2 columns'>
	<div class='spacing'></div>
	</div>
</div>
<div class="row">
    <div class='medium-2 large-2 columns'>
        <div class='spacing'></div>
    </div>
<div class='medium-4 large-4 columns'>
    <p><img src="{{site.url}}/images/blog-images/flo_letsoaba.jpg" alt="Daily Vox Tweet"></p>
</div>
<div class='medium-4 large-4 columns'>
    <p><img src="{{site.url}}/images/blog-images/khanya_dlanga.jpg" alt="Daily Vox Tweet"></p>
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
    <p>The most popular hashtags over the 4 day period was #StopRacismAtPretoriaGirlsHigh with more that 65,000 mentions. #ZulaikhaPatel - the girl who became the icon of the day, standing with crossed fists in the air in front of a greying, white, male superior - was mentioned more than 650 times.This would likely have been higher if she was not a minor as many individuals did not feel right about naming her for fear of backlash against her.
</p>
<div id="hashtag_mentions" style="height: 400px; float: left; margin: 1%;"></div>
<h3>Gender Participation</h3>
<p>The gender split in the conversation is - perhaps surprisingly - very balanced.</p>
<p class="centered-text"><div id="gender" style="height: 400px; float: left; margin: 1%;"></div></p>
<p>There was very little discernable difference topics of discussion and the content shared by men and women. 
</p>
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
    $('#growth').highcharts({

        chart: {
            type: 'column'
        },

        title: {
            text: 'Growth in Relevant Mentions'
        },

        xAxis: {
            categories: ['26th August', '27th August', '28th August', '29th August']
        },

        yAxis: {
            allowDecimals: false,
            min: 0,
            title: {
                text: 'Total Volume'
            }
        },

        tooltip: {
            formatter: function () {
                return '<b>' + this.x + '</b><br/>' +
                    this.series.name + ': ' + this.y + '<br/>'
            }
        },

        series: [{
            name: 'Mentions',
            data: [185, 94, 16673, 54096],
        }]
    });
});
</script>
<script>
$(function () {
    $('#hashtag_mentions').highcharts({
        chart: {
            type: 'bar'
        },
        title: {
            text: 'Hashtag Mentions'
        },
        subtitle: {
            text: 'Source: <a href="http://www.crimsonhexagon.com/">Crimson Hexagon</a>'
        },
        xAxis: {
            categories: ['#StopRacismAtPretoriaGirlsHigh', '#PretoriaGirlsHigh', '#ZulaikhaPatel', '#FeesMustFall', '#VK', '#RacismMustFall', '#Biko', '#Mbokodo', '#SABCSNews', '#PTAGirlsHigh'],
            title: {
                text: null
            }
        },
        yAxis: {
            min: 0,
            title: {
                text: 'Mentions',
                align: 'high'
            },
            labels: {
                overflow: 'justify'
            }
        },
        tooltip: {
            valueSuffix: ' mentions'
        },
        plotOptions: {
            bar: {
                dataLabels: {
                    enabled: true
                }
            }
        },
        credits: {
            enabled: false
        },
        series: [{
            name: 'Mentions',
            data: [65000, 4700, 650, 500, 370, 350, 270, 200, 160, 140]
        }]
    });
});
</script>
<script>
  $(function () {
    $('#gender').highcharts({
        chart: {
            plotBackgroundColor: null,
            plotBorderWidth: null,
            plotShadow: false,
            type: 'pie'
        },
        title: {
            text: 'Gender Participation'
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
            name: 'Gender',
            colorByPoint: true,
            data: [{
                color: '#F9A61C',
                name: 'Male',
                y: 43
            }, {
                color: '#333333',
                name: 'Female',
                y: 57,
                sliced: true,
                selected: true
            }]
        }]
    });
});
  </script>
