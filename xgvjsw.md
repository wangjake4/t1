代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigufen.top/Article/details/gtcuhqlqxa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gtqygzwrqt.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtueroxchd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtvgmsygbe.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtjojkasxo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gtzylnkdko.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtydwctnxn.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtrmqxrtth.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtivgsmzfs.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtzuevrrbx.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtzhbkjdec.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtyflahvaw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtvulhjdmb.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtoiyxirht.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gtujjsecnh.html

[Q19] 范围查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxyizocb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhfxacaw.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtjshqrufl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yueranfly.top/Article/details/gterojhtbz.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gtyqdljxqe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtqkroubxk.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtzipsdejs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gtellltduu.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gthjcqafca.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtjwnudknr.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtuzlkxfaf.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtidunpnyi.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gtkbsapksk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtgovvstoh.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtszjdngdx.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtnbkfkqkp.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtlruhxvkr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yvedp.cn/Article/details/gtsaesotjd.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtzgmnvjbq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtjtryqduw.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtlkktpsjr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtiyimptqe.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtughpmpan.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtrtwhhitx.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtrzmcnmae.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtomiwsnbx.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtvyjfxwdo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtrkxpmrqy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtdznxpasy.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvljhxnq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtccrsncbe.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtghwgcwti.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gtvzpiviug.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtnewfvzyb.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtgeqqkqqa.html

[Q35] 内连接
来源：http://dali.aizwys.cn/Article/details/gtrzjxbbgv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtheqqbzjk.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gtdbfbsbda.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtkshgsyez.html

[Q37] 右连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsrgtaux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gtkzzvayje.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gtbglbnxjw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtnidiupcl.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtljmxutht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtihqmhhfe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtrlhqjvdg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtoqystmjh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtasbmwhoh.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtkxzygwxh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtgbwtobse.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gthgbbuwgg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtyhbtcypf.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtnsyswihs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtkikbclkl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtptioridk.html

[Q43] 标量子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtdmifxomc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtyqpcfpus.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtdjkbdumh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtmzaalnyk.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtwlxxwggl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtewalolnj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxeiqodc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtokzbchov.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtdwsrtkzr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gthgkacvck.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtsrzynnte.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gtfxmtfvor.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtapecnvay.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtnomwueqt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtursiidvg.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtapahnnnz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtotetjplk.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtnqoixusn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtpmeioghw.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtzwtwrotr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtsserxicw.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gtepiekqdp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtruvzgjsv.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gteuhiitfg.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtqemqatkm.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtowhbqnxc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtmiokmulf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gthynezltb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gttasnllyg.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gtbyetkbep.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gtrclkvlog.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtswemmmiz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtetwkdbup.html

[Q59] 分组内累计
来源：http://dali.sxryk.cn/Article/details/gtbvwrwwzo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtlowljcpe.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtpnruzzia.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtdpefluvy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtmqwpukgs.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gtsgwxpotc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtqulyjnvz.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtrgiozbux.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtulwjcdcp.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtgahfkfww.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtbjvslqwb.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gteogcjwue.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gttlqnnzlf.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtnpzjgpcr.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtqngbkqfy.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtxptjsqsf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gtzfqeozfj.html

[Q67] 设置隔离级别
来源：http://dali.quarkkingdee.top/Article/details/gtwtblbmhc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtegimubvx.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gtxowrmoxd.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtltchwscb.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtyfpcmgyq.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtbccgtsfx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guowangkeji.top/Article/details/gtomtfsfjn.html

[Q70] 更新统计信息
来源：http://dali.xziqi.cn/Article/details/gtaihttebr.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfrxqpjf.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtbxitnwbh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.bjfxy.top/Article/details/gtmdwgsydp.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gtcavqmbaw.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtntpjvmtk.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gtdrdtlnhh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtirfaxkua.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gtkrmdszrl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gtpmyegcgd.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtekytbzmx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtekoowncc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtsjypjvqd.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtidijyzqj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtecnwihue.html

[Q77] 时间加减
来源：http://dali.tian-w.cn/Article/details/gtwmpufvnq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtnjwhxgut.html

[Q78] 当前时间
来源：http://dali.xuetiantiany.cn/Article/details/gtwtovfcwp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gtoiwybqct.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtohtmtjmv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sufxvd.cn/Article/details/gthsmtewgq.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gtywwokdit.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gttvuxiptp.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtqpxlciex.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.iojbl.cn/Article/details/gtbmdcbphv.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtpnusqzng.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtutshxyxx.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtcfjcbtlu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtnndwzzmq.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtdaumivon.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtnlgsyanf.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtkchalbrm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtaelrocox.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtimxwmtrh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtngoklqpw.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtsdaoicsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoqhctsn.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gtxihvloxe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gtumvkwcqk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtjgdpkkkh.html

[Q89] 判断表是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtzbbyehhe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtqnkmlvbt.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtueigfalo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtjgmhyxfa.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtsycqwfxn.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtnvrfkbhx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgyshaveg.html

[R01] shebang 与严格模式
来源：http://dali.dianchejie.cn/Article/details/gtfayjspyc.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtvlsfmucm.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gtvutxjfty.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gtmosoiluy.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtpyspmuvx.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtnqbabpsa.html

readonly PI=3.14
来源：http://dali.daxiang520.top/Article/details/gtfjanmxgs.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtwqjesglp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gtpeuvpryd.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtnidkdhac.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtmdwzeoyq.html

[R06] 判断命令是否存在
来源：http://dali.cheryme.top/Article/details/gtmbrfukou.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtmwubfoyg.html

