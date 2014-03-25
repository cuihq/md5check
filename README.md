md5check
========

md5checker is a digital certificates tool for file

[![Code Climate](https://codeclimate.com/repos/532ad6ab695680145f00c3eb/badges/dc0d49428539f3ef93e2/gpa.png)](https://codeclimate.com/repos/532ad6ab695680145f00c3eb/feed)

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
$ md5check -f 'yourfile'
```
