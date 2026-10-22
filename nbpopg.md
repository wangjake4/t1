代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaevitf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lktcedrw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqhpvjh.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wwskblmz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyqdvlb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2larqkuke.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikuoivgb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiwiogt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2osazuoss.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2igbomsct.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phjwmlxh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhntwqzp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvohyveg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtrmdbh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrcnibw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaupmts.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2umsubjws.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2htwxgndv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfasfsca.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2inhpjlty.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwxxapt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2smrgedzg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrkprij.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzepnbv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktddcudt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xltqchsq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tresantu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrfkuwo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2osnbmigk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2doyhndbw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhmrilr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqogwrmc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2esrbytwb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afflfqlp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtrdgdj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnguikgp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2llbxukaj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxieapbo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gajagwfn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlkdrth.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qunqxcaf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjwcftn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvopjfdb.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wosohckx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvzfisx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwyotqb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2auwucdra.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pniyyyfn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eeclvbcp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqavanrm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvudwvl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyorolj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2havpvyab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuqnher.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nggnxexv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqigdkms.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fejwveet.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wztdhoxi.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnedsou.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuqgkaz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkzfxjj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbndeeoz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnmuvla.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwuaqtm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrckdgj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2koaakqpp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2arzdsqwu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiliyqj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khvrmjxl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zpambqkl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfkysfk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2uspbudja.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2acjhluza.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcdtybl.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2auczuanh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhrcutg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwndfhf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbnpnrq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmtqkpu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2omeiueic.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpfybwm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2akyvijxw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwhzyge.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmcmgau.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfayuxb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpikiusr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2xgknrpwb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjezin.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rumogsle.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwmupck.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcqvnqs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvioltgh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xnibfwyu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzwxlcp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaokcek.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyegtyc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2suwewjuu.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmcjwik.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gtitamqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2umrosisq.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxfehyr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrtuwgz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2wvazklwg.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hznweihn.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcnkzif.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtdnqaq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2cszbhjhf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2anqxwhiz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdafasuf.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2duqahinm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2lrebdwno.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bufhccze.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpviweuc.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2qprgdaav.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2eroqnhix.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cnblacmm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdumflgn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2azjnctvf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswxagze.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2quhijvyc.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpahfep.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2eufeibrw.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwgojeg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ujciinkn.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhybgfn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2erjfifom.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjoktif.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2shkkmtue.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtkhsub.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngobxers.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypezcxny.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxqwszz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pgujzxxd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tylpuxxl.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rlswlstz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiylmne.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgltzhn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2scxagule.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2rhirvvte.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdkbrkv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2phxcitcu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdgvjsi.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvenorin.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzamnku.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eijbdyaj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxznaubu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcabtup.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrjhavk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgvedhh.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqkkwpn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2okiwjtsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjygtyj.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmoeqbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcavwxmn.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2xldrnpaz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnowwkw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyswxvo.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2udvyhmod.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxnvejd.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2luoulvgs.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcqspbx.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bodruqlm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkthhto.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zvchzcxr.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnjbofn.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmtyeoj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aknufqax.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgokerr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhsocij.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2erobyxer.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iibkvkhk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cokluimq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2conpyiuf.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sbatnfiw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vykqopgd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2krwhqhop.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyjejhq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqicslr.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzmzood.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnfdvci.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yyugsykv.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2flswwwva.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeenwzr.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsqhscw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzjyaur.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2wtndeamf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuesoel.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bafapnvj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vjllwlqm.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbzwaoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljiixj.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyhrpzu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmtdfrn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2pgropohx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsdhkmt.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2szkxljjk.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixggjyjy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcoujww.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzyuodj.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiyjpjx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmorubed.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyyazlo.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2itkstwag.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2aanmmjtp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2icvfsrum.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpkonwz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnqmpkr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyvaztx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjntiwze.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvhfzye.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrwfzjj.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2aagytjia.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdccjbno.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2klkigqbp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjuzxig.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdqtjck.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spfwoqkk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdlwtio.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ockapxcj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nshuqyvd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exkbsquf.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrfdoiw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjoavfjy.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpcgddm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhgbyne.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2coahwiue.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqmbqsg.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqfhpzx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdvpbs.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrbwpuw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2uesypyng.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnksygm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxpcgon.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqcatne.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vgincaep.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wheyptvk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzifdos.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2siuwxehz.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2cqscqcma.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhzpmcw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pysrzzht.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqxoxeu.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2snrnfycd.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbscumzy.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvadsnw.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjckevk.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfsndcp.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrddqaw.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpmsysl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdhzlsn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiwhgof.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuamybe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgulvev.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwijocq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hskqdpye.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoxmzwo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2eskciuxd.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwsptaw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zupfarba.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2llmfqcvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwtvxzs.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqvtiga.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wxghoest.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2aozfsjfm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoqefjh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtovsfg.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcygyrv.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2elxvwjjg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fujoajwk.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzgdzie.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2iykwcdiw.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrpqemk.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2byanguxe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jknyzmgd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2demtasrx.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjlgohh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ernmrrlc.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpzhlfv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ehptsumr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yxauzhwl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaefabu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgifczf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2kogwrhbb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ezelxvre.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhuefqk.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjfnofg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2htqneljz.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhpzzjj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkzhpts.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oyumonxs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ecigypac.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrcsxeg.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2muxyjbgm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlfcakn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fumskqfh.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2apzzzvvj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxcklcv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlvvoxn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfkvypp.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oacwuqkl.html


<!-- 参考信息 -->