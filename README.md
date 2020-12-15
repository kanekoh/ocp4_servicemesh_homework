## How to deploy the bookinfo application

```
$ ansible-playbook -i hosts/localhsot.ini homework.yaml
```

## Structure

### Roles

|Role Name|Notes|
|-|-|
|bookinfo|Deploying the bookinfo application and create new project for bookinfo|
|smmr|Setup ServiceMesh MemberRole and auto injection|
|security|Setup mTLS and Security to the application|
