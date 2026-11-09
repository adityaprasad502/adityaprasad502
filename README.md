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
<p><a href="https://a.devh.in" rel="nofollow"><img src="https://camo.githubusercontent.com/e2744a050edfe9f7ed81c56cd468f34a9a74be5c58826a63175632a0bb41a268/687474703a2f2f696d672e736869656c64732e696f2f62616467652f436f646525323054696d6525323073696e63652532304672692532304a616e25323032317374253230323032322d3125324339303325323068727325323032342532306d696e732d626c75653f6c6f676f3d77616b6174696d65" alt="Code Time" data-canonical-src="http://img.shields.io/badge/Code%20Time%20since%20Fri%20Jan%2021st%202022-1%2C903%20hrs%2024%20mins-blue?logo=wakatime" style="max-width: 100%;"></a></p>
<p><strong>👨‍💻 Dev Profile Summary (All-Time)</strong></p>
<blockquote>
<p>🏆 <strong>5,996+</strong> Commits made on GitHub</p>
<p>🗃️ <strong>7</strong> Public • <strong>23</strong> Private Repositories</p>
<p>📦 <strong>88.0 MiB</strong> Used in GitHub Storage</p>
<p>⚡ LeetCode: <strong>91</strong> Solved (77E • 12M • 2H)</p>
<p>🏅 StackOverflow: <strong>471</strong> Rep (1G • 5S • 8B)</p>
<p>🎧 Spotify: <strong>5,211h 13m</strong> (89,767 Streams)</p>
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
<td>2 commits</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.4%</td>
</tr> 
 <tr>
<td>🌆 Daytime</td>
<td>6 commits</td>
<td>████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>16.2%</td>
</tr> 
 <tr>
<td>🌃 Evening</td>
<td>12 commits</td>
<td>████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>32.4%</td>
</tr> 
 <tr>
<td>🌙 Night</td>
<td>17 commits</td>
<td>███████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>45.9%</td>
</tr>
<tr>
<td colspan="2"><b>📊 Total Commits</b></td>
<td colspan="2"><b>37 commits in November 2026</b></td>
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
<td>AgentOps<sup>*</sup>
</td>
<td>47h 49m 38s</td>
<td>██████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>41.0%</td>
</tr> 
 <tr>
<td>QML</td>
<td>29h 25m 21s</td>
<td>██████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>25.2%</td>
</tr> 
 <tr>
<td>Python</td>
<td>9h 21m 23s</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>8.0%</td>
</tr> 
 <tr>
<td>Markdown</td>
<td>6h 2m 53s</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.2%</td>
</tr> 
 <tr>
<td>JSON</td>
<td>4h 29m</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>3.8%</td>
</tr> 
 <tr>
<td>Java</td>
<td>3h 13m 5s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.8%</td>
</tr> 
 <tr>
<td>JavaScript</td>
<td>2h 35m 41s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.2%</td>
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
<td>109h 46m 47s</td>
<td>███████████████████████▒▒</td>
<td>94.1%</td>
</tr> 
 <tr>
<td>Opencode Cli</td>
<td>2h 58m 51s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.5%</td>
</tr> 
 <tr>
<td>VS Code</td>
<td>2h 34m 34s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.2%</td>
</tr> 
 <tr>
<td>Android Studio</td>
<td>58m 25s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.8%</td>
</tr> 
 <tr>
<td>OpenCode</td>
<td>19m 8s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.3%</td>
</tr> 
 <tr>
<td>Vscodium</td>
<td>4m 13s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.1%</td>
</tr> 
 <tr>
<td>Unknown Editor</td>
<td>25s</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.0%</td>
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
<td>97,475 lines</td>
<td>-</td>
<td>██████████████████████▒▒▒</td>
<td>89.7%</td>
</tr> 
 <tr>
<td>Sonnet</td>
<td>7,081 lines</td>
<td>-</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>6.5%</td>
</tr> 
 <tr>
