# auto-switch-miners

For Linux (and should work with windows, though not tested)

This program is intended to be used as a auto switching utility to decide and chose the right miner based on 24h profitability report as suggested by whattomine.

Dependencies & pre-requisites:
1) python3 (if you are mining on Ubuntu 16.04 or above, you likely have python3 pre-installed)
2) .sh files to start desired miners (this program is a miner switching utility that uses your existing miners that are configured to be started using customized .sh scripts)

By allowing users to specify and configure the coin-algorithm pair, or algorithms to be matched to your own custom scripts, it provides flexibility in choosing any specific miner you desire for a specific algorithm.

All the configurations for this program utility are done in the input.cfg file -

Section A] provides you to customize and mimic input parameters to what you typically input on the whattomine.com page.

Section B] provides users to specify their choice of miners to be used based on 'coin-algorithm'=minerscript or 'algorithm'=minerscript format