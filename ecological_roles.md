# 🌿 Ecological Roles of Fungi

Fungi are essential players in ecosystems, performing critical roles that sustain life on Earth.  
Below you’ll find an **interactive card layout** summarizing seven key ecological functions, plus an infographic for visual learners.

---

## 📊 Infographic

> **Tip:** Replace the image path below with your actual infographic file in `assets/images/`.

![Ecological Roles of Fungi](../assets/images/fungi-ecology-roles.png)

*This infographic summarizes the key ecological functions of fungi, from nutrient cycling to climate regulation.*

---

## 🗂 Interactive Cards

<div class="card-grid">

### 🍂 Nutrient Cycling & Decomposition
Fungi are the **primary decomposers** of complex organic matter like lignin and cellulose, breaking down dead plants, animals, and waste into nutrients that can be reused by other organisms.  
This recycling keeps **carbon, nitrogen, and phosphorus** moving through ecosystems, preventing nutrient lock‑up in dead biomass.

---

### 🌳 Symbiotic Relationships
**Mycorrhizal fungi** form partnerships with ~90% of plant species, extending root systems and improving water and nutrient uptake.  
In return, plants supply fungi with carbohydrates from photosynthesis.  
These underground networks — sometimes called the **“Wood Wide Web”** — even allow plants to share resources and chemical signals.

---

### 🪨 Soil Formation & Structure
Fungal hyphae bind soil particles, improving aeration, water retention, and resistance to erosion.  
They help create **stable soil aggregates**, which are critical for long‑term soil fertility.

---

### 🐛 Food Web Support
Fungi are a direct food source for many invertebrates and indirectly support higher trophic levels.  
They also influence plant community composition, which shapes the entire food web.

---

### 🛡 Pathogen Regulation
Some fungi act as **natural population controls** by parasitizing plants, insects, or other fungi, maintaining ecological balance.  
Others protect plants from disease by outcompeting harmful microbes.

---

### 🌍 Climate Regulation
Fungi influence **carbon storage** in soils and forests.  
Mycorrhizal associations can increase plant resilience to drought and temperature extremes, helping ecosystems adapt to climate change.

---

### 📈 Bioindicators of Ecosystem Health
Changes in fungal diversity or abundance can signal shifts in soil quality, pollution levels, or climate impacts.  
**Lichens** (fungus + algae/cyanobacteria) are especially sensitive to air quality.

</div>

---

## 💡 How to Make These Cards Interactive

If you want these cards to be clickable and expand with more details:

```html
<style>
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1rem;
}
.card-grid h3 {
  margin-top: 0;
}
.card-grid div {
  background: #fff;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  transition: transform 0.2s ease;
}
.card-grid div:hover {
  transform: scale(1.02);
  cursor: pointer;
}
</style>
