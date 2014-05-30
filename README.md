# BOSH Release for mongodb

## Table of Contents
* [Usage](#usage)
* [Releases](#releases)
<br />
<br />


### <a name="usage"></a>Usage

To use this bosh release, first upload it to your bosh:

```
bosh target BOSH_HOST
git clone ssh://git@stash.hybris.com:7999/idefix/bosh-release-mongodb.git
cd bosh-release-mongodb
bosh upload release releases/mongodb-hybris-1.yml
```

### <a name="releases"></a>Releases
<table>
  <tr>
    <th>Date</th>
    <th>Name</th>
    <th>Version</th>
    <th>Kafka</th>
    <th>Comment</th>
  </tr>
  <tr>
    <td>2014-05-29</td>
    <td>mongodb-hybris</td>
    <td>1</td>
    <td>mongodb 2.6.1</td>
    <td>Initial release</td>
  </tr>
</table>