# Brainfuck on Rails

Brainfuck on Rails (BoR) is a production-ready port of the popular ruby framework [Ruby on Rails](https://github.com/rails/rails).

## Usage

To use BoR you just need to:

    git clone git://github.com/masylum/Brainfuck-on-Rails.git

Then download your favourite Brainfuck compiler/interpreter. I recommend the ones writted in Brainfuck itself. They perform better and you don't need to learn another language to check the source.

## Why Brainfuck?

The main reason of porting RoR to Brainfuck was obviously that **BF scales out-of-the-box**.

Did you know that Facebook's "poke" is implemented using BF?

## Performance

BoR performance is awesome. It runs thousands of events loops that allow you to execute millions of parallel asynchronous expresions.

The footprint of the framework is almost inexistant. It just needs 20MB of memory. You can even run the framework on the cheap amazon machines!

## Convention over configuration

BoR doesn't need **any** configuration. We took the best decisions for you. If you don't agree, feel free to fork the project, but I will ignore your pull-requests, bitch.

## Tests

Something that really annoyed me of RoR was _testing_...BDD, TDD, cucumbers, rats... are your serious? We sent a man to the moon with fucking prehistoric computers and we still have to test our web applications?

BoR **doesn't need tests**, the framework doesn't let you shoot your foot giving you always detailed error messages on compile time.
