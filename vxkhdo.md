代发 wailian999

);
来源：http://dali.zhijiandao.cn/Article/details/gtcsdaxrzt.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmjcwohb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gthbeacgkl.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtbmrvsvut.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gtmcyrwrwa.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtcaoobccy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtmkpxhlgv.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gttygipylr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtjdflfsyb.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gthwivgtgi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtrudfnzew.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtfzpflfoq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gteghrozfd.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtdrwnerdq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtsqubefzv.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gthvsbeubc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gthsdpwqyi.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtulbbatmt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gthvvhjxmd.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtkmezumxz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtndiuafcx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtogjpbvxr.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtuxqwcinw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojruulfg.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtqnezduza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gthpoqbvmj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqaqicys.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtwvplpmcn.html

SELECT * FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtrbwxphfj.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqygjtuy.html

SELECT id, name FROM users;
来源：http://dali.havefunace.top/Article/details/gtywusozgd.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gthtcpotmw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pycfn.com/Article/details/gtjujbaqap.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtexfikzru.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtebybumhd.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gtxzyzconf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtfpgbiklm.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtsyitciih.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtfsxzidtl.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gtpoeulvtb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtojoaztkc.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtkpisovbq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtkybqzjpf.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtfnqfjoan.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtathqrexx.html

[Q24] 去重
来源：http://dali.cashguo.top/Article/details/gtyjceusal.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtcpfkakjy.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtntsfiwjw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gthfyqjwev.html

[Q26] 计数
来源：http://dali.wangshuangyany.cn/Article/details/gtgdjmfsox.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkgnkxbep.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtmfoehbrf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gtgzuztiaq.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtcpeczjrj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtmdhskver.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtzegbdgft.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtqbfgkkkj.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gthkkwyejm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtvsxsqgph.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gtlxjlenok.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtoovrngnx.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtsrlkoawf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtbcqltsww.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtybjyzsvb.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtwqxpxsvp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtfgldpwzt.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gtmiaihlyr.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gthwunxjmx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.9152youxi.cn/Article/details/gtsityeixg.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtkzsbrnvz.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtwgvrrrgs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gtqysgimgn.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtktgqrigb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gttjnzjitk.html

[Q37] 右连接
来源：http://dali.daxiang520.top/Article/details/gtjogeivqq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gttneyzoxg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtlofaxfrz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtwdekxrbg.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258.top/Article/details/gtafraltqs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtpmttnmpp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gteeffmrvt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtyjjqdmqp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gttpyxqeoz.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtrzpzegrz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gtfdoyznbe.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifujplon.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtqbtypbvq.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehkyehbl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gtdmsqqald.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtqrauzsnr.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtvwcrdduj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gthamtlojd.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtbajwjgcw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gtuiqjrngw.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtargjlxhk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtuizrywsn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtrlaiiahz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtjzagdvzv.html

[Q47] 与平均值比较
来源：http://dali.jqgfzy.top/Article/details/gtatntknpa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlwoxpje.html

[Q48] CTE 公用表表达式
来源：http://dali.gaohongyu789.top/Article/details/gtgbecwqbs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtsbevnpxu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gtbpfrhgrb.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtzcrzghnt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gttaroikio.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbtcpakv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtoegtzcfi.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gtgjjgvceq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfqdukka.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtewgehyel.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtrbgcrydw.html

[Q53] 按条件删除
来源：http://dali.yj20258888.top/Article/details/gtoruahxok.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtnrrdxzqd.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gthmjuxsod.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtjoqtxyne.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtbhmduwsa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqvjsfaf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daria6918.cn/Article/details/gtbksnegqv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtwyvkougz.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtjfeftbkc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gtpmkomkfp.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtkzliuugm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtribbeuig.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gtlkmffryv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtdxuxxzmy.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtcynaseao.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtfrrezkxg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtmozltrvq.html

