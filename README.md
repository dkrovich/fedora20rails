fedora20rails
=============

How to setup a ruby on rails development environment on Fedora 20

Packages recommended

gcc
gcc-c++
emacs
make
ruby
ruby-devel
rubygem-mysql
rubygem-rails
rubygem-sqlite3
sqlite-devel

Easy cut and paste in one line

sudo yum install gcc gcc-c++ emacs make ruby ruby-devel rubygem-mysql rubygem-sqlite3 sqlite-devel

edit Gemfile, uncomment therubyracer line

bundle install

rails server
