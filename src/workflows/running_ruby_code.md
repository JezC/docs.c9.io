Author: Garen J. Torikian

# Running Ruby Code

While using Cloud9 IDE, you have access to the Ruby runtime. Accessing the command is no different than the way you'd use Ruby on your computer; just open the command line and type `ruby`. Currently, we run version 1.8.7.

To run a Ruby program that you've created, you can either:

* Open the command line and  type `ruby`, followed by the name of your program; for example `ruby hello_world.rb`
* Create a new run scenario, so that you can do things like pass in command line arguments. For more information, see the section on [Running Code](./running_and_debugging_code.html)

As a quick demonstration, open a new file, and paste this Ruby code into it:

```ruby
#!/usr/bin/ruby

puts 'Hello world'
```

When you hit the ![The Run Button](./icons/runButton.png) button in the menu bar, the console will print out the statement.

Note: Currently, you can't debug Ruby applications, but we are working on adding this feature.