## Lanacoin is a Pow/PoS personalized cryptocurrency
- Ticker: LANA

- Type: PoW/PoS hybrid

- PoW algorithm: sha256d

- PoS block hashing: sha256d

- Max Coins: 7.506.000.000 (7.5+ bilion)

- PoW reward: 10000 LANA (no halving)

- Last PoW block: 750000 (approx 7 years)

- PoS reward: fixed 1000 LANA + 7% (yearly)

- PoS reward halving: 525600 (approx 5 years, halving only for fixed reward, 7% stays the same)

- Minimum PoS age: 7 hours

- Maximum PoS age: unlimited

- Block time target: 5 minutes

- Difficulty retarget: every block

- Coinbase maturity: 100 blocks

- Transaction recommended minimum confirmations: 5

- Minimal TX fee: 100 Lanoshis (0.00000100 LANA)


P2P port: 7506

RPC port: 5706


Testnet P2P port: 17506

Testnet RPC port: 15706

Estimated coins in existence after end of pow 4.068.900.000 (very very rough estimate, depends on how many people will be staking...etc)

LanaCoin blockchain snapshots/chain states/bootstrap.dat (pCloud: http://pc.cd/8p8otalK )

Responsible disclosure and security contact: security@lanacoin.com

Exchanges and listing contact (digital currency exchange representatives should take note Lana is an open source network with no premine/instamine or any type of crowdfunding and no listing fee budget is awailable): listings@lanacoin.com

Developers contact: dev@lanacoin.com

Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of Lanacoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be
labeled 'stale'.

## Get in touch or stay updated:

- Forum: https://bitcointalk.org/index.php?topic=1448065

- Twitter: https://twitter.com/LanaCoin

- Web: https://lanacoin.com/

- Community web: https://lanacoin.org

- Facebook: https://www.facebook.com/LanaCoins/

- Telegram: https://t.me/LanaCoin

- Discord: https://discord.gg/Gf25qN2

- Unified telegram: https://t.me/BlockmasterSi

- Medium: https://medium.com/@LanaCoin/

- CoinmarketCap: https://coinmarketcap.com/currencies/lanacoin/

- Coinpaprika: https://coinpaprika.com/coin/lana-lanacoin/

- CoinGecko: https://www.coingecko.com/en/coins/lanacoin

- Blockexplorer: https://chainz.cryptoid.info/lana/

- Instagram: https://www.instagram.com/lanacoin.cryptocurrency/

- Youtube: https://www.youtube.com/channel/UC23mCMIR7ecKm3cnbOl1laA

- Lbry.tv: https://lbry.tv/$/invite/@LanaCoin:2

- Reddit: https://www.reddit.com/r/BlockmasterSi

- Mobile wallet for android: https://play.google.com/store/apps/details?id=com.cryptowallet.si

## List of wallet commands

￼
* addmultisigaddress <nrequired> <'["key","key"]'> [account]
* addnode <node> <add|remove|onetry>
* addredeemscript <redeemScript> [account]
* backupwallet <destination>
* checkkernel [{"txid":txid,"vout":n},...] [createblocktemplate=false]
* checkwallet
* createrawtransaction [{"txid":txid,"vout":n},...] {address:amount,...}
* decoderawtransaction <hex string>
* decodescript <hex string>
* dumpprivkey <lanacoinaddress>
* dumpwallet <filename>
* getaccount <lanacoinaddress>
* getaccountaddress <account>
* getaddednodeinfo <dns> [node]
* getaddressesbyaccount <account>
* getbalance [account] [minconf=1]
* getbestblockhash
* getblock <hash> [txinfo]
* getblockbynumber <number> [txinfo]
* getblockcount
* getblockhash <index>
* getblocktemplate [params]
* getcheckpoint
* getconnectioncount
* getdifficulty
* getinfo
* getmininginfo
* getnettotals
* getnewaddress [account]
* getnewpubkey [account]
* getpeerinfo
* getrawmempool
* getrawtransaction <txid> [verbose=0]
* getreceivedbyaccount <account> [minconf=1]
* getreceivedbyaddress <lanacoinaddress> [minconf=1]
* getstakesubsidy <hex string>
* getstakinginfo
* getsubsidy [nTarget]
* gettransaction <txid>
* getwork [data]
* getworkex [data, coinbase]
* help [command]
* importprivkey <lanacoinprivkey> [label] [rescan=true]
* importwallet <filename>
* keypoolrefill [new-size]
* listaccounts [minconf=1]
* listaddressgroupings
* listreceivedbyaccount [minconf=1] [includeempty=false]
* listreceivedbyaddress [minconf=1] [includeempty=false]
* listsinceblock [blockhash] [target-confirmations]
* listtransactions [account] [count=10] [from=0]
* listunspent [minconf=1] [maxconf=9999999] ["address",...]
* makekeypair [prefix]
* move <fromaccount> <toaccount> <amount> [minconf=1] [comment]
* ping
* repairwallet
* resendtx
* reservebalance [<reserve> [amount]]
* sendalert <message> <privatekey> <minver> <maxver> <priority> <id> [cancelupto]
* sendfrom <fromaccount> <tolanacoinaddress> <amount> [minconf=1] [comment] [comment-to]
* sendmany <fromaccount> {address:amount,...} [minconf=1] [comment]
* sendrawtransaction <hex string>
* sendtoaddress <lanacoinaddress> <amount> [comment] [comment-to]
* setaccount <lanacoinaddress> <account>
* settxfee <amount>
* signmessage <lanacoinaddress> <message>
* signrawtransaction <hex string> [{"txid":txid,"vout":n,"scriptPubKey":hex,"redeemScript":hex},...] [<privatekey1>,...] [sighashtype="ALL"]
* stop
* submitblock <hex data> [optional-params-obj]
* validateaddress <lanacoinaddress>
* validatepubkey <lanacoinpubkey>
* verifymessage <lanacoinaddress> <signature> <message>
* walletlock
* walletpassphrase <passphrase> <timeout> [stakingonly]
* walletpassphrasechange <oldpassphrase> <newpassphrase>

## Support development 


- Bitcoin (BTC): 3Dho3s7SchiGuq27r37ZLodf8CSba7tX1d
- Dynamic Trading Rights (DTR) : 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Ethereum (ETH): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Litecoin (LTC): MRWtV5V9jtNBWHvnibJ8pHtgyLdFdEv9Ez
- Bitcoin Cash (BCH): bitcoincash:qq6d23evqsgzlqarmnurugvgm4z7u5f5ggdwez6ml2
- GoCrypto (GOC): simpleledger:qr6j9rtq2fpm2q4lp3jr2dnykd6vas8sscjdgq8zez
- Monero (XMR): 4GTDkmbNL8mHBYGV4WHqa9Df63PM6PGWWbrdz6bKB5CjMbgcCRitGFK7fy9zZi6dgfgofHqeRoJGjcJ2LMwST4JH55kk42PwWELGbcXXYV
- Ripple (XRP): rPkitTzAi3KahtGAbdCuq3XxZtDjRCG3U8 tag: 3910586522
- DigiByte (DGB): D7hdrJ25ut3ew2DS1TWMX2WW4TGrvwfJXL
- Dogecoin (DOGE): DS8a89ocpTRKZAvaZZMdz7CWw9rK5moqvy
- Stellar Lumens (XLM): GC62AZDYMGBGPS3MQ5QPTNRNPDRK6F32JAFHTJUBZ4GOSFXASULPKYHG memo:64c40ee2aac9d51b
- Cardano ADA (ADA): DdzFFzCqrht8tWQz2EPwobGccCE3r99kjEzdRhd89oCcP4wTuBLc94sFXuN1zUP8xdag9nkK3uxK8kpKY8sTGXsNh7qMSewB5aPVFRRQ
- Tron (TRX): TUaMUjHDWWY5YyptBgG56ZMXcPwi7u357o
- Tezos (XTZ): tz1NugV7B6eJAVnH6TZseuzB14gmL4PULGzx
- Tether USD (USDT): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Stasis EUR (EURS): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- USD Coin (USDC): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- TrueUSD (TUSD): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Paxos Standard Token (PAX): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Dai (DAI): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Gemini Dollar (GUSD): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Binance Coin (BNB): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- SunContract (SNC): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- 0xcert (ZXC): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Blockestate (BIT): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Digital Assets Power Play (DPP): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Viberate (VIB): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- CargoX (CXO): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Xaurum (XAUR): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- Basic Attention Token (BAT): 0x1823FfcE4C3B78F9641202cC3996bF717B483F1d
- WalaHalaCoin (WHC): WPaWdaSRzXuQx5mW4Z13T5YMU8g1MV6DdZ





