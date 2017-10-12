# Hackerspace Status Bot

Status Bot for Twitter

## Getting Started

Before you start, make sure you have Python and virtualenv installed and in your PATH.

### Prerequisites

Execute the following commands on the command line:

```
ENV_NAME=twitterstatus
virtualenv $ENV_NAME
cd $ENV_NAME
source ./bin/activate
pip install twitter
git clone https://github.com/bytespeicher/twitterstatus.git .
cp config.py.example config.py
```

After the virtual environment is set up, the Twitter library is installed and twitterstatus is cloned you will need to generate Twitter OAuth keys and put them into *config.py*. Also you might want to check if *CURRENT_STATUS* is set  to the path where your spaceapi status.json resides. When everything is set up just run twitterstatus.py.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/Bytespeicher/Bytebot/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Contributors

[Bytespeicher](https://github.com/Bytespeicher)
