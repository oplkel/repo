This is the test.md file from the repo repository. The file is purely for testing GitHub Pages.

oplkel :P

--[=[
	@class myFirstClass

	This is my first class.
]=]
local myFirstClass = {}
myFirstClass.__index = myFirstClass

--[=[
	This is a very fancy function that adds a couple numbers.

	@param a number -- The first number you want to add
	@param b number -- The second number you wanna add
	@return number -- Returns the sum of `a` and `b`
]=]
function myFirstClass:add(a, b)
	return a + b
end
