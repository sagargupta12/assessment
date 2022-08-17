# Technical Assessment

This repository contains the Cloudformation File which deploys an API Gateway & Lambda Function. The purpose of the resources is to host an API Endpoint which 

## Overview

Once the API Endpoint is called, the API in turn triggers a Lambda Function which transforms the string received in query parameter `string` and returns the transformed string. An example of the transformation is: Google will be replaced for Google©. 
