package com.curd.crud.resources;

import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

import com.curd.crud.entities.User;

@RestController
@RequestMapping(value = "/users")
public class UsersResources {

	@GetMapping
	public ResponseEntity<User> findAll(){
		User u = new User(1l, "test","teste","teste", "test");
		
		return ResponseEntity.ok().body(u);
	}
}
	