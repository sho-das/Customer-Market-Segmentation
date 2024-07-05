<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml" lang="" xml:lang="">
<!-- <head>
  <meta charset="utf-8" />
  <meta name="generator" content="pandoc" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes" />
  <title></title>
  <style>
    html {
      line-height: 1.5;
      font-family: Georgia, serif;
      font-size: 20px;
      color: #1a1a1a;
      background-color: #fdfdfd;
    }
    body {
      margin: 0 auto;
      max-width: 36em;
      padding-left: 50px;
      padding-right: 50px;
      padding-top: 50px;
      padding-bottom: 50px;
      hyphens: auto;
      overflow-wrap: break-word;
      text-rendering: optimizeLegibility;
      font-kerning: normal;
    }
    @media (max-width: 600px) {
      body {
        font-size: 0.9em;
        padding: 1em;
      }
      h1 {
        font-size: 1.8em;
      }
    }
    @media print {
      body {
        background-color: transparent;
        color: black;
        font-size: 12pt;
      }
      p, h2, h3 {
        orphans: 3;
        widows: 3;
      }
      h2, h3, h4 {
        page-break-after: avoid;
      }
    }
    p {
      margin: 1em 0;
    }
    a {
      color: #1a1a1a;
    }
    a:visited {
      color: #1a1a1a;
    }
    img {
      max-width: 100%;
    }
    h1, h2, h3, h4, h5, h6 {
      margin-top: 1.4em;
    }
    h5, h6 {
      font-size: 1em;
      font-style: italic;
    }
    h6 {
      font-weight: normal;
    }
    ol, ul {
      padding-left: 1.7em;
      margin-top: 1em;
    }
    li > ol, li > ul {
      margin-top: 0;
    }
    blockquote {
      margin: 1em 0 1em 1.7em;
      padding-left: 1em;
      border-left: 2px solid #e6e6e6;
      color: #606060;
    }
    code {
      font-family: Menlo, Monaco, 'Lucida Console', Consolas, monospace;
      font-size: 85%;
      margin: 0;
    }
    pre {
      margin: 1em 0;
      overflow: auto;
    }
    pre code {
      padding: 0;
      overflow: visible;
      overflow-wrap: normal;
    }
    .sourceCode {
     background-color: transparent;
     overflow: visible;
    }
    hr {
      background-color: #1a1a1a;
      border: none;
      height: 1px;
      margin: 1em 0;
    }
    table {
      margin: 1em 0;
      border-collapse: collapse;
      width: 100%;
      overflow-x: auto;
      display: block;
      font-variant-numeric: lining-nums tabular-nums;
    }
    table caption {
      margin-bottom: 0.75em;
    }
    tbody {
      margin-top: 0.5em;
      border-top: 1px solid #1a1a1a;
      border-bottom: 1px solid #1a1a1a;
    }
    th {
      border-top: 1px solid #1a1a1a;
      padding: 0.25em 0.5em 0.25em 0.5em;
    }
    td {
      padding: 0.125em 0.5em 0.25em 0.5em;
    }
    header {
      margin-bottom: 4em;
      text-align: center;
    }
    #TOC li {
      list-style: none;
    }
    #TOC ul {
      padding-left: 1.3em;
    }
    #TOC > ul {
      padding-left: 0;
    }
    #TOC a:not(:hover) {
      text-decoration: none;
    }
    code{white-space: pre-wrap;}
    span.smallcaps{font-variant: small-caps;}
    div.columns{display: flex; gap: min(4vw, 1.5em);}
    div.column{flex: auto; overflow-x: auto;}
    div.hanging-indent{margin-left: 1.5em; text-indent: -1.5em;}
    ul.task-list{list-style: none;}
    ul.task-list li input[type="checkbox"] {
      width: 0.8em;
      margin: 0 0.8em 0.2em -1.6em;
      vertical-align: middle;
    }
    pre > code.sourceCode { white-space: pre; position: relative; }
    pre > code.sourceCode > span { display: inline-block; line-height: 1.25; }
    pre > code.sourceCode > span:empty { height: 1.2em; }
    .sourceCode { overflow: visible; }
    code.sourceCode > span { color: inherit; text-decoration: inherit; }
    div.sourceCode { margin: 1em 0; }
    pre.sourceCode { margin: 0; }
    @media screen {
    div.sourceCode { overflow: auto; }
    }
    @media print {
    pre > code.sourceCode { white-space: pre-wrap; }
    pre > code.sourceCode > span { text-indent: -5em; padding-left: 5em; }
    }
    pre.numberSource code
      { counter-reset: source-line 0; }
    pre.numberSource code > span
      { position: relative; left: -4em; counter-increment: source-line; }
    pre.numberSource code > span > a:first-child::before
      { content: counter(source-line);
        position: relative; left: -1em; text-align: right; vertical-align: baseline;
        border: none; display: inline-block;
        -webkit-touch-callout: none; -webkit-user-select: none;
        -khtml-user-select: none; -moz-user-select: none;
        -ms-user-select: none; user-select: none;
        padding: 0 4px; width: 4em;
        color: #aaaaaa;
      }
    pre.numberSource { margin-left: 3em; border-left: 1px solid #aaaaaa;  padding-left: 4px; }
    div.sourceCode
      {   }
    @media screen {
    pre > code.sourceCode > span > a:first-child::before { text-decoration: underline; }
    }
    code span.al { color: #ff0000; font-weight: bold; } /* Alert */
    code span.an { color: #60a0b0; font-weight: bold; font-style: italic; } /* Annotation */
    code span.at { color: #7d9029; } /* Attribute */
    code span.bn { color: #40a070; } /* BaseN */
    code span.bu { color: #008000; } /* BuiltIn */
    code span.cf { color: #007020; font-weight: bold; } /* ControlFlow */
    code span.ch { color: #4070a0; } /* Char */
    code span.cn { color: #880000; } /* Constant */
    code span.co { color: #60a0b0; font-style: italic; } /* Comment */
    code span.cv { color: #60a0b0; font-weight: bold; font-style: italic; } /* CommentVar */
    code span.do { color: #ba2121; font-style: italic; } /* Documentation */
    code span.dt { color: #902000; } /* DataType */
    code span.dv { color: #40a070; } /* DecVal */
    code span.er { color: #ff0000; font-weight: bold; } /* Error */
    code span.ex { } /* Extension */
    code span.fl { color: #40a070; } /* Float */
    code span.fu { color: #06287e; } /* Function */
    code span.im { color: #008000; font-weight: bold; } /* Import */
    code span.in { color: #60a0b0; font-weight: bold; font-style: italic; } /* Information */
    code span.kw { color: #007020; font-weight: bold; } /* Keyword */
    code span.op { color: #666666; } /* Operator */
    code span.ot { color: #007020; } /* Other */
    code span.pp { color: #bc7a00; } /* Preprocessor */
    code span.sc { color: #4070a0; } /* SpecialChar */
    code span.ss { color: #bb6688; } /* SpecialString */
    code span.st { color: #4070a0; } /* String */
    code span.va { color: #19177c; } /* Variable */
    code span.vs { color: #4070a0; } /* VerbatimString */
    code span.wa { color: #60a0b0; font-weight: bold; font-style: italic; } /* Warning */
    .display.math{display: block; text-align: center; margin: 0.5rem auto;}
  </style>
  <!--[if lt IE 9]>
    <script src="//cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv-printshiv.min.js"></script>
  <![endif]
</head> -->
<body>
<div class="cell markdown" id="kQogc4aEMXDn">
<h1 style="color:green" align="center"><b> Customer Market Segmentation</b> </h1>
</div>
<section id="about-data" class="cell markdown">
<h1><font color = "black">About Data:</font></h1>
<h3 id="objective-">Objective :</h3>
<p>Customer Segmentation is the process of dividing customers into
groups based on common characteristics so companies can market to each
group effectively and appropriately. The aim of this project is to give
stakeholders recommendations like saving plans, loans, wealth
management, etc. on target customer groups.</p>
<h3 id="link-to-dataset">Link to dataset:</h3>
<ul>
<li>Kaggle - <a
href="https://www.kaggle.com/datasets/arjunbhasin2013/ccdata"
class="uri">https://www.kaggle.com/datasets/arjunbhasin2013/ccdata</a></li>
<li>GitHub - <a
href="https://github.com/sho-das/Customer-Segmentation/blob/main/credit_card_dataset.csv"
class="uri">https://github.com/sho-das/Customer-Segmentation/blob/main/credit_card_dataset.csv</a></li>
</ul>
<h3 id="data-description-">Data Description :</h3>
<p>The sample Dataset summarizes the usage behavior of about 9000 active
credit card holders during the last 6 months. The file is at a customer
level with 18 behavioral variables.</p>
<p>Following is the Data Dictionary for customer's credit card dataset
:-</p>
<p><b> CUSTID :</b> Identification of Credit Card holder
(Categorical)<br> <b>BALANCE :</b> Balance amount left in their account
to make purchases<br> <b>BALANCEFREQUENCY :</b> How frequently the
Balance is updated, score between 0 and 1 (1 = frequently updated, 0 =
not frequently updated)<br> <b>PURCHASES :</b> Amount of purchases made
from account<br> <b>ONEOFFPURCHASES :</b> Maximum purchase amount done
in one-go<br> <b>INSTALLMENTSPURCHASES :</b> Amount of purchase done in
installment<br> <b>CASHADVANCE :</b> Cash in advance given by the
user<br> <b>PURCHASESFREQUENCY :</b> How frequently the Purchases are
being made, score between 0 and 1 (1 = frequently purchased, 0 = not
frequently purchased)<br> <b>ONEOFFPURCHASESFREQUENCY :</b> How
frequently Purchases are happening in one-go (1 = frequently purchased,
0 = not frequently purchased)<br> PURCHASESINSTALLMENTSFREQUENCY :</b>
How frequently purchases in installments are being done (1 = frequently
done, 0 = not frequently done)<br> <b>CASHADVANCEFREQUENCY :</b> How
frequently the cash in advance being paid<br> <b>CASHADVANCETRX :</b>
Number of Transactions made with "Cash in Advanced"<br> <b>PURCHASESTRX
:</b> Numbe of purchase transactions made<br> <b>CREDITLIMIT :</b> Limit
of Credit Card for user<br> <b>PAYMENTS :</b> Amount of Payment done by
user<br> <b>MINIMUM_PAYMENTS :</b> Minimum amount of payments made by
user<br> <b>PRCFULLPAYMENT :</b> Percent of full payment paid by
user<br> <b>TENURE :</b> Tenure of credit card service for user<br></p>
<h3 id="tool-and-libraries-used">Tool and Libraries Used:</h3>
<ul>
<li><strong>Tool:</strong>
<ul>
<li>Python 3.11.7</li>
</ul></li>
<li><strong>Libraries:</strong>
<ul>
<li>pandas</li>
<li>numpy</li>
<li>matplotlib.pyplot</li>
<li>seaborn</li>
<li>sklearn.preprocessing
<ul>
<li>StandardScaler</li>
</ul></li>
<li>sklearn.decomposition
<ul>
<li>PCA</li>
</ul></li>
<li>sklearn.cluster
<ul>
<li>KMeans</li>
<li>AgglomerativeClustering</li>
<li>DBSCAN</li>
<li>SpectralClustering</li>
</ul></li>
<li>sklearn.mixture
<ul>
<li>GaussianMixture</li>
</ul></li>
<li>sklearn.metrics
<ul>
<li>silhouette_samples</li>
<li>silhouette_score</li>
</ul></li>
</ul></li>
</ul>
</section>
<section id="table-of-content" class="cell markdown">
<h3><font color = "black">Table of
Content</font><a class = "anchor" id = "content"></a></h3>
<ol>
<li><a href="#import">Importing Libraries</a></li>
<li><a href="#load">Loading Dataset</a></li>
<li><a href="#eda">Exploratory Data Analysis &amp; Data
Cleaning</a></li>
<li><a href="#outliers">Outlier Detection</a></li>
<li><a href="#scale">Scaling the data</a></li>
<li><a href="#dr">Dimensionality Reduction</a></li>
<li><a href="#hyper">Hyperparameter Tuning</a></li>
<li><a href="#model">Model Building</a>
<ul>
<li><a href="#catboost">K-Means Clustering</a></li>
</ul></li>
<li><a href="#analyze">Analyzing Clustering Output</a>
<ul>
<li><a href="#outcome">Key Outcomes</a></li>
<li><a href="#analysis">Analysis of each Cluster</a></li>
</ul></li>
<li><a href="#save">Saving the Model</a></li>
</ol>
</section>
<section id="importing-libraries" class="cell markdown"
id="FvURjqA38EFW">
<h1><font color = "black">Importing
Libraries</font><a class = "anchor" id = "import"></a></h1>
</section>
<div class="cell code" data-execution_count="1" id="IV6dizi69rgG">
<div class="sourceCode" id="cb1"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb1-1"><a href="#cb1-1" aria-hidden="true" tabindex="-1"></a><span class="co"># import necessary libraries</span></span>
<span id="cb1-2"><a href="#cb1-2" aria-hidden="true" tabindex="-1"></a><span class="im">import</span> pandas <span class="im">as</span> pd</span>
<span id="cb1-3"><a href="#cb1-3" aria-hidden="true" tabindex="-1"></a><span class="im">import</span> numpy <span class="im">as</span> np</span>
<span id="cb1-4"><a href="#cb1-4" aria-hidden="true" tabindex="-1"></a><span class="im">import</span> matplotlib.pyplot <span class="im">as</span> plt</span>
<span id="cb1-5"><a href="#cb1-5" aria-hidden="true" tabindex="-1"></a><span class="im">import</span> seaborn <span class="im">as</span> sns</span>
<span id="cb1-6"><a href="#cb1-6" aria-hidden="true" tabindex="-1"></a><span class="im">from</span> sklearn.preprocessing <span class="im">import</span> StandardScaler</span>
<span id="cb1-7"><a href="#cb1-7" aria-hidden="true" tabindex="-1"></a><span class="im">from</span> sklearn.decomposition <span class="im">import</span> PCA</span>
<span id="cb1-8"><a href="#cb1-8" aria-hidden="true" tabindex="-1"></a><span class="im">from</span> sklearn.cluster <span class="im">import</span> KMeans,AgglomerativeClustering,DBSCAN,SpectralClustering</span>
<span id="cb1-9"><a href="#cb1-9" aria-hidden="true" tabindex="-1"></a><span class="im">from</span> sklearn.mixture <span class="im">import</span> GaussianMixture</span>
<span id="cb1-10"><a href="#cb1-10" aria-hidden="true" tabindex="-1"></a><span class="im">from</span> sklearn.metrics <span class="im">import</span> silhouette_samples, silhouette_score</span></code></pre></div>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="loading-dataset" class="cell markdown" id="CIQCeJdP8QAg">
<h1><font color = "black">Loading
Dataset</font><a class = "anchor" id = "load"></a></h1>
</section>
<div class="cell code" data-execution_count="2"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:223}"
id="A1aL8hILApBq" data-outputId="26f7675d-521f-42d5-ae6e-3948a5bab3c7">
<div class="sourceCode" id="cb2"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb2-1"><a href="#cb2-1" aria-hidden="true" tabindex="-1"></a><span class="co"># import the dataset</span></span>
<span id="cb2-2"><a href="#cb2-2" aria-hidden="true" tabindex="-1"></a>creditcard_df <span class="op">=</span> pd.read_csv(<span class="st">&quot;credit_card_dataset.csv&quot;</span>)</span>
<span id="cb2-3"><a href="#cb2-3" aria-hidden="true" tabindex="-1"></a>creditcard_df.head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="2">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>CUST_ID</th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>C10001</td>
      <td>40.900749</td>
      <td>0.818182</td>
      <td>95.40</td>
      <td>0.00</td>
      <td>95.4</td>
      <td>0.000000</td>
      <td>0.166667</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0</td>
      <td>2</td>
      <td>1000.0</td>
      <td>201.802084</td>
      <td>139.509787</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>1</th>
      <td>C10002</td>
      <td>3202.467416</td>
      <td>0.909091</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.0</td>
      <td>6442.945483</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.250000</td>
      <td>4</td>
      <td>0</td>
      <td>7000.0</td>
      <td>4103.032597</td>
      <td>1072.340217</td>
      <td>0.222222</td>
      <td>12</td>
    </tr>
    <tr>
      <th>2</th>
      <td>C10003</td>
      <td>2495.148862</td>
      <td>1.000000</td>
      <td>773.17</td>
      <td>773.17</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>12</td>
      <td>7500.0</td>
      <td>622.066742</td>
      <td>627.284787</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>3</th>
      <td>C10004</td>
      <td>1666.670542</td>
      <td>0.636364</td>
      <td>1499.00</td>
      <td>1499.00</td>
      <td>0.0</td>
      <td>205.788017</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>1</td>
      <td>1</td>
      <td>7500.0</td>
      <td>0.000000</td>
      <td>NaN</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>4</th>
      <td>C10005</td>
      <td>817.714335</td>
      <td>1.000000</td>
      <td>16.00</td>
      <td>16.00</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>1</td>
      <td>1200.0</td>
      <td>678.334763</td>
      <td>244.791237</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="exploratory-data-analysis--data-cleaning"
class="cell markdown" id="t227bg8p8ZeK">
<h1><font color = "black">Exploratory Data Analysis &amp; Data
Cleaning</font><a class = "anchor" id = "eda"></a></h1>
</section>
<div class="cell code" data-execution_count="3"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="x642gG55IFH4" data-outputId="2aede765-c397-4443-b1be-7725f7527b79">
<div class="sourceCode" id="cb3"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb3-1"><a href="#cb3-1" aria-hidden="true" tabindex="-1"></a>creditcard_df.shape</span></code></pre></div>
<div class="output execute_result" data-execution_count="3">
<pre><code>(8950, 18)</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="4"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="CPAXliTBApEZ" data-outputId="bc4536fa-1728-4c24-fda8-532d7f7799f1">
<div class="sourceCode" id="cb5"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb5-1"><a href="#cb5-1" aria-hidden="true" tabindex="-1"></a><span class="co"># information about the data</span></span>
<span id="cb5-2"><a href="#cb5-2" aria-hidden="true" tabindex="-1"></a>creditcard_df.info()</span></code></pre></div>
<div class="output stream stdout">
<pre><code>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 8950 entries, 0 to 8949
Data columns (total 18 columns):
 #   Column                            Non-Null Count  Dtype  
---  ------                            --------------  -----  
 0   CUST_ID                           8950 non-null   object 
 1   BALANCE                           8950 non-null   float64
 2   BALANCE_FREQUENCY                 8950 non-null   float64
 3   PURCHASES                         8950 non-null   float64
 4   ONEOFF_PURCHASES                  8950 non-null   float64
 5   INSTALLMENTS_PURCHASES            8950 non-null   float64
 6   CASH_ADVANCE                      8950 non-null   float64
 7   PURCHASES_FREQUENCY               8950 non-null   float64
 8   ONEOFF_PURCHASES_FREQUENCY        8950 non-null   float64
 9   PURCHASES_INSTALLMENTS_FREQUENCY  8950 non-null   float64
 10  CASH_ADVANCE_FREQUENCY            8950 non-null   float64
 11  CASH_ADVANCE_TRX                  8950 non-null   int64  
 12  PURCHASES_TRX                     8950 non-null   int64  
 13  CREDIT_LIMIT                      8949 non-null   float64
 14  PAYMENTS                          8950 non-null   float64
 15  MINIMUM_PAYMENTS                  8637 non-null   float64
 16  PRC_FULL_PAYMENT                  8950 non-null   float64
 17  TENURE                            8950 non-null   int64  
dtypes: float64(14), int64(3), object(1)
memory usage: 1.2+ MB
</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="5">
<div class="sourceCode" id="cb7"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb7-1"><a href="#cb7-1" aria-hidden="true" tabindex="-1"></a><span class="co"># Check the statistics summary of the dataframe</span></span>
<span id="cb7-2"><a href="#cb7-2" aria-hidden="true" tabindex="-1"></a>creditcard_df.describe()</span></code></pre></div>
<div class="output execute_result" data-execution_count="5">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
      <td>8949.000000</td>
      <td>8950.000000</td>
      <td>8637.000000</td>
      <td>8950.000000</td>
      <td>8950.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>1564.474828</td>
      <td>0.877271</td>
      <td>1003.204834</td>
      <td>592.437371</td>
      <td>411.067645</td>
      <td>978.871112</td>
      <td>0.490351</td>
      <td>0.202458</td>
      <td>0.364437</td>
      <td>0.135144</td>
      <td>3.248827</td>
      <td>14.709832</td>
      <td>4494.449450</td>
      <td>1733.143852</td>
      <td>864.206542</td>
      <td>0.153715</td>
      <td>11.517318</td>
    </tr>
    <tr>
      <th>std</th>
      <td>2081.531879</td>
      <td>0.236904</td>
      <td>2136.634782</td>
      <td>1659.887917</td>
      <td>904.338115</td>
      <td>2097.163877</td>
      <td>0.401371</td>
      <td>0.298336</td>
      <td>0.397448</td>
      <td>0.200121</td>
      <td>6.824647</td>
      <td>24.857649</td>
      <td>3638.815725</td>
      <td>2895.063757</td>
      <td>2372.446607</td>
      <td>0.292499</td>
      <td>1.338331</td>
    </tr>
    <tr>
      <th>min</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>50.000000</td>
      <td>0.000000</td>
      <td>0.019163</td>
      <td>0.000000</td>
      <td>6.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>128.281915</td>
      <td>0.888889</td>
      <td>39.635000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1600.000000</td>
      <td>383.276166</td>
      <td>169.123707</td>
      <td>0.000000</td>
      <td>12.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>873.385231</td>
      <td>1.000000</td>
      <td>361.280000</td>
      <td>38.000000</td>
      <td>89.000000</td>
      <td>0.000000</td>
      <td>0.500000</td>
      <td>0.083333</td>
      <td>0.166667</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>7.000000</td>
      <td>3000.000000</td>
      <td>856.901546</td>
      <td>312.343947</td>
      <td>0.000000</td>
      <td>12.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>2054.140036</td>
      <td>1.000000</td>
      <td>1110.130000</td>
      <td>577.405000</td>
      <td>468.637500</td>
      <td>1113.821139</td>
      <td>0.916667</td>
      <td>0.300000</td>
      <td>0.750000</td>
      <td>0.222222</td>
      <td>4.000000</td>
      <td>17.000000</td>
      <td>6500.000000</td>
      <td>1901.134317</td>
      <td>825.485459</td>
      <td>0.142857</td>
      <td>12.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>19043.138560</td>
      <td>1.000000</td>
      <td>49039.570000</td>
      <td>40761.250000</td>
      <td>22500.000000</td>
      <td>47137.211760</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.500000</td>
      <td>123.000000</td>
      <td>358.000000</td>
      <td>30000.000000</td>
      <td>50721.483360</td>
      <td>76406.207520</td>
      <td>1.000000</td>
      <td>12.000000</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell code" data-execution_count="6"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="9a6tZ053Do1L" data-outputId="11b76d55-158d-4ee7-e307-b21340c5485b">
<div class="sourceCode" id="cb8"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb8-1"><a href="#cb8-1" aria-hidden="true" tabindex="-1"></a><span class="co"># checking for Null values in data frame</span></span>
<span id="cb8-2"><a href="#cb8-2" aria-hidden="true" tabindex="-1"></a>creditcard_df.isnull().<span class="bu">sum</span>()</span></code></pre></div>
<div class="output execute_result" data-execution_count="6">
<pre><code>CUST_ID                               0
BALANCE                               0
BALANCE_FREQUENCY                     0
PURCHASES                             0
ONEOFF_PURCHASES                      0
INSTALLMENTS_PURCHASES                0
CASH_ADVANCE                          0
PURCHASES_FREQUENCY                   0
ONEOFF_PURCHASES_FREQUENCY            0
PURCHASES_INSTALLMENTS_FREQUENCY      0
CASH_ADVANCE_FREQUENCY                0
CASH_ADVANCE_TRX                      0
PURCHASES_TRX                         0
CREDIT_LIMIT                          1
PAYMENTS                              0
MINIMUM_PAYMENTS                    313
PRC_FULL_PAYMENT                      0
TENURE                                0
dtype: int64</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="7"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="168lrNY0L5m9" data-outputId="e750030f-88af-4b01-9fde-7d0a0998995e">
<div class="sourceCode" id="cb10"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb10-1"><a href="#cb10-1" aria-hidden="true" tabindex="-1"></a><span class="co"># find all columns having missing values</span></span>
<span id="cb10-2"><a href="#cb10-2" aria-hidden="true" tabindex="-1"></a>missing_var <span class="op">=</span> [var <span class="cf">for</span> var <span class="kw">in</span> creditcard_df.columns <span class="cf">if</span> creditcard_df[var].isnull().<span class="bu">sum</span>()<span class="op">&gt;</span><span class="dv">0</span>]</span>
<span id="cb10-3"><a href="#cb10-3" aria-hidden="true" tabindex="-1"></a>missing_var</span></code></pre></div>
<div class="output execute_result" data-execution_count="7">
<pre><code>[&#39;CREDIT_LIMIT&#39;, &#39;MINIMUM_PAYMENTS&#39;]</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="8" id="OItFRcH8L5yv">
<div class="sourceCode" id="cb12"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb12-1"><a href="#cb12-1" aria-hidden="true" tabindex="-1"></a><span class="co"># fill mean value in place of missing values</span></span>
<span id="cb12-2"><a href="#cb12-2" aria-hidden="true" tabindex="-1"></a>creditcard_df[<span class="st">&quot;MINIMUM_PAYMENTS&quot;</span>] <span class="op">=</span> creditcard_df[<span class="st">&quot;MINIMUM_PAYMENTS&quot;</span>].fillna(creditcard_df[<span class="st">&quot;MINIMUM_PAYMENTS&quot;</span>].mean())</span>
<span id="cb12-3"><a href="#cb12-3" aria-hidden="true" tabindex="-1"></a>creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>] <span class="op">=</span> creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>].fillna(creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>].mean())</span></code></pre></div>
</div>
<div class="cell code" data-execution_count="9"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="21VxCR_sL50m" data-outputId="0af46703-2316-4c82-de7c-5c021e51bdd9">
<div class="sourceCode" id="cb13"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb13-1"><a href="#cb13-1" aria-hidden="true" tabindex="-1"></a><span class="co"># Again check for null values</span></span>
<span id="cb13-2"><a href="#cb13-2" aria-hidden="true" tabindex="-1"></a>creditcard_df.isnull().<span class="bu">sum</span>()</span></code></pre></div>
<div class="output execute_result" data-execution_count="9">
<pre><code>CUST_ID                             0
BALANCE                             0
BALANCE_FREQUENCY                   0
PURCHASES                           0
ONEOFF_PURCHASES                    0
INSTALLMENTS_PURCHASES              0
CASH_ADVANCE                        0
PURCHASES_FREQUENCY                 0
ONEOFF_PURCHASES_FREQUENCY          0
PURCHASES_INSTALLMENTS_FREQUENCY    0
CASH_ADVANCE_FREQUENCY              0
CASH_ADVANCE_TRX                    0
PURCHASES_TRX                       0
CREDIT_LIMIT                        0
PAYMENTS                            0
MINIMUM_PAYMENTS                    0
PRC_FULL_PAYMENT                    0
TENURE                              0
dtype: int64</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="10"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="nu1nwwsXL54g" data-outputId="7191f789-0699-4e98-8932-4018f4e0973d">
<div class="sourceCode" id="cb15"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb15-1"><a href="#cb15-1" aria-hidden="true" tabindex="-1"></a><span class="co"># check duplicate entries in the dataset</span></span>
<span id="cb15-2"><a href="#cb15-2" aria-hidden="true" tabindex="-1"></a>creditcard_df.duplicated().<span class="bu">sum</span>()</span></code></pre></div>
<div class="output execute_result" data-execution_count="10">
<pre><code>0</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="11" id="P22UTnrlr-7D">
<div class="sourceCode" id="cb17"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb17-1"><a href="#cb17-1" aria-hidden="true" tabindex="-1"></a><span class="co"># drop unnecessary columns</span></span>
<span id="cb17-2"><a href="#cb17-2" aria-hidden="true" tabindex="-1"></a>creditcard_df.drop(columns<span class="op">=</span>[<span class="st">&quot;CUST_ID&quot;</span>],axis<span class="op">=</span><span class="dv">1</span>,inplace<span class="op">=</span><span class="va">True</span>)</span></code></pre></div>
</div>
<div class="cell code" data-execution_count="12"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="zLzOtHtux2d0" data-outputId="6a48af58-d3b3-4e37-9bb5-c9fcc7645d89">
<div class="sourceCode" id="cb18"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb18-1"><a href="#cb18-1" aria-hidden="true" tabindex="-1"></a>creditcard_df.columns</span></code></pre></div>
<div class="output execute_result" data-execution_count="12">
<pre><code>Index([&#39;BALANCE&#39;, &#39;BALANCE_FREQUENCY&#39;, &#39;PURCHASES&#39;, &#39;ONEOFF_PURCHASES&#39;,
       &#39;INSTALLMENTS_PURCHASES&#39;, &#39;CASH_ADVANCE&#39;, &#39;PURCHASES_FREQUENCY&#39;,
       &#39;ONEOFF_PURCHASES_FREQUENCY&#39;, &#39;PURCHASES_INSTALLMENTS_FREQUENCY&#39;,
       &#39;CASH_ADVANCE_FREQUENCY&#39;, &#39;CASH_ADVANCE_TRX&#39;, &#39;PURCHASES_TRX&#39;,
       &#39;CREDIT_LIMIT&#39;, &#39;PAYMENTS&#39;, &#39;MINIMUM_PAYMENTS&#39;, &#39;PRC_FULL_PAYMENT&#39;,
       &#39;TENURE&#39;],
      dtype=&#39;object&#39;)</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="13">
<div class="sourceCode" id="cb20"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb20-1"><a href="#cb20-1" aria-hidden="true" tabindex="-1"></a>creditcard_df.head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="13">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>40.900749</td>
      <td>0.818182</td>
      <td>95.40</td>
      <td>0.00</td>
      <td>95.4</td>
      <td>0.000000</td>
      <td>0.166667</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0</td>
      <td>2</td>
      <td>1000.0</td>
      <td>201.802084</td>
      <td>139.509787</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>1</th>
      <td>3202.467416</td>
      <td>0.909091</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.0</td>
      <td>6442.945483</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.250000</td>
      <td>4</td>
      <td>0</td>
      <td>7000.0</td>
      <td>4103.032597</td>
      <td>1072.340217</td>
      <td>0.222222</td>
      <td>12</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2495.148862</td>
      <td>1.000000</td>
      <td>773.17</td>
      <td>773.17</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>12</td>
      <td>7500.0</td>
      <td>622.066742</td>
      <td>627.284787</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1666.670542</td>
      <td>0.636364</td>
      <td>1499.00</td>
      <td>1499.00</td>
      <td>0.0</td>
      <td>205.788017</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>1</td>
      <td>1</td>
      <td>7500.0</td>
      <td>0.000000</td>
      <td>864.206542</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>4</th>
      <td>817.714335</td>
      <td>1.000000</td>
      <td>16.00</td>
      <td>16.00</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>1</td>
      <td>1200.0</td>
      <td>678.334763</td>
      <td>244.791237</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="outlier-detection" class="cell markdown" id="nscbI_ftEmSB">
<h1><font color = "black">Outlier
Detection</font><a class = "anchor" id = "outliers"></a></h1>
</section>
<div class="cell code" data-execution_count="14"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="bVKUswoJ8bnE" data-outputId="fa4452ec-80a6-4ba6-8198-6bebc8f6f3ec">
<div class="sourceCode" id="cb21"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb21-1"><a href="#cb21-1" aria-hidden="true" tabindex="-1"></a><span class="co"># find outlier in all columns</span></span>
<span id="cb21-2"><a href="#cb21-2" aria-hidden="true" tabindex="-1"></a><span class="cf">for</span> i <span class="kw">in</span> creditcard_df.select_dtypes(include<span class="op">=</span>[<span class="st">&#39;float64&#39;</span>,<span class="st">&#39;int64&#39;</span>]).columns:</span>
<span id="cb21-3"><a href="#cb21-3" aria-hidden="true" tabindex="-1"></a>  max_thresold <span class="op">=</span> creditcard_df[i].quantile(<span class="fl">0.95</span>)</span>
<span id="cb21-4"><a href="#cb21-4" aria-hidden="true" tabindex="-1"></a>  min_thresold <span class="op">=</span> creditcard_df[i].quantile(<span class="fl">0.05</span>)</span>
<span id="cb21-5"><a href="#cb21-5" aria-hidden="true" tabindex="-1"></a>  creditcard_df_no_outlier <span class="op">=</span> creditcard_df[(creditcard_df[i] <span class="op">&lt;</span> max_thresold) <span class="op">&amp;</span> (creditcard_df[i] <span class="op">&gt;</span> min_thresold)].shape</span>
<span id="cb21-6"><a href="#cb21-6" aria-hidden="true" tabindex="-1"></a>  <span class="bu">print</span>(<span class="st">&quot; outlier in &quot;</span>,i,<span class="st">&quot;is&quot;</span> ,<span class="bu">int</span>(((creditcard_df.shape[<span class="dv">0</span>]<span class="op">-</span>creditcard_df_no_outlier[<span class="dv">0</span>])<span class="op">/</span>creditcard_df.shape[<span class="dv">0</span>])<span class="op">*</span><span class="dv">100</span>),<span class="st">&quot;%&quot;</span>)</span></code></pre></div>
<div class="output stream stdout">
<pre><code> outlier in  BALANCE is 10 %
 outlier in  BALANCE_FREQUENCY is 75 %
 outlier in  PURCHASES is 27 %
 outlier in  ONEOFF_PURCHASES is 53 %
 outlier in  INSTALLMENTS_PURCHASES is 48 %
 outlier in  CASH_ADVANCE is 56 %
 outlier in  PURCHASES_FREQUENCY is 47 %
 outlier in  ONEOFF_PURCHASES_FREQUENCY is 53 %
 outlier in  PURCHASES_INSTALLMENTS_FREQUENCY is 58 %
 outlier in  CASH_ADVANCE_FREQUENCY is 57 %
 outlier in  CASH_ADVANCE_TRX is 56 %
 outlier in  PURCHASES_TRX is 27 %
 outlier in  CREDIT_LIMIT is 14 %
 outlier in  PAYMENTS is 10 %
 outlier in  MINIMUM_PAYMENTS is 10 %
 outlier in  PRC_FULL_PAYMENT is 71 %
 outlier in  TENURE is 91 %
</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="15" id="3d-9p2P5tYVR">
<div class="sourceCode" id="cb23"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb23-1"><a href="#cb23-1" aria-hidden="true" tabindex="-1"></a><span class="co"># remove outliers from columns having nearly 10% outlier</span></span>
<span id="cb23-2"><a href="#cb23-2" aria-hidden="true" tabindex="-1"></a>max_thresold_BALANCE <span class="op">=</span> creditcard_df[<span class="st">&quot;BALANCE&quot;</span>].quantile(<span class="fl">0.95</span>)</span>
<span id="cb23-3"><a href="#cb23-3" aria-hidden="true" tabindex="-1"></a>min_thresold_BALANCE <span class="op">=</span> creditcard_df[<span class="st">&quot;BALANCE&quot;</span>].quantile(<span class="fl">0.05</span>)</span>
<span id="cb23-4"><a href="#cb23-4" aria-hidden="true" tabindex="-1"></a>max_thresold_CREDIT_LIMIT <span class="op">=</span> creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>].quantile(<span class="fl">0.95</span>)</span>
<span id="cb23-5"><a href="#cb23-5" aria-hidden="true" tabindex="-1"></a>min_thresold_CREDIT_LIMIT <span class="op">=</span> creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>].quantile(<span class="fl">0.05</span>)</span>
<span id="cb23-6"><a href="#cb23-6" aria-hidden="true" tabindex="-1"></a>max_thresold_PAYMENTS <span class="op">=</span> creditcard_df[<span class="st">&quot;PAYMENTS&quot;</span>].quantile(<span class="fl">0.95</span>)</span>
<span id="cb23-7"><a href="#cb23-7" aria-hidden="true" tabindex="-1"></a>min_thresold_PAYMENTS <span class="op">=</span> creditcard_df[<span class="st">&quot;PAYMENTS&quot;</span>].quantile(<span class="fl">0.05</span>)</span>
<span id="cb23-8"><a href="#cb23-8" aria-hidden="true" tabindex="-1"></a>creditcard_df_no_outlier <span class="op">=</span> creditcard_df[(creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>] <span class="op">&lt;</span> max_thresold_CREDIT_LIMIT) <span class="op">&amp;</span> (creditcard_df[<span class="st">&quot;CREDIT_LIMIT&quot;</span>] <span class="op">&gt;</span> min_thresold_CREDIT_LIMIT) <span class="op">&amp;</span> (creditcard_df[<span class="st">&quot;BALANCE&quot;</span>] <span class="op">&lt;</span> max_thresold_BALANCE) <span class="op">&amp;</span> (creditcard_df[<span class="st">&quot;BALANCE&quot;</span>] <span class="op">&gt;</span> min_thresold_BALANCE) <span class="op">&amp;</span>  (creditcard_df[<span class="st">&quot;PAYMENTS&quot;</span>] <span class="op">&lt;</span> max_thresold_PAYMENTS) <span class="op">&amp;</span> (creditcard_df[<span class="st">&quot;PAYMENTS&quot;</span>] <span class="op">&gt;</span> min_thresold_PAYMENTS)]</span></code></pre></div>
</div>
<div class="cell code" data-execution_count="16"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:223}"
id="8tVH1zV22z3T" data-outputId="862bc890-8094-4f18-f0a1-7ad6c66b356d">
<div class="sourceCode" id="cb24"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb24-1"><a href="#cb24-1" aria-hidden="true" tabindex="-1"></a><span class="co"># DataFrame having no outlier</span></span>
<span id="cb24-2"><a href="#cb24-2" aria-hidden="true" tabindex="-1"></a>creditcard_df_no_outlier.head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="16">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>3202.467416</td>
      <td>0.909091</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>6442.945483</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.25</td>
      <td>4</td>
      <td>0</td>
      <td>7000.0</td>
      <td>4103.032597</td>
      <td>1072.340217</td>
      <td>0.222222</td>
      <td>12</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2495.148862</td>
      <td>1.000000</td>
      <td>773.17</td>
      <td>773.17</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0</td>
      <td>12</td>
      <td>7500.0</td>
      <td>622.066742</td>
      <td>627.284787</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>4</th>
      <td>817.714335</td>
      <td>1.000000</td>
      <td>16.00</td>
      <td>16.00</td>
      <td>0.00</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.00</td>
      <td>0</td>
      <td>1</td>
      <td>1200.0</td>
      <td>678.334763</td>
      <td>244.791237</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1809.828751</td>
      <td>1.000000</td>
      <td>1333.28</td>
      <td>0.00</td>
      <td>1333.28</td>
      <td>0.000000</td>
      <td>0.666667</td>
      <td>0.000000</td>
      <td>0.583333</td>
      <td>0.00</td>
      <td>0</td>
      <td>8</td>
      <td>1800.0</td>
      <td>1400.057770</td>
      <td>2407.246035</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1823.652743</td>
      <td>1.000000</td>
      <td>436.20</td>
      <td>0.00</td>
      <td>436.20</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>0.00</td>
      <td>0</td>
      <td>12</td>
      <td>2300.0</td>
      <td>679.065082</td>
      <td>532.033990</td>
      <td>0.000000</td>
      <td>12</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell code" data-execution_count="17">
<div class="sourceCode" id="cb25"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb25-1"><a href="#cb25-1" aria-hidden="true" tabindex="-1"></a>creditcard_df_no_outlier.shape</span></code></pre></div>
<div class="output execute_result" data-execution_count="17">
<pre><code>(6466, 17)</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="18"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:738}"
id="hinJyKEnr_BS" data-outputId="ef4cc0e9-7df0-4421-ac60-ce170408a504">
<div class="sourceCode" id="cb27"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb27-1"><a href="#cb27-1" aria-hidden="true" tabindex="-1"></a><span class="co"># correlation matrix of DataFrame</span></span>
<span id="cb27-2"><a href="#cb27-2" aria-hidden="true" tabindex="-1"></a>plt.figure(figsize<span class="op">=</span>(<span class="dv">20</span>,<span class="dv">10</span>))</span>
<span id="cb27-3"><a href="#cb27-3" aria-hidden="true" tabindex="-1"></a>corn<span class="op">=</span>creditcard_df_no_outlier.corr()</span>
<span id="cb27-4"><a href="#cb27-4" aria-hidden="true" tabindex="-1"></a>sns.heatmap(corn,annot<span class="op">=</span><span class="va">True</span>,cmap<span class="op">=</span><span class="st">&quot;BuPu&quot;</span>,fmt<span class="op">=</span><span class="st">&#39;.2f&#39;</span>)</span></code></pre></div>
<div class="output execute_result" data-execution_count="18">
<pre><code>&lt;Axes: &gt;</code></pre>
</div>
<div class="output display_data">
<p><img
src="https://github.com/sho-das/Customer-Segmentation/blob/main/images/8d5de2617ea3b32f38535b889dc4ebfeaa5a8a5a.png" /></p>
</div>
</div>
<section id="observations" class="cell markdown">
<h6>Observations:</h6>
<ol>
<li>"PURCHASES" and "ONEOFF_PURCHASES" -- 0.86</li>
<li>"PURCHASES_FREQUENCY" and 'PURCHASES_INSTALLMENT_FREQUENCY'
--0.85</li>
<li>"CASH_ADVANCE_TRX" and "CASH_ADVANCE_FREQUENCY" --0.81</li>
</ol>
</section>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="scaling-the-data" class="cell markdown">
<h1><font color = "black">Scaling the
data</font><a class = "anchor" id = "scale"></a></h1>
</section>
<div class="cell markdown">
<p>The next step is to scale our values to give them all equal
importance. Scaling is also important from a clustering perspective as
the distance between points affects the way clusters are formed.</p>
<p>Using the StandardScaler, we transform our dataframe into the
following numpy arrays</p>
</div>
<div class="cell code" data-execution_count="19" id="S_Jyux8tr_Ds">
<div class="sourceCode" id="cb29"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb29-1"><a href="#cb29-1" aria-hidden="true" tabindex="-1"></a><span class="co"># scale the DataFrame</span></span>
<span id="cb29-2"><a href="#cb29-2" aria-hidden="true" tabindex="-1"></a>scalar<span class="op">=</span>StandardScaler()</span>
<span id="cb29-3"><a href="#cb29-3" aria-hidden="true" tabindex="-1"></a>creditcard_scaled_df <span class="op">=</span> scalar.fit_transform(creditcard_df_no_outlier)</span></code></pre></div>
</div>
<div class="cell code" data-execution_count="20">
<div class="sourceCode" id="cb30"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb30-1"><a href="#cb30-1" aria-hidden="true" tabindex="-1"></a>creditcard_scaled_df</span></code></pre></div>
<div class="output execute_result" data-execution_count="20">
<pre><code>array([[ 1.35958568, -0.02715353, -0.71136663, ...,  0.18339488,
         0.24802861,  0.33969475],
       [ 0.84268315,  0.48108734, -0.05912009, ..., -0.04878463,
        -0.51957586,  0.33969475],
       [-0.38317207,  0.48108734, -0.69786902, ..., -0.24832644,
        -0.51957586,  0.33969475],
       ...,
       [-0.94653953, -0.45069038, -0.51244565, ..., -0.32934159,
         1.783241  , -4.58327778],
       [-0.96594456, -0.45069038, -0.61814878, ..., -0.34163245,
         1.20753592, -4.58327778],
       [-0.92315108, -2.31424023, -0.71136663, ..., -0.36464695,
         0.63183085, -4.58327778]])</code></pre>
</div>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="dimensionality-reduction" class="cell markdown"
id="xGnQd2sZLFXL">
<h1><font color = "black">Dimensionality
Reduction</font><a class = "anchor" id = "dr"></a></h1>
</section>
<div class="cell markdown">
<ul>
<li><p>Dimensionality reduction is a technique used to reduce the number
of features in a dataset while retaining as much of the important
information as possible.</p></li>
<li><p>In other words, it is a process of transforming high-dimensional
data into a lower-dimensional space that still preserves the essence of
the original data.</p></li>
<li><p>This can be done for a variety of reasons, such as to reduce the
complexity of a model, to reduce the storage space, to improve the
performance of a learning algorithm, or to make it easier to visualize
the data.</p></li>
<li><p>There are several techniques for dimensionality reduction
including:</p>
<ul>
<li>principal component analysis (PCA),</li>
<li>singular value decomposition (SVD),</li>
<li>linear discriminant analysis (LDA).</li>
</ul></li>
</ul>
<p>Each technique uses a different method to project the data onto a
lower-dimensional space while preserving important information.</p>
</div>
<div class="cell code" data-execution_count="21"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:203}"
id="M6GMphxjqWGJ" data-outputId="075c34d0-cb62-4ced-9643-10f03a9c51e0">
<div class="sourceCode" id="cb32"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb32-1"><a href="#cb32-1" aria-hidden="true" tabindex="-1"></a><span class="co"># convert the DataFrame into 2D DataFrame for visualization</span></span>
<span id="cb32-2"><a href="#cb32-2" aria-hidden="true" tabindex="-1"></a>pca <span class="op">=</span> PCA(n_components<span class="op">=</span><span class="dv">2</span>)</span>
<span id="cb32-3"><a href="#cb32-3" aria-hidden="true" tabindex="-1"></a>principal_comp <span class="op">=</span> pca.fit_transform(creditcard_scaled_df)</span>
<span id="cb32-4"><a href="#cb32-4" aria-hidden="true" tabindex="-1"></a>pca_df <span class="op">=</span> pd.DataFrame(data<span class="op">=</span>principal_comp,columns<span class="op">=</span>[<span class="st">&quot;pca1&quot;</span>,<span class="st">&quot;pca2&quot;</span>])</span>
<span id="cb32-5"><a href="#cb32-5" aria-hidden="true" tabindex="-1"></a>pca_df.head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="21">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>pca1</th>
      <th>pca2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>-2.286555</td>
      <td>3.003828</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1.134715</td>
      <td>0.431969</td>
    </tr>
    <tr>
      <th>2</th>
      <td>-1.458103</td>
      <td>-1.493204</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0.740689</td>
      <td>-0.539416</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0.648374</td>
      <td>-1.077139</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="hyperparameter-tuning" class="cell markdown"
id="WQF4hlEsuprz">
<h1><font color = "black">Hyperparameter
Tuning</font><a class = "anchor" id = "hyper"></a></h1>
</section>
<div class="cell code" data-execution_count="22"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:301}"
id="MtmR-6zBr_Il" data-outputId="632d60e0-b461-4d03-87d5-5547498969db">
<div class="sourceCode" id="cb33"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb33-1"><a href="#cb33-1" aria-hidden="true" tabindex="-1"></a><span class="co"># find &#39;k&#39; value by Elbow Method</span></span>
<span id="cb33-2"><a href="#cb33-2" aria-hidden="true" tabindex="-1"></a>inertia <span class="op">=</span> []</span>
<span id="cb33-3"><a href="#cb33-3" aria-hidden="true" tabindex="-1"></a>range_val <span class="op">=</span> <span class="bu">range</span>(<span class="dv">1</span>,<span class="dv">15</span>)</span>
<span id="cb33-4"><a href="#cb33-4" aria-hidden="true" tabindex="-1"></a><span class="cf">for</span> i <span class="kw">in</span> range_val:</span>
<span id="cb33-5"><a href="#cb33-5" aria-hidden="true" tabindex="-1"></a>  kmean <span class="op">=</span> KMeans(n_clusters<span class="op">=</span>i)</span>
<span id="cb33-6"><a href="#cb33-6" aria-hidden="true" tabindex="-1"></a>  kmean.fit_predict(pd.DataFrame(creditcard_scaled_df))</span>
<span id="cb33-7"><a href="#cb33-7" aria-hidden="true" tabindex="-1"></a>  inertia.append(kmean.inertia_)</span>
<span id="cb33-8"><a href="#cb33-8" aria-hidden="true" tabindex="-1"></a>plt.plot(range_val,inertia,<span class="st">&#39;bx-&#39;</span>)</span>
<span id="cb33-9"><a href="#cb33-9" aria-hidden="true" tabindex="-1"></a>plt.xlabel(<span class="st">&#39;Values of K&#39;</span>) </span>
<span id="cb33-10"><a href="#cb33-10" aria-hidden="true" tabindex="-1"></a>plt.ylabel(<span class="st">&#39;Inertia&#39;</span>) </span>
<span id="cb33-11"><a href="#cb33-11" aria-hidden="true" tabindex="-1"></a>plt.title(<span class="st">&#39;The Elbow Method using Inertia&#39;</span>) </span>
<span id="cb33-12"><a href="#cb33-12" aria-hidden="true" tabindex="-1"></a>plt.show()</span></code></pre></div>
<div class="output stream stderr">
<pre><code>C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
</code></pre>
</div>
<div class="output display_data">
<p><img
src="https://github.com/sho-das/Customer-Segmentation/blob/main/images/e42e18e3359df3d61ee6fe2fe60ce822729beb54.png" /></p>
</div>
</div>
<div class="cell markdown">
<p>From this plot, 4th cluster seems to be the elbow of the curve.
However, the values does not reduce to linearly until 8th cluster, so we
may consider using 8 clusters in this case.</p>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="model-building" class="cell markdown" id="h75MkXAwI7zg">
<h1><font color = "black">Model
Building</font><a class = "anchor" id = "model"></a></h1>
</section>
<section id="k-means-clustering" class="cell markdown"
id="exJLE2rTtxIe">
<h2><font color = "black">K-Means
Clustering</font><a class = "anchor" id = "kmeans"></a></h2>
</section>
<div class="cell code" data-execution_count="23">
<div class="sourceCode" id="cb35"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb35-1"><a href="#cb35-1" aria-hidden="true" tabindex="-1"></a><span class="co"># apply kmeans algorithm</span></span>
<span id="cb35-2"><a href="#cb35-2" aria-hidden="true" tabindex="-1"></a>kmeans_model<span class="op">=</span>KMeans(<span class="dv">4</span>)</span>
<span id="cb35-3"><a href="#cb35-3" aria-hidden="true" tabindex="-1"></a>kmeans_model.fit_predict(creditcard_scaled_df)</span>
<span id="cb35-4"><a href="#cb35-4" aria-hidden="true" tabindex="-1"></a>pca_df_kmeans<span class="op">=</span> pd.concat([pca_df,pd.DataFrame({<span class="st">&#39;cluster&#39;</span>:kmeans_model.labels_})],axis<span class="op">=</span><span class="dv">1</span>)</span></code></pre></div>
<div class="output stream stderr">
<pre><code>C:\Users\hp\AppData\Local\Programs\Python\Python311\Lib\site-packages\sklearn\cluster\_kmeans.py:870: FutureWarning: The default value of `n_init` will change from 10 to &#39;auto&#39; in 1.4. Set the value of `n_init` explicitly to suppress the warning
  warnings.warn(
</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="24"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:518}"
id="l2Txeh9g3EAG" data-outputId="344a6623-c01f-4870-f026-1e1c7826292c">
<div class="sourceCode" id="cb37"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb37-1"><a href="#cb37-1" aria-hidden="true" tabindex="-1"></a><span class="co"># visualize the clustered dataframe</span></span>
<span id="cb37-2"><a href="#cb37-2" aria-hidden="true" tabindex="-1"></a><span class="co"># Scatter Plot</span></span>
<span id="cb37-3"><a href="#cb37-3" aria-hidden="true" tabindex="-1"></a>plt.figure(figsize<span class="op">=</span>(<span class="dv">8</span>,<span class="dv">8</span>))</span>
<span id="cb37-4"><a href="#cb37-4" aria-hidden="true" tabindex="-1"></a><span class="co">#palette=[&#39;dodgerblue&#39;,&#39;red&#39;,&#39;green&#39;,&#39;blue&#39;,&#39;black&#39;,&#39;pink&#39;,&#39;gray&#39;,&#39;purple&#39;,&#39;coolwarm&#39;]</span></span>
<span id="cb37-5"><a href="#cb37-5" aria-hidden="true" tabindex="-1"></a>ax<span class="op">=</span>sns.scatterplot(x<span class="op">=</span><span class="st">&quot;pca1&quot;</span>,y<span class="op">=</span><span class="st">&quot;pca2&quot;</span>,hue<span class="op">=</span><span class="st">&quot;cluster&quot;</span>,data<span class="op">=</span>pca_df_kmeans,palette<span class="op">=</span>[<span class="st">&#39;red&#39;</span>,<span class="st">&#39;green&#39;</span>,<span class="st">&#39;blue&#39;</span>,<span class="st">&#39;black&#39;</span>])</span>
<span id="cb37-6"><a href="#cb37-6" aria-hidden="true" tabindex="-1"></a>plt.title(<span class="st">&quot;Clustering using K-Means Algorithm&quot;</span>)</span>
<span id="cb37-7"><a href="#cb37-7" aria-hidden="true" tabindex="-1"></a>plt.show()</span></code></pre></div>
<div class="output display_data">
<p><img
src="https://github.com/sho-das/Customer-Segmentation/blob/main/images/ee30bef36179749dd2dea76e64353c4dfae8fa9d.png" /></p>
</div>
</div>
<div class="cell markdown">
<p><a href="#content">🔝</a></p>
</div>
<section id="analyzing-clustering-output" class="cell markdown"
id="OH_HCsgJgwXs">
<h1><font color = "black">Analyzing Clustering
Output</font><a class = "anchor" id = "analyze"></a></h1>
</section>
<div class="cell markdown" id="gxv4lEA7O4Hq">
<p>We've used K-Means model for clustering in this dataset.</p>
</div>
<div class="cell code" data-execution_count="25">
<div class="sourceCode" id="cb38"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb38-1"><a href="#cb38-1" aria-hidden="true" tabindex="-1"></a>kmeans_model.cluster_centers_.shape</span></code></pre></div>
<div class="output execute_result" data-execution_count="25">
<pre><code>(4, 17)</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="26" id="JPnCI9agqV5y">
<div class="sourceCode" id="cb40"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb40-1"><a href="#cb40-1" aria-hidden="true" tabindex="-1"></a><span class="co"># find all cluster centers</span></span>
<span id="cb40-2"><a href="#cb40-2" aria-hidden="true" tabindex="-1"></a>cluster_centers <span class="op">=</span> pd.DataFrame(data<span class="op">=</span>kmeans_model.cluster_centers_,columns<span class="op">=</span>[creditcard_df.columns])</span>
<span id="cb40-3"><a href="#cb40-3" aria-hidden="true" tabindex="-1"></a><span class="co"># inverse transfor the data</span></span>
<span id="cb40-4"><a href="#cb40-4" aria-hidden="true" tabindex="-1"></a>cluster_centers <span class="op">=</span> scalar.inverse_transform(cluster_centers)</span>
<span id="cb40-5"><a href="#cb40-5" aria-hidden="true" tabindex="-1"></a>cluster_centers <span class="op">=</span> pd.DataFrame(data<span class="op">=</span>cluster_centers,columns<span class="op">=</span>[creditcard_df.columns])</span>
<span id="cb40-6"><a href="#cb40-6" aria-hidden="true" tabindex="-1"></a>cluster_centers</span></code></pre></div>
<div class="output execute_result" data-execution_count="26">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2883.331725</td>
      <td>0.957727</td>
      <td>311.733629</td>
      <td>206.334852</td>
      <td>105.433018</td>
      <td>3138.561602</td>
      <td>0.235644</td>
      <td>0.116352</td>
      <td>0.135821</td>
      <td>0.458565</td>
      <td>12.202170</td>
      <td>5.112426</td>
      <td>5107.215648</td>
      <td>1856.682016</td>
      <td>1251.200337</td>
      <td>0.031366</td>
      <td>11.156805</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1575.657597</td>
      <td>0.975533</td>
      <td>3393.301509</td>
      <td>2197.577316</td>
      <td>1196.590681</td>
      <td>294.622618</td>
      <td>0.923300</td>
      <td>0.676218</td>
      <td>0.686154</td>
      <td>0.053737</td>
      <td>1.073431</td>
      <td>49.429907</td>
      <td>6076.368491</td>
      <td>2849.429760</td>
      <td>736.837829</td>
      <td>0.268146</td>
      <td>11.869159</td>
    </tr>
    <tr>
      <th>2</th>
      <td>750.736440</td>
      <td>0.936642</td>
      <td>896.961919</td>
      <td>309.143975</td>
      <td>588.108933</td>
      <td>154.390396</td>
      <td>0.857646</td>
      <td>0.220664</td>
      <td>0.705934</td>
      <td>0.033873</td>
      <td>0.598140</td>
      <td>18.399902</td>
      <td>3895.678048</td>
      <td>1039.543663</td>
      <td>594.155004</td>
      <td>0.282098</td>
      <td>11.724425</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1142.858409</td>
      <td>0.862488</td>
      <td>286.573297</td>
      <td>236.849684</td>
      <td>49.994545</td>
      <td>505.650921</td>
      <td>0.174426</td>
      <td>0.102639</td>
      <td>0.070199</td>
      <td>0.106460</td>
      <td>1.861278</td>
      <td>3.170677</td>
      <td>3191.923559</td>
      <td>899.686626</td>
      <td>611.358225</td>
      <td>0.061514</td>
      <td>11.563534</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<div class="cell code" data-execution_count="27" id="lWLN4UnpqWB_">
<div class="sourceCode" id="cb41"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb41-1"><a href="#cb41-1" aria-hidden="true" tabindex="-1"></a><span class="co"># create a column as &quot;cluster&quot; &amp; store the respective cluster name that they belongs to</span></span>
<span id="cb41-2"><a href="#cb41-2" aria-hidden="true" tabindex="-1"></a>creditcard_cluster_df <span class="op">=</span> pd.concat([creditcard_df,pd.DataFrame({<span class="st">&#39;cluster&#39;</span>:kmeans_model.labels_})],axis<span class="op">=</span><span class="dv">1</span>)</span>
<span id="cb41-3"><a href="#cb41-3" aria-hidden="true" tabindex="-1"></a>creditcard_cluster_df.head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="27">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>40.900749</td>
      <td>0.818182</td>
      <td>95.40</td>
      <td>0.00</td>
      <td>95.4</td>
      <td>0.000000</td>
      <td>0.166667</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0</td>
      <td>2</td>
      <td>1000.0</td>
      <td>201.802084</td>
      <td>139.509787</td>
      <td>0.000000</td>
      <td>12</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>3202.467416</td>
      <td>0.909091</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.0</td>
      <td>6442.945483</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.250000</td>
      <td>4</td>
      <td>0</td>
      <td>7000.0</td>
      <td>4103.032597</td>
      <td>1072.340217</td>
      <td>0.222222</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2495.148862</td>
      <td>1.000000</td>
      <td>773.17</td>
      <td>773.17</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>12</td>
      <td>7500.0</td>
      <td>622.066742</td>
      <td>627.284787</td>
      <td>0.000000</td>
      <td>12</td>
      <td>3.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1666.670542</td>
      <td>0.636364</td>
      <td>1499.00</td>
      <td>1499.00</td>
      <td>0.0</td>
      <td>205.788017</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>1</td>
      <td>1</td>
      <td>7500.0</td>
      <td>0.000000</td>
      <td>864.206542</td>
      <td>0.000000</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>817.714335</td>
      <td>1.000000</td>
      <td>16.00</td>
      <td>16.00</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.083333</td>
      <td>0.083333</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>1</td>
      <td>1200.0</td>
      <td>678.334763</td>
      <td>244.791237</td>
      <td>0.000000</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<section id="key-outcomes" class="cell markdown">
<h2><font color = "black">Key
Outcomes</font><a class = "anchor" id = "outcome"></a></h2>
</section>
<div class="cell markdown">
<p>There are 4 clusters (segments)- each clusters are shown below in
detail:</p>
<ul>
<li><p>First Customers cluster (Transactors): Those are customers who
pay least amount of interest charges and careful with their money,
Cluster with lowest balance (104 Dollar) and cash advance (303 Dollar),
Percentage of full payment = 23%</p></li>
<li><p>Second customers cluster (revolvers) who use credit card as a
loan (most lucrative sector): highest balance (5000 Dollar) and cash
advance (5000 Dollar), low purchase frequency, high cash advance
frequency (0.5), high cash advance transactions (16) and low percentage
of full payment (3%)</p></li>
<li><p>Third customer cluster (VIP/Prime): high credit limit 16K Dollar
and highest percentage of full payment, target for increase credit limit
and increase spending habits</p></li>
<li><p>Fourth customer cluster (low tenure): these are customers with
low tenure (7 years), low balance</p></li>
</ul>
</div>
<section id="analysis-of-each-cluster" class="cell markdown"
id="H6dmahpojNBK">
<h2><font color = "black">Analysis of each
Cluster</font><a class = "anchor" id = "analysis"></a></h2>
</section>
<section id="cluster---1" class="cell markdown" id="K0ucdv9KjgTv">
<h5>Cluster - 1</h5>
</section>
<div class="cell code" data-execution_count="30"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:223}"
id="OgxDkByUhEZE" data-outputId="ac4aea4a-c0a5-4eb8-8a4c-90599af1c4cd">
<div class="sourceCode" id="cb42"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb42-1"><a href="#cb42-1" aria-hidden="true" tabindex="-1"></a>cluster_1_df <span class="op">=</span> creditcard_cluster_df[creditcard_cluster_df[<span class="st">&quot;cluster&quot;</span>]<span class="op">==</span><span class="dv">0</span>]</span>
<span id="cb42-2"><a href="#cb42-2" aria-hidden="true" tabindex="-1"></a>cluster_1_df.sort_values(by<span class="op">=</span>[<span class="st">&#39;BALANCE&#39;</span>], ascending<span class="op">=</span><span class="va">False</span>).head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="30">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2361</th>
      <td>15532.33972</td>
      <td>1.0</td>
      <td>1168.75</td>
      <td>0.0</td>
      <td>1168.75</td>
      <td>3183.037625</td>
      <td>0.916667</td>
      <td>0.000000</td>
      <td>0.916667</td>
      <td>0.250000</td>
      <td>5</td>
      <td>11</td>
      <td>16500.0</td>
      <td>3906.738592</td>
      <td>3379.593046</td>
      <td>0.0</td>
      <td>12</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>124</th>
      <td>14224.11541</td>
      <td>1.0</td>
      <td>0.00</td>
      <td>0.0</td>
      <td>0.00</td>
      <td>4614.427403</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.333333</td>
      <td>9</td>
      <td>0</td>
      <td>19000.0</td>
      <td>3066.614272</td>
      <td>3406.258999</td>
      <td>0.0</td>
      <td>12</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>4089</th>
      <td>13968.47957</td>
      <td>1.0</td>
      <td>281.71</td>
      <td>8.9</td>
      <td>272.81</td>
      <td>2710.679764</td>
      <td>0.416667</td>
      <td>0.083333</td>
      <td>0.333333</td>
      <td>0.666667</td>
      <td>12</td>
      <td>9</td>
      <td>18500.0</td>
      <td>3464.441992</td>
      <td>3360.086085</td>
      <td>0.0</td>
      <td>12</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>723</th>
      <td>13774.74154</td>
      <td>1.0</td>
      <td>404.24</td>
      <td>0.0</td>
      <td>404.24</td>
      <td>3369.474535</td>
      <td>0.250000</td>
      <td>0.000000</td>
      <td>0.250000</td>
      <td>0.500000</td>
      <td>7</td>
      <td>3</td>
      <td>14500.0</td>
      <td>3167.870886</td>
      <td>3533.464800</td>
      <td>0.0</td>
      <td>12</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>380</th>
      <td>12474.72954</td>
      <td>1.0</td>
      <td>136.88</td>
      <td>0.0</td>
      <td>136.88</td>
      <td>515.147607</td>
      <td>0.166667</td>
      <td>0.000000</td>
      <td>0.166667</td>
      <td>0.166667</td>
      <td>2</td>
      <td>2</td>
      <td>14000.0</td>
      <td>3519.008859</td>
      <td>3430.627754</td>
      <td>0.0</td>
      <td>12</td>
      <td>0.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<section id="cluster---2" class="cell markdown" id="o8i0L9Sgk_JG">
<h5>Cluster - 2</h5>
</section>
<div class="cell code" data-execution_count="29"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:223}"
id="g8gZ0SU1jRrf" data-outputId="927e77f9-3f35-4dfa-a3b1-fae9a1dbb3c4">
<div class="sourceCode" id="cb43"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb43-1"><a href="#cb43-1" aria-hidden="true" tabindex="-1"></a>cluster_2_df <span class="op">=</span> creditcard_cluster_df[creditcard_cluster_df[<span class="st">&quot;cluster&quot;</span>]<span class="op">==</span><span class="dv">1</span>]</span>
<span id="cb43-2"><a href="#cb43-2" aria-hidden="true" tabindex="-1"></a>cluster_2_df.sort_values(by<span class="op">=</span>[<span class="st">&#39;BALANCE&#39;</span>], ascending<span class="op">=</span><span class="va">False</span>).head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="29">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>501</th>
      <td>13479.28821</td>
      <td>1.0</td>
      <td>41050.4</td>
      <td>40624.06</td>
      <td>426.34</td>
      <td>0.000000</td>
      <td>0.833333</td>
      <td>0.666667</td>
      <td>0.416667</td>
      <td>0.000000</td>
      <td>0</td>
      <td>157</td>
      <td>17000.0</td>
      <td>36066.750680</td>
      <td>15914.484620</td>
      <td>0.083333</td>
      <td>12</td>
      <td>1.0</td>
    </tr>
    <tr>
      <th>495</th>
      <td>12478.17286</td>
      <td>1.0</td>
      <td>174.0</td>
      <td>174.00</td>
      <td>0.00</td>
      <td>3269.418821</td>
      <td>0.250000</td>
      <td>0.250000</td>
      <td>0.000000</td>
      <td>0.666667</td>
      <td>21</td>
      <td>3</td>
      <td>14000.0</td>
      <td>3251.190662</td>
      <td>3872.099498</td>
      <td>0.000000</td>
      <td>12</td>
      <td>1.0</td>
    </tr>
    <tr>
      <th>866</th>
      <td>11654.55492</td>
      <td>1.0</td>
      <td>463.0</td>
      <td>74.00</td>
      <td>389.00</td>
      <td>3096.807933</td>
      <td>0.583333</td>
      <td>0.083333</td>
      <td>0.416667</td>
      <td>0.416667</td>
      <td>17</td>
      <td>7</td>
      <td>12500.0</td>
      <td>3024.609470</td>
      <td>5148.045052</td>
      <td>0.000000</td>
      <td>12</td>
      <td>1.0</td>
    </tr>
    <tr>
      <th>3210</th>
      <td>10871.08518</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>4822.559803</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.166667</td>
      <td>3</td>
      <td>0</td>
      <td>18000.0</td>
      <td>2735.624602</td>
      <td>2595.765441</td>
      <td>0.000000</td>
      <td>12</td>
      <td>1.0</td>
    </tr>
    <tr>
      <th>755</th>
      <td>10397.09989</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>4045.620171</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.250000</td>
      <td>6</td>
      <td>0</td>
      <td>13000.0</td>
      <td>3222.169406</td>
      <td>2818.707479</td>
      <td>0.000000</td>
      <td>12</td>
      <td>1.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<section id="cluster---3-silver" class="cell markdown"
id="gIVDZ3RXlBX0">
<h5>Cluster - 3 (Silver)</h5>
</section>
<div class="cell code" data-execution_count="31"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:223}"
id="d1FAq1DnjR3E" data-outputId="1071f179-fc74-47a5-ccfe-6d370019ed0d">
<div class="sourceCode" id="cb44"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb44-1"><a href="#cb44-1" aria-hidden="true" tabindex="-1"></a>cluster_3_df <span class="op">=</span> creditcard_cluster_df[creditcard_cluster_df[<span class="st">&quot;cluster&quot;</span>]<span class="op">==</span><span class="dv">2</span>]</span>
<span id="cb44-2"><a href="#cb44-2" aria-hidden="true" tabindex="-1"></a>cluster_3_df.sort_values(by<span class="op">=</span>[<span class="st">&#39;BALANCE&#39;</span>], ascending<span class="op">=</span><span class="va">False</span>).head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="31">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>138</th>
      <td>19043.13856</td>
      <td>1.0</td>
      <td>22009.92</td>
      <td>9449.07</td>
      <td>12560.85</td>
      <td>0.000000</td>
      <td>1.0</td>
      <td>0.750000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0</td>
      <td>216</td>
      <td>18000.0</td>
      <td>23018.575830</td>
      <td>18621.013310</td>
      <td>0.0</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
    <tr>
      <th>5488</th>
      <td>16304.88925</td>
      <td>1.0</td>
      <td>1770.57</td>
      <td>0.00</td>
      <td>1770.57</td>
      <td>7424.094447</td>
      <td>0.5</td>
      <td>0.000000</td>
      <td>0.416667</td>
      <td>0.666667</td>
      <td>13</td>
      <td>9</td>
      <td>19000.0</td>
      <td>5337.961195</td>
      <td>8345.641905</td>
      <td>0.0</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
    <tr>
      <th>5281</th>
      <td>16115.59640</td>
      <td>1.0</td>
      <td>684.74</td>
      <td>105.30</td>
      <td>579.44</td>
      <td>4354.002428</td>
      <td>1.0</td>
      <td>0.083333</td>
      <td>1.000000</td>
      <td>0.583333</td>
      <td>15</td>
      <td>15</td>
      <td>18000.0</td>
      <td>3546.061550</td>
      <td>5743.736444</td>
      <td>0.0</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
    <tr>
      <th>585</th>
      <td>15244.74865</td>
      <td>1.0</td>
      <td>7823.74</td>
      <td>7564.81</td>
      <td>258.93</td>
      <td>2621.049473</td>
      <td>1.0</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.083333</td>
      <td>2</td>
      <td>62</td>
      <td>19000.0</td>
      <td>11123.409180</td>
      <td>4467.520244</td>
      <td>0.0</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
    <tr>
      <th>883</th>
      <td>14581.45914</td>
      <td>1.0</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>22665.778500</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.833333</td>
      <td>30</td>
      <td>0</td>
      <td>18500.0</td>
      <td>20941.325510</td>
      <td>5433.759888</td>
      <td>0.0</td>
      <td>12</td>
      <td>2.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<section id="cluster---4" class="cell markdown" id="xm0N4gn9lDu_">
<h5>Cluster - 4</h5>
</section>
<div class="cell code" data-execution_count="32"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;,&quot;height&quot;:223}"
id="5hOABUdHkXoU" data-outputId="430fdb09-d5b8-4e53-c706-e57826506c0e">
<div class="sourceCode" id="cb45"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb45-1"><a href="#cb45-1" aria-hidden="true" tabindex="-1"></a>cluster_4_df <span class="op">=</span> creditcard_cluster_df[creditcard_cluster_df[<span class="st">&quot;cluster&quot;</span>] <span class="op">==</span> <span class="dv">3</span>]</span>
<span id="cb45-2"><a href="#cb45-2" aria-hidden="true" tabindex="-1"></a>cluster_4_df.sort_values(by<span class="op">=</span>[<span class="st">&#39;BALANCE&#39;</span>], ascending<span class="op">=</span><span class="va">False</span>).head()</span></code></pre></div>
<div class="output execute_result" data-execution_count="32">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>BALANCE</th>
      <th>BALANCE_FREQUENCY</th>
      <th>PURCHASES</th>
      <th>ONEOFF_PURCHASES</th>
      <th>INSTALLMENTS_PURCHASES</th>
      <th>CASH_ADVANCE</th>
      <th>PURCHASES_FREQUENCY</th>
      <th>ONEOFF_PURCHASES_FREQUENCY</th>
      <th>PURCHASES_INSTALLMENTS_FREQUENCY</th>
      <th>CASH_ADVANCE_FREQUENCY</th>
      <th>CASH_ADVANCE_TRX</th>
      <th>PURCHASES_TRX</th>
      <th>CREDIT_LIMIT</th>
      <th>PAYMENTS</th>
      <th>MINIMUM_PAYMENTS</th>
      <th>PRC_FULL_PAYMENT</th>
      <th>TENURE</th>
      <th>cluster</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>4140</th>
      <td>18495.55855</td>
      <td>1.0</td>
      <td>5288.28</td>
      <td>3657.30</td>
      <td>1630.98</td>
      <td>0.000000</td>
      <td>1.0</td>
      <td>0.583333</td>
      <td>1.0</td>
      <td>0.000000</td>
      <td>0</td>
      <td>76</td>
      <td>22000.0</td>
      <td>4246.168346</td>
      <td>4227.081580</td>
      <td>0.0</td>
      <td>12</td>
      <td>3.0</td>
    </tr>
    <tr>
      <th>520</th>
      <td>15258.22590</td>
      <td>1.0</td>
      <td>529.30</td>
      <td>529.30</td>
      <td>0.00</td>
      <td>4100.891579</td>
      <td>0.5</td>
      <td>0.500000</td>
      <td>0.0</td>
      <td>1.000000</td>
      <td>23</td>
      <td>10</td>
      <td>19000.0</td>
      <td>2051.146470</td>
      <td>3905.740148</td>
      <td>0.0</td>
      <td>8</td>
      <td>3.0</td>
    </tr>
    <tr>
      <th>4708</th>
      <td>15155.53286</td>
      <td>1.0</td>
      <td>717.24</td>
      <td>717.24</td>
      <td>0.00</td>
      <td>4718.274895</td>
      <td>1.0</td>
      <td>1.000000</td>
      <td>0.0</td>
      <td>0.500000</td>
      <td>7</td>
      <td>24</td>
      <td>18000.0</td>
      <td>4002.194556</td>
      <td>3843.924668</td>
      <td>0.0</td>
      <td>12</td>
      <td>3.0</td>
    </tr>
    <tr>
      <th>5913</th>
      <td>13777.37772</td>
      <td>1.0</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>1675.249576</td>
      <td>0.0</td>
      <td>0.000000</td>
      <td>0.0</td>
      <td>0.666667</td>
      <td>11</td>
      <td>0</td>
      <td>14500.0</td>
      <td>3054.844697</td>
      <td>3242.471295</td>
      <td>0.0</td>
      <td>12</td>
      <td>3.0</td>
    </tr>
    <tr>
      <th>153</th>
      <td>13673.07961</td>
      <td>1.0</td>
      <td>9792.23</td>
      <td>3959.81</td>
      <td>5832.42</td>
      <td>2444.445738</td>
      <td>1.0</td>
      <td>0.750000</td>
      <td>1.0</td>
      <td>0.750000</td>
      <td>26</td>
      <td>216</td>
      <td>20000.0</td>
      <td>11717.307940</td>
      <td>6042.391629</td>
      <td>0.0</td>
      <td>12</td>
      <td>3.0</td>
    </tr>
  </tbody>
</table>
</div>
</div>
</div>
<section id="saving-the-model" class="cell markdown" id="edCwjspqOCD5">
<h1><font color = "black">Saving the
Model</font><a class = "anchor" id = "save"></a></h1>
</section>
<div class="cell code" data-execution_count="33"
data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}"
id="2jmKZxzqOI0D" data-outputId="12b0c435-42df-47fd-cdd7-8501fa6d6aeb">
<div class="sourceCode" id="cb46"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb46-1"><a href="#cb46-1" aria-hidden="true" tabindex="-1"></a><span class="co">#Saving Scikitlearn models</span></span>
<span id="cb46-2"><a href="#cb46-2" aria-hidden="true" tabindex="-1"></a><span class="im">import</span> joblib</span>
<span id="cb46-3"><a href="#cb46-3" aria-hidden="true" tabindex="-1"></a>joblib.dump(kmeans_model, <span class="st">&quot;kmeans_model.pkl&quot;</span>)</span></code></pre></div>
<div class="output execute_result" data-execution_count="33">
<pre><code>[&#39;kmeans_model.pkl&#39;]</code></pre>
</div>
</div>
<div class="cell code" data-execution_count="34" id="OefYGmi5P2xu">
<div class="sourceCode" id="cb48"><pre
class="sourceCode python"><code class="sourceCode python"><span id="cb48-1"><a href="#cb48-1" aria-hidden="true" tabindex="-1"></a><span class="co"># save the dataframe in .csv file named as &quot;Clustered_Costumer_Data&quot;</span></span>
<span id="cb48-2"><a href="#cb48-2" aria-hidden="true" tabindex="-1"></a>creditcard_cluster_df.to_csv(<span class="st">&quot;Clustered_Customer_Data.csv&quot;</span>)</span></code></pre></div>
</div>
<div class="cell markdown">
<p>I hope you found this analysis of Customer Market Segmentation using K-Means Clustering model both comprehensive and
insightful! <br> Your feedback is invaluable, please share your thoughts
if you enjoyed it. <br> Check out more such projects <a
href="https://github.com/sho-das">here</a>! 😄😅 <br> <a
href="#content">🔝</a></p>
</div>
</body>
</html>
