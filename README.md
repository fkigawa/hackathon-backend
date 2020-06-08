To get this repo up and running, complete the following instructions:

1. Create .env file in root directory. Initialize two variables using the following form:

'''
MONGODB_URI="<INPUT URI HERE>"
TOKEN_SECRET="<INPUT TOKEN HERE>"
'''

2. Run the following commands:

'''
rm -rf ./node_modules
npm install --save
npm run dev
'''

The backend should now be up and running.
