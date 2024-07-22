# Ruby-Basics
markdown

# Introduction to Ruby

Ruby is a dynamic, open-source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

## Table of Contents

1. [Introduction](#introduction)
2. [Why Ruby?](#why-ruby)
3. [Installation](#installation)
4. [Basic Syntax](#basic-syntax)
   - [Variables](#variables)
   - [Data Types](#data-types)
   - [Operators](#operators)
5. [Control Structures](#control-structures)
   - [Conditional Statements](#conditional-statements)
   - [Loops](#loops)
6. [Methods](#methods)
7. [Classes and Objects](#classes-and-objects)
8. [File Input/Output](#file-inputoutput)
9. [Conclusion](#conclusion)

## Introduction

Ruby is an object-oriented language developed by Yukihiro Matsumoto, who is often known as "Matz." Ruby is designed to be easy to use and to have an intuitive, human-friendly syntax.

## Why Ruby?

Ruby is known for its simplicity and productivity. It's often used for web development (thanks to the Ruby on Rails framework), but it's also suitable for many other types of programming, including data analysis, prototyping, and more.

## Installation

To install Ruby, you can use a version manager like `rbenv` or `RVM` (Ruby Version Manager). Here’s a quick way to get started with `rbenv`:

1. Install `rbenv`:
   ```sh
   brew install rbenv
   rbenv init
Install Ruby:
sh

rbenv install 3.1.2
rbenv global 3.1.2
Basic Syntax
Variables
Variables in Ruby do not need to be declared; you can assign values directly.

_____

name = "Michel"
age = 30
Data Types
Ruby supports several data types, including:

Numbers: Integer and Float
---
count = 10      # Integer
price = 99.99   # Float
Strings: A sequence of characters
ruby

greeting = "Hello, world!"
Arrays: Ordered collections of objects
ruby

fruits = ["apple", "banana", "cherry"]
Hashes: Collections of key-value pairs
---

person = {name: "Michel", age: 30}
Operators
Ruby has standard arithmetic operators like +, -, *, /, and %. It also includes comparison operators such as ==, !=, >, <, >=, and <=.

Control Structures
Conditional Statements
Ruby uses if, elsif, and else for conditional execution.

---

if age < 18
  puts "You are a minor."
elsif age >= 18 && age < 65
  puts "You are an adult."
else
  puts "You are a senior."
end
Loops
Ruby supports various looping constructs, including while, until, and for loops.

---
i = 0
while i < 10
  puts i
  i += 1
end
Methods
Methods in Ruby are defined using the def keyword and can accept parameters.

---

def greet(name)
  "Hello, #{name}!"
end

puts greet("Michel")  # Output: Hello, Michel!
Classes and Objects
Ruby is a purely object-oriented language, meaning everything in Ruby is an object. You can define your own classes to create objects.

---

class Person
  attr_accessor :name, :age

  def initialize(name, age)
    @name = name
    @age = age
  end

  def display_details
    "Name: #{@name}, Age: #{@age}"
  end
end

person = Person.new("Michel", 30)
puts person.display_details
File Input/Output
Ruby provides built-in support for file handling.

---

# Writing to a file
File.open("example.txt", "w") do |file|
  file.puts "Hello, world!"
end

# Reading from a file
File.open("example.txt", "r") do |file|
  content = file.read
  puts content
end
Conclusion
Ruby is a versatile and user-friendly programming language suitable for beginners and experienced developers alike. Its clean syntax and powerful features make it a popular choice for a wide range of applications.

For more detailed information, consider checking out resources like "The Ruby Programming Language" by David Flanagan and Yukihiro Matsumoto or "Programming Ruby" by Dave Thomas.
