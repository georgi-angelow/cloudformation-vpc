aws cloudformation create-stack --stack-name developmentVPC --template-body file://vpc.yaml --profile example

aws cloudformation delete-stack --stack-name developmentVPC --profile example