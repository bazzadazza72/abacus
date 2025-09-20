# Connecting to Firefly III

> [!IMPORTANT]
> If you are using an external authentication provider like Authelia, OAuth clients will not work. You will need to create and use a [personal access token](#using-a-personal-access-token) instead.

## Using an OAuth application

![img_1.png](HELP/img_1.png)
1. In Firefly III, go to `/profile`.

2. Create a new OAuth client by clicking `Create new Client`. Enter this redirect URI in the `Redirect URL` box: `abacusfiiiapp://redirect` then click Create.

![img.png](HELP/img.png)

3. Copy and paste `Oauth Client ID` it will be a number (required, Example: `4`).

> [!NOTE]
> If you chose to enable the `Confidential` box in step 2, you will need to copy the secret and paste it into the `Oauth Client Secret` field.

<img alt="img_2.jpeg" height="670" src="HELP/img_2.jpeg" width="300"/>

## Using a personal access token

1. In Firefly III, go to your profile page by clicking `Options > Profile`.
2. Under Personal Access Tokens, click `Create new token`.
3. 

<img width="840" alt="image" src="https://github.com/victorbalssa/abacus/assets/12813321/f92c8bba-5c48-4b5c-b2be-5eddfb53e6f2">

copy:

<img width="823" alt="image" src="https://github.com/victorbalssa/abacus/assets/12813321/ae91cb88-b994-48ab-87b6-f77d11a99cbd">

paste:

<img width="390" alt="image" src="https://github.com/victorbalssa/abacus/assets/12813321/f8ea01bd-40c2-4f1f-ac95-6be4f2ae9a47">
