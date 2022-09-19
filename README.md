
# PlayStation Network API Wrapper Python (PSNAWP)

Retrieve User Information, Trophies, Game and Store data from the PlayStation Network

[![PyPI version](https://badge.fury.io/py/PSNAWP.svg)](https://badge.fury.io/py/PSNAWP)
[![Downloads](https://pepy.tech/badge/psnawp)](https://pepy.tech/project/psnawp)
[![python-logo](https://img.shields.io/badge/python-3.9_|_3.10-blue.svg)](https://www.python.org/)
[![pytest](https://github.com/isFakeAccount/psnawp/actions/workflows/pytest.yaml/badge.svg)](https://github.com/isFakeAccount/psnawp/actions/workflows/pytest.yaml)
[![pre-commit](https://github.com/isFakeAccount/psnawp/actions/workflows/pre-commit.yaml/badge.svg)](https://github.com/isFakeAccount/psnawp/actions/workflows/pre-commit.yaml)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Documentation Status](https://readthedocs.org/projects/psnawp/badge/?version=latest)](https://psnawp.readthedocs.io/en/latest/?badge=latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<!-- Pytest Coverage Comment:Begin -->
<a href="https://github.com/isFakeAccount/psnawp/blob/main/README.md"><img alt="Coverage" src="https://img.shields.io/badge/Coverage-42%25-orange.svg" /></a><br/><details><summary>Coverage Report </summary><table><tr><th>File</th><th>Stmts</th><th>Miss</th><th>Cover</th><th>Missing</th></tr><tbody><tr><td colspan="5"><b>/opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api</b></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/__init__.py">__init__.py</a></td><td>1</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/psnawp.py">psnawp.py</a></td><td>20</td><td>7</td><td>7</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/psnawp.py#L 65%"> 65%</a></td></tr><tr><td colspan="5"><b>/opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/core</b></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/core/__init__.py">__init__.py</a></td><td>0</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/core/authenticator.py">authenticator.py</a></td><td>46</td><td>11</td><td>11</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/core/authenticator.py#L 76%"> 76%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/core/psnawp_exceptions.py">psnawp_exceptions.py</a></td><td>15</td><td>3</td><td>3</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/core/psnawp_exceptions.py#L 80%"> 80%</a></td></tr><tr><td colspan="5"><b>/opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models</b></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/__init__.py">__init__.py</a></td><td>0</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/client.py">client.py</a></td><td>42</td><td>24</td><td>24</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/client.py#L 43%"> 43%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/message_thread.py">message_thread.py</a></td><td>37</td><td>37</td><td>37</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/message_thread.py#L  0%">  0%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/search.py">search.py</a></td><td>11</td><td>6</td><td>6</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/search.py#L 45%"> 45%</a></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/user.py">user.py</a></td><td>69</td><td>53</td><td>53</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/models/user.py#L 23%"> 23%</a></td></tr><tr><td colspan="5"><b>/opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/utils</b></td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/utils/__init__.py">__init__.py</a></td><td>0</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/utils/endpoints.py">endpoints.py</a></td><td>2</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/utils/misc.py">misc.py</a></td><td>13</td><td>0</td><td>100%</td><td>&nbsp;</td></tr><tr><td>&nbsp; &nbsp;<a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/utils/request_builder.py">request_builder.py</a></td><td>48</td><td>36</td><td>36</td><td><a href="https://github.com/isFakeAccount/psnawp/blob/main//opt/hostedtoolcache/Python/3.10.6/x64/lib/python3.10/site-packages/psnawp_api/utils/request_builder.py#L 25%"> 25%</a></td></tr><tr><td><b>TOTAL</b></td><td><b>304</b></td><td><b>177</b></td><td><b>42%</b></td><td>&nbsp;</td></tr></tbody></table></details>
| Tests | Skipped | Failures | Errors | Time |
| ----- | ------- | -------- | -------- | ------------------ |
| 8 | 0 :zzz: | 0 :x: | 7 :fire: | 0.479s :stopwatch: |

<!-- Pytest Coverage Comment:End -->

## How to install

### From PyPI

```
pip install PSNAWP
```
### Using `setup.py`
To install the library into python. First you need to clone the repo at your local machine and run the following command from the root directory of the repo

```
python setup.py install
```

## Important Links
> PyPI: https://pypi.org/project/PSNAWP/
>
> Read the Docs: https://psnawp.readthedocs.io/en/latest/

## Getting Started

To get started you need to obtain npsso <64 character code>. You need to follow the following steps

1. Login into your [My PlayStation](https://my.playstation.com/) account.
2. In another tab, go to https://ca.account.sony.com/api/v1/ssocookie
3. If you are logged in you should see a text similar to this

```json
{"npsso":"<64 character npsso code>"}
```
This npsso code will be used in the api for authentication purposes. The refresh token that is generated from npsso lasts about 2 months. After that you have to get a new npsso token. The bot will print a warning if there are less than 3 days left in refresh token expiration.

Following is the quick example on how to use this library

```py
from psnawp_api import PSNAWP

psnawp = PSNAWP('<64 character npsso code>')

# Client that is you
client = psnawp.me()
print(client.online_id)
print(client.account_id)
print(client.get_account_devices())
print(client.friends_list())
print(client.blocked_list())

# Getting user from online
user_online_id = psnawp.user(online_id="VaultTec_Trading")
print(user_online_id.online_id)
print(user_online_id.account_id)
print(user_online_id.profile())
print(user_online_id.get_presence())
print(user_online_id.friendship())
print(user_online_id.is_blocked())

# Getting user from Account ID
user_account_id = psnawp.user(account_id='1802043923080044300')
# Same functions as shown above
 ```
Sending private message only works if the message group between you and user already exists otherwise it will throw HTTP Status Code 429. Basically you would have to create the group yourself through the APP or ask the user to send you message first.

**Note: If you want to create multiple instances of psnawp you need to get npsso code from separate PSN accounts. If you generate a new npsso with same account your previous npsso will expire immediately.**

## Contribution

All bug reposts and features requests are welcomed, although I am new at making python libraries, so it may take me a while to implement some features. Suggestions are welcomes if I am doing something that is an unconventional way of doing it.

## Disclaimer

This project was not intended to be used for spam, abuse, or anything of the sort. Any use of this project for those purposes is not endorsed. Please keep this in mind when creating applications using this API wrapper.

## Credit

This project contains code from PlayStationNetwork::API and PSN-PHP Wrapper that was translated to Python. See more in [LICENSE](LICENSE.md)
