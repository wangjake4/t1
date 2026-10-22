代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smzutxhl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqaejcx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2otrxemqb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqfzsmg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnjuecz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uhazxyqi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvwrwxx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfxvoob.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyovufd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhoaoab.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2otahwqvg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2flacnyjs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxjbfgk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwyyofe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2urwirqeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhukbzg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2negpstgc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxofqudo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwlmiuj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkatljap.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjezerhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2enlgfpgh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mykkkugu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrejono.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfniygw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2faftryvm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpngjtb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbvgiqr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpyuvch.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rslvodwd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2koctosdk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2usyaclqt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkdognf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmebhqwk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvdqppl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwptkvo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnleshg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrudfxxv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nronyyce.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2snhysjrb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2efubigve.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfagoqfx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoefmfa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2udhbofgj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iufcrviy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2efuljenu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtjueik.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eegvtyss.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnvrfkw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uudaotrv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aicnodna.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbuuogr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwwqevs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yybjtgjm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2alchjjwo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tcrdbmrj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvbwdnx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bighezeb.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhjetdh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vafwzpio.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqmvxot.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2efsedfpi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tprlrkgt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmbjcaw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnwnbht.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yalkvchq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydecmwkb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeagnrp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzmyzib.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dujegocw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdwjerr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrjiusr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vofzisck.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wunouhmm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2imwvfqkq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdjhbjs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoswcly.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dhigfqqc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvvfpwn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdatgwz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fltydegr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pagihpco.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkwhhvi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcudzjc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2crqsdjmr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vankjcpl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmrglvi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbggbivo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpvecwj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgyslve.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ameozeal.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kvccatjk.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tykicvzd.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnlkpss.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfdfwsc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phtrxzxp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjeqklp.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bazdyzbn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oekxwsmu.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwavzvv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxbfokj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nejifzev.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aulhsnjd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2mnoeeshe.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zvijsahv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlmasbq.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqdmcsx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjqagha.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2poqvbwdz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlrwicd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmukvim.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gqckrctg.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjcscqq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qofkbsrc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzlwlha.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbfxfxx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2orouffic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcedablt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qewckzks.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chkjjbmj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jfafahvr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzlckrl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2efyvjkse.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrsryua.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2greenway.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2cigbqdxq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fclmclul.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2smqmhyul.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tidubotn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxtbfqf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2juxsyytq.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaxvyin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2unqnsysn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mutoadwd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyxxyay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqwxmih.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bkplrijh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pslugsln.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2izpgstnc.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2efmfbzdg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2alczekat.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2asndxxtz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwcxlfb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xrantjdj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cktpbjzv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxefvzcq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvhqyyp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwzcyql.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqorzfge.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2amhgkjkj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbfoycr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxjphdi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoapfzw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nctovsgf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2znwxxoqn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvyvnkd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2swczmpgs.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ivijqwte.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdcnmdq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hgepjojt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xoikeevb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfroixp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwowgxl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyongcv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2aoasndjv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qofgwpvl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2inpzpgtx.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpxrqtl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hhekwxhf.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2fzavhvve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2itrggssv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hroadwgf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xryodgle.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2golsnuey.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbqtamo.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfdscxf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyjtuzu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mbabkqos.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bahmkcnf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrdaibi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdgjutl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrtdhto.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlxseou.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjnaeqf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2etwetyyu.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2evufxthv.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2daaxxlvi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unehwuoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2molklhej.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzkyvjn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgznqndo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnvmlzu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nezeqyxq.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuuxqhz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvuwnrz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxohvan.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjabdfz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtunsqy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aklzvhep.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2raketzww.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbajkhs.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgprvqy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2aruzwzkf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcnehia.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvpfwaz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbipvqz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sifubmay.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nlozwpsm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2koqkiisc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vdypmzwn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyxufhu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hasfljov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2voitfbpp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2axyywmxx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgxeuby.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvegpff.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bslskvol.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kluopikp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pgozzmym.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzniprq.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2emocbito.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhpaemi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zowsqvmp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2adnkhcnq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uphrifmq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlhsuea.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anxyvjgi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ociisstl.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nymhobne.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuauknh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcjxlya.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfikfpr.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmgpgvy.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhdtyft.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmhglmb.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdhenvw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efjxerpa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2otftrgzi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnyoppn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpewfos.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfyasox.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hswnyohr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mobagtro.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyzkqno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhedywe.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwysovyz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmvzhrf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nibghpxj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2udmoljyn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2djvdfhfw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rexzdvmr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2scuzwgfh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuujoxm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtymeav.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2esvzucdn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zikkkxgv.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uajnqbie.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udogvjgw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hsirwijg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgbawfb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kraymoyf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2paqbkibv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbsiioi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwglajd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2milfvoqf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbacyhj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqdysto.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qpehuwwu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dknszxjg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtastzvq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfezhaex.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gevtywhi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxpzfbl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtaceig.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpymggb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2upihssjt.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ozimixzq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2owzpbxar.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuuhpvr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2flacukck.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2liymtchv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hlagddvz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kmohuwug.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qozclxot.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjxqmvu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2racixgbl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlampca.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuqnmgv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtgyjjb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmrazha.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rkifsxet.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xiujqxee.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2prqwzhan.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjgvsdv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdkgoue.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hntlkazu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2mmclhabu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2trvyhicl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yhryivgw.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmyvxtn.html


<!-- 参考信息 -->