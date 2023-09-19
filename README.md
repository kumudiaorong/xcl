# xcl

config language

# comment

- all comment start with `#`

`format` : `# comment content`

example:

```
# comment
```

# symbol

`format` : `(s|b|i|u|f)'value`

- `s` : string
- `b` : bool
- `i` : int
- `u` : uint
- `f` : float

`tips` 
- string can omit `s'`

example:

```
s'hello world
b'true
i'1
u'1
f32'1.0
```

# key-value

`format` : `key = value`

- `key` : symbol but only string
- `value` : symbol

example:

```
s'hello = s'world
_hello = s'world
```

# section

`format` : `[section]`

- `section` : string

`rules`
- `section` can't be empty

example:

```
[hello]
```

# sub-section

`format` : `[section'sub-section]`

- `section` : string
- `sub-section` : string

`rules` 
- `section` and `sub-section` can't be empty

example:

```
[hello'world]
```