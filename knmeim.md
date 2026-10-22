代发 wailian999

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2teinrxiq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxnkant.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2upgbqsdc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzshwsy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qedzlgxg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwqmdgd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bashrwij.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2urbsdnxe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2weqkwoco.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xetgyvtv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcszxybj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2chjfmihl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmvnbsn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgepmgw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeskuui.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2swszmuxr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoeryet.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrtwhmt.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqknurc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfibzvhw.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnxzger.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyamvuy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpmwqvi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrbsbci.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsxutzy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynflfwob.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyrxwpq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuvuybs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiyxest.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrimqtaq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfrifxf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyhnydl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2noslgilp.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbbgek.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ramrzyfh.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqoabay.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfuwdxw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2izlcxdpg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2twccofkx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2shxqkfcd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxvnmlg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrflnbk.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2qndljifq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpprwzje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2geikdnlr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtkxhkd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2epytqptp.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mflycgtl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsuwxmw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxdxkvw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqrtogi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lwijrgri.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nswlhqly.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hshhowcc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfyqdke.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwsbznz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wesrjxhx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2woabzmqu.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bosqdbrv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvgxnnf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2uztzcjmq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2omgkuwaa.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2glctquhe.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfnmbaw.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnvfrky.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2dslyqiwt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwhnjoh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2upahvycg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2safxrbuv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqapbuas.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2corbtsnz.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjbhkrt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2faizijpw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dfspwequ.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyskexe.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyztzhj.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqinskp.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwihvvm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxzacfh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dzngkiso.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnhezqt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwhduwm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeebfts.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sixnddmb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ammictrn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqesquy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwwnhzw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xldfpkep.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsyomgc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eirvhlqi.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdsdoui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdouasn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hvobxfpf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xldsyafk.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2diixcqqv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2wxoevwrf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqarixd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeuaqur.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxvzgix.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcweubsr.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2veubjpiv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwjlmky.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2spvzkocb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2muaexsts.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fmomftzx.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzioqayd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2cbynhury.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrmjgli.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwooarm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wqatjvkd.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpdfwrl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2olhedahl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxbssny.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpiesbn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgvsaef.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2azwdujrn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2myscmwoy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmlkuwr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hesgtdeb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaewixt.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2izfeudcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfagfefi.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvoeevz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhhkyvc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zihsdclk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaqbjya.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmqkipo.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnsxiyb.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hszygrar.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfqrmdj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbpqezx.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpljyea.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrvdgxh.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2clegmngs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgtmihi.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gobcuxer.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsmqmfx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gtirshyo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2upginwtl.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxmhocv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2krtqhdkg.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vpejmmrr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmckghf.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2refwkdxu.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbomqez.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtbnqtw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vchnwbmm.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxzoujy.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2zvziygtu.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utlxxuqg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2urzyccvi.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqzdozl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjrlifh.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzdxeqq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yemvkzsk.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rpabiuwp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mupqflhf.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrdqksh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pglmqdyl.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2uiswslny.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jvesyxho.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsppjrp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wncxdzjx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yuylnixw.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrisqdec.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfmoibd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpcqgao.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2endtiltg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaxbrwg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyaioxy.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mieycedj.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyhksnm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fasbucju.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqnuodc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyrjbfe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2invxuciv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2djnczhzh.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaledjz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzjypyr.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfdmzvw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkcgzjj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2pogzkeal.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2rceqzftt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gljuikfr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uodfziwu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ljndarpy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaeekmp.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2waohaisf.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyallqhg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jiszkbha.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgykrvww.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qaajxuvz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wkegknou.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2esrvxxye.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxddkik.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wolgcbtr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhptzvj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2npefcezh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nbacobkp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qsewqedd.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2snlipevq.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqrboae.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxtjawu.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgvyfpf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlnvbfa.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jypymxwp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2opqfqslf.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bqowtxvw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2asqezjee.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdfgccf.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2reegjrzv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqkveli.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvrrzqj.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aykfanra.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlnhasf.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sguwuolt.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzpqkpz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbcjbtx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyzgnqv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gnefpvif.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2erqyitzl.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2humnxoyz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnotdym.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2udsqgsnj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwqemrw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpxykzc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxctqrp.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2wzckgqgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhpfddj.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhjnlop.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpdaomr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lagvzsct.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iewocfwz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrsmdiz.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ztidgzbt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtzzhth.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vhojowhs.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dkibrbky.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgapope.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkstsdp.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2rokvlqzy.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2amkomuvr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjmpeis.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2reihdbud.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2cqinlrwt.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wzidnerh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2czcfsppj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2smwtgbvw.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2petqhrmv.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxkofso.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vplryuow.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2crwmfftv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2zssjogvo.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsycejq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2slhbeywb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2iqroevag.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvvvpon.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gagodqjq.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcltxmd.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2eiawuizh.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2xwshhprc.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhztwmq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iokevdiz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqymyme.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsoxalg.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxxuqze.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjqgurr.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewovnuxl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqaeugo.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2yfclwudj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwhiyfi.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2loamimlm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnbgohm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaskqfb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vqktymnm.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2djkxqlmm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbhqfqo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2doxqwmzi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfsrpoc.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2thxtbzrr.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vosqgyhv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrhywuo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wxslhfnp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2enmvgumn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgztozl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2goxvpecq.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqkfdur.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaiovnz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zgecrirq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plesgijh.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pujntsvf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ordyakgx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdbxkwa.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kqytmzmv.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iodmobgp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jarogvsz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsfqask.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wleukpsk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpibbls.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzdfqgs.html


<!-- 参考信息 -->