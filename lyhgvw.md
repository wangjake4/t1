代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2slktfkzl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlyxrzn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snechkds.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrhhnpc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbikqffp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdgwwms.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukafrjxr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jkohlxyc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwytdkvn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcnkcie.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2siqxrdtk.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2voefqzwb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cutxzopl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gamsvuhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobamijw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpifcxy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjgsxy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vscisuek.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aijiwovu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2onskdmmx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzjxljh.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yacuesna.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwyjphy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfkopta.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeaeqqp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqasrorr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kwibtxjl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gonhirtm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkpzugz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljiyqlxj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzoivta.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrjyfdl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cptzkufq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2blulmoaz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2cayywyrg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kecarjcq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2iljwdutq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2usdeyofb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpbwqfb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsifgdw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hodngoub.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiexdyj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bmriuulr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkdemeb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkhmbrf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qebmmebz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2noowmzyj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aeooovnd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2unesrxha.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnsvgrj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2igfywlmj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkclscys.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wbovjold.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhslnlu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmbdzfh.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzwbght.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzmuvkk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrjrofr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tgodccxm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2whrulgio.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjzrgna.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2snrjwmrw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hompirpx.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzbrlnm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrtavdx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2canjucvg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyozfcb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuebumec.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wobvoqyx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2blltbpjg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfzmtha.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtnwdtr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mglwuacg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2inplhfja.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2viepziem.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nymdmhqj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2adbnlrrn.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zuigwceg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2jvohgfeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylytiigu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuvonwl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgsdtyn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxpjexc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaqihdj.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqiuwto.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ornwfiqw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxeqojb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdooizky.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aseskejf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xikwthmh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oboqhlri.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrrvuob.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2mntfrzxk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsriuao.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2azzyswmn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vekcjoel.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxfglhm.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uryejixk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhrnrbq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2uszpaewn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpxxxku.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hjazgcus.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2gfezxizn.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcwyzdp.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrpjpwb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzqziqw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yctclyhy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2elmjjbly.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwtuznz.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzegtcl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyalwdx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjeplly.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvqhsws.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsosnnj.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2slwlatmk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaapigf.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eivdnzzf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjxyeoz.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2miodswus.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2glfvcqyr.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbbanod.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqubeyn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmifnjb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azhnlane.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qlplxnuk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhjmkdu.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmcgojy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmyoowx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxgfxmd.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2imvmxqcq.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2vkerbfau.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2swapajcj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaauyet.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fblxyzmi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hejfowoc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2opyeofaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnnahqv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdxkoir.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyosufaw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aygcuupn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfdeuzy.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2quocgztk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeyixwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfdopfu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzkrmsx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsfffab.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnyrwvu.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2avozfdml.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrortvo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwlboip.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbvgmkq.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlipmply.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2umudywvv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbsqmel.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxbpaqr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmbdmkr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtxjpbs.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmeykpl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypysiryc.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsesvzy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2isilfivx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uoccoahw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvuxzhi.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pghqyghe.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2njxusqad.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbefzcx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2biwcuyff.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lzipqcvb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2noebhrvp.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrlpjrg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlcjuen.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqtvxmo.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2opjwmkmh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2enyqjkxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qaumfavf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nurtjeei.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2roczecaw.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzjyrve.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpoholj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bompmhna.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jleqwacl.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhoyijz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtkpaur.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2candupvz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsdihxc.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdonhvm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hokoheyx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nlecfzad.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfamwfg.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhxoxib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uudrwrhj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2regnyktb.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjjsriy.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2msakvpxw.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hkutvibw.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2teyknknk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tboghrgq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ralvvkko.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mipblumt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2siscpwht.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfmariv.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pguhgpts.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzmxlla.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxubfzq.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oatziktr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wntfgwyk.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2moppvmqn.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuxccuw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqzxxid.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdlqfve.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxsybbr.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzqgtqq.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bacodyvy.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrqrxab.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwfereu.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mbseahpq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2qfppxnpt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wvubmzcg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yozsnqpf.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtheead.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2turdyyxp.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scttledi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jinnultz.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oekseplw.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfwyvgc.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tvznxdkd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjoxknv.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zptspfye.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnqpyuj.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbszajh.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2imhfzuie.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgcwzri.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2twugmyct.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2erjiamvg.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oilbvsqz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkorffet.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wgogzbfq.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2unrffcyn.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zyolkfhq.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfsryvb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwrcpif.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdapxqg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2tmimhtcm.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfekogfj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qutdyekq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dugxpisw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lmatedxi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zagskifr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2brsqfrnq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kdteuoqe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmlefpq.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yodpuzeq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqwxagi.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2abmqxysh.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbebyvre.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvcailu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wydytigz.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmwgtmq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpmnuqt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfjdcfy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtodfrb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqeuiwy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2auyoaonj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ykacconf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2holxxnhr.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uubetgou.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvbfele.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeuimrz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxjbloa.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxstcdny.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2uycgbruc.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwdolid.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqxevjy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aneeylhs.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaocfkx.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhuuksa.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtcxvfg.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaaomhx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxmweer.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgehqlx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2njcfiscb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tutmswvm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzsvmyf.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqebshw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2qsskvxue.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqjmjqn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpkodgv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fejerjxh.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2magfddnu.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2edupltpc.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2mecvpkcz.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xrisaryi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwvzusx.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhsqtfz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvbizkk.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxzchqp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2catfppxp.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2glgsdsdu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2atudycqq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dybotvcw.html


<!-- 参考信息 -->