#!/usr/bin/env groovy

@Library('longhorn-shared-library') _


dockerPipeline {
    imageName = "ad-test"
    chartName = "ad-test"
    checkoutDir = 'src/bitbucket-eng-sjc1.cisco.com/bitbucket/nextg/adapter-test'
    skipAutomationTests = true
    goVersion = '1.13'
}

