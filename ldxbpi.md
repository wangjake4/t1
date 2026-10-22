代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtmeaygtlt.html

);
来源：http://dali.cdnleiting.top/Article/details/gtxkghpmyk.html

[Q02] 创建带外键的表
来源：http://dali.pycfn.com/Article/details/gtypurxpxd.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtbvetsnqg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtxmpiexgv.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtguvqnhrm.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtoohlygvp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ppjwa.cn/Article/details/gtnmqyynyi.html

);
来源：http://dali.nwbrower.top/Article/details/gtyudurfjc.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtvhzhpudr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gttwljvkuh.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gthjraboez.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gtvivdcfhk.html

[Q05] 重命名列
来源：http://dali.yj20258888.top/Article/details/gtroilozng.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtkxwxgckm.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gteqxvvwdn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ehwqpu.com/Article/details/gtczlejedm.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtppbfixzx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangdashe.top/Article/details/gtxydhzttz.html

[Q08] 创建普通索引
来源：http://dali.xinyue.icu/Article/details/gtzhojppka.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtlwiausza.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gthhbudvix.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtmtkzdytp.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtdxwmyvxn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtdtefpxbu.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtcwdmkkjm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtndbbziqr.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtnriqxuaj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtzhglvthw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtswgdfjbe.html

[Q13] 忽略重复插入
来源：http://dali.zhiwuduotai.top/Article/details/gtpddvorcz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.c1oappe.top/Article/details/gthbtxsobq.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gthwvauugp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gthxvoiieg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtnwobibps.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gtswlwhxcf.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtuhestoca.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtslefjxwh.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gteayrzoqx.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtzmwpkqlf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtowiojncg.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtynxnszax.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.c1oappe.top/Article/details/gtugrydelj.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtdvgjvlgl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtgiurnafc.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmlrwqyh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.9152youxi.cn/Article/details/gtsuroacgo.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtwjeyrbab.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtcdfiznnw.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtvfgruhiw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtcxhhhrsr.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gtljvkthsb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtakixkkht.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gtgcnobpmr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysrsdkhb.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gtlzllduub.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtpqdabhlp.html

[Q26] 计数
来源：http://dali.snrcjt.cn/Article/details/gtyctylvxe.html

SELECT COUNT(*) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtotawqavr.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkvmucha.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvfmlhukw.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gtubfjausg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtoxggheak.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtibjckqwy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtupdnoqjd.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtpqvghoxw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtzuiuayoo.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtuhanmclh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gtclzcckhq.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtnuxiacyx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtgymwdepg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtbbaxlxkd.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtyhrihbsi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtmphyokgg.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtwzhzhhnq.html

SELECT * FROM (
来源：http://dali.jiagoushi.top/Article/details/gtklisvqsk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtrgbangnn.html

) t WHERE rn = 1;
来源：http://dali.zdqjudy.top/Article/details/gtrvzaqhqs.html

[Q35] 内连接
来源：http://dali.fzhhl.top/Article/details/gtajiovwzv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtzhnqcbdj.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtbwzihnrk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctrfiigf.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtjqnjruhy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gthmbjubli.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gtolxwgvon.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gturmkrsfo.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtdssncovc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdujskqe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gttjzjvngf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtajhvcguk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtakszdsje.html

[Q41] 多表连接
来源：http://dali.shangyingyoupin.top/Article/details/gtbhbmeplm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtuzrfdmor.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtrvyhhjqs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtrlxglndy.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gtszzjejtc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtjnpkoeje.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgwabnmg.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtxddnkpvg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtfxcxtkff.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtmzlqgpvw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtabwxqwxh.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtjsqstqgz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtecobqksr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqtlisfk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtsbbjyeho.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtgxiplnql.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtpsmoigsd.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtolnijmru.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtulppvzzd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtoqzlulps.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtfhmeqkey.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtcwthwbyh.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gtgidlmexy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhpjtrsh.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtxhqaqfgg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtkssqfyjy.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtycrgagic.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtdyfhgfpw.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtwpxwyoxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtpaxnsajg.html

