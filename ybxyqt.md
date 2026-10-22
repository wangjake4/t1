代发 wailian999

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdicwsf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zexwrbfs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxexfoe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyjhsdy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oezpaxkc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrphzuk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nofznvwd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ngagifsg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ckriwddz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zylsqwem.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqnttvs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlzohom.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiqjdmf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkwmsag.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxjyuko.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2npudfzpm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xguqcknz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2awuvkrbj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fphrmqyj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcnwipp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uqasmwsx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2damiytiz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lzytnreb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fldbyxxw.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqdrvgq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibncdovx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzttsdrm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2coxsyqef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmppwnw.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tubsacuu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnufvct.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvwtbwd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfyrvmi.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2njugwars.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmofwesq.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mxijwrsd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sedwlhpq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpazshwa.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiysjoi.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjdsrrb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tczqceii.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqeyssj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqbbrok.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2izqsfmtg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgernkbe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjpaecv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dezbaywb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzgmfxd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tttfopgt.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uizjfaxr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmqgchi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcorhqol.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfzalqv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xziluvvo.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwwupfe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmrkqsz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwdkrxt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqsaadf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrohaqi.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2izzgattq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2evsaisnk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvfseac.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcvyrfk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgnsbrl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnomigv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2lirdutjf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2cicrslav.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxhggjz.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqwwknu.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdwmxwp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hozhrlkn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiqeeyj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfpozvx.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2lllfkiua.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2rugyjyxv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tzigfqft.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaxwtka.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ryszmajg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgyqltk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2siazsyhe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2toryvlju.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgywylk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycabfkar.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbywthz.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lirxurdn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbzhhuf.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cpctpchu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiifrlo.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tkidqait.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2naaotjap.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2roxxpkqt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsufipj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2pbokhneu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqusetqw.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoslfgw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aorbcnnz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2omcecqdy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjqxrbh.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxceajcm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixriuycf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2alahdsby.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrvgezj.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtdceay.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2qthbfwox.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuuosff.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2yupapcwv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anmczjad.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvdohyy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2edgqhswc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vdutwacj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcaoshu.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtxkwfu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xuaazbkx.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgwiump.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cubwxken.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdnctrk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhlbret.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awflzoli.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzgzusk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2gsquwibc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfbxtix.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2azfjkwtx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyflorj.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcctydm.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2uivoyebr.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjnaafn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ciujknwe.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfecljt.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpxfgqt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ofygoumg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbafxnm.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmiiagki.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jttrdjxv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiffckx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvofkcr.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2skhxaony.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2viohzjvn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbylufl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzeapcy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2asbpwmug.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mswqcane.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhaaczr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2paeyutwi.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nczgfrdq.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2mzdsaznt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuspgha.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlxlzoe.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2blwclqpj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tebpcuth.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2rewrypdq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qhguqbbi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kshahjii.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yhetjcng.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aofrbigf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtvpmad.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhzlzsa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctiskjrq.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2zljxmqyq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2snnohilv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dzntjczl.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vomfjuvz.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2klacipyh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcijyddf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2equreyiz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpzqxck.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxzirun.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlgqttp.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdqbfoc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfjedyp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2htguhcje.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zitdfxdz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fmuqmdbm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2poetgvwv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rydzlflf.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbcdlml.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2eekcdzkr.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xubnqlrh.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2htegnfvu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkocjbb.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzszwvse.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvfgylr.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zimlqtso.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzelnjrw.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsqgkow.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmfthlo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuwehva.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flyqwixr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbjykgr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2sxawtjha.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzwcoye.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgkmqxd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lruyrguo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdfypde.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2invmkrrt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqqpagx.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkgmggy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvrndlm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfjgwmv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpkmkqc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjwhlzt.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2agalsrqk.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxxoede.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2imxcshwv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgafvef.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvhwegz.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2msafrafq.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwohgqi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhebirw.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lspvjvod.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2byxpkjui.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzwntud.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxwjqgq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2frnencmm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tucsvkkh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2ezanzpvd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeqvdur.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gragdzqk.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqgkhys.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzfxuvp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuamygk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2afeboodd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gaownulf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eedqnpge.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2kinwkchd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2njndsrlw.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgjuhci.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsllidf.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2llwsjnxx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpdcfke.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrwvpej.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eydiaxvx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ydixtdoa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbomgvo.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwhxsdi.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnjyurg.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvpllcu.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlasdpj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxgpyco.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmioxbt.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2acgcvqml.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2yheugjrz.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtyvmtl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyuxvrn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbzynbo.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dezcrjaf.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hycpqlzm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2elhdgzcq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2svanvsug.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2wlthydjq.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiropon.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbimquuu.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oteifjyy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjvyzz.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkpguii.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgbiido.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpmxrxw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2anjnaatv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2abspvhmp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pjljqekj.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2bfymdlee.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cucdxatv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ozltixqb.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hneqqzcl.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgxtybk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2solkghul.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxzgnjy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mozmgnpf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pirxriaz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2rldaxjrd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhicstu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxcwxns.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bficdbcn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkiwtfk.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2weratqam.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkpsats.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rrftuzwt.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbggmxs.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2xftesfce.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ueonjcvb.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrqlvji.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzwbtem.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgrbdev.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbgboam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlalxipr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2clqavsut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzuhlhn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvirvxu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoapxve.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsyynwt.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tratavwd.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgpnlqd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cschcnny.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2glmwgugi.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pigvcdhz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sacovfao.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtwccjy.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpahsixj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgllucl.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfajunt.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2euzqqcub.html


<!-- 参考信息 -->