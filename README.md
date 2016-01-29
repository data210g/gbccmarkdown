A package of R markdown templates.

Currently, there's one `gbccmarkdown::default` :-)

When you use RStudio to create a new R Markdown document, select "From Template" and
choose "GBCC Default Template". 

Alternately, you could just start a blank R markdown document and replace the YAML with:

    ---
    title: "Analysis Title"
    author: "GBCC Author"
    date: "2016-01-29"
    course: "DATA 210G Elements of Data Science"
    output: gbccmarkdown::default
    ---
    
There is currently only the `gbccmarkdown::default` template that uses [Skeleton](http://getskeleton.com) instead of Bootstrap, auto-places a GBCC logo at the top and formats the author & date metdata a bit differently.