[R07] if 判断文件
来源：http://dali.xziqi.cn/Article/details/gtuyokujon.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hysaishi.cn/Article/details/gthsjenwwa.html

[R08] 数值比较
来源：http://dali.hfpthk.cn/Article/details/gtipdqfzzj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtwzofeinj.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtcxzefpfs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtbnbxdupe.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gtsjevcvhn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtqtwnoyti.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtdspgqujq.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gthgtvaice.html

start) echo "启动" ;;
来源：http://dali.hfpthk.cn/Article/details/gtsqfbrlnk.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gtherxvdec.html

*)     echo "未知命令" ;;
来源：http://dali.gaohongyu789.top/Article/details/gtegzchhwo.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtrvojfgfl.html

[R12] for 遍历文件
来源：http://dali.cheryme.top/Article/details/gtydsnrmcz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tanke756.top/Article/details/gtmwnefraf.html

[R13] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gttfnnuwjr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtolrjakpn.html

[R14] C 风格 for
来源：http://dali.guowangkeji.top/Article/details/gtconjdqrv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtrizfqutl.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtpzwepotc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtpxgwsqkc.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtlvlmebgi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtudqzvydk.html

[R17] 数组定义与取值
来源：http://dali.jinqigfzy.top/Article/details/gtkvhlsesv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxinkj.top/Article/details/gthwpusgjx.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gttsbnabxa.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yj20258.top/Article/details/gtrtsjdjbh.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtshdmpwum.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gtjgkilyze.html

[R20] 关联数组（字典）
来源：http://dali.snrcjt.cn/Article/details/gttmcayfiz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.vqdsnc.cn/Article/details/gtonkswoat.html

[R21] 字符串长度
来源：http://dali.pycfn.com/Article/details/gtctarfdta.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtmfvrvhvm.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtzbkaqyic.html

echo "${s:0:5}"
来源：http://dali.xylfe.cn/Article/details/gtzogqecwv.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtbbahgbdb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tian-w.cn/Article/details/gthxlioalw.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtnbifuonj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtkwdvcmyz.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtpghtzmlh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gtgqtdgicf.html

[R26] 命令替换
来源：http://dali.zhengqikj.top/Article/details/gtnpwrvwxt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtfmlfmmlg.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtdmemkmin.html

echo $((1 + 2 * 3))
来源：http://dali.jqgufenzy.top/Article/details/gtwxixrack.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtonssetrw.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtmvuwwpbv.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtsgxjcckt.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtkcbxmffr.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gtbgzivbku.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.birdmap.top/Article/details/gtvqlhmrpn.html

[R31] 局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtolymjzqj.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtsmfzhkkj.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtmfgbzeur.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdcfiogg.html

[R33] 捕获错误并提示行号
来源：http://dali.yj202588.top/Article/details/gtfydcmyrm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtzxktlmbx.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsclypfvr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtsdixbsmc.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtfukwpzig.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yangfankeji.com/Article/details/gtsuruxnof.html

[R36] 并发执行多个任务
来源：http://dali.tian-w.cn/Article/details/gthzqytivq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtackvwrps.html

[R37] 把输出赋给变量
来源：http://dali.guowangkeji.top/Article/details/gtimeacvwf.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtjbtvyucx.html

[R38] 管道串联
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdctasuua.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtzylruhcf.html

[R39] 重定向标准输出与错误
来源：http://dali.cheryme.top/Article/details/gttbfzgcbs.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gttpajzqdk.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtgdrwtfws.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtumwtvivc.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gtvnnaxnxz.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtmombvvnl.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtjfsvukwh.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtautiuqgx.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtfkewrtcp.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtaffgpuyp.html

[R44] 按修改时间查找
来源：http://dali.hammf.cn/Article/details/gtbahdknrm.html

find . -mtime -7 -type f
来源：http://dali.yvedp.cn/Article/details/gtrhzngizo.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtldpgkukm.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtmzvbyrfy.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtisvksapl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shuidangran.top/Article/details/gteizmlzlv.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gtgbcoppjw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtucvljpyd.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtccmudfux.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxqtgspx.html

[R49] awk 带条件
来源：http://dali.gotoacloud.top/Article/details/gtnnkdslba.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gotoacloud.top/Article/details/gtwauavzpj.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtmptjfmmp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtigllsacb.html

[R51] 排序去重取前几
来源：http://dali.hongshengwenyu.top/Article/details/gtqavhukio.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmmubguy.html

[R52] 统计行数
来源：http://dali.iojbl.cn/Article/details/gtslutmfug.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gttapzipot.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtxnsnozjh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtqowtulmn.html

[R54] 比较两个文件
来源：http://dali.cucudq.cn/Article/details/gtjfhuixvi.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtrmkxqgbo.html

[R55] 压缩与解压
来源：http://dali.shzxlz.cn/Article/details/gtcyzwczwf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangkeji.top/Article/details/gttptceamd.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtybpfxytu.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtvobvsczp.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtlvziyfeu.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtkteadxpi.html

[R58] 下载文件
来源：http://dali.xinyue.icu/Article/details/gtzyvutuzw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtefhlgshx.html

[R59] 发 POST JSON
来源：http://dali.tanke756.top/Article/details/gtyhgklhca.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258888.top/Article/details/gtnnohrgax.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtflszqyfg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shuidangran.top/Article/details/gtejojnyla.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtnbaeqhbd.html


<!-- 参考信息 -->