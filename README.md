# kwrb
kwrb is MQTT client for mruby.

## install by mrbgems
- add conf.gem line to `build_config.rb`

```ruby
MRuby::Build.new do |conf|

    # ... (snip) ...

    conf.gem :github => 'tascript/kwrb'
end
```

## usage

**connect**

```ruby
s = Kwrb::Client.connect('host')
```

**disconnect**

```ruby
s = Kwrb::Client.connect('host')
s.disconnect
```
