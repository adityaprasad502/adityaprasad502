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
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Code%20Time-1%2C949%20hrs-f2c35c?logo=wakatime&logoColor=white" alt="Code Time"></a>
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Spotify-5%2C254%20hrs-1db954?logo=spotify&logoColor=white" alt="Spotify"></a>
</p>

```
# tip: swipe on mobile for full view
• ▶ fastfetch -c adityaprasad502

                  -`                     pu94x@xoarch
                 .o+`                    ────────────
                `ooo/                    OS              Arch Linux x86_64
               `+oooo:                   Host            xoarch (124h 54m / 30D)
              `+oooooo:                  Terminal        kitty (fish)
              -+oooooo+:                 Editors         Antigravity (115h 49m · 92.6%)
            `/:-:++oooo+:                                OpenCode (5h 00m · 4.0%)
           `/++++/+++++++:                               VS Code (3h 13m · 2.6%)
          `/++++++++++++++:              WM              Hyprland (Wayland) [riced]
         `/+++ooooooooooooo/`            Uptime          Since 2020 (tracked since 21st 2022)
        ./ooosssso++osssssso+`           ────────────────────────────────────────────────────────────────
       .oossssso-````/ossssss+`          30D Runtime
      -osssssso.      :ssssssso.           QML                 45h 51m  [########################]  36.7%
     :osssssss/        osssso+++.          Markdown            15h 53m  [########----------------]  12.7%
    /ossssssss/        +ssssooo/-          AgentOps*           15h 32m  [########----------------]  12.4%
  `/ossssso+/:-        -:/+osssso+-        Python              12h 05m  [######------------------]   9.7%
 `+sso+:-`                 `.-/+oso:       Text                 6h 46m  [####--------------------]   5.4%
`++:.                           `-/+/    ────────────────────────────────────────────────────────────────
.`                                 `/    AI Orchestration · 30D
                                           Gemini          53.4k lines  [########################]  92.4%
                                           DeepSeek         4.0k lines  [##----------------------]   6.9%
                                           Sonnet            304 lines  [------------------------]   0.5%
                                           Total           57.8k lines  ·  total generated
                                           Tokens          173.46M      ·  156.67M input / 16.79M output
                                         ────────────────────────────────────────────────────────────────
                                         All-Time
                                           Commits              6,031+  ·  72 (30D) · 48.6% night commits
                                           Repos              31 repos  ·  8 pub   · 23 priv   · 88.4 MiB
                                           LeetCode          91 solved  ·  77 Easy · 12 Medium ·   2 Hard
                                           Stack Overflow      471 rep  ·  1 Gold  · 5 Silver  · 8 Bronze
                                           Spotify           5,254 hrs  ·  90,468 streams
                                         ────────────────────────────────────────────────────────────────
                                           *scripting, device tuning, ricing & agent tasks
```

---

> *"If we’d asked the customers what they wanted, they would have said “faster horses”."*  — Henry Ford

---

<p align="center">
  <code>sync: 2026-11-17 09:29 IST</code> &nbsp;·&nbsp; <code>next: ~09:29 IST</code><br>
  <sub>Metrics reflect a fraction of total activity across tracked environments.<br>
  Copyright © 2020 - 2026 | Aditya Prasad S</sub><br><br>
  <a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://da.gd/track0" width="94"></a>
</p>

<!--END_SECTION:waka-->
