<p align="center">
  <a href="https://github.com/SatoshiNakamoto99" target="_blank" rel="noopener noreferrer">
    <img id="typing-svg" src="https://readme-typing-svg.demolab.com?font=Georgia&size=18&duration=2000&pause=100&multiline=true&width=500&height=80&lines=Antonio+Nocerino;Advanced+Machine+Learning+Engineer;AI+Engineer+%7C+Computer+Vision" alt="Typing SVG Animated" />
  </a>
  <br/>

  <a href="https://ai-genius.xyz/about" target="_blank" rel="noopener noreferrer">
    <img id="website-badge" src="https://img.shields.io/badge/Website-anto.dev-red?style=flat-square" alt="Portfolio Website" />
  </a>  
  <a href="https://www.linkedin.com/in/anocerino/" target="_blank" rel="noopener noreferrer">
    <img id="linkedin-badge" src="https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn Profile" />
  </a>
  <a href="mailto:nocerino.antonioai@gmail.com">
    <img id="email-badge" src="https://img.shields.io/badge/-Email-red?style=flat-square&logo=gmail&logoColor=white" alt="Send Email" />
  </a>
  <br/> 

  <a href="https://github.com/SatoshiNakamoto99" target="_blank" rel="noopener noreferrer">
    <img id="github-stats" src="https://github-stats-alpha.vercel.app/api?username=SatoshiNakamoto99&cc=22272e&tc=37BCF6&ic=fff&bc=0000" alt="GitHub Summary Stats" />
  </a>
</p>

---

## 📈 GitHub Stats

<img id="github-profile" src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SatoshiNakamoto99&theme=dracula" alt="GitHub Profile Details" style="display:block; margin: 0 auto;" />

<div style="display: flex; gap: 10px; justify-content: center; margin-top: 10px;">
  <img id="repos-language" src="http://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=SatoshiNakamoto99&theme=dracula" alt="Repositories Per Language" />
  <img id="most-commit-language" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=SatoshiNakamoto99&theme=dracula" alt="Most Commit Language" />
</div>

<script>
  // Funzione per aggiungere cache busting a un URL
  function addCacheBusting(url) {
    const cb = Date.now();
    // Se c'è già un ? usa &, altrimenti ?
    const separator = url.includes('?') ? '&' : '?';
    return url + separator + 'cb=' + cb;
  }

  // Array di tutti gli id delle immagini a cui aggiungere cache busting
  const imgIds = [
    'typing-svg',
    'website-badge',
    'linkedin-badge',
    'email-badge',
    'github-stats',
    'github-profile',
    'repos-language',
    'most-commit-language'
  ];

  // Aggiungi cache busting a ciascuna immagine
  imgIds.forEach(id => {
    const img = document.getElementById(id);
    if (img) {
      img.src = addCacheBusting(img.src);
    }
  });
</script>
