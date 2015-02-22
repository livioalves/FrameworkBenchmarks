# [nginx + mruby](https://github.com/matsumoto-r/ngx_mruby) Benchmark Test

The nginx app is distributes across a few files. most of it is in [nginx.conf](nginx.conf)
The nginx conf is inside [nginx.conf](nginx.conf)
Requires a nginx compiled with ngx_mruby module. It has been called nginx_mruby for lack of a better name


## Test URLs
### JSON Encoding

http://localhost:8080/json

### Single Row Random Query

http://localhost:8080/db

### Variable Row Query Test

http://localhost:8080/db?queries=2

Based upon the [openresty](../../Lua/openresty/) implementation.