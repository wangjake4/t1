代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeitzms.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2opsycoow.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ogenpbvn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkdynrb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cayoshob.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2drlmwnrr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmjwqte.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpycpige.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeiuxuj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2orqxcnuy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsrorhy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgihbysw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnurrxwt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yllatfsf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzzlezv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ruydawoe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2utnoscej.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqzbmgg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ontygqhh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqlwltt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2isivwflc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ugiaxwqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoardweq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2irrflcyp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqzptlb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyrklou.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjbwhap.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2advheznp.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iaogbcvk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjqwsb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itntokry.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtvbsus.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2seqliype.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yincegwl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xspfvtzk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmkigxz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2elljuoyj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtpbskv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2aodshxtz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2itafhtbo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxggbxaj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtkwnzk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ornygszm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsggrbb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zepbojkl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qctpsvso.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2odkuttow.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oqinefrz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdgmzgz.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2osycidtm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvwykrw.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uljjgiwo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cikhqahh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgurvehx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cddquvis.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnvydmd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgisitsk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wixsosxz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uobomgtj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2okuglmni.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhzylbg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2crgppqod.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cizhofap.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2trbdgjik.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzaqmng.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoxkbfx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kmackoux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnmthxe.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkfbygc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyoijkh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfhdfkr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpddereu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaaulxe.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2icfnyfwv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obyhjtim.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhribmfs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2miavumit.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofvhlc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaisnit.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sezzfmll.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjafxebq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsooauk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjzeljg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyfvwot.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2crkfgszk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2byeutvyn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhyxph.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzfmrdv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byyijaqa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbhvwvy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnnrrfi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vehqawmz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zsybyzkj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxlkgsi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyopehet.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nlapavfm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzoherc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2upoaqbhf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtelwkd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2marqwwta.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuqwelt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtpnsy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2smjxwxrb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgdaxzc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2czmgdlbk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2deldcqrn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2toyihise.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpukfqqj.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjhmncp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqntnyc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2agxptags.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2buuuzvyf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhalegg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fczlhspe.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wfupnvkh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2frqgcnan.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2cjimaump.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxihgb.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpsflyf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgnuwfc.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiojbvuf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqwojqc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcjqamu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2attjylbi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqrnmkk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uoykxkqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2sltpzywd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnjkmvd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mxowbarr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnypouhw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyflphay.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hugqoxvj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xauelxpr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhglpdg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehofty.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2coaejcvy.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2udtqaqku.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2izagesoi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2pektmvgj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2psnlbdtm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyvzomx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khixvape.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qttvmpus.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhosmef.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhseetn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2adxltogq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2toprmcvv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vomzyhcp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcejvjz.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2romstyjz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmjvpgy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkyuqfi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpuupgl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnvshxz.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtexdvqf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2olovolla.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpaiwnk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnnisps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkpwgmk.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxzkgtb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnegumd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kepybxmk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tezctorw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yikpbhga.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxmvbqe.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2epwuyhqy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvyfoqf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzkuxhn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynloipto.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmcwwdb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zttrqavo.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hholdjkg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eknsqudk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmfswcz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnnnwks.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnfxyqw.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lbohwylx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gydsenbv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgiynea.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrycdiw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qreccdsa.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzcujmw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkizmrb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vpswkjuo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdzhfsg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rklylaqq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvevdrga.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2qpczfcqn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsijtme.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkgfvdl.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuyufyk.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxpwsgr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqocprl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnvdfvu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhrjkma.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcntensy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldxisqo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpwemuu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veingrkb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2riqukapr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyufbte.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2teuptdbi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgekxdb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zewygcnj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2abbsnlrd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2djdrxxew.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmetvuo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeojcjx.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbglqsez.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvtrbul.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwwwedm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxitzlp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ganphnpz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfnzawo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpvqhej.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuccluo.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cpojaljg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vulfyycm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbpsoex.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nraaghjm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wsldpdaq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2npimnbti.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2knenfutf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tthzghtb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjarvax.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aodzfsnq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tyadftpk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgphpdm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhozwbs.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpimrdc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xszhnklw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvljsspf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rweceevl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kbneuivf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpjofty.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ciptkxug.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxkmqxl.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfnuazv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2duvlpbbz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sopdkldi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmqoxaq.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qarqeirt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmykawq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlchfww.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iygjwobq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yuihogpv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gzabjbgf.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wznvfdjl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qptjkutz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkfbrqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2igregyno.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyqgajz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrbahzf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtppkpzg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjgexxl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2usrztohy.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2smaqszuh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhllbcxc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ocawaxhd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhmenib.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2benxuejk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2sxumbtnr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrjkbzn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqtqmtn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2aerzohef.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxkggqm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hattlxtc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkatass.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nuupwzxj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcwhkda.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnwgntn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wftraasj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2okbtoebz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuyoawx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfefsaq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhbbgbc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfgajjm.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gqohkusj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2birzxfgr.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qzimumsp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qftwncum.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zqipklzo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxmpvej.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkbpkxy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqitzcmt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jedmpctw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2clazgxdg.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnthrhe.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tolwbjcu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpfxlcp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxtyhkk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrccfqo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snngbita.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtvfpnj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiovnxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpxdmtj.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2psrlqrek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrwhfrf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyuwhly.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzlqqmb.html


<!-- 参考信息 -->