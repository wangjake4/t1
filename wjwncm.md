代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gslafdba.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hclcwufi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2yulgbtba.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qpszatez.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfldzbym.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yjedqwzo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiztbdq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lcttnvxt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2sekwlhrp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eurhybhl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjugfyp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wovozvgr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2spempxyv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxccqnk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnqrpdt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2niihlrjb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokwjaix.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrnyxge.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkzxvov.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2emvuviig.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vabvexso.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hgejannn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkpmxou.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2axxhbxgi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2orzjsmds.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhldcsf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqvhszj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxqjyww.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2izvlfnaw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2limmssnh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfaqofo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2alcpqkxo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgatgln.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsypgedm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyzcmrn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkpfnge.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlucowk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vukrjmmm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhnkowj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwihnpz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilefrhgm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2psruaumc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2drhhpbbn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2haotjtgt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvlwslr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oglgyrbv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtbercz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2onjbujjf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmwukmn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgixcplc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbgrbiu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2utausvpm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhryegli.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoahwfi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxosoqm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2drieokle.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qdywgyde.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfzgnkl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aamikivp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhdonas.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdddzsr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxqwrtt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzfhayv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjidgtb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpvdzmt.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxyenam.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuopfoz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uuenemyq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvgptir.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mooactcy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzihqtvb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2diapfejt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2txivdmft.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyexkxiu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzbfdpj.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2msbqtutt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqicunhk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpgigeo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdfyirv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkvtspo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anfhidkh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sndfumci.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2abzjvplr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnbfkdq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxglomee.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lywxxsdl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kbukqgxt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2clbjjtza.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wyshnsvr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2utcrjori.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdnkozr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvhltdr.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbbnzce.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xibzyksx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vimpwfpc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2adaxgfsb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrzxdco.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocphqjkf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrznxyz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2docicpuq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2svgzknlx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgruwrp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2plazcwum.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtxkmen.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuzyhls.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvlyhlr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2kridzoky.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdkdshm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvopjysf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wayjcekw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pisbbjfx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mudyobie.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzocsnry.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcaffmg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdbfzjw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nauecvck.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzcgysv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnjpzkk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zokinzqq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgtuajv.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkshcfg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2esbiebad.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwdmcp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmgaol.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzevrna.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2rzetroyq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbivuzr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mftfeqjc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2udxabror.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eulfxsnr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmccfiya.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcgpnrw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2einnpubz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsreqbf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jykscgcp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkdgdnj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2qrljsfyu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exviripd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dcskjplx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2paheyvfk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgtjcni.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqgxyfz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvbbucd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbolvoh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwwhenu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hlasoxqr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtvemmr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yodilokm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mnejuqcu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2fikgcvac.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqbeixz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkrlinb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vshdzhro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svgqaswt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yqplhbvh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlwbmbp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2phrwpqsw.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqhacvj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwketaw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jutoepjk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jaifstcu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdarbtn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnwqrtf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvzsozo.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfthbiyz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qppdxujn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcuslwr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuxmymz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlkylgh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtxjprs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpjwrey.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ropvhgom.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jdibifeq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2poqzxyjm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbiuxsq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hwphacto.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vapgncvg.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoyentp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaxfyeu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qytefglo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ebppnhci.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmronua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuyshhf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkazchb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrueti.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2aophvmde.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjxjmyf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kscvrwod.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwgagip.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaypxna.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzbwycb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkdouwc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkbsrzz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2jhshwoii.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wesxwtso.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbnvvjj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqutsyzt.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoogcsw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2arvpqeqr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hujqohfr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrehvpcx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2efklupzk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ottnqrin.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeyxxct.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbfqvyu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikueujvx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gquwdtbl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jainockm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2raxxlylg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkvjxnb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mopdqgpk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzdhzcb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnllmwh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfktrdb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2maadcnsh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svndcfwf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fywfrgxh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfipdpp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gaytotsm.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcccypd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wncchnkg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2thknhiwa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pahrpenw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2umuizxim.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2onealflh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cscszizk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2efzpamzg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2trywhszq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmokxmz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsiibiy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2omqobbfa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaphsbz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuuvnmh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pguvgopz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2skkkbvul.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ladlvikw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfdrkkg.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2idjgtbgv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2obxfpnyr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wevvdtdh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrsfksh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxabfkv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2migshxeh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ccheiipz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iejydrix.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jephmfyc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2suxdwjpi.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nsamdmfo.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2oyomcbga.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwcnbbr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2xagjydxx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjnzlaj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnbdlve.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uucijtwz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxljesvq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2slwmhvse.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqxwkhv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2becattxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxpwxnq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2omqzdimy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lykrcpxo.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhjvdhh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kboahohd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dgefvrdz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrryknm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fytjrbxt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2apokflal.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2semablxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbrifwk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lurcizrq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kfegmxwr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxpnqys.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gbftefiv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oevrpwbn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpznzql.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cydkvgvv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2odoytozt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjfdjll.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsbwrqw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsljsly.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbilotc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sszheahb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqvjbyc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrqofqy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2iemudqlu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsbawlr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2egeezlco.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gokfgpes.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2qazfrodo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvjjrwu.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2whggnskg.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzrtqhi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nosadwsu.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jiucpfgj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fqksiwfz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyuvncm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xifzwglm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2deoqdwlq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ityslspn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlwjaab.html


<!-- 参考信息 -->