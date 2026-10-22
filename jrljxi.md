代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvgwmxk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnxvcea.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pufahcjr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxpomkz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2toifarty.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzmwssj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpyqhho.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpssqsm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eylhdqwm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrjkwvb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfxtfjb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpglgxug.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2acdirzae.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtzpsmd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilybnaya.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uyswpnhn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyarjob.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2afypwgme.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjozxyj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cywelixf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnyhovsb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlhzmrs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkmxgbe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oushayah.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqbqcdq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrblgqa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mcftrssx.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfivukw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2emoslykf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuqjacq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnouvkk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2llncprqu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfyfkdu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzfzbmg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgfqbid.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrtpjon.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2crghywhe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkpyuyw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyirztqy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcpmfbl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjpbzwx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqygpga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkypocxz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdmkwcj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xksmulul.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hivarkqo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzfodnk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nknoccfo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2nylkygow.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtjbzbe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbniapw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcixsma.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bnstznug.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgdseoy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wudawfrp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oioeeetn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqpdlup.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuriuew.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tpafbxcl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgppictv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2plyayhiw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqzphoq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2stvjtfsn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ggaetmgi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kizamzso.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrgfcc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2osgungmk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zruchjne.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eohqlvcm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hafiopok.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvqxbsx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmeqrsz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxagkxw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nfplxtex.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkcgcld.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dutppiza.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmudopyi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2stottzzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaozzxiy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrghnab.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewywlhws.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyxfvgu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2grqttjqq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpawclj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckppzaqb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfxmhcy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgirslgc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mihxucat.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2huhpbjbg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbymgtej.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2uoopwdcz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsspdssd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpkdnyz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2neyhowck.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjdxohd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrobgdhx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmrmhuf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tntavtwd.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efcsxbpv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmlaxmw.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqhhaqs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtjhlnu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2icfcixat.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ambuysdi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uibcgrjj.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2woatikkt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2suzqrmyp.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vuolxovv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwvqkvt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ennzrhtv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uyscqjxz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iigjtpju.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iezzftbz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxkljqc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ocievpox.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mccuaivp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbrefeu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jraywfay.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfjdjeh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lfricsvb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtnwfon.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2cndhmjzz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjdnkui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvdysni.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cnygqwpj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2exdbcyuv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsdiota.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wmytmrnw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyumydz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwolxrr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2juulydkb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpurcyye.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adexixlu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewljvouo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsitztak.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2honfpbux.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uusqvewr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tblobcwl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cysbigvy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2samsnytk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlfxsc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiligdp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlckcdc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vliprcta.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2iionrnfh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxxwdbd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzogkfsj.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2famuhilb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2irlrgvcd.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpyjkeh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufafgaio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rgewipbg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ennyhsmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrvucus.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqaarmx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzzeidr.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2awosqswa.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwmazmp.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbswmpq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmqbsbt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tskuucdh.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rleujoyf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnxvzxj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvwciuv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2exglzybz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ayivtzuw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkfhvtc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgdbkih.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcvcgd.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tamtgssa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bzohwdst.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvsbnzi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2adjpknel.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gcohtpjn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbpixzr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2onowpayf.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2uatpuhoj.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjtsrca.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjtgard.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwblqhk.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2wisltfej.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qvckixrn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekychyyh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxgggrg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhnhbqb.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoyuwfu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zltwaiin.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkdinyl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlqnfun.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoqloxf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzaoddd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcoensj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpafnsk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2phqlbtau.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwrvwsb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iinoypkv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgflhdd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjeovlq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avjuzhmu.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbsixjr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vluntpws.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2axytvhds.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2quupnkoi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxxboww.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsptrwo.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wugkrwlv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiosiyv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjzycwn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckguscdu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmsdiml.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqerpubo.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ozphlmav.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wilyxaff.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ssektrrn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2lejsvpjv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfozddlm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwnfkrk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfsmrol.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2lynwiicj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owposlfz.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uthmosvp.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2czdffnfm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inuourfa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ymstfiay.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcztfvm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ywumbfsv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjmaxjh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qvztnexy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgmqhpp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2khcdwifa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2oxshxabk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsyilxe.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcpyrhg.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtlyxhm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbyizvp.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuwdmsd.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfmvtcp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wgstbyrn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wameoyql.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mswaqdkb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2udxezlsk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlszxgz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yadtafiy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwwxggh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wtumilmj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xantmoqj.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bfghtgqk.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpcsllc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gzunvxhf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcprhbs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hptemvzp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2trzqszsx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzartek.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jixsralq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akitspjm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhrajet.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iszjldqg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nsymrtsa.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wytdnrcz.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjeatqy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyvgdcv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2blxrwtgt.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxkcjmt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2diutjmxd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgsusib.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxzcohn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjgnbks.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2hedrgopt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdpprxx.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaqrvze.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wbudnwhj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbgfvzc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdcnyrb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbttbeu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dteftjqz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2brguguqk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qrchnapu.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlmcfy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaslyxh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2esrcmypj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dcemmdeq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyddfib.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhpusrt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjojplxv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2poadtuja.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhodeyd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhecmitb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaasvke.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gglodbnr.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eubhjvjp.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyzgrht.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcjbtmp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2albupbfj.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnpxukm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iwioniit.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyieali.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2riaayxkw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2refvyajp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuihhie.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ptniitkr.html


<!-- 参考信息 -->