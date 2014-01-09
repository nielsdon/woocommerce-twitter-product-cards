woocommerce-twitter-product-cards
=================================

Because all plugins like this need to be paid for and that's bulls#!t.

TODO
====
1/ Register a function to be executed when the wp_head action fires:

add_action('wp_head', 'my_function');

2/ Make the function echo whatever you want in the header:

function my_function()
{
echo 'twitter card meta data here';
}
