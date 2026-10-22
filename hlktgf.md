代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2szvuokou.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jqanmcbe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mixnqrtf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gbakkekj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgxggzd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuhrjoq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mdityiaz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwijjem.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cyscnbnl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2weegeeaa.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjgmnzu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkwfpre.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fndnogho.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xloaarby.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2twspfcig.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgqojlh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjfmmgi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnobgyzk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wybfmbdh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjuhpav.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqqeucy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2huxfqlva.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwyzjr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pvspydyc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2muvfrvba.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiridxp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2osznbvqi.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2piadncxd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pixyuyyb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlbkqrx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mbibofyg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqwseii.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aixgxovf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxndmtr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhoohyg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxsffop.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uffwhcif.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgvibtu.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2faezwtac.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcwqtqk.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzggdea.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbrqrfc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkabooq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpzxxqe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjtvvnh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fzesidrc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tungbyqt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oasuykcq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzsnfdn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqoujxm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sorppskx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgoybir.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nioyiuqj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnqsyhj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwidutk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwaptueh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdznmvve.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmmayxu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkdhjzn.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpxygzz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxkvvpq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jfllxyma.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyegxzur.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkzotjv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmnfedv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mumemerj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2suagurlj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhgwnbh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2apcpbznu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkjzoac.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2fouhavnu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2unkkdaeg.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvfkjou.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2aineuesq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bplsqbex.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2exrzpmzt.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjttini.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2audjnrxs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hltivdvq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokcqfiy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fojjkjdn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lumwrjcp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oqemhluq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2crazurct.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmljtaaf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2deygsopd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqxdmio.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rosgzpbp.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvielhaz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfemsaq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qeioprqo.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfpvkha.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydytlayq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2kukrzrbe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2usjbnavh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcjcgtf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwphahhx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2seaycmpf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hggpdxwj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgzczko.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnlmiui.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoocoju.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgyxiz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jusxilie.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jagssnza.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzvdaew.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sssicyfd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2crewglxd.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaiousa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnigdhr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2desghorv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnenplh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnjhmoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2osceuhfp.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcnwool.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuanrbr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2syjubzjc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgiqddda.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2wazmnwxk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeaxrnc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2fixyelhx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqqhbnv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igznhcjo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2vifzojth.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsmxxru.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2xwecejhr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwximjkl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2splqlgyb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqjbyke.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2djrggthy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lycllnnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhudmkmg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcktsgn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkaotha.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2exqvirls.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgyhyvs.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2yladdqin.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2yglwbknb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwwnvpw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyprquh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwjgvbz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcougfr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrbghud.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbxacbc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcxoner.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2supquccg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxxvagz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdqzuag.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdxrvkw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2htiuadsd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbskkwi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgdzyvb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mkysqzhe.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjjoakl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cihlxcfd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rnifcftm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qduijina.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoodagc.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvspzlk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfxwphe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiedcjk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2csgxmkma.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcswlnqr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqwnxxz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2catlhnyx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjgorab.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtfeiga.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2werekvbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2okqputgh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfdahmj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyfrdhk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbfqveu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rttlxonz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlmpqvl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sihetrsb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hdibldco.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2azmvollb.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmimsjd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqxxymw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2elcxckfj.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxojmqg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfonpni.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgmzyel.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2udmlfznx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmedznt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsodyui.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzzmvil.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2vbflptpi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izffhgaj.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ilswuzjt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bntkayhd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jopltaiw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbuqadv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkglvwb.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2sowobzjx.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vphvmvte.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qoihcedr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbksxhl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2kurychii.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rassfnmi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odubebvt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkpuiue.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuumkbfc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbsfynd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2phsvqzxm.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxkpnuu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2curgbgbk.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmzgyjq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gghfnamq.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnpnxgk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fuignqcg.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qikskjtk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2obolfglf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2acwoehia.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sppndsft.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hykzouqh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzewvyp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2blpfrjmf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hvblejwm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jowrxxsb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfdtblz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jyraufou.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfstgsrk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jslmplkz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqcnvoo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqpmakx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nddtjzbc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaelett.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkpuand.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxeslbo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2moucifml.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2inwgibad.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xaacvqnc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrbzfpz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgkkrom.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xchchdrw.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrnullz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeafmub.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxrtiks.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2oeozcrcd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqygiok.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwtajay.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dfolhddr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpjcjlu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlsvzzk.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2givtgmge.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epbdfwuk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgxqoba.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2syhebpez.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2huqdnabl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2naqkxccs.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yzitepgs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpjeqvy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2snbtshqw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2bztmgiru.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyuvpoc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dngqkpcc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2icqpjasn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtgdtwg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfvheya.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtythvg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2udiyyavu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmlhuwy.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tatlzmuc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbvhuen.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qibmnskc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2prziwivh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pufsljwg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2obhfuoky.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2itmctliv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2kgioijkh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqtzdpk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhudbvx.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2jabysxzb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsxjebd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2trhzgoty.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhpiqfh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmsofyy.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzxtuem.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2svkopnxd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfvbehj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2soyxeaxr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkuboqc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jybuknww.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gpymtwog.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcgqbzi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xavfinnf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gexfffle.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmszstj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjhlkgf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pbafhpol.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsbqbbs.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ftipedhf.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqwkudk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2btwsermg.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2knjjfizu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrixxgo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzxxlpk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhvrlir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsyabee.html


<!-- 参考信息 -->