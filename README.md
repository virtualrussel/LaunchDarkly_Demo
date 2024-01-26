# LaunchDarkly_Demo
A simple LaunchDarkly + Dynatrace demo website

Requirements for deployment:
* Web hosting platform
  * I leverage Netlify to publish directly from Github
* Dynatrace Tenant
  * For Real User Monitoring create the JS code snippet for Agentless Monitoring
* LaunchDarkly Environment
  * Create two feature flags
    - Blue-Green Flag with the default rule of *on = enabled*
    - User-Tagging Flag with an individual target enabled and a default rule of *on = false*
