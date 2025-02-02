# Starter Workflows for ServiceNow CI/CD using GitHub Actions

These are the workflow files for helping people get started with GitHub Actions when building applications on the Now Platform.

Just copy and paste into your pipeline once your workflow is created for your application's linked GitHub repo. 

## Description of workflow templates
- [workflow.yml](https://github.com/ServiceNow/sncicd_githubworkflow/blob/master/workflow.yml) Standard example to start from with 3 stages - build, test, deploy to prod. First two runs for CI on feature branch PR. All 3 run for CD on master branch update. 
- [workflow_publish_with_detect.yml](https://github.com/ServiceNow/sncicd_githubworkflow/blob/master/workflow_publish_with_detect.yml) Example for how to use the "detect" option with the ServiceNow/sncicd-publish-app GitHub Action. This is necessary for the repo source to be populated into the runner environment. 
- [workflow_scan_instance.yml](https://github.com/ServiceNow/sncicd_githubworkflow/blob/master/workflow_scan_instance.yml) Standard example to start working with Scan Instance action.
- [workflow_batch_install.yml](https://github.com/ServiceNow/sncicd_githubworkflow/blob/master/workflow_batch_install.yml) Standard example to start working with Batch Install action. [Example of payload](https://github.com/ServiceNow/sncicd_githubworkflow/blob/master/batch_payload.json).

## Marketplace

- https://github.com/marketplace/actions/servicenow-ci-cd-apply-changes
- https://github.com/marketplace/actions/servicenow-ci-cd-install-app
- https://github.com/marketplace/actions/servicenow-ci-cd-publish-app
- https://github.com/marketplace/actions/servicenow-ci-cd-rollback-app
- https://github.com/marketplace/actions/servicenow-ci-cd-run-atf-test-suite
- https://github.com/marketplace/actions/servicenow-ci-cd-activate-plugin
- https://github.com/marketplace/actions/servicenow-ci-cd-rollback-plugin
- <Add Batch Install Action After Publication>
- <Add Scan Instance Action After Publication>

## Repos
- https://github.com/ServiceNow/sncicd-apply-changes
- https://github.com/ServiceNow/sncicd-install-app
- https://github.com/ServiceNow/sncicd-publish-app
- https://github.com/ServiceNow/sncicd-rollback-app
- https://github.com/ServiceNow/sncicd-tests-run
- https://github.com/ServiceNow/sncicd-plugin-activate
- https://github.com/ServiceNow/sncicd-plugin-rollback
- https://github.com/ServiceNow/sncicd-batch-install
- https://github.com/ServiceNow/sncicd-instance-scan

## Support Model

ServiceNow built this integration with the intent to help customers get started faster in adopting CI/CD APIs for DevOps workflows, but __will not be providing formal support__. This integration is therefore considered "use at your own risk", and will rely on the open-source community to help drive fixes and feature enhancements via Issues. Occasionally, ServiceNow may choose to contribute to the open-source project to help address the highest priority Issues, and will do our best to keep the integrations updated with the latest API changes shipped with family releases. This is a good opportunity for our customers and community developers to step up and help drive iteration and improvement on these open-source integrations for everyone's benefit. 

## Governance Model

Initially, ServiceNow product management and engineering representatives will own governance of these integrations to ensure consistency with roadmap direction. In the longer term, we hope that contributors from customers and our community developers will help to guide prioritization and maintenance of these integrations. At that point, this governance model can be updated to reflect a broader pool of contributors and maintainers. 
