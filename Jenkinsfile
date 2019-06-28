#!/usr/bin/env groovy
//Leave the above line alone.  It identifies this as a groovy script.
@Library('vs-build-tools') _

List<String> lvVersions = ['2017', '2018', '2019']

ni.vsbuild.PipelineExecutor.execute(this, lvVersions)
diffPipeline(lvVersions[0])
