# chefconf2015_demoapp-cookbook

This cookbook deploys demoapp.

## Supported Platforms

RHEL, ubuntu.

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['chefconf2015_demoapp']['version']</tt></td>
    <td>String</td>
    <td>Version of demoapp</td>
    <td><tt>1.0.0</tt></td>
  </tr> 
</table> 
 
## Usage 

### chefconf2015_demoapp::default

Include `chefconf2015_demoapp` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chefconf2015_demoapp::default]"
  ]
}
``` 

## License and Authors

Author:: Intuchef (intuchef@intuit.com)


X
