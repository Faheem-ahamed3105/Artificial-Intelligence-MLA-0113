% Facts
male(john).
male(bob).
male(jim).
female(mary).
female(susan).
female(emma).

parent(john, bob).
parent(john, jim).
parent(mary, bob).
parent(mary, jim).
parent(bob, susan).
parent(emma, susan).

% Rules
father(X, Y) :- male(X), parent(X, Y).
mother(X, Y) :- female(X), parent(X, Y).
sibling(X, Y) :- parent(Z, X), parent(Z, Y), X \= Y.

% Queries
% Example: Who is the father of Susan?
% Query: father(X, susan).
% Response: X = bob.

% Example: Who are the siblings of Susan?
% Query: sibling(X, susan).
% Response: X = jim.

% Example: Is John a parent of Emma?
% Query: parent(john, emma).
% Response: false.
