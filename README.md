# wta
What The Amazon?  Command line scraper for AWS service status page.

Install this as a gem, and it will pull in the `wta` script.

```
$ gem install wta
$ wta -help
Usage: wta [options]
    -r, --region=val                 Select region NA, SA, EU, AP. Defaults to NA
    -s, --summary                    Add a summary header for services
    -a, --all                        Include services that are operating normally in the listing
```

Example output, taken from the super fun time Dynamo outage on 20 Sep 2015 when at one point, 10 Amazon Web Services were red-lined:


![screenshot](doc/screenshots/failshot.png)