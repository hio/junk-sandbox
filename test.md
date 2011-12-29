
SYNTAX
------

1.  use list representation for expressions of do.

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

        ?do([m1, m2, ...], [
          ..
        ]).

putting '_' for monadmod gets same behavior as ?do([..]).

    % same as ?do([..]).
    ?do('_', [
      ..
    ]).



# comment?

// comment?

<!-- comment? -->

-- comment?

; comment?


