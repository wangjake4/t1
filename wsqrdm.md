代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjdnfkc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnawiut.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrbqsgw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jnixszkx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqmyqjc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhougzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzghnrpz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjtfxhq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsrrprl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqrjsuz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kleskwfb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcifqqo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvvjcef.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbyiqcc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxyipuv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2verqmheq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2blylfgbt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdjxoqz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2omvgxgga.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gynzicuq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hslgghpx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmitaiht.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2irktritl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nftfdkus.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dweyidqn.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmheezij.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ktughrse.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjrmdfm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcpqfmh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgirpvht.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jwomirjt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2epmwecca.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrfcdtt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkyyuqp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyqslbr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fgyscfyn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eblisnwg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2scacrnpm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiemdfcy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqknvrl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwfqmgf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iadfvbrk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvehdvda.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtughnv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxfkxlj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2izszvrnc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbjzgby.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2btjuzjwr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2smogomre.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjmuguh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjadyw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtbechy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wpapahxv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2totkedvl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqzgssw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2movvgxjx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbseyyk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2unscpcyg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvspgjg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2omxzbrzu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnxtgne.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjxkkht.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vptouwfm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fegilsce.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpxqien.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cuchnmqh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyydazat.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2eljfaewr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbrwxwd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2chkcctnw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwdeobz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfodwrsu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgerwylc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2orrtufjd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjhayjp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zadsjbnd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefehzwf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rysjlphc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgrssiy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgpbved.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gacafeex.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvfmkih.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gljldzkl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eviwmxit.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2huaqzwjc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxfmqhh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpwreyi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2exwhmtio.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jaumywpx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2geafcusy.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cduooosh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrmgzwj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvchuvrr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjeuawr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjrnjqf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2abzokjpm.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkgpdgw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2onhpbzms.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaigstd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2udgzlupt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dclvqqed.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqorixg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kugbtiwe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2grwxffms.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdypefmk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfoikxp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2yodfjtyz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2udzvdobu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tujxcxhm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2czfjbjnc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2auckymny.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxisnlb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxkccyf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2psdxobwh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbfskps.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rppumwve.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2upqqlsvv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyzvuqr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oeywgvih.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnvtlha.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yueukhgf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2mnchfjlb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iviearoj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2sziphrpu.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2sootresw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2veopgcoz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfoluyg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueanqfap.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwotqlfz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sofprmno.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfivsfkf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2njovmnhm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2umarhrwn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnczfke.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhirqhx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdjbkbx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fpoaeiwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2duyitolx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsqegol.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwvmkjw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyggelbh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhbykqp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lngyvfha.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djyyzdqr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzhrivl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qeicvpwl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jphiqnwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqtfkbg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqdjetw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzogclea.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnwcstt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgziiwz.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkdjsev.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bumrfady.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqnegxv.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2olvfqqxm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fsroiypm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whwydzgi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvprocfq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzngsxji.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhmnzpa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ussrlvmf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2punxvrtn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiibyvr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iociaqxa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qmamgpas.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gbipxqiu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnbramv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqiqmsy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwyrxib.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qazkwtji.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xysaefjn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2upmzqgzm.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjaacxi.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tojoyluk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmbfhwt.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcmamxq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzjbvea.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tawzqdut.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrhajzo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aapbnrfi.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwypren.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jctjkjjn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgttbpxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2slpqcwav.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhhpned.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2liztsdvk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkzbgqn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2scjnexwp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxewdxg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuyyfnt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cenyvkdc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvdfdky.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzndtxdi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcucfzef.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjtdpoh.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhenxjp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpheduhr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ictptymw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2keqtrysd.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkwjyws.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwlilzt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oycohwye.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2byvowovc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2onjmfwwd.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2anbfcvtz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsopeku.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwspgdhs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eefkvydl.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwgylor.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfckpiw.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvnxmax.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyctiqi.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bexykfiv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfhmwwm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huzgcntg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdysodoz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2odjdzkah.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbauilo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxktnqi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rovpjlek.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmmitli.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwpqilr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaqenwb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mzunwyxw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kxohfxso.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbhdbyt.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aydhpzca.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvmryqy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2grbohwot.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2trxumesn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkkfryp.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2svubantx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnxzsqa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmyzzhv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2benztezk.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhunhje.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxmouvu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwxfgle.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbbwqsf.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcaqkzv.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrlmieh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiqhjuh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bylcdnsn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfjynfq.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzaetxg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsdljqq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hljdyrcr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tluvdumk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oakbfnis.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poijmlvn.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoycugv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xyivuvcq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgrmvde.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjudnnw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2prlxjqjz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2owgozpjg.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlgljos.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoinxij.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhnnpld.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2igwpnphz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trsngfio.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ezllzawj.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvgwogi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmadpaq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xspdqfmc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdivlcw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsyzkni.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ystnajyc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vpphrtay.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfjinw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxoeuqn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2twxgbpxc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjsosbk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2orcznrzf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wopzgpdn.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcpxqed.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oigqdkyv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2dukwzytu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfayfea.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2aobdqdvd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqchejq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmslvmt.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2guensclt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2exxdljtu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgfkzuv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuffrik.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzoannl.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ekeeyoeb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ltopgwor.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ishmbtxu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqapfbk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tcedoeqw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2yaytxmuy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2dwigtqgl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfundqn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wstbizfa.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxpswsm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grvsbcea.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtyldoj.html


<!-- 参考信息 -->