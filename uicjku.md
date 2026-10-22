代发 wailian999

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uynjfbxf.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gt2earcymbi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2zhnzwwou.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2jgeypunk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gt2upugkduz.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gt2fzinbgeu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gt2yhdvyctg.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2ceymedsi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2iiohcrpy.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gt2bfrvyiso.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2qsedziko.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2ciambskv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gt2oemyhlyp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gt2mbidqoss.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2baahqdrp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2uyebbvhe.html

[Q14] 存在则更新（upsert）
来源：http://dali.sxryk.cn/Article/details/gt2arsatvyl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gt2ncidubew.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.c1oappe.top/Article/details/gt2aodzvwmw.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gynhsyuf.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2rkqpbwbq.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gt2aaccpino.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2wniqtdwa.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2lyxlnkvg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kktczexl.html

[Q18] 模糊匹配
来源：http://dali.yanxiufei.cn/Article/details/gt2fnwsccck.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gt2uognfkqc.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2oskrjtzk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gt2rzxzkdve.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gt2faakwnng.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gt2xbnomwmi.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2nqhxwvle.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2ektyjwjx.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gt2hdliaysx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gt2ogmkaqfv.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2vawnniqk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gt2nxitlbph.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gt2omihlpwo.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qbfpsphj.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gt2keiqminy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gt2emfcobhh.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gt2ygbvgqet.html

SELECT COUNT(*) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2aysnurna.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gt2ruwfurvx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2byzhmbfu.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gt2fnxiduov.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2qcjzgiah.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlwoxfv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2mpdkurxi.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gt2ktjapwik.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gt2ruyqlwqv.html

[Q31] 分组后过滤
来源：http://dali.cheryme.top/Article/details/gt2iuipnawn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgwjjda.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2usapitcd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2waagwifh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gt2cxoaoblq.html

[Q33] 多列分组
来源：http://dali.haohaochexian.top/Article/details/gt2lapikzel.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gt2mzuvqxoz.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gt2lhlvucfv.html

