```html
<!-- ===== PROBLEM SECTION (from Pioteye) ===== -->
<section id="problem">
  <div class="problem-video">
    <video autoplay muted loop playsinline>
      <source src="../uploads/The_Science_of_the_Curb__version_1.mp4" type="video/mp4" />
    </video>
  </div>
  <div class="problem-overlay"></div>
  <div class="container problem-content">
    <div class="reveal">
      <div class="tag"><span class="dot"></span> Analisi Urbana</div>
      <h2 class="sec-title" style="color:white;">Il Costo del <span>Giro a Vuoto</span></h2>
      <div class="divider"></div>
      <div class="problem-grid">
        <div class="prob-stats">
          <div class="pstat reveal">
            <div class="sn" data-count="30">0</div><span style="color:var(--cyan);font-weight:900;">%</span>
            <div class="sl">del traffico urbano è causato dalla ricerca di parcheggio</div>
          </div>
          <div class="pstat reveal">
            <div class="sn" data-count="17">0</div><span style="color:var(--cyan);font-weight:900;">min</span>
            <div class="sl">tempo medio sprecato per ogni sessione di ricerca</div>
          </div>
          <div class="pstat reveal">
            <div class="sn">€4.2B</div>
            <div class="sl">ricavi persi globalmente per sessioni non verificate</div>
          </div>
          <div class="pstat reveal">
            <div class="sn" data-count="40">0</div><span style="color:var(--cyan);font-weight:900;">%</span>
            <div class="sl">emissioni CO₂ in eccesso per la ricerca parcheggio</div>
          </div>
        </div>
        <div class="reveal">
          <p class="sec-sub" style="color:rgba(255,255,255,0.7);">Le città perdono milioni ogni anno a causa di una
            gestione inefficiente. Trivium risolve il problema alla radice.</p>
          <div class="fact-list">
            <div class="fact">
              <div class="fact-icon">📡</div>
              <div>
                <h4>Visibilità Real-Time</h4>
                <p>Rilevamento istantaneo dell'occupazione con latenza sub-secondo.</p>
              </div>
            </div>
            <div class="fact">
              <div class="fact-icon">💸</div>
              <div>
                <h4>Recupero Ricavi</h4>
                <p>Elimina le perdite dovute a sensori difettosi e sessioni non pagate.</p>
              </div>
            </div>
            <div class="fact">
              <div class="fact-icon">🌍</div>
              <div>
                <h4>Sostenibilità</h4>
                <p>Riduce drasticamente il traffico parassita e le emissioni urbane.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
```

```css
/* ========== PROBLEM SECTION (from Pioteye) ========== */
#problem {
  position: relative;
  overflow: hidden;
  padding: 110px 0;
}

.problem-video {
  position: absolute;
  inset: 0;
  z-index: 0;
}

.problem-video video {
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.4;
}

.problem-overlay {
  position: absolute;
  inset: 0;
  background: linear-gradient(135deg, rgba(26, 30, 36, 0.95) 0%, rgba(10, 22, 40, 0.85) 100%);
  z-index: 1;
}

.problem-content {
  position: relative;
  z-index: 2;
}

.problem-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 70px;
  align-items: center;
  margin-top: 50px;
}

.prob-stats {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
}

.pstat {
  background: rgba(0, 212, 232, 0.05);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  padding: 24px;
  position: relative;
  overflow: hidden;
}

.pstat .sn {
  font-size: 2.2rem;
  font-weight: 900;
  color: var(--cyan);
}

.pstat .sl {
  font-size: .8rem;
  color: var(--gray);
  margin-top: 5px;
  line-height: 1.5;
}

.fact-list {
  display: flex;
  flex-direction: column;
  gap: 14px;
  margin-top: 28px;
}

.fact {
  display: flex;
  gap: 12px;
  align-items: flex-start;
}

.fact-icon {
  width: 36px;
  height: 36px;
  border-radius: 8px;
  background: rgba(0, 212, 232, 0.1);
  border: 1px solid var(--border);
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: .95rem;
  flex-shrink: 0;
}
```
