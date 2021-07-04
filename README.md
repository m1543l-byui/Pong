# Pong
# Overview
This is a simple game written in Unity.
Pong is a 2d game, so I started by creating a png square 64X64 as my main sprite and duplicated/edited to create
all the objects needed.
The scripting language is c# and I created several scripts for things such as:
Ball
Player1
Player1 Goal
Player2
Player2 Goal
Game field which includes 3 objects within that create the walls.

The trickiest part is programming the ball as it is a constant changing variable.
We first launch it at random and a bounce Physics material was added to bounce off the walls.
    private void Launch()
    {
        float x = Random.Range(0, 2) == 0 ? -1 : 1;
        float y = Random.Range(0, 2) == 0 ? -1 : 1;
        rb.velocity = new Vector2(speed * x, speed * y);
    }

[Software Demo Video] 

# Development Environment

This program was created in Unity 2020.3.12f1  
Programming was done in the C# scripting language using Visual Studio 2019


# Useful Websites

* [GitHub Guides](https://guides.github.com/activities/hello-world/)