SELECT * FROM (
来源：http://dali.redwolf501.top/Article/details/gt2mgvyvqfh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gt2vnhskgtc.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmdogrwi.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gt2kuezsohb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2ihuxqzsg.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gt2vtdupeyj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2ynjatwxe.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gt2gpjdauyf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gt2eqgatjom.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gt2kuhrxnsa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gt2xkhyiglf.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gt2crvhmufm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2wpjynmcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gt2hdogzmzg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gt2tphyqbnc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gt2jaibemcz.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gt2ztcuszpu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tian-w.cn/Article/details/gt2jduznhag.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gt2fleirbny.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.iojbl.cn/Article/details/gt2yfvtblqg.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2gqnogwhl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.andypj.xyz/Article/details/gt2bjmqjkkm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ceyyazyg.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijtrnzkb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gt2hnfemohb.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gt2otkvmhar.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gt2nldqxxdk.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gt2huwemjiy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2veyftedc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gt2cbrjmqgy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2nhcfwypa.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gt2yqktobqc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gt2ggfqzuyl.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gt2bdkmmssn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gt2wvvzooha.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gt2olhavund.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2mxmdhkdq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2tntaxvqd.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gt2wqnqccdr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2cakpnwpg.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gt2nmmhoccn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gt2eyscomlz.html

[Q52] 删除指定行
来源：http://dali.yvedp.cn/Article/details/gt2ziebaikm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2cgmsfudw.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gt2nhmxdoxa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2ggetnkep.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gt2rwzfbpjz.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gt2cfbglyqx.html

[Q55] 排名（并列占位）
来源：http://dali.sufxvd.cn/Article/details/gt2vmcrmahx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqzjfeo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gt2xohvpkgv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangdashe.top/Article/details/gt2bowbolup.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gt2rgigewju.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2ecnuneyq.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2mcbfjahf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2ifptkqzv.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gt2zoqgvaph.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2rcczuutn.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbdgoekb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gt2uskjspms.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2bpzujmmp.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gt2dnglnbhh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2bvtvujhu.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gt2rvjtcedb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2zzisgkfg.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2ekwldrfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gt2qicvhqrg.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gt2gbtfoptp.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvnsqsvk.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gt2ciglwuxw.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gt2ynwkensx.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njffjhee.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gt2urtwsjrc.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gt2exxtqpuy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhaqzsss.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gt2bigxnsnn.html

SAVEPOINT sp1;
来源：http://dali.xuanzx.com/Article/details/gt2ttudfmyp.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gt2jpnlhnbu.html

[Q69] 查看执行计划
来源：http://dali.aibaodan.cn/Article/details/gt2bbkdclvb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gt2sechytlv.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygxvszls.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvkdlbij.html

[Q71] 查看建表语句
来源：http://dali.haohaochexian.top/Article/details/gt2vucnqwej.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gt2kuycndht.html

[Q72] 查看索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsvitqiw.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2tyqsngqn.html

[Q73] 查看表状态
来源：http://dali.guannengcc.top/Article/details/gt2orghitrx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gt2dgkswfrn.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2oibzxgrd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2lofbdxsr.html

[Q75] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2texpevjj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2zbrtjxvb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gt2athbfogn.html

[Q76] 按天统计
来源：http://dali.cashguo.top/Article/details/gt2mhklgraz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2troxvzur.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gt2zdozuhqz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guannengcc.top/Article/details/gt2npglntii.html

[Q78] 当前时间
来源：http://dali.jqgfzy.top/Article/details/gt2mqcblrhs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gt2owqxnhnz.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2ffpafnlk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gt2wpmcxeyd.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gt2pepdhffy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2frkinluu.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chdqmevi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypbhfmht.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gt2zqxidcaq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2kjxtujmb.html

[Q83] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2wplbtlss.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2fnwuwoyl.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2sybbfxhd.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnzexblj.html

[Q85] 数值取整
来源：http://dali.jlsjyb.cn/Article/details/gt2uvywxvvo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aibaodan.cn/Article/details/gt2zywsnokw.html

[Q86] 读取 JSON 字段
来源：http://dali.0kj1m.cn/Article/details/gt2wmyoffln.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gt2cpijgjvg.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gt2dngmensx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gt2ocgilmxt.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2mavktyhv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2rfqcoozb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.316326.xyz/Article/details/gt2umccrqam.html

[Q89] 判断表是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlwpowlk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gt2taecfrgs.html

[Q90] 生成序号列
来源：http://dali.yuanzhike.top/Article/details/gt2vylbbacn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lxxsytlh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hpcronlo.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gt2oakvgwon.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2lnxjjyro.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cngqimjp.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2qvptpyga.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gt2dnjctvam.html

[R02] 变量赋值与使用
来源：http://dali.ppjwa.cn/Article/details/gt2gwodfwjw.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2dybrvtec.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gt2tvjlfcmj.html

readonly PI=3.14
来源：http://dali.aizwys.cn/Article/details/gt2tflqkyuu.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gt2eewmbfus.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gt2gdmnqqat.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gt2oapwtoso.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gt2ntoznzuc.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gt2uphzvwcz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2winnckwo.html

[R07] if 判断文件
来源：http://dali.sufxvd.cn/Article/details/gt2ndifknrt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gt2lgqcrwzx.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2esbhdrxq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2aettyvwq.html

[R09] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gt2xqxvmdpg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gt2tooevawv.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2efwfnnzg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gt2apdjwvwu.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2rzezkdww.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gt2wsumasnx.html

start) echo "启动" ;;
来源：http://dali.xinyue.icu/Article/details/gt2dkhycram.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gt2sctbtsfs.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ysrhgeoa.html

esac
来源：http://dali.meibo888.top/Article/details/gt2mnicnpce.html

[R12] for 遍历文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdxfhuje.html

