In XDITA,

~~~~~~~
 <topic id="t-marinara">
   <title>Marinara sauce</title>
   <prolog>
     <data name="author" value="Unknown" />
     <data name="category" value="Italian" />
   </prolog>
   <body>
     <p>Prepare a crowd-pleasing red sauce for pasta in about 30 minutes.</p>

     <section>
     <title>Ingredients</title>
     <ul>
       <li><p>2 tbsp. of olive oil</p></li>
       <li><p>2 cloves of garlic, minced</p></li>
       <li><p>1/2 tsp. of hot red pepper</p></li>
       <li><p>28 oz. of canned tomatoes, preferably San Marzano</p></li>
       <li><p>2 tbsp. of parsley, chopped</p></li>
     </ul>
     </section>

     <section>
     <title>Preparation</title>
     <ol>
       <li><p>Heat olive oil in a large saucepan on medium</p></li>
       <li><p>Add garlic and hot red pepper and sweat until fragrant</p></li>
       <li><p>Add tomatoes, breaking up into smaller pieces</p></li>
       <li><p>Simmer on medium-low heat for at least 20 minutes</p></li>
       <li><p>Add parsley</p></li>
       <li><p>Simmer for another five minutes</p></li>
       <li><p>Serve over long pasta.</p></li>
     </ol>
     </section>

   </body>
 </topic>
~~~~~~~

----
In HDITA as generic topic,

~~~~~~~
---
title:  This is the title # We can have a title here... but we need our h1
author: Unknown
keywords: Italian
---

<article id="t-marinara">
 <h1>Marinara sauce</h1>

 <p>Prepare a crowd-pleasing red sauce for pasta in about 30 minutes.</p>

<h2>Ingredients</h2>
 <ul>
   <li><p>2 tbsp. of olive oil</p></li>
   <li><p>2 cloves of garlic, minced</p></li>
   <li><p>1/2 tsp. of hot red pepper</p></li>
   <li><p>28 oz. of canned tomatoes, preferably San Marzano</p></li>
   <li><p>2 tbsp. of parsley, chopped</p></li>
 </ul>

 <h2>Preparation</h2>
 <ol>
   <li><p>Heat olive oil in a large saucepan on medium</p></li>
   <li><p>Add garlic and hot red pepper and sweat until fragrant</p></li>
   <li><p>Add tomatoes, breaking up into smaller pieces</p></li>
   <li><p>Simmer on medium-low heat for at least 20 minutes</p></li>
   <li><p>Add parsley</p></li>
   <li><p>Simmer for another five minutes</p></li>
   <li><p>Serve over long pasta.</p></li>
 </ol>

 </article>
~~~~~~~

In HDITA as specialized task,

~~~~~~~
---
title:  This is the title # We can have a title here... but we need our h1
author: Unknown
keywords: Italian
---

<article data-hd-class="task" id="t-marinara">
 <h1>Marinara sauce</h1>

 <p>Prepare a crowd-pleasing red sauce for pasta in about 30 minutes.</p>

<section data-hd-class="task/prereq">
<h2>Ingredients</h2>
 <ul>
   <li><p>2 tbsp. of olive oil</p></li>
   <li><p>2 cloves of garlic, minced</p></li>
   <li><p>1/2 tsp. of hot red pepper</p></li>
   <li><p>28 oz. of canned tomatoes, preferably San Marzano</p></li>
   <li><p>2 tbsp. of parsley, chopped</p></li>
 </ul>
</section>

 <section data-hd-class="task/steps-informal">
 <h2>Preparation</h2>
 <ol>
   <li><p>Heat olive oil in a large saucepan on medium</p></li>
   <li><p>Add garlic and hot red pepper and sweat until fragrant</p></li>
   <li><p>Add tomatoes, breaking up into smaller pieces</p></li>
   <li><p>Simmer on medium-low heat for at least 20 minutes</p></li>
   <li><p>Add parsley</p></li>
   <li><p>Simmer for another five minutes</p></li>
   <li><p>Serve over long pasta.</p></li>
 </ol>
 </section>

 </article>
~~~~~~~

----
In MDITA (rough draft),

~~~~~~~
---
title:  This is the title # We can have a title here...
author: Unknown
keywords: Italian
template: task # this calls a template file for validation and generated subheadings
---

# Marinara Sauce

Prepare a crowd-pleasing red sauce for pasta in about 30 minutes. <!-- Template will treat this as a shortesc if specified -->

## Ingredients
 -   2 tbsp. of olive oil
 -   2 cloves of garlic, minced
 -   1/2 tsp. of hot red pepper
 -   28 oz. of canned tomatoes, preferably San Marzano
 -   2 tbsp. of parsley, chopped

## Preparation
 1.   Heat olive oil in a large saucepan on medium
 2.   Add garlic and hot red pepper and sweat until fragrant
 3.   Add tomatoes, breaking up into smaller pieces
 4.   Simmer on medium-low heat for at least 20 minutes
 5.   Add parsley
 6.   Simmer for another five minutes
 7.   Serve over long pasta.

~~~~~~~
