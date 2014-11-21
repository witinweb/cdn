    **7 Reasons to use a Content Delivery Network**

    Content Delivery Networks (CDNs) have revolutionized web hosting during the past few years. Rather than hosting your website a single server, you can
    distribute the files and load across multiple systems.

    What Files can be Hosted on a CDN?

    Most CDNs are used to host static resources such as images, videos, audio clips, CSS files and JavaScript. You’ll find common JavaScript libraries, HTML5
    shims, CSS resets, fonts and other assets available on a variety of public and private CDN systems.

    CDN Services

There are a number of free CDNs offered by Google, Microsoft, Yahoo and other large web organizations. For example, few people host their own videos when    [YouTube](http://www.youtube.com/) and [Vimeo](http://vimeo.com/) offer amazing free services. Similarly, if you require jQuery, you
    can load it on any page using:

<div>

        &lt;script src="http://ajax.googleapis.com/ajax/libs/jquery/1.6.4/jquery.min.js.js"&gt;&lt;/script&gt;

</div>

    or

<div>

        &lt;script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.6.4.min.js"&gt;&lt;/script&gt;

</div>

Alternatively, you could use a private commercial CDNs such as [Amazon S3](http://aws.amazon.com/s3/),    [Microsoft Windows Azure](http://www.microsoft.com/windowsazure/) and[MaxCDN](http://maxcdn.com/) to host your own files.

    The Benefits of Using a CDN

    There are several reasons why a CDN could benefit your website and company.

    **1. Different domains**

    Browsers limit the number of concurrent connections (file downloads) to a single domain. Most permit four active connections so the fifth download is
    blocked until one of the previous files has been fully retrieved. You can often see this limit in action when downloading many large files from the same
    site.

    CDN files are hosted on a different domain. In effect, a single CDN permits the browser to download a further four files at the same time.

    **2. Files may be pre-cached**

    jQuery is ubiquitous on the web. There’s a high probability that someone visiting your pages has already visited a site using the Google CDN. Therefore,
    the file has already been cached by your browser and won’t need to be downloaded again.

    **3. High-capacity infrastructures**

    You may have great hosting but I bet it doesn’t have the capacity or scalability offered by Google, Microsoft or Yahoo. The better CDNs offer higher
    availability, lower network latency and lower packet loss.

    **4. Distributed data centers**

    If your main web server is based in Dallas, users from Europe or Asia must make a number of trans-continental electronic hops when they access your files.
    Many CDNs provide localized data centers which are closer to the user and result in faster downloads.

    **5. Built-in version control**

    It’s usually possible to link to a specific version of a CSS file or JavaScript library. You can often request the “latest” version if required.

    **6. Usage analytics**

    Many commercial CDNs provide file usage reports since they generally charge per byte. Those reports can supplement your own website analytics and, in some
    cases, may offer a better impression of video views and downloads.

    **7. Boosts performance and saves money**

    A CDN can distribute the load, save bandwidth, boost performance and reduce your existing hosting costs — often for free.

    _What’s not to like?_

    As you’d expect, that’s not the whole story. Come back soon for _7 Reasons NOT to use a Content Delivery Network_…