---
layout: public_reports
title: Boko Haram Fear and Funding Report
subtitle: Analysing data on Boko Haram
date: "2016-06-13 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "Analysis on the Fear and Funding of Boko Haram"
images: "images/boko.jpg"
categories: public_research
ogimage: boko.jpg
published: true
---
<div class="row">
	<div class='medium-2 large-2 columns'>
		<div class='spacing'></div>
	</div>
<div class='medium-8 large-8 columns'>
<p>We used Crimson Hexagon to answer three key questions of the social media conversation in Nigeria regarding Boko Haram:</li>
<ul><li>What issues of social concern are Nigerians talking about on social media?</li>
<li>How has the level of fear risen over the years?</li>
<li>How do people that are active on social media in Nigeria think Boko Haram is funded?</li>
</ul>
Our research timelines were January 2009 to November 2015</p>

<h3>Social Concerns</h3>
<p>We identified areas of socio-economic concern to Nigerians, and then identified and analysed 1,060,647,786 relevant social media posts coming out of Nigeria between January 2009 and November 2015.

We found that the breakdown of concerns expressed on social media over this time frame was as follows:</p>

<div id="concerns" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<div id="concerns_increase" style="min-width: 310px; height: 400px; margin: 0 auto"></div>


<h3>The Rise of Fear</h3>
<p>In looking at ‘Threat’ more closely, we found dramatic change over time. Threat here refers to threat to life or property – largely as a result of (but not limited to) Boko Haram activity.

In the years preceding Bok Haram’s increased level of activity (July 2010 to December 2013), we found Threat levels to be low to the point of insignificance. Throughout the period below, Threat comprised less than 1% of the total conversation on social media in Nigeria:</p>

<div id="before_concerns" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<p>Once Boko Haram became more active, this level increased dramatically. The graph below shows how Threat, between January 2014 and October 2015, grew to comprise fully 22% of the total Nigerian social media conversation on topics of socio-economic/ social interest. This is by far the greatest single contributor to the national conversation around socio economic issues in this timeframe.  Of interest too, is how education as a concern grew from 8 to 13% of the conversation over this time frame. </p>

<div id="after_concerns" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<div id="concerns_increase_14_15" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<h3>Funding of Boko Haram</h3>
<p>Turning our attention to Funding of Boko Haram, we identified 47 205 English posts emanating from Nigeria relating to the funding of Boko Haram over the time frame.  In social media data terms this is a small data set, but still represents, of course, 47 205 individual pieces of  data. In alanalsyi9ng this data set we found the following – given that ‘wealthy Nigerians’ inevitably refers to men of power, fully <strong>54% of all Nigerian social media opinion points the finger at various levels of government or official power.</strong></p>

<div id="funders" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

<h3>Funding of Boko Haram 2011</h3>
<p><img alt="" src="{{site.url}}/images/blog-images/funding2011.jpg" /></p>

<h3>Funding of Boko Haram 2012</h3>
<p><img alt="" src="{{site.url}}/images/blog-images/funding2012.jpg" /></p>

<h3>Funding of Boko Haram 2013</h3>
<p><img alt="" src="{{site.url}}/images/blog-images/funding2013.jpg" /></p>

<h3>Funding of Boko Haram 2014 (note the rise in volume)</h3>
<p><img alt="" src="{{site.url}}/images/blog-images/funding2014.jpg" /></p>

<h3>Funding of Boko Haram 2015 (note the rise in volume)</h3>
<p><img alt="" src="{{site.url}}/images/blog-images/funding2015.jpg" /></p>

<h3>About The Citizen Research Centre</h3>

<p><a href="{{site.url}}">The Citizen Research Centre</a> is an organisation dedicated to investigating our societies and providing accurate, meaningful data that can be used to effect change – through knowledge, understanding of ourselves and ‘the other’ and through policy.

We describe what we do as social research. This is research done in order to improve and expand on our knowledge of the world by providing decision makers in social policy and intervention projects with the best data possible.

We run primary face-to-face research - both quantitative and qualitative - in 54 countries in Africa and the Middle East. Click here for a list of countries in which we run face-to-face research.

We run analytical research on social media globally through our partnership with Crimson Hexagon, arguably the best social media analysis platform in the world. We work for a variety of clients but are also committed to generating our own projects for public distribution. These are exclusively generated through mining and reporting on our social media data base, which currently holds almost 1 trillion pieces of social media data.
We work for a variety of clients, but are also committed to generating our own data for public distribution – on this website, and through traditional, online and social media.

The Citizen Research Centre is a sister company to <a href="http://vibrand.co.za/">Vibrand Research (www.vibrand.co.za)</a> , a longstanding market research firm with a reputation for intelligent, innovative work. 

