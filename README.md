wbchen99 and hnote0 Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/bitcoin/bitcoin.svg?branch=master)](https://travis-ci.org/bitcoin/bitcoin)

https://hnote.org

What is hnote?
----------------

Hnote is an experimental new digital currency or note that enables instant payments to
anyone, anywhere in the world. Hnote uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Hnote Core is the name of open source
software which enables the use of this currency.
歡迎進入「區塊鏈金融」共享共治美好社會

人類文明歷史的演進，社會機制與人類行為創造的價值，一直以不同的形式進行交換，從貝殼到銀子，從銀票到黃金，從紙鈔到虛擬貨幣，貨幣創新（如比特幣）是科技進化社會體驗的成果，傳遞價值來自於交換過程的信用與風險溢價，金融科技的創新，將帶領我們進入區塊鏈的世界，「去中心化」的共享共治，在對等關係的信任機制下發展美好和諧社會。

在區塊鏈金融的美麗新世界裡，通過點對點技術實現了「虛擬通貨」的區塊鏈系統，分散式網路將所有交易傳送到每一個人手上安全保存，您可以在線完成你可能需要的所有交易，同時完成記帳安全傳送，直接由您發起與另外一方進行交易溝通，中間不需要通過任何仲介機構，交易成本大大降低，安全大大的提高，不會依賴「中心化」節點讓您無法完成交易需求，直接溝通，共同管理共同知識，直接交易，共同開發共享智慧，直接清算支付。

想像一下，當一個一個區塊串鏈起來，區塊鏈的世界通過去中心化的分散式節點，去信任方式集體維護數據庫的技術方案，區塊鏈方案讓參與系統中的任意多個節點，一段時間系統內全部信息交流數據，通過密碼學算法計算，記錄到一個數據塊，數據指紋鏈接一個一個數據塊和確認，由系統所有參與節點來同確認記錄，所有的節節點都是平等，您自己就是銀行，銀行就是您自己。

區塊鏈的金融創新，我們引領了虛擬通貨的科技，開發了虛擬通貨憑證（或票券 或代幣 或虛擬信用)，h*Note 提供了交易憑證，讓您的交易在區塊鏈的虛擬網路中，得到如同真實世界銀行一樣所提供的交易安全，同時得到超過千萬節點的共同技術支持與交易確認。 

For more information, as well as an immediately useable, binary version of
the Hnote Core software, see https://Hnote.org/en/download, or read the
[original whitepaper](https://bitcoincore.org/bitcoin.pdf).

License
-------

Hnote Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly to indicate new official, stable release versions of Bitcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The developer [mailing list](https://lists.linuxfoundation.org/mailman/listinfo/bitcoin-dev)
should be used to discuss complicated or controversial changes before working
on a patch set.

Developer IRC can be found on Freenode at #bitcoin-core-dev.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations can be submitted to
[Bitcoin Core's Transifex page](https://www.transifex.com/projects/p/bitcoin/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.

Translators should also subscribe to the [mailing list](https://groups.google.com/forum/#!forum/bitcoin-translators).
