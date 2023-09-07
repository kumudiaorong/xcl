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
i32"123"
f64"123.456"
```

# key=value

```
i32"123"=i32"456"
f64"123.456"=f64"456.789"
s"hello"=f64"456.789"
```

# section
format: [section_name], section_name is a string

```
[section_name]
i32"123"=i32"456"
```
# sub section
format: [section_name.sub_section_name], section_name and sub_section_name are strings

```
[section_name.sub_section_name]
i32"123"=i32"456"
```