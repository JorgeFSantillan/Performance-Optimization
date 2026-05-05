<h1>Website Performance Optimization Case Study</h1>

<p><strong>Project:</strong> Govsera</p>
<p><strong>Stack:</strong> WordPress + Elementor</p>
<p><strong>Scope:</strong> Performance audit and optimization</p>

<h2>Overview</h2>

<p>
This project focuses on improving performance on a WordPress website built with Elementor.
The goal is to reduce load times, improve Core Web Vitals, and stabilize page rendering
without impacting layout or functionality.
</p>

<h2>Before vs After</h2>

<h3>Before Optimization</h3>
<img src="before-performance.png" alt="Lighthouse performance before optimization" width="800">

<h3>After Optimization</h3>
<img src="after-performance.png" alt="Lighthouse performance after optimization" width="800">

<h2>Performance Results</h2>

<table>
<tr>
<th>Metric</th>
<th>Before</th>
<th>After</th>
<th>Change</th>
</tr>
<tr>
<td>Performance Score</td>
<td>72</td>
<td>91</td>
<td>+19</td>
</tr>
<tr>
<td>First Contentful Paint</td>
<td>1.4s</td>
<td>0.6s</td>
<td>57% faster</td>
</tr>
<tr>
<td>Largest Contentful Paint</td>
<td>3.6s</td>
<td>1.9s</td>
<td>47% faster</td>
</tr>
<tr>
<td>Total Blocking Time</td>
<td>20ms</td>
<td>0ms</td>
<td>Eliminated</td>
</tr>
<tr>
<td>Speed Index</td>
<td>2.2s</td>
<td>1.2s</td>
<td>45% faster</td>
</tr>
<tr>
<td>Cumulative Layout Shift</td>
<td>0</td>
<td>0</td>
<td>Maintained</td>
</tr>
</table>

<h2>Key Problems Identified</h2>

<ul>
<li>High Largest Contentful Paint (LCP)</li>
<li>Render-blocking CSS and JavaScript</li>
<li>Staggered page loading</li>
<li>Large image assets affecting load performance</li>
<li>Excess CSS from the page builder increasing load time</li>
</ul>

<h2>Optimization Strategy</h2>

<h3>1. Caching and Server Optimization</h3>
<ul>
<li>Configured LiteSpeed Cache</li>
<li>Enabled page caching</li>
<li>Enabled browser caching</li>
<li>Improved server response consistency</li>
</ul>

<h3>2. JavaScript Optimization</h3>
<ul>
<li>Implemented deferred JavaScript loading</li>
<li>Reduced render-blocking behavior</li>
<li>Maintained layout stability by avoiding aggressive delay settings</li>
</ul>

<h3>3. CSS Optimization</h3>
<ul>
<li>Enabled asynchronous CSS loading</li>
<li>Reduced render-blocking stylesheets</li>
<li>Improved time to first render</li>
</ul>

<h3>4. Image Optimization</h3>
<ul>
<li>Resized images to appropriate display dimensions</li>
<li>Reduced image file sizes for faster loading</li>
<li>Improved above-the-fold loading performance</li>
</ul>

<h2>Key Outcomes</h2>

<ul>
<li>Achieved a 90+ Lighthouse performance score</li>
<li>Reduced LCP from 3.6s to 1.9s</li>
<li>Eliminated total blocking time</li>
<li>Improved page rendering consistency</li>
<li>Enhanced perceived load speed</li>
</ul>

<h2>Conclusion</h2>

<p>
This project demonstrates a structured performance optimization process: identifying
bottlenecks, applying targeted fixes, and validating improvements with measurable results.
The final result is a fast, stable, and production-ready website with strong Core Web Vitals.
</p>
