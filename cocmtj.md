代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcpdkbg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhtsxgc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xiezcudy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnxqvjq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2afpkipdx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2odoxskmw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bokfzwmr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvthinv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpgxhym.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iljhftlv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcduvla.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzezukn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzudxav.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkymcumh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2codkqjgb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwfbkta.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpqsnsf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjpbqvz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpjckef.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uewcgtkl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2shodqohk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wthusekv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqytaduo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjipxbb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2brbdbbbz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gemxnrml.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2flbyjinu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcljmej.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2venxmxft.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2emrpmqnm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqzjxcf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxpoepq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vqexjjan.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjrzigm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbamfwov.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bekmwdqu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvqcrih.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pslsizxl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kywcsexq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtjzkxa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvcwfcw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2osbkqukc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtolgcq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwldnr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhhgkno.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2luzsknak.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2suvdmtdn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcbbgkp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnikqmwr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2shvyedpb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hixilvan.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrndzwh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrngpok.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2axylnhvk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfvmspl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvroeyf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zghpgdry.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmbnalb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uyklcowk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnhcsqd.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxhmlmi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ortyzkpu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnhnlbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmodhusy.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xzneefnb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2avryeplw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdacqbn.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2janyolkh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzraavrm.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyliatwp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2viwdqilv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2zujpfagn.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2cttwykqx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2myqumsxk.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwsvoli.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eekhotos.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyakaqf.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2olyswkve.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uagbahlb.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqlruxf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upiuncqe.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzifvtz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwxxvxq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnsjdwy.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrzzcwg.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2soeqnzfb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsdtzgw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yjusuytn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vflmuhmn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2egyxnrof.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfboaiby.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpprmdo.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcbylux.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddskeue.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpixsan.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpxlaoq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hhuecloh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2pimuguvq.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kobrfain.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qicwfnci.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwlvrdj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iutvewjl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2klapwlsv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmfhlrl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsktvnt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fijguhnn.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiwhofw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nddloqzi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nshnrqyr.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiicqgwp.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2emvbcvsb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rutqheac.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzkkrve.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkyagvx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhgfbzk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzroyjs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkwvsqo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2huvchcwh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyiqpcwd.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjlrzsi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rmttwwcj.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pokzlvmr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlegcsid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2codbvbsa.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdlixmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zivxdfpt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2eraoelky.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzqhrir.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhwruhg.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhqygqq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dypyyvmt.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvpckjt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mscvcryj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tctagyqz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkhloye.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uanyiqzu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jetvfqio.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhskdtlm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukudjqcn.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2slesjfrn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qtphmedo.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eirekzeq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nixxuhxd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pncscyih.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghuqtl.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzoldona.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gunvhavs.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwglkpq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbuhyxb.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdziutu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnqlmem.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwqsjnn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrpvpjt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhovfnco.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lzndffkn.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2llvyuqpi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2afnshryx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2enoetaph.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtlwkba.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyhifhy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2swkibsyl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdxiayn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vapxeehy.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhtaxbi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvcqefq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwdkwlt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvfvxij.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiznxgl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfucjtzz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciovqixm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xajdphlm.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvqndxz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnjuyrz.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2bycpcrau.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrjgbir.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lsemmcju.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwjyxsm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoerajv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzetcll.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2zuiojhbv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crcaarel.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbokgzqc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2poezgnxq.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvhzqqi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bopsucje.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2eurnhilh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2phyvkess.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aegxqymy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dybjewok.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nojqwlej.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2juetrgws.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbfugki.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzomiosm.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjpnmbb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pytwqomp.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lloyvema.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmwhvsi.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaucwxr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ickommvv.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2vddgwdyd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkeyqmv.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhhvztg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2chlzifdy.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdrmpqr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyigkog.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsjrgne.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2wohxxpyg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obiwidof.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bcizercu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2perwsgcb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bftzwgrp.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2egltgpwa.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2hngwbvtx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ushvvedv.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fnerspfi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtgoztq.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnzjvta.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vnokbeey.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2omlwdaoq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfpjjuq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2srnkstuk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fskzmysm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqithl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jurohtkq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dsojyzir.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlcwhte.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzbaxzi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvxjjiu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2waufkbgq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvcwmyu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfkldrc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2nrplugum.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jixhtxfh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfhvkms.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etkdtbtj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2syillplv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfepmqy.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzzqqhz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agmmnptt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2glnnnhgl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnkhkuz.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqdzxei.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2bmykkboa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwrklhk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rcijvnlh.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2velntkbj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpcsxuh.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdtpeju.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvfaugs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkxmvhg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgjpmqp.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrhqgqq.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2yezgpczm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2seuxbjar.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoryilc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcsgifm.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2reykhfhk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gupqsybo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgfkkwl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfggcol.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2eftlizgs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlpjyjj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nllcbgfv.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2zohqnhdg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuvkzas.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqtloaw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2onapjiwd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bsneoxeh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcltmjyl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kaknieuj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzfwile.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dljstnxe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qemmwbtl.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrzmewb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmwlyi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2palpjmka.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gwggwhvd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xpallrkd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2izqozeft.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2udwyydsa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfhtvjr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2znvorypq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqskcgx.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmqpshb.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcydfyn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjcgcfi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpvlbiz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewzrsp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gadmbzir.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2oelouiil.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxwwupo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aafbgnfq.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ertmfymb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzhbxfr.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxtgqvh.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcidecm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjypbvlw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mwddrihc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmxycut.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kektyxih.html


<!-- 参考信息 -->