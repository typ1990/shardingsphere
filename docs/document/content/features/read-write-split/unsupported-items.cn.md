+++
pre = "<b>3.2.3. </b>"
toc = true
title = "不支持项"
weight = 3
+++

1. 主库和从库的数据同步。
1. 主库和从库的数据同步延迟导致的数据不一致。
1. 主库双写或多写。
1. 跨主库和从库之间的事务的数据不一致。主从模型中，事务中读写均用主库。