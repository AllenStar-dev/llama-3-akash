# llama-3 On Akash Network

- Deploy Llama 3 70B with 16-bit quantization on Akash Network.
- It's a zealy task and was developed for [zealy](https://zealy.io/cw/akashnetwork/questboard/902cfb01-2158-4f0a-9af5-5ea1a97abc8c/1c804b53-c970-4200-b1ee-cd3495255f96) and Hosted on [Akash Network](https://akash.network/).


## Akash Guide For Creating and Deploying Applications.

* Install and fund the Wallet.

     - [Kepler](https://chromewebstore.google.com/detail/keplr/dmkamcknogkgcdfhhbddcghachkejeap?hl=en)
    -  [Leap](https://www.leapwallet.io/#inpage-download) 

* Fund the wallet
  - You can Swap Atom to AKT on [Osomis](https://app.osmosis.zone/?from=OSMO&to=AKT)
  - Buy Atom from Centralised Exchanges.
  - Connect your Wallet to Swap.
    
* Go to [Cloudmos](https://deploy.cloudmos.io/)
* Connect your wallet again.
  - You Need to have minimum 0.5 AKT in the wallet.
- You Need to create Huggingface account and get access to the llama models.
  - Here is the link [llama](https://huggingface.co/meta-llama/Meta-Llama-3-70B-Instruct) for the huggingface model hub.
  - You then need to request for access to the models from the authors by sharing your required information.
  - Then create an [acces token](https://huggingface.co/settings/tokens) after getting access to the models
  - Use the access token and replace it with hf_yourtoken in [deploy.yaml](https://github.com/AllenStar-dev/llama-3-akash/blob/main/deploy.yaml) 
  -   

* Go to Deployments.
* There you can build your own template or run pre built SDL from Akash Marketplace.
* For this build  Select Build Your Template.
* You can name the deployment.
* Click YAML and Paste the SDL (Your own or pre-built).
* Check this [Readmefile](https://github.com/AllenStar-dev/story_maker/blob/main/README.md?plain=1) on how to run docker.
* My SDL [deploy.yaml](https://github.com/AllenStar-dev/llama-3-akash/blob/main/deploy.yaml).
* Click Create Deployment.
* You'll receive a transaction request in the wallet.
* Approve the transaction request.
* After Approval you'll receive bids.
* Review the bids and select the provider.
* Accept the transaction for the provider.
* Wait a few minutes.
* Then go to the Leases and Click the link of url.
* The Url redirects to your Application.
* If Everything is successful then the link works if not re-check and redeploy.
* For More help reach out to [Akash Discord](https://discord.com/channels/747885925232672829/1111762591937732648).
* Also Check [Akash Docs](https://akash.network/docs/deployments/cloudmos-deploy/). for any further queries.
* Happy Deploying on Akash.
