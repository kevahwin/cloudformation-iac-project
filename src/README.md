# CD12352 - Infrastructure as Code Project Solution
## Kevin Ahwin

## Spin up instructions
To spin up the infrastructure, run the following command:

```sh
./run.sh deploy <region> <stack-name> <template-file> <parameters-file>
```

Make sure to replace <region>, <stack-name>, <template-file>, and <parameters-file> with your specific region, stack name, template file, and parameters file.

## Tear down instructions
To tear down the infrastructure, run the following command:
```sh
./run.sh delete <region> <stack-name>
```

## Other considerations
Note: Before running the script, ensure it has execute permissions by running:

```sh
chmod +x run.sh
```