</p>
</div>
<div class='medium-2 large-2 columns'>
	<div class='spacing'></div>
	</div>
</div>


<script>
$(function() {
  $('#concerns').highcharts({
    chart: {
      type: 'column'
    },
    title: {
      text: 'Social Media Concerns'
    },
    subtitle: {
      text: 'Source: Crimson Hexagon'
    },
    xAxis: {
      categories: [
        'Conversation Areas'

      ],
      crosshair: true
    },
    yAxis: {
      min: 0,
      title: {
        text: 'Percentage of Conversation'
      }
    },
    tooltip: {
      headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
      pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
        '<td style="padding:0"><b>{point.y:.1f} %</b></td></tr>',
      footerFormat: '</table>',
      shared: false,
      useHTML: true
    },
    plotOptions: {
      column: {
        pointPadding: 0.2,
        borderWidth: 0
      }
    },
    series: [{
      name: 'Education',
      data: [8]

    }, {
      name: 'Threat',
      data: [11]

    },
    {
      name: 'Water',
      data: [13]

    },
    {
      name: 'Poverty/Money',
      data: [10]

    },
    {
      name: 'Addiction',
      data: [18]

    },
     {
      name: 'Fuel (Petrol, Diesel, Gas)',
      data: [18]

    },
     {
      name: 'Electricity',
      data: [3]

    },
     {
      name: 'Communication',
      data: [6]

    },
     {
      name: 'Corruption',
      data: [1]

    },
     {
      name: 'Government',
      data: [2]

    },
     {
      name: 'Employment',
      data: [4]

    },
     {
      name: 'Ebola',
      data: [8]

    },]
  });
});

</script>
<script>
$(function() {
  $('#funders').highcharts({
    chart: {
      type: 'column'
    },
    title: {
      text: 'Public Belief On Who Is Funding Boko Haram'
    },
    subtitle: {
      text: 'Source: Crimson Hexagon'
    },
    xAxis: {
      categories: [
        'Funders'

      ],
      crosshair: true
    },
    yAxis: {
      min: 0,
      title: {
        text: 'Percentage of Conversation'
      }
    },
    tooltip: {
      headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
      pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
        '<td style="padding:0"><b>{point.y:.1f} %</b></td></tr>',
      footerFormat: '</table>',
      shared: false,
      useHTML: true
    },
    plotOptions: {
      column: {
        pointPadding: 0.2,
        borderWidth: 0
      }
    },
    series: [{
      name: 'Wealthy Nigerians',
      data: [8]

    }, {
      name: 'Nigerian Government',
      data: [30]

    },
    {
      name: 'Borno State Leaders (Elrufai)',
      data: [16]

    },
    {
      name: 'Banks and Prisons',
      data: [14]

    },
    {
      name: 'Oil',
      data: [9]

    },
     {
      name: 'Kidnapping',
      data: [7]

    },
     {
      name: 'The West',
      data: [9]

    },
     {
      name: 'Other Terror Groups',
      data: [8]

    }]
  });
});

</script>
<script>
$(function() {
  $('#before_concerns').highcharts({
    chart: {
      type: 'column'
    },
    title: {
      text: 'Social Media Concerns before Boko Haram Threat (July 2010 - December 2013)'
    },
    subtitle: {
      text: 'Source: Crimson Hexagon'
    },
    xAxis: {
      categories: [
        'Conversation Areas'

      ],
      crosshair: true
    },
    yAxis: {
      min: 0,
      title: {
        text: 'Percentage of Conversation'
      }
    },
    tooltip: {
      headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
      pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
        '<td style="padding:0"><b>{point.y:.1f} %</b></td></tr>',
      footerFormat: '</table>',
      shared: false,
      useHTML: true
    },
    plotOptions: {
      column: {
        pointPadding: 0.2,
        borderWidth: 0
      }
    },
    series: [{
      name: 'Education',
      data: [3]

    }, {
      name: 'Threat',
      data: [1]

    },
    {
      name: 'Water',
      data: [20]

    },
    {
      name: 'Poverty/Money',
      data: [13]

    },
    {
      name: 'Addiction',
      data: [25]

    },
     {
      name: 'Fuel (Petrol, Diesel, Gas)',
      data: [20]

    },
     {
      name: 'Electricity',
      data: [3]

    },
     {
      name: 'Communication',
      data: [8]

    },
     {
      name: 'Corruption',
      data: [1]

    },
     {
      name: 'Government',
      data: [1]

    },
     {
      name: 'Employment',
      data: [3]

    },
     {
      name: 'Ebola',
      data: [2]

    },]
  });
});

</script>

