# Where gem docs are installed

`gem env home`

If want to prevent gems from generating documentation during installation, then turn off local documentation generation by creating a file called ~/.gemrc which contains a configuration setting to turn off this feature:

`echo "gem: --no-document" > ~/.gemrc`

<br/>

# Uninstall ruby/rails


```
ruby -v
rails -v
```

`gem uninstall rails` # To uninstall

And to uninstall ruby, you'd just follow the uninstall instructions from rbenv, rvm or whatever you used to install it.
As a side note, you don't want to remove any Ruby that comes pre-installed on your system (like macOS has a Ruby pre-installed) because the operating system depends upon it.


# Prototype to destroy a controller in Rails:
`rails destroy controller <ControllerName>`
OR
`rails d controller <ControllerName>`
