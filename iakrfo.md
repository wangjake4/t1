代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiydcfq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwwukyt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcnlid.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2euscurlr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2totiytre.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cpokaott.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpkocxw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaoevbq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdpcnlb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2snildtej.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cobcsxxw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbwrvsn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zvndhynn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnylcrr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqudidrv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gjednqry.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iswscjdd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyzucyz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxhsicg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvkcjnr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxwgscj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbvurlu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqawiglb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2reyxbhtq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2phmkmmjw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bprcmwpu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuljuct.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkbgnnf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqqhqie.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjkkwia.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgniglxr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gajuexae.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymthyh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcfqvpm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjxkfrz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqhbgib.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2zovoeipg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwfllxc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cffapqgq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbugvuv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oqugsxbd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rotcueyo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wacezalh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoazocb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2papnuxzy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrskbkt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrrdynr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyfgifx.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2isjpotud.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrelreo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2erhpfyaf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qflaqyux.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhugmbd.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rmajnkzd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2iectvjlt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2budmorto.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnsyhuh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2szvqmnbf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2spaujlhs.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpbzulr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvynmcsh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rptyujer.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2faidtyjc.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhietcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2atsaqqif.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chmmrftz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmobllhi.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mizeoyjg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzjpjwk.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mianvnai.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wghtaogq.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2psxtzkto.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhywaxo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxgtkwc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzxviva.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cozcmfnn.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2abnjuiqq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbayjgqr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tspwyhir.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eslvxqbb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hxomvrop.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2htpsmuuj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlbunaq.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqkqhrh.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxfcetq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcofuepf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oldaqxzr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqlwwxr.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxdvwb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfxdwvw.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2ypirrujh.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyosllrt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcodqanb.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2yztvbtwd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2klmzkmyt.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nevbbjop.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmhngfh.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2nathvmoe.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyogexh.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2quqdjynr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfyvovl.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxdhlml.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzdegi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jesyfega.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfjsdgw.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqaquiv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfxmuid.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiqyhpg.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xxseoaie.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmlagjz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwqwuyz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2apkewrbp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kyytloii.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kohxqjpr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2efnaqwhs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgoqegf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2jdslrdrz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgchmsl.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlxyrhq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkphxqtf.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gesuesqg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqikjfva.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bflfhhnl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrlkcnj.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmwfruw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzhpnje.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjrytrx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwsczxs.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2qavypaym.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lppomctg.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hyftsilu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrpwbfh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sitapgvv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbdmwtv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awljdaba.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsqqtzw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2aafntecv.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhvknbz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2clanlbgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lukjranp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjfmmyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmxvawy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2keqxmvxo.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfwydpf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2sybiwciz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvhvuwc.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2suwspuhn.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnaaciq.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaowysi.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlkzsnj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgllppmi.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2levnklrs.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmtkre.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyqnhlb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unjupgoo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyuzdbg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2twzkngvl.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cgodrmhk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rclezvaa.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsukyar.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgobxts.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyiignl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ximqgfvc.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dxapvbjy.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrysbou.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nakywwij.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdytliv.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlsknce.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzxyyma.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lclqwgjd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kzblzzbr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oadcdtjw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedwdlt.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyfimka.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xioxpckl.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcjphwb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdisddr.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzvezdp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrcldco.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlzxasn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bciiucgu.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvnfjik.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zivpbrjf.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhgcexr.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzwyqhr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2orbbafnd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khojxbom.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2depyqock.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpwctlg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuqxpxa.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrknoyvz.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cypnelxo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsyjifm.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxumzusc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bskkcwko.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2rclnvdeo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2clnapeka.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qekckced.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2txevlbst.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxbcroy.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2telvnpim.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqmzqmh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2nabxkzgi.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ustinwoh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orhaiztp.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2plgojzuh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfptqssi.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ioutmocn.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzkpvpk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsgixfl.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prfyhxkw.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2clqxlvxr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2ncijqmmo.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsywnkn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfimckn.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hocvwybi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2lasnagfh.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdtlsaj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nmunimjz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhclohsr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxselvbz.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhzywjy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2usyjkfmg.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxgfmsk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzqiqwq.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvpmtpn.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqaoaif.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhjwhdm.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqdqpis.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmzszfr.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqatghn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2itkcdbmb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcaocii.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2saqbimtq.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2uottaqsc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vrufkfez.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2owjjmmiu.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2izqberwx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tddobfrf.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rjluwggg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2efaurgib.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdimsqcg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jymgwfoh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jijctsrd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2bzksmszx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbxcmah.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oulimriv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzdsdbg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2smilvdkz.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxfxnpb.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoissnv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uruaoecj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zdriugii.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdqyjhy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqakddm.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zizgkftl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvwlnfd.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdsxjan.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2uuriedvy.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdenuzl.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2aukypine.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uagugwhq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxvrrfx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdsgbak.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2matibjfg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkmyvlz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2udfdylde.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2quujbogd.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjowxbg.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2piutlgdi.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2katqdigj.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxihjqcp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqotgsd.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnzeoor.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpflzgza.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2scmljilz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2luyoqyhb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwmsptj.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xiovnwzz.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbwxmvj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzwmszr.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ounpkuwp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glqljlzw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2dujhrgre.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnyehbp.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcyiupm.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2duptejbp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghbdkk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyonpqcs.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwsowsj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgcfjmn.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fskgwxdm.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoxonmr.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjxdgef.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjxdbyc.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebobhtiq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylffmgfm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfjomct.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjabdta.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2njqohdcj.html


<!-- 参考信息 -->