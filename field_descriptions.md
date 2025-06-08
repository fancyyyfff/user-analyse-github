| 字段名        | 数据类型   | 说明                                              | 示例值                 |
|---------------|------------|---------------------------------------------------|------------------------|
| user_id       | 字符串     | 用户唯一标识符                                    | 123456                 |
| event_time    | 时间戳     | 事件发生的精确时间                                | 2023-01-15 08:30:45    |
| event_type    | 字符串     | 用户行为类型(view/cart/purchase/remove_from_cart) | view                   |
| product_id    | 字符串     | 商品唯一标识符                                    | P1001                  |
| category_id   | 整数       | 商品分类ID                                        | 15                     |
| category_code | 字符串     | 商品类目层级编码                                  | electronics.smartphone |
| brand         | 字符串     | 商品品牌                                          | Apple                  |
| price         | 浮点数     | 商品价格(单位：人民币)                            | 6999.99                |