# Two-Legged OAuth

This sample shows how use the OAuth 2.0 "client credentials" grant type to return an OAuth
access token for an application based on the application's own credentials. (This is 
sometimes called "two-legged OAuth.") 

It contains the following policies:

1. An OAuth 2.0 policy to generate the access token on a specific URL.

# Set up

* The username and password that you use to login to enterprise.apigee.com.
* The name of the organization in which you have an account. Login to 
  enterprise.apigee.com and check account settings.

# Configure 

1. Update `/setup/setenv.sh` with your environment details

2. Configure API products, developers, and apps in your organization

3. Run `/setup/provisioning/setup.sh`

# Import and deploy sample project

To deploy, run `$ sh deploy.sh`

To test, run `$ sh invoke.sh`

# Get help

For assistance, post to the [Apigee Developer Forum](http://support.apigee.com)

Copyright © 2014 Apigee Corporation

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy
of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
