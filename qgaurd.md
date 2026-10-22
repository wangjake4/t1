代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jejeujnv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ndipkgka.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2abfzsppw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2banrjvgd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyqlmxb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2whbaikdb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yutnqjgs.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2csvjujrq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqobqyn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xfenvsny.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhadvjqa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtrklaa.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbbhyqf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnhmdwp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbjnzyd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rserqwll.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2kamocljl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbciddey.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdanujc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2echmhqtz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kurbbfiq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfbjaec.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2utlonmgg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rweesyzh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvgivgo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjjxoiv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpnceyn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2megylnwc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhhkyff.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sppgrwvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwibfovh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcashyg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwdpnxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gccmyuac.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtcpjul.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdcefrp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gidufwrb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvptshla.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2unjsudsa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2uipfwtvi.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqtofmp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ensjjzdm.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fapvduec.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvqcxyz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvbsjdo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2clhpwafd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcypdikk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eczjupdm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ludhtafp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujslqnfg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2sarwihnm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2znmqvstn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2splezerr.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2czlhxlpw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cylviukf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkveqlj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryevljwa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2saygfzmm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctnezkf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwzemcd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdngwsbu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiqoybm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjixqzvi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iggewomq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnoewzk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqoqbabl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gabvfupm.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wnigehwv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jccrabwk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgzrmmk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzulyvhp.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfnysqy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfodsiy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvrnbph.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gblbdgkq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktelqyvl.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuxyhcj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aevgggxk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ukffwmar.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlazamgr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kauoicxv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2dvafdkkr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2umhskvib.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnieest.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsxjlrd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2szczabre.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvfcmvn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2uunlvzxg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2okpewrwx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2eluootrs.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcreubd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuwtkne.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeptxryf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwdwiym.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyrqkng.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2algfhetm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsighriq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtimvam.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2khoymcqv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgzcufc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcqnldd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ksonudtx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfnhufd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2izegilqs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2clwbvsod.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwvvmcx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2usbmchsq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2pysmzgvw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hiludsrq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpwgthd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2vbilqybq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cpywtevl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tmimjmvi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxirstjw.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ccuxhnxg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zupcexbh.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2daprwrii.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgmosdb.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czwjebef.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxojoiy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2feixgkqk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ummjgsqu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufibwuju.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfaixzhu.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uhntfegg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpeqtznu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlotjnf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtahqfdl.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbmpslo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wobheses.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xheazzid.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2unedyjst.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiysczpm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxokjar.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grrswflf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwcwwbd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qpplxxab.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppunvtts.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2wosqtexn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bytiqkbm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fanznctr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyrxvbv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzbnoxt.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwjgvbo.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cifjjmxg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyqyvul.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzikwnyx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwcyqmw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qqutvrak.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwyvdvy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzxtwhd.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vswjapvr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzsslay.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoeeudx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aacnitnq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zftgivhh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfmntyc.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yinfqxzz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sfchbixf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvfxiwv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmlrftm.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxxnqqh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzerbwsj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyjszwk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2spodnwwb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjibreqp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbaqlkx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpkluyy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnxhrwz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2difhsbec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jajxghct.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pamokbdu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfidwupu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qaonwjms.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2amqsexhv.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rykhlwzd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcnythc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvqzbde.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkogwvb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsicpxc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyedwlbu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdshcpr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbkoqzj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzimbcld.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbniioo.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvrfisn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2anddlkaj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qavuhjpt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaqpdko.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgcwmmm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2osohwqob.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlhsvcc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzkkubl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmsbnfp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwyyfbm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uenejhnx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2drmxfkso.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfopqix.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2foaasjxd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wampayjt.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2eajibxqb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqbsebp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpmmzrz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjrmohd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiqqamm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2idfcvlwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lisazhjz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxkwxmv.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnamrdyo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2exagfxld.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgeqnmt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiqqwlq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2nydhacci.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjbjdzb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2bpumiafv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoiihei.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2btfzfkaj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ukprepsw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2lgawfmlb.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsscyht.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwufjzl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnlivgv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmofglh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ouutmumz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2trnpadhn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2spdgfyjz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jvskhwbw.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjjdsjp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrmewxq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzrrbgq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfevcwy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hypgqxmz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlvtaip.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmoihqq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2htfplejr.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbkdfvi.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvmjlhp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvczjrw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cebqxdrs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aeshbpmr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2owsqjkmp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wybyxskm.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvppusws.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tciwtgec.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzajars.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kgubheaz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smpuldzb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rahagdtv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaqzwup.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nloztvqq.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzqzivl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ctririjg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2makggbim.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuxfswn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nldcyspu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzajzqj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sljlqeoo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2szolykxx.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqpbnuh.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2oaslhakk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbeltgf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgoooz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsvhwij.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jekzwlgr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrbkxus.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2opdbbiba.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxwgotx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vygiyxig.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jtawkmfd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbckhfi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2pijqnmzf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2skxpfaob.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvfdmtv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ecloiweg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjwqkwk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglkbtu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgziuvx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2woewwvoe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2oguiiiwd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpfxabe.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2koujrkuh.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2tgudxkcl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lotepwaf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcevnzu.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bomxdeho.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbzylin.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xncxnovh.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkrhold.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcjujvz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkouiwi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkogvnyk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uguugjrz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pfilnmhy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dffivrrh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csbukdag.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2requqjan.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaelbxli.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xovjxyhr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoesgqf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uviavsxi.html


<!-- 参考信息 -->