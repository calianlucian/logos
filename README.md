# SushiSwap Logo

# Requirements

- Logo extension should be jpg
- It should be 128x128 exactly, no larger, no smaller
- It should be named by the checksummed address of the token

# Checksummed address

Using weth as an example, the checksummed token address is 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2, often when looking these address up they may or may not already be checksummed. It's important that they're verified. You can do this with a tool like https://ethsum.netlify.app/

If you were to put a non-checksummed for wrapped ether 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 into the checksum tool it will turn into the checksummed 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2.

# Adding a token logo

1. If adding a token logo for a network which does not yet exist, add a new folder named afer the network in the network folder of this repository. e.g. ethereum

2. Using wrapped ether as an example, you would add this to the etheruem folder, and it should be named by the token address, and extension should be jpg. e.g. 0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2.jpg

# Invalidating cache

cld uploader explicit "https://raw.githubusercontent.com/sushiswap/logos/main/network/moonriver/0x4a436073552044D5f2f49B176853ad3Ad473d9d6.jpg" type="fetch" invalidate="true" eager='[{ "width": 24 }, { "width": 32 }, { "width": 48 }, { "width": 64 }, { "width": 96 }, { "width": 128 }]'


