ResponseEntity<UserDto> 
@RequestBody
  
  
  
  	@PostMapping
	public ResponseEntity<UserDto> createUser(@Valid @RequestBody UserDto userDto) {

		UserDto createNewUser = userService.createUser(userDto);
		return new ResponseEntity<>(createNewUser, HttpStatus.CREATED);

	}
