# Action - `{{ regproducer }}`

## Description
 
### 1. The intent of regproducer
The intent of the `{{ regproducer }}` action is to register a block producer candidacy. This contract is considered a governing document as defined by the EOS User Agreement (EUA).

regproducer의 목적

`{{ regproducer }}` 작업의 목적은 블록생산자 입후보 등록을 하는 것입니다. 이 계약은 EOS 사용자 계약서 (EUA)에 정의된 바와 같이 관리 문서로 간주됩니다.

regproducer 的目的

`{{ regproducer }}`操作的目的是注册成为出块节点候选者。根据 EOS 用户协议(EUA)的定义，本合约属于治理文本(governing document )

### 2. Nomination
I, {{producer}}, hereby nominate myself for consideration as a block producer candidate. This nomination includes agreement to the terms of this contract by my block producer candidate entity, including all of its shareholders, owners, employees, staff, members, and any individual working in official, direct, or affiliated capacity for my Block Producer entity.

지명

나, {{producer}}는 블록프로듀서 후보로 고려되도록 자신을 지명합니다. 이 지명에는 블록프로듀서회사의 모든 주주, 소유자, 직원, 멤버, 회원 및 공식인원, 직접 또는 계열사에서 일하는 모든 개인을 포함한 블록프로듀서 회사가 계약 조건에 대해 동의함을 인정합니다.

提名

本人，{{producer}}，特此提名本人为出块节点候选人。本提名包括了本出块节点候选人实体对本合约中所有条款的明确同意，包含其所有者、雇员、员工、成员，以及任何以正式方式、直接或附属方式为本出块节点实体工作的个人。

### 3. Resignation and Removal for Inability to Perform Obligations.

If I, {{producer}}, am unable to perform any of the obligations stipulated in this contract, I will resign my position by calling this contract with a null producer key.

If I, {{producer}}, fail to resign when unable to perform said obligations, I understand that procedures enumerated in this contract shall be enacted.

의무의 불이행에 대한 사임 및 철회
{{producer}}가 본 계약서에 명시된 의무를 수행 할 수 없는 경우, 생산자 키를 null 로 함으로써 본인의 지위를 사임합니다.

만약 내가 {{producer}}의 의무를 이행 할 수 없을 때 사임하지 않는다면, 나는 본 계약에 열거된 절차가 집행됨을 동의합니다.

因不能履行义务而退出或被取消出块资格
 
如果我，{{producer}}，不能履行本合约中所规定的任何义务，我将使用无效的出块节点公钥调用本合约，从而使我的出块节点退出。

如果我 {{producer}}, 在无法履行上述义务时未能退出(resign)，我知晓将会根据本合约所列举的程序对我实行制裁或处罚程序。

### 4. EOS Accounts

Block Producers may never affect an account on the EOS blockchain, except for the reasons specifically cited in this contract that pertain to Block Producer accounts. User accounts can only be affected on the basis of Article VIII in the EOS User Agreement.
 
EOS 계정
블록프로듀서는 본 계약에서 해당하는 블록프로듀서의 계정 차단에 관련하여 특별히 언급한 이유를 제외하고는 EOS 블록체인의 계정에 결코 영향을 미치지 않습니다. 사용자 계정은 EOS 사용자 계약서의 8조에 근거할 때만 영향을 받을 수 있습니다.

EOS 账号

出块节点永远不会对 EOS 区块链上的帐户造成影响，除非是本合约中特别提到与出块节点帐户有关的原因。只有基于 EOS用户协议中的第八条的情形下，用户的账号才会受到影响. 

### 5. Producer Key

I, {{producer}}, will sign blocks with {{producer_key}}

If I, {{producer}} suspect my key has been compromised I will alert the other Block Producers immediately.

I, {{producer}}, acknowledge that any and all actions executed with my {{producer_key}} is my responsibility, regardless of the account being compromised.

프로듀서 키

나, {{producer}}는 {{producer _ key}} 로 블록에 서명 할 것입니다. 
만약 내, {{producer}} 가 본인의 키가 손상되었다고 의심되면 즉시 다른 블록프로듀서에게 알려줄 것입니다.
나, {{producer}}는 EOS 블록체인에서 본인의 블록프로듀서 계정이 실행하는 모든 작업에 대해, 계정 이상 유무와 관련 없이, 책임이 있음을 인정합니다.

出块节点公钥

 我, {{producer}}, 将使用 {{producer_key}} 对区块签名。
