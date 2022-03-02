# Event schedule and registration

## Summary

Simple card designed to show a list of upcoming organisation Yammer live events.

The Data JSON option has been leveraged to enable users without advanced knowledge of JSON to easily add event items to the card. 

Users can simply update the data JSON to change the events listed and easily add more.

![picture of the extension in action](assets/card.png)

## Compatibility

![Adaptive Card Version](https://img.shields.io/badge/Adaptive%20Card%20Version-1.3-green.svg)


## Designer

<p>
    <a href="https://adaptivecards.io/designer/index.html?card=https://raw.githubusercontent.com/alexc-MSFT/viva-connections-cards/main/samples/yammer-liveevents/liveevents-qv-json">
        <img src="https://raw.githubusercontent.com/pnp/AdaptiveCards-Templates/main/assets/btn-open-in-designer.png" alt="Open in Adaptive Card Designer" />
    </a>
</p>

## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

## Minimal Path to Awesome

This design was created for the Viva Connections dashboard and is designed to be used with a Card Designer card.

![picture of the card in action](assets/dashboard-card.png)

Steps to configure this card with *Card designer* as follows:

- Add **Card designer** to the Viva Connections Dashboard
- **Template Type** - Description
- **Card size** - Large
- **Title** - *Upcoming Live Events*
- **Icon** - Icon with the preferred selection
- **Heading** - *Upcoming Live Events*
- **Description** - See all of our upcoming live events. 
- **Card action** - Show the quick view
- **Primary Button** - On
- **Primary Button Title** - *View Events*
- **Primary Button Action** - Show the quick view
- **Secondary Button** - Off
- **Template JSON** - Paste in the content of the *liveevents-qv-json* file
- **Data JSON** - Paste in the content of the *liveevents-data-json* file
