---
title: "2023.02.06-2023.02.10工作周报"
date: 2023-02-10T00:00:00+00:00
author: 李承前
layout: post
permalink: /2023.02.06-2023.02.10工作周报/
categories: Genel
tags: [李承前, 2023.02.10]
---
本周，完成在个人博客添加代码功能开发，效果如下：

{% highlight c %}
#include <stdio.h>

//Function declarations
int is_prime(int n);
void goldbach(int g);

int main(){
	int number = 0;
	while(1){
		printf("Enter even number:");
		scanf("%d",&number);
		if(number>2 && number%2==0){
			goldbach(number);
		}
		else{
			printf("Incorrect number!");
		}
		printf("");
	}
	return 0;
}

{% endhighlight %}
