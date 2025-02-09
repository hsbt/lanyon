Release History
===============

## 0.4.0

* Support .html extension stripping

## 0.3.4

* Allow Rack 2
* Use Rack::Utils.unescape_path with Rack 2
* Update development dependencies

## 0.3.3

* Use a nicer progress output format

## 0.3.2

* Flush progress output before starting build

## 0.3.1

* Do not set a Cache-Control header

## 0.3.0

* Use ETag instead of Last-Modified for caching
* Allow Jekyll 3
* Provide a Lanyon.build method

## 0.2.3

* Handle URLs with percent-encoded characters

## 0.2.2

* Prevent CRLF conversion for served files by using File.binread

## 0.2.1

* Sanitize path info to properly handle directory traversal

## 0.2.0

First gem release.
