## Usage

```
echo deb https://radxa-repo.github.io/apt/ stable main | sudo tee /etc/apt/sources.list.d/radxa.list
curl https://radxa-repo.github.io/apt/pubkey.gpg | sudo apt-key add -
sudo apt update
```