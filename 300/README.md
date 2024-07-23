# 300 - Building Our Application

TRANSCRIPT

Watch how I set up a folder to be a terraform solution.

I create a variables file.

```

```
variables.tf

I declare main.

```

```
main.tf

I declare an outputs.

```

```
outputs.tf

Terraform works up a folder, takes inputs, and produces outputs.

I run terraform init

```
$ terraform init
```

```Init``` loads providers and downloads modules per on terraform plan.

Plan is a read-only operation that analyzes dependencies and sequences a plan of steps to execute across all the providers you play within your solution.

I run terraform apply.

```
$ terraform apply
```

```Apply``` executes that plan and returns outputs from prospective resources.

That's it!