# Website-Blocker
Python CLI to block/unblock access to websites when you need to be productive

## Usage

**To run this script, you must use `sudo` on Mac or `Start-Process powershell -Verb runAs` on Windows to elevate yourself to admin**

Add the URLs of the websites you want to block/unblock in this list

```python
# List of URLs to block/unblock (can also set this at runtime with below commands)
sites_to_block = []
```

To _block_ websites, use the `-b` flag:
```
python blocker.py -b [sites]
```

To _unblock_ websites, use the `-u` flag:
```
python blocker.py -u [sites]
```

