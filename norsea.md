代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtjfsixryd.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtkqcfjpzt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gtnwduodrq.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtpejwdmpr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtxchngazu.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtzgvfihot.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtdeeahvuq.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gtelptychk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtawzzgkww.html

[Q11] 一次插入多行
来源：http://dali.xylfe.cn/Article/details/gtlznnjqcj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gteifimgnj.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtckoogskj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gtbkopxkpb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkajclkdf.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtquslxoos.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtijshxsqq.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtkwaawoly.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hnxiangtu.top/Article/details/gtuxpnbzvp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtqyllvven.html

[Q15] 查询全部
来源：http://dali.snrcjt.cn/Article/details/gtdeyghixw.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtvnjteiqw.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gtrdcoxtrb.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtpmwrkznx.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtetsktxsi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtvezclyvg.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtzvytaskd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.iojbl.cn/Article/details/gterpdcagl.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtjalxsqpo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtbkcszkjx.html

[Q20] IN 列表
来源：http://dali.hysaishi.cn/Article/details/gtvhgnoaep.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtagaapxvt.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtufdkuckj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtgwljqwzr.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtauikiumt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hammf.cn/Article/details/gtebjimaaw.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtwpghxuve.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gtoxdmowpz.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtowzuhsnm.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtkzvfnfym.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtrtozlxdx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtmrlckwxg.html

[Q26] 计数
来源：http://dali.xziqi.cn/Article/details/gtvlchxfss.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtueoxgovs.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtogkhlipf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtftizmrpm.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlajdmiai.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtyqseoxsv.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtxkhuywdu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtufqtmjch.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtcccnhkdg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gthioitmnc.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gtfgqyghqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtrwzrfzkg.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtgfbhcplh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtbbhtovcr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsftimbkw.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtpapsjfag.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cucudq.cn/Article/details/gtktpiphtb.html

[Q34] 每组取第一条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebbmlvgw.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gttvplddnc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtekudmgaj.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtptqcbkdp.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtlckdkfud.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtlayqidrc.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtavqckevr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtmvxtktvt.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtwycvwjcp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtdojjtqie.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxagguqxu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtfxkikdvt.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtunavhznt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtbmsirxtx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhoulong.xyz/Article/details/gtijneohzu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtsusxyzga.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtijuynvbn.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtzykqpsbr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtfujykwme.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtefljjesc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtzinaddtd.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtmsomuzqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtpnkcojyy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtwhvgxrew.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtzhonxscs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfozbcsbm.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtlyegykux.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gteedksrrb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtowazhixi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtqfecdomw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gtdotyrkxm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtbsfmtvxr.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtwzugfjbp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtuzaphhks.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtapbwuouq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gttdputlnj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtxibhxgyf.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtgtujkdgf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtivdtbakt.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gthwflqxin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gttaooaclm.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtwovsluuk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gtjfhndrlo.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtlwhwcvwb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtnbaagaqk.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtowpyuhaf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtblnmxwdb.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtbhmhkqsm.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtrkrvrteb.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtgnjimect.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gthvshtpad.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gteabnunmm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtldxrkymp.html

[Q57] 行号
来源：http://dali.daxiang520.top/Article/details/gtcgarpbsv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gttuyzoith.html

[Q58] 累计求和
来源：http://dali.aizwys.cn/Article/details/gtozoydpmv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtqfzqvvgj.html

[Q59] 分组内累计
来源：http://dali.hywenlv.cn/Article/details/gtprnddteh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtlysuvply.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtjtctiwhh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbarniyo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtstkvnlcr.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtnnozfvud.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtqrlbegzj.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtpskhqbys.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtajixxdqf.html

[Q63] 开启事务
来源：http://dali.hammf.cn/Article/details/gtjlxztgij.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtuwxeazzn.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbchgdcx.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtrptaqbtn.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtfsuwfsje.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtbutynxlc.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtqygzrqkq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtmjnjjsrp.html

