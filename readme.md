# Google Maps Practice

This is my practice project

- Work with Google Maps Javascript API in React

- Fecth data from the remote json file

- Responsive layout

- React Router for navigation

React library

https://react-google-maps-api-docs.netlify.app/#polyline

Link to TRF website

## Next

1. Fetch() file

2. Use Object to clean up the code

Trail visibility

Just add text to Info display

Perhaps before element for each trail

3. UI White shadow for nav

Trail not clickable

- Change page title

- Set max / min zoom

## Fix

map() instead of for()

Check Marker Icons

`TypeError: can't access property "maps", window.google is undefined`

## React Router

Set up React Router

Another page

Get images track profile from official site

Image from public or source?

## Split into components

InfoBox with props

Polyline

That's the point! One component, different props

## Here's the plan

- Start with mostly clean file

- fetch json

1. click button  

2. update selectedTrail state

3. if (selected trail) map through to output Info

4. the same with Polyline

Just map from 0 to 1 if (selected trail)

<!-- 
    <Polyline 
        point={fetchedTrailPoints[i]} 
        position={position} (panTo) 
        style / colour
    > 
-->