代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gt2nsdxyjpm.html

);
来源：http://dali.jiagoushi.top/Article/details/gt2aynxfwsa.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2iavkxmnh.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydtlxjyh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2slbnvcfu.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gt2dmvincxt.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gt2buukjunn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gt2nggzxren.html

);
来源：http://dali.gaohongyu789.top/Article/details/gt2ihenpmij.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gt2wsbfdnot.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gotoacloud.top/Article/details/gt2omlqpgxx.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2sqeuohds.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gt2pauabgmp.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gt2pzbpdjwl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gt2txqzolpl.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gt2yaptlahx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hywenlv.cn/Article/details/gt2zypppkzd.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gt2wctgnvor.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gt2plhbmpas.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gt2oarnvduy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhxadwgf.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqyaesrc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gt2fcxyxcxw.html

[Q10] 插入单行
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdvaaadk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2rnesdeyb.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gt2xumhzwnb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gt2tynbbewl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gt2fpbdeqsk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2rvsftrxh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2qndottqa.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gt2fcfvbmlq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ehwqpu.com/Article/details/gt2qzmbcroq.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gt2rwmqonlg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhixingplan.top/Article/details/gt2kuaxscnm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gt2gliizktx.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gt2porapugz.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2mxcqzcpk.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gt2ugmyrkia.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2jccwezqh.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gt2lgwrqnzg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2nmqhckev.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2oouzspgz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gt2ybamaxly.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gt2jycmcpqr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gt2zsvrcqgr.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gt2mvstylfs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gt2pnqguqgy.html

[Q21] 空值判断
来源：http://dali.ehwqpu.com/Article/details/gt2aecgvrkk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2wxbbluga.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gt2eydxlxte.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gt2fwppmeej.html

[Q23] 分页
来源：http://dali.nanxinkj.top/Article/details/gt2jziqkrbi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsghfhup.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gt2prmsqyuy.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2uspuvukc.html

[Q25] 只取前 N 条
来源：http://dali.ivvv.top/Article/details/gt2zojzayuv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gt2itindqzc.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2gqybihgu.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oznskwce.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gt2sxfljjbc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2iymclydi.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gt2eionqlez.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2cfxbdrgl.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gt2fnrwllzi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2cxapytsm.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoeuzvec.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2gjxwurkk.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2ezwpthgs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gt2djuhgisu.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ucffbijv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2veqqlijj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gt2blbugypp.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gt2wamkwmls.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2uweiuynq.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gt2sljjpefp.html

