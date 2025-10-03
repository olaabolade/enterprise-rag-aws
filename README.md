# enterprise-rag-aws
A production-ready Retrieval-Augmented Generation (RAG) system for intelligent document question-answering, built with AWS serverless infrastructure and deployed via Terraform.
# I finally decided on the structure that should work!

# Enterprise RAG System: LLM-Powered Document Intelligence on AWS

# Project Structure

enterprise-rag-aws/  
├──terraform/  
│├── main.tf                
├── variables.tf   
│└── outputs.tf            
├──src/        
│├── app.py               
│├── rag_pipeline.py        
│├── document_processor.py  
│└── requirements.txt      
Python  
├──tests/                    
│└── test_rag.py          
├──docs/                    
│└── architecture.md      
├──deploy.sh                 
├──.gitignore                
└──README.md                 

# Technologies - for now
LLM & AI: Amazon Bedrock, RAG, Prompt Engineering
Cloud: AWS Lambda, S3, API Gateway, IAM
Infrastructure: Terraform, Infrastructure-as-Code.
# hnmm 🤔
