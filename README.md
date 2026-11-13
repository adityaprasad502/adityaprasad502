<h2 align='center'><a href="https://a.devh.in" rel="nofollow"><img src="https://media4.giphy.com/media/rar203X81bEN2bVdYJ/giphy.gif" height="120" width="120"></a><br><code>// Howdy, &lt;Peepers /&gt;</code><br>
<!-- <a href="https://a.devh.in" rel="nofollow">
    <img src="https://media3.giphy.com/media/WKF4d7M8OpGmqxOsHb/giphy.gif" height="36" width="36">
  </a>
  Howdy < Peepers />! 
  <a href="https://a.devh.in" rel="nofollow">
    <img src="https://media4.giphy.com/media/B6m7Q7Bak35QaLtmcy/giphy.gif" height="36" width="36">
  </a><br> -->
</h2>

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

<h1 align='center'><a href="https://a.devh.in" rel="nofollow"><img src="https://media.giphy.com/media/Sh1iCtJZEdx4PFYy4q/giphy-downsized.gif" height="32" width="32"></a> Github Stats <a href="https://a.devh.in" rel="nofollow"><img src="https://media.giphy.com/media/cYU6YcPE5YlJxh6otp/giphy.gif" height="31" width="31"></a></h1>


  <!--START_SECTION:waka-->
<p><a href="https://a.devh.in" rel="nofollow"><img src="https://camo.githubusercontent.com/d6549499a5471e390ce66bdf4bd47a38b82d0ff6cf7363442b0485c1bd55c1fc/687474703a2f2f696d672e736869656c64732e696f2f62616467652f436f646525323054696d6525323073696e63652532304672692532304a616e25323032317374253230323032322d3125324339333425323068727325323031312532306d696e732d626c75653f6c6f676f3d77616b6174696d65" alt="Code Time" data-canonical-src="http://img.shields.io/badge/Code%20Time%20since%20Fri%20Jan%2021st%202022-1%2C934%20hrs%2011%20mins-blue?logo=wakatime" style="max-width: 100%;"></a></p>
<p><strong>👨‍💻 Dev Profile Summary (All-Time)</strong></p>
<blockquote>
<p>🏆 <strong>6,020+</strong> Commits made on GitHub</p>
<p>🗃️ <strong>8</strong> Public • <strong>23</strong> Private Repositories</p>
<p>📦 <strong>88.3 MiB</strong> Used in GitHub Storage</p>
<p>⚡ LeetCode: <strong>91</strong> Solved (77E • 12M • 2H)</p>
<p>🏅 StackOverflow: <strong>471</strong> Rep (1G • 5S • 8B)</p>
<p>🎧 Spotify: <strong>5,245h 23m</strong> (90,308 Streams)</p>
</blockquote>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>🕐 Commit Patterns</b></summary><br>
<table>
<tbody><tr><th colspan="4"> 👻 I'm a Night 🦉</th></tr> 
 <tr>
<td>🌞 Morning</td>
<td>3 commits</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>4.9%</td>
</tr> 
 <tr>
<td>🌆 Daytime</td>
<td>19 commits</td>
<td>███████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>31.1%</td>
</tr> 
 <tr>
<td>🌃 Evening</td>
<td>14 commits</td>
<td>█████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>23.0%</td>
</tr> 
 <tr>
