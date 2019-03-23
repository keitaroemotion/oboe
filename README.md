# Oboe

Easy memorization script for terminal users

## Environment

- Ruby > 2.3.x
- Any Unix/Unix-like OS which contains the `/usr/local/*` directories


## Installation

```
./installer
```

## Usage

### target file execution

```
oboe [file]
```

### Help menu

```
oboe -h
```

### Edit default file:

```
oboe -e
```


The file structure should be:

```
apple, りんご
banana, バナナ
icecream, アイス
```
comma separated such as `[key], [value]`

By default, it will look at the file of

```
/usr/local/etc/oboe/words.txt
```
