代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2iimwussz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyufyigi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2shovyopl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pvctacfh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavosovf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aznyrvol.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2loqqhfnt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvtvhnz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eftanhcm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bgatypsf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grkpjemp.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpxkhmv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbphkgq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iozjsiga.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxwxkwu.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qysckeqs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceamunbl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvcsmve.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrmvidg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtadjbl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwyrbzr.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hypgabdn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciootsqt.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpntnnp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2urazwwre.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fefizxho.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uugxenvq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgwfiju.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiivmlr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2edkttywn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfxdgkz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzkgonu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrsamei.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqppfem.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tsczbkrv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2esairjpo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgyeslu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2llrkkoty.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bijfjsfv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdysole.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mglnuspn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqtzhyg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2acclpaqa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2deruxvry.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftccvzsy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxvggcv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2albrfwxz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvzkako.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcypebo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vncswweg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqcxrpk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjgeqgq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaemkkq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2riknjnat.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ditxergh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2enyahmad.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2udoafcek.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyoccvp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hryztbcy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpvlnlw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cxflbily.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2czanaxve.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnehhmy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdvlymg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbjjjg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljujcmuc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwahxuk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2onyfhemu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lulerzcs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2aandcmyy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mixbeiex.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxskaoy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cysgkexg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnalmoz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlmkdio.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmlrcsa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjeyuld.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwamklq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkooeod.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcnyheh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlknjof.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbidgkgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2obpknjet.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xczevxjs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlgifwp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2svtsueue.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubzyspex.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxavijp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybycjju.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfbmkpz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uptjyvpp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxnmxwo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwmmwno.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdddtvl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gsocwjfn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlfgrnu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgpmqby.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qdslhpwb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlywtcw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyozpah.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zelxbcnr.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2adhdcvye.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2epmunctl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmudjuia.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqrqyxx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbmimwa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hghlupmd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqoqmez.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkdlybl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgixbfz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2pajfdfod.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqfyhqd.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqnezil.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qiopygso.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtpadne.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ttarvwau.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2btairxss.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2wunvuuct.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwoztsn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhbnlam.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jywryzgh.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2irydvoqg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnwqotd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwhnzw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmkcqcz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tberahza.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2amillvnb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mkclnhne.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbvgwjq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtpnlyi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpmvnui.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxjkzfr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qfupwisv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfizhzp.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxaarxxt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhhppau.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkgthxe.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dumtmalp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kunvzwgd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnjzucg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcuoezw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2shhqqbgu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxbpqck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2flgkseva.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2enxlbyoq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2moblssep.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkxlrgt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wojrtiag.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmdcmoi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2rvclbwwq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwoytsuh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnozaas.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsqagoq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cibujlae.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlqdnbu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owexnpqm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwzbsyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvokxkf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmcotin.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyxijqm.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rijkcnxw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gigvjhxa.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pizzhmeh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkqcynz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhywbtf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bigjunda.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2naubfuev.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsbrqpt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqufhytr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqkgczo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjxvusj.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaojrtb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdnyqwx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmjvkio.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ihznlfmg.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaofdyv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrvkql.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrkadft.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmteotz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgdejln.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhwonzd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeqtnxv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bibzcrdm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvknjpad.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2imiqwpej.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhnqynf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2svgejxwq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeeibyv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsndonl.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ackkdymw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rzryjodw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2epugqgdq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nfipmuqa.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsogjbw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcqxbjf.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mujvsjmv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okteswjy.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnqiypn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjprpjy.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2khjbjcze.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmvovnq.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyafvgkp.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwsiqfh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbnhsxc.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdeokbs.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2obnrrxhi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyishkw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sphyokgp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jeypnjey.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2apgfthfx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqflycc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2runstuwk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knbfxvkr.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsrsdlb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2saauyhvx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmnkugv.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubspjpjp.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqqzuqe.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2avtuhgoj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okwcnzxr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzpapja.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2znhbiifb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lurcazcb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdebsea.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqgknnl.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2beomrxvn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emamayqb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ozclugyh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mswpfcmc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2akblxvdt.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2heqhvjtn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qstwhkjt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbxxurx.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxevfii.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2snjwttkf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azxumfeq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcusgkv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qweiyzys.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrvolis.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2evyrkffz.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpypxlu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxrahka.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mlachpoi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mdavvwoj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyqafkl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlwcskb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxalkor.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2exowjhhq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cbybemgf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xzikuzmm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bafhbhqh.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhyraza.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2toxfnhhd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwqnpbr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxhchnj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nmexhkpm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2srjdkqbi.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2czjozlrw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnqaobs.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prqoszgg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vemajelg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mecfslji.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbozmfy.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bnffwzxo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxtbeyp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqtsqtt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lgijyamz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbuavce.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfjtvlp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyjftfz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eleptbos.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoablsb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2morpwvit.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lllemhht.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnrotyz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fmguanmm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qumgkpxf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isahkrff.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbroktq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxjsqnz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkfoyej.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sesptvvf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyxixih.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2coqczosm.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmahdtq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtnzbea.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzowdxk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuayuqh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzqlhut.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpnrlki.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bakebwwp.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lecyetml.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyfnwve.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pswwsldr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2klifokom.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2csguzuns.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqurpwy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaikoxv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atvwyzvj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmtbxti.html


<!-- 参考信息 -->