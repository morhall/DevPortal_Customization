# Apigee Customization Repository Template

##Purpose:
 * Provide a template directory structure for your repository
 * Assist in developing Drupal best practices
 * Ensure a structure that will integrate with Apigee automated deployment processes

### Basic Directory Structure

 * Repository Root - preferably named after your organization
   * devportal -- Developer Portal specific changes
     * files
     * libraries
     * modules
       * custom -- location of your custom modules
       * contrib -- location of contrib modules for your specific portal
     * private
     * themes
     * tmp
   

## Getting Started
 * Download this repository from Github.  
 * Rename the root directory from DevPortal_Customization to something more specific to your organization.
 * Create a new Github repos for your organization based off this directory structure.
 * Start commiting your changes.


## Common Changes

### Custom Modules
If you are needing to create custom modules to support your specific business needs
place those modules in the **modules/custom** directory.

Be sure to follow Drupal development best practices and keep your theme changes distinct from custom modules.

### Contrib Modules
If you need to add special functionality via the thousands of contributor modules available for drupal, 
place those in  repository/devportal/modules/contrib

### Custom Themes
Company Brand is the most common way that customers customize their portal.  A custom
theme can be added to the **themes** directory to give your portal a completely new look and feel
to match your brand.
