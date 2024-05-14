# Sundial: a dashboard for gnomonic timesetting

Sundial is a flexdashboard built around the 'suntools' R package and is stored as an Rstudio Project. It is designed to produce a series of start and finish times in relation to sunrise/sunset for autonomous recorders. It can also use baselines of civil dawn/civil dusk or nautical dawn/ nautical dusk, if prefered. It is designed to work for all time zones and should be accurate within a 1 minute for tropical and temperate latitudes. 

## Flexdashboard and leaflet comptability issue
Recent versions of flexdashboard package do not operate smoothly with the leaflet package. For this reason an earlier version of flexdashboard (version = "0.5.2") is required. The correct version of flexdashboard can be installed using the following code:

```
library(remotes)
install_version("flexdashboard", version = "0.5.2", repos = "http://cran.us.r-project.org")
```

