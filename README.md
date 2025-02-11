# SPIDER by Utility Server

![SPIDER by Utility Server](https://utility-server-public.s3.ap-south-1.amazonaws.com/logo-SPIDER.png)

Welcome to SPIDER, the ultimate tool for enhancing your JavaScript website's visibility to bots and crawlers. In today's web landscape, where JavaScript-driven sites are prevalent, it's crucial to ensure that your content is effectively indexed and accessible. SPIDER is here to help. By seamlessly interpreting and presenting your website's content to bots, SPIDER boosts your online presence like never before.

## For more details, check out our [Knowledge Base](https://github.com/utility-server/SPIDER/wiki).

# spider-nginx
This is the SPIDER middleware configuration for an nginx server to allow Google (and other crawlers) to crawl your javascript website.

This file is based on [this](https://github.com/utility-server/SPIDER) and it was updated following the recommendations in the comments

The `nginx.conf` in this repository is full file for __reference__.

Nginx config for
* Single Page Application: [nginx.conf](/nginx.conf)
* PHP application: [nginx-php/nginx.conf](/nginx-php/nginx.conf)
* reverse proxy: [nginx-reverse-proxy/nginx.conf](/nginx-reverse-proxy/nginx.conf)


## debugging

To debug the page sent to utility-server.com use the following log format:

```
log_format spider_debug '[$time_local] $remote_addr - $remote_user - $server_name user-agent: $http_user_agent spider: $spider: $request to: $upstream_addr upstream_response_time: $upstream_response_time msec $msec request_time $request_time';
```

Here is a layout where each plan for **SPIDER** has its own column in a tabular format:

Here is the updated table where **0** is replaced with **Free**, and the cost is displayed with a **$... (USD)** format:

----

### SPIDER Plans (Scope :: End User)

| **Plan**             | **SPDR-FREE** | **SPDR-TARANTULA** | **SPDR-ORBWVR** | **SPDR-WOLF** | **SPDR-GOLDNSILK** | **SPDR-BLKWIDOW** |
|----------------------|---------------|--------------------|-----------------|---------------|--------------------|-------------------|
| **Cost**             | Free          | $30/month          | $75/month       | $145/month    | $250/month         | $600/month        |
| **Renders**          | 1,000         | 25,000             | 75,000          | 150,000       | 250,000            | 500,000           |
| **Hits**             | 10,000        | 250,000            | 750,000         | 1,500,000     | 2,500,000          | 5,000,000         |
| **Cache Duration**   | 5 Days        | 7 Days             | 10 Days         | 15 Days       | 25 Days            | 45 Days           |
| **Extra Cost / Render** | *         | $0.0015 (USD)      | $0.001 (USD)    | $0.0008 (USD)| $0.0007 (USD)      | $0.0005 (USD)     |
| **Extra Cost / Hit** | *             | $0.000375 (USD)    | $0.00025 (USD)  | $0.0002 (USD)| $0.000175 (USD)    | $0.000125 (USD)   |
| **Extra Add-on** | Not Allowed             | *    | *  | *| *    | *   |

* Extra Ad-on: $1 / 2,000 Renders + 20,000 Hits
* Extra rendering and extra hits are not allowed; accounts will be blocked in case of overage.
