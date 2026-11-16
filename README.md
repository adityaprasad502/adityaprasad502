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
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Code%20Time-1%2C946%20hrs-f2c35c?logo=wakatime&logoColor=white" alt="Code Time"></a>
  <a href="https://a.devh.in" rel="nofollow"><img src="https://img.shields.io/badge/Spotify-5%2C252%20hrs-1db954?logo=spotify&logoColor=white" alt="Spotify"></a>
</p>

```
                  -`                     adityaprasad502@xoarch
                 .o+`                    ──────────────────────
                `ooo/                    OS              Arch Linux x86_64
               `+oooo:                   Host            xoarch (118h 20m / 30D)
              `+oooooo:                  Terminal        kitty (fish)
              -+oooooo+:                 Editors         Antigravity (109h 37m · 92.5%)
            `/:-:++oooo+:                                OpenCode (5h 00m · 4.2%)
           `/++++/+++++++:                               VS Code (2h 40m · 2.3%)
          `/++++++++++++++:              WM              Hyprland (Wayland) [riced]
         `/+++ooooooooooooo/`            Uptime          Since 2020 (tracked since 21st 2022)
        ./ooosssso++osssssso+`           ────────────────────────────────────────────────────────────────
       .oossssso-````/ossssss+`          30D Runtime
      -osssssso.      :ssssssso.           QML                 45h 51m  [########################]  38.7%
     :osssssss/        osssso+++.          AgentOps*           14h 18m  [#######-----------------]  12.1%
    /ossssssss/        +ssssooo/-          Markdown            11h 48m  [######------------------]  10.0%
  `/ossssso+/:-        -:/+osssso+-        Python              10h 42m  [######------------------]   9.0%
 `+sso+:-`                 `.-/+oso:       Text                 6h 46m  [####--------------------]   5.7%
`++:.                           `-/+/    ────────────────────────────────────────────────────────────────
.`                                 `/    AI Orchestration · 30D
                                           Gemini          51.2k lines  [########################]  92.3%
                                           DeepSeek         4.0k lines  [##----------------------]   7.2%
                                           Sonnet            199 lines  [------------------------]   0.4%
                                           Total           55.5k lines  ·  total generated
                                           Tokens          164.78M      ·  148.90M input / 15.88M output
                                         ────────────────────────────────────────────────────────────────
                                         All-Time
                                           Commits              6,029+  ·  70 (30D) · 48.6% night commits
                                           Repos              31 repos  ·  8 pub   · 23 priv   · 88.4 MiB
                                           LeetCode          91 solved  ·  77 Easy · 12 Medium ·   2 Hard
                                           Stack Overflow      471 rep  ·  1 Gold  · 5 Silver  · 8 Bronze
                                           Spotify           5,252 hrs  ·  90,415 streams
                                         ────────────────────────────────────────────────────────────────
                                           *scripting, device tuning, ricing & agent tasks
```

---

> *"That's the thing about people who think they hate computers. What they really hate is lousy programmers."*  — Larry Niven

---

<p align="center">
  <code>sync: 2026-11-16 06:38 IST</code> &nbsp;·&nbsp; <code>next: ~06:38 IST</code><br>
  <sub>Metrics reflect a fraction of total activity across tracked environments.<br>
  Copyright © 2020 - 2026 | Aditya Prasad S</sub><br><br>
  <a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://da.gd/track0" width="94"></a>
</p>

<!--END_SECTION:waka-->
