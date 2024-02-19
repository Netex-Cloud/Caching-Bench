# Caching-Bench
Web server caching benchmark

If you are looking for a web server that needs to deliver files very quickly, for example this might be for CDN, this benchmark can help you. We will not measure the latency created by the network, instead we will focus on the latency caused by the web server.

# Development

Create a pull request with very basic webserver caching configuration. Or combine a web server with a caching plugin.

# Method

Github actions will bootstrap web servers in docker containers. Than a local Jmeter program simulates a little traffic. A script commits results to repository.

# Thanks

[The Benchmarker - Web Frameworks](https://github.com/the-benchmarker/web-frameworks)

[CDNPerf](https://www.cdnperf.com)
