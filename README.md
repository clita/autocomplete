# autocomplete
Autocomplete module for clita application.

## Usage 
**Initialisation**  
```go
  autocomplete.Init(threshold, max_results, training_file)
```

**Autocomplete Suggestion**  
```go
  autocomplete.Autocomplete("hell")
  
  // Output: 
  // Results (maximum 5) for target similarity: 0.30
  // match: hell             frequency: 3177030      similarity: 1.00
  // match: hello all        frequency: 525838       similarity: 0.44
  // match: hello and        frequency: 339673       similarity: 0.44
  // match: hello to         frequency: 256602       similarity: 0.50
  // match: hello from       frequency: 277949       similarity: 0.40
```  

