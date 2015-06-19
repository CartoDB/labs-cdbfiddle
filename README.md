# cdbfiddle
Template that takes a viz.json URL and displays a map, SQL pane, and CartoCSS pane for the *first* cartoDB layer

Useful for providing examples on blog posts where the user can copy and paste the code to try themselves elsewhere

##How to use:

Create a named map with a single layer.  Use the editor to format your SQL, CartoCSS, and map view.  Get the viz.json URL from the *Pubish* button.  

Go to: `http://cartodb.github.io/labs-cdbfiddle/#{yourviz.jsonURL}`

In the javascript console you will see a nice iframe snippet that you can copy and paste in your blog.

For example, 
`http://cartodb.github.io/labs-cdbfiddle/#https://team.cartodb.com/u/chriswhong/api/v2_1/viz/589a8ffe-15d7-11e5-8f5b-0e853d047bba/viz.json`
looks like this:

![Screenshot](https://www.evernote.com/shard/s288/sh/b03f02f8-5ce8-4266-b6e8-8a117eaef3a7/21090bef4a9b7b0d/res/6abdf767-ea6f-455b-b6b6-bbe46260632a/skitch.png?resizeSmall&width=832)
