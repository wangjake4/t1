代发 wailian999

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnquwmzml.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtxlfezfcl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkxzxcfdq.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtwatcxpwl.html

CREATE TABLE users (
来源：http://dali.ehwqpu.com/Article/details/gtncwwdqsv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtddegyjgi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtbbupcuxn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtcxglhmjp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtlafizoki.html

);
来源：http://dali.zdqjudy.top/Article/details/gtopqolwqo.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtlsekcsmz.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtgkwwifeb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtjqfvsqra.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtfsxozypf.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gtqpeltiut.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gtwguqtiji.html

);
来源：http://dali.c1oappe.top/Article/details/gtcvughfgr.html

[Q03] 增加列
来源：http://dali.daria6918.cn/Article/details/gtcksaoqxs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtycatqkco.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtlsiesyey.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtrdihompe.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtgqrzenmg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtxzpfnmaf.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtmiqbhyaf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtkupzrdnu.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtyynaenxv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gtgmqsgkix.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gtqhqsbcni.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gteiwcykfk.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gtdtuueese.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtprywkged.html

[Q10] 插入单行
来源：http://dali.9152youxi.cn/Article/details/gtnduvvsnn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtszpcvszc.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtibsvngtd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtyzhlnqae.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtutxrelnr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtqjoygqdg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtsncltwde.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtqqzjezyk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gthzuyhjhw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwspjilvr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtzpndxkty.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gtwsobeshm.html

[Q15] 查询全部
来源：http://dali.cheryme.top/Article/details/gtrongtsxd.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtwomvcoie.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtswnwlhhi.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtlbbehtxz.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtkuvuzscl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtifxzzzut.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtwotkijdu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobnfrlok.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gtyjhpnvse.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gtrrkynvxd.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtfsqnsqek.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtpytrsgam.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtkqheqkyl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtsdbdxffi.html

[Q22] 排序
来源：http://dali.hywenlv.cn/Article/details/gtizabjcss.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aibaodan.cn/Article/details/gtsafxgszp.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchvnluvp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtsrhkdyhc.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtuhjaptvw.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtgpdmoaes.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gtxixuuzir.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gttxnotcgq.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtiifshdwh.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtovepaafv.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozekpyhc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzukserif.html

[Q28] 求和与平均
来源：http://dali.cheryme.top/Article/details/gtlrdmfnxx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gthvyfgczs.html

[Q29] 最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtvrwjyaca.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtbejiimqm.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtzdrvtsfs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtiglzhenf.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtbhkxsevd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yangfankeji.com/Article/details/gtpmqhlrmm.html

[Q32] 分组拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gtalnrxdnk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gttmzsnayo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtjscblque.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtxflapaqt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtkrhkxtdy.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtcikavhau.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtwdodeifk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gthhzireov.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gtfmruyljn.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtfvuiplve.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtnqaxtqsz.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtndhndexj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gttebkxmxh.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtpevgoepa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtdtatiphe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtciwmildu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtcpazxvbo.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gtdrjqvfqk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gtwnrfcizk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtovuqibmt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtbdeacrqp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtfdfajxtf.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtehxajwip.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtnnfindgc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtqnatptzp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtcqfbdahg.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gttpfwoqnw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtzwjxniwb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtvlftcoos.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtvsdhgbcm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtpecxmfdp.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtaheygreo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtkggckhdv.html

[Q45] EXISTS 判断存在
来源：http://dali.cqqwz.cn/Article/details/gtxmsgfsjh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtiyyiflbe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtokgopfyu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtmpzimxgg.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtibblclbb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jyoumei.cn/Article/details/gtkvigdgkb.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtkmttpwuo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtifxhmdyp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtcyyldghp.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtgcamruvi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtgvcegpzt.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiytgials.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtwgixarbn.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtgbbrreut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtjloonzsr.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtwwjmbqtv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gthzemfffs.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtfxgspafo.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtwaknykjz.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtywojybah.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtkgpurbjh.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtzcxgqkzk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtysptjnpr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtwtdgfrru.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtkimrghjn.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtvddybaby.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtnxpoiduy.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtanutrgkr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtbxsgjfaf.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gtxrxwqlsw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtbpaorwbv.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtbcgxtnvg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtryaosdrl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytdyesnb.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtcavhjjhi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtuescsnzn.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gtiwmhrdjg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtkdgbrsce.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtazpmvqkh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtbzckmmqk.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtyqixrkrk.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtkcyrxlzz.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtoddirkmo.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnufucec.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gteahoawex.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtoynahyvd.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtnwpclbhy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtmmetksgu.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtbgsnfujt.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtmxblzabu.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtueleemwc.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gtoclvjeef.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtugtvguoi.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gtqjuyrubk.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtgtwwvokg.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtuigwwlgu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtinbnmdia.html

[Q72] 查看索引
来源：http://dali.guannengcc.top/Article/details/gtdnbnxxxx.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gttgcstiur.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtoohskqgl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtoxaccfhj.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtdvbfnwhc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmednerq.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtxecodszv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtaxjuzdvz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gtinydtdrk.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtvsfebqed.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhixingplan.top/Article/details/gtpvqtmpqz.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtuewcdoba.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.haohaochexian.top/Article/details/gttqiqqwkv.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiffnmpuo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtuyxjuqrp.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtymqrfjyn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tanke756.top/Article/details/gtaibkjifw.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtisarvhtx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtktfcrklq.html

