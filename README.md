md5check
========

md5checker is a digital certificates tool for file

### Installation

For the latest stable version:

```sh
gem install md5check
```

### Usage

```ruby
require 'digest/md5'
m = Digest::MD5.file 'yourfile'
m.hexdigest # 51b1ec8d1ad08c3b7bcbcb29db8c45db0
```

or

```sh
$ md5check 'yourfile'
```
