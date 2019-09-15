# cdn
Info about solution and how ti works on apiunit


## Example solution:
https://wp-rocket.me/blog/reduce-http-requests-speed-wordpress-site/

+ Minifying and Combining HTML, CSS and JavaScript Files
+ Fix Render-Blocking CSS and JavaScript Files
+ Deleting and Optimizing Images
+ Evaluating and Reducing External Scripts


## Content Delivery Network

Using a CDN can further speed up how quickly your pages load for users. A CDN is a network of servers, usually located at various sites around the world. These servers cache the static content of your site, such as images, CSS and JavaScript files. When someone lands on your site, the static content is served from the server located closest to the user’s physical location. Shorter distances to the server means faster data retrieval. But keep in mind that if the majority of your site visitors are local, a CDN isn’t necessary – CDN’s are more suited to websites that have international traffic.

With WP Rocket, you can integrate your website with CloudFlare, a popular CDN. Go to the “CDN” tab in WP Rocket to enable CloudFlare and then add your account. For more, check out WP Rocket’s documentation on how to use CloudFlare with WP Rocket.

While Cloudflare is a useful free option for users with small websites, larger websites should invest in a premium service, such as MaxCDN (now StackPath), KeyCDN or even an open source option like jsDelivr.

# Cache
    A cache temporarily stores content for faster retrieval on repeated page loads.
    Using a cache for storage is called “caching.”

Below are the differences between each kind of cache, summarized for clarity:

    A site cache saves certain types of content and is controlled client-side.
    A browser cache saves the same types of content, and is saved on your computer, through your browser, and is controlled by the browser. It’s a type of client-side cache.
    Server caches store content, code, queries, or similar data on a server, or multiple servers, and is controlled by the server instead of a browser (client), or user.

## Server Cache

A server cache is a type cache that’s related to site caching, except instead of temporarily saving content on the client side, it’s stored on a site’s server. Server caching is also fully handled and amistered on the server without any involvement of the end user, or a browser.

Types of server caching include, but aren’t limited to:

    Object caching – Storing database queries in a server-side cache for quick retrieval on subsequent page loads.
    CDN caching – A Content Delivery Network (CDN) is a cluster of servers that are geographically located all around the world. They cache content that’s loaded using the server that’s closest to the end user for much faster loading times.
    Opcode caching – PHP code is compiled between each request, then stored in a cache so it’s executable faster on repeated page loads.
    
    
