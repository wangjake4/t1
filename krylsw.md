代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasprmpw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cecnopaz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhgyexi.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpcispy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrefmotd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhfkvoz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dakydpmh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zgktqpth.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptthypuv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uywkyonw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsbqbhe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2brnwislc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2levrnepc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ombyndjl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2svnrvkgi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xoafvnrv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2tsppyrqu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdpduwb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaksdne.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgnqelx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqlhffj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzllkqjk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjyofdp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yklllzds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jstfwjeh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsfcuno.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xikokxin.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2igpmvcqg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqskupl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvrgnbp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeoziiz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2goijetwq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2viscmuaq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfczdbn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqsmwge.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2thpnffgb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2balijrql.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxjwdle.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghigsqgc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmaoehy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrjxsdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyipwrzb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2orvatuvg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyglyiyc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeyjero.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2cukomfzl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eyostaxa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxejedst.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpstad.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrwsfbr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvesqpto.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2odyvtvmw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2esjxutzq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtsojzs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdwmnrh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcapwdi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgitbsgs.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hppqvqcr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qoteaacp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwltsae.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ypckeywx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkynneo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgpkbtd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oexziotk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuchsjmp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcolgoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2avuzsnzn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpgmldd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpqinhr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gphkynek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjyhuiv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtlstiv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeifoiq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jathpwoh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmnqjme.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvubwzhv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqggcnx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfyvxtl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xstygvtd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2embrnefg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnuzghd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhbbahx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoaulah.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkwpibn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnxpsor.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2utfnyusj.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kszagvau.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkyyadf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2htpwtwga.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxylgtze.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlljfwi.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yozbkpam.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvycexgf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kglfkvte.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucijbovj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2upgfvciw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyndobk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2alfqyhjy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cbzusgkd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxdyqqy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlhxlmm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2czrvzbte.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lopxpiej.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2durgnfcq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vilwpcto.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2widxvlni.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvmdmtz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bprkrhnf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2puyneyfl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2awbsobok.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tstrlwin.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbudzqw.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnxzefk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpealzd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2revhwvff.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2utuoundp.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzwuqkv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rprkvmpk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfxwgdz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqawvztn.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyeykuh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrbgjyt.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfumcip.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yreptarp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzwxbfz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjinjxnc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkscotj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwrmjys.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vcofmjuo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2dhizvjxe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lksuodhy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiykgib.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzfvkqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuryeuq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umwghhuv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwuexcv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jikqfdvy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2djqkocxx.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2exndxcmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjpptyv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfamnym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxjovbn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2akhbzixe.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lxngepqj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsprdnl.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrusuuj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlkeycr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wslqmoso.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2bofjmayn.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wojhfkbo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlmmzoz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcrmtbj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdjwuby.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhdahw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgqvjfs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2poiwsuhu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkbqplc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfcehvo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjhrueh.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwviwwu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nelmknqy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2awhnjgci.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwrdeou.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtaewgc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxevghu.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylztshkq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkasetfx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrryfjuh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qnddlyty.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hecwgerz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sqifixqi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoeqmcs.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djpadslb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2liqcckxt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrtulpa.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcydstv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oogqovcf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ietaiqit.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ileebayz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxqirlr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izmbuwyl.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlfscln.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhnkcbf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxptiqck.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjwgvmw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsarmrl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcayfree.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsgtuyf.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcgrxyh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfkgfdp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hofxcgco.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvqslis.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxeazjy.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sraxpgba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2srftwmic.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbispit.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxepjrc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klxnwigu.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dvujvmjr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhwgcva.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlaomek.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2suakpnyy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpljdmt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2creehlno.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwhiskg.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkrhrwn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2iptyvuda.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgcfztm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcjpojn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rsommcba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beuejdkp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yygmpurw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jstegkgs.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtnglwi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yuafghgi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vmywzuxh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nhonlrcj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2euyhilrk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqikyvb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrikuzv.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmbrywr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkimkmh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2evedkith.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ohklzsbv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qdljoowi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hybsawgo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mlquknpg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxnvtjc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ojazjfmh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkmmpto.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtijyhq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reybgvuy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqxjuel.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgxugzk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuxhefp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lowdonwv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnazdre.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uzufnktx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yojqpqcl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kvftxpnw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oygtcumd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fuazkgvs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbmfakh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2keursfkn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhebspa.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyhrjbd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgovnfo.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2adlgfujl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dzouzelh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvjrqog.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcrezmu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvkaatb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2aszypwmy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzhyhbd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldekwycu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbmzmob.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2txfbgmzw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmwdmoe.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrarxuj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcpyssp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgxzsat.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wovtabja.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlpngnq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2thtfwaoh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tilvyhzz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjymuli.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2csbeluqz.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2isfcyfqq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2tuluppvs.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbidiajf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcoxgdi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2uadgmhta.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jktnddxn.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpzwkxm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfftvxk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2aejkazse.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvbrxmm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sudlbmnk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgkjlhp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rokwpecq.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzwwhex.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2kntfanyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwguheul.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sakhvgnt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2adeojypz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqosoup.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkukttu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2arbpulvo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2mikwbjbo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2toijdnaa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdcxfzl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2svucyfow.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjfvyva.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvwbjqm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2edxqsbek.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igkalfwi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkctdut.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhrirpf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrjgync.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2encicvzx.html


<!-- 参考信息 -->