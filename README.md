# nodebeginnerbook

1 url.parse(string).query
2 |
3 url.parse(string).pathname |
4 | |
5 | |
6 ------ -------------------
7 http://localhost:8888/start?foo=bar&hello=world
8 --- -----
9 | |
10 | |
11 querystring.parse(string)["foo"] |
12 |
13 querystring.parse(string)["hello"]