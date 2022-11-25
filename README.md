#jenkins docker ec2 reactjs

## launch ec2 instance , here I am using ubuntu(22.04lts)

![image](https://user-images.githubusercontent.com/40553867/201889291-6f307913-2cdd-4335-a70b-25926bc2e893.png)

## connect instance with jenkins
![image](https://user-images.githubusercontent.com/40553867/201889682-ce0430ee-4571-4cf0-919f-6d09b2b5b1cc.png)

## create reactjs repo
![image](https://user-images.githubusercontent.com/40553867/201889965-3aca7337-a526-4322-a7f8-d7d1866a75bf.png)

```
npx create-react-app jenkins_docker_ec2_reactjs
```

## push to github 

```
git add .
git commit -m first 
git remote add origin https://github.com/krishna-gbu/jenkins_docker_ec2_reactjs.git
git push --set-upstream origin main
git push
```

## create instance and connect throught ssh
![image](https://user-images.githubusercontent.com/40553867/204035440-f24c81c2-138e-4048-8878-671ecef0f970.png)

![image](https://user-images.githubusercontent.com/40553867/204035606-af562509-dbf2-488f-920b-c07d961376e0.png)

## install nodejs and check version

```
curl -fsSL https://deb.nodesource.com/setup_18.x | bash - 
sudo apt-get install -y nodejs
```

![image](https://user-images.githubusercontent.com/40553867/204036207-6a85208f-71da-4c41-8140-1755a5c6fe70.png)

## create-react-app 
### option 1 
![image](https://user-images.githubusercontent.com/40553867/204036832-5facd3a9-b7c8-474f-81aa-4c47493a00fb.png)

![image](https://user-images.githubusercontent.com/40553867/204036879-c528cfaf-2e59-4e79-bf66-4b8bd19d5d7b.png)

![image](https://user-images.githubusercontent.com/40553867/204037300-111a9acd-205f-4bf2-a7e2-5ccf77d45fff.png)


### option 2

![image](https://user-images.githubusercontent.com/40553867/204038964-18eebeb9-6bb3-4936-a115-0cd7df198b54.png)

![image](https://user-images.githubusercontent.com/40553867/204041649-4258717e-3422-4500-838f-a192f13a0b76.png)

![image](https://user-images.githubusercontent.com/40553867/204041857-75659387-9d44-496b-a21e-e4b518460f19.png)

![image](https://user-images.githubusercontent.com/40553867/204041912-1f52da49-e44a-4a28-8a54-a5924fb64fdd.png)

![image](https://user-images.githubusercontent.com/40553867/204042166-b9a6b52f-c5cc-4435-94de-0e16934b62d2.png)

![image](https://user-images.githubusercontent.com/40553867/204042356-87e7a4ca-29ee-471a-92f6-decec2c68412.png)
