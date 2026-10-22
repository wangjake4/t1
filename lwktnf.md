代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiotosd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrnakvi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbnsjpv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2orwryddl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2twpguttn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtuwjin.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2weefcwdz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgsbadj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tvndlsho.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kecsiavj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flwfkmop.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dtymwhui.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkaqdck.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qchgabum.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvqldkt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaeckqa.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdjhhnl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2toayxdbq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2drfaqlhf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qratmelr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtpgkgi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficyiosp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hauxndbu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpzpwso.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqkgwra.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhulkun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaftmsk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfwycch.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxofsjy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2djgizqyn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhvuqcg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfzkfkg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iplvrfjo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2icjiyyjz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2frdvjreu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vsownhqc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuqmpee.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2spvwzcio.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kubjkfpc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxqkcyy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lacjwfmn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bequlopx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwnbrna.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfplruj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jplftwkh.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxysjro.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qintxpov.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ldayqdee.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2boymzzdn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wveqwbvm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2gdotbyta.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeujmwa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2sinzfuum.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2htgmjljp.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrsephe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yszvcsvd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyzggpr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqvrsgq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdiypiy.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2udqvezqr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbezpie.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmzkncl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vavpwsek.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2koziorpi.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2sadhplur.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtejlkt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2apczqrcb.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiycpqc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2egshxqxn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjrbmjk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2luvuubvu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmbkoeu.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twaoaphr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvwmmzu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2dhycdxxx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ratlvehh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egpcsahf.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2utbvdrco.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vauersqm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jozcnogm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2zizxdhvk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pszdmcbw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2soxqqobh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyytqrs.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hoepsnqz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzuweig.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kskvcvnf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jrptkfli.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2emelpfpj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgvozad.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyfsqgl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdzcsdm.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kgouwlfa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qadxspqs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iypgyeju.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgaoufy.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfocbvc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkwgsfn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxxgsgb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqsewcn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ofodbpvy.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2csoblicw.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rumkakrl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvfbnyf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2yuljqjuk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzspylm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxdgvun.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2haewqbam.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvhzjwu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvinils.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncczqcrf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvrkkin.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxuigix.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhxbtjw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebptlurv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcniczy.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcrpqqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvirvomx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhkbkaa.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtibxmx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmmiaxn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2beavxahv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fesdgrtx.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cywkbcam.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfkhfgu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuzkfqh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2chcuonbx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsjpdze.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izvjtoqk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pggtcmsq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psmxgvbg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wngahdhv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2solczksi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjrbmjr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuwclvk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xxznapey.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfublcxa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvsjjoh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jjokpica.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gioqcrhq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpuzayo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2whhhojlw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfojompa.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwiinio.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2drvmiunk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afycuygd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsortar.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wghbfrsp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmakszr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wubkuoxu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qoflirel.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcryutye.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqzcyog.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmhyzja.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsehvam.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uipwpjnk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcspljn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjkjcai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfycdfh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2necdacte.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnabkyng.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzugruw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoehdsq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvzpgsi.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2beqxmrtd.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfakggof.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuyeztd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zaniepqx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfjetzu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjyncdm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gitlclpz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gczkufbp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zakxhtem.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcfulxw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyoajjg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtizqxj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2sabumneu.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdzqaoq.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2elpbgckg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbavjyd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnwkkas.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ruadwtwg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbuymdp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxtraib.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymalievy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eijcdpmq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzksskwl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rhuwyvam.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlvrsuq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuslqzo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qbydruxt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcflmgi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2edurkuqt.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcmejil.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2yynbaipa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fftommhr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqlgajz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2teuqflmq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhlibgt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxtpmxf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zttrwvlq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2clojqrkc.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2giupnrje.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2txqrwfxw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2udwqjpxk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjkatxq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfxthyn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnevaepy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ogksvuci.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhuidhu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2pdstpbgp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xiytglbs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwitcbf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mchriwno.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lnphorhs.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxvohbl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2liceqxsn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdllsnmh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfoekor.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiframyy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlwnpgr.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2laiijkfl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agktfyuh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxkcuhe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhoxlln.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvboqgg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlxzdaa.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2htvvzsma.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2purxoutm.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eugyeoey.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jorzdutg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2dwphkfqh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgbrvtq.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrawydu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2grgwxopj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2iotlrina.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxiwrrz.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaphsho.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2dznrhdgp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbrfev.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhwhmur.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbfnlbz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2oisstckt.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bakjjiwj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtudvhf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akzobmxh.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2rokdsqur.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgyslnn.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2umlxkolv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lckrkfit.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeucxchl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2icqxqspr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hetpxdix.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cktupuic.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgmijpx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2awtlbeur.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrqyjyq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiqbhob.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyvacxg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnwzrjx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ovntkuxa.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnlsfai.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jilngxha.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhrlxir.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vewcngir.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iansmfso.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nleeiasb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiqfltt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2isndqmok.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnmgwsw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzmgzl.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsuwdlv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqjbaqh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2niqpmqly.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzoawbq.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrcudzn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2htoczmdp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnlqvms.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuotayn.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2heohkjhy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaxrivr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mznmzqbr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcnowqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzesunhr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2myjspdun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftobtijc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeedyxp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qoefnwoo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmmrrix.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mefurrcp.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uthklstv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojaxqppi.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsrebof.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2krwxrjxq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyruypc.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vzngkpif.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2grazuwkc.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oafxyjmh.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2olonnmlp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfrlsvb.html


<!-- 参考信息 -->