# Project Title

This is a project from the #DevOpsAllStarChallenge 🚀. This is the day1 project. Got 29 more projects to complete. The application is about collection data about the weather api and storing it inside an s3 bucket for easy retrieval.

## System Design

![System Design](images/weather.png)

## Installation

Install my-project with npm

```bash
 uv venv day-env --python 3.11
source day-env/bin/activate
uv pip install -r requirements.txt
```

## AWS QuickSight Integration

To visualize the weather data stored in the S3 bucket, you can use AWS QuickSight.

### Steps to Integrate AWS QuickSight

1. **Prepare the Data**: Ensure your weather data in S3 is in a format that QuickSight can read, such as JSON or CSV.

2. **Create a Dataset in QuickSight**:

   - Log in to the AWS Management Console.
   - Open the QuickSight console.
   - Choose **Manage data** and then **New data set**.
   - Choose **S3** as the data source.
   - Provide the S3 bucket name and the path to your weather data files.
   - Follow the prompts to create the dataset.

3. **Create an Analysis**:

   - In QuickSight, choose **New analysis**.
   - Select the dataset you created.
   - Use the QuickSight interface to create visualizations, such as charts and graphs, to analyze your weather data.

4. **Embed QuickSight Dashboard** (Optional):
   - You can embed QuickSight dashboards into your application if needed. Refer to the [AWS QuickSight Embedding SDK](https://docs.aws.amazon.com/quicksight/latest/user/embedding-overview.html) for more details.
