Provision Azure VM

1. Create requirements.txt with libraries
2. Run `pip install -r requirements.txt` to install libraries
3. Fill in and export environment variables
```
export AZURE_TENANT_ID={your tenant id}
export AZURE_CLIENT_ID={your client id}
export AZURE_CLIENT_SECRET={your client secret}
export AZURE_SUBSCRIPTION_ID={your subscription id}
```
4. Then run `python provision_vm.py`