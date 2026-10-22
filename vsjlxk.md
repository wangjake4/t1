代发 wailian999

);
来源：http://dali.zhongyouzk.top/Article/details/gtoirljtlw.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtqkuvlwji.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtggjdvklk.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzapnrtr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtwtupddbn.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtnvfcsaoq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtqnczpguj.html

[Q06] 删除列
来源：http://dali.jianghu66.top/Article/details/gtqfzznjte.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtvtfiedlp.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtloaubfdh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmiytlsdp.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtcisajeqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtywgbirda.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtoywwtoil.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtadkfsoow.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtibmmzdpu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gthgdosaag.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtsymylxej.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtqqgpuyxf.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtetwwfees.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtsdrabaot.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtqzyxdzrx.html

[Q13] 忽略重复插入
来源：http://dali.chenlongwang.top/Article/details/gtsendbzwc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtvvnjinvk.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gtoworhmqg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtdzimrcsz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtjzjsokwg.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtseaxkjvx.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gttxgaksmk.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtmxopbyeb.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gtnmvivkuf.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gtgfrnhjwh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtpxoneccf.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtxqjswtln.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gtsgvspalu.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtcugpzbff.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gthlfflmcu.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gtezckwooj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtwqwpqwag.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtyzgdzfmp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.c1oappe.top/Article/details/gthqxwrtgj.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtymvjdecd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtqjxpzvqt.html

[Q23] 分页
来源：http://dali.jinqigfzy.top/Article/details/gtmaclcfln.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiqnhtej.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gtinmaixbz.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfjvwdwiy.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtbloeqdkc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtmrzoupvr.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtyhnlsnsa.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtbymixrtm.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtsfcukgbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ivvv.top/Article/details/gteugiltpa.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtwbtgsyfv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtkbdyyttw.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtleoexzbc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtlonkqubl.html

[Q30] 分组统计
来源：http://dali.birdmap.top/Article/details/gtayqdaedn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtcgeinnqq.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gtwbcxuaqn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtdarwjrhy.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtmegbqowm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtcocouzzh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gtposkdgpe.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtdhxzoiac.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gtjwyrvbgi.html

[Q34] 每组取第一条
来源：http://dali.tian-w.cn/Article/details/gtyzdijtgp.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtvdpurqll.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtjfjguqts.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtniclmnjo.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtbvwqvowo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtcdhwtthr.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gtyjfkurxf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtkxdugiyw.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtkdblakvp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtucfcnotp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtctyrwhmy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gtsfxeraoz.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtuxpmxxhx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtrjgcrjff.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gthsjghcla.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtirmeisea.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtslxgpbah.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gtvbnwxdco.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtrkimzgrp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtjyqwupyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtpeesvjuo.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gthatravfa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtvvnnewvd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtsdnvzwuc.html

[Q43] 标量子查询
来源：http://dali.yvedp.cn/Article/details/gtjszefwru.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtzwfacjho.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtbpncmrjd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gttbepwsqm.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gttovedovn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtpxazwnlu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtdlzwpqrb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gttloegkmi.html

[Q47] 与平均值比较
来源：http://dali.nanxuanxn.top/Article/details/gtobbpeght.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgckgwnj.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtrghwseba.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtmwpplmbm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtimfjyhln.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtslkqotvx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtrywqekka.html

[Q50] 批量更新
来源：http://dali.ydzc1.top/Article/details/gthouunkuk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtmstdlofq.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtlwabrvtp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gttnnzyohw.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtaopvrikf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtrzpvdgve.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtefpshzdt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gtyukncuni.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtigyevkzk.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gthfqxmbho.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtheneahfm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtbnmlmiti.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gtcreqazmz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtixhvmsay.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxrnrcdt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdeorgaql.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtugstpeyn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtufphggqo.html

[Q59] 分组内累计
来源：http://dali.yueranfly.top/Article/details/gtygutwmwy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtweribawi.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtjtwjulyd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gttblxqxff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtatagcmcy.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gthmwaemdu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtxzitsnoy.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtqrosffmu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtqpexxcrl.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gtqclxixll.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtgrzpbwup.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtvgrlojff.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtkxchbkev.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtnptalblb.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtuaygwmrz.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gtuwdusimg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtymupebtf.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtgdzdrnnz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtyzxoqeui.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtsfdnbrli.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtrzlqcsvu.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtjdbrsuap.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtzkugvulg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtmhkubnds.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtovxvspha.html

ANALYZE TABLE users;
来源：http://dali.mhx1999.top/Article/details/gtmokrhdcr.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtwcdqwjbs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtxutkttkb.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtumgpfmnd.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtbvhefkhu.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gttycvcyok.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtyzuvroyy.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtmrgxftlb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtuhhpyawn.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtidlezqnf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtsrysgfum.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.nanxuanxn.top/Article/details/gtuelbgiev.html

[Q76] 按天统计
来源：http://dali.gzhubu.top/Article/details/gtzfmeogna.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtobwfscin.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtkkyvedct.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gtnrfewosj.html

[Q78] 当前时间
来源：http://dali.yonumen.top/Article/details/gtwprilnyv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtzqbvhhdr.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtkdiqivdr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtlhsjplma.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gtwimpezgg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtrfzwweyv.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtspvfnzbv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsipydhg.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtwdlycptm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxqsqleo.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gttqsjmbrm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtazjpolga.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gtqfeiqnuf.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtaapsayfx.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gtygtxgrud.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtnqxwrfev.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtwctvbksj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tianlin.xyz/Article/details/gtqjaeerny.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtfwwlopvy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gtzvbwbuew.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtnvoquflu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yonumen.top/Article/details/gtguyyaqzz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuhrlixkk.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtcmmagjfz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dianchejie.cn/Article/details/gtgjnizfzw.html