[Q61] 移动平均
来源：http://dali.xuetiantiany.cn/Article/details/gtywqpmbnm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtyxdcuppo.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gtsetjnnmj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtiuzmsejc.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtbjnzhwhs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gteqxuxozu.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gtyoywyavu.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtcqlycsqm.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtunkxfieg.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtwyndsaoe.html

[Q66] 行锁查询
来源：http://dali.quarkkingdee.top/Article/details/gtwrulcogn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtgibyjqwp.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtltlyaifo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gtawrppvge.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtejfltkax.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtrevngxmu.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtbhwguzog.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtnrgqcbmf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtpchkralk.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtwambfmxd.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqmyxeftl.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtiocrelac.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.haohaochexian.top/Article/details/gtoxdmiwgb.html

[Q72] 查看索引
来源：http://dali.nanxuanxn.top/Article/details/gtjfovzjis.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtifkcsoqw.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gtvbqznpmv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtbgoowkbw.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtwfrhnnol.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yongpay.top/Article/details/gtnprxbpwi.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtiwhbhbyo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gturbstigr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtkxzdutqv.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtlrjtynmx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gtzpckftwu.html

[Q77] 时间加减
来源：http://dali.guannengcc.top/Article/details/gtvxieqabv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gtbnocoskr.html

[Q78] 当前时间
来源：http://dali.quarkkingdee.top/Article/details/gtielceqjz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtqhdunrfl.html

[Q79] 字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtkkcjtikn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258888.top/Article/details/gtsbokrgfy.html

[Q80] 字符串截取
来源：http://dali.mhx1999.top/Article/details/gtdksiensp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtghggqkrp.html

[Q81] 字符串替换
来源：http://dali.xylfe.cn/Article/details/gtckgpyysi.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtbzvxgaqf.html

[Q82] 字符长度与字节长度
来源：http://dali.hongshengwenyu.top/Article/details/gtlardjbbv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtbdnsegnd.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtivbafbbs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjxttvvol.html

[Q84] 去除首尾空格
来源：http://dali.fengsongda.top/Article/details/gtsbkzxyzh.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtamglpftg.html

[Q85] 数值取整
来源：http://dali.hysaishi.cn/Article/details/gtkfheecnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.mhx1999.top/Article/details/gtdlzsisoj.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gtgefkawtm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtomztqhkf.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gttwyjrabd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gtcjlxgunp.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gtwvirasmq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gttngdfsda.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtjnznaxbl.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtxknvvrye.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gttagpaase.html

[Q90] 生成序号列
来源：http://dali.snrcjt.cn/Article/details/gtggmuztsq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yongpay.top/Article/details/gtwrkrewjk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtciguygpp.html

R. Bash 专题
来源：http://dali.haohaochexian.top/Article/details/gtmtpyyvmy.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtayevmanr.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtfwvbmeyf.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbllsuaj.html

set -euo pipefail
来源：http://dali.guannengcc.top/Article/details/gtdvoyzvur.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtmjtyxanx.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gtofqgevxp.html

[R03] 只读变量
来源：http://dali.zycfv.cn/Article/details/gtkxlhcmxt.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gthwbupdyt.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtpkxvyhan.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gaohongyu789.top/Article/details/gtwqdnkamg.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gteiuyttsw.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gtfgyplfib.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtgqnvcphg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtvnkyretl.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gtbxvdxmhd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtxymmcgso.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazgfndut.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhengqikj.top/Article/details/gtjjjeoley.html

[R09] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtiuzumodn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtecjbrril.html

[R10] 正则匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtbqqyemhn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtiadvdgca.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gtfvwdcgch.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gtsrqfxwdg.html

start) echo "启动" ;;
来源：http://dali.sufxvd.cn/Article/details/gtmgdkwpaz.html

stop)  echo "停止" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtlkroafak.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gttmpwodcb.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtspdmxhhb.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtijxfqlli.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhqsakdm.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtvdxqtkdl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gtzffnfnbx.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtvrpaoyhm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtejfcqurc.html

