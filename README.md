# Ready Layer One Welcome NFT
Just a clone of the NEAR NFT tutorial

### Minting Token

```bash=
near call nft.readylayerone.testnet nft_mint '{"token_id": "token-1", "metadata": {"title": "Ready Layer One Podcast Cover", "description": "Check out the Ready Layer One Podcast at https://anchor.fm/readylayerone A crypto and NEAR focused podcast.", "media": "http://readylayerone.s3.amazonaws.com/1.png"}, "receiver_id": "'$MAIN_ACCOUNT'"}' --accountId $MAIN_ACCOUNT --amount 0.1
```