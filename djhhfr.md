代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvczorvd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wufmlxzm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmbfyie.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxwpyqo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuwsvft.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2felkqzwe.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axkgqtbh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lptpxhux.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrmxfrc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2epdjwpob.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjhytit.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvluxlu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gznrocya.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbxgrrt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hitfgajg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmdaydr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfxcvqt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvnjdxl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaxhopb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zftnkufs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pycwpkaq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2bboelnnw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtblwmw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kzibdrog.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwlnpwu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdarkqs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpwuppv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2futcygkk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxsxcdy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2waawucxi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hgznatln.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtzokwp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2caikucvu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkoptmk.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkbgyqb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcqyfmk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gowelxyf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpxeepp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwmatqn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwvpguv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gygizcac.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2srephmxg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtsyxwb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rvetyank.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2awplltse.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfarahah.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rhazaxka.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkqojfe.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnsxqeb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2onabtnbz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gilbuzwr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxadvdq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrrzgwc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhixrzgg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtsvzry.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajstgtqr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ooktpjvb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2shoqsaut.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkyyebg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfexjldd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yznmljmj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjndahq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmtnluw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bheooyoa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2acwcixac.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2napxdncp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uespgqbg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2khoetmmq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbsqksv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnuwljr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxwsrsd.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2egibakbv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtlbgje.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2acvdmlzu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzpczdw.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2htxfbxpm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfiotxn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrfbcrq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsonwpsu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2nwemyioy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcovfbx.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2veiauxuh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2exgmbvzr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsxdmyy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkuydfx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhbimaz.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlmulsy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvrgnam.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuswwin.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2edusaldz.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2blfiyxtt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2iakctfua.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2razqhmuq.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yogfaiat.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2upcxwtso.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2akhfvgti.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2alzilpkh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnxtzae.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wpasgijy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkyomph.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zidxnscw.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmwsqtb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoltsvm.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2iimawvbl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnvyuuv.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpmtuki.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lygjbtij.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrqirio.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tygohffx.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzwgoec.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2vkctvwdk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2csgeylrw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbfxoat.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwphccx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2biepzzzp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2macpdteb.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfikubi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2deyhssxn.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2njpvurzr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfhmckj.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpefzjj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ebertriy.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjgstro.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2cucrumjq.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2baybxybt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kurazuwa.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkflbcnp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gokxwamu.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdleabd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rznkqdoz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqpmuff.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdhngnm.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2eigndaot.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqttelmi.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2joqypxjp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjkmlx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwkuwed.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsiwxrv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2myvhpojo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaulalak.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxadjemc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhiclsk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eovligxn.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2helssqgm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjnlbkk.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcabjxmo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2phsajhqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwnywwx.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxmcjxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsiyoue.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoxuklb.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjhwmyd.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2beczjorb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxganlh.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2shajqrmf.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjyfnzr.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoklvdf.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jailbdka.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzqesqy.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jviinmdn.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbjuobi.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvjzdkv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyykydu.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkhscsr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2prtwlfqu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrigosp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkqvdqp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ophuvieq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyxtzej.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdtofgt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yucxzhyp.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvvjxvm.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcpufqt.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2zctwbjqt.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2moldoghe.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaluzpc.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2hahgnonc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cofknvzi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcxjftf.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2syynwstz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zluxtduc.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsthfjy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiwjbse.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgafgyl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cbecywcm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkucjgu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2thxdekqv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwaaagh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apniubxi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2frwavisc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2meevrzfx.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbyyzls.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfktpcnh.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2iatdqnhy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaueaye.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkdoph.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ndohpeym.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuhkxly.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2efdiojws.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2banndtjf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzliepr.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjjufvo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjniqqe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrswxyv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eatmsxho.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfapmwb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqajyhd.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2eabujuca.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjrdkfb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2iipibinx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrhwywq.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdiwczu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjvrvsf.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkzbxat.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfwuozd.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rigoznbw.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjffiefv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bexljhty.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqebcaug.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrbnuff.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwqhmam.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2pjckdmdg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqtsmro.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcewcgt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyduozc.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvozvhf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzzvsen.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxergcr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoudrac.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxbgnua.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2smnfdawe.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wmotkqhk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jiarbpey.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdmbqbu.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvpgwyu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kmswrgzv.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jinnsibp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2obktcotl.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wutzlfkv.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfttwyad.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2edvqswox.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyjuqkv.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xifbfwll.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoeefqa.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdpzdps.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwbjjrd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoaeefq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lzirjuni.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mwigxqdp.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqpluyf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cnctqxyd.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iebehzlq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfqvcwq.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2erowccxf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gygctjxc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqfkhxm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdduidc.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsehmbvi.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnjwgij.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqjepfq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2idgppqly.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uamuwcjs.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vumnrnod.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgzhivx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrocaru.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxztgov.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ztomzksj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2abhwgifr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwzlarm.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bukkmdzc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlqdwwk.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2swtcxvto.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2pegvohwg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyswfzy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2voqcbbga.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2leoyibgp.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkxhtqc.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kzibszgz.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsmoydt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dblxrowp.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwjjnfx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzsavah.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqtnexi.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvoyqwf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2mklnqfbl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aynzqdmh.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpyotji.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfkowey.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2fvozdlbo.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvrncpl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ylckhyym.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxioxvwq.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2xuldwnec.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2xdicslmt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlqqkqu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wfltqreu.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnvmpsj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2blgvauwe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2duslansw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tidgobra.html


<!-- 参考信息 -->