# Gaianet-Node-Guide

# GaiaNet Node Setup Guide

## 1. Register on GaiaNet

Visit the GaiaNet website and register using the following link:
[GaiaNet Registration](https://gaianet.ai/reward?invite_code=RgJNzz)

- Use this invite code for a boost: **RgJNzz**
- Complete social tasks under the **Gaia XP** tab to earn more points.

---

## 2. Install the GaiaNet Node

To install the official GaiaNet Node CLI, run the following command:

```sh
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

After installation, apply the changes by running:

```sh
source /root/.bashrc
```

---

## 3. Download a Model

You can download any model of your choice. To proceed with the recommended model, simply run:

```sh
gaianet init
```

---

## 4. Start Your Node

Once setup is complete, start your node with:

```sh
gaianet start
```

To stop your node at any time, use:

```sh
gaianet stop
```

---

## 5. Register Your Node

Retrieve your **Node ID** and **Device ID** by running:

```sh
gaianet info
```

Now, go to your dashboard on the GaiaNet website:
- Navigate to **Settings > Nodes > Connect New Node**
- Enter your **Node ID** and **Device ID**

---

## 6. Join a Domain

On the Gaianet website, navigate to the **Nodes** section:
- Click on the three dots at the end of your Node ID
- Select **Join a Domain**
- Copy the provided command and run it on your server:

```sh
gaianet stop
gaianet config --domain gaia.domains
gaianet init
gaianet start
```

Go back to the dashboard and click **Next**. Search for any running model and select the one you've started, such as **Ollama 3.2:3B Instruct 5Q**.

---

## 7. Final Steps

Congratulations! Your node is now up and running.

**Note:** Remember to convert your daily points into credits. This allows you to chat and earn more rewards.

---

### Need Help?
If you encounter any issues, refer to the official GaiaNet documentation or reach out to the community for support!