[Q54] 清空表
来源：http://dali.xuanzx.com/Article/details/gtoozdpcwt.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtvbmsueie.html

[Q55] 排名（并列占位）
来源：http://dali.wangdashe.top/Article/details/gtpgbzfkmp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtsufykkqc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtmjaurnmj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtvmareijp.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtkknkeisu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtrmbiktay.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gtfojpdaet.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtfrreaexu.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtexvkalvc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtjlpotzza.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtonhxqhfb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtqswcihvl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtlsxrzbnz.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gttijultrj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtduumnfoa.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtigbkwkej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtsphsdtsx.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gttqvfstil.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtpjdreupp.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtbdfxippb.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtqrrkwrng.html

[Q65] 回滚事务
来源：http://dali.gotoacloud.top/Article/details/gtemvlgkmf.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gtaoehuncp.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrkzwabu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaajgsjph.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtdkohrasl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtepomnjaw.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtpxsneixh.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtvigvilbz.html

ROLLBACK TO sp1;
来源：http://dali.9152youxi.cn/Article/details/gtsrjptyvp.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtsawucvow.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtljocvcll.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtlssvskap.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtbhfwwspm.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gtcsmbkfna.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtriazecme.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtfazyzsqr.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gthykjbcrg.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtrxxjbpeo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtjczbhwvg.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gtomlbfvuo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtofozxnnx.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtyhggitnm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtdeujwmmv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtsjpasvxt.html

[Q76] 按天统计
来源：http://dali.chenzaomai.com/Article/details/gtuykiyqeg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtcrfhadsg.html

[Q77] 时间加减
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaeiozbht.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtugzrgrbt.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibilvppl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtrdrqxvpk.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtojacqxmq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtzqskctrs.html

[Q80] 字符串截取
来源：http://dali.yanxiufei.cn/Article/details/gtlisrhezv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cashguo.top/Article/details/gtfkrblezl.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gtsfvicgtr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnqzz.top/Article/details/gtrwrkozlr.html

[Q82] 字符长度与字节长度
来源：http://dali.ivvv.top/Article/details/gtrgoscgig.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtqmydpwdx.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtvguclkki.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtiwyxplzf.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtwjhtfrdl.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtaikmbgjn.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtlipqhahs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.kuanghao11.cn/Article/details/gtxwzdtozm.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtqfvniajv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtxgeffxfn.html

[Q87] JSON 字段做条件
来源：http://dali.gzhubu.top/Article/details/gtgcodwbhl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtmwdhivny.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtqghmbesw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtywyzmrrl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.bjfxy.top/Article/details/gtqprwivqu.html

[Q89] 判断表是否存在
来源：http://dali.aibaodan.cn/Article/details/gteqwlhvfq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtyerlvgaq.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtiiodtfpa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamzrzojh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqevgbynp.html

R. Bash 专题
来源：http://dali.gotoacloud.top/Article/details/gtarxzgfvz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfhatpqui.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiggvxgx.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtttkaokon.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtzmwzlgkx.html

[R02] 变量赋值与使用
来源：http://dali.hywenlv.cn/Article/details/gtbaqmysnn.html

name="Tom"; echo "$name"
来源：http://dali.ybcxt.top/Article/details/gtiwlkuvba.html

[R03] 只读变量
来源：http://dali.yj202588.top/Article/details/gtuxshxjnk.html

readonly PI=3.14
来源：http://dali.daria6918.cn/Article/details/gthffmvpyn.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gteuossdik.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gtpvspzgpl.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gtzpsjflxf.html

