# To show the current year on the screen in Wordpress.
It can be used for the date in the copyright area, especially for websites designed with Wordpress.

# For the functions.php file:

<pre><code>
function year_shortcode() {
  $year = date('Y');
  return $year;
}
add_shortcode('year', 'year_shortcode');
</code></pre>

# Usage:

Use <code>[year]</code> in your posts.
