/*|| (OR) — returns the first truthy value. It evaluates left to right and returns the first operand that converts to true, in its original form (not converted). If everything is falsy, it returns the last operand. 
So null || 0 || 1 gives 1, and firstName || lastName || "Anonymous" is a common trick for picking the first available value or a default.


&& (AND) — returns the first falsy value. The mirror image: evaluates left to right, returns the first operand that converts to false, or the last operand if all are truthy. So 1 && 0 gives 0, and 1 && 2 && 3 gives 3.


! (NOT) — converts to boolean and flips it. !0 is true. The double-NOT !!value is a shorthand for converting anything to a plain boolean (same as Boolean(value)).
Three extra details worth remembering:

Short-circuiting: both || and && stop evaluating the moment the result is decided — so true || alert("hi") never runs the alert. This matters when operands have side effects like function calls.
Precedence: ! is highest, then &&, then ||. So a && b || c && d reads as (a && b) || (c && d).

The one-sentence takeaway: in JS, || and && are value selectors (first truthy / first falsy), not just true/false machines — that's what makes patterns like default values possible.
*/