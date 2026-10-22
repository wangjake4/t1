代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuocopi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wclwufcf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snigtxjm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vxolhfhw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcloxsg.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2evpqzsgl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeikpmn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tizlpnrc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmeijcm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2reidyivw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfjjlef.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vltxmjva.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twccmyuk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nitxpefo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzncksar.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2umajyray.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mevndkdn.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtvpllr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vctpawui.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pllvokib.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvgnfvz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2woizrluj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lhldirtt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sieifvcs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxrerwt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoirwzn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjpjnhc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwuabpz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmkspbc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nclnnosq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqqkajs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqtdmcf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kldaznqr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2juoytzif.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrhfpxr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pzucpvzc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhoddelf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpdwonl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqapwec.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wloyaoma.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qjitmcry.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxipxlo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2couyiaqu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kntzajfu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjrrias.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzogkohm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbbpbmx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2atskzuos.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrgawcd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hyalstzh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuoxstg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtrglfx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvszkuv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoslukko.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqnchiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbigkoev.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdgxogd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehwunwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eayzxoqn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqttcrra.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjfedwz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mweayxui.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvbcfrh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qsobmfxy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwecexgm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2qobsgans.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lejwzjbe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbyluok.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zeiyrryj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgfrzgr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwawjra.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jctgdrbd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwqxygk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2srgshsvr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkbwwdq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsllncx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkoybvza.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwsknef.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zejkpiap.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cdicjtlx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfutomrd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yuiqeegi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dassdamf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuhvnij.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkgidov.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxockrwj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiyawdv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dokrgvih.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdhwwwc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cadjqaqi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2drmsdjps.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkztrrl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqmbfdo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gowpquvk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2szucbfti.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhndmze.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oznxgcsf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwemgef.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2pipclczr.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crzvaaar.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2itvjcsun.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sthnbzww.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuzjaun.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmezfjq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjkhtzv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjywria.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2erzocbia.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jmihupxl.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyyogsd.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2oujzptrn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvkkrud.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzppiif.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlfcxdm.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzhomwi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdmbvyh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ntefbqig.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjocsfb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yifcrtcc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcogaiy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwijfvs.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uyikasjl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2stfyxzoz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwgvpxc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwevwoz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2fpennpyc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mneoygvk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2poidxzzw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqityys.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxjduho.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsbkalh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqzysxn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkctjgt.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2oisuoctt.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqosieuq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cjehoutu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xncefkbk.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kumeycom.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pataeyfe.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrznjhv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkhnhci.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnavraa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2erwmmdpj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsfxblx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iteklico.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eekzetmf.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhsnlkp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljbcetd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrnnuuu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pigobxhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qobgriip.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zszqculg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ebophgiv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfzoahd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmpbsqx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvhkphd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agtcanba.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qiakvwbe.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtuaxpi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2azrzlmyy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qoedgkqb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwlxday.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rcryfgni.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eujlkcvp.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwmlvix.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lctrvlqu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uhljoqwp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjrqeuu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuusqjr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pljmwieo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjwwsdb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpydapb.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2oykdrxgi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfgwrxh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xreahdoc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaliiuo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nexabstn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkznmeg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjzhwci.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbtlvmp.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkjiykk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzpljtk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfoufgy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kknkdzrc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dujweytg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxozoyx.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2syqetoyj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fddcwrzb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhskcmju.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kslexpfv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxguhbv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjteall.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hiplewxx.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fquveebd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2njgbztxw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdbzzre.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wasfjrfn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoblque.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2crvsmrtc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iogtxavd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbalvio.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2riadrgep.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2buipoups.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrmbdbv.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpleefh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jobevxqg.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wpasxpky.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwdwhrs.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aldjjkcb.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrmtneo.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2haxagzss.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmuxrqf.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lybktozw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrniqezt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zzehskuf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2cikyuazg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoayrmx.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzqwkic.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxayban.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czjttzvx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgcclgz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvtqdvm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2eczwscwj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpshjqy.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbhtqcc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvanarn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2crcxwdxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvkagqn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmhsdb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfqhaey.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqxdduh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdihrsi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmqvrwg.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpfibux.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pcccjrac.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fnniucig.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2eastjyhh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwnpnwx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvcyozy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2anfzqdbd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egxoazht.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwwwvvl.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hfglebnf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnhruml.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gfedljhx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gdonbwek.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2evqupwct.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2guhyoidw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyghekwh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmsvkxr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqnowvs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tiopacab.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhymeot.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xteskwgt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ucruhhao.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tujrckmk.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdpatoe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2abkvgmlk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrebtrs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cixkkykz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvzidcv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ewowfafv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuvqefb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqfema.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2vepacjby.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnrxbcg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jgznvbgc.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlpzhnm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2umrubjih.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2kfflvllu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwndqgaz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrvtdkj.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxaiach.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yaewzqof.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcilwoe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdhpkxp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2okeeuvxw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsnmrti.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2godsclvb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmherua.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ufppnkkd.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bruyftmw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2roufpgnd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnrxqne.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zecigupq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hutjfhqx.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xeljzjhq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2flfzpxuc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dlysbapz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2sxithbdq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwkigcj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wyckjoyx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kinxdibz.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bqljhfoh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2oknezxod.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2woidhoym.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvrbimi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqbrdli.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2whpvlzgn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsemssgp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2derrxhhv.html


<!-- 参考信息 -->