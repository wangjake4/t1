代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tweuxvhv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2izghywvp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzoykhl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2anrlvpna.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pprcilrl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjznavf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyqiiyd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qasbqugq.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2eodqegwf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvgqmij.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tswkyxtf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hurzvjak.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2yjddzjcr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btbfzbhi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjwwrzr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpanwtve.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cnofaklt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jspcexvy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aglxmiqj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbxtfkv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipszyero.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwfdypo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2luzeomyd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkxqxpz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nigyuaro.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2exjvlzcz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2joyggxeo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eymwkqzl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpjkxbt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsmcmkz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnsijjm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxjqalz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2syyzwhkc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2iidhyjrj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uininxtt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2swrbydcn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mthbsfwf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqyplcx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoeyxcv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2icgqojvm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zofztjbx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rogxupag.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqlxeth.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubohzvny.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgqumnn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2goguvkmz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnxadrt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yyospoet.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsysyqyu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbpbuaw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vxftwyuz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qyudumpf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsirleg.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnbvxnk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcqweal.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkvghvy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jktyfhzy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sehtiavr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnchngax.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzmhnzq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfkolch.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeybteb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffonqlek.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvytnjc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2icunayik.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ajimnhsp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgaqbdh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2whhvugpr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2airxgoin.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjqfyzy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uakkgqzh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2unwmnxyz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2evloqzjl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hevgtgoo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2eawkcnpx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2itrfmehc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjvknvs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxmiuj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkedcuy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uczsmbja.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fctoivnm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxyeqjt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwajbjv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2iemfveke.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyqrldi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2svctvknw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2giaxmqzs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrtlvvp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brxhjpod.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwyumab.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2grqxkukq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaqvqli.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqvqnxv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwibgfd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrzhost.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyyooum.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbqrwbw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuejfeo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oufnsnyd.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtffgmu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2lquzkbgn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nykobqrt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2abzkdxuu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2meavkcfz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgzkvgp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytarhmjp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2pnocovcn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxlmpxi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjfnsn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqwjizn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxdobpy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepymuw.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qmioacuf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffchtgwr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnbvckf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oolrlnwa.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aepzjfyj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtasdmd.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bebbynxt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2codmwkcf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lwedyibg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2edwoswir.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nswjkphp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uikhjmzf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2lknewklw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jffrbgmo.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gydortjq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcseafz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2adjlqhfc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvvtmad.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2afhmufdl.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoqfvba.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ynayplch.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2angkdasn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqkwons.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhuesrl.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yocwkwtg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqkpafv.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wupqxqww.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2xsukctdf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmqdinq.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqbkxta.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrreduft.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbickklg.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwfxvoj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtzuxsy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2dptnhfnu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wicosnoz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdpwkkb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yqygmlgy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqrczpv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiieiwz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmxvwon.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsukrob.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ghccskpc.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qywrqheg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2eefdotyg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kgieanrm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmgcaql.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pguxuiwh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmkoosl.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sejofkad.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bocmuwps.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkofvhc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nffrgoff.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbwnhql.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrxxlbv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2imfbvqtd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yftjlsse.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2neowmfee.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vfszsfou.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gaanazuh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpsobsq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkgrzbw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snoqoyel.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrwrzma.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ripbzfej.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvtwxfh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tnimgstj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrqtknb.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaicxno.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2idfofszk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vodfamcj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjtcaig.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abpakdpg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2juzajahc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zynkkncm.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpwmdye.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2erntzwvs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2klyxhjfe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ficurols.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoendlh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sogzztme.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocraopfe.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2abajfqxy.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iddryvkh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxqwfgb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzemdlr.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zouxfaqi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzivnzlh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcqbci.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wgimeuqr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsmyywj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqalral.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxkimps.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2atxhxmob.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaozwgs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyzdciu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2lebwfsmp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwyjnir.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qifptrrt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lftvytja.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlobock.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyasdrm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rksrpgji.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhdzrgu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwsuvjx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbijyli.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zaawxmfm.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obuhsbjy.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2naaokmyz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mejznobr.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyjokbx.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2psxwnqbd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbfdeds.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2iaswdvqg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsgfcde.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvakepfn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcsoiyp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiwpnou.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyksdgb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sesvujcd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2anucadyd.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2deuuxvcb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eghfgihd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2caygwsly.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dacantpa.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cyemkrjf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtpfyld.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyidgmc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2swhvbwgk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoxouna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlljeen.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ngplcuoa.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfizdoj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyoeugy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzmcnix.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuoqzam.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdxftrl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tolwvjvd.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gldnlkjl.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2etwyhwcr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2oyerpmpy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pnklqctr.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuoioyk.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jecrradm.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrhhxsf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvulpgg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvrwhrc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2azpehczn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2krypymrr.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxzrtxp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hinfhipu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cidpnqlr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbmrseb.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mskdvqow.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtlfwfw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2phrtwext.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2geahaulo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vncetlii.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gedlnoow.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2folvxdib.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xonfxvhg.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeqxbnz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfgidke.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2izwronfz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbgzmia.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2inhhykur.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdsevdu.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2shkiafkn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzxjvpn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dicksviu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhihaee.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2abhendyt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbczlhn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2obaoyrya.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpfkoyt.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqqvfpu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2uupqbqiw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdvzvzm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ziczrgnm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2szssqjle.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpgamrj.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpclpnzk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hncogrtv.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyunfqi.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2aeglfohg.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdzzbfa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dirsqarb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjtjzgh.html


<!-- 参考信息 -->