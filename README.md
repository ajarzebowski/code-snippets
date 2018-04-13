Code snipets:

1. Check server response time:

```
curl -s -w %{time_total}\\n -o /dev/null https://google.com
```