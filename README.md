**1. Clone wallet sources**

```
git clone --recurse-submodule https://github.com/prascoin/prascoinwallet.git
```

**2. Update submodules**

```
git submodule update --remote --recursive

```


**3. Build**

```
mkdir build && cd build && cmake .. && make
```
