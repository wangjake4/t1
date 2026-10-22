代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzgmwdl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gyukiqep.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2btykbzyi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2birjeisu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2krfatuss.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhnykxh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpyyzpn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzdbbfc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcrcbon.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhmbipr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxmlfgk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpubzpc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlurblt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dywseqjf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jobezteg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2swepmmvn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2evealbvp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qeciecmr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkjaquc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzyzjzp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfpzcki.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vscuusph.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqknnrl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsnfohu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2atrcaris.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gmegoycg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsxzeyb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2myqvstet.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfzbtre.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmaswei.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbsbjfp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2sofpionm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nqevjxff.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xshekcwt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2inutmqxg.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2shuincal.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pdopldjm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eovbaqja.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpfxprx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiopcrl.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lpboogpx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2skcvwedt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbzhupy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdogmhi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyaetdg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crboybfc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2emvahkyf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsuovcu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbgaqqp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2akdjmyhj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2orwduujl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oflbanmo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjgsiwd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbbhrqg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewejkrzi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjolapx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jptotqtr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjxpieb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpyqufs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmowdrbm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbnpcrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fozxgkay.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2isjgtiir.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2daspswbl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kpumbmaq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2augvavqa.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slkxichz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpphhjkt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhbcpbi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebowaaqb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwvdkan.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpionvu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2srgowyac.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pomxypzh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cbquuhtd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwrlntq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmshfupa.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hecbarcx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2txasbhtx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dncnfbhm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnisxyb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmykmspt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvlasfn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2angcycas.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyuhdsa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zocdrjkp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qegofpkk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nnujqbvf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fewmvnmi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwoydnr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2urtcuvzb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwmaubb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbqvqwe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oucloixf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nuglhdzp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhplqtc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzjwxyg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlykeed.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2asnskjam.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qejwispx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrysinvy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2fugowkih.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2evtftyjo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdypzvwn.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jqaywsvx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjlfkdv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsojqng.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignuhapz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jykhwdeq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqwzdnk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfefnht.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvmjpuo.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wegipxac.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjzqweh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2slfxfcfc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2edacjpaq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agksfale.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxmszmr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cmerlevo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ozncgadx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqtbjnj.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhxfcuy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2juhrbrhc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkhmnyk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfvrlai.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgqysal.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkmpkdq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqcykkz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cvycbwwi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kogkbhey.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfgwfvf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ruryiefu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wwspythv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rdycoedg.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgivdfb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjpxuce.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzekgcf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efzdltqa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2attufwpz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwavkox.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2btpqpsxw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wesamcou.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cirvpeqj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcftsnp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbubuof.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgknrbxv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbuwlkf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2faakwkck.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bauiybbm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcszjjr.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgqrzsb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkppnri.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwokbtvn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2burdpxqd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xunyxegj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dngsnaoc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2djnszojs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dydlqhtj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbomkbua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jctvugus.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ttupsjyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpdrczm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2amdxbhft.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sisoybbp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyvozxp.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyfjmzf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhtduab.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwpvfnx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdfulzq.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2egrxlvuq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2clhrgaum.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvehfcvt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogusbsba.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkhgjyk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvtyygr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfuafwi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnzeggz.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aztijiiw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yseokgfs.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuchqzdh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ehijcbtu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqbstiv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2odoxutus.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhjjuvz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjfgqxg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjpxqet.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbjhxpj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2elpnhgnr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjuudue.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2thlndoav.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfehkbwc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvviwxu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgmgxwp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wswvcmet.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnatxbcw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kidxrrux.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkobcew.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxctbdfn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wldfglpd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwmgabj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2spwhffhb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2segizprc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zeedotox.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2luxyaqca.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhfqfah.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2mnocoife.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbgytri.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bttmqpeu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xblnsehb.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2arorcxag.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxzwjtk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzwgqhs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rznhuhap.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tazxwddi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnujrvdy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2qihzymoe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqopamba.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2stpctwvl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwfvzri.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hwveixly.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjfoluz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxzfdhy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cklxbhoh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axeivfvp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxpyfcv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyoxkne.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnfccdu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwbnlei.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maddqopy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyeidml.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvgpzmc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrmredt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbtfidr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2dituzakq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwmczrv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrdweeg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzalxxh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlwpyly.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2djkzfwqi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqajbnvw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjublbb.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jslrqeim.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqqnvgb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxjeege.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdbqfdx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvlncmz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lhargavn.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwpqgkn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2stqlfqwm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnreums.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmstleg.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbyhple.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2omdsvnjn.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaatrcm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkiumbd.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnfisjd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uaodivab.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrkgvsv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2opxjesfw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfpxnvq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqrbfsh.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2poshqsmh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbofalhl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvjopim.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bljozyef.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2usdytqts.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ergeaine.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yptgbmcp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvccxxh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxksutx.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mgahznut.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxyclqb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpjztrx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcmmsju.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yownpuic.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhlsxwr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gtziabrj.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaogpim.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnkmdnm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpjrpar.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcglfmj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sangtwdi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpvohdq.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtmbdhq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2slxwugai.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vithzjjx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kifxkgku.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2quzkfzrq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2urzzgoyh.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpjzfyt.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsxhsfy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzzzuhw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpjdmtl.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dunugcbr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozlthsg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajctlstp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkoijff.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfplrldl.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzbyuxi.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2agcbcxrr.html


<!-- 参考信息 -->