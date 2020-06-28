# Cloud-Infrastructure-Demo
This is a repository to demo some infrastructural architecture done on the cloud using Cloud Providers.

This is a sample infrastructure of an application. This infrastructure is built with AWS you can find it [here](https://app.lucidchart.com/invitations/accept/9fe9821f-76ed-4168-bebe-4cb511874456).

A typical Cloudformation script follows the following pattern

```YAML
Parameters:
  # Parameters are entirely optional.
  # but using them will make your cloudformation templates more reusable
Resources:
  ResourceName:
    ResourceType
    Properties: 
```
