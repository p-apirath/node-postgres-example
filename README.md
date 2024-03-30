
## Note for nodejs-postgres-example


```sh

# https://www.bezkoder.com/docker-compose-nodejs-postgres/
git clone https://github.com/bezkoder/node-js-postgresql-crud-example.git

```

```sh

docker-compose up -d && docker-compose logs -f ; docker-compose down -v --rmi all

```

---

## Pros and Cons: Jenkins vs Bitbucket Pipelines vs GitHub Actions

### Jenkins

**- Pros**

1. Hosted internally

2. Free and open source

3. Great to build, deploy or launch anything async

4. Tons of integrations and Many Plugins

5. Has support for build pipelines

6. Large Community

7. Configuration as code

8. Great flexibility

**- Cons**

1. Workarounds needed for basic requirements

2. Groovy with cumbersome syntax

3. Plugins compatibility issues

4. Lack of support

5. Limited abilities with declarative pipelines

6. No YAML syntax

### Bitbucket Pipelines

**- Pros**

1. Hosted internally

2. Best Jira integration possible

3. Software as a Service

4. Dedicated tehnical support

5. Containers Support

6. Auditing

**- Cons**

1. Small Community

2. Pricing is based on amount of users for both the cloud and on premise versions.

### GitHub Actions

**- Pros**

1. Integration with GitHub

2. YAML Syntax

3. Free

4. Easy to duplicate a workflow

5. Configs stored in .github

6. Containers Support

7. Largest Community

**- Cons**

1. Lacking allow failure

2. Lacking job specific badges

3. No ssh login to servers

4. No Deployment Projects

5. No manual launch

---