<!DOCTYPE html>
<html>
<body>

<h1>Endangered Species Analysis</h1>

<p>
  This repository contains materials for a project analyzing endangered species trends in several U.S. National Parks. 
  The goal is to explore species information, observe patterns in conservation status, and derive recommendations 
  that can aid park managers and conservationists. 
</p>

<hr>

<h2>Repository Contents</h2>
<ul>
  <li><strong><code>biodiversity.ipynb</code></strong>: A Jupyter Notebook performing data loading, cleaning, 
  exploration, significance testing, and visualization of the species datasets.</li>
  <li><strong><code>species_info.csv</code></strong>: Contains information on each species, including its 
  <em>category</em>, <em>scientific_name</em>, <em>common_name</em>, and <em>conservation_status</em>.</li>
  <li><strong><code>observations.csv</code></strong>: Holds recorded sightings (counts) of each species 
  (<em>scientific_name</em>) at different parks (<em>park_name</em>) over the last 7 days.</li>
</ul>

<hr>

<h2>Project Overview</h2>
<p>
  This analysis covers several major topics:
</p>
<ul>
  <li><strong>Data Cleaning & Exploration</strong>: Examines missing values, merges datasets on <code>scientific_name</code>, 
  and analyzes how many species are under each conservation status.</li>
  <li><strong>Statistical Significance</strong>: Uses chi-square tests to determine if certain <em>species categories</em> 
  (e.g., Mammals, Birds) are more likely to be endangered.</li>
  <li><strong>Observations and Trends</strong>: Identifies which parks host the greatest number of sightings and 
  highlights species most frequently observed in each park.</li>
  <li><strong>Recommendations</strong>: Suggests possible interventions for conservation efforts, emphasizing 
  targeted protection for the most at-risk species and multi-park collaboration.</li>
</ul>

<hr>

<h2>Usage Instructions</h2>
<ol>
  <li><strong>Clone or Download</strong> this repository.</li>
  <li>Ensure you have Python and Jupyter Notebook (or JupyterLab) installed.</li>
  <li>Ensure you have Python 3.7 (or higher) installed, as well as Jupiter Notebook (or Jupiter Lab).</li>
  <li><strong>Install Dependencies</strong> using the <code>requirements.txt</code>:
    <pre><code>pip install -r requirements.txt</code></pre>
  </li>
  <li><strong>Open the Notebook</strong> (e.g., <code>analysis_notebook.ipynb</code>) in Jupyter.</li>
  <li><strong>Run the Notebook Cells</strong> in sequence. This will:
    <ul>
      <li>Load the data from <code>species_info.csv</code> and <code>observations.csv</code>.</li>
      <li>Perform data cleaning and merging.</li>
      <li>Generate plots (bar charts, stacked bar charts, etc.).</li>
      <li>Run statistical tests and output results.</li>
    </ul>
  </li>
</ol>

<hr>

<h2>Key Findings</h2>
<ul>
  <li>Most species have <em>No Intervention</em> status, but a significant number are listed as <em>Species of Concern</em> or <em>Endangered</em>.</li>
  <li>Categories such as <em>Mammals</em> and <em>Birds</em> demonstrated higher proportions of endangered species, confirmed by chi-square tests.</li>
  <li>Some parks (e.g., Yellowstone, Yosemite) had notably higher total sightings, suggesting either larger habitat areas, more park visitors, or greater biodiversity.</li>
</ul>

<hr>

<h2>Recommended Next Steps</h2>
<ul>
  <li><strong>Focused Monitoring</strong>: Increase observation or survey frequency for at-risk species identified in the analysis.</li>
  <li><strong>Multi-Park Collaboration</strong>: Enhance coordination across parks, especially where endangered species overlap.</li>
  <li><strong>Longer-Term Data</strong>: Extend observation windows beyond 7 days for more robust trend analysis.</li>
  <li><strong>Further Research</strong>: Incorporate habitat/land-use data or invasive species info to see if external factors correlate with endangerment.</li>
</ul>

<hr>
<p>
  All data and materials provided here are for educational and informational purposes. The National Parks Service 
  is the original data source for the species and observations datasets. If you plan to use this data in 
  research or publications, please ensure to cite the original source appropriately.
</p>

<hr>

</body>
</html>