for f in *.txt; do echo "$f"; done
来源：http://dali.aizwys.cn/Article/details/gt2lgraaaon.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gt2jqlbmdrh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gt2hkhhcymn.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2sagujynz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.andypj.xyz/Article/details/gt2ihgdagih.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gt2ymqdeuxb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zycfv.cn/Article/details/gt2olclyapd.html

[R16] until 等待条件
来源：http://dali.mhx1999.top/Article/details/gt2ljocuxzs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2jvzckkzh.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2lqlcxzfy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gt2nyzqauzr.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gt2kuaytlfz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2kgresiob.html

[R19] 数组长度
来源：http://dali.chenlongwang.top/Article/details/gt2qcyslsaw.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfqtsjuu.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gt2wtxmoblk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajenypia.html

[R21] 字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gt2ymrqnbwr.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gt2hnjgckwe.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2nuysscvp.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2abzwpvcb.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gt2akmmujzi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhengqikj.top/Article/details/gt2dfrjdssr.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2wwvxgblc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenzaomai.com/Article/details/gt2vfppbysu.html

[R25] 去后缀 / 去前缀
来源：http://dali.bjfxy.top/Article/details/gt2bndoosrg.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gt2hibtykmg.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdzhpcwc.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gt2eahsurwa.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gt2zkucdrbi.html

echo $((1 + 2 * 3))
来源：http://dali.yuxming.cn/Article/details/gt2lsrfvhqg.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gt2vtvxzowa.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gt2yttbhmbi.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2fakalnah.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jyoumei.cn/Article/details/gt2kcssqawa.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gt2jmdbekjh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hfpthk.cn/Article/details/gt2kbajogjz.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gt2kswholom.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gt2pvsoeedj.html

[R32] 参数个数校验
来源：http://dali.mhx1999.top/Article/details/gt2cbnuatbf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gt2jrwwfxfd.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gt2vrtzysgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gt2dtzmvilp.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gt2cpdlzybk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkrywyip.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gt2zwkxvxkc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpjccopp.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gt2hupfewrp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gt2ermuywfy.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gt2ivwnykeg.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwqrqcrd.html

[R38] 管道串联
来源：http://dali.tianlin.xyz/Article/details/gt2yyslokjh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gt2cutxftks.html

[R39] 重定向标准输出与错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbrmyeew.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gt2jgvnnspk.html

[R40] 追加写日志
来源：http://dali.redwolf501.top/Article/details/gt2figaatxp.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbvldkae.html

[R41] 丢弃输出
来源：http://dali.chenzaomai.com/Article/details/gt2mbvvctpp.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gt2hucymwgt.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2xfsdsewr.html

wc -l < a.txt
来源：http://dali.pycfn.com/Article/details/gt2chwzyhhc.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gt2traeyoqm.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gt2taqbprmy.html

[R44] 按修改时间查找
来源：http://dali.zycfv.cn/Article/details/gt2uamkrhfq.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxcveifv.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gt2qlykyklv.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gt2tufjbkaw.html

[R46] 递归替换文件内容
来源：http://dali.nanxinkj.top/Article/details/gt2ovjnpcyu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gt2adcvfczt.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2qncgzmga.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkjpwidd.html

[R48] awk 取指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrsoqbto.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2maegbeat.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gt2ovpnxckf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.9152youxi.cn/Article/details/gt2pidwxftp.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gt2zuxfxygo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gt2ulbhmwxt.html

[R51] 排序去重取前几
来源：http://dali.jqgufenzy.top/Article/details/gt2gdezfziv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gt2xsxkfsun.html

[R52] 统计行数
来源：http://dali.aizwys.cn/Article/details/gt2omwjkfsz.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gt2wxipjkfo.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gt2thsqskgf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gt2dvkthbmk.html

[R54] 比较两个文件
来源：http://dali.sufxvd.cn/Article/details/gt2hohaxegp.html

diff a.txt b.txt
来源：http://dali.wangdashe.top/Article/details/gt2rfeyofri.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gt2suvymodv.html


<!-- 参考信息 -->