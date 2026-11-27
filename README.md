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
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Code%20Time-2%2C044%20hrs-f2c35c?logo=wakatime&logoColor=white" alt="Code Time"></a>
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Spotify-5%2C320%20hrs-1db954?logo=spotify&logoColor=white" alt="Spotify"></a>
</p>

```
# tip: scroll → for full view
• ▶ fastfetch -c adityaprasad502

                  -`                     pu94x@xoarch
                 .o+`                    ────────────
                `ooo/                    OS              Arch Linux x86_64
               `+oooo:                   Host            xoarch (209h 01m / 30D)
              `+oooooo:                  Terminal        kitty (fish)
              -+oooooo+:                 Editors         Antigravity (162h 55m · 78.0%)
            `/:-:++oooo+:                                Claude Code (24h 56m · 11.9%)
           `/++++/+++++++:                               OpenCode (12h 44m · 6.1%)
          `/++++++++++++++:              WM              Hyprland (Wayland) [riced]
         `/+++ooooooooooooo/`            Uptime          Since 2020 (tracked since 21st 2022)
        ./ooosssso++osssssso+`           ────────────────────────────────────────────────────────────────
       .oossssso-````/ossssss+`          30D Runtime
      -osssssso.      :ssssssso.           QML                 63h 34m  [########################]  30.4%
     :osssssss/        osssso+++.          AgentOps*           39h 25m  [###############---------]  18.9%
    /ossssssss/        +ssssooo/-          Markdown            19h 50m  [#######-----------------]   9.5%
  `/ossssso+/:-        -:/+osssso+-        Python              18h 00m  [#######-----------------]   8.6%
 `+sso+:-`                 `.-/+oso:       Text                 7h 20m  [###---------------------]   3.5%
`++:.                           `-/+/    ────────────────────────────────────────────────────────────────
.`                                 `/    AI Orchestration · 30D
                                           Gemini          64.8k lines  [########################]  84.1%
                                           DeepSeek         6.4k lines  [##----------------------]   8.3%
                                           Tencent Hy       4.0k lines  [#-----------------------]   5.2%
                                           Total           77.1k lines  ·  total generated
                                           Tokens          243.00M      ·  219.02M input / 23.99M output
                                         ────────────────────────────────────────────────────────────────
                                         All-Time
                                           Commits              6,117+  ·  158 (30D) · 50.0% night commits
                                           Repos              31 repos  ·  6 pub   · 25 priv   · 97.4 MiB
                                           LeetCode          91 solved  ·  77 Easy · 12 Medium ·   2 Hard
                                           Stack Overflow      471 rep  ·  1 Gold  · 5 Silver  · 8 Bronze
                                           Spotify           5,320 hrs  ·  91,516 streams
                                         ────────────────────────────────────────────────────────────────
                                           *scripting, device tuning, ricing & agent tasks
```

---

> *"The act of describing a program in unambiguous detail and the act of programming are one and the same."*  — Kevlin Henney

---

<p align="center">
  <code>sync: 2026-11-27 09:10 IST</code> &nbsp;·&nbsp; <code>next: ~09:10 IST</code><br>
  <sub>Metrics reflect a fraction of total activity across tracked environments.<br>
  Copyright © 2020 - 2026 | Aditya Prasad S</sub><br><br>
  <a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://da.gd/track0" width="94"></a>
</p>

<!--END_SECTION:waka-->
