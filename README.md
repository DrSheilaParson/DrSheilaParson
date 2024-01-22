- 👋 Hello, I’m @DrSheilaParson 
- 👀 I’m interested in Leadership Training, Brand Advising, Digital Marketing & Human Resources ...
- 🌱 I’m currently learning Marketing  ...
- 💞️ I’m looking to collaborate on Learning More ...
- 📫 How to reach me theqsagroup@gmail.com...
- 😄 Pronouns: she/her ...
- ⚡ Fun fact: I was enlisted in the US Army and then went to Officer Candidate school and served in two wars...

<!---
DrSheilaParson/DrSheilaParson is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
curl https://api.openai.com/v1/images/generations \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer $OPENAI_API_KEY" \
  -d '{
    "model": "dall-e-3",
    "prompt": "A cute baby sea otter",
    "n": 1,
    "size": "1024x1024"
  }'
