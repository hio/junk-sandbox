
SYNTAX
------

1. use list representation for expressions of do.

    ?do([
      _X = {value, 10}, % ?return(10).
      _Y = {value, 20},
      %?return(_X+_Y),
      {value, 100},
      {value, {_X,_Y}}
    ]).

    ?do(monadmod, [
      ..
    ]).

# comment?

// comment?

<!-- comment? -->

-- comment?

; comment?


