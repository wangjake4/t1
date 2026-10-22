代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzfedkf.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrmoedd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeriotwl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjivxek.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvddpcbb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfsdpzf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxriyzl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2awkbxqfq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlefecb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnerpmx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hweepdgl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jocvulsk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2snolebya.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdswgjnk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ticcqqfa.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsczvdt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrptxcw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxebmsga.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnzitfi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2szurqyhm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fypsamlj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkncujk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uisomelx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfdpeql.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ealsxfvq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtmyroa.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoeppjx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhseken.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fujsutpj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvwlmgx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jildptts.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbnkbhx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mckcrrni.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmnnafn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkbyxnh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpvrmin.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rnajpxkb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pktwrryb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tlisfxvp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eefannhf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjyzlts.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rercfomo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzuhxjg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2trzunlxk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skwvdmqc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sujyjvfx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2laiqofxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqncckoz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwqsfak.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlknazcj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2snwlngmx.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hkohibmn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yewwayil.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwwzbfo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwyvaxf.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2thhwmjeu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfrcnuj.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqwdqkc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbaxnbm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vafxrenw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qefpulop.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyfnzkx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctebqjlu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsaaenpm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2szviltpi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxychdt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pefgskdl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rzaxrasn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeaibus.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uygmhofe.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2evynahfb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2wrklffdx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqholvwk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfkbvpj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2etjhznbd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsxjqlx.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfmjsco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sujnlead.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2saiqaixj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwamfnej.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uoczgdrr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2tctjxvzb.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2caclqgns.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlirovwc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2osdptdug.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2nohkstdv.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2imqxoijn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybtvklr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqfngsl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2fatokkjm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gphlteot.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqcgkzj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtcqhfd.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2iexokepg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuatsit.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cudbanoc.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znvvxbjp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbsvwbu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2skmkjvmd.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wasbggzh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbxubzq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwsoffo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcglbku.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfyvrce.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhgyxbk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdmfmsl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtffglw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ashebhbg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvpxjix.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2plgmnqub.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2eriitwpl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2kniyttrf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrxcrgk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkbtxrs.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sghndffy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvstums.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2metzkudq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2madkxhyo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ltawhlgn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqohmhw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okwikusy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqcekxq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiymxmj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcpzbkp.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjmgaeh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhumhklm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2knezlciq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtnwmw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2gesxlzyo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ocauzqwm.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2crxfdkcw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2efdiidqx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyjsasd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgnbkvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arlzzjtg.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uopkafif.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zczzyxnk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfcvkst.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfadwmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thmxgdtq.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmwendk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcptjmdm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2abgowqua.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dshrekuh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wbczvhpk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxgbzxu.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxedvtcg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pugybxwd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xsidbohu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvpiitj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwtcojs.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpcvxnv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vplxzwbg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhxecls.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvmqkug.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mupjbxbs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dbngvvar.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njcfgvsp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdbqwad.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mjysqaza.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kefqtuyh.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vuysafjx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfhozxg.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtxchrt.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgxktcs.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcmidxo.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sevmwuyw.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucowkocf.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jsiwnukx.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtwurjb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2twpnlqpb.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2exnjigyo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxaobgm.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjrnang.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlckifr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyjujoz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxojpeh.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaimwdt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aohcvoee.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsnkajc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wctrbemc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgxvlmq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpoflxx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2njwozgpi.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeucboy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvzcuxt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2izloxqcs.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2csvifyoq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcspbjp.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ouseoeap.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdardtio.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcykrqt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtyeidg.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xcumpqrx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cidffvxg.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ryenpscy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuqpoks.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcputlc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgxttdb.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvsfleu.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsidtcah.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2uanqubyv.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2qexxoexg.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iejuziaq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxqfwyn.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxvflja.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuefyvj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvpisiw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkogzcma.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zufcpntq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgdbhzx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvfshni.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlakqvg.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpvgorj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqroiyb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrexgeq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjpeevw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bybdsrpo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2fdutqlcv.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yppxrvin.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azeadehj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlgswnn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jekffksc.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkomoqe.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2twndgfbi.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2umxdjzsl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwzxbbk.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2klstcugt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wgotdytv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2eocxayql.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pnowywve.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeyifvd.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcyvskg.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rftcgsgq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2knleyava.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2npdulpth.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgqekda.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2myevcywl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2guqxqlrw.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2muigazhl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvkkfhn.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oegbvtcs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oofmxmei.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vduzhvrf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2iabffpeh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqdpfym.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zqccdibr.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoifrjf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jktdvecv.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoxowvm.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvrvrxz.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoglopx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2mcffsdul.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzntgulb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2urxvodvt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2bcylfwep.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sumwbfiv.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2haeatpud.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tbryjlcb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzxuraz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkdured.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2evlxcyvf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jpignevf.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pydfuvkh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyirtfy.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmpahon.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuwjxsy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvrzfhj.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnrfanm.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoxeyvd.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsvachi.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cegqgbdj.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbdgsxm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2swqzkwdw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bocdqzyi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqciloh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrahxgo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdhdecr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2susqmcua.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtdlssw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxuzokd.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rctghwmu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpgxmec.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gojgnqzg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlbxlkn.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xydcespu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmozaua.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tajaplcz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgdlsqu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zwccvcns.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdfrldp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnmukpe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsigdsc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrajbzr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ottthnnu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxvegvb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2whjmmbua.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjkckgn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gawpwkzu.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2orougiys.html


<!-- 参考信息 -->