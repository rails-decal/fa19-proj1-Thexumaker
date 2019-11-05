# Q0: Why are these two errors being thrown?
The first error is happening because the database has been changed but not updated yet.
The second error is occurring since it's trying to access the pokemon model, but we haven't made it yet
# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
They are appearing because we have populated seeds.rb with a set of pokemon to experiment with. None of all the possible pokemon don't have trainers.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
It creates a button that when clicked leads out to the patch capture route, which calls the capture function in the pokemons_controller. It sends a pokemon id as a parameter for the function to use.  

# Question 3: What would you name your own Pokemon?
I don't really go by the route of creating friendships, so I'd just name them random stuff.

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
I passed the trainer_path with the pokemon's specific trainer id.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
Whatever error was made(no name or same name) gets passed and rails processes the rorr into a message?

# Give us feedback on the project and decal below!
The project would be nice if we got directions to upload to heroko and not be part of extra credit. 

# Extra credit: Link your Heroku deployed app
