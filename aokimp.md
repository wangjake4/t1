代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdppowh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yejassnu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjcsmng.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2iswqbyiw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcbjiqw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2icpuxssl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoakzse.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2spszhjzh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zptbabhi.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmyqkuz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmmrakk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdjuibm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbtsknn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqlrvpg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiwqolx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhesehb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tizhlcgy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlyesao.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeceghi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2viikumgu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zevjpuce.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqxyuhs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sylewbud.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtswdar.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtagdxm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yorzshnc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2apndwpsm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoajeak.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwwzbba.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvhsshj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjpqlge.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxglemy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgzdcll.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjbqicc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lisjavqv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbffuxwm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjimown.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmewcn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzgmtvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2owzacjhf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2svrzoydt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzclemo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nggbwlvv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnabqau.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlifrpl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhodddq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzypcei.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfnrrrn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngypxdqz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zbajvgoj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqyhhvx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jhexjdqu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kwslqywx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2axjiplge.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjygsdwo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxydxajo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvdixeh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhmmhez.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxtnggz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhwmcu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajffpguq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwmdbpc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyxquqd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfcchiv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwexkaf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vcunnulc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2bauhmriv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvvworn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ympzqlkg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2foeskcug.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtwnenv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhwnpam.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuwvtrj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rryyemjm.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zyykconx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2oplvtnuu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlrmgoq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2euqjygrc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqofqzx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcringke.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcezyho.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2baebpnkk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2okpkjwkj.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmyhcxp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iklpazyd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhkbyyr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkffizi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcegzej.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozjrtnk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfxbwxu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnplstc.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2awmfubuu.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wglfglvn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqkzchq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2abeqtxjp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bosawwcd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfctnbdp.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cgritxvz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgkmkgw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnpvsxw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yipqaxvc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcxhhik.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaygngv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mmugrtkb.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrqucap.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvjgino.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2asafgojq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzvrpvs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpkyfrk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjstmrs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgfirnt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiabzcw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfzcjfg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lunmtxez.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxphyhi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqdzmhf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2affkfeew.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatriiov.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnraxgf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2auxthzeu.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ogezynjz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zfidgwux.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hibrxhzy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2randmqcj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjywqtx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojexwuye.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anjdjymu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qsminycr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdziftw.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrmhgpb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2adfxywyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmnmqiu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2txugeheu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaauoac.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxhfemd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmitndg.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvpgjym.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfbpoyf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fybiwovy.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yroboasw.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyaznre.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyemwpnf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsujbozp.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hovpomqb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzjifhg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2edoadhbj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhjelvt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqggxj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pczouaeh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iidyqclv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2atenurxy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmabmix.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2koppnozq.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgkpzhk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2szafxjde.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfwuojc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtwhpkq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcujlynq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtdrqki.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2biwazgil.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzflgsz.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsmqmhy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrtxvli.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2plugcztd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2erdkcxhg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2grihberx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oraqbghp.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpjbdvr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nplapmmi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2haelkapk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uphtxoas.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bovwfwhl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eodyafar.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxavsojo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlwgzym.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbyopin.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwnoxbp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdsoaln.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdddxlid.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2opmhgqpe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvumin.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bmurbiyt.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlopuel.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mspazaqg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwrgdab.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuybprt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2llksampm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpxrgau.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpealstl.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iexvtadq.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmeuvkl.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2brierhtn.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvsqrui.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vevcqjde.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2pbumgnti.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjllfsg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzndzze.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2beslyrux.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2klqdpusw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtovnuy.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iabpdamb.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iughzabm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkmmcrq.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qsurunhd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyepquz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbsvmko.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rphsnfui.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ohruqbst.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2phycblmu.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qffvecxg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhfheyr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmfepxj.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwukasld.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2omkxtrve.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yyinmuxo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xreoabeo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrsckfp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osnbglxo.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2fnenbecj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlyotma.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eogzqdjg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgyaimj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggudydqv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uweexrkw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnainch.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rqksqwxb.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2nixhxocv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwzkzpx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpnvtqc.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qzexomnu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2luadrfxp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxybigu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fupnoziu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sblbbzjg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zhspaqlb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyuwjih.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2asrqmnar.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zeszberl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvksbxd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmlxhri.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2kidnfqhs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuryeetl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcanbtgl.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pidmpyao.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zykucnhf.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmdvkdd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdxqswa.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2qolziwld.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrvhjlr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtqjsxd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2thjwxibt.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hkemyqou.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2iotdmvvp.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azcqlqzm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tljsbext.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pytlqbnu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2bttfudja.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkyqzir.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhokmeq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpftlzq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bcawpvyx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjloxog.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vodomrza.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqirfqf.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtfyfrw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuqtipk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwoutkmm.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvclkue.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfmecci.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwpifot.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2molvnaml.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2knkbtsez.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsfuuql.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2djwqpxyh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uahaniub.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvrfanp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ycywhwvl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmajrpt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgudgwb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpiubsz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmtcahq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2axumxdzr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfbhrwd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzomaua.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrtsgmy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrsiywy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kttydepj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjsrupt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2voyzxqyo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vumbijsn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iynpnsvs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdyksia.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhfvxcn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcpkuah.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwwismn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2aphwqhxm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmprjiq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfooqda.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nggcwptg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flpzotql.html


<!-- 参考信息 -->