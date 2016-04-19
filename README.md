#Nexus OSS

Install Nexus Repository Manager OSS

- http://www.sonatype.com/nexus-repository-oss

#Requirements

* `java`

#Role variables

* `nexus_oss_group`: nexus
* `nexus_oss_user`: nexus
* `nexus_oss_installation_dir`: /opt/srv/nexus
* `nexus_oss_working_dir`: /opt/data/nexus
* `nexus_oss_context_path`: /nexus
* `nexus_oss_version`: '2.12.0-01'
* `nexus_oss_port`: 8081

#Dependencies

None

#Example Playbook


	- hosts: selenium
	  become: true
	  roles:
	    - netzwirt.nexus-oos



#License

BSD

#Author Information

[netzwirt](https://github.com/netzwirt)

