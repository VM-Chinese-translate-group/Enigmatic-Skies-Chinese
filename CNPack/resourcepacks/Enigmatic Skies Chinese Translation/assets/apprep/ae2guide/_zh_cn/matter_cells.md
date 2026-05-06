---
navigation:
    title: ME物质存储元件
    icon: matter_cell_256k
    parent: index.md
item_ids:
    - matter_cell_housing
    - matter_cell_1k
    - matter_cell_4k
    - matter_cell_16k
    - matter_cell_64k
    - matter_cell_256k
    - mega_matter_cell_housing
    - matter_cell_1m
    - matter_cell_4m
    - matter_cell_16m
    - matter_cell_64m
    - matter_cell_256m
---

# 应用复制：ME物质存储元件

<Row>
  <ItemImage id="matter_cell_housing" scale="4"/>
  <ItemImage id="matter_cell_1k" scale="4"/>
  <ItemImage id="matter_cell_4k" scale="4"/>
  <ItemImage id="matter_cell_16k" scale="4"/>
  <ItemImage id="matter_cell_64k" scale="4"/>
  <ItemImage id="matter_cell_256k" scale="4"/>
</Row>

可用于存储复制物质的[存储元件](ae2:items-blocks-machines/storage_cells.md)。

<GameScene zoom="6" interactive={true}>
  <ImportStructure src="structures/matter_cells.snbt" />
  <IsometricCamera yaw="195" pitch="30" />

  <BoxAnnotation color="#dddddd" min="0 0 0" max="1 1 0.3">
    连续使用两次填满的物质储罐以使其显现。
  </BoxAnnotation>
</GameScene>


基本规格与常规[存储元件](ae2:items-blocks-machines/storage_cells.md)相同，但每256点物质将占用1字节空间。

作为MEGA Cells模组的联动内容，本模组同样提供了MEGA规格的物质存储元件。

---

## 注意事项

必须使用<ItemLink id="replication_connector" />才能与复制网络进行物质交换。
注意：本设备与其他模组中具有类似功能的方块互不兼容。
