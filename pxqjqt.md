代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqhummz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcztsni.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwoofmlz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2epamcpvt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vntwlqfh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wipdosxw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cysrwqsc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sedkmivz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzymnkh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gayhvils.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxcpcjn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnmmtxe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqwdgyd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcqxnda.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fagptfpq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2plcvsdvr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyfubzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2epnsmeei.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hpekelbu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeitzge.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzncixb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2epkccyrs.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkuaxhx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdeifld.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdsrvrz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2soonixlt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoahzye.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vphvhqcw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckusvlcf.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpncepx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzkklur.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxtatpc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkzzynt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2koytcfls.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2caghwxzg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhmzalf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2frytgjgs.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgizijm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrmqfup.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzaebnm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfkajsh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2shmrfpgk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cifipfrk.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpecirq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lctglvnm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbgnxoc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxzkqoq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwurpxp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrrwyhj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2onsuxano.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2wdepqttb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uitapbhc.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2apzrjmyn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsclrfu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hoajqffj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2igtvawvc.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcvqtpv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2wvusowxn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2drkmhyvu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sffqhghy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpbrtip.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nircdotl.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dxztjwki.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtcrimy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2dljnvikk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbnagpf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2xttjnpwl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usmrddkd.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nruavtnf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2pfujicde.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uejkcgkc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjkckta.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfugkwkq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhwqqtm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tonyuvwh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2giovtqwv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajafjsri.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzahnes.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmaycvq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfrcnbh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rclysziu.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyexxji.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2remqdjdm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2anshokaf.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wiymprua.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpssvyuy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfinvuf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlhggmu.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nwilhqhc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2efeshikq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsudzae.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2skfudtqy.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zbprcoof.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pokkklkv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nryfyrhm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bswvgelt.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmidklo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2udtjtdih.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnehsgw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upflzifh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2iumueywb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbmjbef.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xbytecnd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkceews.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vaamybpc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2pxedfwks.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tewyjdcu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwhbvzn.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkefyqwk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2mevyafiq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqcqgqm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uoahuftx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmtevzk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hytcdwel.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2apmznzpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wabwmpkh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wojsrzax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yydtxqbm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnslzwy.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmljaap.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2knolrkkk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdzkmac.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzshhuor.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2arevjqab.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvkauth.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlitohl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ombhkboa.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2johfqxmj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxssbnic.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqdrkrc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2artjmsad.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbgjyde.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2intqqcme.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vidxyigg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxiiais.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twyhzlpi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdwxmkc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2krxqbgti.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2segfongc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqtengl.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcommvn.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhvynyg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhkcvrt.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxgwsos.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqjdfwr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbkuxms.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwajjjo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhnvzjj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gntczimq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yefvfpbl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwupdat.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjyalfh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqkiekz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqswwdqt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeenkam.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyllxim.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lniygyyg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iusdixpn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rjoymzui.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbiwkog.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2otjzxrdd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnchnmsu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhpzpmh.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2detseget.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwcfpya.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2efhgtpvm.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxgoeoq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmfhrvv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2okllaquk.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtttbim.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cybtadnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cnffaeai.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdvubgn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkymejj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgfdvyb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwaokpz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2lucvhwaf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcumlhf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2csmpclru.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qducypzl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2binhkunz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnxtqyx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxzivyx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyroyegf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juypoofn.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2plvmpwlo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfddqhap.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjbhly.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfbpkkw.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrpxhps.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2akxkwynq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbuclgd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrpveum.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhawmncg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vowefjrl.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdfojgq.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuwkiud.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwekoka.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2duqxovaf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxgqrro.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ccngcrvi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsamcyl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zbpopxuz.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2acjcmvsl.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yunapzmu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2suixzgjq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rsofzqoq.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ignsppep.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ojunqxaz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2sbanolqx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcalidm.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmvckue.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2uysndmuz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ynekygzj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2oeoknnlv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqxzchk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qqehxykw.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyzurfo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phtzitrr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdgsbiq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zclvwaxo.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2drmqtsai.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqlvhsq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrzfolp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2okzjidbn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmgjsyy.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2amzypyck.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnezhzo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhfppgy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2omowbffn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhjaueq.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2axfhpnpl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2waxmqbam.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlxaosq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2acgkxspg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfiqur.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2usudqqju.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjopbdi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2shbcxbtm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qfineuyi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2qvktaxez.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbbshws.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwdvmzw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2abxwguyg.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yiliwxou.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfwhumy.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2orsxhzpd.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuhcpre.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzsdlpd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjrurwq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzyehtk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlqpkkn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gmskuzlu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hueqamra.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuhyucf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdqpbo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2opzoyzey.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvrtsnw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ischqpxg.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2uubpudib.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2qfddjbgn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2eedzntgx.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pnucrdkr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cocdzogd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gttqaiog.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiklzaf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwjymop.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkmdsvg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxizoow.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyyuzyb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hznfwmvg.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orfpizdk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ucetgmmb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzozrsg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2smlkqlqp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2txatrrmj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvxgupk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mhweyzwp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oakkzyaa.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nccwvpeb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vygfdxwx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnezhip.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvagamw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2diyqqhif.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtouidz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhexsuo.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etjmblhu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtytrmj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tivnxcgq.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uzprgcfa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2srrrsnse.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxrnjgf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdlluur.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2acitcajn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiioyue.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xegoeour.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2haiwpoij.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pwobfnrz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbreabp.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfpxcfw.html


<!-- 参考信息 -->