# sosc

I added a simple feature to [christoph-heinrich/sosc](https://github.com/christoph-heinrich/sosc). In idle state, it shows a quote about writing and art.
You can copy the text with `script-message copy-quote`, and also add your
favorite quotes to `script-opts/modernx-and-quotes.txt` file.

Below is README from original repo.

> A stripped down version of [osc.lua](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua) to supplement OSC replacements like [uosc](https://github.com/tomasklaen/uosc) with the idle screen and messages provided by the original OSC.
>
> It listens to all the script messages and sets shared-script-properties just like [osc.lua](https://github.com/mpv-player/mpv/blob/master/player/lua/osc.lua) does, except for the `osc-visibility` message and the `osc-visibility` and`osc-margins` shared-script-properties because those don't make sense without actually displaying an interface.
>
> Your configuration for the original OSC will be used automatically.

## Installation

1. Save the `osc.lua` into your [`scripts` directory](https://mpv.io/manual/stable/#script-location)
1. Save the `osc-quotes.txt` into your `script-opts` directory
1. Make sure you have `osc=no` in your [mpv.conf](https://mpv.io/manual/stable/#configuration-files).
