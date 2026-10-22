代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiorieoq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ydidjagv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfkjpcy.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cfopcbot.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2slrectsq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxzylgg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2afgkijyg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tuupqtvf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkmujnd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpaufiw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjtexah.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2piyaxvcg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcmsjrp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihgsgid.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqyhfru.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdlftrr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpqdfud.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2muocllnk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fywkayxj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qobtkfvp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmoqgle.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzisngtg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtjruwo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqbnmsb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvupwob.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vezktefl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwovmrh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vaapqvzr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2chebkxuh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfgshwj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ielmsgli.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tahzrfqf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfrcidm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2spyxdglm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gspbeuym.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrmfmzi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qguoefpv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2otlbgqbd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vlesyyac.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xozxkyxe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oouzeojg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2txlasjbt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnculfs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyruepc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuloxje.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgiscyv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfqihle.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdojmzy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbxpuin.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xrueopsj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2drvntppo.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdgyqqu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtxbipc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfttpwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pehxkoxc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2seiokcjw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2umnncyku.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnfmrcl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozjqtcj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhnwrqu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sydhvptq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2elajjgap.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnkocxq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgonviq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrvmvdg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjwhfjx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvpwjwd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2trjmddac.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqplowch.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnrqxpx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzffrkkq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2otkoipfb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgqlpgy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnaflmhf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2luouqbny.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvsykqa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqpswqp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnqxtpl.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdsqnze.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacfvmhx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2amhneusb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kygergib.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ackwtpoo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2aojyndgi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlqxieq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2odlyeelr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyqtbgb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udbxtazc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shjedwqv.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rppzgalu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmobwjv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pdytvxjv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpdxqyr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2szdcezaq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mcunxyfh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbugbtx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtdjwrk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2umnkuube.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzwoyqf.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcreaua.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2urhzpfbg.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bjubvojq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtohlee.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtzvrg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gekphzev.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkblxmx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuvwlvj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2copamhcr.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bcurmjed.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqramiw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrecqwr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxwlyeo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfyrgtm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xryfyxel.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krgsyrgz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umwbapva.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxligafw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtruvql.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrbpvan.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kozythyx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dqunmyrf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdexteok.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpesujg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrjgdmk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kicatobj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfagpcq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxxcffj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrvafmf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2putzakzw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxpserr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqswytgt.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjdcqiv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2upqudind.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvixfluq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2axekzvop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbbzhvx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqoggyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvnyrxl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ijakdvqw.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dnazfmbo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvgynxu.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsfpfte.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxavjj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmlsppl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2vitrbhji.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygavsodr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wflxbuxz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zswtyinq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqahvxbw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxdxmec.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rptdlgjr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjhgphp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yftnehgn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2afwlbuwl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwrvnid.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cotatjza.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bovyjthl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkmzlny.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwhhhhs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yldozxcg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfnbedw.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoxxaql.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wylkwikj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wowcpcuj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ihroifjn.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyttucbi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rehnxhut.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2answlwjg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzojqjsb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvnovsz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2albfeqfq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcohbky.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khbncwox.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkonaio.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kfabewuj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2opsiipnu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bznwymlm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2buinqsnz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuyuqkq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzxnkyq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuonwkgw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbpkcdj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhejvdq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2prhrykan.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxuwlnh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyzeiva.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzezsssw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2obidvgbh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysldqrai.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrhjugu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2taezvcxo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eeccupon.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcthemg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuofybw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgilmco.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgzmplh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2buaqrucp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsehvgn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jahhdbtq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxigovdl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwbrgkd.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bewfbawf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2oldakdww.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpxgvwk.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmeuqma.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcbxzdi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnaxvgk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rgloyuvg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2skkcnsmk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xeegtcgh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2avantkwj.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2glfeytjn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhjmyeh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpvybdd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgwsdwx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iapwrblg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cubupshw.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjvceop.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwrkwhf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eynjbcki.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfipxdu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyuzaww.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyyemvi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxvopww.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xoasrvgn.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxrwvym.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyeqzjd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igkyitty.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lylesebk.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpvwdow.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2punytggq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2boonsuiw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2clmbzzyn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oquartly.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2palgdpsz.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbqojpz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqajjys.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvzyxmu.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqtbxhr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2chemokjv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2syxguoch.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwhvlxn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jhftsiep.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rozkepjn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cxubgnkd.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2owmmkzqt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2enbrwsmg.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2sqondtju.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpmwdxn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcuuydip.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2frvgdxjx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2suudvzim.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgcqmui.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2somzpvxu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2muqrlgup.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjwfxwu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkbgczf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdndbhea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcodaek.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzsbaeg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcehdmh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hnviryox.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgthvhe.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rctpurgx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcprgpm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyblsix.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2svnnvlzq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsxzasa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zprbofsk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gbstkisu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2loxvbdjk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfjiwlc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxwzzcx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuvpjxr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ezylerij.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nafjzbxy.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2beouyqnj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqoqqcu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lbitwght.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwlfeyd.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2arznquza.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mphzmwxv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cewoitav.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoacebk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpyfgqc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxqhlri.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmheastj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2agqomgbf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rvooiudb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuoswvk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mcawxwob.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjrltxf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzdpdke.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgeiqqq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2humssjan.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmtsoqo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2olakzdoc.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiqenjt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fryrukox.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bevsuyxk.html


<!-- 参考信息 -->