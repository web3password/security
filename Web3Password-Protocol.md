# Web3Password Protocol
```shell
version + dataLength + dataBinary

big endian
version - 2 bytes, fixed string: "01"
dataLength - 4 bytes, length of dataBinary
dataBinary - bytes by bson

```

## Example
```
mode 1: 
node web3password-api-audit.js 'science hundred humor hat jelly kangaroo receive drum buzz elite gym witness tuna shrug enlist' 'logdata=MDEAAAMeHgMAAAVkYXRhAEQBAAAARAEAABBjbQAAAAAAAmNuAAMAAABjcAAFY3QA7QAAAABkU313kMSWzcRXQwezoX7oq6TZcZXhVGx8nsxVqhP/5T4FOf4kC+VOPkECinnrh9CPKs6YFKm0W8KEnwBr1V1JYQVLNhDtPSt0WGIGFeOH5QBIxTvLQTAgr3bcbf2m7sDooWsXAKy3DOFg9J84PAGz9dbbSE42vZPyofYzfMByn/IXEryW78c0iwrGz9KOQjDisaEIgYuGdocTDlMVfTXep+bVn4BTq4rVK3sNQCXkC8Bpb1rQS7HoJHpxHNYZ8ePstEU6ZdFPGyXeUlDED0T4yCtQwdJ8B/txGREoBrVORqDaSDTEHT+6X4W4/UcQaWQA4QMAAAVpdgAMAAAAADtmSgFk2OUZlHleBgV0ZwAQAAAAAMf/8/EWajo1Tpck6ctsQgIAAnBhcmFtcwAqAQAAeyJhZGRyIjoiMHhlNGZjYWY2N2YyZjFkMTljOWEyMmVlOWNlZWM5ZGExYTQ2NjQ1MWU2IiwiY3JlZGVudGlhbCI6bnVsbCwiZmxvd19pZCI6MCwiaGFzaCI6ImJhNWI1Yzk3MDFjYzNlZGM0YzYwZTNiNDczNWMxNDdjZDExNTdhYjE2ZmQwMTdhMjY2OGM0MDE1MTBkNjU4MzIiLCJpZCI6ImM0MWY0MmRhLTVhNDEtNDYyYi1hZTM2LTJiNzM3MGVlYmM0OSIsIm5vbmNlIjoiN2MzNWViZjEtZDUwOS00YjU4LTliYzUtYTA4M2JhOWI3NzUyIiwib3BfdGltZXN0YW1wIjoxNjk5NTA1NzI5LCJ0aW1lc3RhbXAiOjE2OTk1MDU3Mjl9AAJzaWduYXR1cmUAhQAAADB4NzFmOTBlMzAyNmUwMDUwZTFmZjdjNTI3ZmZlMzA4YmFkMDVmMzgwN2QzOWUzOWYxODllNjIwZDU2NGMzOTVjMTdmMDBjMmUxMzQ2ODllMTVjZjIyNWFjZTZlMTlmNmYzZmMwMTA3YTRlMzM3YzI3Y2M0NTQ4YjljYjQyYTQ3YzUxYgAA'

mode 2:
node web3password-api-audit.js 'science hundred humor hat jelly kangaroo receive drum buzz elite gym witness tuna shrug enlist' 'logdir=/usr/local/var/map/go/src/w3p/web3password-protocol/test/log' 

mode 3:
node web3password-api-audit-stream 'science hundred humor hat jelly kangaroo receive drum buzz elite gym witness tuna shrug enlist' 'logdir=/usr/local/var/map/go/src/w3p/web3password-protocol/test/log' 


```
