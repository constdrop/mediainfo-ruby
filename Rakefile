require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new("mediainfo-ruby", "0.2.0") do |p|
	p.description = "MediaInfo Ruby Bridge. Call MediaInfo lib directly"
	p.url         = "http://github.com/hackerdude/mediainfo-ruby"
	p.author      = "David Martinez"
	p.ignore_pattern = ["tmp/*", "script/*", "pkg/*"]
	p.dependencies = ["rice"] # TODO How to do native dependencies?
	p.require_signed = true
end


Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each{|ext| load ext }

