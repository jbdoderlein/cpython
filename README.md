# Python Iflooped

## Build

```bash
./configure
make
```

## Install

```bash
make altinstall
```

Use `python3.11` to execute your code.

## Example

```python
def test_ifloop():
    a, b = 5, 5
    ifloop a!=0:
        print(f"{a=}")
        a-=1
        if b==0:
            break
    else:
        print(f"{b=}")
        b-=1
        a+=1


if "__main__" in __name__:
    test_ifloop()
```
