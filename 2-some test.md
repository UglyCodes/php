id:1

This code above produces a PHP Notice:
<br>
<strong>Undefined variable: var</strong>

<div class="bad"><pre class="brush: php">
if ($var) {
    // do something with $var
}
</pre></div>

Use instead:

<div class="good"><pre class="brush: php">
if (!empty($var)) {
    // do something with $var
}
</pre></div>
