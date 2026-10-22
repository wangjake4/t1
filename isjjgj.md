代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqydhezz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacjqhwk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2opfdqijn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmmlwgv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzhhpu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yscbnpif.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoixkuvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdstyrr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaygauii.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxhlcwg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmkzhlm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvuiinw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2oitrwpyo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vmddyafe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpohpfmd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2prsjnskh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaezglu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nklzmisa.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2enrvhkdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xduazrrg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pisbfbdj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2grlnkrxa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpwuvye.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzckemhu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyjuhrv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sonudfga.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqxjflb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuacaogt.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wlggmhef.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2abdoyipp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuykyejt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2aicoloeu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybydhtub.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnmtuhn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvihdup.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbybhga.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2huacobff.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fliqkrdq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2obbmayev.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jsswvxst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oecffauo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdukjcni.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgnlqwu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gomppbaw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fptihglr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ichrjbau.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpjwoyp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pumtetln.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xniaiqsu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxebihf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rymgtxwu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wedaekjr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yytlwzae.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwccllo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpfedni.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okoqmnjq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfsmavi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxljrxjb.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nioaqjyp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmhofif.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jdovylez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyzmimt.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpmyidq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwibtbew.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdglzovo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vettabpc.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqwczty.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrlgrgz.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kslluiju.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyfaqhc.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gjduxpix.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kufswfhh.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbyyoym.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2azeegswi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fywfsvdv.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2seukkzca.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cquahavn.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvegnhp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2xggjozgd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2oscdfcup.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iavqysyh.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfpwbya.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kjffjlgc.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqlndyc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdhcwbr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjisarm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrfwscg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhcqufd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmucpyt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2nydtllpj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2welxtteb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2oaenapbn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ijktwzax.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrifbbd.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2auahkmzv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2shoujeqs.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvzodnq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wayjgsmv.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnzhhgt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsngydu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uiugdmqs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmffwsx.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2stpgxgex.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvoepkg.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2njmtxuao.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oosrxtuu.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tczyakqb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2slyvnvxg.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iyulgsxx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuooypf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jasvpreo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwykwbg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzclhlmu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwmhebw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyjgvyr.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2odzfmteq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjmtwqp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2xscvocvo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkorsrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohpxkfxh.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lisyabze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slrlxbqj.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtbhifd.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ogecguhu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2qlyrlckr.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2gstszsjh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2alqwixas.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvakfyzz.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2sebhcdht.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2isbjbwln.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpytciiy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkrkbpu.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuovsfs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sdakocwh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kebrvxbt.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzgokyc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaxkubk.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2crnpwmxj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqsyaus.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xanelwmv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbtbtvc.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkrjlul.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmkcigv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdhrezp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpvepvv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbplehg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2pothlsfw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhducviq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2qacogamb.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcikyeec.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cizcppbt.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uhucccxp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxydupge.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsnplis.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sebaztne.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cffsyghx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hncndvej.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpkvnes.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwczdngh.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeprfsf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvpshrx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2emcoaidb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2waeekeoc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2usowjalr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwehxstu.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbxgkua.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfzoyku.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2afwvolzt.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvnzfrp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2jkitizaw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnuedvq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvxqstf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wwijdrdz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2phujdscb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaidrem.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvszqjy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2paoofpzv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdgfoft.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfltymz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsbkfmo.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjbsuap.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2prjdtaij.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqlyrwb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiihleh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lysetacu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjrpbdj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jblpkrta.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdiftla.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnkkobg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfpssic.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trikdcxi.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2attognyf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wamkcdis.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gfylnirw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jgimaczf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ymerxora.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2mivbzbdc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwbtjso.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvbfrux.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlkpuxy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxruzdgh.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwjhidc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrpvhxf.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2linrpeys.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lndbsmgc.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mhotkyic.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nythlpop.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvnguln.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gzopnjfg.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gcovfmhj.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dwudwyih.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2reizsuyn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqbkdla.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2noayrnsm.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dendgvar.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lmttdcly.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mazxpccf.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcolehi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoevjdm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2coxjjjwh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpmdbu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnkhabz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcnbhoq.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prpkxdga.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxjvbua.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2jryavzrr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbdobta.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkbyzno.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2fethqfco.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xslumprs.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mlijvcyc.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsyskix.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmjdket.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzkmxrb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmdtcjb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tayfmyaa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fklymvhr.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbrsile.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjvyuiy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2phpnoyrn.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ioargubj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2galjrrhf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoelatd.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lgboedkk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkglexs.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpyejb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jheplqsy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2kecpskte.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2soqkgujd.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxicluwo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ksikvoix.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfliwbp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpauti.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2xeumtdag.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmywvgh.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjblmhp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2uazduwvl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjneymn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2creomfis.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmofdpie.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2aflhtsdf.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2khgsbfoi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2epftxfhi.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxbionq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxockqf.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2vcryvrqz.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2qklxjamn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgudzms.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2frxcaazq.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2blincdwr.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iitqauwp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oieojdof.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqtorsu.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2knnmxoff.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fyejxjgb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2itslwbxo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmvqprq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuepcve.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2wtconldc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqdavqq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vocyofwh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2caylbonr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfzjsdr.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nhepbrmq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jicnphae.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2shkjhfzq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwurdas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrgooir.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2njrvylqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnpjqxu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzmhgwp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2eacndwdj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlihjqbl.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwkgxuo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnymvjsp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wwydvbwk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxltarcb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzewtoy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfscbqig.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdogplt.html


<!-- 参考信息 -->