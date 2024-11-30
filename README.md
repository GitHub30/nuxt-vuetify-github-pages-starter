# Nuxt Vuetify GitHub Pages Minimal Starter

[Demo](https://youtu.be/vrkbt1L4VJI)

# How to use

## Deploy

<details><summary>1. Create a new repository</summary>

![image](https://github.com/user-attachments/assets/8c55d303-c2f0-4ede-b83e-0f078fa49b98)
</details>

<details><summary>2. Create repository</summary>

![image](https://github.com/user-attachments/assets/24706f61-9e47-4783-b4e9-ddd80e0ba66f)
</details>

<details><summary>3. Goto Settings > Pages > Enable GitHub Pages</summary>

![image](https://github.com/user-attachments/assets/79abdc10-104f-4af2-aaa1-ef619d2c3545)
</details>

<details><summary>4. Goto Actions > Deploy to GitHub Pages > Run workflow</summary>

![image](https://github.com/user-attachments/assets/9c133641-b2b9-4cd2-a076-0f8f4613c175)
Published to `https://<username>.github.io/<repository>/`.
![image](https://github.com/user-attachments/assets/98211736-a675-4911-b7db-94800508ddfd)

If you are using a custom domain or `https://<username>.github.io/`, remove NUXT_APP_BASE_URL
https://github.com/GitHub30/nuxt-vuetify-github-pages-starter/blob/5e3a16a08970477912fe8d7684499041d6e3f461/.github/workflows/deploy.yml#L19-L22
</details>

## Develop

<details><summary>1. Create codespace on main</summary>

![image](https://github.com/user-attachments/assets/11c50783-cdf0-463e-9574-a805161beaa2)
</details>

<details><summary>2. Open in browser</summary>
  
![image](https://github.com/user-attachments/assets/1185559a-a202-4cd8-b482-d41983443ad5)
</details>

# Contribution

<details><summary>How to create this repository</summary>
  
```bash
npx --yes nuxi@latest init --packageManager npm --gitInit .
npx nuxi@latest module add vuetify-nuxt-module
# Add https://github.com/GitHub30/nuxt-vuetify-github-pages-starter/blob/main/.github/workflows/deploy.yml
# Add https://github.com/GitHub30/nuxt-vuetify-github-pages-starter/blob/main/.devcontainer/devcontainer.json
```

Get started with Vuetify 3
https://vuetifyjs.com/en/getting-started/installation/#manual-setup

Deploy Nuxt to GitHub Pages
https://nuxt.com/deploy/github-pages
</details>
