package com.example.demo.controllers;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController 
public class Home{
  @GetMapping("/")
 public String indexPage() {
    return "<h1>Hello from index page</h1>";
    }
}
