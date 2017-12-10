# Unpunctual

This project aimed to modify erl_scanner and erl_parser to support automatic comma, semi-colon, and period insertion as well as correction in many cases. The initial approach was to modify the lexer to make newlines more clear and then to interpret them in the parser. The issue here is that my expected behavior isn't working so I've put this on hold to try again outside of the Spawnfest event.

Thanks for organizing it though... It was a good motivation to go in and start reading more of the code in the Erlang compiler front-end, which was enlightening.
