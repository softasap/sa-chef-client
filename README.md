sa-chef-client
==============

[![Build Status](https://travis-ci.org/softasap/sa-chef-client.svg?branch=master)](https://travis-ci.org/softasap/sa-chef-client)


Tests cover LTS releases only

Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-chef-client"
      }


Advanced:


  roles:
    - {
        role: "sa-chef-client",
        chef_client_version: "12.10.24"
      }