<td>🌙 Night</td>
<td>25 commits</td>
<td>██████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>41.0%</td>
</tr>
<tr>
<td colspan="2"><b>📊 Total Commits</b></td>
<td colspan="2"><b>61 commits in November 2026</b></td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>⌨️ Languages &amp; Ops (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>QML</td>
<td>46h 46m 38s</td>
<td>███████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>43.6%</td>
</tr> 
 <tr>
<td>AgentOps<sup>*</sup>
</td>
<td>11h 34m 59s</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>10.8%</td>
</tr> 
 <tr>
<td>Python</td>
<td>10h 40m 35s</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>10.0%</td>
</tr> 
 <tr>
<td>Markdown</td>
<td>10h 24m 35s</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>9.7%</td>
</tr> 
 <tr>
<td>Text</td>
<td>6h 7m 43s</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.7%</td>
</tr> 
 <tr>
<td>Image (png)</td>
<td>5h 6m 29s</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>4.8%</td>
</tr> 
 <tr>
<td>Go</td>
<td>4h 8m 19s</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>3.9%</td>
</tr>
</tbody></table>
<br><sub>* Ad-hoc scripting, device tuning, desktop ricing &amp; agent-driven system tasks.</sub>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>🛠️ Editors &amp; IDEs (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>Antigravity</td>
<td>98h 59m 3s</td>
<td>███████████████████████▒▒</td>
<td>92.3%</td>
</tr> 
 <tr>
<td>OpenCode</td>
<td>4h 22m 52s</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>4.1%</td>
</tr> 
 <tr>
<td>VS Code</td>
<td>2h 39m 11s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.5%</td>
</tr> 
 <tr>
<td>Android Studio</td>
<td>59m 36s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.9%</td>
</tr> 
 <tr>
<td>Vscodium</td>
<td>12m 36s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.2%</td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>🤖 Top AI Models (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>Gemini</td>
<td>49,416 lines</td>
<td>███████████████████████▒▒</td>
<td>92.2%</td>
</tr> 
 <tr>
<td>DeepSeek</td>
<td>3,852 lines</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>7.2%</td>
</tr> 
 <tr>
<td>Sonnet</td>
<td>199 lines</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.4%</td>
</tr> 
 <tr>
<td>GLM</td>
<td>89 lines</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.2%</td>
</tr> 
 <tr>
<td>Flint</td>
<td>20 lines</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.0%</td>
</tr>
 <tr>
<td><b>Total</b></td>
<td><b>53,576 lines</b></td>
<td colspan="2"><b>144.21M tokens (129.85M in / 14.36M out)</b></td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>🐧 Operating Systems (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>Linux</td>
<td>107h 3m 45s</td>
<td>█████████████████████████</td>
<td>99.8%</td>
</tr> 
 <tr>
<td>Unknown OS</td>
<td>9m 33s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.1%</td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>👨‍💻 Dev Workstations (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>xoarch</td>
<td>107h 3m 45s</td>
<td>█████████████████████████</td>
<td>99.8%</td>
</tr> 
 <tr>
<td>Unknown Hostname</td>
<td>9m 33s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.1%</td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>💽 Repo Distribution (Owned)</b></summary><br>
<table>
 <tbody><tr>
<td>QML</td>
<td>2.4 MiB</td>
<td>█████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>39.2%</td>
</tr> 
 <tr>
<td>Python</td>
<td>904.1 KiB</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>14.6%</td>
</tr> 
 <tr>
<td>Kotlin</td>
<td>894.9 KiB</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>14.5%</td>
</tr> 
 <tr>
<td>JavaScript</td>
<td>524.1 KiB</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>8.5%</td>
</tr> 
 <tr>
<td>Go</td>
<td>405.8 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>6.6%</td>
</tr> 
 <tr>
<td>Dart</td>
<td>245.3 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>4.0%</td>
</tr> 
 <tr>
<td>Java</td>
<td>200.3 KiB</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>3.2%</td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<div class="markdown-heading"><h2 align="center" class="heading-element">🎈 Fun Bytes 😜</h2><a id="user-content--fun-bytes-" class="anchor" aria-label="Permalink: 🎈 Fun Bytes 😜" href="#-fun-bytes-"><span aria-hidden="true" class="octicon octicon-link"></span></a></div>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>😄 Laugh Break</b></summary><br>
<p><strong>Why can't Helen Keller see why kids love the taste of Cinnamon Toast Crunch?</strong></p>
<p><em>» She's dead.</em></p>
<hr>
<p><strong>Why did the crab get arrested?</strong></p>
<p><em>» It was a crabby crime.</em></p>
<hr>
<p><strong>The average penis has...</strong></p>
<p><em>» Been in and around my ex-girlfriend's mouth.
Fuck you, Karen!</em></p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>💡 Did You Know</b></summary><br>
<p>💡 Annual growth of WWW traffic is 314,000%</p>
<hr>
<p>💡 The Great Wall of China is the only man-made structure visible from space.</p>
<hr>
<p>💡 In 10 minutes, a hurricane releases more energy than all of the world's nuclear weapons combined.</p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>✨ Inspiration</b></summary><br>
<blockquote>
  <p><em>"If you smile when no one else is around, you really mean it."</em> - Andy Rooney</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"To win true freedom you must be a slave to philosophy."</em> - Seneca</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"Is freedom anything else than the right to live as we wish? Nothing else."</em> - Epictetus</p>
</blockquote>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>🕓 Last Updated</b></summary><br>
<table>
<tbody>
<tr>
<td>Last Refresh</td>
<td>Friday</td>
<td>November 13, 2026</td>
<td> 07:26 AM IST</td>
</tr>
<tr>
<td>Next Refresh</td>
<td>Saturday</td>
<td>November 14, 2026</td>
<td>~07:25 AM IST</td>
</tr>
</tbody>
</table>
</details>
<p>
	<a href="https://a.devh.in" rel="nofollow">
		<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
	</a>
</p>
<p align="center">
<sub>These metrics represent a fraction of my total activity and do not capture work across all tools and environments. <br> Copyright © 2020 - 2026 | Aditya Prasad S</sub> <br><br>
<a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://camo.githubusercontent.com/9ecdedaac0f66d2baeea53f9fd787afb65577dc2242282f9fa0f1c47ce34a8b4/68747470733a2f2f64612e67642f747261636b30" width="94" data-canonical-src="https://da.gd/track0" style="max-width: 100%;"></a>
</p>

<!--END_SECTION:waka-->
