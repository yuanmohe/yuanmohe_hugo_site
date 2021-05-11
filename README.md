## Setup locally

### Install R blogdown package and Hugo

```r
> install.packages('blogdown')
> blogdown::install_hugo()
```

### Open project with RStudio

In RStudio, open **academic.Rproj**.

Go to Tools->Project Options->Build Tools:

Select **Website**

Uncheck **Preview site after building**

### Build and run project

Goto build panel, select **Build Website**

Then goto Tools->Addins->blogdown Serve Site

Then website should now be running at [localhost:4321](localhost:4321)