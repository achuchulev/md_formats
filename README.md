# This is a sample repo showing different markdown formats

## Examples

### Editing styles example

In this example I use a combination of **bold** and _italic_ *visual* __styles__


### Lists

#### Unordered 

* Terraform
  * Enterprise
  * Free
* Vagrant
  * Enterprise
  * Free
  
#### Ordered

1. Terraform
   1. Enterprise
   1. Free
1. Vagrant
   1. Enterprise
   1. Free
   
   
### Links usage example

[Link to GitHub md_formats repo](http://github.com/achuchulev/md_formats)


### Adding images

![Build Status](https://travis-ci.org/achuchulev/HelloUser.svg?branch=master)


### Text Block

> 	Getting something done well at the beginning 
>  is always less expensive than trying to fix it later.
>  When you are writing some code 
>  you should try to make it easy for people to understand it.


### Putting some code inline

This is a common usage of _ls_ command `ls -la`


### Table example

Team |Points|Played
-----|------|-------
MU | 6 | 3
Ars| 7 | 3
Liv| 9 | 3


### Script blocks

```
#!/usr/bin/env bash

# Define organisation and box
echo "Specify user:"
read var1
echo "Specify box:"
read var2

# Exports URLs of all available providers for the box
curl -sL  https://app.vagrantup.com/api/v1/box/$var1/$var2 | jq '.current_version.providers[].download_url'
```


### Tasks

- [x] this is a complete item
- [ ] this one is still not complete


### Automatic links

This is ~~~not~~~ a link to my repos https://github.com/achuchulev?tab=repositories


### Emoji

@achuchulev This repo looks good :+1: 
