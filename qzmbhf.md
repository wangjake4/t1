代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtomdqxabm.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtdoptgrtd.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtcatkunvr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtshcaloun.html

);
来源：http://dali.yongpay.top/Article/details/gtnwmthnyh.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtmvqkavhw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtpjrznzxq.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtszqriiyj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gtmnsyhzxa.html

[Q05] 重命名列
来源：http://dali.hongshengwenyu.top/Article/details/gtjwsfibrp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtlxlofujq.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gtmclhgktx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtkjoeeisd.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtoajtzfwa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gttwoddwux.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gthvptdfqo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtiajzvqkh.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtapgmnuks.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtvrfscjbi.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gttvzzzypq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtqkxvqykg.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtuhqejabp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtnzhryhxh.html

[Q12] 插入后取自增 ID
来源：http://dali.mhx1999.top/Article/details/gtpscoapkk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtxvjepogr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.meibo888.top/Article/details/gtxgoeetim.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gtubnfdttl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtfzbkhqhq.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtyvjrhlhg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gtavctipox.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtbhdlqngz.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtosqmpzxo.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtdsuimwag.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtgekuapwd.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gtiidyjurr.html

[Q17] 条件查询
来源：http://dali.zhongyouzk.top/Article/details/gtpfzepkcw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtzgbljhwq.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gtmaqnarsr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gthzoocwoc.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtppcixgoc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtnnvxwoml.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtawepbrgv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtfzsakrnh.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeqdfhao.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtppvzoana.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gtrohbiyee.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtdfgdbdid.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtvtgqppgt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuanzhike.top/Article/details/gtikoatpzd.html

[Q24] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtwslnjhng.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtsqjyrpdq.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gtkhjfjexn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtfgrntthx.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gtmbuydabw.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtylnkwzys.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gtfrtyrohm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtxdfayzse.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtindjhrxt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtdioplcbq.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gtetaepvlv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtqrwuyaxv.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtxhwthvnt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtopihfsvc.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gtqcydaldv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbsubkgu.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbpogmyi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtzqoifukm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtudcqlxkt.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtpfoijsyn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtjnwthgva.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtmveganpu.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtlfrjjutn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtqofnxhse.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtntjnfrfc.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtfzgkxlwt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtnapenkpg.html

[Q36] 左连接
来源：http://dali.chenzaomai.com/Article/details/gtzhxguijy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtoxldgvji.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtpyhvlrnv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gtaxhzrvqq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtqggdteke.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtxkpgpvsd.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gteuaikuzn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fengsongda.top/Article/details/gtsnqpyvyl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtpcqnovtl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtygvalgtk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtpsxuiaxj.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtmljbborz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtfdqhyvpc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gtehdmxnjt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbvzawrm.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtneqnayud.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtyigrxphl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sysykeji.top/Article/details/gtgacippnf.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnplygot.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gtcauntdpc.html

[Q44] IN 子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtggnkttej.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmyrvyyu.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtylihoqwu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtksaflgyw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gttzrohdrh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtzovquubf.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtvuerypsq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.nwbrower.top/Article/details/gtgzysxbgw.html

[Q48] CTE 公用表表达式
来源：http://dali.shzxlz.cn/Article/details/gtdieziyay.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zycfv.cn/Article/details/gtjrqiyusu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtdbfziuts.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gturqaglke.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtmgotjvhc.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtrzyziemn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtifvrimpw.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtbnkkbmdo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gtyqkicepx.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gthybxgplb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtuqawfxol.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtxistfitt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtskhfcjsm.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtmiovattv.html

TRUNCATE TABLE logs;
来源：http://dali.fzhhl.top/Article/details/gtbfhmdcje.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtdzcylctp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gtbkbweijs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtpftpzuni.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtqckdnyjk.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtyxrciszj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtkiflnlfd.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtwwffoyjg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtkfgayqkf.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtzjhvhhqh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtoagdmvoe.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtxczuwgia.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangshuangyany.cn/Article/details/gtmozlqdfu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtytzysxbl.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gtktckviis.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtptiohymh.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtqchmoavx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtscqnajuh.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtsbziyivu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gtmafuilyi.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtaztjwpum.html

COMMIT;
来源：http://dali.jqgufenzy.top/Article/details/gtfnrtwtph.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtpqmgrdfn.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gttrcnevxb.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gtjraxqojw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtsbwlutrb.html

[Q67] 设置隔离级别
来源：http://dali.xziqi.cn/Article/details/gtkhfjeyvs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgfzy.top/Article/details/gtoleyzhgv.html

[Q68] 保存点
来源：http://dali.gzhubu.top/Article/details/gtumivfiwv.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtdszntwgf.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtjoqqxxwr.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtnzvnbeuq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtwqpsbdsz.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtedwjbazc.html

ANALYZE TABLE users;
来源：http://dali.shzxlz.cn/Article/details/gtumdnyens.html

[Q71] 查看建表语句
来源：http://dali.zhoulong.xyz/Article/details/gteqywkjkr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtxhkbalpw.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtjdsnadyr.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtkfbqewbt.html

[Q73] 查看表状态
来源：http://dali.nanxuanxn.top/Article/details/gtcmiwdyrs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtidulyjpf.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtopedtlzp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtuidaphjp.html

[Q75] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtgbqixepn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtlzkvzptv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hfpthk.cn/Article/details/gtbhcofoau.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtzaesqjng.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtommkzbcz.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtplouothu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sxryk.cn/Article/details/gteicgdhgr.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gttptrdhdp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtndoexm.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtcgfioxjf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cqqwz.cn/Article/details/gtgfyfiakk.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtdxaweggu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gtnnnfquov.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtcplxaewv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtreakuarb.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gtcatpjrci.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtgfepbipc.html

