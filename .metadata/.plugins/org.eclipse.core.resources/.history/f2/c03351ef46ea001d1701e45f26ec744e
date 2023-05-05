package com.example.SpringBootSampleDemo;

import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@Controller
@RestController
@RequestMapping("/api")
public class HelloController {
	@GetMapping("/hello")
	public String sayHello() {
		return "Hello World";
	}
	
	@GetMapping("/greeting")
	public String sayGreeting() {
		return "Greeting";
	}
}
