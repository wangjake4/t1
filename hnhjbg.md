代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiiigmz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsmpffc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2atkrtdvh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrjaekq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekmwukn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmagwlyk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhevcabq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqioxnhq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yverymmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2czyjojwb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2svfgjyqw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uchwohoz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdkhcak.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyozlxvx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlwehcu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqowpwbo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlatngu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnjzcxu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvlrgjw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcvvnpn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aukcbnee.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuvrisl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwkltdi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwfurhe.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yimcceoe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvgwejl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2okyqlzlk.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2udclfdas.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzssdms.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tlweufvt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwdizmk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bmldhbdk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfoapdc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2eueqnytx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbeoiid.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaoaxkr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nxylbcjo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2yispbuyi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2livuxrcm.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrctipjn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uijfyovk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pojzqxrj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzaosty.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbcwgcx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfxetex.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2auclsybb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbvzcuv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2eyexduht.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2axaruspy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sorcbkol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwrqcch.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbawceu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeloofs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfewgpc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vlicmfxi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudkcjel.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctclbbnt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uprquizh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvnwalc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhvudib.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmqyeki.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxggltz.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csgjgevq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqekmjo.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhfdhhs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpwctwm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2iazrphmy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhjrizy.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsbcslu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfsmgqv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2trobtwaf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkytmlv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mficppqa.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kyadoeaq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ntubqjzg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2twcqylyt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiafognk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2doafduia.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ijglwbxe.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jsywitmp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2frdnxlop.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2brdokvmd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnujtcup.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2frnjilbd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zyabqwgz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpuyjfg.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2chtbqsri.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2hseghkms.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2awrmdlow.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrjdlay.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjecqokg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwyfhfc.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2smcdmide.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jssjmmap.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwhefqy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upgqvivx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmpdpnw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfchouk.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyycvaaj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oorwduhy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrhsgmh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmseuxxk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2svnvtmoj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxacsxq.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsqxoyi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsqcceg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2twrxgpxu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmczeage.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnkjrei.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgipzjr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cclibvre.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qctvifsl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kabayzxu.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvfefdh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatbzubp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzmwrnb.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zeztijwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmbesqw.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2mikroalh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2igvkxgwj.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2iucnnrrx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmaivdk.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eslxtjqp.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2awkawwwv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tdryevmg.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kobptydr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmsfxxf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fulmlieq.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaivdrg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwcialq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjotgkk.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaokvhu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2flfilrdj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmaqqqh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2llucalfp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2irumiylk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgdkbxo.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dblvcwjs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ellzfllh.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2idyrkpgz.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2vdztgemi.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhleedf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonratfe.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourpxuoq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2nekifdik.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcimifmo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pdudhoix.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqhraaa.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yrthcqet.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2txxlapaa.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fbywonqj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtpjrfq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odcpbuvs.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2shsjvunh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqfhlqb.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ricueito.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwtehru.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gebnyyew.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xiajyzlx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yrorilvt.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaspron.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhxwdfh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmftwjki.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhtrrhb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnffdeya.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vodduipy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyofvigd.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pelptjuo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdjnwjx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2intswlbs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmeqkxk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2isdmgzyk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dftgtctv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmmiekj.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsnzqeg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aakzafgc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrzrkqj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ibggrhcg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hukidjlj.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nigpdrsp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqoastw.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2hqddgqsx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbyvsvl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fbshlwnh.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfieucz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhvjdqp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqflgllw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgvukjd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2iflzyopp.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwosijn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2oijsekha.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoaedng.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2urzrbdmg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iejysfpy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rctdznwr.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfyvtxs.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxmbmgx.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2lhegsyqn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhfoqux.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2enqsjvpj.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhcaqlr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2caaypjky.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ratonhlm.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwexljy.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2sajjxuvf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcicisa.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bebhsmnh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlmcujm.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfbmksq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjrwajx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uujxohzb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qcddyhxa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwemnpz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fasqdbgn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkmyfvt.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpammgq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwmdtet.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcaerfp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yscrusnv.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrredoh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ualehzfw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2clyjrmjc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2henhyyjh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwhyekx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhpbyze.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbildhbb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qpensvxc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpmbjjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjniavo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlmcsrv.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lghsccpd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwakmsw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfzfrpy.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ekttekyl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwbnpii.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgcknbc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvzjlxc.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwznrlx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhzbqhp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwksgrq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2szixxgyj.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfinkybr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gebujmhi.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcnrpbr.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxzqzdn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hcljoxtp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2gatnfgzp.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbhofun.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtnlaee.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2krtpgeiv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjplxux.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pznmzsit.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwtxpwq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2idxhkjng.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzwhibc.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnkpiio.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtydnep.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzpbyrz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwmakov.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhzlptj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rchrgbcj.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ojivwgcq.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gdigektn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2afxakowy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjnvtqx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpxkoks.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzmooez.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rqulufes.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2yyohnntr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkctmfv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2oebfgeuv.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2esmellss.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2oznnhqhn.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjuyspt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dazqydqy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqpxxpn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdyvhes.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2nekjjwox.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2doqjhveh.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kjncsgvd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2flkbcwsn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrikygg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfnjvqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnyevvx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ickdyocd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tibnjgap.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2upnvujkp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2zttcvvir.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snjmhgtf.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxbktta.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2utopubgu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnaknuc.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbywtgi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2iusfcfos.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrryqgz.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdzujxp.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbltiheg.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nubbmwzz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2aykaegme.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoprqxa.html


<!-- 参考信息 -->