代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gthfpostwq.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtxgwywchm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtgowztzgg.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtnozyrmxy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtpxkncqrz.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtgevqdeie.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtzknxnpaj.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtbscftbei.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtrfnyzpcw.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyksvvjed.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtgbcirtic.html

[Q10] 插入单行
来源：http://dali.yonumen.top/Article/details/gtngtnnboe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtuemmxsgb.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtzovtsozy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtijpcmcvs.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbibkoeha.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtxfsblfvf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gtrlixiujj.html

[Q13] 忽略重复插入
来源：http://dali.jinqigfzy.top/Article/details/gtcjlsjslz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtlkwqbbnd.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gtalmtchbk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gthnckrkac.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtznqpuywk.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtfjbmowht.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtfwsuffsm.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtemdydexv.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmlumaxmp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gtxbkhvuho.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtgafkljfy.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gteplqzmsp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtximgfbmd.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtobfelebj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtbbmlzlxt.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtwqtcvvwe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjkrufaz.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtokrnqqga.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsoalovu.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gtrpblznem.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gttkuylupm.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtnzpdqrte.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gtpinhaxrc.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtqoxfoenx.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtaiycayzu.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtudbxhukm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gtkuabhwfg.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtfgmdqpvh.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gteddckxao.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtiwiipodr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtxlpfapbh.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtegfaopfq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtwnnagrdp.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtchptltho.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtldycxuqg.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtqaiukwcx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtxhwpsabh.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtlnyihzyj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtdcvsrj.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtwllfbrwf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtqcedbfhg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cdnleiting.top/Article/details/gtyzingyha.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gtfnnlmnzt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtqhpboadr.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtlhivafmz.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtatkzdygt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtlfcoxify.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtdrqfsquc.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gtutmtdeki.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtsilyneyu.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtwlshytch.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhoulong.xyz/Article/details/gtzzhyybjr.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtjnazgspt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zycfv.cn/Article/details/gtgchfhfka.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gtopwmltvf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtahelwocw.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtqjdmrrsd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gtubhqdihy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnssvcrms.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtdytupzlj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgufenzy.top/Article/details/gtzrgfphqx.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gttwunaheu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtpxdivtfh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gtsgafumyu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtdhbqqokp.html

[Q42] 连接条件附加过滤
来源：http://dali.dashuyun.cn/Article/details/gtzdihmglj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtrugyfvjm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtfcrtliqc.html

[Q43] 标量子查询
来源：http://dali.sxryk.cn/Article/details/gtdlvqxeyf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gtpclftylq.html

[Q44] IN 子查询
来源：http://dali.hammf.cn/Article/details/gtvtzdcpui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtmbwnavmq.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtvsqftysm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gthzqwzfsd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtoksdkjut.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtdgfokeaq.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtjfsksckt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gthglcolvr.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtepzsicee.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtkxvxdjvz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtysqszdsk.html

[Q49] 更新单行
来源：http://dali.xziqi.cn/Article/details/gtrjxgnxjw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtgssuncsl.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtcmhhfgpm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuhkzrtb.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtfabvrurq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj20258888.top/Article/details/gtbvtfxwhf.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtkwqbjkcg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtlhbkiwga.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtxaqyebkn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtlccaabea.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtoqjlfkau.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtochqqkqc.html

[Q55] 排名（并列占位）
来源：http://dali.chenjidiqi.icu/Article/details/gtgbwzwdzt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gtkcgqbgbw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtgethlmyf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtabkqiicf.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtnssdztwj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtkeyiscgt.html

[Q58] 累计求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtfddapsld.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gthnhkmgdu.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtxlrwlcww.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtcguscvxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtzomocomj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtqihrgkop.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthnxicwke.html

[Q61] 移动平均
来源：http://dali.ybcxt.top/Article/details/gtpcerndwn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtthjhorcb.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtzsbcqpcd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtdhmtdtaj.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtbdfmngue.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtqxwweofz.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gttwlotbee.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtuturdcwz.html

[Q65] 回滚事务
来源：http://dali.jianghu66.top/Article/details/gtawratobd.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gtexrcmksr.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtmlbjkkyl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtlcezgghh.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtdoxsxnfn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtrebksylx.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtxcoziqin.html

SAVEPOINT sp1;
来源：http://dali.yueranfly.top/Article/details/gtauqcehzs.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtckkvxsoa.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtkxvsdikk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gttgyzusng.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gtkexmmbkr.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtfcakrnxo.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtlnptwkhy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtwhhnjcan.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gthnzznseb.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthkvygpsh.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtvviqioow.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdluiewkg.html

[Q74] 强制使用索引
来源：http://dali.zycfv.cn/Article/details/gtaqnswexe.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtxhsitsxs.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtgvwyeepz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtshfmmqra.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtxfqkcevb.html

[Q76] 按天统计
来源：http://dali.ydzc1.top/Article/details/gtfphstezq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gaohongyu789.top/Article/details/gtswxtjqaw.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbvrfwkml.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gtddyrlfgv.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gtpzbbytnc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtrlmeavkt.html

[Q79] 字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtlxeraipf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shuidangran.top/Article/details/gtrfqconcx.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtamiabxlz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtoobntckj.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gtounvuuuj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtakvrjxzt.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtejynpivv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiqdctfh.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtypaszyfj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtqfatrzwa.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtethwypup.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtmftvekfu.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtohcuijck.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yueranfly.top/Article/details/gtcwtwfxna.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtirbfksfa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtudsjpuen.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gthrduwdjp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtjhavinrh.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtufzqqdfs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtycbszcwi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtxqdgifqp.html

