---
layout: public_reports
title: Re-engAge: Brexit, the Young and the Old
subtitle: Unpacking Social Media Data on Brexit 
date: "2016-05-19 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "This paper examines what the young and the old were saying on social media before and after the Brexit vote, and attempts to answer the question on the lips of Remain supporters – how did it come to this?"
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


<div id="language" style="min-width: 275px; height: 400px; margin: 0 auto"></div>


<p>The Citizen Research Centre is an organisation dedicated to investigating our societies and providing accurate, meaningful data that can be used to effect change – through knowledge, understanding of ourselves and ‘the other’ and through policy.</p>

<p>We run primary face-to-face research - both quantitative and qualitative - in 54 countries in Africa and the Middle East.</p>

<p>We run analytical research on social media globally through our partnership with Crimson Hexagon, arguably the best social media analysis platform in the world.
</p>

<p>Go to the <a href="{{site.url}}/africa-twitter-index.html">Twitter Activity Index page</a> to view the data by country.</p>
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