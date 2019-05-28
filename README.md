## Packer

### What is Packer and what is it used for?
Packer is an open source tool that is used for automating the creation of identical machine images. A machine image is a unit that contains a pre-configured operating system and installed software which is used to create virtual machines.


### Continuous Delivery
Packer is 'command-line driven' which means that it is perfect for using in the continuous delivery pipeline.

As part of this pipeline, the newly created images can then be launched and tested. If the tests pass, you can be confident that the image will work when deployed. This brings a new level of stability and testability to infrastructure changes.


### Advantages of using Packer

- Packer is lightweight
- Runs on every Operating System
- Can be used to generate images for multiple platforms at the same time. e.g. If you use AWS for production and VMware for development, you can generate both an AMI (Amazon Machine Image) and a VMware machine using Packer at the same time from the same template.

### Documentation for Packer

https://www.packer.io/docs/index.html
