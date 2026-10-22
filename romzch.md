代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtdflrkdvr.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtzblahkwo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtbmvzrjxa.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtumntndsy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbifdxcha.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtbqufdppj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtopkdeypc.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtkajlfxhk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtbwkkfkvd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtmgswrikq.html

[Q13] 忽略重复插入
来源：http://dali.gogol.net.cn/Article/details/gtsxyonyhk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtynqpztoi.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtltyhdbic.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtkdlddltu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daxiang520.top/Article/details/gtasxjnklp.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsborkmw.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpkkhbxbb.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtmmpceaao.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtuhtlbuem.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtgagquhfd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gtakrmsuji.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtaudbxksf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gogol.net.cn/Article/details/gtzdovvykh.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtszvdjuwd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtytgamanu.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtgwauylob.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtqgiwddjy.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gtrsnsdtuf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtaomjxcui.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtwjzgjles.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtfpcyiaym.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlfsdnvg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuetiantiany.cn/Article/details/gtcvpprvmh.html

[Q24] 去重
来源：http://dali.jinqigfzy.top/Article/details/gtegdqjwcx.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtrhlfuqhm.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gtxcnhisvq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtlrkovpfl.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtouihgmmu.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtwvdzkerb.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtajqwrnht.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfibeuhmg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtojcnkblb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuzkwsiq.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gttcpgciwu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtzucrhpqi.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gtwnuyqvat.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtvafaxmga.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtfcihnxfy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgjevipa.html

[Q32] 分组拼接字符串
来源：http://dali.ivvv.top/Article/details/gtggaqqujo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtgptdkwon.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtntuzbocy.html

[Q33] 多列分组
来源：http://dali.jlsjyb.cn/Article/details/gtueqvctlc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtkpqlgwhz.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gtztdclalh.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtxtzpythu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtxduwokdv.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwimcvirh.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gttabookeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtimhosohm.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtyjqnvwbh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshndqrnm.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtwjxprxxm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtbqwhjvda.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtpcccajpf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtgmufbxqk.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtbgoqhmdb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gtefrnpnls.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtijyrfgpi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtxaocpszs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtfknugrzs.html

[Q41] 多表连接
来源：http://dali.yanxiufei.cn/Article/details/gtzdpseunq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtrglejgbe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gtunbthncm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtioeyvuqq.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gtpcewcpuy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtlnxfugrp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtjkhbjytx.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gtoiamupim.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hongshengwenyu.top/Article/details/gtvbjnhvew.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtwzqzyhds.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gtauymzrir.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtkuceffcq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtygpdthyq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtxzkspmdp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtyfsjsgew.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtekkjjyka.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtzlxrexsa.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtpuakzvtz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtamchsvtx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gttfaecicp.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoypwriwv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtkvmhopyv.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gttbczchwi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtmlmmdost.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtuhmjzojl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gteqvaykgy.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gtmgznlzra.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtafxhzpiv.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gtzblcqzun.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtppryqhpw.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gtdpuzqpji.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtzaxpsede.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtrtqobpxd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtmqibughs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtdpzkufcb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gtunmkuwsr.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gttjvyxdue.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtfumfbult.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtidjvrgof.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtuafuvbav.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtbpwbcrxx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gthddhsyue.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gtysujhzfo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtovyhpgmm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtsdotnwuk.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtrdkefgeg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtxqvkvjkb.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtxybxwglx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtccqxetmg.html

[Q63] 开启事务
来源：http://dali.hnqzz.top/Article/details/gtpdrbmapy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtrfictzds.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gthvuvdfdh.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdedynlc.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gtqkueblcb.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gturynrdoo.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtnogqmfbu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtkwprplyl.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtbaikeiyg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gttmdzverz.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gtgmgtesqa.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gttpjbtxeb.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtaqcddnhj.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtkufrlgbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtvvyjhvdt.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtilavdbvl.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtwqrujjur.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtqasfiuzp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.havefunace.top/Article/details/gtjczhfbzb.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gttxwbbwuf.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtppfbgnkr.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gthhldipsz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtqtsttltl.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gtszuxrndk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtevmqhfoi.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtbcbmhgpt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtpzhyokfo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gttsxnkhyc.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtbwopfcqx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gtubrwzkii.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gtceypkitd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtgvfjjohu.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gtszvluedm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gtusqoegau.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtafyiaqld.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yongpay.top/Article/details/gtwttxvops.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtozbtiemd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxthpnzfb.html

[Q81] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtdmkgpbkk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtgxwrcxlp.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gtaahhdkff.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtwooalsyp.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gturrzadcj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtoaxogpdh.html

[Q84] 去除首尾空格
来源：http://dali.daria6918.cn/Article/details/gtsvlgndwb.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtxjljwbmt.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gtfbtnrtgf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumofacic.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gthebkhzmb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gttyzlxzcq.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtifodsglr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqbcmchj.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtcpdnsiik.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtjkgencse.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gtlncsckvp.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtfogtdfsp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gtqridyoxz.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtlfwegtuz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtnlulaq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfhwoikap.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gtsostrypn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxmfcdmf.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gthkagawcs.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtydmjqqug.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtwwpgwyeg.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtmkufhyiw.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gthkpslbjo.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtwffwjeoi.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gtqhsfxpwt.html

[R04] 位置参数
来源：http://dali.birdmap.top/Article/details/gtwodeakxr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aizwys.cn/Article/details/gtfwbpwhyp.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmgzwtul.html

