代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ksokjsnv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrwvnj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zannigdf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkgzkux.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2khrkxyjq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwfjwon.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgrynpv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fotyqsrx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvrwwed.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxoldnp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxxovdl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxhjopq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qswytsmd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaodntxf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2drdqylda.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hehndalb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oelzlsxb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rohturhs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfksbus.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyswdxn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqkdjwv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hluxwneg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ytifhhrn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzfjhtw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnojjjs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmphqrmr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvoulpq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhftwlyv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iutmujfp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwtxmlf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lotdflhh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnpryov.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2updpfjxf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sckdevno.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzerltt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfyzirl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcxjkrg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fidvijmc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrhgmdx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrpkwbo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjljmhkq.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2izxflexx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2smewujeo.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yuubfhvr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aasbwhjj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhrjesm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndazjppp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmofvfjy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2onbohgpg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvksugks.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkwsox.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jjulxqkf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkvarmy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmhskbw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2caiymror.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2slzqotju.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkhzxjb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqazgyg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhzfsvj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpqwuym.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xmghppzz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eskrwirc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2jccipjxk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkqhleo.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqrjjhe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiiwzsk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2elsapbbb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2chbfwiaw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsojsxs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrlzmzl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2brponrjq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2bifaucqy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2esyhkalm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwarvse.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkjqdwv.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrqojwm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2krjatykr.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2eqthyipr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxfsbcq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiimfyv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2agblphtc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2irtgqfex.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrkhsah.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwychhq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzhvcsw.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ozudfdao.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhexmqw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2knyjtsdn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2oknlrvvd.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2edsoyupe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yogomxzm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvqqwim.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdtchav.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvtpebh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkxwaaz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2brmvyjmi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ouelqzkk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fipagfmi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rldizhid.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhohgcy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ocigqzcx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbltlyhs.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdjvgbg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znylsahz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ijufhgyf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzdxtgy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2podiathv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzheidji.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwnrewb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2genpgmby.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxvhfua.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2camgvdoz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vezysexf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2unwqwzmp.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnbwbtn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2biscfkkb.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwggnns.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfoskal.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuzllqw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ovprpwwp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnjznlu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnejpsl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxttolgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hebgboef.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yyidujli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcaoqtd.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsvzbba.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2vegiswpd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxatlfs.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ickortiy.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrdfguh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mcadetpj.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlejzin.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2admngman.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiagmnv.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2epuexnen.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucupqgkc.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pmczcpxg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcppixe.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfatfag.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnhyyun.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvmxwki.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvemrsna.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhbgobi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxxgizu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfdqcto.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ropzyhsg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wncqtbvi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pehdvqtz.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pebfexif.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yptytgap.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2imkxeyrf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2actvueqg.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqjfzzt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrqvbyc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bhztmsie.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxejrar.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2lqknnzju.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rypakipn.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxzsybw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lnexfyeg.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtncuyy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2moxivspx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhwynfo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxkvqaz.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbzvjll.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvdvxoe.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gitsqrbs.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeklwes.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2imipdnrt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcmmdma.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2maxqkapu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcojlxrp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqogzobd.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqotoge.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gzotqkee.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjmtskp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2okmkhczu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmnfvut.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gmberwad.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skovhudo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2veabgjec.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcomwofe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dptokvvh.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmupbwzr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqjctwy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qozgfldp.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjowilhd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amdkstyn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nzycjhkw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyrzgpq.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwmxjuc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnvbuln.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vypsbczk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2penauqcs.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2etzogdje.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2bzuivwkw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2icteltzp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxcvhnc.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2whetfssx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kprclsuw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2llwrqwcw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzfxjqj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2toizzfew.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adfjlfpc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxkmvzm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdmajzh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kobapgbf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrzjjyxz.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nldnnabi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oaulicne.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkcztee.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2irmatoei.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xufjhwoc.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdmxxvk.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoqaghc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eievsxvf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqucpka.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zharmtut.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcmuijn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2awpjejsa.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hiukbuml.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhaalsk.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2donyjdtc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrsjxaj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqpvuxf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihebybsj.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrkhiox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lervyhvy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lmomdbjo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvihcjp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2jepeqnzg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qncnvfff.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsolrns.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kuauzhdu.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2fhewmhea.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mtylzryv.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbpuryu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqlkqjm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fajjzfum.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2isheuspp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lljvydqi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2relqdknw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdxdkcp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ymppstup.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evvqniyt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2owppxarh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2avovjhlu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcobacp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sqndkxzy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2eonxkqgb.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrtdnuu.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlqtdwd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzzmnzm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2otfeckis.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2byhcxujt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qglcodrf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pejjjpvy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2iubtxwpi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtwshif.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxpdtdp.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbcuavz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eunsluqq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zvworctk.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2llpjnwzg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnueaocw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mduwyqmb.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfjsbwg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2tqizlblw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaeghlo.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlnmbhm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkbxpng.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjrggtn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqkskl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpwizpc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcvdxfy.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dploiybb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxqylws.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fiknqiny.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvwnhmn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvdlmpd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hedirwaf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqyxyte.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2nudnkuja.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2csisksvu.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqjapgl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwckgpl.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xncbydra.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twcelnfz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmwsdsi.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyjgusr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyutobaw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcebueg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eotywaqg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyalgiv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvzzmjx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kthzezgk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2numkuyol.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmqbppm.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncivzygb.html


<!-- 参考信息 -->