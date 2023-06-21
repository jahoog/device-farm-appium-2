# About Appium 2 on Device Farm
As of 21-June-2023:
- Appium 2 just released RC.3
- Appium 2 is not included as a template in Appium tests in device farm (see https://docs.aws.amazon.com/devicefarm/latest/developerguide/test-types-appium.html)
- Appium 2 can be ran using a custom environment in AWS device farm (see https://docs.aws.amazon.com/devicefarm/latest/developerguide/custom-test-environments.html)

## Example test spec files for Appium 2:
 - iOS: https://repost.aws/questions/QUlK5xNrTmSgq54_VYH06Btg/how-to-work-with-appium-2-0-with-aws-device-farm
 - Android: https://github.com/jahoog/device-farm-appium-2/blob/main/appium-2-test-spec-node-js.yml

Basically, all the custom test spec file is change the installed release of Appium and then modifies prefix parameters that are required for Appium 2 server.
