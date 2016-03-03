# Create a custom Directive structure

## Objectives

- Write a Directive and definition Object

## Instructions

Now that we've got the know-how on how to create very basic directives, let's create some.

We're going to have a success directive and an error directive. These should have templates inside them that have a message for when something succeeds, and when something fails. This means we can use the same language everywhere in our app just be referencing these two directives.

They should be named `successMessage` and `errorMessage` so we can use them in Angular via `<success-message></success-message>` and `<error-message></error-message>`.