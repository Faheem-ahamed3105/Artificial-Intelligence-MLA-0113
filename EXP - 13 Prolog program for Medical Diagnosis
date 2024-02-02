% Rules for medical diagnosis
diagnosis(X) :-
    symptom(X, fever),
    write('You may have a fever. Please consult a doctor for further evaluation.').

% Facts defining symptoms
symptom(john, fever).
symptom(mary, cough).
symptom(bob, headache).
symptom(alice, fever).

% Example Usage:
% ?- diagnosis(john).
% Output: You may have a fever. Please consult a doctor for further evaluation.
%
% ?- diagnosis(mary).
% Output: (No output, as the symptom is not fever)
