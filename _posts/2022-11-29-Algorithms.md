---
keywords: fastai
title: Algorithms
nb_path: _notebooks/2022-11-29-Algorithms.ipynb
layout: notebook
---

<!--
#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: _notebooks/2022-11-29-Algorithms.ipynb
-->

<div class="container" id="notebook-container">
        
<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Operations">Operations<a class="anchor-link" href="#Operations"> </a></h1><p>Subtraction:
Represented by “-"</p>
<p>Addition:
Represented by "+"</p>
<p>Multiplication:
Represented by “*”</p>
<p>Division:
Represented by “/”</p>
<p>Getting the Remainder:
Represented by “MOD” (% in python)</p>
<h1 id="Order-of-Operations">Order of Operations<a class="anchor-link" href="#Order-of-Operations"> </a></h1><p>Arithmetic operations in programming are performed in the same order as operations in mathematics:</p>
<p>Operations in parentheses should be done first.</p>
<p>Division and multiplication should be done before addition and subtraction.</p>
<p>Modulus works similar to multiplication and division.</p>
<p>Example: Evaluate num1</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="mi">5</span> <span class="o">%</span> <span class="mi">2</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">



<div class="output_text output_subarea output_execute_result">
<pre>1</pre>
</div>

</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">num1</span> <span class="o">=</span> <span class="mi">9</span> <span class="o">%</span> <span class="mi">2</span> <span class="o">*</span> <span class="p">(</span> <span class="mi">8</span> <span class="o">-</span> <span class="mi">2</span> <span class="p">)</span> <span class="o">+</span> <span class="mi">8</span> <span class="o">/</span> <span class="p">(</span> <span class="mi">6</span> <span class="o">-</span> <span class="mi">4</span> <span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">num1</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">var1</span> <span class="o">=</span> <span class="mi">9</span>
<span class="n">var2</span> <span class="o">=</span> <span class="mi">7</span>
<span class="n">var3</span> <span class="o">=</span> <span class="mi">2</span>

<span class="c1">#var = var1 + 5</span>
<span class="c1">#var2 = var1 - var3</span>
<span class="c1">#var1 = var2</span>
<span class="c1">#var3 = (var1 + var2) / 2</span>
<span class="c1">#var2 = 6</span>