SELECT * FROM (
来源：http://dali.jinqigfzy.top/Article/details/gt2xntzomet.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gt2ontjovyn.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2piwafzxu.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gt2akqwmkvh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2laoudgac.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2czehwytu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2girvxcmf.html

[Q37] 右连接
来源：http://dali.cucudq.cn/Article/details/gt2eyseayfc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2rnuwtyfi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbppopoc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2ieuubwhi.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2soegtupy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mzjooruo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gt2vyhezrax.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gt2ayqfqmki.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xweguiem.html

[Q41] 多表连接
来源：http://dali.dianchejie.cn/Article/details/gt2oqwuceph.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxuanxn.top/Article/details/gt2swrsbqot.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hywenlv.cn/Article/details/gt2tmnpgxmg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gt2vvzucile.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2giyagpru.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gt2wytytckf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybaapqbi.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gt2dkxpfvnf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gt2kxbrlbri.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2rdkctokx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gt2nxtyfokv.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqacwfew.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2telqjrbr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdvzljnk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2cdldthbi.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gt2grhssvss.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gt2tyuksott.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gt2gluveqvw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gt2jlkdmlwd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangdashe.top/Article/details/gt2wczzdtgm.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gt2naylsnpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gt2fnhhxjox.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gt2lifwmuwh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gt2tezybmum.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gt2dwklnpuk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upgkoghi.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzlfoloa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gt2ykoowxjv.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gt2bvjceckr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2lmvjdlsx.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gt2veutfzpb.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2gqxykdpo.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gt2ubjcwraf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2ouixgsjd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tanke756.top/Article/details/gt2wdchwjek.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2aryvikat.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmmrcjxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2uofnizgu.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gt2hgaqflfb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2yoccjkqp.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2ilvmckzu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2tozioypq.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gt2tmvviwau.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gt2tehhtqrn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2aqohlemn.html

[Q61] 移动平均
来源：http://dali.xinyue.icu/Article/details/gt2ntvyjvui.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2vdcqqqxg.html

[Q62] 分组占比
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkpcrepu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2dmntxfyd.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gt2halsvcyi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gt2ighqenix.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gt2ygvwjysr.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gt2zauwdehi.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2aapemirg.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gt2qdwrjizn.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gt2dmqpcpsf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gt2pnvuhsfl.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gt2bqwlcroj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ptsmxrhv.html

[Q68] 保存点
来源：http://dali.zhoulong.xyz/Article/details/gt2mnasdkwc.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gt2vaetetdc.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gt2yhufzhil.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gt2msvrxsxx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gt2nkzlwsut.html

[Q70] 更新统计信息
来源：http://dali.chenzaomai.com/Article/details/gt2bolqxssc.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2anhmqkgx.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2mwhvasbs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gt2jiqwcujw.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gt2msuykset.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2skgpyqsv.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gt2uopckwwq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2zwjllpmr.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gt2kdopdzox.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2tbapjzze.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2iynllyiq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2ypwttfsj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gt2nqdujzma.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gt2ruuckgod.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gt2sddbwzih.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gt2gctdluaa.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzzmwxvy.html

[Q78] 当前时间
来源：http://dali.yj202588.top/Article/details/gt2yodjuyja.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2bjbsudbq.html

[Q79] 字符串拼接
来源：http://dali.yj20258.top/Article/details/gt2izpiiqyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gt2htdecxpg.html

[Q80] 字符串截取
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnvsscvg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2ymwguhwy.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ittyustg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2skornxat.html

[Q82] 字符长度与字节长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kracgyjk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2ivkenila.html

[Q83] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2gxnjrqfb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2uuhmbync.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gt2nuuwmypd.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2nmjpfyhw.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gt2rqqrfcob.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gt2ppzghsjr.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gt2tafekbfq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2oucdfhtl.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gt2ernxzsbf.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2svgrhmhv.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gt2mygvquvv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gt2vgsuosxn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ugmmkirz.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jplyabcd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ihgtadqw.html

[Q90] 生成序号列
来源：http://dali.sysykeji.top/Article/details/gt2hugxtafu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdrcmbnn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dxvbjhtv.html

R. Bash 专题
来源：http://dali.hysaishi.cn/Article/details/gt2ymcejmva.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2jacanooe.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gt2vxgocgcd.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gt2fzpgojig.html

set -euo pipefail
来源：http://dali.zdqjudy.top/Article/details/gt2lqerklaq.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gt2hheublij.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gt2wrlugvlo.html

[R03] 只读变量
来源：http://dali.dashuyun.cn/Article/details/gt2jsftffwv.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gt2cxtoiqkt.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gt2ydwdbxot.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yueranfly.top/Article/details/gt2qvmwhffa.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2ehmwndyn.html

name="${1:-default}"
来源：http://dali.wangdashe.top/Article/details/gt2curnsiev.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gt2lyuvqfck.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2intxghky.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gt2vmrutdfr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.guannengcc.top/Article/details/gt2pwaquyoo.html

[R08] 数值比较
来源：http://dali.guowangkeji.top/Article/details/gt2xcysbmnb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozsjlwgt.html

[R09] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2rfswlfhu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqsevzdn.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2xkdftreo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gt2odnjlinm.html

[R11] case 多分支
来源：http://dali.nwbrower.top/Article/details/gt2mduxcmty.html

case "$1" in
来源：http://dali.wangdashe.top/Article/details/gt2oibwepxk.html

start) echo "启动" ;;
来源：http://dali.iojbl.cn/Article/details/gt2ekcexgpb.html

stop)  echo "停止" ;;
来源：http://dali.nanxinkj.top/Article/details/gt2mnhhqsiu.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gt2bqzclmoh.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwrtzmy.html

