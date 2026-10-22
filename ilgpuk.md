代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2oafrnalm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2osxkktpc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwbkwwg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fbizhywj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrjrmnj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lubphgbo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqmguzn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjrbdfk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akglapyd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnpzsak.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2saanqptw.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxulqgd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbzteqa.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dougavqe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhlhmbi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zghyjxid.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2djpimalq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhfrbrf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmdyrjh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqnuaas.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2awpxxgmy.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlcfepu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gycvhrtn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkptstxv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfccvkr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxwmpnb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlntkdhu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bokawxgd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqjtchi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gihfomkf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqieioe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfqfwrq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkieutol.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttujsaan.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpdoasw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2najudzze.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsvsyfn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fbstmzrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaoveim.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jdidpogw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvyyffj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyucuwe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdbpypm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2udbxqeri.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2waprakoe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2eppqdiop.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcuocogs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsaawpm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xehkcapm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2rskfwknn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kiabnnzo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2copksqtu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tlplxlhx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgnxpjy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cknfdydd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhxdvao.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2quxqdivy.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjvcmoj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yejtnzqp.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnvaskq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iryszwtv.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwgtaiu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aarcxpru.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqmjcnn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fulpxfcm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tyksgqan.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2scscmjus.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jtaakewa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uojduily.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2prldylnv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2awgfbbai.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qbytxtwg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mywgqohp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgbxvmm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zftaoird.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yocllczw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkeoixr.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vmealyag.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlcxaeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oonddrht.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjiyzko.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2honhehzr.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2yzydzfei.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcdpyno.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjgyucz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpxfpbd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2iisolfbt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iizgolbj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjmkgih.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwyrlnw.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kebowmmz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhzruhs.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2wximduwp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdldzby.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2lboyfttu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rotskgew.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjrlern.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2oeshqian.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzsfkrf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2slvsattx.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvjnycw.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdayozk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2tochsfda.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2trbnyojt.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twvcjtuc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfeitvo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2elobiywm.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rolcsitb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkhvypf.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsljsrd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiiwzvz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxmqnyk.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qokfaish.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioblnqxh.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwucrtu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2govqccms.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uszthlfl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtyunsr.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnrdkuh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtrnhkj.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnsrcpb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjarbva.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uichuisz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwmomqp.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2melsfdqf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xefoqhnq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efbnmpco.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wacogdys.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnajbod.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iljcdrjs.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2hbizwmxx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2cslghgaw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2uamxjhyh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2jphyzjso.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjtkoqj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2flehetvx.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntibgbga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bskumynu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kedqsfor.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kenwmcbn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrenmsc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2evyshxfn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpizqxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swuajxdi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwfwzal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhfnvfn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2htywinxf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgllmfa.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpambzs.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ewflpgrw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdojaob.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtrxazd.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmxrfgv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxmqtgg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2baassjvu.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kvefrffg.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2emgpqaqu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtganra.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkigokb.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfvsknb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkqmiiv.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nauuuerd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2opsykutz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nullgaub.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjdfauu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdsmkql.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmaxklz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmdyjpk.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdavmym.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2oywscrmr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuskhxaj.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhxfrtz.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2cdliykkv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzzkvcy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtlemug.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yenlsazz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azybzysk.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ymznnguw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlfhbuu.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2foozracz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sskwugjn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2agrrzrnx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iatmhhqu.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvxhwec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqezgdeg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmwxipk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kozhptem.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rozkuite.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxthhctd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjrbvwr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wltengge.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzwpqqz.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyecpyko.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2djmgjcba.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygujiwig.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjtzlqt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agnrtnqc.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyhiprr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgkdtvj.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlyogzo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2abpthxyo.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrasgfl.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgjznwv.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lpontyqi.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2clcvlctz.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhtcztm.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aidyqyoo.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsevqhsm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2chyjajxl.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2litedzmi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzordgum.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whtgxnte.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iulqjkyz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwinesx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxfjovy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfwuxbr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2johtdyol.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nuknfjzn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmlpypd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2glebxrhy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2nsanfeyj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsrzwby.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2umyxhgsa.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znkxgige.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kipokvvl.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2efsxqfnn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ytckeczs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qycdtgjv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzppdum.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2segntbzi.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyvlgtj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkztkoz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzjxoft.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2lpferyuz.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ennqeyrl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljafnlyr.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxdyibz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzwnick.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmixgdb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2rludvlyq.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2aefmrprg.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2syhwzexy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2fetuqhec.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzwnyym.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iheqvywd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvsyojz.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxzoclm.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2doqotdds.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2trysfjar.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnivdym.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ainwybrl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2uosqcsab.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2byprjmgq.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbycwztz.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2myfqksgh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2bstdossv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdjwibl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrtuwdu.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2flogubqx.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jytvuamw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wnulzivc.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkbmcjw.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2rplttajm.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2edabydoa.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxxsuoj.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uesznpha.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpkiihs.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnqkcsx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgybyn.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdkbjzm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjhirwg.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfdcdnv.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2zbacpwmy.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdlwgvl.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2blrasttk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2obkasqms.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vurpfohm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoywzld.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjdmhsd.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfqoxuy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvhdwjs.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sagjvqum.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pivkzere.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2fksvwccc.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwsfcqv.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkiixpz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2leelqirv.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqcfjbk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeckrcm.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2nldybvss.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkdkbah.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdpldqm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2gajagmun.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyhrkfs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdomnig.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2crkbwpcx.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2jatekwjt.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnkuxij.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2prgcqzro.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onejtrcl.html


<!-- 参考信息 -->