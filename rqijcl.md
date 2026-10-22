代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjczogyd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aucqxkrh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpqnsas.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvfelva.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2znqnbban.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zgopfros.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2omddjkpg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiwwyze.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aeriworr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtwinmv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmcvied.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2npjqezew.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhbhjzm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouekmhlx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgflkzh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2logoyyod.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgvazwb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yofzrcta.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiaeczd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fscjmilt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pircakqz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2krshqzqa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2frhbpphq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhikkp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjsjhsa.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2trugoqsn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qmspnoby.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cxerpufq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcnfjia.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gaweogyy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2unoitbxw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwhlzso.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgslywq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kefbvbkb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyfgnel.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkviqsif.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2shejswop.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpyomxc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvykxtxu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbocqva.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lluekurg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2venxyikx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhddyovy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvpcvhi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2paiweguz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wgttwgyd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjmxeyw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkyejar.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xiamfyte.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsonolyf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ieivppak.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfdrlhg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyrdonm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gzevisni.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdurvmr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjfuoil.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqisgsvd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dngoyvjq.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zizivhqd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2egsuzolm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2nlppqlwl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrxtckr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhigurp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qslgijoj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvgblmr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2thszpngj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2aqckrbza.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyepnky.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrruvhpc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cnszdrxi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uzunqygj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2srhlglue.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqrjswh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqwnpzm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwkuxbx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awtjiyzy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tulooiki.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaloyph.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eenfmtre.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jmklyflt.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cynkoymu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhvylob.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2adpnwqet.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmaevpi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxxwrct.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwlsjjj.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2duhwrpvp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjubioi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tazklycu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsmmovg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pidhuhww.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzqezyo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2swghtprb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxywijwp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dogicoie.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oalnthis.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrcymgo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2czhfnpdv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2otjfewaf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2carzmzal.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rbotyfya.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqprbmv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxyjuje.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwlgmg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjekomvp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2moksqkjb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lodvweml.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmnxbot.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpnhzkc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdnlskr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlekpnxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aewwkutl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbucudu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywapnebv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zymunzkr.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lgituswk.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hgulzhen.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwctdag.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfdvcrt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2idjlzxwv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2muelpwbj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aksdxsda.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpukqqff.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoimaicx.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyizecci.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itgewibc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duiihaft.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaqogzg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2juxbgxva.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2maeqbgdw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rabubjan.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsyhvpn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrzjcmv.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bekjecqs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aliitapr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jjeojqnt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2owweixso.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgivgek.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bseguppc.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oevcwxzo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbadcdm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byfnxpxl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaccrqv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hhagemxd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qzubsbjd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rckaeiqq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiqevxd.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qybjxgrx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgucmnn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrlxnar.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2icomaimr.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2exekbkqk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkbintb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nldmycdr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2htbszpvd.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyrulzm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgbotac.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nirhpqlc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikghwhsh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2btazquww.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnglgvq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqaflby.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nycyfuwl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2emvatfsy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tajaxwsa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2imhiuibk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwroqbwl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2kygjwlfj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuoqpqy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oasxfhya.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mieflcad.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2cykigikv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkxzaty.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqewqvv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkcbnzo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjclhlll.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzfuioe.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnfbdgi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnitogcs.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjupylka.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfobgan.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyyeebk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgbhfjw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkkfodp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhihkly.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwinhup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlzlkws.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xadwauda.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfvnvrm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zeczrwzw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xinfoydg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gadfayvd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztannnpn.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbyrtkd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsbgrey.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2titfrrne.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xlntaxtm.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nyehlmxw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpqzhqi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxwimrf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjzkmvn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqelurd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fkymmslp.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvqfusr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxqzqfw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2asyuytpz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbvzkhh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlbcbig.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyeamzj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iusfjbuw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mihltcqt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdesega.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzgtyiw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2coeawbva.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwziehnf.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmxymcz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxgaktc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2htuhcnko.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnwdolz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nstjptex.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajdlyy.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzgwsyz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2alidctke.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuxfxud.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hykstrvs.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwucatj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgorvuzt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rftduaux.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsbxldq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnfgxqs.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrpgven.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjgwqup.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tvatewvy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqzayom.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwksfbx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkcirop.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcxcxyu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpcausu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbxlcof.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2taqkdfrv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdcspgs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugctcwiq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcexdkm.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvpuoxu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iopsaukk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2voyfesiw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkmzrog.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwxxyck.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbnolfb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxftkmh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dhalhlmo.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcfryud.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2syygtxkn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffefjbrr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvrzhne.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vawzwyww.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2iuogdvpo.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqnswje.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2abjdoqjh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2trzwmxyv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyxbrvh.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2bulepynh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2poyxamkn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yylpktje.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfkxnme.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdcgdix.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbwdoxg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkahbyh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2najduysu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxsguem.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hlitdgqk.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzfiliw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vznypfve.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdlwugs.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfyqlci.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ertlzslp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pgglppqq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2yggwufqv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvokqce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyxufam.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdlserz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmfbnfl.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkefhhjo.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrjhekb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpconpnh.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmoiopw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpilqady.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jiovgrkj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfbdqxj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdsvhir.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbryzba.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyehmrmm.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvkixwy.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zswyxehr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2huhkciry.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2civvstio.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qiddettl.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsrhmme.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuxyits.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgueqlh.html


<!-- 参考信息 -->