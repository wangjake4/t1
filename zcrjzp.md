代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdaebzl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edvfupai.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fzonyspr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaqnabs.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvofkdm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuytbmi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2febtuegb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjnlhtc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bylavqso.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaucvudz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjzpbum.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaieebd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsyqjqp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2myjpysla.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2sejuqjvx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjimqyi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sroeoraz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2puelonpp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2exbhpxcj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2utxqrnkc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyasbre.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eveppcqv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xhryijfo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzesaknz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyaogbs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2npfnczfj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kppyygmj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2irbvhiin.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aapbosyu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydemrfwg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqmochr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqiqbcj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tismzgru.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvupkgeh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtmatdd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcvuivt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tampjsbu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ereseevs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwistnxd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sitqetsc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2usxbeymh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtlpbas.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwemrtsi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpglbru.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkuqswd.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2besajues.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2otemqscn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmutpiv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tetibdhq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijflsg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jazdxaum.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2roxqvuhk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2howgsfjc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpumlyk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrbojzm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bevatbxd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2migcuewa.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ujylcyja.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2brsgrvke.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2msdgdpgj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2koekcluy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrbshek.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ouykccpm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkhwtuh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ildvwnpt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtazisv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2poqmaivx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtrwuwu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2parvtcrs.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoeiuni.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2waotpszq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2nztmzkll.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2djghopzp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzihnpp.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tijtsupg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ridychsu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpaakng.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2sckmosls.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xyizwxvm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhufvsr.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjlfcvx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wagqzycw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgipdfq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnxeymc.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnorwmos.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvrgcgy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2bnphlvdr.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zijrkaje.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrtuaep.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tqteaczn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bozrtsuk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gehkmutu.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2flhwlegb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbxmivb.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuhsyeh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2umkvdkrg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmxdujr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfyhsql.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgkdqug.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2huukmhwx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqrjtai.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hucxammx.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2unrxlciu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmnrpal.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dijzlwlu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcwjdab.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nxchrizj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zesgqklh.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yiokcvme.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrmohga.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdepoai.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjisryx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2awcyegqc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2eymkgiyd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrweyec.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2btnbhkes.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbghuyqf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2afljrttu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uczhkytf.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iqluhxkp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqyvamb.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvnfqsd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpujqwbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkrerpp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkhuinw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laugxkkn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjtscie.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrfjwcu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ethgdkwn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwofqqf.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmbsfds.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrvdrwu.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvatpru.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gttjapxm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xildthxj.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgqzlpl.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrcscid.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbzelxq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nozwuxwk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inhfqudc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2crncpyzn.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opafykam.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqhhgzw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iznxhgwz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2blttijzp.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtywpcyt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2buzbkdya.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yswmcjqk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nktvccyr.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrpkdko.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqlpqfl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2njszsbdy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ficgigyc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbpntwp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjydnxfn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clukscnm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bemhxgdt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qemudfxd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvcmxcm.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tcprzihx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgfrkwt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgyewpv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtjnoeb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xoprcuop.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxeklbg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2wrakrgff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbuddxj.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2avcdbpmi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bigxtxae.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeljxly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpzkdvc.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnzzsib.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iebkallm.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vajgexqi.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axvbisqk.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2btrbldbb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pumqstsr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkrzxug.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmycjnvx.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2emuacera.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbtimfc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhnbjws.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmrccpc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsujjia.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuinswy.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjhrmhm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfftwuq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtbwjgv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iaixotpt.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cuilsdnw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnlxyyb.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqxjtxo.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqhbbct.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfeprfm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgzgmyr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqqogdh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtynwxk.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wohqdgfx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbywpuf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2njuurgxm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2shhfjxji.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqcvhgf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrbxnzw.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2timiwbjl.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpqkpuu.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuydeen.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtjifvq.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uatemakf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnjnecu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdbbiff.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2htdrioai.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jrloakeq.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ccctyiwl.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmdxbak.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzkimck.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwyompt.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhydhpu.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pypauxru.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gvduorae.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgdakkt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rharfjou.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxviegn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2gawhyslf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjugqmr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2chkllmdo.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvtdntp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnvyayx.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2buhstjbr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2nifausgv.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2clmhmagx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2legtqvbl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmadklq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmwvjzv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2sohwsrey.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrywoxr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtkbwfv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cuitnaqh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rohsfgnb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnrwoca.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsvawkk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2btpbmrui.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kouhrzmv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qdopmseq.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyuuupr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2floavqkj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzswfikx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jbijicak.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2balbauun.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2noycxqra.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fexwhsok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kfojnxjl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2euzawjwe.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2gabjbtmf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bidgieor.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2wccbarhl.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2yyivifji.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2chrlxzhd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2naidbktk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lieappnr.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoyzose.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsvrsfl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2djyqfdjv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwnrptq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkkttcc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkdenef.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2aulotffj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rclhonxc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oujffqgo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2skldsbbg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2phacvjmt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2yflvoeeu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdyjesr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxmnkbe.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hirciztb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tkajkryx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2squoqzkj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2clcaeqwi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2lyoywjro.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2igvzputx.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoqpxou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qizlzhuv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wudnrttz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmxvzdj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcnyjci.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrfvypv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqyglti.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzbifua.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kaedaqso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqphvghv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkjstwn.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsuhwem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxyrzrr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2olejrmvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcchivg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrffpag.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmwdmdf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sotmbnxa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcmmaop.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxstyod.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxvkyyf.html


<!-- 参考信息 -->