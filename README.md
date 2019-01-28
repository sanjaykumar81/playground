This is space of for testing your sharing your java or spring knowledge



## Validation of VO

To trigger the validation process, we’ll simply annotate the object in the controller layer with the @Valid annotation 
and used standard javax.validation annotations on the fields of the DTO object. For the simple checks, we can use 
bean validation annotations on the DTO object – annotations like @NotNull, @NotEmpty, etc.
