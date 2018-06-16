# BGTJson
A wrapper for JSON (JavaScript Object Notation) in bgt

JSON (simplified) implementation in the bgt scripting language.
This is a simple version of json, implemented in bgt.
This include can convert a dictionary to a json string and back.
Because it takes a dictionary and converts it to a string, it could be used in conjunction to talk to a webserver.
This implementation only support one layer of json (see example data in example.sjon.

# Example:
Look in the example.bgt and example.json file.

# Function overview.
string json_encode(dictionary data)
argument: dictionary that has the data.
returns: JSON string.

dictionary@ json_decode(string json_string);
argument: a json string.
returns: a new dictionary with the parsed data.
	