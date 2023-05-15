Welcome to the AirBnB clone project!

The first step is to write a command interpreter to manage the AirBnB objects.
This is the first step towards building our first full web application: the AirBnB clone. This first step is very important because we will use what we build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help us to:
put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
then we will create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
We will then create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel.
We will also create the first abstracted storage engine of the project: File storage.
Then create all unittests to validate all our classes and storage engine
What’s a command interpreter?
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

We are going to Create a new object (ex: a new User or a new Place)
and then retrieve an object from a file, a database etc…
then do operations on objects (count, compute stats, etc…)
And update attributes of an object
And finally destroy an object

Resources:

cmd module
cmd module in depth
packages concept page
uuid module
datetime
unittest module
args/kwargs
Python test cheatsheet
cmd module wiki page
python unittest.
