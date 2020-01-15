## 治理

### 治理周期



### Token锁定

参与投票需要锁定 NEO,在本轮治理周期结束之后，NEO 解锁，也可以选择连续投票。

另外，当选的共识节点也需要锁定一部分 NEO。

### 投票

对于标量和枚举量的决策分别有不同的投票以及计票方式。

#### 标量（共识节点数量）

1 NEO 1 票，取中位数

#### 枚举量（共识节点）

采用 CAV 投票方式，具体为，1 NEO 1 个选择列表，分别选出认可的节点列表和不认可的节点列表，不限定列表内节点数目。计票时，认可列表中的节点票数+1，不认可列表中的节点票数-1，其余的参选节点票数不变，统计所有的投票之后，取前 N 位票数最多的节点。

## 激励

### 经济模型

NEO和Gas总量均为1亿，Gas分22年逐步解锁。（同 Neo2）

### Gas分配

其中ρ为投票率。r为0到1之间的一个值，r = 0表示NEO持有者永远不会获得GAS，除非他们参与治理过程；而r = 1表示NEO持有者不能因为参与治理而获得更多的GAS。我们建议选择尽可能低的 r 来激励选民，最好让所有NEO持有人都能在持有NEO 一个治理周期后投票或转让其NEO。那么NEO持有者就不需要从其他地方购买额外的GAS来参与治理过程。