[Q81] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxautmvu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgpwybmie.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gtzrjclwzv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtmxwqvrar.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gtdqmkextm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gttpqplayq.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gtgiotsznq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtvvblqert.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtsepiaxyt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.fengsongda.top/Article/details/gtyiweejai.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258.top/Article/details/gtorubrwwv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtcgtbzkyp.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtvhmyqfme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtfowfbtlo.html

[Q88] 行转列（条件聚合）
来源：http://dali.vqdsnc.cn/Article/details/gtrpeugoyi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtedmnnimx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtjfgrgfnn.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtptmhfhrl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gtukpohxzv.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtzffagiie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtnuxwvjyj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttebgvues.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtybhhenfm.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayparfgk.html

[R01] shebang 与严格模式
来源：http://dali.feifeiyinyue.top/Article/details/gtogbonwrj.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtkqhrfbnb.html

set -euo pipefail
来源：http://dali.yueranfly.top/Article/details/gtnapltsxd.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtppkukukx.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gtwcmujydd.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtmzegwdfc.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtefcsncuk.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gteklbmptn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtvwkeeezv.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtmkshbggm.html

name="${1:-default}"
来源：http://dali.nanxuanxn.top/Article/details/gtmzeaqhtm.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gtxcxzvxxy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtjglkbqfu.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtsyqwqagy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtjpieojhe.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtfbdwbuoj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gtjysfavjz.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtjkwakyyb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtephvhodv.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gtaakkasgq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yangfankeji.com/Article/details/gtpmxwsdhs.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtrfibxazw.html

case "$1" in
来源：http://dali.sufxvd.cn/Article/details/gtlkbykzeo.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtmcmyipyy.html

stop)  echo "停止" ;;
来源：http://dali.jyoumei.cn/Article/details/gtyobpglfi.html

*)     echo "未知命令" ;;
来源：http://dali.xziqi.cn/Article/details/gtcejldiit.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gtnrbwztnx.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gtuicheato.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtotjqlfpw.html

[R13] for 计数循环
来源：http://dali.tian-w.cn/Article/details/gtatinwhov.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtwdqemifx.html

[R14] C 风格 for
来源：http://dali.c1oappe.top/Article/details/gtnkdspekf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtxwzkdwad.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtbqfigisk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtemkldqhr.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfhhueqv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtqugsechi.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtnncbuxsk.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtbkvtgxmm.html

[R18] 遍历数组
来源：http://dali.bjfxy.top/Article/details/gtnxixcfys.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gtyysdyhgw.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadyshkbk.html

echo "${#arr[@]}"
来源：http://dali.sweek.top/Article/details/gtekelfqvx.html

[R20] 关联数组（字典）
来源：http://dali.feifeiyinyue.top/Article/details/gtdaadvuub.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yongpay.top/Article/details/gtppqikvrc.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtvghfgzqv.html

echo "${#s}"
来源：http://dali.nanxuanxn.top/Article/details/gtuvthalgi.html

[R22] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtmhizwzqe.html

echo "${s:0:5}"
来源：http://dali.ppjwa.cn/Article/details/gtvlpamfvk.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlfrocwb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zdqjudy.top/Article/details/gtntdeaypg.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtebemqayw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtygmuwqtq.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gttdelklwr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj202588.top/Article/details/gtbrcjrpvi.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtdtuvxeaw.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtgmuepczd.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtavurmlxm.html

echo $((1 + 2 * 3))
来源：http://dali.hywenlv.cn/Article/details/gtzaghplyf.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gtwkyvhleb.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gteveiqnls.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtwdnenkar.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.snrcjt.cn/Article/details/gtbxbobyya.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gtclafdqrl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gtoaamruzm.html

[R31] 局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtggcgnjzr.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigufen.top/Article/details/gtsdhzjjko.html

[R32] 参数个数校验
来源：http://dali.ivvv.top/Article/details/gtkkgermve.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtlirelnda.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtcmeyavol.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gthtqamuyl.html

[R34] 退出时清理
来源：http://dali.yangfankeji.com/Article/details/gtmuaccned.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtdqswafga.html

[R35] 后台执行并等待
来源：http://dali.zhoulong.xyz/Article/details/gthzmbepum.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gttcqinsqc.html

[R36] 并发执行多个任务
来源：http://dali.shuidangran.top/Article/details/gticiojrom.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtiiduhsne.html

[R37] 把输出赋给变量
来源：http://dali.jianghu66.top/Article/details/gtuvwxptdc.html

files=$(ls -1)
来源：http://dali.andypj.xyz/Article/details/gtjtgtytuz.html

[R38] 管道串联
来源：http://dali.tian-w.cn/Article/details/gtlkfgppeq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtwjegkjvq.html

[R39] 重定向标准输出与错误
来源：http://dali.pengpengdd.cyou/Article/details/gtitqbpbtb.html

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtrzqmqdno.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gtcxkfuoak.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtrfxqpxba.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrrraqpc.html

cmd >/dev/null 2>&1
来源：http://dali.fzhhl.top/Article/details/gtttvmilpl.html

[R42] 输入重定向
来源：http://dali.haohaochexian.top/Article/details/gtbsllytgj.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtuyepdzwg.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtrgyajzev.html


<!-- 参考信息 -->