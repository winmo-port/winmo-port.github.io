---
title: "Retail Inventory Analysis Dashboard"
summary: "Interactive Tableau dashboard analyzing retail inventory turnover, revenue concentration, and regional sales to guide smarter procurement and stocking strategies."
tags:
  - Tableau
  - Business Intelligence
  - Retail Analytics
  - Inventory Management
categories:
  - Dashboard
  - Data Visualization
date: 2025-10-01

featured: true
image:
  preview_only: false
  filename: "Inventory Analysis.png"
---

## Project Overview  

This project explores a retail company’s inventory across product categories and regions.  
The goal: **help managers decide what to stock more of, what to cut back on, and how to allocate resources smarter.**

The dataset is fictional but designed to reflect real-world retail challenges.  

---

## Why This Matters for Business  

Retailers constantly juggle:  

- **Too much stock** → wasted money & storage space  
- **Too little stock** → missed sales opportunities  

This Tableau dashboard gives procurement and product teams a **clear view of what’s selling, what’s stagnating, and where to focus next.**  

---

## Key Business Insights  

### 1. Top Products Drive Most of the Money  
- Class A items generated **over $300K in 2021 revenue**.  
- Some Class B products performed nearly as efficiently → growth opportunity.  

**Action:** Increase Class B stock to capture more revenue.  

---

### 2. Categories Tell Two Stories  
- **Home Accessories & Decoration**: High revenue, slow movement.  
- **Office & School**: Low revenue, but high turnover.  
- **Jewelry**: Weak across the board.  

**Action:** Keep Office & School moving, optimize pricing, reduce Jewelry stock.  

---

### 3. Regional Focus  
- USA, Canada, and Europe dominate orders.  

**Action:** Focus stocking and marketing in these regions first.  

---

### 4. Year-over-Year Winners  
- Products like *Doughnut Lip Gloss* nearly doubled revenue YoY.  
- Demand shifted from Home Accessories → Toys & Edibles.  

**Action:** Double down on trending products.  

---

## Final Recommendations  

- Scale Class B products to grow sales.  
- Cut underperformers like Jewelry.  
- Improve pricing/marketing for Office & School.  
- Prioritize USA, Canada, and European markets.  
- Always stock fast-growing products like *Doughnut Lip Gloss*.  

**Bottom line:** The dashboard helps teams **reduce waste, free up cash, and grow revenue**.  

---

## Tableau Dashboard  

## Tableau Dashboard  

<div class='tableauPlaceholder' id='vizResponsiveCategory' style='position: relative; width: 100%;'>
  <noscript>
    <a href='#'>
      <img alt='Category and Country'
        src='https://public.tableau.com/static/images/In/InventoryAnalysis_17593808760620/CategoryandCountry/1.png'
        style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='name' value='InventoryAnalysis_17593808760620/CategoryandCountry' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image'
      value='https://public.tableau.com/static/images/In/InventoryAnalysis_17593808760620/CategoryandCountry/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
  </object>
</div>

<script type='text/javascript'>
  var divElement = document.getElementById('vizResponsiveCategory');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';

  // Responsive height with minimum to stop clipping
  if (divElement.offsetWidth > 1000) {
    vizElement.style.height = Math.max(divElement.offsetWidth * 0.55, 700) + 'px';
  } else if (divElement.offsetWidth > 600) {
    vizElement.style.height = Math.max(divElement.offsetWidth * 0.75, 650) + 'px';
  } else {
    vizElement.style.height = Math.max(divElement.offsetWidth * 1.1, 600) + 'px';
  }

  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
