代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhukjpe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxnavpr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsguoedm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jthypana.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dikquxia.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gablugko.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iayduevj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyuaunn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rauucdig.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqntsfa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxqnqle.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfsvoxn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjcgsod.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpxtamd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsklxoy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpxflib.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lglpdsvy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdztvrxo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umorcjcu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjvxwzb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyepiylu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2glkamjfm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ionccjul.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgkkilz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzwantd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsxrzfa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcomyks.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2unttpcro.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xasbsbmv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbvrgfa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2amtlirlv.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcmiurg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlbkzir.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2maeijptf.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2elscmxyc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyallxt.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtnmbrc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2crtjwwjb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2khymgpjr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcwmvts.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bncprcui.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2grpltqvz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvzkiiw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcybabtd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfivrvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqnhrak.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhnubhf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsicumde.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sypnpihi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2owzwnlbc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvbafeb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sewgpcku.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgpasmf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2joymwjph.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaynwsbe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cyilcuzr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoetspv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsriekq.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zladbeab.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiokvzp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxdgvhb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivumvmgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmvnusc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qudveoyb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoniuog.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2egzquhxa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnqhgod.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2azlywush.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wugbjnzb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmcslth.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iplhvfrg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2spupdwim.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2szvjnels.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldebxur.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzimhid.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpysvhjs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xctdxmia.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zhohrywz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmiegmp.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bagbtjvs.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzxaoin.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaaorkx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbagymx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrherqha.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hocebbqd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpfmlid.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbbalqx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwugkite.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttamhjvd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhaucgh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2nbofrrej.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yogtpzxs.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qisnfugz.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgektwj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qajsjwjb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bzglhhfn.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adrsjnss.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2deivdmsz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2nvomgxeh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgqpnjo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtofteug.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlaving.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgyfsxk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjugnkc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wveeihoe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2spntxarj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgnsvvn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgwlgmi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kibappuk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bholzqfb.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqsszyb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmbgrbz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2znkmgkne.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcekrrsu.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bejkitgr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvruitsz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mortimnb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2itvzbqjq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwuzdqn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ictkpjlz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2btrwtdhm.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrrdpyo.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zakyuspx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqabpnrr.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bupznbhw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsnceqx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lohysqtn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2phvocukv.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwguowdt.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcuytwg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdxvjsg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qlratgea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtfznlk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmlwbjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zujdnzkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yllfsrre.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vugpeffu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhhulat.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaemder.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kyexueyy.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2clmrifzr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdutkef.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnrbvtc.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwcgjse.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqmsusy.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnckvch.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjacxvb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gsycktzc.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuvqysu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvqzfqt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbtjzqm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsxrujg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsuquzb.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2alccmzzv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlxaqnf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzfxiiz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2otieggux.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cizhxxxc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2byfuzael.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2srjwppmn.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpuiozd.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxpkxkw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujjwvli.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbsvhicc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxxqsin.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnklrveg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrgcksa.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzuwekf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtmjniu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2avevxuag.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzpsjpi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmeryuh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhjazbh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxjadid.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqnzhkc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2regbxtpr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rokrplsi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvibaav.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnlzlni.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfvkgdg.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlsvojm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxadulea.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nupwbhoo.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ghetufhe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2prniwpdm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzytmyq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjcmdzw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zavknpsb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hrokwwsr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awdpslrb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsgdpzk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2wtaayxvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtabdira.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxwncec.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmcnfhr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2iirafvoz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmriljg.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uioabvtk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvebves.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2encezjtp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plxmavex.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hiihhxuz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqicsqgw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzosxgfc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2caeqcvvs.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2okkqvtki.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lidydkat.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oggkpebd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxdyulg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxnvfsb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkavnwq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nepirtzz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2equorcsf.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoqbsrd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwskrtr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqskkic.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2osjuhklr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgxajk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpuhysi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2njdtxmjo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uecqfctl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bcarjujj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xowzflvf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfnibzw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqgwexm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2uitesspp.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlevigb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whrmwacs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpcvrxe.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuopdhv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zekfjxhz.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhtsaxd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hamzayzg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rmncojvi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2bntyyrpx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjmpzku.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnhrkvf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2onznsvyi.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aboqwyta.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbpgves.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkntain.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fuehkowy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aykfifao.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yntamhry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2njzaclmh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiekktdu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bljuulnz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2urnuzvur.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfbyauv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aospfpkv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpucnov.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvkripo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvgvqes.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrxubqp.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfqnzor.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhlpyqu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vbenpdjf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjxtacs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2amttxjyu.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ueswupvu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbgnvqc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmobiuy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcrplgh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2otakvbxd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaffkcp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnranrtf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ivapgnhp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2znlapgnc.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbfqzge.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iunlfjsy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldtygov.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2crdwkbtd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hjarzswo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwdsvsn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jqasarta.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsaauhm.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2naonraag.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aawxgjsz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrojutp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxghgxp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkzsnge.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2gfywjkzl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbpvxwc.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2laehzbnb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjglflff.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbdbkzw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kztjwaul.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rqplogou.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxjmucy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dakyhxse.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gchnrcyj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kbabseuh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeyseed.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgveoaf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxlrhyr.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2safytjin.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bndlffmx.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gptlixjn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfahtbr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2txqeknso.html


<!-- 参考信息 -->