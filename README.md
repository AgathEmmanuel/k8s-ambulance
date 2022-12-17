# k8s-ambulance


An ambulance for your k8s cluster to serve emergency purposes




## Controllers VS Operators  


A control loop is the fundamental building block of industrial control systems.  
It consists of all the physical components and control functions necessary to automatically adjust the value of a measured process variable (PV) to equal the value of a desired set-point (SP)  


The Operator pattern aims to capture the key aim of a human operator who is managing a service or set of services.  

However, the term was originally coined by CoreOS with a very specific meaning:  
An Operator is a method of packaging, deploying and managing a Kubernetes application.  

Furthermore, the Kubernetes documentation also states a few requirements for some controller to fall into the Operator pattern category.  

    Operators make use of the controller pattern.  
    Operators make use of Custom Resources to extend the Kubernetes API.  
    Operators are focused on a single application and its components.  


# Steps  


```

https://kubernetes.io/blog/2021/06/21/writing-a-controller-for-pod-labels/


operator-sdk init --domain=agathemmanuel.github.io --repo=github.com/agathemmanuel/k8s-ambulance
```

# Links  

[https://kubernetes.io/blog/2021/06/21/writing-a-controller-for-pod-labels/](https://kubernetes.io/blog/2021/06/21/writing-a-controller-for-pod-labels/)  

