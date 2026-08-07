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
<p><strong>👨‍💻 Dev Profile Summary (All-Time)</strong></p>
<blockquote>
<p>🏆 <strong>5,831+</strong> Commits made on GitHub</p>
<p>🗃️ <strong>7</strong> Public • <strong>17</strong> Private Repositories</p>
<p>📦 <strong>80.1 MiB</strong> Used in GitHub Storage</p>
<p>⚡ LeetCode: <strong>91</strong> Solved (77E • 12M • 2H)</p>
<p>🏅 StackOverflow: <strong>471</strong> Rep (1G • 5S • 8B)</p>
<p>🎧 Spotify: <strong>5,570h 44m</strong> (94,611 Streams)</p>
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
<td>1 commits</td>
<td>████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>33.3%</td>
</tr> 
 <tr>
<td>🌆 Daytime</td>
<td>0 commits</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.0%</td>
</tr> 
 <tr>
<td>🌃 Evening</td>
<td>0 commits</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>0.0%</td>
</tr> 
 <tr>
<td>🌙 Night</td>
<td>2 commits</td>
<td>████████████████▒▒▒▒▒▒▒▒▒</td>
<td>66.7%</td>
</tr>
<tr>
<td colspan="2"><b>📊 Total Commits</b></td>
<td colspan="2"><b>3 commits in August 2026</b></td>
</tr>
</tbody></table>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>⌨️ Languages (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>Kotlin</td>
<td>8 hrs 1 min</td>
<td>████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>34.8%</td>
</tr> 
 <tr>
<td>XML</td>
<td>4 hrs 36 mins</td>
<td>█████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>20.0%</td>
</tr> 
 <tr>
<td>QML</td>
<td>3 hrs 27 mins</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>15.0%</td>
</tr> 
 <tr>
<td>Markdown</td>
<td>1 hr 53 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>8.2%</td>
</tr> 
 <tr>
<td>Java</td>
<td>56 mins</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>4.1%</td>
</tr> 
 <tr>
<td>Text</td>
<td>47 mins</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>3.4%</td>
</tr> 
 <tr>
<td>Other</td>
<td>44 mins</td>
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
<details>
<summary><b>🛠️ Editors &amp; IDEs (30D)</b></summary><br>
<table>
 <tbody><tr>
<td>Antigravity Desktop</td>
<td>10 hrs 43 mins</td>
<td>███████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>46.5%</td>
</tr> 
 <tr>
<td>Android Studio</td>
<td>9 hrs 47 mins</td>
<td>██████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>42.4%</td>
</tr> 
 <tr>
<td>VS Code</td>
<td>1 hr 52 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>8.1%</td>
</tr> 
 <tr>
<td>Copilot CLI</td>
<td>41 mins</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>3.0%</td>
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
<td>23 hrs 4 mins</td>
<td>█████████████████████████</td>
<td>100.0%</td>
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
<td>23 hrs 4 mins</td>
<td>█████████████████████████</td>
<td>100.0%</td>
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
<td>1.9 MiB</td>
<td>███████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>43.6%</td>
</tr> 
 <tr>
<td>Kotlin</td>
<td>867.0 KiB</td>
<td>████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>18.9%</td>
</tr> 
 <tr>
<td>Python</td>
<td>706.3 KiB</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>15.4%</td>
</tr> 
 <tr>
<td>JavaScript</td>
<td>383.0 KiB</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>8.4%</td>
</tr> 
 <tr>
<td>Dart</td>
<td>245.3 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.4%</td>
</tr> 
 <tr>
<td>TypeScript</td>
<td>124.2 KiB</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.7%</td>
</tr> 
 <tr>
<td>CSS</td>
<td>116.3 KiB</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.5%</td>
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
<p><strong>What’s 50 Cent’s name in Zimbabwe?</strong></p>
<p><em>» 200 Dollars.</em></p>
<hr>
<p>A programmer puts two glasses on his bedside table before going to sleep.
A full one, in case he gets thirsty, and an empty one, in case he doesn't.</p>
<hr>
<p><strong>What's Santa's favourite type of music?</strong></p>
<p><em>» Wrap!</em></p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>💡 Did You Know</b></summary><br>
<p>💡 There are 1,792 steps in the Eiffel Tower</p>
<hr>
<p>💡 There is no solid proof of who built the Taj Mahal.</p>
<hr>
<p>💡 A signature is called a John Hancock because he signed the Declaration of Independence. Only 2 people signed the declaration of independence on July 4. The Last person signed 2 years later.</p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>✨ Inspiration</b></summary><br>
<blockquote>
  <p><em>"When everything seems to be going against you, remember that the airplane takes off against the wind, not with it."</em> - Henry Ford</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"A room without books is like a body without a soul."</em> - Marcus Tullius Cicero</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"The question isn’t who is going to let me; it’s who is going to stop me."</em> - Ayn Rand</p>
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
<td>August 07, 2026</td>
<td> 06:34 AM IST</td>
</tr>
<tr>
<td>Next Refresh</td>
<td>Saturday</td>
<td>August 08, 2026</td>
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
