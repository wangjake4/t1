代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtybjww.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dinfraax.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfuxucg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtzzelf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vedplfcm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2whqcwyke.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2prwfxdmn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jegtwmmv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbscjjqk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqjsaow.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaimorf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sotkvfnr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nojiivsh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlnyoil.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgdjngm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zihtmiey.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwqhaur.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjbggwp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpbancd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2teqaelsj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sttpztqo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2aihygkyf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlqzoyu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rofxllkk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jxprtboh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2reptmduz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgqxdjf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2twledzgu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwzahhj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujblzlxk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zffzdhpp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhykjst.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvixgdtd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbedur.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hzalekkp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlxcqwh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sejrmuau.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2cdindfqo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtnkjgi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbmywdu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrxzgmy.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyxchlf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtiyyyp.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnvmhpq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoxuoan.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfryhepx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpaqwut.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2llqekety.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrtdriu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqmpsii.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkxeukh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nskgxnec.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljovnvst.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsrwaxr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2etscsncq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsibroa.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqcwtjs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdkbaey.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtkydtl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcykmfbs.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aezlorav.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zhedjloh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2orkgbgbh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybytwpz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdxazwq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvoxirh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lfitgxrl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmmcmkd.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfypdbg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsmdvya.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2idwcujbe.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2taqbbwaa.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2elmszien.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mujohlht.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2dngushkh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rqozcwvb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lahxvoza.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nusckyxh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrukbqx.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2txyjekjh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uirivmcu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ulipkhul.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpnfpkp.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wolecoqf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiwsdyq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpyoncs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxxoash.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nmibmgyn.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xkppwvcc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrswboyt.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlfuvxv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkyxtgi.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkjzldl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvkwqbe.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ktndlyiy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2skiucano.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlfjkks.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlwpewn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbmreel.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrcmtmi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlyueos.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfflfpl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpuvgue.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oddagnfn.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtkswjl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzitahul.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiyafuc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2adtgevxv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjpdhih.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrxzoyi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjdqleo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzscavk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsahciy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2dstjaxpq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgvgpka.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeqqxss.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2geqttcfq.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2apsfuoga.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uglclvgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhjvwzi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmsvaan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrwsdts.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2otuadynx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2beofisix.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2rglcnfxn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmznldix.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtintbnt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2merlsiac.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqiqzsj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlsasvo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjdsygo.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pawnzdoj.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfiagrtr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rottkmxx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtscamsb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjettuwa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaaiqje.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2raxsxcsm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbiafwz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvzcphw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnsljnd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjszrlj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2edoyxguq.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbkvcvi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxtfkwo.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xujeuwmp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjoihvb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbihrqy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrhjxkq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2augnppip.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbcxrqr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkkzaft.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zsinoxmq.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmuzfid.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mhobqnuc.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmipccup.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evilbnho.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqhjlah.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fidirykl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2exhtnqcw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lukxcjhx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2agqedhfh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhihfmsb.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmlqrir.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bahjqglr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgedgfkm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuwtoaz.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2olsfyuxp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpagslxf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfcdzqr.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxubraqi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlvrebg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjflrub.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rphamlba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2evotmmht.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jotbmutr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tszejnrk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtdlocw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwregtr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqxgzpi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzkrifs.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkgmvyw.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2unyfymuh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2getbusmd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfgswkq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eclxilmd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdqqdkz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxueqgky.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugopoyfy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cajzknst.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exxydazp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hggkuued.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwnoxel.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2piidetgo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xocahooa.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2spwpfgds.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjnzkad.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgrtboz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfrgolm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsxmaum.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqowrwok.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nivbikfw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2dobyyfnd.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtekyro.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsozlyn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhxzwbf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qxorurwa.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qngncupm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hvberrqy.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzxvhmg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2evltqjsb.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2welyhcxm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2eplcnxvh.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lkaproho.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlxuvpo.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvvfaoa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hfttvicg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2shfzoagn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2pivkryuf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqrhbni.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxwrcyy.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzesdknb.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgrrbmi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxftebxj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2qfntrudq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrplyyl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rscovzty.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpayshd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyloslx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeeoair.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2atcqvztt.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ncftghtl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2oufehywc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cagmacyc.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uicxjdgk.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2joopvqav.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xqovozxl.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dzucfott.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bwntgzim.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxeieeu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtsajim.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxauwvwq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hovkzwbi.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2riigdgry.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzvxnjg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zroehzcs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsfphbm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyxyiib.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uousdjiy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfnhktm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2msazscdo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdqrewu.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2foupfxrv.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbekxti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtknopf.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kcidluqo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2txyooksh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeqbgaj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ssgkrwxx.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ziupaefh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2eklijnsg.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuzksvf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2unapsodw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgrtden.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2toterbhz.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsgxglg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqcpbbm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ibblyqog.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2klqrfjnv.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2domppelg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gdajunne.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2opagbryi.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfirywv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ichqztcb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oerxiyli.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uiznxnvl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqteqtu.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgghkmml.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfqakmh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2npuvwcqr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2thugnsoj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jaujleeh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtqgbju.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtiemqf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwosclu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyuzney.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hbssbyck.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paejevhx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mftlevje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfrcoug.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxevjsyz.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2snfdwopx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooekfomb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxvmqak.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhtxuoq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2udphodpy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hflyfdxl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2asqrhwfn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlfrwqq.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ohozuuba.html


<!-- 参考信息 -->