[Q89] 判断表是否存在
来源：http://dali.yj20258.top/Article/details/gtxzkfpjgp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gtzzuajofr.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtflwfjjxk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtudrtlleg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzeohdlin.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtxkptrmus.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjhvyowlj.html

[R01] shebang 与严格模式
来源：http://dali.yvedp.cn/Article/details/gtzosegupj.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtpqkjzhho.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gthdbpgwwt.html

[R02] 变量赋值与使用
来源：http://dali.shuidangran.top/Article/details/gtaahglhas.html

name="Tom"; echo "$name"
来源：http://dali.fengsongda.top/Article/details/gtdqmzvhle.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtknwbjluy.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtmvbedvym.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrgwpvtb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtkdcyhgkr.html

[R05] 参数默认值
来源：http://dali.jqgufenzy.top/Article/details/gtheppbssg.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtrunweouo.html

[R06] 判断命令是否存在
来源：http://dali.ivvv.top/Article/details/gtqxlqpcvx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvxyeyqi.html

[R07] if 判断文件
来源：http://dali.ppjwa.cn/Article/details/gtrhywhsbj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtagjzfrvu.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtkbwtvjax.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtyvohmwuf.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtofizuznj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gtzdkjxbua.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gtwupehzio.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtlpmgjnre.html

[R11] case 多分支
来源：http://dali.yangfankeji.com/Article/details/gthjrvxclf.html

case "$1" in
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkrkavye.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtqtuoaacu.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvhjcttv.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtesmavrit.html

esac
来源：http://dali.hysaishi.cn/Article/details/gtuowfkjuu.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gthsnjslpk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtqqmwkjzz.html

[R13] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gtsarzoipo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtnznvwtdv.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtyzzuzghf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtszepebjq.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtfbjmwxgy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gtlyskcebh.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtfcgebdeb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtteoykyxj.html

[R17] 数组定义与取值
来源：http://dali.haohaochexian.top/Article/details/gttpmjarpd.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtbkzppjgt.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtyefpqbeq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtirbbfyhk.html

[R19] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtlxyfyzjp.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtdcfzysiy.html

[R20] 关联数组（字典）
来源：http://dali.jqgufenzy.top/Article/details/gtmmbvwvha.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jlsjyb.cn/Article/details/gtsuecchbw.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtxmfwavet.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gthfqdwdje.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnarpucyz.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gtppmudqly.html

[R23] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtwyjixttj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gthygddrct.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtmmhkmulr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gtqycuhyaf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtptammsfe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtxtkrjakp.html

[R26] 命令替换
来源：http://dali.jqgufenzy.top/Article/details/gtemliqifb.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gteogncrqz.html

[R27] 算术展开
来源：http://dali.smart0.xyz/Article/details/gtotprqhjn.html

echo $((1 + 2 * 3))
来源：http://dali.dashuyun.cn/Article/details/gtqjxwpmoi.html

[R28] 浮点运算
来源：http://dali.hammf.cn/Article/details/gtsbwoddwe.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtovgozsbp.html

[R29] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtmanrbedk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtgbqnauxa.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtigwvfuhv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtqtnudpzg.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtllxkmcux.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtwpnnalwj.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtixbopxgc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtivfigwnv.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtvmuhcvgh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gtgqotvaly.html

[R34] 退出时清理
来源：http://dali.tianlin.xyz/Article/details/gtxfydfcfa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtgipuzztv.html

[R35] 后台执行并等待
来源：http://dali.bjfxy.top/Article/details/gtgiyiktco.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtykulsnam.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtljexaqna.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtehmqofwy.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtujjvcwwn.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtztgmsqrg.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gtxoeadwyg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gteenqyldz.html

[R39] 重定向标准输出与错误
来源：http://dali.redwolf501.top/Article/details/gtiiebzwmm.html

cmd > out.log 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtdduwmecc.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtukgkvdgh.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gttuiujaib.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtsziinncg.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtxfmxysyd.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtfmbfvqlv.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtjesqdmhr.html

[R43] 按名字查找文件
来源：http://dali.nanxuanxn.top/Article/details/gtvcilvvil.html

find . -name "*.log" -type f
来源：http://dali.chenlongwang.top/Article/details/gtgemdxjsc.html

[R44] 按修改时间查找
来源：http://dali.xinyue.icu/Article/details/gtptylvxbn.html

find . -mtime -7 -type f
来源：http://dali.0kj1m.cn/Article/details/gtlnvgemdq.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtkviaigct.html

find . -name "*.tmp" -delete
来源：http://dali.tanke756.top/Article/details/gtgbgxnrzf.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gtysozfbne.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtpfipyujf.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtshfbreqb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxxrukqo.html

[R48] awk 取指定列
来源：http://dali.daria6918.cn/Article/details/gtpeqwteqw.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtjkmhevtu.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gtigwnmmtf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hammf.cn/Article/details/gtmomlgyfb.html

[R50] awk 求和
来源：http://dali.svipenyu.cn/Article/details/gtvkaaqunz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gttfcwpxzz.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gtpuxjajio.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hfpthk.cn/Article/details/gtjovkpajm.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtwtwthymp.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtroonpyyd.html

[R53] 查看文件头与实时尾
来源：http://dali.cashguo.top/Article/details/gtynucztag.html


<!-- 参考信息 -->