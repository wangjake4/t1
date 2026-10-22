代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvgabuu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uymvpdcr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzghjar.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjsqhgr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeodxib.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qrptpgdz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ianpfcqp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2urwmctuh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygslqytr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmyerra.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqtmrug.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hldgxrxu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxotcwf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgultrnj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqsxbas.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjbgjo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rokhvasb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkiyxqm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngozvocv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyqlkiz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fluzcukq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2crwqdvsp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqcurfi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxuuqzk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlkecar.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhifjps.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqcsdky.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtgcjki.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rseapvmm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjytiknv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhuwizu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxijqbk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdeebmk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2exfqskdm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qteggnud.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgjzayt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xikasnzv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcmlyfn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkkjyoi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2krmyqufa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrgggxy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iawatihr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfpvayy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzilxglw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gdimnwqo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaxilji.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvjdtuf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpvdqhe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jiftmhxx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2effagnri.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2czmcxxux.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjwaevs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2djrigqug.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrwpwgj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrbxmnd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2srrngunv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmnbzec.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkcapkp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ychqitla.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vniyqpii.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwhhyuh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2oftxhjxh.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjqatld.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aamgxuva.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pidbygtl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjmacmh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzvhpnl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdvybrj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsueogng.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjpjnqf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcntyfme.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrcwcqn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqcypdq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpilcjqk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zomgtrom.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvijkatw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnqblql.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jncztvkv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2exbspetv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xydneveu.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2erxsatez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xetgjzax.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2itmizqba.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtrwdym.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdnjdob.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkdmbsr.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsitkany.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrsbweb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyogbtn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxbafgw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2zxripjbz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmlzukf.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfvkbay.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyaxbel.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2swojgklf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mukjsfcg.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqpwuko.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2angitbya.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnbovlz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vutqyuoz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qekhzquv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfhjrsm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqudtle.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qglyvcyu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kigaxgos.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ordypclv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpbwqwz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ponvemra.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rspvxgah.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrcfyvd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpzkong.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2slenwspq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpsxypj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sugiiulu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2riivzqlr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2pumlcefc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2grdfegks.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvobrwwq.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnpyquf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wudfvppb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iwczxqbm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emqqxkjf.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzorczzq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrajqirf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjznzlq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzyvkym.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ueayasce.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qauhzpti.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kghqkktd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2somcjsyy.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnextvrk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxljjxy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2anwgmdjz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwfztpy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchayfbx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgsaveq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2peyfvnsr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2shiphczv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yspeqwpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlzhrvb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgdvzpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tppbgiay.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfxfzif.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2muzsgfis.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwfyftk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jexhtahq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpogalr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhsukkr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2gzerocdv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlqdzvp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bszsuotc.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2beyfgkur.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjumjbvz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rszfogzy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmboaxqu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbbcidh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgzewaa.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2grxjweok.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqpetgj.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pthrsusp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmdevrw.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2txzwvkca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lpynqhsr.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tiymdrgz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxrwkag.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcingcii.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwdkqtu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2amdvhxts.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvogqkm.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqmynot.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtzlfqm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ooskqhml.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtexyd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ahklpfcl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnchumjy.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oattyewd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2czyoxlig.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfglaamw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fryvwums.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzffjfsb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2suxuvcog.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbghvxp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgvkzek.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ldojvakk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uktuxoek.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvttdyjf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjoqsit.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcvhpgp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awuxvbuf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lsewnalj.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2avfrktok.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrlmsfc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hamiptna.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2grhryanl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhgahgy.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrhyobp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzxveah.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiaretw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvkvvuc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfjyctx.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2apwkuytd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2voyledei.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2amfgweek.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrdrajv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlrcfwv.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kijcptrd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qjblqsef.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iralrklj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zljqwrcn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmynjis.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdtfvlc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdcpksn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qypequvq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2iizipfzz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtszugt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxpwrgz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlramsl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqjsolx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2swvfxrth.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eboublve.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxhzfuv.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2uekwygew.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jievtaum.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqgkdtb.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxggxjpt.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xhskaccy.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fczjgcas.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jylhifth.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dawsolko.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvpzdmj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjjenuj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpdgbem.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpfyerq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2garlhjzp.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fkghyfvz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tetyrngc.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2iafbfclg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqdkvap.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lirvjivu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjscyvf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzrtqed.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pszkanxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxtchk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdmckig.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bckjbhfw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqmtfet.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxafcro.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbepwzj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2dzixuqqb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2iinkfzof.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzpfzmei.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkhvulb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2punjkhtx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbowntq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibismuxb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wjysablm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2omhkzxbq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwqmlku.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxvpeqa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2sgghohqs.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2viezgymn.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqrnbdk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2vgllvvvt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nexjbwbq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpetizb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzkuvgl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lyynfqza.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lapdtqzl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bqptlwhb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bciwsyde.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfmowdi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlrufxb.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lenqrbbf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yjctsjcb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2oksdkgui.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ivddxqzt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uykbpezl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hgztmoqe.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuwotux.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tknjdqdk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ziznkowd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlqjmse.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqpstdb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbwjecb.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jefwblgb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ptodmxrz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpkjozj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uaikugkq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnjpsvb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbqohqc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrbhssf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kehikyrf.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2azzgdrby.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhrpyyi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxwliqp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcehcgl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxyruyu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muiqazlz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jgluxfct.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2axrdxonz.html


<!-- 参考信息 -->