代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrddqrkl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2foaparhz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhulnwwi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bksxmnfu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfugvuiy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgqdzpt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2clilbkwu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdtokrp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2scubrofy.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2boolrxpo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfwunzw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2alcimjkt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pczwjkzl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcvxvfb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uelqzhgd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bplcwwci.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgpcfmi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qytjmfld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjspcjiz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhoxioh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcxhmle.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeoxduh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2juorbxoi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xacsrukt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsvadfv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jryfqqub.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dgahqxlt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqgtxpp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdfomes.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2loknyout.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmaduei.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oylvxkkk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sikmglhb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2awtngwjb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfvtyfs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmtdgzf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvfhihi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2amiouuqp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtpipto.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuiuniq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2apvtairt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2viubnhwo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tucwaoas.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrrqjwm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqzzahs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hphxmpdv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciufgczi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwzsrkl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xommbxyb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nampzmos.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svwjksgk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmblxafd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxvutzp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hakcnxvw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsvtdaq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2urwlazzo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2alkcxzlt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfvqwpd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nshdusjt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhnwryz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpxbfdd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwrpupj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2knfzinmk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqebidf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iazcuple.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2igbttzyo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rlygcksl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwaycli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqslgkbt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzpriro.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hydenibb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mllpydve.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjjghed.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcuhrkg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdxbbsu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywimuowl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zutbczfv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqpbvnm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzikqmnt.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoedkel.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atqwcduv.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uphiatoq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtehylk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vedymdlo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uohzbohv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dylyeayj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ecigirex.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlglinr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzvrpes.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwjklzo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qpphiuod.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjsdowk.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqhvnpn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaxrqxr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2guudgype.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pelwditw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2memrxgdv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsalhwuh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qfalkwjf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2doryifkc.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oplpiaum.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tocpgjuk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zukwqesa.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvrlazi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqseaeb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mlheozpl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvhqiai.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgvukpx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdpinva.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2flvafnhh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2efqozvhl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxgotwd.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfrqpek.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeodrde.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvvtjyi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2baitwptg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2cnullhgz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2schesufr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpidwkg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2sduryocb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2chbhibxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgngoosl.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxpzppz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2xluhcwss.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fycyfapj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfdelet.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbjnmpt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2afqzofrb.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tytpddcv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhakwij.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzxzsfv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmsrejx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqfoxxp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbspgxw.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaulaui.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhfcceh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yduqhgyc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceegsusn.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqwedsx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeeciil.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ralfkkzz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdyijr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uclzwfgw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wergvmch.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbnkwlr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwulnrl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybexqufk.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzioqwr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcgrlbm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkxtdgb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcngddvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbabedr.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2veqcwsde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfhrlkw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2bolxknwq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmkwhey.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ceahezvv.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zacagwsc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdagaxde.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2alffkmxg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuacaui.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iyknnjtq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuxlqix.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ztojmmrl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2atvncxkk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2diojzdpa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkdooiz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vscuiqrb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmwkuwj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oiauxajq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2slrhhexb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oorsdtpy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfxgeyc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnfhmus.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlbbysy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ewitzjev.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2xppgzwzj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqlwauc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxtgiwx.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvaalhq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2egdvqqch.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfpaigp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wiiixmkn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xbccpnso.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbtuctz.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhwtsvg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gofgurqe.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaqokpg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdagnsmm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzvvyts.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vazvlezp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2retxtqdz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdjgkzd.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yvaweqdi.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhpuuaf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjpflgd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzsduvu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgapapeq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbbyimq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlqwlfm.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clgksdkr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkqksde.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uoomnuhy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqscnusp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nolwnpmx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnmsity.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xasbcgyy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfeulfc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoiqzob.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqpyens.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgdadnc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaegyon.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwuezbx.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jexxqahu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aimoghrb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnarwal.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqzrsxp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xrejsbrb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2legwblfv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzbigpx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiskssad.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbnapvi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzdrohi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyiryzz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeovpdd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sziaddup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbvyfrz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcbeaqe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhrjqkr.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2soghhnpz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpsmsfj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bidbmqof.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzipmkkx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2fvozrhgr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcmsmou.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmhhiza.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvrpkuv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgiayoz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqracya.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bvttrcip.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxnsoxw.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uynduibs.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpwtwtt.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmkijzx.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pqryeiox.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bskgdbaw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2unrsmqwt.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmvaocm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2liccvmmp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvxmklk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpzhkcg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2leticusy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqrilki.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2elogzavp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cyerpsvb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsherknl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lropfxoz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmcivcn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxorpkf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcouhtp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjnsquc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2aikyimhn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcirajd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dweijcdb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdinydk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hltdkkqp.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmmsehc.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxzwrcy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2crjufrdh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbhzpgz.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrwqgeg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvdymjw.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xjecznct.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rakhtewi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmdqpub.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wajhgjmy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ispawzfe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2unnysgkz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2voklpbts.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mndflacr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ctglnjqm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoezlnz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjmsmba.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iqclmndk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqgsmnz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zavyzxyc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjorldrr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzwnyrv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnjfqxu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrgaoed.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvmtejs.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqncect.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2siyrywla.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrltmqy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anljcthf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhnvqop.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2fmurjpwi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyynjqy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjrumqe.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbelvxa.html


<!-- 参考信息 -->