<span class="nb">print</span><span class="p">(</span><span class="n">var1</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">var2</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="n">var3</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
    {% endraw %}

<div class="cell border-box-sizing text_cell rendered"><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Strings">Strings<a class="anchor-link" href="#Strings"> </a></h2><h1 id="What-is-a-String?">What is a String?<a class="anchor-link" href="#What-is-a-String?"> </a></h1><p>A String: A string is a collection of characters. What is a character as character can be anything from numbers, letters, spaces, special symbols, etc.</p>
<p>A string is a collection of characters. What is a character as character can be anything from numbers, letters, spaces, special symbols, etc.</p>
<p>Certain procedures may be used with strings and they vary from programming language to language Python examples</p>
<p>len() to find the length of a string</p>
<p>lower() to convert to lowercase</p>
<p>etc. Pseudocode examples</p>
<p>len() returns the length of a string</p>
<p>concat() returns a string made up of the concatenated strings ex. concat("string1", "string2") would return string1string2</p>
<p>substring() returns the characters from the string beginning at the at the first position to the last so an example of this would be substring ("abcdefghijk", 2, 5) would print bcde (pseudocode starts at 1)</p>
<h1 id="String-Concatenation">String Concatenation<a class="anchor-link" href="#String-Concatenation"> </a></h1><p>What is string concatenation?</p>
<p>String concatenation is combining 2 or more strings to make a new strings in order to create a new string</p>
<p>concat() in pseudocode and varys from language to language can be used to combine to strings such as concat("cookie","monster") returns cookiemonster</p>
<h1 id="Substrings">Substrings<a class="anchor-link" href="#Substrings"> </a></h1><p>What is a substring?</p>
<p>A substring is a part of and already existing string.</p>
<p>In pseudocode substring() method is used for instance for concat("Mr.Mortenson is very handsome" 1, 2) the system would return Mr (remember that pseudocode starts at 1)</p>

</div>
</div>
</div>
    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Num1</span> <span class="o">=</span> <span class="mi">50</span>
<span class="n">Num2</span> <span class="o">=</span> <span class="n">Num1</span> <span class="o">%</span> <span class="mi">9</span> <span class="o">+</span> <span class="mi">15</span>
<span class="n">Num3</span> <span class="o">=</span> <span class="n">Num2</span> <span class="o">/</span> <span class="n">Num1</span> <span class="o">+</span> <span class="p">(</span> <span class="n">Num2</span> <span class="o">*</span> <span class="mi">2</span> <span class="p">)</span>
<span class="n">Num4</span> <span class="o">=</span> <span class="n">Num3</span> <span class="o">+</span> <span class="n">Num1</span> <span class="o">/</span> <span class="mi">5</span> <span class="o">-</span> <span class="mi">10</span>
<span class="n">Result</span> <span class="o">=</span> <span class="n">Num4</span> <span class="o">-</span> <span class="n">Num2</span>

<span class="c1"># Num2 = 5+15 = 20</span>
<span class="c1"># Num3 = 20/50 + (20*2)= 40.4</span>
<span class="c1"># Num4 = 40.4 + 50/5 -10 = 40.4</span>
<span class="c1"># Result = 40.4 - 20 = 20.4</span>

<span class="nb">print</span><span class="p">(</span><span class="n">Result</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>20.4
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">Num1</span> <span class="o">=</span> <span class="mi">10</span>
<span class="n">Num2</span> <span class="o">=</span> <span class="n">Num1</span> <span class="o">%</span> <span class="mi">3</span> <span class="o">*</span> <span class="mi">4</span>
<span class="n">Num1</span> <span class="o">=</span> <span class="n">Num2</span>
<span class="n">Num3</span> <span class="o">=</span> <span class="n">Num1</span> <span class="o">*</span> <span class="mi">3</span>
<span class="n">Result</span> <span class="o">=</span> <span class="n">Num3</span> <span class="o">%</span> <span class="mi">2</span>

<span class="c1"># Num2 = 1 * 4 = 4</span>
<span class="c1"># Num1 = 4</span>
<span class="c1"># Num3 = 4 * 3 = 12</span>
<span class="c1"># Result = 12 % 2 = 0</span>

<span class="nb">print</span><span class="p">(</span><span class="n">Result</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>0
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">valueA</span> <span class="o">=</span> <span class="mi">4</span>
<span class="n">valueB</span> <span class="o">=</span> <span class="mi">90</span>
<span class="n">valueC</span> <span class="o">=</span> <span class="mi">17</span>
<span class="n">valueB</span> <span class="o">=</span> <span class="n">valueC</span> <span class="o">-</span> <span class="n">valueA</span>
<span class="n">valueA</span> <span class="o">=</span> <span class="n">valueA</span> <span class="o">*</span> <span class="mi">10</span>
<span class="k">if</span> <span class="n">valueB</span> <span class="o">&gt;</span> <span class="mi">10</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="n">valueC</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>17
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

    {% raw %}
    
<div class="cell border-box-sizing code_cell rendered">
<div class="input">

<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">type</span> <span class="o">=</span> <span class="s2">&quot;curly&quot;</span>
<span class="n">color</span> <span class="o">=</span> <span class="s2">&quot;brown&quot;</span>
<span class="n">length</span> <span class="o">=</span> <span class="s2">&quot;short&quot;</span>
<span class="nb">type</span> <span class="o">=</span> <span class="s2">&quot;straight&quot;</span>
<span class="n">hair</span> <span class="o">=</span> <span class="nb">type</span> <span class="o">+</span> <span class="n">color</span> <span class="o">+</span> <span class="n">length</span>
<span class="nb">print</span><span class="p">(</span><span class="n">hair</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">

<div class="output_area">

<div class="output_subarea output_stream output_stdout output_text">
<pre>straightbrownshort
</pre>
</div>
</div>

</div>
</div>

</div>
    {% endraw %}

</div>
 

