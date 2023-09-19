# xcl

config language

# comment

all comment start with `#`

`format` : `# comment content`

example:

```
# comment
```

# variable

all variable start with a letter to identify type, and a single quote to identify variable name
variable name can be any string, but don't use empty string or single quote
`format` : `(s|i|u|f|d)'variable_name`

example:

```
s'hello
s'hello
i'123
f'123.456
```

# key,value

## key

just string, but don't use single quotes
`format`: `key_name` 

## value

just like variable
`format`: `variable`

example:

```
a=s'hello
b=i'123
c=f'123.456
```

# section

like ini file, section name is a string, and section name must be unique and don't use empty string
section has key,value, and sub section

`format`: `[section_name]`

example:
```
[section_name]
123=i"456
```

# sub section

sub section is a section in a section, sub section name must be unique in a section


`format`: `[section_name'sub_section_name]`

```
[section_name'sub_section_name]
123=i"456
```
