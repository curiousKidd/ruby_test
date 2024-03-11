# README

루비 테스트를 위한 프로젝트

구 버전의 루비 사용 예정
rails 프로젝트 입니다

* Ruby version
  * 2.4.1
  
* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

rbenv 로 루비 버전 관리 및 설치

`#로컬 macOS 환경에 ruby 설치`

`$ brew update`

`$ brew install rbenv && brew upgrade ruby-build`

`$ rbenv install 2.4.1`

sudo RUBY_CFLAGS="-DUSE_FFI_CLOSURE_ALLOC" rbenv install 2.4.1

chown -R [개인계정] /Users/[계정]/.rbenv

`$ rbenv rehash`

rbenv local 2.4.1

`$ ruby --version`

rbenv versions

`#ruby gem dependency 관리툴 설치`

`$ gem install bundler`

gem install thrift -v '0.11.0.0' --source 'https://rubygems.org/' -- --with-cppflags="-Wno-compound-token-split-by-macro"