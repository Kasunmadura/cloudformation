## Cloudformation

This repo for my Cloudformation tesing and implement few best practiese.


### Basic Template

1. template is a declaration of the AWS resources that make up a stack.
2. Resources are declared in a template
3. Resources map to a stack
4. Declare object as a name-value pair or a pairing of a name with a set of child objects enclosed.
5. The Resources object is the only required object


eg: YAML

    Resources:
      KasunBucket:
        Type:AWS::S3::Bucket



### Template Anatomy

 Template Sections:
 
1. AWSTemplatedFormatVersion
2. DesCription -A text string that Describes the Template
3. Metadata - Objects that provide addtional information about the template
4. Parameters- Specifies values that you can pass into your tempalate at runtime
5. Mappings - A mapping of keys and associated values that you can use to specify conditional parameter values, similar to lookup tables.
6. Conditions - Defines conditions that control whether certain resources are created or whether certain resources properties are assigned a value during stack creation or update
7. Transform - for serverless appications, specifies the version to use
8. Resources - specifies that stack resources and their properties
9. Outputs - Describes the values that are returned whenever you view your stack's properties
