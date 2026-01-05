# ⚠️ ARCHIVED - This repository is no longer maintained

**This repository has been archived and is no longer actively maintained.**

This project was last updated on 2016-12-13 and is preserved for historical reference only.

- 🔒 **Read-only**: No new issues, pull requests, or changes will be accepted
- 📦 **No support**: This code is provided as-is with no support or updates
- 🔍 **For reference only**: You may fork this repository if you wish to continue development

For current CARTO projects and actively maintained repositories, please visit: https://github.com/CartoDB

---

# cdbfiddle
Template that takes a viz.json URL and displays a read-only map, SQL pane, and CartoCSS pane for the cartoDB layers

Useful for providing examples on blog posts where the user can copy and paste the code to try themselves elsewhere

##How to use:

Create a map in the CartoDB Editor using *public* datasets.  Format your SQL, CartoCSS, and map view.  Get the viz.json URL from the *Pubish* button.  

Go to: `http://cartodb.github.io/labs-cdbfiddle/#{yourviz.jsonURL}`

In the javascript console you will see a nice iframe snippet that you can copy and paste in your blog.

For example, 
`http://cartodb.github.io/labs-cdbfiddle/#https://team.cartodb.com/u/chriswhong/api/v2/viz/b047457a-8e2d-11e5-87da-0e5db1731f59/viz.json`
looks like this:

![screenshot](https://cloud.githubusercontent.com/assets/1833820/11279341/ef928b78-8ebd-11e5-9081-f52c0ed46e03.png)
