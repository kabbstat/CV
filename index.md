---
layout: default
title: Mohamed Kabbaj - CV / Resume
lang: multi
---

<div class="language-selector">
  <h1>🌍 Mohamed Kabbaj</h1>
  <p class="subtitle">Data Scientist & MLOps Engineer</p>
  
  <div class="lang-cards">
    <a href="./fr" class="lang-card fr">
      <span class="flag">🇫🇷</span>
      <span class="lang-name">Français</span>
      <span class="lang-desc">Voir mon CV en français</span>
    </a>
    <a href="./en" class="lang-card en">
      <span class="flag">🇬🇧</span>
      <span class="lang-name">English</span>
      <span class="lang-desc">View my resume in English</span>
    </a>
  </div>
</div>

<style>
.language-selector {
  text-align: center;
  padding: 2em 0;
}

.language-selector h1 {
  font-size: 2.5em;
  margin-bottom: 0.2em;
}

.subtitle {
  font-size: 1.3em;
  color: #8b949e;
  margin-bottom: 2em;
}

.lang-cards {
  display: flex;
  justify-content: center;
  gap: 2em;
  flex-wrap: wrap;
  margin-top: 2em;
}

.lang-card {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2em 3em;
  border-radius: 16px;
  text-decoration: none;
  transition: all 0.3s ease;
  border: 2px solid #30363d;
  background: #161b22;
  min-width: 200px;
}

.lang-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 12px 40px rgba(0, 0, 0, 0.4);
  border-color: #58a6ff;
}

.lang-card.fr:hover {
  border-color: #0055a4;
  box-shadow: 0 12px 40px rgba(0, 85, 164, 0.3);
}

.lang-card.en:hover {
  border-color: #c8102e;
  box-shadow: 0 12px 40px rgba(200, 16, 46, 0.3);
}

.flag {
  font-size: 4em;
  margin-bottom: 0.3em;
}

.lang-name {
  font-size: 1.5em;
  font-weight: 600;
  color: #e6edf3;
  margin-bottom: 0.3em;
}

.lang-desc {
  font-size: 0.9em;
  color: #8b949e;
}

@media (max-width: 600px) {
  .lang-cards {
    flex-direction: column;
    align-items: center;
  }
  
  .lang-card {
    width: 100%;
    max-width: 280px;
  }
}
</style>
