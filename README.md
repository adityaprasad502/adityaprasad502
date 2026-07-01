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
<p><a href="https://a.devh.in" rel="nofollow"><img src="https://camo.githubusercontent.com/97907f2b02ba8f04363e017fd6d1b846728d85d7a3ce2bab9f3b78ca718d56af/687474703a2f2f696d672e736869656c64732e696f2f62616467652f436f646525323054696d6525323073696e636525323032322f30312f323032322d3125324336393525323068727325323031322532306d696e732d626c75653f6c6f676f3d77616b6174696d65" alt="Code Time" data-canonical-src="http://img.shields.io/badge/Code%20Time%20since%2022/01/2022-1%2C695%20hrs%2012%20mins-blue?logo=wakatime" style="max-width: 100%;"></a></p>
<p><strong>👨‍💻 Dev Profile Summary (All-Time)</strong></p>
<blockquote>
<p>🏆 <strong>5,741+</strong> Commits made on GitHub</p>
<p>🗃️ <strong>6</strong> Public • <strong>17</strong> Private Repositories</p>
<p>📦 <strong>76.6 MiB</strong> Used in GitHub Storage</p>
<p>⚡ LeetCode: <strong>91</strong> Solved (77E • 12M • 2H)</p>
<p>🏅 StackOverflow: <strong>461</strong> Rep (1G • 5S • 8B)</p>
<p>🎧 Spotify: <strong>5,437h 54m</strong> (92,370 Streams)</p>
</blockquote>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>🕐 Commit Patterns</b></summary><br>
<table>
<tbody><tr><th colspan="4">📅 No commits found in July 2026</th></tr>
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
<td>JavaScript</td>
<td>5 hrs 47 mins</td>
<td>███████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>28.8%</td>
</tr> 
 <tr>
<td>CSS</td>
<td>4 hrs 56 mins</td>
<td>██████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>24.6%</td>
</tr> 
 <tr>
<td>Markdown</td>
<td>1 hr 58 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>9.8%</td>
</tr> 
 <tr>
<td>Python</td>
<td>1 hr 32 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>7.7%</td>
</tr> 
 <tr>
<td>XML</td>
<td>1 hr 16 mins</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>6.3%</td>
</tr> 
 <tr>
<td>Kotlin</td>
<td>1 hr 5 mins</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.5%</td>
</tr> 
 <tr>
<td>Other</td>
<td>1 hr 3 mins</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.3%</td>
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
<td>11 hrs 5 mins</td>
<td>█████████████▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>55.2%</td>
</tr> 
 <tr>
<td>VS Code</td>
<td>4 hrs 32 mins</td>
<td>█████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>22.6%</td>
</tr> 
 <tr>
<td>Android Studio</td>
<td>2 hrs 31 mins</td>
<td>███▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>12.5%</td>
</tr> 
 <tr>
<td>Antigravity IDE</td>
<td>1 hr 57 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>9.7%</td>
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
<td>18 hrs 6 mins</td>
<td>██████████████████████▒▒▒</td>
<td>90.1%</td>
</tr> 
 <tr>
<td>Windows</td>
<td>1 hr 59 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>9.9%</td>
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
<td>18 hrs 6 mins</td>
<td>██████████████████████▒▒▒</td>
<td>90.1%</td>
</tr> 
 <tr>
<td>Pu94X</td>
<td>1 hr 59 mins</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>9.9%</td>
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
<td>Kotlin</td>
<td>735.2 KiB</td>
<td>████████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>34.3%</td>
</tr> 
 <tr>
<td>Python</td>
<td>636.6 KiB</td>
<td>███████▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>29.7%</td>
</tr> 
 <tr>
<td>Dart</td>
<td>245.3 KiB</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>11.4%</td>
</tr> 
 <tr>
<td>JavaScript</td>
<td>208.7 KiB</td>
<td>██▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>9.7%</td>
</tr> 
 <tr>
<td>TypeScript</td>
<td>124.2 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.8%</td>
</tr> 
 <tr>
<td>CSS</td>
<td>116.2 KiB</td>
<td>█▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>5.4%</td>
</tr> 
 <tr>
<td>HTML</td>
<td>63.0 KiB</td>
<td>▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒</td>
<td>2.9%</td>
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
<p><strong>What do you call a nervous javelin thrower?</strong></p>
<p><em>» Shakespeare.</em></p>
<hr>
<p><strong>Did you hear about the cheese factory that exploded in France?</strong></p>
<p><em>» There was nothing left but de Brie.</em></p>
<hr>
<p><strong>Why does Santa go down the chimney?</strong></p>
<p><em>» Because it soots him!</em></p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>💡 Did You Know</b></summary><br>
<p>💡 A pig`s orgasm lasts for 30 minutes.</p>
<hr>
<p>💡 Dreamt is the only English word that ends in the letters “MT”.</p>
<hr>
<p>💡 When sharks take a bite, their eyes roll back and their teeth jut out.</p>
</details>
<p>
    <a href="https://a.devh.in" rel="nofollow">
        <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" style="max-width: 100%;">
    </a>
</p>
<details>
<summary><b>✨ Inspiration</b></summary><br>
<blockquote>
  <p><em>"Speak less than you know; have more than you show."</em> - William Shakespeare</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"The function of leadership is to produce more leaders, not more followers."</em> - Ralph Nader</p>
</blockquote>
<hr>
<blockquote>
  <p><em>"The distance between insanity and genius is measured only by success."</em> - Bruce Feirstein</p>
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
<td>Thursday</td>
<td>July 02, 2026</td>
<td> 04:13 AM IST</td>
</tr>
<tr>
<td>Next Refresh</td>
<td>Friday</td>
<td>July 03, 2026</td>
<td>~04:10 AM IST</td>
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