如果我, {{producer}}, 怀疑我的密钥已被泄露，我将立即通知其他节点。
我，{{producer}}，承认我的出块节点帐户在EOS区块链上所执行的任何操作都是我的责任，无论该帐户是否被盗。

### 6. API Endpoints
 
If I, {{producer}}, qualify for, and choose to claim rewards due to votes received, and/or blocks produced, I, {{producer}}, will provide functioning and queryable public P2P and API endpoints to maintain synchronization with the blockchain and submit transactions to be included. API endpoints must be updated to a recent functional version that does not have known security vulnerabilities.
 
I, {{producer}}, hereby acknowledge that if I am unable to do so within 30 minutes of being alerted by another {{producer}}, I can be removed by use of the rmvproducer action.

API 엔드포인트
만약 내, {{producer}} 가 투표를 받아 블록 보상을 청구할 수 있는 자격을 얻으면, 나 {{producer}}는 작동 및 쿼리 가능한 공개 P2P 및 API 엔드포인트를 블록체인과의 동기화 및 트랜잭션을 제출할 수 있게 유지관리합니다. API 엔드포인트는 알려진 보안 취약성이 없는 최신버전으로 업데이트해야 합니다.
 
나, {{producer}} 는 다른 {{producer}}가 경고 ​​한 후, 30분 이내에 바로잡을 수 없다면 rmvproducer 조치를 통해 자격이 제거 될 수 있음을 인정합니다.

API 端点
 
如果我，{{producer}} 由于得到投票和/或出块的原因，符合领取奖励的条件并选择接受奖励，那么我， {{producer}}，将提供功能正常的公共 P2P 和 API 端点来维护与区块链的同步，并提交要打包入块的事务。API 端点必须更新到最新的可用版本，并且该版本没有已知的安全漏洞

我，{{producer}}，在此确认，如果我在收到另一个 {{producer}} 的警告后30分钟内仍不能符合上述要求，可以使用“rmvproducer”操作移除我的账户。
 
### 7. Execution time
 
I, {{producer}}, will deploy and run network infrastructure capable of maintaining 2ms or less CPU execution times.
 
I, {{producer}}, hereby acknowledge that if I am unable to do so within 30 minutes of being alerted by another {{producer}}, I can be removed by use of the rmvproducer action.

실행 시간
 
나, {{producer}}는 2ms 또는 그 이하의 CPU 실행 시간을 유지할 수 있는 네트워크 인프라를 배포하고 실행합니다.

 나, {{producer}} 는 다른 {{producer}}가 경고 ​​한 후, 30분 이내에 바로잡을 수 없다면 rmvproducer 조치를 통해 자격이 제거 될 수 있음을 인정합니다.

执行时间

我， {{producer}}，将部署和运行网络基础设施，能够将 CPU 执行时间维持在 2ms 或更少的水平。

我，{{producer}}，在此确认，如果我在收到另一个{{producer}}的警告后30分钟内不能符合上述条件，可以使用 rmvproducer 操作将我移除。
 
### 8. Ordering
I {{producer}} agree to process transactions on a first-in-first-out (FIFO) basis, and not to manipulate the contents of blocks in order to derive profit from the order in which transactions are included: the hash of the block that is produced.

생산
나, {{producer}}는 선입 선출법 (FIFO) 방식으로 거래를 처리하고 거래가 블록의 해시에 포함되는 순서에서 이익을 얻으려는 목적으로 생산하는 블록의 내용을 조작하지 않기로 동의합니다.
 
顺序

我， {{producer}} ，同意根据先进先出(FIFO)的方式处理事务，并且绝不会为了牟利而利用区块内容、操纵区块中交易处理的顺序。
 
### 9. Random Rotation of Standbys
I, {{producer}}, agree that if I am in a paid standby position, I can be randomly called into a producing position. Upon failure to produce blocks, code may self-execute penalties regarding future vpay rewards.

유급 대기 블록프로듀서의 무작위 로테이션
나, {{producer}}는 본인이 유급 대기직에 있을 때, 무작위로 생산직으로 부름 받을 수 있다는 것에 동의합니다. 이때 블록을 생성하지 못하면 코드는 향후 vpay 보상에 대한 처벌을 집행할 수 있습니다.

备选节点随机轮换

我，{{producer}}，同意若本节点处于有偿备选状态，可被随机调入出块状态。如果我无法出块，合约代码可能会自动执行就未来的 vpay 报酬进行处罚。

