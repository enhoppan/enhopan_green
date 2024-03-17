# auto-green

测试一下

## 原理

github test

## 使用

修改

每个时间字段的含义：

|符号   | 描述        | 举例                                        |
| ----- | -----------| -------------------------------------------|
| `*`   | 任意值      | `* * * * *` 每天每小时每分钟                  |
| `,`   | 值分隔符    | `1,3,4,7 * * * *` 每小时的 1 3 4 7 分钟       |
| `-`   | 范围       | `1-6 * * * *` 每小时的 1-6 分钟               |
| `/`   | 每         | `*/15 * * * *` 每隔 15 分钟                  |

**注**：由于 GitHub Actions 的限制，如果设置为 `* * * * *` 实际的执行频率为每 5 分执行一次。

## License

[auto-green](https://github.com/justjavac/auto-green) is released under the MIT License. See the bundled [LICENSE](./LICENSE) file for details.