[Q67] 设置隔离级别
来源：http://dali.xinyue.icu/Article/details/gtjoztxwuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenjidiqi.icu/Article/details/gtkgqmqnlp.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtdwzmugbp.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtroovrepp.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtdymgtviy.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtdnwcijqh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gthuihndqt.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtgtdbnonc.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtgxbnaikk.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtarhnxwxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtkgvyijdp.html

[Q72] 查看索引
来源：http://dali.andypj.xyz/Article/details/gtwdldntmk.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtbiwhrnyd.html

[Q73] 查看表状态
来源：http://dali.tianlin.xyz/Article/details/gtciyzxrxo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gttpycqphp.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gthjgyifvh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.guowangkeji.top/Article/details/gtmndxojdj.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtrwaqlpwv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtwbubmfic.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gotoacloud.top/Article/details/gtvlepukii.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtnuyvffjs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtvvkjvqat.html

[Q77] 时间加减
来源：http://dali.quarkkingdee.top/Article/details/gtqdfstylg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtntwcxwjp.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtwsotovio.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.mhx1999.top/Article/details/gtgttwarst.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtlsgfipay.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gtoyrmlnmc.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtmoainqso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtwitfldhf.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtyqgomfed.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxlbthsnr.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtmljrenha.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtyzzweueg.html

[Q83] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gtqokhuipb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtggtgnusy.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdgpciof.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtuoufqpwk.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtrijxdyhg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtevpopvrp.html

[Q86] 读取 JSON 字段
来源：http://dali.hywenlv.cn/Article/details/gtbiqmzgus.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtfglxeoiy.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtfcsadvxb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.9152youxi.cn/Article/details/gtmigjkguk.html

[Q88] 行转列（条件聚合）
来源：http://dali.quarkkingdee.top/Article/details/gtvclkxccw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258888.top/Article/details/gtgrzgxuxo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttqawgmld.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gtwhkjljeb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ivvv.top/Article/details/gtzsxuajbd.html

[Q90] 生成序号列
来源：http://dali.jinqigufen.top/Article/details/gtgccfzatz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jqgfzy.top/Article/details/gtujeqhprh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuyzxuujv.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtfwplprud.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvaorcvqw.html

[R01] shebang 与严格模式
来源：http://dali.jiagoushi.top/Article/details/gtmgjlanfu.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtcvugjmks.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gtowmalnop.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtqufouslr.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gtzyddfgse.html

[R03] 只读变量
来源：http://dali.ivvv.top/Article/details/gtzfjgrnzw.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gtirkukjuy.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtfmyzdvxm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hongshengwenyu.top/Article/details/gtnuvjhfpu.html

[R05] 参数默认值
来源：http://dali.dashuyun.cn/Article/details/gtgmygkbiz.html

name="${1:-default}"
来源：http://dali.birdmap.top/Article/details/gthxvhwbht.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtuajxhrmo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gthvdzmjch.html

[R07] if 判断文件
来源：http://dali.cdnleiting.top/Article/details/gtptokofoq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtzpfzpwhb.html

[R08] 数值比较
来源：http://dali.hnqzz.top/Article/details/gtrqcnjqwj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangdashe.top/Article/details/gtdspextdv.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtcqhmkgcr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ehwqpu.com/Article/details/gtndtejxwt.html

[R10] 正则匹配
来源：http://dali.zhoulong.xyz/Article/details/gtlegrgyrb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtzxnizwyl.html

[R11] case 多分支
来源：http://dali.ybcxt.top/Article/details/gtopzwsazj.html

case "$1" in
来源：http://dali.sysykeji.top/Article/details/gtokvouiqe.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtkaymdjdr.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gttzyvvbfe.html

*)     echo "未知命令" ;;
来源：http://dali.gzhubu.top/Article/details/gtbccoezst.html

