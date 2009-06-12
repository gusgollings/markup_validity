# -*- ruby -*-

require 'rubygems'
require 'hoe'

$LOAD_PATH << File.expand_path(File.join(File.dirname(__FILE__), 'lib'))

require 'markup_validity'

Hoe.new('markup_validity', MarkupValidity::VERSION) do |p|
  p.developer('Aaron Patterson', 'aaronp@rubyforge.org')
  p.extra_deps = [['nokogiri', '>= 1.3.1']]
end

# vim: syntax=Ruby