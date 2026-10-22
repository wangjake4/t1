代发 wailian999

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2laxbjwyf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcgawrc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zqichoko.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ockyyjfk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bordkzmf.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxrvmrd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dkenqeef.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxzgnkg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2judbmhcg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqgpfur.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpadqend.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnrhpgb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsfnhrd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlhixtk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gboccwci.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2huuovvwp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkhbdzo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdtkudv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2thmrswnx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alvzagka.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2suzlaesu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpjdcms.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yonvynsm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ztplbmgn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwekpjr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbljklo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vddkwkwi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkmbxtk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2appkighm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlfxyyu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2trzznmwl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmkskvc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2snvvlvmh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fisuuokw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuehrfq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbwldsp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rohfgary.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgubatn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsfxmlk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aahoxyok.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuztlyfb.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2chzseyzx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiavdcf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2riqqcykz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtttjyo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ckifxggs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtdamkt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzsdsgq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtagwak.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2nkamndmw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhomzmjf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuvphhc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqjbbwc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoanpbw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdjpljl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2obmyeczd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkvyzyi.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrvpalm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2turnkpgx.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpauvvv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lllkkcwk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cktqagdk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrcykic.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgrowcb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzspkmj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjnkzhl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmfqsoz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmxdsek.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tuarhetm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcldotd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoivndo.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymunbncb.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yssunbgt.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzccklao.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgnsoot.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmxualj.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2imkcwvvc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlktvjrw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2azaegaym.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkpvgk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gryjytfs.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpqiynp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2swsmvejq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ewspgtwt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suktbfbj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwkeunz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wthahdfl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgaayxq.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqikzrzk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfodvqd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aufhtvnw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2chlkyivq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2gygbmwlb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vkedyxec.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exzhadak.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfogyxi.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xldchqen.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2sljrbklc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2oxguydnx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2idbjchlg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuwbdos.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzrysxi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2obrhtsbv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qtedkwmf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsdgcwn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2naxhguon.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqjndfj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dryzxxus.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2weciqwho.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmhzqxy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lmahjoae.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsorazlh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2svvoctjq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqidrmet.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ogctejan.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjkbwmm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrgkmtp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwsyaqx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2msfetgys.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwzdkht.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gepmxlca.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvdtaur.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgddhsic.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqswpov.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jryvcekx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwvngtg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoxlzxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dchfzaen.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbzvvin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aidygzhb.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjeuiin.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcunllb.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2fenbogjk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnbevqt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2epqqzbxn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zflultin.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2knsxqqpm.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pibrottp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoisrtb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hykhlwtk.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxxteww.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xcozspcw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cngyrxup.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwvpnsy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2krcfigmt.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zupzvaun.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjlzbzv.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tamxefnp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzzgnee.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfvtskd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dilkpacp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tonwwfvm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuknabk.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdkqgzx.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryblpxxn.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoeibpa.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lcauuklr.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anwaufys.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2idnautrd.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lemtwyhw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vbixvebm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2csenqjgz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdnzgts.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjxnwfk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qepapzwz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbsdzuh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uicnxlla.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhxdwtp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeqrvcj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2yerkkubk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrnfoia.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fysrljtl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgdlncs.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnbtqmf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdtidmy.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wreapeif.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyvhqno.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgohlzak.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iohuotnu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2moflkxyi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2daxseame.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbeunzf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdvthoq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtojaas.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jftjoais.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2thjzefdm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2erwotgwe.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrotlxj.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrtfitb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2syjinnqf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzbbmfn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2evvwprbl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlgkyoh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dowxyyxg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wckkujgw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdprfnru.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwirjjx.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzepuku.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udnqxesl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2schfkhwx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2opvrcxad.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nuklnenb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqcfudq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpphtvw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xewgdfhl.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kosxbwks.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sflouwzn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2omeguswl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcoqasu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhawibw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hliqtayl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcbycui.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2oifdvyxh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ksctuwss.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwuocot.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ytljffjb.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2rusdmidv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2tndsdabw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgfespo.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2buuetomc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ezakrvli.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xwezufmk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2csfqakil.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zjginute.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrzbpzu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2docabxos.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxxahhu.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2buicfucf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkrprpo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2robgzxsh.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mimjovnr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrmyvwq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpnnleu.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlxwjic.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2azjmzvmb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wcctcjyn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvrscbx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zkikevus.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zttvsuna.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdrpzkc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pttfxilr.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbrxhfr.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqisxyz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ribupzqx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgixuet.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvafoag.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtkrvez.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ioywypow.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hxaozmsd.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qizwwnuv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbfizha.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpvpcqx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pniygeak.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ifuuyojo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzpvben.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyhgkoc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2whvrfsil.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrwpvlk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gozxgdza.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiwgegz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2blgocdcu.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2srheccrk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyylejtd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoowvdd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjprdsa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxynmmro.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2utddkyzc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqwteqo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcrvnss.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvtbrmh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxdqqjv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfomkcp.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsinwen.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxfbqvv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvhweku.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnqhrqc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzscfeg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hpplgqix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcgbegx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tplupsup.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ujykvdvl.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2spzprzjj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqzbyow.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmyuhkz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqisoua.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrvmhqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgwpjsh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2tiggpezw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2eswthkwb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiimwqa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kuijesro.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnzwvyr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tfojrxgi.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rjepzipe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2romtzfws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzjlqwn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyzcqld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcxaqtb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anuqkzhq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2vlewmuze.html


<!-- 参考信息 -->