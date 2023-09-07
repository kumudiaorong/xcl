# xcl
config language

# comment

```
# comment
```

# variable

format: type before name, with quotes or single quotes

```
s"hello"
s'hello'
i32"123"
f64"123.456"
```

# key=value

## key
format: just string, but don't use quotes or single quotes


## value
format: just like variable

```
a=s"hello"
b=i32"123"
c=f64"123.456"
```

# section
format: [section_name], section_name is a string

```
[section_name]
123=i32"456"
```
# sub section
format: [section_name.sub_section_name], section_name and sub_section_name are strings

```
[section_name.sub_section_name]
123=i32"456"
```