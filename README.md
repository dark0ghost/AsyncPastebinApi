# AsyncPastebinApi

#  use async
```python 
import AsyncPastebinApi
import asyncio

async def main():
   pastebin = AsyncPastebinApi.Pastebin()
   await pastebin.open_session()
   
   print(await pastebin.send_paste(data=pastebin.generate_data(paste="text")))
   # pastenin.com/******
   
   await pastebin.close()

```
