## 📊 GitHub Analytics

<div align="center">

<!-- Animated Stats Cards -->
<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 15px; margin-bottom: 20px;">

[![Star History Chart](https://api.star-history.com/svg?repos=DevAhmedNaeem&type=Timeline)](https://star-history.com/#DevAhmedNaeem&Timeline)

</div>

<!-- Main Stats Grid -->
<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 15px;">

<!-- Profile Stats Card -->
<a href="https://github.com/DevAhmedNaeem">
  <img src="https://github-readme-stats.vercel.app/api?username=DevAhmedNaeem&show_icons=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=61F1E1&icon_color=61F1E1" alt="Ahmed's GitHub stats" style="width: 100%; border-radius: 10px; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.03)'" onmouseout="this.style.transform='scale(1)'">
</a>

<!-- Streak Stats Card -->
<a href="https://github.com/DevAhmedNaeem">
  <img src="https://streak-stats.demolab.com?user=DevAhmedNaeem&theme=tokyonight&hide_border=true&border_radius=10&date_format=M%20j%5B%2C%20Y%5D" alt="GitHub Streak" style="width: 100%; border-radius: 10px; transition: transform 0.3s ease;" onmouseover="this.style.transform='scale(1.03)'" onmouseout="this.style.transform='scale(1)'">
</a>

<!-- Detailed Metrics Table -->
<table style="width:100%;background:#0D1117;border-radius:10px;border:1px solid #30363D;overflow:hidden;">
  <tr>
    <td style="padding:15px;text-align:center;border-bottom:1px solid #30363D;">
      <strong style="color:#61F1E1;">Metric</strong>
    </td>
    <td style="padding:15px;text-align:center;border-bottom:1px solid #30363D;">
      <strong style="color:#61F1E1;">Value</strong>
    </td>
    <td style="padding:15px;text-align:center;border-bottom:1px solid #30363D;">
      <strong style="color:#61F1E1;">Trend</strong>
    </td>
  </tr>
  <tr>
    <td style="padding:10px;text-align:center;">🌟 Stars Earned</td>
    <td style="padding:10px;text-align:center;" id="stars-count">Loading...</td>
    <td style="padding:10px;text-align:center;">📈</td>
  </tr>
  <tr>
    <td style="padding:10px;text-align:center;">💾 Total Commits</td>
    <td style="padding:10px;text-align:center;" id="commits-count">Loading...</td>
    <td style="padding:10px;text-align:center;">📈</td>
  </tr>
  <tr>
    <td style="padding:10px;text-align:center;">🔀 Pull Requests</td>
    <td style="padding:10px;text-align:center;" id="prs-count">Loading...</td>
    <td style="padding:10px;text-align:center;">📈</td>
  </tr>
  <tr>
    <td style="padding:10px;text-align:center;">❗ Issues</td>
    <td style="padding:10px;text-align:center;" id="issues-count">Loading...</td>
    <td style="padding:10px;text-align:center;">📈</td>
  </tr>
</table>

</div>

<!-- JavaScript for live data (works on GitHub profile) -->
<script>
// GitHub API fetch example (will work when hosted)
fetch('https://api.github.com/users/DevAhmedNaeem')
  .then(response => response.json())
  .then(data => {
    document.getElementById('stars-count').innerText = data.public_repos;
    // Add more API calls for commits, PRs, etc.
  });
</script>

<!-- Trophy Case -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=DevAhmedNaeem&theme=onedark&no-frame=true&margin-w=15&row=1&column=6" alt="GitHub Trophies" style="max-width: 100%;">
</p>
