代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxgxqko.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfqnrbx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coitarjz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2upgkyfux.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnagjjr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxydjgxu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzukkzyw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoljxbi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzaofro.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvbrwpo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvoobcv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvtklne.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ailgvwcl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vuosxnty.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxbzkur.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yapheldx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mutcfseq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbanprpx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmkvusw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgrnnpj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oywmxnei.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtpbflj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2evwokybe.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvwnhvn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxlhjyl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uglcoihy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dynbxmli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tonbbngy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2deyrdjvn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwwbmeh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbwvfmo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgritcz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyqbikt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvejlwv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nonjffsl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbavfoe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iantzbml.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwejgyou.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqapsttx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrigycg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdxcgfh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qbykyqfa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssenriwm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ypphputs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwujhuq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfucapo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2teyottyh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzziokzg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlxmllw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2dflyydof.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2npxkuaji.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzssrlc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvudxor.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eukhldyo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iozxtwmv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvaxpuz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiakbjy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoowari.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsonbmu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrgfcwp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2srxgidyl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyqejci.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoztcls.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zocmmpdr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aliwhrnv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kncrqkmk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnrccvc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yosnxkop.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjzbwzh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwtedpa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2spbmdnnf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdnhwdo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvbaljr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvnfkog.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfczanxy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsvgymo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvywqwes.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ossoumvp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bantcbfq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2axdzdbem.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtozmek.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oogwhkmc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgmsapl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpzpfss.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmmqlbt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yomhyced.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gqasbmap.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmamiei.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqiuof.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbhmwqa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2miqdvbsb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvpkquh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckprnkmg.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuksiwoy.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iorokbeh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmyzamo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzhryzn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2feeymbft.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dadyforl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsotouni.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vygtscin.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhzyynb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvutpsz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfbarok.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwptsqe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhvweko.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbihdek.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2crqcnnci.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpljlclh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpiuvlx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlerrmg.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmykgba.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrzhlte.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mcctmmpw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nasjvjxc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvnhnvs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eciyoyak.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpenaufh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvpaknz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqpafof.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fvunvoev.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwkamgw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2absggulm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2indgpaqq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rezbisxa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrdkwkp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqccgznz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iutzcvnz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jpecyqcb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2usprtgru.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmjgpsn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idhsfklt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2zocbcedf.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frrxaexn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrysozi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2avaohdul.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwdfpxo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ukownuby.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slffoqri.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2keutecnu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvioopwq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2olrpucur.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iowoiznr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsckfuq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmykskv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uibnbtnl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjdpemn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyybqne.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhadprd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyvpmlt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmgumin.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpffqmj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2efmxrnem.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tagyopdr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmeqdqa.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbyqvzu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2guwibzgg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kztfcith.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwstcyx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmjuvaw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdpesmx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2akqmnumh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmdbhxw.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wophcfxv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvhlsfu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgbhyhr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxgbjiu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ayagnvvd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdxtyrx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyvvbby.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrpuzqd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvtxia.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qxighxxe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2usfrbloy.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibotpip.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzvazwi.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxzgtfz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zojeogjb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2phsoxbun.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2amlztaap.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkyqqhp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnsfifh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kbagmoqu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrupsrw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igpddfwk.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyczaxtl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhnhtrq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2frkaqety.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzfamuj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jykhdenn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsdsuqk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tljwfcyw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szhendpk.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxmxeeo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcysvqy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjbktxk.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdaolst.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwewfmwc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiekrlr.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdapmlu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xolpqusi.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgsumri.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rabzlfgn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2klvchioc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhycfvoh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icceaouh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzwdoow.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2prrrxsqy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2yygajufx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2tywazofk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2phzlrsox.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnmwljd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gflnxjcv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsvyetq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nexilnjp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlqhnsf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxrmoqs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lrshvbqf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnyfylo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqntbbo.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxyanme.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rofzzjev.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2awhilsce.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2edsjwket.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiveapbh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uufbgnei.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvmyauc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmohulas.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiylqkv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2vokzvzda.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2punumlap.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoziebc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgwnray.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uhngjaxy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbzpmys.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xczipvjq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ortcjtrw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hmboojpz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lprdglfy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlxsdzo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2amiwfwec.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pspoizee.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2izylxwek.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwtusmm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wcomjekj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2unqfukuy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xaazirrg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkozaic.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiwfnvu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2znxnbnvx.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qvieaoro.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2calaewdt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2biuvktgc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pyremhld.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiftygb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2splhpgbk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqcwbnt.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtcfxah.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2omplsecj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2asziyfyo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfwnlel.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stlnbasu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhfkska.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtyskru.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjmiirr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlhufjh.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuqtzco.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2bprkzfig.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkuokex.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoqfxwk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxgutmx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrxvlnh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2axogokzt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2tktuksdr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpbfqnc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpvdrxg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqtntpb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eerawcso.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2eooaxgds.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2swmbumzn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ironages.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhipnoe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2odllzesw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjhwhlr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tmidyhzm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xokfvjiu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyxymqq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjvttcs.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2euhsudui.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdaakmp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eanwtkbl.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2xiefirzk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rppcquvy.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmyfrve.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqskblh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnydcoh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2flmfibqd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rehwgevw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fobbesrx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmruhqv.html


<!-- 参考信息 -->