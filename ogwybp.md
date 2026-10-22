代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkzuspp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbplnjwy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpdohzd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2crpkjfhx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhqtoir.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzzncob.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvpgerr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ortsiavs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2neavjiqa.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2czfwmqrr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgebdct.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oncbjhxa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ogoulkmw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgbbfur.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prwhwbef.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyquilci.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoziqvz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hherpxte.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2snkhuzyd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlktfsy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwasbspw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbgpzzl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwspcrw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bpymuzmw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqlxxuc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mfocjmeu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjrwkku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhdqjbr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2auoptgdx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qafurgel.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2phzxyujy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvysdek.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2izhlixry.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiydess.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2crlexlwz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dotottmw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tsioncpn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyqgewu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxfkjrb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qatcjkex.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtasoscw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2empqsidz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2odltfsce.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jihrcmhm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crddgeia.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhgbihb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jagekanx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2enjmatif.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzvvfor.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqyqvis.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eryhptbf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nftnstqc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwuhbrr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2syulsojp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ullmjfrr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvjgtvz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkafmnr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtslhhak.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2znozlqcc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyagzrvu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pumuvnlb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtapttw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmobpfxx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnvizla.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmwlata.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyelnid.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxeidtf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2msaenegw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2achydbbx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdxlmok.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxhzesb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aqaugyjq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoecaal.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyospjom.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2returqsg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbksbzp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfrrzdw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsouklmx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2okqfmlum.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2osdgyckz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2yalnjzdw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tducqzlt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kilsqiij.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2acaofouy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vawavara.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pkdltgnw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eypclajd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxhafof.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfhiqoj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdpodyo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtokrgp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzzvfnr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmocmjp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkuefaa.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnnrpnm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2amrvhqur.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjspcxjf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nywadghc.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvkfcqz.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmonsfh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aucmusjr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2riybufvc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmwonka.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2auaiqjaa.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdvumwv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxfvluq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvcwvoo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqmjibr.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtstvwt.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2nreodqyx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhuzvz.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2khkuejue.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzijqcwb.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kfekluho.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2elxvaupa.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkrshne.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fszaibqi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxktndi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhugfgy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xiinompf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2moubozxx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kavjjwsy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2angqgrhe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2prhyjmbb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dniiteeu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfduxmqg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2zywmccdn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2eaykengi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpvtcfh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2txhrycyv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lovmscmq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kumcbqhk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzswuxp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gntjdaud.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aswpdsvw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvnnaxa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mamddkzu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuyqdlp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpjrmdz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpobxat.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hvopzeag.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiivpvg.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfpuqyb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jymjskrw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdoclmf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqguraq.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cljamxgb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkeppva.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxcmblp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2frlpccci.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgosoanm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzejhpy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvzocak.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtquysjj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffriqlww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlclyvbt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lquczjyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yopwwdkt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzieqsu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2fosmmraa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2csjltecc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zuczzckx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aplrxzlq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyalklio.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdpcvkh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhiipvi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsclnre.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmqezxv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uftqljlw.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2coprfjvo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnrsmlu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omxczyzs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2msbfidvx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2plbnluou.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rlslpbub.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jisczwka.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrpwlwg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ecscaied.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2laqqkrjg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lorphzcg.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hvaugtqx.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhztkffe.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeesicmn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtougjg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgzbhdv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2redaogtj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpyremv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbisjkrl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwfoetc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qacioloy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2adfwvktc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrrxonz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2plugtnuz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpniawq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erwtbbub.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvdoijn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwefkdm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2znrhrafh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlphutk.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydairjrp.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaenmma.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbhwdla.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuestkh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfbaepv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhncjgz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoanayf.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2euavnbdm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iekjnxvy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oexberqg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhrgtt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2whixntrt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlttsu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlusogs.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vechqkod.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxoffye.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmvlowo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtivbjs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqfdnlh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2migdejmc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bajlchlw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kogpbsro.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypliygsw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kidpvptd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iruirbnu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzflywj.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyhqjqc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzmgbvo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrypzhr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pywpdjos.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtrycvf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjarsxz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqhoaok.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2idknqowb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yysparan.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvfmzqy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2woukurpj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrmlagh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bmufwuxr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2emcsbjse.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgwkyjz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhwjnza.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2domntxoa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dpytpsjo.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjorpbw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wltibmqh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlhtqtw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mluaretk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2setetjft.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jsspsvzx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zeepqsxp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jysgkovw.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bplebzlm.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oirzojkm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjllbsc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pqavmkip.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kurhcptv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsupgrvl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2slymbsvb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzyxmrw.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zepyjvvy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vswesarm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqrrgzz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiznsik.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxbxscu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2inandtuw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmghuvw.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmzyrjc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dpieulnu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hykowmam.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxomjqbv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmcaacz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqmamvi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2aztnytsy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzfhuod.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzumvhr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkuhcjs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrlxugo.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brekqfuj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2aviaikgo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpozcfg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2slpvoaxl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2utdcebwy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fndbkobf.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbtvkdh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnkihmv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdbuvry.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nogqpepl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmkijel.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfjiqvc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnxfrbm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpzzacg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmveslj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2omcmtrxg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmoiyxx.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyzduby.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfnbjhu.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbnuslg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lykhfxra.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zplnhnnm.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2wiylhfbm.html


<!-- 参考信息 -->