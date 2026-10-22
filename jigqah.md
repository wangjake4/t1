代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqjqgqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2purhwgrt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kefvxcox.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2htxgwcll.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikqpml.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2efuyodlf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjohzok.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2twphyvhq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntceapry.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2azxpfjbz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcmgnny.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbibiaqm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdnlufn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lurhwdtg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpjoazq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2esqyirdo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqmctov.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgkfrfb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tepxdiep.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nchhzbus.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kwujnadd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pegqmmkf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmndalo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxoofiwt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2djggtqff.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlekkif.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbzvfnn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2iigxvtgd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2renujczh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcymtxm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpvbzvh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2htpnnkae.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2izdalyso.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwodism.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2snqxvsjf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dwabtvqi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aahebqet.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mykxrppd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqfonhv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpvitcw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwcntqj.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqsuzzf.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2jazjdhuf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2remiapmi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bljbqrif.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwannff.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvesnplc.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwzmpug.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydpeqmy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjhtdqb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyqrofg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kuafkmnw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2llvcvvyb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeysolf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlxxros.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaxkswo.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2svysjxjx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ougpwfvu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2toyzpztz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyfzujj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2udlcvxqm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqaxxgn.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzywhjlh.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpnhfgm.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gahsypig.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pclrsalm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsxnrfz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeemafci.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2zbikcuvs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnyxkyg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tafogzhn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2necpjdyq.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwztgny.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uihxiuil.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzixpsm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmcqnhm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkknxbt.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvmjreu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjnfajl.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2umdksjfz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2alvecona.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gswfbqrz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuyllwj.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbmilqj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkowenz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2icndgtvw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwraads.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2aklbvajb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jlokrwal.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcoublk.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dphuowvg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbdofse.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrombod.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwkvfdf.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yziiexjy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2htlaolsi.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2csbuipsp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcqpgbz.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmshddw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrdpyf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqjosro.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epavuznc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2offrbifp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aezezrvr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2rafdeeet.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2anilkfvv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xulvztun.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2chtfsggn.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ozswvxat.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2odafftac.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pvofimib.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmtfgut.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrjfqfb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aggvcaxh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owsoviga.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfiuqeq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tdepvezt.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzuvuyz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxubjijw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skvphyyw.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2frdlnhin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmmzenx.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2reupyhri.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzugvhn.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2shcyqvnb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxekwrs.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcckfzeb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tstkrswt.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2tbirjunx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeyzwqt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsarqqw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmeunqz.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uytttjlv.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhfzske.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kldffzdd.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hycunzdn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mtteuxli.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvjajnf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2csqlgcdw.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zylvjgke.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sewuscod.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2koaiyygb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wqggnobm.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2aronxftv.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dccppstq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdkndig.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcwtgkl.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyjpwya.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaiiecd.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmclrkk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqdrifo.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2epkjuggb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vtmyxxtv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpuyazj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdyglph.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nijgydag.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpkaczb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrirdpc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hiewjyxm.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwtqyrr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpivwks.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmjmroz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxoumqh.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cxlmbsoc.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfmtjzm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2bobwbqvg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfdunmk.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpuvkzv.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2crjxuvwh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lellldak.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aljsxuol.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cmblrtoj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dauhxbnp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ityhutie.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqybbtl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2goclpexf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmvpflz.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyqefma.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2owaiivrg.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpciity.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlpwyzj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2fguplytc.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhhfcxe.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxdseuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzfvnyl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uaycfupj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2crozfybz.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yskvkvzj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zspyarqe.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xcioqoce.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zazhojnk.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2prdqufmw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2brbehrhf.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfhwcgj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2isyiojwb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2asuzlidk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bljtqott.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aclpcuca.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvxlaoo.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfxgnjb.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2clycvbuj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfyiitt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2haljuobg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jubcmcen.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwciveh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhnuexa.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlhoide.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2qjljwltp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2picuwoge.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ewezpuvu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zledhpvc.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bitkcifn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdmjirw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cowtvtiq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ursfexuq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2haruwgwf.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrizhmg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rizrmvzt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2kzobqedw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tewicejx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjlvnit.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjsobuj.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjnjkga.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wonwavbe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lazbmddd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrvqbsh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgxtvrn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaoniha.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeepupf.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2aknvssax.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqjjaxy.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpmynvs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrhlmzz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xflmaeww.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2woefohhe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtfgqli.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2grkgnzqb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpxhzwk.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2emkjdgyn.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cowighpc.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oapepbfm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhlmuwn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpwqkgw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2saxxpfhj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2epszdjhc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtirdag.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2voqbdooc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgryyupd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgbwvhw.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irgvosdp.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2skkhmtuw.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2shjijvtt.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqjjqpg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2skezshfy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzdpatl.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhsocqb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2nteisrcu.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2etpevshn.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2djmiywpj.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2doqdbhyi.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbaietc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2boortthg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlehbmdd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2llxzlxey.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxojsily.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2qexmxetv.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgngyit.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kddzrqdf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pginnfdj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhtroxc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2teboxrsq.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaqickn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfeymnn.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqlyaot.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrcopcd.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpokxnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kertzqrp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdieevqb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2atrkrfwf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqfazag.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxceiiz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cagrdwmz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2imowsyhp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhslkmw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eainpwvs.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2coqzdjgj.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2omfgfylo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgpjiyy.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nckujmub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogobbcjg.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2baouariq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2lazqgspw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlmigvj.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqvowoo.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wddvnnib.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2seephshj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtwzwjy.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2adgsliwp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbpkslu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2umtygwcc.html


<!-- 参考信息 -->