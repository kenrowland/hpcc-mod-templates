# HPCC Environment XML Modification Templates
As advanced features have been added to the HPCCSystems (c) platform, these changes also require additions to the _environment.xml_ file when running in legacy non-containerized environments. Some of these changes cannot be added or changed using the existing congiruation tools. In order to support making these changes w/o directly editing the XML, the _envmod_ command line tool is used. This tool uses an input modification template that instructs the tool how to make the necessary changes. 

This repository serves as a location for some standard modification templates.