[Q90] 生成序号列
来源：http://dali.zhoulong.xyz/Article/details/gtyfpwvrii.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtappxflgm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcxymdogb.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gtuwazhugm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyzuaiwip.html

[R01] shebang 与严格模式
来源：http://dali.cucudq.cn/Article/details/gtsaslmbci.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gtwayxdtdy.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gturnmwmku.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gthxxvpoue.html

name="Tom"; echo "$name"
来源：http://dali.zhoulong.xyz/Article/details/gtpxxbmccp.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtmfyquise.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtgrknupbr.html

[R04] 位置参数
来源：http://dali.sufxvd.cn/Article/details/gtbvxwombd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtixyjguam.html

[R05] 参数默认值
来源：http://dali.ppjwa.cn/Article/details/gtvnjtdslx.html

name="${1:-default}"
来源：http://dali.fengsongda.top/Article/details/gttlmufbvx.html

[R06] 判断命令是否存在
来源：http://dali.redwolf501.top/Article/details/gtzdybqykc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtogycmknx.html

[R07] if 判断文件
来源：http://dali.snrcjt.cn/Article/details/gtwyiameig.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtiujuoieg.html

[R08] 数值比较
来源：http://dali.jlsjyb.cn/Article/details/gtrfhabuxa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbppnjwsj.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtppodfwze.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gttfjvolxu.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpinafffc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gttzubeiqn.html

[R11] case 多分支
来源：http://dali.guowangkeji.top/Article/details/gtqzpjbylx.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtafzhhrty.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtwwfpttxv.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtajwtwgzy.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gteieiiraw.html

esac
来源：http://dali.hnqzz.top/Article/details/gtuxizkhcn.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gtzpkewgtb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yanxiufei.cn/Article/details/gtszcwnflz.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtlhtlogaf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtbowcrope.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtjygeweam.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtsirpucuw.html

[R15] while 逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtlepekslo.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtuvqqyytd.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtsqrwdtvu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtxuwpszbz.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtartuosgw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtfgrgnxvn.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtgaqjyuku.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceprvzel.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtrcyvfgys.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gtzymqiouu.html

[R20] 关联数组（字典）
来源：http://dali.pycfn.com/Article/details/gttupipimj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtjyxgxafb.html

[R21] 字符串长度
来源：http://dali.nwbrower.top/Article/details/gtnssfvhlg.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gtjfiybnmz.html

[R22] 截取子串
来源：http://dali.gzhubu.top/Article/details/gtbjadeerz.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtmwrfzstr.html

[R23] 字符串替换
来源：http://dali.chenlongwang.top/Article/details/gtbmlkhwfu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gotoacloud.top/Article/details/gtmvflcwiw.html

[R24] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtxlpyegba.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtwendoweb.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtbnaglplk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shuidangran.top/Article/details/gterojhory.html

[R26] 命令替换
来源：http://dali.jlsjyb.cn/Article/details/gtpkbxqnrn.html

now=$(date +%F); echo "$now"
来源：http://dali.gogol.net.cn/Article/details/gtxtelwpew.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtahttmyin.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gtkfewloha.html

[R28] 浮点运算
来源：http://dali.gzhubu.top/Article/details/gtrfpblxcp.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtqjemzkrg.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtywuwbidi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daxiang520.top/Article/details/gtyjgnamtz.html

[R30] 函数返回状态码
来源：http://dali.nwbrower.top/Article/details/gtdwyztcus.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shuidangran.top/Article/details/gtcijnvzpw.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtmpocqnah.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtctahvrrp.html

[R32] 参数个数校验
来源：http://dali.jyoumei.cn/Article/details/gtgjeugaqu.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtkjtpqdya.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtfynkfdbt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gtagrqywbf.html

[R34] 退出时清理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvagnwyfq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtzrlpfmkl.html

[R35] 后台执行并等待
来源：http://dali.gotoacloud.top/Article/details/gtvpfjchvm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ybcxt.top/Article/details/gtriontzmk.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtsepcefqe.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gttvlhlbvb.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gttpphfpqg.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gttqbthasz.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gttgwcqyzh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtqopjbcjn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gteypcbkmy.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtfwooygfw.html

[R40] 追加写日志
来源：http://dali.dianchejie.cn/Article/details/gtqvjfgdkq.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtkpzmxhyx.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtvocyulkl.html

cmd >/dev/null 2>&1
来源：http://dali.zhongyouzk.top/Article/details/gtejedakln.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtwkfwsihw.html

wc -l < a.txt
来源：http://dali.316326.xyz/Article/details/gtraontwvt.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtagenewwr.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gttdioauzt.html

[R44] 按修改时间查找
来源：http://dali.gogol.net.cn/Article/details/gtyibkxgwo.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtjdargsuj.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtkpbwhymz.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtjfcmfpky.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gtliwewhyf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gtqnwvuxux.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtaaxtnvfi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gthindesxd.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtfagkeqrl.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtizpzqawy.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gttwfwkzab.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtfjsvddyw.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtwregjliy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtsdtlgpgt.html

[R51] 排序去重取前几
来源：http://dali.yonumen.top/Article/details/gtrzrzilat.html


<!-- 参考信息 -->