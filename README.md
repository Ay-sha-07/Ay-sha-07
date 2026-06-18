<p align="center" style="font-family: 'Fira Code', monospace; font-size: 24px; color: #FFFFFF;">
  <!-- First line that types out and stays -->
  <span style="display: block; margin-bottom: 10px;">Welcome to Ayisha's GitHub</span>
  
  <!-- Second line where 'Building' stays still, but dots animate one-by-one -->
  <span>Building<span class="animated-dots"></span></span>
</p>

<!-- The magic styling that makes the dots appear one by one without refreshing -->
<style>
  .animated-dots::after {
    content: '';
    animation: dot-tick 2s infinite steps(4, end);
  }

  @keyframes dot-tick {
    0%, 20% { content: ''; }
    40% { content: '.'; }
    60% { content: '..'; }
    80%, 100% { content: '...'; }
  }
</style>

<h2 align="center">📊 Statistics</h2>

<p align="center">
  <img width="25%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ay-sha-07&layout=compact&theme=dark&hide_border=false" alt="Top Languages" />
  <img width="33%" src="https://github-readme-stats.vercel.app/api?username=Ay-sha-07&show_icons=true&theme=dark&hide_border=false&count_private=true" alt="GitHub Stats" />
  <img width="35%" src="https://github-readme-streak-stats.herokuapp.com/?user=Ay-sha-07&theme=dark&hide_border=false" alt="GitHub Streak" />
</p>

<p align="center">
  <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Ay-sha-07&theme=github-dark-neon&bg_color=0d1117&hide_border=false" alt="Activity Graph" />
</p>