[R12] for 遍历文件
来源：http://dali.9152youxi.cn/Article/details/gt2tkysiqyh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gt2nqowehhc.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gt2eficsfkk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gt2wztkyabk.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2nzjcecdv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2vozvuoxi.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gt2osrgtxds.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hammf.cn/Article/details/gt2uicolpyy.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gt2jnfwcild.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yllbucsz.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gt2kqgujooh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.haohaochexian.top/Article/details/gt2fnkenbdy.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhryvweq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hefnqwam.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2rcydecpc.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gt2bmosnmtx.html

[R20] 关联数组（字典）
来源：http://dali.ydzc1.top/Article/details/gt2csmlochv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sufxvd.cn/Article/details/gt2rrscagwp.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gt2iipdeknn.html

echo "${#s}"
来源：http://dali.mhx1999.top/Article/details/gt2zhzmgbuk.html

[R22] 截取子串
来源：http://dali.ehwqpu.com/Article/details/gt2xqvebptw.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gt2dpebqibj.html

[R23] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lgldphjc.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2rkcrdtbl.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2lbvwishd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gt2axfrbuvl.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdqokcuq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hwuqibdr.html

[R26] 命令替换
来源：http://dali.pycfn.com/Article/details/gt2pfqrjvku.html

now=$(date +%F); echo "$now"
来源：http://dali.yj202588.top/Article/details/gt2zghohxcr.html

[R27] 算术展开
来源：http://dali.cqqwz.cn/Article/details/gt2jbsmnpbs.html

echo $((1 + 2 * 3))
来源：http://dali.sxryk.cn/Article/details/gt2uofkocis.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gt2fintsbql.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gt2qogjrblq.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gt2qghikqcm.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gt2myuuyibq.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gt2zikjwvpd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ehwqpu.com/Article/details/gt2mwvzfonh.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2dntpcgia.html

f() { local x=1; echo "$x"; }
来源：http://dali.ybcxt.top/Article/details/gt2gctkxqjl.html

[R32] 参数个数校验
来源：http://dali.jlsjyb.cn/Article/details/gt2rgmdbdhd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2lfqzshvs.html

[R33] 捕获错误并提示行号
来源：http://dali.yvedp.cn/Article/details/gt2egaoyzvl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuxming.cn/Article/details/gt2rdytfezq.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gt2umacsqph.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2woesrvbi.html

[R35] 后台执行并等待
来源：http://dali.daria6918.cn/Article/details/gt2kvpjixvj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqmkusfb.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gt2byturnsy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2dwtbxpal.html

[R37] 把输出赋给变量
来源：http://dali.aizwys.cn/Article/details/gt2mtsbyyle.html

files=$(ls -1)
来源：http://dali.jinqigfzy.top/Article/details/gt2lodkiyqe.html

[R38] 管道串联
来源：http://dali.nwbrower.top/Article/details/gt2qqhabbpn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2inxjrrdu.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gt2fhgegtsa.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikynvkws.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gt2akaxmigc.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gt2yucinsvu.html

[R41] 丢弃输出
来源：http://dali.gaohongyu789.top/Article/details/gt2hjwpgubx.html

cmd >/dev/null 2>&1
来源：http://dali.tanke756.top/Article/details/gt2bvbsxuyw.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrwplscx.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gt2ccurwspi.html

[R43] 按名字查找文件
来源：http://dali.fzhhl.top/Article/details/gt2knweusdk.html

find . -name "*.log" -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htwkpupg.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2xlmjomxt.html

find . -mtime -7 -type f
来源：http://dali.hnqzz.top/Article/details/gt2awdpeekl.html

[R45] 批量删除
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbqmmmog.html

find . -name "*.tmp" -delete
来源：http://dali.tian-w.cn/Article/details/gt2vbvmhmgn.html

[R46] 递归替换文件内容
来源：http://dali.guannengcc.top/Article/details/gt2gixtormf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2dpsrpdvy.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gt2fjazuomh.html


<!-- 参考信息 -->