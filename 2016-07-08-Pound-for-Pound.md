---
layout: public_reports
title: Pound for Pound | Social Media Conversation on the Pound vs Crypto Currencies during Brexit
subtitle: Unpacking Social Media data on Brexit 
date: "2016-07-06 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "The Brexit referendum result had a dramatic effect on currencies around the world, and on the pound in particular. It also impacted on crypto currencies, the most famous of which is Bitcoin."
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
<p>The Brexit referendum result had a dramatic effect on currencies around the world, and on the pound in particular. It also impacted on crypto currencies, the most famous of which is Bitcoin.</p>
<p>Using <a href="http://www.crimsonhexagon.com/" target="_blank">Crimson Hexagon</a>, we analysed social media traffic from the 1 June to the 4th July 2016 to find out more. </p><p>
Overall conversation on Brexit over this period comprised 8,030,014 pieces of social media data. Of these, 360 491 posts concerned the pound and various crypto currencies.</p><p>
Of these 360 4912 posts, 88% focused on the pound and 12% on crypto currencies.</p><p>
Most of the conversation took place around and after referendum day, with 46% of the conversation taking place on June the 24th:
</p>
<p style="text-align: center;" ><img src="images/blog-images/conversation_1.PNG"></p>
<div class='spacing'></div>
<h3>Pound Centric Conversation Topic Waves</h3>
<p>Pound centric conversation was all doom and gloom once the result was announced: </p>
<p style="text-align: center;" ><img src="images/blog-images/crypto_conversation.PNG"></p>
<div class='spacing'></div>
<h3>Crypto Currency Centric Conversation Topic Waves</h3>
<p>Crypto Currency conversation by contrast was quite upbeat – with crypto currencies touted as an increasingly attractive option following the Brexit referendum.  Most of the conversation concerned the spike in the Bitcoin prices, with minor themes being the growth of Bitcoin in popularity after the referendum.</p><p>
While this has since corrected, immediately following the vote, the Pound dropped as much as 9%, and the value of Bitcoin climbed by 8%.
</p>
<p style="text-align: center;" ><img src="images/blog-images/crypto_conversation.PNG"></p>
<div class='spacing'></div>
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