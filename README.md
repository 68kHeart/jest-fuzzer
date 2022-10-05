# jest-fuzzer: Delightful Fuzz Testing for Jest

We all say that we should make tests, but writing good tests can be hard though.
You want to thoroughly test your work, but you can't hammer it with all sorts of
values to make sure it handles different cases properly...or can you? Welcome to
the world of fuzz testing!

Fuzz testers are designed to randomly create data to test your software against.
Making sure it passes (and fails) with a bunch of different kinds of inputs will
help identify edge cases in your software. Writing your own value generators can
be hard though, so why not use ours? This library's goal is to make good testing
more accessible and easy to use. Just need a simple value, like a number? We got
you covered. Want to create an object with other objects in it? No problem. Want
to generate full structures conditionally with varying fields and types? Yep, we
thought of that, too. By combining primitives and transforming them, same as you
do when writing code in JavaScript or TypeScript, you can build a fuzzer for any
occasion. Speaking of, did we mention it's all typed, too?

So now we have no more excuses; we can write good tests to make good code! Okay,
maybe _less_ execuses. ;-)

## Thanks

- [elm-test][] is a huge inspiration for the library. This likely wouldn't exist
  without all the hard work of those who have built and contributed to it.

- [Elm][] for changing the way we think about how to design and create software.
  It has made programming fun for us again and we're constantly delighted by the
  lessons learned.

- Our wonderful partners for helping keep our head on right and get things done!

## License

Copyright (C) 2022 Devan Ferguson. Licensed under the GNU General Public License
version 3. Please see the [provided license](LICENSE) for more details.



[Elm]: https://elm-lang.org "Elm - delightful language for reliable web applications"
[elm-test]: https://github.com/elm-explorations/test "GitHub: elm-explorations/elm-test"