<script>
$(function() {
  $('#after_concerns').highcharts({
    chart: {
      type: 'column'
    },
    title: {
      text: 'Social Media Concerns (January 2014 - October 2015)'
    },
    subtitle: {
      text: 'Source: Crimson Hexagon'
    },
    xAxis: {
      categories: [
        'Conversation Areas'

      ],
      crosshair: true
    },
    yAxis: {
      min: 0,
      title: {
        text: 'Percentage of Conversation'
      }
    },
    tooltip: {
      headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
      pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
        '<td style="padding:0"><b>{point.y:.1f} %</b></td></tr>',
      footerFormat: '</table>',
      shared: false,
      useHTML: true
    },
    plotOptions: {
      column: {
        pointPadding: 0.2,
        borderWidth: 0
      }
    },
    series: [{
      name: 'Education',
      data: [13]

    }, {
      name: 'Threat',
      data: [22]

    },
    {
      name: 'Water',
      data: [6]

    },
    {
      name: 'Poverty/Money',
      data: [8]

    },
    {
      name: 'Addiction',
      data: [10]

    },
     {
      name: 'Fuel (Petrol, Diesel, Gas)',
      data: [15]

    },
     {
      name: 'Electricity',
      data: [2]

    },
     {
      name: 'Communication',
      data: [3]

    },
     {
      name: 'Corruption',
      data: [1]

    },
     {
      name: 'Government',
      data: [2]

    },
     {
      name: 'Employment',
      data: [4]

    },
     {
      name: 'Ebola',
      data: [14]

    },]
  });
});

</script>
<script>
$(function() {
  $('#concerns_increase').highcharts({
    chart: {
      type: 'column'
    },
    title: {
      text: 'Change in Conversation Concerns from 2009-2015'
    },
    subtitle: {
      text: 'Source: Crimson Hexagon'
    },
    xAxis: {
      categories: [
        'Conversation Areas'

      ],
      crosshair: true
    },
    yAxis: {
      title: {
        text: 'Percentage Change in Conversation Area'
      }
    },
    tooltip: {
      headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
      pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
        '<td style="padding:0"><b>{point.y:.1f} %</b></td></tr>',
      footerFormat: '</table>',
      shared: false,
      useHTML: true
    },
    plotOptions: {
      column: {
        pointPadding: 0.2,
        borderWidth: 0
      }
    },
    series: [{
      name: 'Education',
      data: [24]

    }, {
      name: 'Threat',
      data: [47]

    },
    {
      name: 'Water',
      data: [-18]

    },
    {
      name: 'Poverty/Money',
      data: [-11]

    },
    {
      name: 'Addiction',
      data: [-23]

    },
     {
      name: 'Fuel (Petrol, Diesel, Gas)',
      data: [-4]

    },
     {
      name: 'Electricity',
      data: [-2]

    },
     {
      name: 'Communication',
      data: [-15]

    },
     {
      name: 'Corruption',
      data: [2]

    },
     {
      name: 'Government',
      data: [2]

    },
     {
      name: 'Employment',
      data: [4]

    },
     {
      name: 'Ebola',
      data: [25]

    },]
  });
});

</script>
<script>
$(function() {
  $('#concerns_increase_14_15').highcharts({
    chart: {
      type: 'column'
    },
    title: {
      text: 'Change in Conversation Concerns (January 2014 - October 2015)'
    },
    subtitle: {
      text: 'Source: Crimson Hexagon'
    },
    xAxis: {
      categories: [
        'Conversation Areas'

      ],
      crosshair: true
    },
    yAxis: {
      title: {
        text: 'Percentage Change in Conversation Area'
      }
    },
    tooltip: {
      headerFormat: '<span style="font-size:10px">{point.key}</span><table>',
      pointFormat: '<tr><td style="color:{series.color};padding:0">{series.name}: </td>' +
        '<td style="padding:0"><b>{point.y:.1f} %</b></td></tr>',
      footerFormat: '</table>',
      shared: false,
      useHTML: true
    },
    plotOptions: {
      column: {
        pointPadding: 0.2,
        borderWidth: 0
      }
    },
    series: [{
      name: 'Education',
      data: [11]

    }, {
      name: 'Threat',
      data: [31]

    },
    {
      name: 'Water',
      data: [-11]

    },
    {
      name: 'Poverty/Money',
      data: [-6]

    },
    {
      name: 'Addiction',
      data: [-13]

    },
     {
      name: 'Fuel (Petrol, Diesel, Gas)',
      data: [-10]

    },
     {
      name: 'Electricity',
      data: [-2]

    },
     {
      name: 'Communication',
      data: [-5]

    },
     {
      name: 'Corruption',
      data: [0]

    },
     {
      name: 'Government',
      data: [5]

    },
     {
      name: 'Employment',
      data: [-3]

    },
     {
      name: 'Ebola',
      data: [2]

    },]
  });
});

</script>