name="${1:-default}"
来源：http://dali.nwbrower.top/Article/details/gtxgbsxqle.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtimolpvzw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtabfagpdd.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtryxprmzo.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gttwknpvcm.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtwzmqhuet.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtpxvpdlau.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtkuxsguvj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gtyjwkxyxc.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gthdnqyfca.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtmvmxgcjj.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtzwgopzqg.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gtxznbkxop.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gtmygeurzk.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtrfkpcxav.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtwxbmwmfz.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwiimkrs.html

[R12] for 遍历文件
来源：http://dali.xylfe.cn/Article/details/gtjgcsttcb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtsjamazbk.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtxzklyocp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.bjfxy.top/Article/details/gtsigjelnz.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gteqitsuxv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinqigufen.top/Article/details/gtlsiryxow.html

[R15] while 逐行读文件
来源：http://dali.sxryk.cn/Article/details/gthrtyitsl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhoulong.xyz/Article/details/gtoduqzygq.html

[R16] until 等待条件
来源：http://dali.shuidangran.top/Article/details/gtyisszvgf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtxduiwokc.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gtohvibsjv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtvhdrklfu.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtitggpgqc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtolmvhldj.html

[R19] 数组长度
来源：http://dali.dianchejie.cn/Article/details/gtleyciskm.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtggrpdspf.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtfsbebzvk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigfzy.top/Article/details/gtethclnee.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtonulbdbr.html

echo "${#s}"
来源：http://dali.sufxvd.cn/Article/details/gtrygrcdww.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtxbzudroo.html

echo "${s:0:5}"
来源：http://dali.tanke756.top/Article/details/gtezrxisor.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtmvvvdorz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aibaodan.cn/Article/details/gtnpbpxwmo.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtbyyiksuv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhixingplan.top/Article/details/gtbepeupzc.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gtosveqseq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gtlzvzqzsm.html

[R26] 命令替换
来源：http://dali.hnqzz.top/Article/details/gteaoiocyd.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtfjvmywkq.html

[R27] 算术展开
来源：http://dali.xziqi.cn/Article/details/gtlwjissvb.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtdjywgtyl.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gtfcoinpee.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtqehovbvc.html

[R29] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtsghwwsdu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtuiqlhcol.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gtgulshrmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pycfn.com/Article/details/gtnxyzkhzi.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gtuulzucde.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtuhgmlvhw.html

[R32] 参数个数校验
来源：http://dali.iojbl.cn/Article/details/gtcpndahlw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbutkrhpn.html

[R33] 捕获错误并提示行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtsbchdqub.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtmqhnywlk.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtnubipibg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtjihhfvko.html

[R35] 后台执行并等待
来源：http://dali.yvedp.cn/Article/details/gtqthjppbd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ehwqpu.com/Article/details/gtmkpjyoep.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtgspwzpxl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.9152youxi.cn/Article/details/gtpecwctic.html

[R37] 把输出赋给变量
来源：http://dali.jqgufenzy.top/Article/details/gtpgfgqbft.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtlybhtizj.html

[R38] 管道串联
来源：http://dali.aizwys.cn/Article/details/gtdirrhdyy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gterjhpegw.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtjtumsztw.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtbdebsltq.html

[R40] 追加写日志
来源：http://dali.zhixingplan.top/Article/details/gtjwfcxgbj.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtmzvqspyk.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gteljkeigv.html

cmd >/dev/null 2>&1
来源：http://dali.hnxiangtu.top/Article/details/gtasncsojx.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtaymaaahj.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtsjxnuntq.html

[R43] 按名字查找文件
来源：http://dali.guowangkeji.top/Article/details/gtofqbiqmk.html

find . -name "*.log" -type f
来源：http://dali.nwbrower.top/Article/details/gtlwsjrhbx.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gtoxwyezjj.html

find . -mtime -7 -type f
来源：http://dali.zdqjudy.top/Article/details/gtvqndywsp.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtokpopjxn.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtrpyrakny.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtxtklglfg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtinpavsxn.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gteheksthr.html


<!-- 参考信息 -->