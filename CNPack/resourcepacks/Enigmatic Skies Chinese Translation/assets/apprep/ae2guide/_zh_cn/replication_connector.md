---
navigation:
    title: ME复制连接器
    icon: replication_connector
    parent: index.md
item_ids:
    - replication_connector
---

# 应用复制：ME复制连接器

<BlockImage id="replication_connector" scale="4" />

此方块用于连接复制网络与ME网络。

可将复制网络中的物质存入ME网络，亦可将物质从ME网络提取回复制网络中。

<GameScene zoom="6" interactive={true}>
  <ImportStructure src="structures/replication_connector_basic.snbt" />
  <IsometricCamera yaw="195" pitch="30" />
</GameScene>

## 自动合成

存储在芯片存储器中的样板会自动在ME网络中注册为可合成项。
复制器的产物将通过ME复制连接器输入至ME网络。

<GameScene zoom="6" interactive={true}>
  <ImportStructure src="structures/auto_craft.snbt" />
  <IsometricCamera yaw="195" pitch="30" />

  <BlockAnnotation color="#dddddd" x="0" y="0" z="1">
    自动合成会消耗ME物质存储元件内存储的物质。
  </BlockAnnotation>
</GameScene>
