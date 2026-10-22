代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2emvuocmo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkvphiy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjxydqc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tphfiwqs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtecbmmw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnrzxyi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yixpuiaj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wstetilf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqokinda.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2npyvrfmo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgorpkyl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2npokhtxn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkybdyn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfkrgkb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbzaaea.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2upbzrxhn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2puqgtvoo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2taybsmvw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvneeel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiydzbs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eptkdrkv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrfzect.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ikupdhbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mknfruft.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2shxdcnyi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2oguehguw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abluzxrq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eydhqwor.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zswcowhw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxehhzbd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2icylutvj.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgouxcb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrrmcbw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxrfnsy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2isgdylzl.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kcglhcsw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgrddyc.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnhvsth.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqetgxyv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjiiboj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhapeah.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfykyyo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2poqyodwz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2asneejvk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjmlqy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxhijmc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2grjqatoo.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2avdyzloe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkvtibx.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsryvcz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrlacqc.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqracmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zldesvwo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhbfjcj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnaxdaz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzfcemn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbxzdr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbtxieo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfcjgdz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlghkec.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2teawsnkr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsevskk.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnepkju.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2aktcmftm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqqgjbh.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pifaahln.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqqfuwk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2woveezvn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yajledno.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2stjazfgq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2otevmxzl.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmuxkpw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tboqoekm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jondukak.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2yaapmxdk.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbrekdf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiopqrq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnlsktn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2arvdjpuu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2miwveaan.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gewizunr.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yeetmrfz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnqngvs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rcomxczh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvgbzpb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhqrppn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iouexklj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcqisaq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdaqnpk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwlqgdj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhvurnc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2rateacao.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yubdfqxv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2axfelpyo.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ralvzlii.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiqfhom.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2shrgipip.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jidihntz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2onrmfnnv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxttidcb.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqcvden.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrxwiqu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsexwxkk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjbpzws.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2opnnardz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpvdwjv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2djxyyykm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyfcwbx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2btiemozw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2csoavtiu.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdtlwoj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2odfxpney.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfirmrhg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwrkezu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdychbo.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgrfdcp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2omsbtjgs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbfwawt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xonzzayo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmaoepv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2idyslcwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhbedce.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2uodpizod.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfmmzbt.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2oipzzkjh.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtfmmru.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmiocts.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqmwfpp.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbthjwi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrqaipu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlymeqr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwjusip.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kczbivtr.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfctyvt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brwwpboy.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrehsmf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwsvfjr.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2koehfllw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwqrrex.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfikwvn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjzfkma.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzcexmt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iawqhzrz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgaydks.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ynazoyek.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2txyqyqtv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmulbnb.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlrwxjh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdabmij.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zllwqugl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2taqlcecq.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcziobf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fvitwfec.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wjddcqft.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqixfuu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qluwmqkm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cptkaagr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnptmgi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mupyfass.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfluaxlm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrfdaoh.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdryajd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2laipdoht.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrwemet.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2genidyfd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdyxolh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjznykoi.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mgretvly.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgotrtcz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2tifsduvw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfssiqx.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwpsjbk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fyscrmcu.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfuljzx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2euuwvuxm.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkhjata.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbdqxcp.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrdmjyx.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xytbognq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zagqudme.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbmzglt.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwagrws.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ssafixym.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxawbml.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thazdsxm.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dokxthdd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ontjglpa.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ouozuetn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhupqnnq.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2faxmprss.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yketixvc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bitxqoow.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdfewzl.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmeipcy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2vtiqnznm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjgfamf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqfthat.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqmfosx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpmhabi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dctuqsfn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdcolez.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbevjze.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuiwuvx.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kaibmgja.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ullusbsl.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vituwwut.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jewdsfyk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvdxojd.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkwfedg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpmohyy.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdujvge.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfwemzj.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2upmqjlcr.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsaokfc.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2naxzubhl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2amnjprxv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2srovfeat.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pqksskcp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kazsfsbr.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnkdbaq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kewezdqc.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbilahrp.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2stwnudcy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fezkfbtk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjyfmmh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuucnoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prxifiga.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ouavprhu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2aehkupyx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2fslybkow.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oebmprjz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcfidfm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2snenyvtw.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfctitj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnilqmkm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2pecrxwmh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbmxykw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2negchqmy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bomgxssp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2jyoqvicp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxcsdgw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuybqwvk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nivtfxsc.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2belzxbay.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xjifeymc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhiqhkz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtsoxvx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2svfylgby.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mujcrglq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kyczkorw.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2btmiodfj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfaruci.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2unbnapbw.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfbidxs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwxggza.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2tnahuqxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuvkvpb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wozaqxuv.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2itgdoyuh.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zspjnbki.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxkxesq.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrlyeht.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyhlpgc.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kynfxhmc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxokrvdi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nooidhtn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qssenjtv.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2runtjcfz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwlwamg.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2raibrvqw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuzwsmq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdikixl.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2afdeprtv.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuznfks.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiwwiej.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzolkrba.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2stuitcyv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxehyosg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sizczxqs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2omiqbrpk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2uotwieqr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgbrllk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2culynjay.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpcmgvx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tbanhoov.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gomlsvyy.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxxyqly.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhnjdwl.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nlehpaba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjapqghu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aenmqjce.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2flzrfrlm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2scuamtnx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2optdblpx.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2luwlyoux.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvypgwqh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcnspvs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrubbat.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zamzqpcp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqeoehb.html


<!-- 参考信息 -->