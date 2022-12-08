# Gravity Payments - emergepay API
Payment integration that’s easy– emergepay provides you with a fast, scalable, cloud-based payment solution.

[emergepay developer documenation](https://dev.gravitypayments.com/docs/emergepay/)<br>
[emergepay demos](https://demo.emergepay.gravitypayments.com/)<br>
<br/>

 # Postman Collection

#### Don't have a Postman Account?
[Create a free Postman Account](https://www.getpostman.com/)

<br/>

## Step 1: Install The Postman App
:exclamation: This collection only work with the installed version of The Postman app.
<br/>
[Download the app](https://www.postman.com/downloads)<br>


## Step 2: Review the emergepay API documentation
[API Reference](https://dev.gravitypayments.com/reference/)


## Step 3: Get the Postman collection

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/21195321-d4db0328-fc77-4f29-b1d5-ecc6d25f197b?action=collection%2Ffork&collection-url=entityId%3D21195321-d4db0328-fc77-4f29-b1d5-ecc6d25f197b%26entityType%3Dcollection%26workspaceId%3D91a447ee-7549-4f7a-a79c-be3e91d8de9a#?env%5BEmergepay%20API%5D=W3sia2V5IjoiQXV0aFRva2VuIiwidmFsdWUiOiJleUpoYkdjaU9pSklVekkxTmlJc0luUjVjQ0k2SWtwWFZDSjkuZXlKMGFXUWlPalU1TVN3aWIybGtJam94TWpVeE5URTBNalkzTENKMGIydGxibDkxYzJVaU9pSnZjblFpTENKeWJtUWlPakU1T0RJME5UazRNekl1T0RJME5ETTROaXdpWjNKdmRYQnpJanBiSWs5eVowRlFTVlZ6WlhKeklsMHNJbWxoZENJNk1UWXpOVGczTXpBd05uMC54SlFkR1d5Wm90MnUzdWd5WnJLMTBLdFNHNHZMdGtGM0JlTjlvV3o1TnNFIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiJleUpoYkdjaU9pSklVekkxTmlJc0luUjVjQ0k2SWtwWFZDSjkuZXlKMGFXUWlPalU1TVN3aWIybGtJam94TWpVeE5URTBNalkzTENKMGIydGxibDkxYzJVaU9pSnZjblFpTENKeWJtUWlPakU1T0RJME5UazRNekl1T0RJME5ETTROaXdpWjNKdi4uLiIsInNlc3Npb25JbmRleCI6MH0seyJrZXkiOiJPSUQiLCJ2YWx1ZSI6IjEyNTE1MTQyNjciLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IjEyNTE1MTQyNjciLCJzZXNzaW9uSW5kZXgiOjF9LHsia2V5IjoiZGV2aWNlX25hbWUiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoyfSx7ImtleSI6ImV4dGVybmFsVHJhbnNhY3Rpb25JZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiI1NTQ5MmFlZC03MjI2LTQzN2YtYjhiOS0wODEzYzMwMGI0MzIiLCJzZXNzaW9uSW5kZXgiOjN9LHsia2V5IjoidHJhbnNhY3Rpb25Ub2tlbiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiI2OTg3NWQwMmU1MWE0MDI3YmUzZTgyOGQ5NzRiNWQ1ZCIsInNlc3Npb25JbmRleCI6NH0seyJrZXkiOiJ1bmlxdWVUcmFuc0lkIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6ImYyNWNkOWMzYjVjOTQwOWQ4YjU1YmZiOTcwMmUwYjAzLWUzNzI5NTYwNDllYTRjMjdhMjU1M2JmODA2NzYwOTcxIiwic2Vzc2lvbkluZGV4Ijo1fSx7ImtleSI6ImFwcHJvdmFsTnVtYmVyUmVzdWx0IiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6Ik9LMDczMiIsInNlc3Npb25JbmRleCI6Nn0seyJrZXkiOiJwYXltZW50UGFnZVVybCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjd9LHsia2V5IjoicGF5bWVudFBhZ2VJZCIsInZhbHVlIjoiIiwiZW5hYmxlZCI6dHJ1ZSwidHlwZSI6ImRlZmF1bHQiLCJzZXNzaW9uVmFsdWUiOiIiLCJzZXNzaW9uSW5kZXgiOjh9LHsia2V5IjoiaW1hZ2VCYXNlNjRBIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlLCJ0eXBlIjoiZGVmYXVsdCIsInNlc3Npb25WYWx1ZSI6IiIsInNlc3Npb25JbmRleCI6OX0seyJrZXkiOiJpbWFnZUJhc2U2NEIiLCJ2YWx1ZSI6IiIsImVuYWJsZWQiOnRydWUsInR5cGUiOiJkZWZhdWx0Iiwic2Vzc2lvblZhbHVlIjoiIiwic2Vzc2lvbkluZGV4IjoxMH1d)

## Step 4: Set the active environment to "Emergepay API"

<img width="1074" alt="image" src="https://user-images.githubusercontent.com/108539652/206423851-2868a844-4fb9-4cd0-b2f6-0571f08a95ab.png">

## Step 5: Run your first collection

