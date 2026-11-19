# Fitrofy

The `fitrofy` tools answer from Fitrofy's Indian food database and diet brain.

- Macros are for one unit of a food (`unit`, e.g. one katori); `usual_serving` says how many
  units make a normal serving.
- A user is named only by `user_ref`, the company's pseudonymous ID. Never put a person's name,
  email address or phone number in any request.
- Register a user (`register_user`) before logging meals, asking for a plan or asking a question.
- `log_meals` is a conversation: when Fitrofy replies with a question, ask the user and send
  their answer back with `log_meals`. Only the first message of a user and date is charged.
- Most calls cost money, and each tool states its price. Don't repeat a paid call for the same
  answer.
- Fitrofy's answers are food information, not medical advice.
