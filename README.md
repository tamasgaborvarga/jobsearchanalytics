# Job Search Analytics

A data-driven approach to tracking my own job search process in 2026. I treat my applications like any other business problem: collecting the data, measuring what matters, and visualizing the results.

**[VIEW LIVE DASHBOARD](https://job-search-analytics.vtamasgabor.workers.dev/)**

---

## Technical Stack
* **Frontend:** Vanilla HTML5, CSS3 using Grid/Flexbox layouts and custom properties[cite: 1].
* **Data Visualization:** Chart.js combined with a custom Vanilla SVG Sankey diagram[cite: 1].
* **Data Management:** Client-side JavaScript processing an anonymized raw application log directly[cite: 1].

## Key Metrics (KPIs)
* **Interview Conversion:** The percentage of outbound applications that successfully reached the interview stage[cite: 1].
* **Response Rate:** Total company responsiveness, tracking both rejections and interview invitations[cite: 1].
* **Avg. Days to Rejection:** The mean and median duration from the application date to a definitive rejection[cite: 1].
* **Ghosted Status:** An automated classification for applications with 30+ days of silence to avoid inflating the active pipeline[cite: 1].

## Usage and Customization
You can easily track your own 2026 data by modifying the `var DATA` array inside the `index.html` file using this structure[cite: 1]:

```javascript
{ 
  loc: "Budapest", 
  pos: "Business Analyst", 
  applied: "2026-05-07", 
  rejected: "2026-05-11", 
  rej: true, 
  interview: false, 
  inbound: false 
}
