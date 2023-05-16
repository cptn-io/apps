# cptn.io Apps

This repository powers the Apps downloaded to all cptn.io instances. Ready-to-use apps downloaded to cptn.io instances allows users to quickly setup integrations or refer example implementations in the Apps and build new integrations.

## Contributing Apps

Starting with Alameda release, any user can contribute apps to the community. 

### Downloading App JSON

Simply create a Transformation or define a Destination on your instance (ensure that your scripts do not include credentials or any other private data) and click 'Export As App' button on the destination/transformation details page.

The Transformation or Destination defined on your instance is automatically downloaded as an App JSON file. A JSON file will be downloaded to your machine.

Update logoUrl (if applicable) attribute in the downloaded JSON file. We use brand logo icons at https://simpleicons.org/ for the apps, if applicable. SimpleIcons are hosted on CDN and accessible via https://cdn.simpleicons.org/<slug-id> (e.g. https://cdn.simpleicons.org/twilio)
  
### Create a PR
Create a new Pull Request for your Apps in this repo to *dev* branch. Add any testing instructions (if applicable) to the PR. If your service requires credentials for testing, send the instructions to support@devraven.io
  
We will review the PR, test and merge the PR to dev and main branches.
  
### Installation of Apps
Each cptn.io instance polls the repo at regular intervals to check for new apps and updates. 
  
Once an App JSON file is merged into main branch, all cptn.io instances will automatically receive the App in few hours.

## License
By checking in any content to this repository, you are agreeing to share the content with the community under MIT license (as defined in LICENSE file). 
  
DO NOT PUSH ANY PROPRIETARY CODE OR CODE UNDER DIFFERENT LICENSE TO THIS REPO.
