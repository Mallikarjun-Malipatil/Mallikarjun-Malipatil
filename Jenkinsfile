pipeline {
    agent any
    
    stages {
        stage('BUILD')
		{
        steps
        {
          sh  '''
			#!/bin/bash
			ls-lrt
			pwd
			'''
        }
        }
        stage('TEST')
		{
        steps
        {
          sh 'sleep 5'
        }
        }
        stage('DEPLOY')
		{
        steps
        {
          sh 'sleep 5'
        }
        }
		}
