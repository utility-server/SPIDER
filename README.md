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
