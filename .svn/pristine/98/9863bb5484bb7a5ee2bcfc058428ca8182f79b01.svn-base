package com.app;

import org.springframework.context.ApplicationContext;
import org.springframework.context.support.ClassPathXmlApplicationContext;

public class Test {

	public static void main(String[] args) {
		ApplicationContext ac=new ClassPathXmlApplicationContext("Config.xml");
		Object ob=ac.getBean("empobj");  
		Employee emps=(Employee)ob;
		System.out.println(emps);
		
		

	}

}
