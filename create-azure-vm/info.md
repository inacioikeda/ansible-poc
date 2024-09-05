pip install azure-mgmt-compute azure-mgmt-network azure-mgmt-resource azure-identity msrestazure azure.cli azure.storage.blob azure.mgmt.automation

ansible-galaxy collection install azure.azcollection

pip3 install -r ~/.ansible/collections/ansible_collections/azure/azcollection/requirements.txt

pip3 install --upgrade requests

az provider register --namespace Microsoft.Storage

az login
