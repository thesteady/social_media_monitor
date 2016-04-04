Social Media Monitor
====================

An app to play with event streams, socket.io, and nio.js.

This dashboard displays realtime data about social media activity (# tweets/sec, # instagram posts/sec) and displays that activity.

Questions someone using this might ask:
- is the twitter activity "normal", "high", or "low"?
- is the instagram activity "normal", "high", or "low"?
- which feed is more active?

## Getting Started

Install the bower components:
`npm install bower -g` (if you haven't already)
`bower install`

Open `index.html` in the browser. I like `http-server` to serve it up on localhost:8080.

See data.

## Notes:

Twitter assets and colors from: https://about.twitter.com/company/brand-assets
Instagram assets and colors from: https://www.instagram-brand.com/

## Questions
- Why is Instragram flatlined at 0?
- Don't seem to be getting any cached data from the socket?

## Things I'd Like To Update

- update yAxis / yScale to update dynamically if the data changes (for reference: http://bl.ocks.org/phoebebright/3098488)
- add a style framework like materialize or bootstrap to make things pretty
- bigger chart to compare the two?
- add a color code to show increase/decrease over previous datapoint (or a trend over x points?)
- use the other stream to show counts over time at a higher level?
- sounds ?
- bubbles that transition bigger/smaller with the data? not very informative, but could look neat.