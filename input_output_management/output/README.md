Note that the input used for these state machines is:

{
   "hello": "world!",
    "foo": {
       "bar": "baz"
    }
}

and the output of the executed lambda is:

{
    "success": true,
    "body": {
        "somekey": "somevalue",
        "all": {
            "this": "is",
            "a": "lambda",
            "result": "!"
        }
    }

}