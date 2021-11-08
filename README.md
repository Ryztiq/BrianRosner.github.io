# BrianRosner.github.io
Brian R's Github Portfolio

Programming Portfolio Example
Adventure Game
Image

A game that demonstrates object-oriented programming principles inheritance, encapsulation, and polymorphism. C# Adventure Game

Study Application
A Study Application that reads in terms and definitions from an external file (or files).

Explorable Areas
A command-line application with areas to explore and items for the player to find in each area. Before you can travel to the lake for snorkeling, the equipment must be found in one of the other areas. Explorable Areas

Underwater Creatures
Underwater Creatures demonstrates inheritance, polymorphism, and encapsulation.

Adopt-An-Insect
An application that lets a player create a custom insect character: Adopt-An-Insect

Shift Cipher
Shift Cipher is an application that encodes and decodes using a simple substitution cipher.

Trivia Game
Trivia Application

Zero Sum
Zero Sum is a C# WPF application of the penny game described in 'The Computational Beauty of Nature'.

WPF Navigation
WPF Navigation is a C# WPF example of using a frame and multiple pages.

WPF Character Customization (Radio Buttons)
WPF-CharacterCustomizationExample is an example of using WPF and C# to allow a player to modify something with radio button choices (like an item or a creature companion).

More projects on my github repo site

Code Gists
Gists used in class
Programming is Fun Gists and other example code
Code examples can be shown like this:

private void Play()
        {
            foreach (TriviaItem triviaItem in Questions)
            {
               Clear();
               WriteLine(player.PlayerInformation());
               WriteLine(triviaItem.Question);
                string input = ReadLine();
                if (triviaItem.CheckAnswer(input))
                {
                    player.IncrementScore();
                }
            }
        }
For more details see GitHub Flavored Markdown.