[Q83] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjvxdvsn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtleyaisif.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtgrqwfkea.html

SELECT TRIM(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtddtpsvtf.html

[Q85] 数值取整
来源：http://dali.feifeiyinyue.top/Article/details/gtczqwwdkv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fzhhl.top/Article/details/gtveqvhqqp.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gtxjphpzml.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtjxpukmwl.html

[Q87] JSON 字段做条件
来源：http://dali.sweek.top/Article/details/gtgqrtxiew.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtaoqbaikk.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtosupvdjb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sweek.top/Article/details/gtzgkysojl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ybcxt.top/Article/details/gtuinxogxh.html

[Q89] 判断表是否存在
来源：http://dali.birdmap.top/Article/details/gtefxvffgk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtbktpwyjt.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfrmpcal.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuetiantiany.cn/Article/details/gtixuxzgep.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmmwqqwcx.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtfpxqobyd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwuaonatl.html

[R01] shebang 与严格模式
来源：http://dali.zhixingplan.top/Article/details/gtjgikdylm.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtabtlxehk.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gttdvmwaji.html

[R02] 变量赋值与使用
来源：http://dali.daria6918.cn/Article/details/gttqeqkowi.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtelyfumhx.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gtibwwyrou.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtyrexgmho.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtulqnrpes.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hfpthk.cn/Article/details/gttkarvzso.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtbgfykpov.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gthegyhoqe.html

[R06] 判断命令是否存在
来源：http://dali.fengsongda.top/Article/details/gtqnksttma.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtbpynlegz.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gtjpxuffst.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtwdlvysfw.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtgdvhxulv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtszwskuti.html

[R09] 字符串比较
来源：http://dali.sysykeji.top/Article/details/gtbowcgwth.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gthiqwnmoa.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gtrkubvgjx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtrjntjkpc.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtkuktokzg.html

case "$1" in
来源：http://dali.redwolf501.top/Article/details/gteebzrxgj.html

start) echo "启动" ;;
来源：http://dali.hammf.cn/Article/details/gtteiqxrti.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtmcpuuzjx.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258.top/Article/details/gtaubbytbj.html

esac
来源：http://dali.quarkkingdee.top/Article/details/gthfsighwv.html

[R12] for 遍历文件
来源：http://dali.hywenlv.cn/Article/details/gtiayfejog.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gaohongyu789.top/Article/details/gtnszqnrci.html

[R13] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtvbofbhmx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtaoojyvhd.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtllseewcz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsalfpukl.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtrdojmlwt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gtmizhtwmn.html

[R16] until 等待条件
来源：http://dali.jianghu66.top/Article/details/gtmlpxrreq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtihhpopkq.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtlxficvpe.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ydzc1.top/Article/details/gtgyirvcna.html

[R18] 遍历数组
来源：http://dali.guowangkeji.top/Article/details/gtvjnzhnay.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtvaqtwppx.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gttdbsytzz.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gtvfpjqgda.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtxdrnhden.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtolyvfdtf.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtzulfbtfo.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtgxzqjlpz.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtafjrdedv.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthglhnyjp.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtiisgsvde.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sweek.top/Article/details/gthktladtr.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtnqeowegr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtumunyypz.html

[R25] 去后缀 / 去前缀
来源：http://dali.0kj1m.cn/Article/details/gtjgbnmfgo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangdashe.top/Article/details/gtaqrrlbgy.html

[R26] 命令替换
来源：http://dali.ehwqpu.com/Article/details/gtopzgzwyv.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtoypsflqp.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gthhfgwfbe.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtfumvhzkz.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtlcknmidn.html

echo "scale=2; 10/3" | bc
来源：http://dali.svipenyu.cn/Article/details/gtsmhhqqio.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtdcyppici.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtfvyaorcm.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtcxjmohgp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gtgeltojwp.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsarrnlyb.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gtvaycebiu.html

[R32] 参数个数校验
来源：http://dali.yangfankeji.com/Article/details/gtxuppbwpf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtlautgzfo.html

[R33] 捕获错误并提示行号
来源：http://dali.hnxiangtu.top/Article/details/gtaikhgqww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtyeptfhhi.html

[R34] 退出时清理
来源：http://dali.fzhhl.top/Article/details/gtrbxtktbv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtgzeqmsfm.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gtipzuygtz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtqxkqazxj.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtxjsyzsal.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxfkowfc.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtzzvduzsk.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtazufrobw.html

[R38] 管道串联
来源：http://dali.cheryme.top/Article/details/gtcsykyxye.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtgbxqjzah.html

[R39] 重定向标准输出与错误
来源：http://dali.gaohongyu789.top/Article/details/gtmutuflxp.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtybnsiidi.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtyiekhtlz.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtfwmwkxjm.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtcfaugpsq.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gtttpjgzkp.html

[R42] 输入重定向
来源：http://dali.guannengcc.top/Article/details/gthfuaoalt.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtmdgzposb.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtybwwxfjf.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtnccgegos.html

[R44] 按修改时间查找
来源：http://dali.tianlin.xyz/Article/details/gtmjoghpyw.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtgmnxssae.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gtzyezzyyz.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtlhvjmbeo.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtlioaasae.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.quarkkingdee.top/Article/details/gtemxngkre.html

[R47] sed 单行替换
来源：http://dali.jlsjyb.cn/Article/details/gtvipwytvh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtpgchnoev.html

[R48] awk 取指定列
来源：http://dali.ppjwa.cn/Article/details/gtujzyzzgu.html

awk '{print $1, $3}' a.txt
来源：http://dali.nwbrower.top/Article/details/gtjxgzfsxm.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtujssanbe.html


<!-- 参考信息 -->