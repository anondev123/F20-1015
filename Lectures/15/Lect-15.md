# Lecture 15 - Cool Little Objects

An object is a mix of data and code.

Let's model vehicles.

How do we associate code and data in a simple class.

"words" that you have to use:

class - the thing that defines that this is an "object"

__init__ - the thing that sets up a class - called a "constructor"

__main__ - the special name that allows you to build tests in the same file as a class.

self - the name that allows you to access the data associated with this "instance" of an object.

an "instances" is the "type" of a class with its data.


This is the definition or "type" for the object.

```
class vehicle:

	""" this is a constructor """
	def __init__ ( manufacturer, model, year ):
		self.year = year	
		self.model = model	
		self.manufacturer = manufacturer	
		self.odometer = 0


	""" this is a Method ""
	def SetMilage ( n ):
		if n < 0 :
			print ( "Error: can't take milage off" )
		else
			self.odomoter = self.odomoter + n


```

