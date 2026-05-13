# Tutorial 6: Deploy Custom Scripts & Components

**Network:** Miden Testnet  
**Cost:** $0  
**Funding:** $25M

## Steps

1. Visit [Miden Playground](https://playground.miden.xyz)
2. Start **Tutorial 6**

### Create Script
- Click **Create new script**
- Enter any name (e.g., "Counter Contract")
- Set script type to **Account Component**
- Click **Create**
- Click **Next Step**

### Edit Script
- Scroll to line 32
- Replace `1` with `2`
- Click **Compile**
- Click **Next Step**

### Create Component
- Click **Components** in sidebar
- Click **Create new component**
- Enter any name
- Keep Type as **Account Component**
- Under **Script**, select your script
- Click **Create**
- Click **Next Step**

### Add Storage
- Click **Add storage slot**
- Copy storage slot name from the right side
- Set Type to **Storage Map**
- Click **Add key value pair**
- Set **Key = 1** and **Value = 1**
- Click **Create**
- Click **Next Step**

### Deploy Account
- Click **Accounts**
- Click **Create new account**
- Select **Deploy account**
- Enter contract name
- Select your account component
- Click **Deploy**
- Click **Next Step**

### Invoke Contract
- Click your deployed contract name
- Switch to **Components** tab
- Scroll down and click **Invoke**
- Click **Next Step** → **Next tutorial**

## ✅ Done!
