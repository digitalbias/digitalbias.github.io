---
layout: post
title:  "Activity Monitors"
date:   2013-10-05 23:31
categories: health
---
I did an analysis of the different health monitors out there before I ended up buying a [Fitbit One][one]. Here's the table showing the various features. Eventually I was narrowing it down to a couple of pieces of tech, so the table isn't complete. Still, it may be useful for somebody. It was done in multimarkdown, which is not completly supported by Redcarpet (or at least the version used by Jekyll).

## Fitness Trackers

This is designed to be a review of the different features provided by the various activity trackers out there. I am creating this so I have a good senses of what is avaliable and can make an informed decision. I get the feeling no matter what I choose, I'm going to be making some compromises.

| Feature                | [Fitbit Flex][flex] | [Fitbit One][one] | [Fitbit Zip][zip] | [Jawbone Up][up] | [Lark Life][life] | [Bias][bias] | [Pebble Watch][watch][^watchapi] | [Pebble][pebble] |  Pedometer |
|------------------------|---------------------|-------------------|-------------------|------------------|-------------------|--------------|----------------------------------|------------------|------------|
| Price                  |         $99         |        $99        |        $59        |       $130       |        $150       |     $200     |              $150                |                  |    $5      |
| Track Steps            |          Y          |         Y         |         Y         |         Y        |         Y         |       Y      |                                  |                  |     Y      |
| Track distance         |          Y          |         Y         |         Y         |                  |         Y         |              |                                  |                  |     N      |
| Track calories         |          Y          |         Y         |         Y         |                  |         Y         |              |                                  |                  |     N      |
| Altimeter              |          N          |         Y         |         N         |         N        |                   |              |                                  |                  |     N      |
| Track active minutes   |          Y          |         Y         |                   |                  |         Y         |       Y      |                                  |                  |     N      |
| Monitor sleep          |          Y          |         Y         |         N         |         Y        |                   |       Y      |                                  |                  |     N      |
| Goal progress display  |          Y          |         N         |         N         |         N        |                   |       Y      |                                  |                  |     N      |
| Wireless sync          |          Y          |         Y         |         Y         |         N        |                   |              |                                  |                  |     N      |
| Bluetooth sync         |          Y          |         Y         |         Y         |         N        |                   |              |                                  |                  |     N      |
| Rechargeable battery   |          Y          |         Y         |         Y         |         Y        |         Y         |       Y      |                                  |                  |     N      |
| Sync with MyFitnessPal |          Y          |         Y         |         Y         |         Y        |                   |              |                                  |                  |     N      |
| Can export data        |       [^data]       |      [^data]      |      [^data]      |         Y        |                   |       N      |                                  |                  |     N      |
| Software/Data vis      |          Y          |         Y         |         Y         |         Y        |                   |              |                                  |                  |     N      |
| Inactivity Alarm       |      [^script]      |     [^script]     |     [^script]     |         Y        |         Y         |              |                                  |                  |     N      |
| Heart monitor          |          N          |         N         |         N         |         N        |         N         |       Y      |                                  |                  |     N      |


[flex]: http://www.fitbit.com/flex
[one]: http://www.fitbit.com/one
[zip]: http://www.fitbit.com/zip
[up]: https://jawbone.com/up
[life]: http://lark.com/products/larklife/experience
[bias]: http://www.mybasis.com/
[watch]: http://getpebble.com/
[pebble]: http://www.fitlinxx.net/pebble-activity-monitor.htm

[^data]: Requires premium membership on fitbit.com. If you are a developer, you can get access to the data via a free API.

[^watchapi]: The Pebble Watch is an e-ink watch and has the capability to do this activity monitoring, but there are no apps that provide this functionality yet.

[^script]: Using their REST API it is possible to write something to do this. [Fitbit API](https://wiki.fitbit.com/display/API/Fitbit+API)
