# automate-jenkins

```sh
git clone https://github.com/dihogoteixeira/automate-jenkins.git
cd automate-jenkins
```

Change value in variable `dockerhub_user` on `setup-and-run.sh` local file

```yaml
.
├── Dockerfile
├── README.md
├── config
│   ├── authentication.properties
│   ├── credentials.properties
│   ├── globals.properties
│   ├── initial-jobs.properties
│   └── tools.properties
├── groovy
│   ├── credentials.groovy
│   ├── globalconfig.groovy
│   ├── helpers.groovy
│   ├── initialjobs.groovy
│   ├── java.groovy
│   ├── maven.groovy
│   ├── scriptSecurity.groovy
│   └── securityOwnDB.groovy
├── plugins.txt
└── setup-and-run.sh
```

Just run local `setup-and-run.sh` script:

```sh
sh setup-and-run.sh
```

url: http://localhost:8080

```yaml
user1: jenkins
user2: hudson
passwd: Br@s1l2021
```