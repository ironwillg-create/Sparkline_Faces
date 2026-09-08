# Sparkline Faces

> **This is a fork.** Upstream is
> [thejambi/Sparkline_Faces](https://github.com/thejambi/Sparkline_Faces) (MIT),
> kept as the `upstream` remote so his later work can be pulled in with
> `git fetch upstream && git merge upstream/master`. The only change here is the
> second time zone in Emberline's header - see
> [Emberline/README.md](Emberline/README.md#the-second-time-zone). Built on
> ROCK-AI at `C:/PersonalCode/Sparkline_Faces`; the Pebble SDK itself lives in
> Proxmox LXC 118, so builds go through the pebble-dev helper rather than
> running on Windows.

Watchfaces built around one idea: the last hour of your movement, drawn a
column a minute. It began as the compact info band from
[Solfarer](../Solfarer) — clock, steps, distance, heart rate, date,
temperature and a 10px activity strip — and grew from there.

**Emery only** while an idea is being tried. Other platforms get a layout pass
once something is worth publishing.

| Face | What it is |
| --- | --- |
| [Emberline](Emberline) | Sky over ground. A stacked clock, and the hour as terrain along the bottom edge — which becomes last night's sleep before you get up |
| [Sparkline](Sparkline) | The Solfarer band given all 228 rows, with a tall chart along the bottom |
| [TeaScene](TeaScene) | The band kept compact, with a Chinese gongfu tea table filling the rest |
