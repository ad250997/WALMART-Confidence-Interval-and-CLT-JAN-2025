<!DOCTYPE html>
<html>
<body>
    <h1>Walmart Customer Spending Analysis Using CLT and Confidence Intervals</h1>
  
  <h2>Overview</h2>
  <p>This case study analyzes Walmart’s customer spending patterns using statistical methods like the Central Limit Theorem (CLT) and confidence intervals. The dataset includes 550,000+ transactions with features like gender, age, marital status, and purchase amounts. The goal is to identify actionable insights for targeted marketing and inventory strategies.</p>

  <h2>Key Objectives</h2>
  <ul>
      <li>Evaluate differences in spending between genders and marital statuses.</li>
      <li>Analyze age-group spending trends to optimize product placement and promotions.</li>
      <li>Apply bootstrap resampling to validate statistical significance of results.</li>
  </ul>

  <h2>Methodology</h2>
  <ul>
      <li>Performed bootstrap resampling (sample sizes: 50, 500, 5,000, 50,000) to estimate confidence intervals for average spending.</li>
      <li>Applied CLT to validate normal distribution of sample means for purchase amounts.</li>
      <li>Compared confidence intervals (90%, 95%, 99%) to assess statistical significance of differences.</li>
  </ul>

  <h2>Key Insights</h2>
  <ul>
      <li><strong>Gender-Based Spending:</strong> Males spent significantly more ($9,367 avg) than females ($8,671 avg) at a 99% confidence level for large samples (50,000+).</li>
      <li><strong>Marital Status:</strong> No significant difference in spending between married and unmarried customers (overlapping confidence intervals across all sample sizes).</li>
      <li><strong>Age Groups:</strong> The 51–55 age group had the highest spending ($9,387 avg), while the 0–17 group spent the least ($8,830 avg) with non-overlapping 99% CIs.</li>
  </ul>

  <h2>Recommendations</h2>
  <ul>
      <li>Target premium products and loyalty programs toward males and the 51–55 age group.</li>
      <li>Design universal promotions for married/unmarried customers due to similar spending patterns.</li>
      <li>Optimize store layouts to highlight high-margin products for high-spending age demographics.</li>
  </ul>
</body>
</html>
