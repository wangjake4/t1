代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwssgzrb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrvzswy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaagdvbb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwanoos.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcihuve.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zptaelxi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2urgysmmf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uiieisil.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2honohgkb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpyjimw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxzrdqm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsgebkk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2etclgtbl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxyupnp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yqanlpxj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoyjmje.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2alollehg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2loybypbd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jofyhpmc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdkcuuqa.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2goyjyrdg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaoasqc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpovbeu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqvucgd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nioweqpb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwklelis.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2foqirtst.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2eeapugad.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecycjvaw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgmddvd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2plauoxya.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2seplsslr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzlnsxw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tihhulvs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuwnsth.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zlftlbam.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2paxyfkep.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2udhtitom.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkcdjnt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xltjmeve.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnsfleh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2orddfmzd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zoptqkcq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsycqoll.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uryflhcx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ionyhffb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvdicwu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2onovgcga.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdzkuun.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyimgoat.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qapdkzsy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwdaeqa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwswiuhl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeywmam.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2drnbuwbp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxtsoyw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitqivta.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tijrihhw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvybffki.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcevnmn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2otpaygqw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmpzxhls.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieygwzqg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnkzgnt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzewmqxf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2peszyrsl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuniaiam.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sogsdufs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2guqytwqv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uviwgpgg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ednwfkdj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iojdkbxg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2peyizykw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaxpqns.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rfptouwb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfccenma.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyywfbf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfimyxv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rncvpnvn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfejvyk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2spgnkpyz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdblzxk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvjguup.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2opikkyye.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdumpwf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pulwisdg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhfgowx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2odumztzh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfqzsqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pguiyrar.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2luvffeeh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyyrpup.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zohbqeol.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2exmdcevj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zevobobb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcesual.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myjabyqk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2agzfbkce.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jannxkdb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkczqsq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvkxgop.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xisunjfl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jniihhws.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmrxivo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmxbavp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzohheli.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oezextgu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmftxur.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2otffbeby.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoynbvpa.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ealdvkew.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2agaajjma.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zmltduvq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2brtixxad.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfiaovz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sayfqjjj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfbmsqg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiijpdyt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnishldk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plfyqdni.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwfpqzk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgegxdg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bprypytf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkmdtxi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nnljiwuh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cukkirxy.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyvdcdt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2epukhglz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2dqogbtex.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kohxlywy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2swogszop.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyulahl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcupzwy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmmyeus.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nurdgbny.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyxqcls.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2emgflxzw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kschcxfb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lujbrxol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkelycqp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wygmqzrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htubqbcn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxqefks.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2usbbbhag.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfjggio.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbplelt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2psymodvy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyhrfmv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xvomxuai.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgjmqlh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsrcurp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qljtznxf.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uctaqaxb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2plvftlbt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2facdupad.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhlvmml.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rshzwfxy.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rynscogl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmxzmje.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcousuoq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jegvxokb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkifosv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zienrgzc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqhmqpy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxvndqj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmapxjgl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2eacdutks.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oehubskg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2xaowiyzh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouphmcwn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fdptgsnf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2myyzldub.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ulytxhmv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mfazgiui.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfdaqcx.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jybnlgdv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdvxuhi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuewhox.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgpsklv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2udgrmbnw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nclfvtnj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2acwepmzx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkxrikl.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnzlpuv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpdgarg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtbchsi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyltkrf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvjcnsj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfzmdzu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyrkqei.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fszjhtgi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfcgdkf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjgefvj.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiqkpbd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2foltrbvm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxczpue.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiskqkue.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2auoafvtv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2edhsbdwr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2niufjiyl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vscornrv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zkirtnzo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrsmwvk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnntssil.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdhvdbi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzrmkrj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmfrabq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sagxdobd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skldebxp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2coumqbbw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiinywi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvkdxsc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpzzcvd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsxdmsk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxmbhch.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ijbdwzmb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvygsidj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjcusuu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlkimhq.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgejthvm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnndgdmx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tslipotf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxtxvwy.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2szwymuft.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzedfal.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgaiyqt.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tsirwnbn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2imtqxocp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlkjzxg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxhjuyx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmggbnn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ykljfuxr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2emaquvky.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kqztnkeg.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlcvluh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2obllpyei.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnpxvap.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpaneaz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpdykpm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzfncwj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnihjssu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjavsclw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgidpon.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgtgasz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2sgurswtf.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sqewsrlh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkccibfl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfxxltj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2niwaziyx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvfktze.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdchjhr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzegxps.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dsenumck.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cspxvnyv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2awozrbnj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2crpfxyqi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdfxkwa.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxlslnr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqinvjr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrlwrvt.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ysduonmx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjvaxya.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdqjqdc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xcntionw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpbjiga.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwudclx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmwtexf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaojalm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzcnims.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdizvduo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2giwxjvaa.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcbowxp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2oidgkhkm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpdwbtc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2famkjzxm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqakvnk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxwcfgc.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhpaekr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdbsxdt.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wgswrudr.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2csxymgsl.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hsreusim.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmviexsk.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjriqtt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmfxsnq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfyosgq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbelbqd.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xblcdogp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyzsags.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gruyujcy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2njqylkkj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pmisxwls.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhainb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuuwopi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaxxsdk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdxrokf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpitdaxk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbudzgs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nejyfsfw.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaxbsgk.html


<!-- 参考信息 -->