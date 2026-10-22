代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qebijspd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeecsjl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdtuarw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vuampapp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dhysxpyx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvinzsl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2orahguuv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bawkiodw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vivhdxrv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2khgzhxtc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hceoylpa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2enodceki.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzxzwaw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcagnajt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxqoauv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnrvqmu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlzkvqj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsyxevs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2budnwlqg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efgmczds.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjzccgh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlggmua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eozuymot.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvzotfy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzfsgln.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvrhnnp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jccnydkj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhdymha.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2srqrypov.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwroklll.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skhvdpfy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wycjcmgk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eneckokl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2psvprivr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzcnvgm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoustbws.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vohsubai.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2noevsezj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqkhapn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeewyya.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfgibfj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wuollgqg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvresnx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lumhgnzh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmxkesj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2czmhwyex.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltrthh.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2aylzwwhe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2elnzalfj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnkgxfs.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbgdcao.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ectxgpej.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyklbpk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtblvzn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufoyime.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2inxrohrc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wavyurgj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbiizwo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2unjigpps.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pfodoqtv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhvgcvi.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2engdiizq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrroask.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqbtpde.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bivnirln.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2enpchxpv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2txgjrflx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2stnbulig.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmhubuo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqcxzty.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2chxhmqxt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ionqdohb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaostyf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdirwnii.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjtxmbh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwecmyqp.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxbvohl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2adlwdbis.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrnmrgk.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvjjxuj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeggzjov.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2guwmanmo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxwmiyb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyqbbdc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flkeohnj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkfjkrd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpwlhsi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiqhwjm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axehmjdo.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnshkue.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yteidkca.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjfdebh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuigdunu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoiuwqr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fulpavrs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkkqnlw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tddminfs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2mahdipjo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtvlvnk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2swzikwfx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2llysuama.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2whdmeldd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tixmtwnj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlxcony.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtgdozq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adqlbgmw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yiusfyrt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drwssqgi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zglmpntc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqegdyo.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzbnsdm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoxohhi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tadmkflu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrjhtmk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2npbvptjh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2odevbugn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqyfmvw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2imkmgkpf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kygygaxe.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wopkndgu.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuhqnlm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lboyplcz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyevobxh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqlohiq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jiiiqjrg.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2neqwsdws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2spcvoxsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwotgtd.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2puauuaoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwnlkoo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fhahxtfs.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxlysmf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fvotvepq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2omciitlz.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmctruf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vszydjax.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ohffcxyr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2auggqrqy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2govoohnn.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oygqyuvh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzlgioo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ortbujge.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orelmbqn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbvhjwx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkntyka.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqqfemk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aweympbe.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wewlrumc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dgujcput.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvpkxzc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tksqlcsd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfwotde.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2fizzwson.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewybourn.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nihlxaqf.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwrphtu.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tjugyuya.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqddmscm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2novlujjm.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhdvmpc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiyztlj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2utszfflz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrfidqc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdjxvgu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udxikomq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtptarj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ccijzjtd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2kywjhrnd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2odshcsle.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2irxhllki.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwueieu.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzulfflr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfmepte.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2liljaisx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqozolb.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aerwjpgr.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njqcqfao.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzheahdl.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzjebbm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxfvhex.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czdrmovm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2whjggrws.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2viocoxbf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cipupgea.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnuvmju.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgaqlev.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2frotjppy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzwqydl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyxcnzv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqnlgip.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2grwapzdg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuuihoo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dmigglnp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxxrpvf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2itvyfuvg.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfhqygn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raacsgdy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmasdkv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqqqulk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpazpou.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgcbphj.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkvqqoh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlaryqo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtqyhcg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wftcriut.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2latghmou.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vfofvggf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhhwwox.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqbugmy.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsbhigz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fytbmdaw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2optorydx.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxxjzbr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgxzibz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2brqbjtbi.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lafcskfc.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxmgsuu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2doatrjqi.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqceyrov.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlqzcls.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwwvsx.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2clhvdigf.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjbubic.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsdhpfk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgjlmig.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pgguxakf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfeiplg.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyhlcmu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsamkwo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfjipnk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldthzjde.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzrvsix.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bzicpqkn.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsomijt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvpxzvt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxuhezd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnmzimp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2irxlsmjo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2elaqmcgc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhnaycq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbcasju.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urarwhap.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsmvukm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wneuamtg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzwsuog.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cufiorvv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrcahng.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsixqdq.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwgrink.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sdznhfgi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcovrwk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rysojkeh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jhexsyhf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2onstjuwh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpljhnw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2owybdpjz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bldznvwj.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtstcagk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2matjvwhu.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcllrun.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvjnosx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2edvprqkd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaorbip.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2womrovjf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgdvzey.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvsagkn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoyfvhf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnmubja.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzrijxe.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xusgyqhl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqubydpq.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2frdtqxxm.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2npuatjqb.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2galmpqhj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2eigunncj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqijjof.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdenrnwd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dbulrrtg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxysfnf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgyomid.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2beonwwqx.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2jruyrsun.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvsuvgp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzursog.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrpoxuv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjruebtu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yyprmesf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2otvsioby.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcfdoez.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2adrofojz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqafuakn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ijicfnns.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pajbnliq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2atnhicgu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iohqdalk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxmtkra.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2grvvhasp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzcujsn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwetixa.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyjidjr.html


<!-- 参考信息 -->