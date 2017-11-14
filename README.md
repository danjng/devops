# Purpose

The purpose of this repository is to capture all of the work involved with establishing a DevOps pipeline.

# Contents

Contents include:
  *Vagrantfile

## Dockerfile

This file will define the infrastructure of this project. Using vagrant, it will provision all of the infrastructure necessary to host the DevOps pipeline being developed.

Vagrant will provision:
  *An instance of GitLab Community Edition
  *An instance of Jenkins Open Source
  *An instance of Cucumber and Selenium