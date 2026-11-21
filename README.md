<div align="center">
  <a href="https://a.devh.in" rel="nofollow">
    <img src="https://media4.giphy.com/media/rar203X81bEN2bVdYJ/giphy.gif" height="194" width="194" alt="">
  </a>

  <br>

  <h1>
    <a href="https://a.devh.in" rel="nofollow"><img src="https://media.giphy.com/media/Sh1iCtJZEdx4PFYy4q/giphy-downsized.gif" height="39" width="38" alt="" align="middle"></a>
    Howdy, &lt;Peepers /&gt;
    <a href="https://a.devh.in" rel="nofollow"><img src="https://media.giphy.com/media/cYU6YcPE5YlJxh6otp/giphy.gif" height="40" width="40" alt="" align="middle"></a>
  </h1>
</div>

```kt 
// try this on a Kotlin IDE, IntelliJ IDEA? 
// (avoid online compiler && notebooks) 
fun main() {
    val l = listOf(
        65, 68, 73, 84, 89, 65, 32, 
        80, 82, 65, 83, 65, 68, 83
    )
    val pu94x = sequence {
        while (true) {
            yieldAll(l.indices)
            yieldAll(l.lastIndex - 1 downTo 1)
        }
    }
    pu94x.forEach { i ->
        println("xo | ".repeat(i) + l[i].toChar())
        Thread.sleep(94)
    }
}
``` 


<!--START_SECTION:waka-->

<p align="center">
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/OS-Arch%20Linux-1793d1?logo=archlinux&logoColor=white" alt="Arch Linux"></a>
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Code%20Time-1%2C977%20hrs-f2c35c?logo=wakatime&logoColor=white" alt="Code Time"></a>
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Spotify-5%2C276%20hrs-1db954?logo=spotify&logoColor=white" alt="Spotify"></a>
</p>

```
# tip: swipe on mobile for full view
• ▶ fastfetch -c adityaprasad502

                  -`                     pu94x@xoarch
                 .o+`                    ────────────
                `ooo/                    OS              Arch Linux x86_64
               `+oooo:                   Host            xoarch (140h 25m / 30D)
              `+oooooo:                  Terminal        kitty (fish)
              -+oooooo+:                 Editors         Antigravity (127h 32m · 90.7%)
            `/:-:++oooo+:                                OpenCode (6h 04m · 4.3%)
           `/++++/+++++++:                               VSCodium (4h 33m · 3.2%)
          `/++++++++++++++:              WM              Hyprland (Wayland) [riced]
         `/+++ooooooooooooo/`            Uptime          Since 2020 (tracked since 21st 2022)
        ./ooosssso++osssssso+`           ────────────────────────────────────────────────────────────────
       .oossssso-````/ossssss+`          30D Runtime
      -osssssso.      :ssssssso.           QML                 45h 51m  [########################]  32.6%
     :osssssss/        osssso+++.          AgentOps*           19h 05m  [##########--------------]  13.6%
    /ossssssss/        +ssssooo/-          Markdown            17h 29m  [#########---------------]  12.4%
  `/ossssso+/:-        -:/+osssso+-        Python              14h 11m  [#######-----------------]  10.1%
 `+sso+:-`                 `.-/+oso:       Text                 7h 19m  [####--------------------]   5.2%
`++:.                           `-/+/    ────────────────────────────────────────────────────────────────
.`                                 `/    AI Orchestration · 30D
                                           Gemini          54.5k lines  [########################]  91.5%
                                           DeepSeek         4.0k lines  [##----------------------]   6.7%
                                           Sonnet            861 lines  [------------------------]   1.4%
                                           Total           59.6k lines  ·  total generated
                                           Tokens          191.76M      ·  174.11M input / 17.64M output
                                         ────────────────────────────────────────────────────────────────
                                         All-Time
                                           Commits              6,038+  ·  79 (30D) · 49.4% night commits
                                           Repos              31 repos  ·  7 pub   · 24 priv   · 88.5 MiB
                                           LeetCode          91 solved  ·  77 Easy · 12 Medium ·   2 Hard
                                           Stack Overflow      471 rep  ·  1 Gold  · 5 Silver  · 8 Bronze
                                           Spotify           5,276 hrs  ·  90,804 streams
                                         ────────────────────────────────────────────────────────────────
                                           *scripting, device tuning, ricing & agent tasks
```

---

> *"I think the best way to supervise is by personal example and by frequent code reviews."*  — Charles Simonyi

---

<p align="center">
  <code>sync: 2026-11-21 07:59 IST</code> &nbsp;·&nbsp; <code>next: ~07:59 IST</code><br>
  <sub>Metrics reflect a fraction of total activity across tracked environments.<br>
  Copyright © 2020 - 2026 | Aditya Prasad S</sub><br><br>
  <a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://da.gd/track0" width="94"></a>
</p>

<!--END_SECTION:waka-->
