# Creating Custom Terraform Providers

As my work colleagues might attest, I like Terraform Providers.

Much with all things in life though, a little moderation goes a long way.

To that end then, before embarking upon the ultimate quest for custom terraform provider glory, be sure to ask yourself:
 
> Do I really need this?


### Recognising Terraform's Strengths...

I really appreciate Terraform's ability to do the following:

- Manage the entire lifecycle of stateless infrastructure
- Provide a common mental model when dealing with a variety of infrastructure as code (as long as someone has implemented the provider)

Others are quick to point out it is sometimes difficult with terraform to:

- Manage the state of existing infrastructure that was not created with Terraform
- Manage long running infrastucture that may or may not have accrued manual changes, or may or may not have complex state


### You got this far so , why don't we write one

```
Code time
```

### Resources and Actions

- Read the Custom Terraform Provider Doc...
- Read an existing provider.. Start small: try terraform-providers-random
- Read a slightly bigger provider.. try terraform-providers-digitalocean


