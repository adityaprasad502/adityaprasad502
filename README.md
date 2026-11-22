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
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Code%20Time-1%2C987%20hrs-f2c35c?logo=wakatime&logoColor=white" alt="Code Time"></a>
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Spotify-5%2C284%20hrs-1db954?logo=spotify&logoColor=white" alt="Spotify"></a>
</p>

```
# tip: scroll → for full view
• ▶ fastfetch -c adityaprasad502

                  -`                     pu94x@xoarch
                 .o+`                    ────────────
                `ooo/                    OS              Arch Linux x86_64
               `+oooo:                   Host            xoarch (150h 00m / 30D)
              `+oooooo:                  Terminal        kitty (fish)
              -+oooooo+:                 Editors         Antigravity (134h 37m · 89.7%)
            `/:-:++oooo+:                                OpenCode (7h 31m · 5.0%)
           `/++++/+++++++:                               VSCodium (4h 33m · 3.0%)
          `/++++++++++++++:              WM              Hyprland (Wayland) [riced]
         `/+++ooooooooooooo/`            Uptime          Since 2020 (tracked since 21st 2022)
        ./ooosssso++osssssso+`           ────────────────────────────────────────────────────────────────
       .oossssso-````/ossssss+`          30D Runtime
      -osssssso.      :ssssssso.           QML                 45h 51m  [########################]  30.5%
     :osssssss/        osssso+++.          AgentOps*           24h 41m  [#############-----------]  16.4%
    /ossssssss/        +ssssooo/-          Markdown            17h 37m  [#########---------------]  11.7%
  `/ossssso+/:-        -:/+osssso+-        Python              14h 13m  [#######-----------------]   9.5%
 `+sso+:-`                 `.-/+oso:       Text                 7h 19m  [####--------------------]   4.9%
`++:.                           `-/+/    ────────────────────────────────────────────────────────────────
.`                                 `/    AI Orchestration · 30D
                                           Gemini          57.1k lines  [########################]  90.7%
                                           DeepSeek         4.0k lines  [##----------------------]   6.3%
                                           Sonnet           1.1k lines  [------------------------]   1.8%
                                           Total           63.0k lines  ·  total generated
                                           Tokens          201.10M      ·  182.91M input / 18.19M output
                                         ────────────────────────────────────────────────────────────────
                                         All-Time
                                           Commits              6,035+  ·  76 (30D) · 52.6% night commits
                                           Repos              30 repos  ·  6 pub   · 24 priv   · 88.5 MiB
                                           LeetCode          91 solved  ·  77 Easy · 12 Medium ·   2 Hard
                                           Stack Overflow      471 rep  ·  1 Gold  · 5 Silver  · 8 Bronze
                                           Spotify           5,284 hrs  ·  90,930 streams
                                         ────────────────────────────────────────────────────────────────
                                           *scripting, device tuning, ricing & agent tasks
```

---

> *"Truth can only be found in one place: the code."*  — Robert C. Martin

---

<p align="center">
  <code>sync: 2026-11-22 06:55 IST</code> &nbsp;·&nbsp; <code>next: ~06:55 IST</code><br>
  <sub>Metrics reflect a fraction of total activity across tracked environments.<br>
  Copyright © 2020 - 2026 | Aditya Prasad S</sub><br><br>
  <a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://da.gd/track0" width="94"></a>
</p>

<!--END_SECTION:waka-->
