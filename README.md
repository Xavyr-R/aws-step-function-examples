# aws-step-function-examples
This repository contains examples for different configurations for using AWS step functions. Its purpose is purely informative to give developers an idea of the different ways we can configure our workflows. It was created to add to practical examples to my blog on [aws step functions]().

Each folder contains the following files:
- At least 1 example JSON file, showing the code of a workflow (note that they all contain comments to elaborate) 
- An image of what the workflow looks like visually (often the same since they are quite small)

To give a brief overview of the folders:
- choice: contains two examples of the choice state, one with a simple statement (if string equals) and a second with complex statements (combining "and" and "or" statements)
- error_handling: contains examples on catching and retrying on exceptions
- fail: shows the fail state (how to explicitely make state machines fail)
- hello_world: simple hello world state machine
- map: shows the map state (an iterator to repeat a set of states over a list of inputs)
- parallel: shows the  parallel state (how to execute multiple states in parallel)
- pass: shows the pass state (do nothing state which can be used as placeholder or transform results)
- sequential_states_by_name: shows how to create a workflow with multiple steps (how to chain steps)
- success: shows the success state (how to explicitly make state machines succeed)
- task_input_output_management: shows how to manipulate inputs and outputs in steps
- task_invoke_glue: show how to invoke a glue job
- task_invoke_lambda: show how to invoke a lambda function
- task_invoke_step_function: show how to invoke other state machines
- task_s3_copy_object: show how to directly integrate with the S3 CopyObject API
- wait: show a wait state (wait for X seconds before continuing the state machine execution)
 
