<div style="text-align:right">
  <a href="http://cardiff.ac.uk">
    <img
      style="width:15%;"
      title="Cardiff University Logo"
      src="https://upload.wikimedia.org/wikipedia/en/b/b1/Cardiff_university_logo.png"
      />
  </a>
</div>

## Media Monitor

A joint research project between the [School of Computer Science](https://www.cs.cf.ac.uk/) and the [School of Journalism](http://www.cardiff.ac.uk/journalism-media-cultural-studies) at Cardiff University. The tool will be used to conduct an analysis of journalism conversation on social media.

---

### Getting Started

To get started you'll need the following packages
- `twython`
- `pymongo`

To install them run

```
$ pip3 install twython
$ pip3 install pymongo
```

Next, you'll need to add a `credentials.py` file containing you twitter access tokens.

`credentials.py`

```python
app_key = 'your_app_key'
app_secret = 'your_app_secret'
auth_token = 'your_auth_token'
auth_secret = 'your_auth_secret'

```

To start monitoring run

```
$ python3 start.py
```