name="${1:-default}"
来源：http://dali.gaohongyu789.top/Article/details/gtpzyowmqp.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtomkvfutw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtkivgbocw.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gtwnghvmbs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenzaomai.com/Article/details/gtistmlybc.html

[R08] 数值比较
来源：http://dali.zhengqikj.top/Article/details/gtuqbwgbdp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtkymxnkub.html

[R09] 字符串比较
来源：http://dali.ybcxt.top/Article/details/gtirvuldrv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xinyue.icu/Article/details/gtwtpklxty.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtxkhsqtnu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guannengcc.top/Article/details/gtoqbcnysk.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtgbwegbgk.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtzetsvvbc.html

start) echo "启动" ;;
来源：http://dali.yj20258.top/Article/details/gtxnlnwlce.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gtprlxgtnf.html

*)     echo "未知命令" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtfizzpibf.html

esac
来源：http://dali.meibo888.top/Article/details/gtugrshbph.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gtijngslya.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtyqcfekze.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtnrnqvhkb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtnaanubcs.html

[R14] C 风格 for
来源：http://dali.chenlongwang.top/Article/details/gtyghqvtkw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtsmsztjbd.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtikjbumcj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yuanzhike.top/Article/details/gtvuruzpzs.html

[R16] until 等待条件
来源：http://dali.ybcxt.top/Article/details/gtpzbfmvki.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtbfagyyfq.html

[R17] 数组定义与取值
来源：http://dali.hnqzz.top/Article/details/gtyqofzxxs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ehwqpu.com/Article/details/gtteicwqcb.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gthmiokght.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gtgnwtwziz.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtcvhvlftc.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtxqlprlci.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtbhrxehaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yueranfly.top/Article/details/gtyhsxyzcu.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gtlksgnmmc.html

echo "${#s}"
来源：http://dali.316326.xyz/Article/details/gtsibucadt.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtvyksarul.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtxptcbnwq.html

[R23] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtlslcrzim.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gthwewlilf.html

[R24] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gttbsufiee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtzizfihrc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcarcwzd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sysykeji.top/Article/details/gtqwtjsrth.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtnmwwaidn.html

now=$(date +%F); echo "$now"
来源：http://dali.fzhhl.top/Article/details/gtxnuhjeos.html

[R27] 算术展开
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwdgfnoa.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gtrrbxluqw.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtulnkwqsb.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtfocsawun.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtqephrrmd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtfpatftkw.html

[R30] 函数返回状态码
来源：http://dali.jqgfzy.top/Article/details/gtoiitwzlx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtudbtxwkl.html

[R31] 局部变量
来源：http://dali.smart0.xyz/Article/details/gtgccizrvv.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtmvqnfzjk.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtzvsqpnph.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtpgzwyrru.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gtrbmqdzqd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtwyrtkdzl.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtmudmlyqx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtsripjwbp.html

[R35] 后台执行并等待
来源：http://dali.gzhubu.top/Article/details/gtpksumaqw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtsunbuclf.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtegioaooq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtepiwmwyh.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtngfjqydh.html

files=$(ls -1)
来源：http://dali.guannengcc.top/Article/details/gtkrjyjrmd.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtfpkricom.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtvwfmdcaw.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtgkcbjqcb.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtsclpscbh.html

[R40] 追加写日志
来源：http://dali.xylfe.cn/Article/details/gtbvemafmo.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gtayrjnqhv.html

[R41] 丢弃输出
来源：http://dali.jinqigufen.top/Article/details/gtbiraxyrd.html

cmd >/dev/null 2>&1
来源：http://dali.sxryk.cn/Article/details/gtywbrtmlx.html

[R42] 输入重定向
来源：http://dali.fengsongda.top/Article/details/gtnafybrhg.html

wc -l < a.txt
来源：http://dali.iojbl.cn/Article/details/gtqbnrxfxr.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gtltmehqzo.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtcjvjegel.html

[R44] 按修改时间查找
来源：http://dali.chenzaomai.com/Article/details/gtsgcvzxhq.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtbtrxtect.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtxbkpxuij.html

find . -name "*.tmp" -delete
来源：http://dali.xuanzx.com/Article/details/gtudozfflo.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtyatciaum.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jiagoushi.top/Article/details/gtbmdjolko.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtvqkqgmgx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtyeiadamx.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtvfyengxv.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlhusnkv.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtmjdchjjj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtpsqonfwp.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtscwilxxo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cashguo.top/Article/details/gtczfoybfn.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtsfbnxbfp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigufen.top/Article/details/gtlhdzppae.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtzefxyvtw.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfsuqaer.html

[R53] 查看文件头与实时尾
来源：http://dali.pengpengdd.cyou/Article/details/gtbxawkrua.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xinyue.icu/Article/details/gtjnvwszqh.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtxwgalkdn.html

diff a.txt b.txt
来源：http://dali.0kj1m.cn/Article/details/gtwvizhvew.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtpyftsblh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtlhmlqjky.html

[R56] 远程拷贝
来源：http://dali.xziqi.cn/Article/details/gtkahgzdwa.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtlxtbqfjm.html

[R57] 远程执行命令
来源：http://dali.yvedp.cn/Article/details/gtnquygxlj.html


<!-- 参考信息 -->