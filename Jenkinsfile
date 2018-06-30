#!groovy​
pipeline {
    agent test_node
        stages {
            stage ('Ansible Code checkout ') {
                steps {
                    echo "Hello checkout" 
                      }
                }
            stage ('package stage') {
                steps {
                  echo "second stage"
                  }
                }
            stage ('archive stage') {
                steps {
                echo "deployed"                  
            }
          }
        }
  }