<td>DeepSeek</td>
<td>3,852 lines</td>
<td>-</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>3.5%</td>
</tr> 
 <tr>
<td>GLM</td>
<td>101 lines</td>
<td>-</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.1%</td>
</tr> 
 <tr>
<td>Antigravity-Desktop</td>
<td>86 lines</td>
<td>-</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.1%</td>
</tr> 
 <tr>
<td>Vscode</td>
<td>54 lines</td>
<td>-</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.0%</td>
</tr> 
 <tr>
<td>Flint</td>
<td>20 lines</td>
<td>-</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.0%</td>
</tr>
 <tr>
<td><b>Total</b></td>
<td><b>108,669 lines</b></td>
<td><b>196.65M tokens</b></td>
<td colspan="2"><b>180.34M in / 16.3M out</b></td>
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
<td>88h 29m 25s</td>
<td>███████████████████▒▒▒▒▒▒</td>
<td>75.8%</td>
</tr> 
 <tr>
<td>Unknown OS</td>
<td>28h 12m 58s</td>
<td>██████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>24.2%</td>
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
<td>88h 28m 49s</td>
<td>███████████████████▒▒▒▒▒▒</td>
<td>75.8%</td>
</tr> 
 <tr>
<td>Unknown Hostname</td>
<td>28h 13m 34s</td>
<td>██████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>24.2%</td>
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
<td>2.3 MiB</td>
<td>██████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>40.7%</td>
</tr> 
 <tr>
<td>Python</td>
<td>898.6 KiB</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>15.4%</td>
</tr> 
 <tr>
<td>Kotlin</td>
<td>894.9 KiB</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>15.3%</td>
</tr> 
 <tr>
<td>JavaScript</td>
<td>522.1 KiB</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>8.9%</td>
</tr> 
 <tr>
<td>Go</td>
<td>401.2 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>6.9%</td>
</tr> 
 <tr>
<td>Dart</td>
<td>245.3 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>4.2%</td>
</tr> 
 <tr>
<td>CSS</td>
<td>130.5 KiB</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.2%</td>
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
<p>What's the difference between roast beef and pea soup. Anyone can roast beef, but nobody can pee soup.</p>
<hr>
<p><strong>What are bits?</strong></p>
<p><em>» Tiny things left when you drop your computer down the stairs.</em></p>
<hr>
<p>A bartender broke up with her boyfriend, but he kept asking her for another shot.</p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>💡 Did You Know</b></summary><br>
<p>💡 In the 17th century, the value of pi was known to 35 decimal places. Today, to 1.2411 trillion.</p>
<hr>
<p>💡 In the last 4000 years, no new animals have been domesticated.</p>
<hr>
<p>💡 More than 50% of the people in the world have never made or received a telephone call.</p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>✨ Inspiration</b></summary><br>
<blockquote>
  <p><em>"There is only one thing that makes a dream impossible to achieve: the fear of failure."</em> - Paulo Coelho</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"There is no easy walk to freedom anywhere, and many of us will have to pass through the valley of the shadow of death again and again before we reach the mountaintop of our desires."</em> - Nelson Mandela</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"The secret of getting ahead is getting started."</em> - Mark Twain</p>
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
<td>Monday</td>
<td>November 09, 2026</td>
<td> 06:30 AM IST</td>
</tr>
<tr>
<td>Next Refresh</td>
<td>Tuesday</td>
<td>November 10, 2026</td>
<td>~06:30 AM IST</td>
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
<a href="https://a.devh.in" rel="nofollow"><img alt="Hits" src="https://camo.githubusercontent.com/7edf0c29bf18ff9855bf1cd912410ceacdd695cd5e29de282bf2547982ff981a/68747470733a2f2f64612e67642f747261636b30" width="94" data-canonical-src="https://da.gd/track0" style="max-width: 100%;"></a>
</p>

<!--END_SECTION:waka-->
