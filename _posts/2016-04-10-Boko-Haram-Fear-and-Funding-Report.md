---
layout: public_reports
title: Boko Haram Fear and Funding Report
subtitle: Tracking Social Media Voices
date: "2014-05-05 20:37:53 +0800"
author: The Citizen Research Centre
excerpt: "A report showing social media data on the Fear and Funding of Boko Haram from 2009 to 2015"
images: "images/blog-images/rise.jpg"
categories: public_research
published: true
---

We used Crimson Hexagon to answer three key questions of the social media conversation in Nigeria regarding Boko Haram:
- What issues of social concern are Nigerians talking about on social media?
- How has the level of fear risen over the years?
- How do people that are active on social media in Nigeria think Boko Haram is funded?

Our research timelines were January 2009 to November 2015

### Social Concerns 
We identified areas of socio-economic concern to Nigerians , and then identified and analysed 1,060,647,786 relevant social media posts coming out of Nigeria between January 2009 and November 2015.
We found that the breakdown of concerns expressed on social media over this time frame was as follows:

<div id="socialconcern" style="min-width: 310px; height: 400px; margin: 0 auto"></div>

### The Rise of Fear
In looking at ‘Threat’ more closely, we found dramatic change over time. Threat here refers to threat to life or property – largely as a result of (but not limited to) Boko Haram activity.
In the years preceding Bok Haram’s increased level of activity (July 2010 to December 2013), we found Threat levels to be low to the point of insignificance. Throughout the period below, Threat comprised less than 1% of the total conversation on social media in Nigeria:

Once Boko Haram became more active, this level increased dramatically. The graph below shows how Threat, between  January 2014 and October 2015, grew to comprise fully 22% of the total Nigerian social media conversation on topics of socio-economic/ social interest. This is by far the greatest single contributor to the national conversation around socio economic issues in this timeframe.  Of interest too, is how education as a concern grew from 8 to 13% of the conversation over this time frame.

Social Cohesion Research employs a mixture of technological excellence and years of research experience to deliver some of the most innovative and informative research available.

### Funding of Boko Haram
Turning our attention to Funding of Boko Haram, we identified 47 205 English posts emanating from Nigeria relating to the funding of Boko Haram over the time frame.  In social media data terms this is a small data set, but still represents, of course, 47 205 individual pieces of  data. In alanalsyi9ng this data set we found the following – given that ‘wealthy Nigerians’ inevitably refers to men of power, fully 54% of all Nigerian social media opinion points the finger at various levels of government or official power.

In order to understand why this opinion was so overwhelmingly held, we conducted a retrospective analysis of relevant social media conversation from 2011 till 2015.
The results showed persistent reports – ranging from rumour to arrests – of government or official involvement in Boko Haram funding.  We show below the timelines for 2011,2012,2013,2014 and 2015:

### Funding of Boko Haram: 2011
<img src="{{site.url}}/images/blog-images/funding2011.jpg" alt="Funding of Boko Haram: 2011">

### Funding of Boko Haram: 2012
<img src="{{site.url}}/images/blog-images/funding2012.jpg" alt="Funding of Boko Haram: 2012">

### Funding of Boko Haram: 2013
<img src="{{site.url}}/images/blog-images/funding2013.jpg" alt="Funding of Boko Haram: 2013">

### Funding of Boko Haram: 2014 (note the rise in volume)
<img src="{{site.url}}/images/blog-images/funding2014.jpg" alt="Funding of Boko Haram: 2014">

### Funding of Boko Haram: 2015 (note the rise in volume)
<img src="{{site.url}}/images/blog-images/funding2015.jpg" alt="Funding of Boko Haram: 2015">

<script>
$(function () {
    $('#socialconcern').highcharts({
        chart: {
            type: 'column'
        },
        title: {
            text: 'Concerns Expressed on Social Media '
        },
        subtitle: {
            text: '2009 - 2015'
        },
        xAxis: {
            categories: [
                'Areas of Concern'
            ],
            crosshair: true
        },
        yAxis: {
            min: 0,
            title: {
                text: 'Total Conversation (%)'
            }
        },
        tooltip: {
            valueSuffix: ' %'
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

        }, {
            name: 'Water',
            data: [13]

        }, {
            name: 'Poverty / Money',
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

        }]
    });
});
</script>