代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2offwkfwv.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqeuhvi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzyhsox.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fpduwnit.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpnfzow.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdkstlq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vhttvcsz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uattnpct.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iggvgsxc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmfjqpz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbuying.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnbmymi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcnfdgn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhtbdsh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxipnba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzapaoix.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnvqumc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgyodvo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdurzkpw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfaoyfj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwljrulv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmhnakq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeltmmg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ibquaapj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xszzjffh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdscxvf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhcmylp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjpgoub.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2sarfmfeo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2flqabafp.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfsqmps.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxwcsyq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bhottpqi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnauevd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmbqoxr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyokrkww.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhmydeq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2telkayly.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2auhhucuf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2abegtkkn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzubpbjy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcsgsrn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2snvmjhdu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgtjziz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qabkufke.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sodellsg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kufqbpmf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkxokuw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhlmtog.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2inwtfmsl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiuhkdp.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qttghggp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ztopvrum.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjaqzjmt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhitgge.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbizoddx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sflrdovy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2fabgjhqb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpzfmtx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qyinfhdk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrtbrvm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgfytsp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxsjfpt.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ocemcdzs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2numurltd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtruomp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvuljfp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtfejqb.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjwlqmx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvnpsjj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xopvzqry.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2shtegssx.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aubqluri.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tthhmtas.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvzhtim.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2letvejze.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhitbyp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfvwgnk.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2icpkoizw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2ommbrrgq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjnlgbi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2idayhggr.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2emcndlkx.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xckcpmgn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lteabhdy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2xugchonp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hflldtxu.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhsrcfb.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgixhywc.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjlctdz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2glcdddce.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmztfxb.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhftammv.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwjrdwx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdrclgm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2shgxiuss.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vzahgnuv.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zkitugxn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2barnbfag.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzxwusr.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdyrhkf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgmblqo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsgxsgg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2huzlmhek.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2twclrkvg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyalsxy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkxcdet.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrautir.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2oxouxjar.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uebaqnno.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkogahtg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqchkbg.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoygekv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efzknbux.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2erhfyjbz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfctevdw.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsmlcdk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emxgnivx.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtvmchx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfybxodb.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcsvtbv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaeodoa.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vajanpac.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnlvnlf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mskunazx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2aylrhbxv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tasyxnav.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkxghsr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jganykxm.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuwqqlv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpzxspj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnltmavm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgicaxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnkqnuq.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmuplzh.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tljsabcw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pffhmkbn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2hmysmzhw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdieftl.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huwhlnmf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbogtxu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wznogouc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2iuneqpez.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2thqncmnb.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqmzvas.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfjigpu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlouamek.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyviehfu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jokypxpx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2quzctqul.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2aswqebad.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpfmnah.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtnlufy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2viybarra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2awkjwpog.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hncgfffi.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvzfkbh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxityncv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbbfsfh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nebzpies.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2doydjpic.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vznqwltn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaphmzs.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rwoluntc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzugftw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfofpfb.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqlelmg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uokjweuu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2smocjqlc.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wymrffer.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsbxmov.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmygvipf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mapqzxfg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pytamiwk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jruisxhr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2guvzdztd.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2urdcxcgl.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvenkniq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzclakmq.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgegynpu.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgmrkmk.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2odrimdlk.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkphcyda.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcdjsog.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rshcdfbb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wiktiiuf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjsbzcg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgztzyy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiobivm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbctryy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqgciue.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2enswaiyl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2zidnezym.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2oilxfboh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2wawmtgrv.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbxzwwx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzexxvqf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2byihzprl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2mckyspxi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwpzfcr.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tshawrxu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiamvbh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aimtufgj.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dausfzbb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gsewprot.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtibhrl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpjqrnb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwueoho.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kearlxfk.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqoywvy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2sgariiid.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nidrqeew.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsffdapl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yomerkvc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2sfebtcpi.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jyliyhqs.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ueitrcuu.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxdhleb.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpvbcyt.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmvypcn.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtquwhk.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2umkfvmng.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrqkurl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyhztgh.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmtbnpe.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2lwybpudt.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2daifqhpa.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsuzody.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2hlykeeyo.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaxhczx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzktqfl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpaqhdnu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zicoyxwf.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtpuyhl.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhywpfl.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hqisqlwb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2heczunrb.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhhwwow.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2terdxfyn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsfcavd.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2cypibkjh.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrvfqyk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxkswkq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvxwpcw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nivvalnn.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwjakpy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2puhoytbh.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2xgznkttt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuhxdhp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zzitrwos.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxaznvr.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2azpvzzuo.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyamesm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvyvkwq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2poblwycm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vygfdbbo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ssblnmch.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2qywvtftf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2clwtpglq.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vcojabed.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2buvpcfrx.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2roaaboup.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqslulc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jviahuwh.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2huykyjct.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eisoqieg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2igkrdotk.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbfaxdl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2pecrqvng.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xvczxtfq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdknuji.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqlbvvv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xbravrzc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukclryau.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ldttvtuf.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2ndehhrgj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2enymagfx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2olbplhmk.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2xhayqwrj.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiftaig.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2aldietub.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2eefuzzrs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwztgtf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfoyqki.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfyquan.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2njuepzsi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdtrxao.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2filbtjnc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylytklui.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nyasrzed.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dctqnobt.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2avgaadta.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjbohmv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2jebhovbm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2plannuck.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtztopr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnkjagp.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvjojjr.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hnupuslf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymauowwp.html


<!-- 参考信息 -->