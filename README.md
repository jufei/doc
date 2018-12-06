# Title

## level 2 title

### level 3 title

ok

> someone said this word

ok 2

**critical word **

_myunlineworkd_

```python
def clean_all_connections():
    for bts in gv.allbts:
        bts.conn_bts = None
        if hasattr(bts, 'cpc'):
            gv.logger.debug('Teardown BTS CPC')
            bts.cpc.teardown()

```



```python
def hello(p):
    print("ok")
```



>

```sequence
ÀîÀ× -> º«Ã·Ã·: Hello Ã·Ã·, How are you?
Note right of º«Ã·Ã·: º«Ã·Ã·ÐÄÏë
º«Ã·Ã· --> ÀîÀ×: I'm fine, thanks, and you?
```