esac
来源：http://dali.yuxming.cn/Article/details/gthprtbsgv.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gtrmirjvss.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shuidangran.top/Article/details/gtvmgpsycr.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtydersdol.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtgyraiwxl.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtosimhymn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtusnaoyzi.html

[R15] while 逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtwmmbzkmb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gtouitpdgm.html

[R16] until 等待条件
来源：http://dali.xziqi.cn/Article/details/gtxiouoqoe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtlcdbgxnw.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtvftbosru.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yongpay.top/Article/details/gtbcemwfuq.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtyhpnukbb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtlznjgzfv.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gttygednnv.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmermhnro.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gtitxzjgyx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hnqzz.top/Article/details/gtdwcwoobz.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gteilolrfj.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gtrmatklhy.html

[R22] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtwjafrgqr.html

echo "${s:0:5}"
来源：http://dali.cdnleiting.top/Article/details/gtzkllpdeg.html

[R23] 字符串替换
来源：http://dali.haohaochexian.top/Article/details/gtpfqpymrb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gttswmungm.html

[R24] 大小写转换
来源：http://dali.andypj.xyz/Article/details/gtfksstszp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtoklusmyo.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtyqojprup.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtzznaadvy.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gttzuhkrwq.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtpfzclnov.html

[R27] 算术展开
来源：http://dali.yangfankeji.com/Article/details/gtdnwuhtjn.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gtrbhdjfny.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtyirhobet.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtlvmllotr.html

[R29] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtcmeobbjq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nwbrower.top/Article/details/gtkddodsfs.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gthcdzuaow.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtvdzgzuoq.html

[R31] 局部变量
来源：http://dali.fzhhl.top/Article/details/gtdmwcgvjo.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtjoxpoqoa.html

[R32] 参数个数校验
来源：http://dali.svipenyu.cn/Article/details/gtqkvurtba.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtwxtezmxa.html

[R33] 捕获错误并提示行号
来源：http://dali.zhiwuduotai.top/Article/details/gtlvrgvili.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtenoasxwp.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtvziqbcql.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtitrrdcln.html

[R35] 后台执行并等待
来源：http://dali.0kj1m.cn/Article/details/gtbukxesls.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtdlnqakxg.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdjobyhy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangtech.top/Article/details/gtebajvrsm.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gtxcsdmkub.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtopautjtx.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtzkokcutj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gogol.net.cn/Article/details/gtmlbejgko.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtgdibzhdl.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gthzofgsbp.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtuiirjpdw.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtrnurlwui.html

[R41] 丢弃输出
来源：http://dali.havefunace.top/Article/details/gtdvrvoalk.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258.top/Article/details/gtvyhfqyuy.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtxsshuzuz.html

wc -l < a.txt
来源：http://dali.zhengqikj.top/Article/details/gtlqbcyxdx.html

[R43] 按名字查找文件
来源：http://dali.dashuyun.cn/Article/details/gtyojuoypj.html

find . -name "*.log" -type f
来源：http://dali.wangdashe.top/Article/details/gtewpaihox.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtrrqehiuk.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtdsabhugw.html

[R45] 批量删除
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbiiqnqy.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gtfgdjqznl.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtxpbnszjo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtpyttmdig.html

[R47] sed 单行替换
来源：http://dali.dianchejie.cn/Article/details/gtshxosmnr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ivvv.top/Article/details/gtkfrgaqeh.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtydwqwvjb.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gtexxmqtlv.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtsjmffjsu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtrdatqvma.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gtshpxindb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtspocwule.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtrvyoppry.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtnnjarfhd.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtriqeutil.html

wc -l a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtndmmpkgh.html

[R53] 查看文件头与实时尾
来源：http://dali.sufxvd.cn/Article/details/gtgkqrkkdf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtimopmlkw.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gtfxmkwhpp.html

diff a.txt b.txt
来源：http://dali.jinqigfzy.top/Article/details/gtcooxxlbw.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtxvumzqpw.html


<!-- 参考信息 -->