### 10. Missing Two or More Rounds of Blocks
I, {{producer}}, acknowledge that if after missing 2 or more rounds of blocks in succession I am unable to be contacted within 20 minutes, I, {{producer}}, acknowledge that I may be removed from a producing position by use of the rmvproducer action.
 
I, {{producer}}, acknowledge that after missing two or more rounds of blocks in succession, standard practice stipulates removing my producer by using the rmvproducer action until the given issue is resolved. 
  
두 라운드 이상의 블록 누락

나, {{producer}}는 두 라운드 이상 연속하여 블록을 누락 한 후, 20분 이내에 연락 할 수 없다면 {{producer}} 가 rmvproducer 액션의 사용되어 생산 위치에서 제거 될 수 있음을 인정합니다.

{{producer}}는 두 라운드 이상으로 블록을 연속적으로 누락한다면, 주어진 문제가 해결 될 때까지 rmvproducer 작업을 사용하여 본인이 생산 위치에서 제거됨이 표준 관행으로 규정되어 있음을 인정합니다.

两轮或更多轮丢块的情形
 
我，{{producer}}, 如果连续两轮或更多轮丢块且无法在20分钟内联系到我，我，{{producer}}, 同意可能会用 rmvproducer 操作将我移除。
我，{{producer}}, 如果连续两轮或更多轮丢块，根据标准实践会发起 rmvproducer 操作将我移除出块资格，直到问题解决。
 
### 11. Urgent Security Patches
I, {{producer}}, acknowledge that if I am not able to be contacted in any form after an urgent security patch being is announced, I may be removed by use of the rmvproducer action.

긴급 보안 패치
긴급 보안 패치가 발표 된 후, 어떤 형태로든 연락 할 수 없는 경우 rmvproducer 작업을 사용하여 제거 될 수 있음을 나, {{producer}}는 인정합니다.

紧急安全补丁

我，{{producer}}，确认如果在紧急安全补丁发布后用任何方式都无法联系到我，可能会用 rmvproducer 指令将我移除。
 
### 12. Disclosure of Entity and Server Information
I, {{producer}}, attest that I have disclosed the approximate geolocation for my main production node.

법인 및 서버 정보의 공개

나, {{producer}} 는 주 생산 노드에 대한 위치 정보를 공개했음을 증명합니다.

实体和服务器的信息披露

我，{{producer}}，确认我已经披露了主出块节点服务器地理位置的准确信息。

### 13. Establishes the penalty and procedure for unwillingness to comply with penalties or procedures

I, {{producer}}, acknowledge that failing to comply with penalties or procedures enacted against me will result in Block Producers executing the rmvproducer contract to remove me. 

I, {{producer}}, will not execute the regproducer contract until serving or fulfilling the requirements from a penalty or procedure that results in having the rmvproducer contract executed to remove me.

I, {{producer}}, acknowledge that if I continue to call the regproducer action without serving or fulfilling the requirements from breach of regproducer, my account keys associated with the registered Block Producer in question may be nulled by Block Producers by using eosio.wrap.

페널티를 준수하지 않을 경우 벌칙

나, {{producer}} 는 나에게 제재된 처벌을 준수하지 않으면 블록프로듀서들이 rmvproducer 계약을 집행하게 될 것이라고 인정합니다. 나, {{producer}} 는 rmvproducer 계약이 집행된다면 요구 사항을 충족될 때까지 regproducer 계약을 이행하지 않을 것입니다.
regproducer 계약 위반으로 인한 요구 사항을 충족시키지 않고 regproducer 계약을 계속 호출하면 해당 블록프로듀서와 관련된 계정 키가 eosio.wrap 을 사용하여 블록프로듀서들에 의해 무효화 될 수 있음을 인정합니다. 

对不愿遵守处罚的行为予以处罚
 
我，{{producer}}，承认若不遵守对本人制裁的处罚，BP 可以实施 rmvproducer 合约，我接受投票的资格将被取消。若有针对我实施 rmvproducer 合约的情况发生，我, {{producer}} 在遵守/履行所收到的处罚之前，不会再次执行 regproducer 合约。

我，{{producer}}，在履行惩罚程序的要求之前，不会执行 regproducer 合同。如不履行此程序， rmvproducer 合同将会再次将我移除。

我,{{producer}}, 承认如果没有遵守或履行因违反 regproducer 而受到的惩罚要求却继续调用regproducer操作，BP 可以调用 eosio.wrap 合约将我用来注册出块节点的账号密钥设置为无效值。
 
