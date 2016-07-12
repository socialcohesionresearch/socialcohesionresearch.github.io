---
layout: public_reports
title: Pants on Fire: Brexit and it’s Lies
subtitle: Dissecting political lies in the build up and aftermath of the Brexit vote. 
date: "2016-07-06 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "These days it seems politicians are practically expected to lie – and no more so than in the debates pre and post the Brexit vote."
images: "images/lies.jpg"
categories: public_research
ogimage: lies.jpg
published: true
---
<div class="row">
    <div class='medium-2 large-2 columns'>
        <div class='spacing'></div>
    </div>
<div class='medium-8 large-8 columns'>
<h3>Overview: 1 January to 9 July 2016</h3>
<p>These days it seems politicians are practically expected to lie – and no more so than in the debates pre and post the Brexit vote.</p><p>
Who do people think told the biggest whoppers? This research looked at social media activity in the UK from the 1st January to the 9th July 2016 to find out…</p><p>
We used Crimson Hexagon (link), a leading social media analytics platform, to identify 694,154 pieces of social media data referring to politicians and their lies between 1 January and 9 July 2016.</p><p>
The conversation peaks in April, when the Panama Papers were released, and shows enormous growth around the time of the Brexit referendum. It peaks on the day of the vote with 37,170 number of posts.</p><p>
Note the timeline volume below, with the peak on the 24th largely related to the 350 million pound NHS porker perpetrated by the Leave campaign in general, and by Nigel Farage in particular…</p>
<p style="text-align: center;" ><img src="images/blog-images/lies_month.jpg"></p>

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

    $(document).ready(function () {

        // Build the chart
        $('#prevote').highcharts({
            chart: {
                plotBackgroundColor: null,
                plotBorderWidth: null,
                plotShadow: false,
                type: 'pie'
            },
            title: {
                text: 'June 1- June 22nd (the days before the referendum) '
            },
            tooltip: {
                pointFormat: '{series.name}: <b>{point.percentage:.1f}%</b>'
            },
            plotOptions: {
                pie: {
                    allowPointSelect: true,
                    cursor: 'pointer',
                    size: '80%',
                    dataLabels: {
                        enabled: true
                    },
                    showInLegend: false
                }
            },
            series: [{
                name: '% of Brexit Conversation',
                colorByPoint: true,
                data: [{
                    name: 'Under 18 (51 365 posts)',
                    color: '#26B8EB',
                    y: 6.5
                }, {
                    name: '18-24 (8 407 posts)',
                    color: '#333333',
                    y: 1.2
                }, {
                    name: '25-34 (12 404 posts)',
                    color: '#868686',
                    y: 1.8
                }, {
                    name: '35 + (605 724 posts)',
                    color: '#F9A61C',
                    y: 89.4,
                    sliced: true,
                    selected: true
                }]
            }]
        });
    });
});
  </script>

  <script>
  $(function () {

    $(document).ready(function () {

        // Build the chart
        $('#voteday').highcharts({
            chart: {
                plotBackgroundColor: null,
                plotBorderWidth: null,
                plotShadow: false,
                type: 'pie'
            },
            title: {
                text: 'The day of the referendum'
            },
            tooltip: {
                pointFormat: '{series.name}: <b>{point.percentage:.1f}%</b>'
            },
            plotOptions: {
                pie: {
                    allowPointSelect: true,
                    cursor: 'pointer',
                     size: '80%',
                    dataLabels: {
                        enabled: true
                    },
                    showInLegend: false
                }
            },
            series: [{
                name: '% of Brexit Conversation',
                colorByPoint: true,
                data: [{
                    name: 'Under 18 (20 180 posts)',
                    color: '#26B8EB',
                    y: 14.9
                }, {
                    name: '18-24 (4 397 posts)',
                    color: '#333333',
                    y: 3.2
                }, {
                    name: '25-34 (4036 posts)',
                    color: '#868686',
                    y: 3
                }, {
                    name: '35 + (107 166  posts)',
                    color: '#F9A61C',
                    y: 78.9,
                    sliced: true,
                    selected: true
                }]
            }]
        });
    });
});
  </script>

<script>
  $(function () {

    $(document).ready(function () {

        // Build the chart
        $('#threedaysafter').highcharts({
            chart: {
                plotBackgroundColor: null,
                plotBorderWidth: null,
                plotShadow: false,
                type: 'pie'
            },
            title: {
                text: 'Three days after the referendum (24-26 June)'
            },
            tooltip: {
                pointFormat: '{series.name}: <b>{point.percentage:.1f}%</b>'
            },
            plotOptions: {
                pie: {
                    allowPointSelect: true,
                    cursor: 'pointer',
                     size: '80%',
                    dataLabels: {
                        enabled: true
                    },
                    showInLegend: false
                }
            },
            series: [{
                name: '% of Brexit Conversation',
                colorByPoint: true,
                data: [{
                    name: 'Under 18 (86 551 posts)',
                    color: '#26B8EB',
                    y: 14.5
                }, {
                    name: '18-24 (20 014 posts)',
                    color: '#333333',
                    y: 3.4
                }, {
                    name: '25-34 (17 781 posts)',
                    color: '#868686',
                    y: 3
                }, {
                    name: '35 + (471 369   posts)',
                    color: '#F9A61C',
                    y: 79.1,
                    sliced: true,
                    selected: true
                }]
            }]
        });
    });
});
  </script>
   
<script>
  $(function () {

    $(document).ready(function () {

        // Build the chart
        $('#lastdaysjune').highcharts({
            chart: {
                plotBackgroundColor: null,
                plotBorderWidth: null,
                plotShadow: false,
                type: 'pie'
            },
            title: {
                text: 'The last three days of June'
            },
            tooltip: {
                pointFormat: '{series.name}: <b>{point.percentage:.1f}%</b>'
            },
            plotOptions: {
                pie: {
                    allowPointSelect: true,
                    cursor: 'pointer',
                    size: '80%',
                    dataLabels: {
                        enabled: true
                    },
                    showInLegend: false
                }
            },
            series: [{
                name: '% of Brexit Conversation',
                colorByPoint: true,
                data: [{
                    name: 'Under 18 (18 565 posts)',
                    color: '#26B8EB',
                    y: 6.2
                }, {
                    name: '18-24 (3772 posts)',
                    color: '#333333',
                    y: 1.3
                }, {
                    name: '25-34 (6705 posts)',
                    color: '#868686',
                    y: 2.2
                }, {
                    name: '35 + (269 335  posts)',
                    color: '#F9A61C',
                    y: 90.3,
                    sliced: true,
                    selected: true
                }]
            }]
        });
    });
});
  </script>