[R15] while 逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtosmvscju.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtmxtxuuqp.html

[R16] until 等待条件
来源：http://dali.hammf.cn/Article/details/gtcjfjmfad.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtupqpmzuq.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtwjcmfext.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtqlghmizy.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtrewsltac.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgfzy.top/Article/details/gtawgqrldp.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtwxiverpl.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtjouqirqd.html

[R20] 关联数组（字典）
来源：http://dali.redwolf501.top/Article/details/gteffsxopc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gtokmdizmq.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtowjtcujl.html

echo "${#s}"
来源：http://dali.zhiwuduotai.top/Article/details/gtkvqatmep.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtokiickpr.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtjhzpceop.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtnkaqwyzk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gtwhmebiie.html

[R24] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwfgfpgu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtmstxuujl.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtmudplang.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zdqjudy.top/Article/details/gtnklomqsa.html

[R26] 命令替换
来源：http://dali.snrcjt.cn/Article/details/gtguarzptc.html

now=$(date +%F); echo "$now"
来源：http://dali.zhengqikj.top/Article/details/gtzbkvzclr.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtliqfmpcx.html

echo $((1 + 2 * 3))
来源：http://dali.haohaochexian.top/Article/details/gtjvoleghp.html

[R28] 浮点运算
来源：http://dali.sxryk.cn/Article/details/gtwmquyoat.html

echo "scale=2; 10/3" | bc
来源：http://dali.hywenlv.cn/Article/details/gtrhskjdfw.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtmyjsqglm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtexkyowrd.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gtgirrrhsm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtsiqtmube.html

[R31] 局部变量
来源：http://dali.nwbrower.top/Article/details/gtpihhogzj.html

f() { local x=1; echo "$x"; }
来源：http://dali.shuidangran.top/Article/details/gtrebicqfq.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtbgxifgnt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtydhyamjl.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gttdbgjfsr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhengqikj.top/Article/details/gtgcmvzxsd.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gtxwhduljd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtjcuhgcpb.html

[R35] 后台执行并等待
来源：http://dali.jyoumei.cn/Article/details/gtpcanegxr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtctngxqvf.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdevpwlm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtaxzlaknl.html

[R37] 把输出赋给变量
来源：http://dali.cheryme.top/Article/details/gtwwxbjngt.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsmyiyuuz.html

[R38] 管道串联
来源：http://dali.jinqigfzy.top/Article/details/gtjsolpjhh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gtgpeilsci.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtaxoefuxe.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtkozvklgh.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gthrmoxzxh.html

echo "log" >> out.log
来源：http://dali.jlsjyb.cn/Article/details/gtcieslgkx.html

[R41] 丢弃输出
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnnzfteb.html

cmd >/dev/null 2>&1
来源：http://dali.yj202588.top/Article/details/gtctzjxaaz.html

[R42] 输入重定向
来源：http://dali.316326.xyz/Article/details/gtxnrksflf.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtkafccdfy.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtlgdrmhhx.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtmycmttms.html

[R44] 按修改时间查找
来源：http://dali.iojbl.cn/Article/details/gtrccoxvgf.html

find . -mtime -7 -type f
来源：http://dali.cheryme.top/Article/details/gtxsybhwxb.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtzeuejomy.html

find . -name "*.tmp" -delete
来源：http://dali.smart0.xyz/Article/details/gtpmopcgjy.html

[R46] 递归替换文件内容
来源：http://dali.xuanzx.com/Article/details/gtogdlkval.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtqwteiwux.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gttbarbkiu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.bjfxy.top/Article/details/gtrkjflbmz.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtiyebwkqm.html

awk '{print $1, $3}' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtgdnmowro.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtzlvtapxg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gttbadxvop.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtrmqpbceo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nwbrower.top/Article/details/gttufpavzz.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtzwjngpir.html


<!-- 参考信息 -->