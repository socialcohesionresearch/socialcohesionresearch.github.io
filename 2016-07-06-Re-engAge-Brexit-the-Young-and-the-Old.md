---
layout: public_reports
title: Re-engAge | Brexit, the Young and the Old
subtitle: Unpacking Social Media data on Brexit 
date: "2016-07-06 20:37:53 +0800"
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
<h3>Overview</h3>
<p>Post-Brexit Britain is in a state of political and social fracture – and there was widespread disbelief when the results were announced. Bookies had stay at 3-10 and leave at 5-2; polls suggested it was close to a foregone conclusion that the stay vote would win. There was jubilation in the Leave camp, coupled with a rising sense of unease at the inevitable question – what now?</p><p>
This paper examines what the young and the old were saying on social media before and after the Brexit vote, and attempts to answer the question on the lips of Remain supporters – how did it come to this?</p><p>
One of the more popular theories in this debate is that the younger generation have been let down by an out of touch, disengaged older generation. That younger citizens desperately wanted to stay, but were voted down by their parents and grandparents; that the ambitions of the young and hopeful were eaten by the old and fearful.
</p>
<p style="text-align: center;" ><img src="images/blog-images/old_negative.png" widht="80%"></p>
<p>According to a YouGov.co.uk poll of 554 registered voters aged of 18 to 24, 75% of the age group intended to vote to remain. Of interest to us was the 10% of these voters that didn’t vote - against only 2% of voters over the age of 65 that chose not to vote.  If these figures could be extrapolated out, would that 10% of voters have been enough to swing the vote to a decision to stay? Need attribution link</p>

<table style="margin-left:auto; 
    margin-right:auto;">
     <caption>YouGov.co.uk Brexit Poll</caption>
  <tr>
    <th></th>
    <th>18-24</th>
    <th>25-49</th>
    <th>50-64</th>
    <th>65+</th>
  </tr>
  <tr>
    <td><strong>Sample Size</strong></td>
    <td>554</td>
    <td>2042</td>
    <td>1174</td>
    <td>1002</td>
  </tr>
  <tr>
    <td><strong>Pre Vote Day</strong></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Remain</td>
    <td bgcolor="#fcbf31">75</td>
    <td>56</td>
    <td>44</td>
    <td>39</td>
  </tr>
  <tr>
    <td>Leave</td>
    <td>25</td>
    <td>44</td>
    <td>56</td>
    <td bgcolor="#fcbf31">61</td>
  </tr>
  <tr>
    <td><strong>After Voting Closed</strong></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Remain</td>
    <td>66</td>
    <td>52</td>
    <td>42</td>
    <td>38</td>
  </tr>
  <tr>
    <td>Leave</td>
    <td>23</td>
    <td>40</td>
    <td>53</td>
    <td>59</td>
  </tr>
  <tr>
    <td>Did not Vote</td>
    <td bgcolor="#fcbf31">10</td>
    <td>7</td>
    <td>5</td>
    <td>2</td>
  </tr>
</table>
<p>So we decided to look into social media to investigate further.  Using Crimson Hexagon (link), we analysed 297,474,704 tweets, Facebook and Tumblr posts, blogs and forums originating from the UK in June 2016. This social media research approach affords us an intimate and uniquely honest view of the entire online conversation from public sources.</p>
<p style="text-align: center;" ><img src="images/blog-images/Caputo-tweet.png"></p>
<p style="text-align: center;" ><img src="images/blog-images/shukat-tweet.png"></p>
<h3>The Old vs The Young?</h3>
<p>Much has been made of the youth being angry at ‘old’ people voting against their interest, as tweets such as this show:</p>
<p style="text-align: center;" ><img src="images/blog-images/luke-hawlet-tweet.png" width="45%">   <img src="images/blog-images/ellie-sadler-tweet.png" width="45%"></p>
<p>And weighing up the decision based on life expectancy:</p>
<p style="text-align: center;" ><img src="images/blog-images/tom-holder-tweet.png" width="65%"></p>
<p>Social media analysis shows, though, that the youth were remarkably ambivalent about Brexit before the referendum.</p><p>
From the 297 million posts generated during  June of 2016 in the UK, we identified 7 496 582 that discussed Brexit.  The Crimson Hexagon platform then used a complex algorithm to identity the age groups associated with those posts.  The platform was able to identify the age of over 22% of those posts.  This does not look at whether these posts were for or against leaving, but rather looks at the level of engagement of various age groups in the conversation.  This leaves us with 1 707 771 posts to analyse – a very healthy sample of public opinion on Brexit.
</p>
<div id="prevote" style="min-width: 275px; height: 400px; margin: 0 auto"></div>


</div>
<div class='medium-2 large-2 columns'>
    <div class='spacing'></div>
    </div>
</div>




<script>
  $(function () {
    $('#prevote').highcharts({
        chart: {
            plotBackgroundColor: null,
            plotBorderWidth: null,
            plotShadow: false,
            type: 'pie'
        },
        title: {
            text: 'The period June 1- June 22nd (the day before the referendum)'
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
            name: 'Age Groups',
            colorByPoint: true,
            data: [{
                color: '#F9A61C',
                name: 'Under 18',
                y: 7.6
            }, {
                color: '#333333',
                name: '18-24',
                y: 1.2,
                sliced: true,
                selected: true
            }, {
                color: '#26B8EB',
                name: '25-34',
                y: 1.8
            }, {
                color: '#868686',
                name: '35+',
                y: 89.4
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