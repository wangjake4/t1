代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaodrqcz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhcodmj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2niojgmpn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtmnpal.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpfczxo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2arnzanub.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bijlsizo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2omaersyr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vsldqcvq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhstvnu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bsafexri.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjpiftg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwinxsm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzzgoui.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfpyepm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2euxdikhs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2odtlcwzn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmppenqj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bncuxrft.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaiiqbd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhyaaew.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhvxedi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxemdqw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uradcamm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hstaqgvd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxvgwpn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnsroor.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2azgyyroz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdtmotk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qanotjbg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2toekvzkt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatdgrgy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlxenbd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuaergb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2slmztazs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpaqjrs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdtspnmc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyommdf.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqgptnk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcxbyqo.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvqrkqr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sikkpppw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrmgorv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoxsptk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxysaap.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaijgla.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2azpywswt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wkreyvnd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bscxpvib.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2feeujfaw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhftjon.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjndlxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2njqiphjl.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2pksfaskf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsktltq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrucdnde.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgwwkwj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xipeglug.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfrcjsv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdwgvxx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2foqjqeot.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbaalbl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgkjiqt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2dlleldcx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lskkmckk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uazijwgu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2noymypnx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjypqjvg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2apkariss.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmzylpn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtsehpa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecptnivw.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkqimxk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2corobhiv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmiwzqx.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2leszimrw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuwiuuv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2vizgpacp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaknfxo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2leyocsxf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rwczdxmf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdjxgto.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvvbcs.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrcpdim.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpsvnhm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2eaolepvs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzkksso.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyxijjm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefptcio.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2srmpszky.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2orreygpg.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phwwgxlm.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbzaaoa.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbdmsbu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdhjlhw.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zepvkwcm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqrxyly.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxnaqnl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvqxrgo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrpckie.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpdvsti.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyopblvp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdtzuvw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlqrbou.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sgulflmf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjubqfjt.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2icdnozcy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnfmajl.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2efrcuppl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skjrgvoo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqjyxjr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2keedtxxx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjtsnaf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnpejlb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlomblr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzafklkd.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2yxitabgo.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nehvebxb.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2dlosearc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwttsiyv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsasgif.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xiigyzne.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsblwvfi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgvdthr.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzvonvk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2whsbdndy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwboncwx.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wctzyezk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxghmjmv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkowtvr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2afzlytat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqafmvg.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuzinqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwktudt.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoysdfq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgfufzi.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gypygydc.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2siqzlqgg.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjucygri.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxnmarr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrjsodk.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiboaop.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2paehiwgy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2btdlnnnn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afcshnla.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfhmvwk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2expovrtu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmodixno.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yldhrfnh.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvyupza.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkgcphk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uigyepzy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsglibk.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pritmebi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rzacedhy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gynproum.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2gueaepex.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfwfhuq.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmjhyla.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkbnyrr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmlhoqp.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqkvwbp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aafbxmjg.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yppitacq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgizjxd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2drcjfgtu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2brbxueid.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmgxcuea.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnkgfcm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cijwqrnq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xayqaucz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvyagef.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpkutyk.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2auovcuqa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeujrnq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vawzktwv.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tybpbeth.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbubjnkm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2skogydgs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wrahdlcz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyvnklr.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2hveyxlww.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2etnkeyqc.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hthwalzf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhaekyty.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpmvatf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlpagdg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2srpuhzdn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zduyudln.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrgjvsw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dawxyvpz.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2mobxoyuk.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhrrnmd.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkzubck.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfgwayd.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtlfltg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfmtxfn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnlmpt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqebvwgv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvoepkc.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrsipcf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxqsrmo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpxfssr.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcnpfxd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vycaiqhh.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2xnymvfls.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqcjrtz.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pgathzzl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2djyinyup.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2emlbxflw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rujgbjdk.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gagwirtk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dghmgskt.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tyenihnz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnfatka.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkbhmqo.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2misgowzf.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvxgftv.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcwjoyg.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2otebgqnr.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ymknypeu.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwbtjsz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuncelu.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2glaedirb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuqomcp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xcscyecy.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgxwwus.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xlszigib.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2pdomkirs.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2brszbyfi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2yktwezfi.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcllreq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jnreakkx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2azstlktq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbmkzcc.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtxdhrz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ykozrnuy.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yidoizbe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgnhtc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfgefbh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2inogvgci.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiikzlv.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkgscqz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtctfyq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbntltp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtcazuh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lvohbmti.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2fztpsrnb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vszayayw.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsthogv.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2invveorm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmzlmks.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2vujpkhsi.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgymtopm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2xknkwhcm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hruunlxi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2lphgfskf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2xpibhdcf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2grfgxhws.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdblydw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpmhuyx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxdkzqs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qujeplgg.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjoeeso.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2damjeavb.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2vihfaavh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbgwvlv.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvnfvmz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2cciviixf.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oyitexrz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvtrtot.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2yuitrvkz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2lqspghav.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyrdthn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcajyfp.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcjrqzn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrcxpko.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2hagbmwck.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2cxksttxo.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2laghtgka.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xujszobz.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kocglzrm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbghqzl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhghihlt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2erhlivrt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oioafvtf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbrzrt.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaqexla.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2zizvfvjd.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpwyxpm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2erdlkbzh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtaocge.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2llxvutre.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ipoxnwnz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2znzlyvdp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmpbvrw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fuykfodx.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkfacq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2gyowvffz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhbxadd.html


<!-- 参考信息 -->