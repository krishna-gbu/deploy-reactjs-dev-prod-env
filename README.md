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

