# nginx-lua-project

## Setup command

1. Clone this project `git clone `
2. Enter the dir `cd nginx-lua-project`
3. Run docker `docker run -d --name nginx -v "$(pwd)":/var/nginx -v "$(pwd)"/config/nginx.conf:/opt/openresty/nginx/conf/nginx.conf -p 8080:8080 ficusio/openresty`

## Test
Run basic get to the localhost:
`curl http://127.0.0.1:8080/exam?request=NTAwMCwzMSx0ZXN0IG1lc3NhZ2UsMTQ2ODQyMjMxNDk1NyxNb3ppbGxhLzUuMCAoTGludXg7IEFuZHJvaWQgNS4wLjE7IFNBTVNVTkcgU0NILUk1NDUgNEcgQnVpbGQvTFJYMjJDKSBBcHBsZVdlYktpdC81MzcuMzYgKEtIVE1MLCBsaWtlIEdlY2tvKSBTYW1zdW5nQnJvd3Nlci80LjAgQ2hyb21lLzQ0LjAuMjQwMy4xMzMgTW9iaWxlIFNhZmFyaS81MzcuMzY=`

And see in `pwd` the exam.csv file updated

Good luck
