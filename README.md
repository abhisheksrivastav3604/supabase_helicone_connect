# Aim: The aim is to connect Supabase to Helicone and fix errors in the Sign-in and Sign-up processes of Helicone.


## Steps to Follow:

1. cd web: This command changes the current directory to the "web" directory.

2. supabase start : This will start the Supabase server on  local machine.

3. Create a .env file is in web/.env. Here is an example:

`
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=""
STRIPE_SECRET_KEY=""
NEXT_PUBLIC_HELICONE_BILLING_PORTAL_LINK=""
NEXT_PUBLIC_HELICONE_CONTACT_LINK="https://calendly.com/d/x5d-9q9-v7x/helicone-discovery-call"
STRIPE_PRICE_ID=""
STRIPE_STARTER_PRICE_ID=""
STRIPE_ENTERPRISE_PRODUCT_ID=""
STRIPE_STARTER_PRODUCT_ID=""
DATABASE_URL="postgresql://postgres:postgres@localhost:54322/postgres"
NEXT_PUBLIC_SUPABASE_ANON_KEY="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZS1kZW1vIiwicm9sZSI6ImFub24iLCJleHAiOjE5ODM4MTI5OTZ9.CRXP1A7WOeoJeXxjNni43kdQwgnWNReilDMblYTn_I0"
NEXT_PUBLIC_SUPABASE_URL="http://localhost:54321"
SUPABASE_URL="http://localhost:54321"
SUPABASE_SERVICE_KEY="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZS1kZW1vIiwicm9sZSI6InNlcnZpY2Vfcm9sZSIsImV4cCI6MTk4MzgxMjk5Nn0.EGIM96RAZx35lJzdJsyH-qQwv8Hdp7fsn3W0YpN81IU"
`

4. yarn and yarn dev: 
    These commands are used to install project dependencies and start the frontend application. 
  
    The yarn dev command is often used in development environments to launch the application in development mode.

  
5.  In Other Terminal

    cd worker: Changes the current directory to the "worker" directory.

    yarn and wrangler dev --local


Now you can go to localhost:3000 and create an account.

When creating an account on localhost, you will automatically be signed in.




