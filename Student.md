package com.utkarsh.springbootlearninglab.model;

public class Student {
    
    private int id;
    private int age;
    private String email;
    private String name;

    public Student(int id,int age,String email, String name){
        this.id=id;
        this.age=age;
        this.email=email;
        this.name=name;
    }
    
    public int getId(){
        return id;
    }

    public void setId(int id){
        this.id=id;
    }

    public int getAge(){
        return age;
    }

    public void setAge(int age){
        this.age=age;
    }

    public String getName(){
        return name;
    }

    public void setName(String name){
        this.name=name;
    }

    public String getEmail(){
        return email;
    }

    public void setEmail(String email){
        this.email=email;
    }

}

// we will do the rest of the changes tomorrow 