% Printing all elements of a list
print_list([]).
print_list([Head|Tail]) :-
    write(Head), write(' '),
    print_list(Tail).

% Appending an integer to a list
append_integer(List, Integer, Result) :-
    append(List, [Integer], Result).

% List membership check
is_member(Element, List) :-
    member(Element, List),
    write(Element), write(' is a member of the list.').

% Example Usage:
% a. Printing all elements of a list
% ?- print_list([1, 2, 3, 4, 5]).
% Output: 1 2 3 4 5

% b. Appending an integer to a list
% ?- append_integer([1, 2, 3], 4, Result).
% Result = [1, 2, 3, 4]

% c. List membership check
% ?- is_member(3, [1, 2, 3, 4, 5]).
% Output: 3 is a member of the list.
% ?- is_member(6, [1, 2, 3, 4, 5]).
% Output: (No output as 6 is not a member of the list)
