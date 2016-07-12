---
layout: public_reports
title: Pound for Pound
subtitle: Social Media Conversation on the Pound vs Crypto Currencies during Brexit 
date: "2016-07-06 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "The Brexit referendum result had a dramatic effect on currencies around the world, and on the pound in particular. It also impacted on crypto currencies, the most famous of which is Bitcoin."
images: "images/crypto.jpg"
categories: public_research
ogimage: crypto.jpg
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
<p style="text-align: center;" ><img src="images/blog-images/pound_conversation.PNG"></p>
<div class='spacing'></div>
<h3>Crypto Currency Centric Conversation Topic Waves</h3>
<p>Crypto Currency conversation by contrast was quite upbeat – with crypto currencies touted as an increasingly attractive option following the Brexit referendum.  Most of the conversation concerned the spike in the Bitcoin prices, with minor themes being the growth of Bitcoin in popularity after the referendum.</p><p>
While this has since corrected, immediately following the vote, the Pound dropped as much as 9%, and the value of Bitcoin climbed by 8%.
</p>
<p style="text-align: center;" ><img src="images/blog-images/crypto_conversation.PNG"></p>
<div class='spacing'></div>
<h3>Topics of Conversation</h3>
<p>This trend continued in the topic wheels of the conversations. The Pound conversation was largely doom and gloom…</p>
<p style="text-align: center;" ><img src="images/blog-images/pound_wheel.PNG"></p>
<p>While the Crypto Currency conversation was more hopeful:</p>
<p style="text-align: center;" ><img src="images/blog-images/crypto_wheel.PNG"></p>
<div class='spacing'></div>
<h3>Affinities</h3>
<p>A powerful tool in Crimson Hexagon’s social media analysis box is affinities analysis. Here we were able to match the interests of the people contributing to the Pound conversation against the rest of twitter, so the same for the members of the Crypto Currency conversation and then look at the variances of each against each other.</p><p>
Those contributing to the Pound conversation tended to be more ‘establishment’ – interested in stock markets, forex, David Cameron and finance.</p><p>
Those contributing to the Crypto Currency conversation were demonstrably more forward thinking – and tended to be interested in Noam Chomsky, P2P (sharing services), Bitcoin and Reddit. 
</p>
<h3>Implications</h3>
<p>As established currencies wax and wane, hedges emerge… Traditionally gold has been the hedge in turbulent times –now crypto currencies also play a role.</p><p>
While this piece has focused on the pound, emerging market currencies and economies usually bear the brunt of political uncertainty and social upheaval. Strong, coherent policies that are supported by citizens are the hallmark of a stable democracy. Brexit has shown us that even the most developed economies hide fractured societies, with disparate ambitions and goals for their future. Fear hides in the wings, and politicians need to beware of reducing complex decisions to binary options in referenda.
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