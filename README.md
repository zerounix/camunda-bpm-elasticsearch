camunda BPM - ElasticSearch extension
===========================

[![Build Status](https://drone.io/github.com/camunda/camunda-bpm-elasticsearch/status.png)](https://drone.io/github.com/camunda/camunda-bpm-elasticsearch/latest)

camunda-bpm-elasticsearch combines the camunda-bpm platform with the powerful search capabilities of ElasticSearch.
It comes with a process engine plugin which indexes all generated history events through ElasticSearch.
To use the indexed data, a cockpit plugin is also provided to allow querying and retrieval of process instances through ElasticSearch.

Documentation
-------------

Read the [User Guide](docs/userguide.md).

Components (Modules)
--------------------
<table>
  <tr>
    <th>Module</th><th>Description</th>
  </tr>
  <tr>
    <td>elasticsearch-cockpit-plugin</td><td>Integration of ElasticSearch with camunda BPM cockpit as a cockpit plugin.</td>
  </tr>
  <tr>
    <td>elasticsearch-engine-integration</td><td>Integration of ElasticSearch with camunda BPM engine as a process engine plugin.</td>
  </tr>
  <tr>
    <td>elasticsearch-jboss-module</td><td>Produces in its target directory a folder named modules with all required libraries to use with JBoss 7.x.</td>
  </tr>
  <tr>
      <td>elasticsearch-lib-module</td><td>Produces in its target directory a folder with all required libraries to drop into Tomcat's lib directory.</td>
    </tr>
</table>

