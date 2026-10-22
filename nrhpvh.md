代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhyrrhm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2syalfhmt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmojhhg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpnwulx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiclfba.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aohugixp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oafeuntm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2txvfwoks.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmoizlk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieybjoqd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2glbmfcnc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnsqaks.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hdciekzt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrntmwz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnbumvo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2irnlwihe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2icckoser.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2otgvllap.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwhfay.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqyckyb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jjadfcef.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwirgbqr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oniwriyp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gisushkm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvddei.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyvnbdt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auihkxsr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vonidupi.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpqvmng.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzxywcx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pawceeew.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzvdtdu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jemsjktk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ulznepsa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2attphuuc.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jwksaeli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfzrjiy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrdggoz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhsttib.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjemuzf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2teamshal.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhnjhti.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2odskxqxv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehuhuzpw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdwbtpf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwctzal.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbwbnbf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsghatl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dksddavq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2stcktxaf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pklwsmvm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzjmwai.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcycpdju.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qxonmquf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2otnmxxhm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyhcqyd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2pudkqear.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwusltx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2muqveaoc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmjsagd.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2resjxvdp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiokszq.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxhcpaa.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdvmgou.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdzqhkv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2lndpraef.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crziasaa.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zucjrbmy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2axtnpnff.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdzetpu.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzeskoq.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2erkgcbix.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxascqi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2aevgvhyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqplhsh.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2diumbjgi.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqgngyx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwsvjfs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnwxhtb.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hiavbsqf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyamgewx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2mseittci.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrlzukk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrrhesa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2psjgvktj.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ephaztuz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmusixnh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvswahy.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yeayaikx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxrlbvd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yleltbeu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zxayxtna.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jdftvcrj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ukssfxgp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbvycsh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2aegmiwne.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhxzoou.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kniespck.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjfgmxx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogedceqo.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2knexjxfn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlboqwot.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvvdiqc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrhrpdq.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrwakaz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnximwbl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmghwsn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2crnsubqh.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2srlsijfh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtuwdcz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asdjxanc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuuybtj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqnzdro.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqvnyex.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2flcdlfbd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qyedkgqt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yufhzlni.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjrwuea.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcatkkml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mstrtxei.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2yaapbhju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlqsger.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpsltv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2bopfyujh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xorlwpxz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2lstillkj.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymefrrqf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfjesra.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlgblyt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tujtnbob.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2blmvblcb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2giiimhrp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkekjrx.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pevhwemf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoysfgbb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avdknnev.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zuymjefi.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhoeeso.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsulrrp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2udyiqosm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nyurzpix.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyttadc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gcltluck.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nwozxlca.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqxpuqe.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcevpzeu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcabbase.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wciwtwcm.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ychhmfud.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huslxmgn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyeqyth.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgoyqrt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2acvikqjd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2eauokjcn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xuixxkaw.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxocaos.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2alrcuotn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2acrfmqma.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeqhhfq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeywtrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2omsullel.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lddtctmj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsdwkpn.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iklldfao.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2obtlgxrg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2kohbksrq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzzgsto.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdolsrx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqorfjx.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbbkfyz.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mupyialy.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtwpnrr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etljmojb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2maptibep.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2agllgstg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhhgcbe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgmocax.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfazcbc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2duwgwjgi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkjfnmw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2onfwbczv.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2gexcnzrk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2hizqlqgr.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qomhteui.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqdcfqh.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zsifsovv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmsmynf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxsskar.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutvowws.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gpderayt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsfdyvo.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2gcijohkk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvohhgd.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuwyups.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2cyedbdpq.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2heurchyc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2spvuzmgj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yibtxbvq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2saetqnuf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2infktqul.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrclyhm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nglbnorj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wzivyzga.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2elxxppkh.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wozyusbh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdgrnji.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2urlhlfnt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uapttarr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjlgcgh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmcjvw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2esocrjdj.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anvrtcto.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqfnccs.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2omghcrkd.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwdcsrl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlcufie.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hladyfec.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lniicuhv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpcaviq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyfkftc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbzcalf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gronblbt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbdzjun.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2txencuib.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ltteueyh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkkqeed.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2houbptvw.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2elmiotju.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwooptb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fifhaweg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqfsajo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nerohzym.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hhusgdyc.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoekpva.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lagzahiz.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2mckgrong.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vknmprld.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ifownlum.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2difjaczz.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jboqwtkx.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2xaioppxk.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoikakv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtkyifz.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2snhcyvvd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2szhvpyta.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdazgypw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xhagyrdh.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsvbtnh.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2kjljvduz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxjgabs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2foqqcmjx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2desmncdj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2kyobeedw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjioskd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2htdsdpcw.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkpohqp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2otawvcay.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2afhvlrhy.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaslutr.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbpbupj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ritxeszm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2daptyoot.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vfetpovn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwanvjl.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrcjioq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2imhakcfv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2piufnnbi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jwglciaw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hckmczwp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfxuzkz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2huhzgrwe.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tszxqvej.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfbobro.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrfwcqj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnydteqh.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bevpjoxb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2unxtdcdp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeqredv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkdhcdp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsxirqv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbkeerb.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uajkqdns.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuhitgu.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwxsvge.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2csrpnekv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2npmllmgt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbfrttc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yclhezgx.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mcifglcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfffljpt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnuemiw.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2mcktmock.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvrjemm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2goagorhe.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnywtxhd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2braywkze.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sezfhhcx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2aionhzlh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuhdhfk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzduhhx.html


<!-- 参考信息 -->