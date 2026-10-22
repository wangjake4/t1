代发 wailian999

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xlhcabdw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gt2yeuhsfsa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hjcklnjk.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2gwwhzbfl.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gt2hxlehdvl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kndkducm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gt2xhllyfhc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gt2hrpfjjlw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jiitvosm.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2mfyzgqqb.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gt2eudswtqy.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2yfrlowxe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2qdgpgbjh.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2apjweshr.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gt2ytdegrcd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gt2fjuucdaa.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2qrzrujpx.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gt2oomziowa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gt2dgfyjxsa.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gt2ponosupl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.kuanghao11.cn/Article/details/gt2kujzejrd.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2jbtofxgs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kkgynwoe.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gt2hbtezlir.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gt2satlmvcp.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gt2rlomkese.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2zussjohi.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gt2twhjpeqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2zejhqswm.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gt2pqpldwkf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2gpzlcgtu.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gt2bsakvxou.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gt2vekhueop.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gt2ckegpsnk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqpnrzof.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gt2vurtbvoy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gt2dwpyovtl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenjidiqi.icu/Article/details/gt2yupbxlfi.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gt2qvijvmkj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2qcosbrlu.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gt2apyuvjfm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gt2wgjzhvbq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gt2yzwocttj.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2awbnpqft.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2hcsojhwt.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gt2hskyjncf.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2hhanfnhy.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gt2wiynknjj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wglbcgek.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2foawdahe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gt2wzynunsv.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gt2bkfxucsf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gt2sirpscpe.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2nvscgdjz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2bpybkzps.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gt2lmkhbaot.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gt2uwfssjqi.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2rbqhfwzj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gt2aklhypik.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gt2hhafpywi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gt2vyllmvqq.html

[Q24] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2qvhauprp.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2fdgqptkx.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofcsczfq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gt2qpslklcn.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnoqikkn.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lkejdfpo.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gt2lkhoqtib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2wxavpngo.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gt2cdeeheps.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2ndwrbshf.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gt2kxmgfeoe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2wrhdlmua.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gt2wdpfccdu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2uyehdizh.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2xqlibmyg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.aizwys.cn/Article/details/gt2cpccmnwb.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gt2vgbcdxhi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2hkawiqms.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gt2vwapaivz.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gt2idllpsjd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bqftxcyh.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2pdulccgq.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aovunrbn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gt2ttmuhndy.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2bwaywxqd.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2tgdzutet.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2nlfdqgpk.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gt2smekdxqh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2eqewoefa.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbcnoean.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gt2ohxabbhr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gt2yptjqcpq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2dcoynmwo.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gt2ytxigwru.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gt2tyluyzwc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2nbxhpfvj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2ggvhdqyh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yvedp.cn/Article/details/gt2qnanjtli.html

[Q41] 多表连接
来源：http://dali.xuanzx.com/Article/details/gt2rztnmvxl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gt2fspzvmrg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gt2xkdoylho.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gt2tzymngmx.html

[Q42] 连接条件附加过滤
来源：http://dali.hywenlv.cn/Article/details/gt2yttwpphu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2iozwubii.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2oyojhhzu.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gt2pttrgkrj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gt2zeverdrv.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2tzelszik.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gt2pajvqaml.html

[Q45] EXISTS 判断存在
来源：http://dali.ivvv.top/Article/details/gt2upfbavnu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gt2oomdmtrz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gt2rhcubmiw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2oeuigtfv.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gt2uvjwsnyh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gt2tlnvbzap.html

[Q48] CTE 公用表表达式
来源：http://dali.dashuyun.cn/Article/details/gt2ozweoclb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2iytrozza.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gotoacloud.top/Article/details/gt2faahvbgr.html

[Q49] 更新单行
来源：http://dali.quarkkingdee.top/Article/details/gt2ojrnmqyq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2avfzshon.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gt2pilhglcl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gt2tpqapqzo.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gt2ntfvrmgt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrdtqufy.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpqvgzbt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2pgnqdvlh.html

[Q53] 按条件删除
来源：http://dali.yanxiufei.cn/Article/details/gt2xyfsycdp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2bglqqxnq.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2xwafrecn.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gt2rsykucvj.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gt2xrgfaqkv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2xcpdfulu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gt2kzylswjh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfshozcd.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gt2msnlfdqn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2caodcfjq.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2uaamfsli.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2ayhvyqbe.html

[Q59] 分组内累计
来源：http://dali.xinyue.icu/Article/details/gt2lhfvzhrz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fopuvsgl.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gt2hcmdsdcd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gt2kqqwsmip.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2tcfkelnm.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gt2dgarbmxw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2tzqqqizr.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gt2hjtaojbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2bqrwoujs.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gt2cyufiatz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gt2eotptcvz.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gt2rhvqbjdl.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiyiwdbo.html

[Q65] 回滚事务
来源：http://dali.bjfxy.top/Article/details/gt2oxteabfh.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gt2llubwdfd.html

[Q66] 行锁查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2lrlpxfau.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gt2ipxjfcny.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jutuoddf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gt2qagufxcj.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gt2ehgmiqdd.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gt2hqyijcet.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gt2ofhlmucm.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gt2gjvfcasd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2bsgeqbpr.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2chpndwup.html

ANALYZE TABLE users;
来源：http://dali.daria6918.cn/Article/details/gt2aqdnxhdk.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2rouflsuw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gt2xsjyinvh.html

[Q72] 查看索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ufbflrdu.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xcndvulp.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2jqxcvowk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gt2xdwqfzzm.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gt2bumthmta.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gt2tgdebgny.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gt2oksmwxoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2ozlvldfa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gt2eeptkwfk.html

[Q76] 按天统计
来源：http://dali.chenjidiqi.icu/Article/details/gt2lszjbhpj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsbxtxxw.html

[Q77] 时间加减
来源：http://dali.cheryme.top/Article/details/gt2ionuxsaz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gt2qwkiqlxz.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgcyjxch.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gt2afsbhlzw.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gt2stnsfmdt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gt2sgbnmtad.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gt2kroqhzrg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2cinpweun.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gt2aywdcunu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gt2sjtpbqaz.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gt2nqudxiol.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2eruzxpib.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2iqevumgb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tflagkkm.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gt2rxdinjot.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2ssbxcsmw.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gt2jtmtadzp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gt2rdyllien.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gt2jwowpnyj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gt2upvmoslt.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2hbkpzmln.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2gvibthlw.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gt2egsurwyp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gt2uuyzasih.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahszsyaf.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gt2csdogvpk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2pljdkqpu.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2icabzgnc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gt2shtmpcvx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2qcugymsi.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gt2qfirazwu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2beynqogc.html

[R01] shebang 与严格模式
来源：http://dali.pycfn.com/Article/details/gt2dtlcjsqg.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gt2icfoqmec.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2axystvfz.html

[R02] 变量赋值与使用
来源：http://dali.jiagoushi.top/Article/details/gt2dnapzzmk.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2htivublc.html

[R03] 只读变量
来源：http://dali.fengsongda.top/Article/details/gt2nvnwvvks.html

readonly PI=3.14
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyysskad.html

[R04] 位置参数
来源：http://dali.c1oappe.top/Article/details/gt2wqlpaebl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqajkhdw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xruqrbua.html

name="${1:-default}"
来源：http://dali.dashuyun.cn/Article/details/gt2tqwlxuvh.html

[R06] 判断命令是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgteipto.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gt2htidaakt.html

[R07] if 判断文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yybxufiv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gt2ahjdnpcz.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gt2ancatolw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2euxfhhvx.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2qcrznkjt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2fwkxandg.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2lftorhry.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uckxifyh.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2uzcrgbox.html

case "$1" in
来源：http://dali.xziqi.cn/Article/details/gt2slsqeeny.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gt2furndrsv.html

stop)  echo "停止" ;;
来源：http://dali.havefunace.top/Article/details/gt2hkyjgjjd.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqablwqq.html

esac
来源：http://dali.jiagoushi.top/Article/details/gt2fshfiqdv.html

[R12] for 遍历文件
来源：http://dali.nanxinkj.top/Article/details/gt2jtmannbz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gt2efixduyg.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gt2vmhzsumz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrkfwogj.html

[R14] C 风格 for
来源：http://dali.dashuyun.cn/Article/details/gt2hwlxflzh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmiqhwgw.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ycgdtidq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gt2wfzxlrza.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gt2dgmpflhf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gt2wyzjjxzs.html

[R17] 数组定义与取值
来源：http://dali.yuanzhike.top/Article/details/gt2eeawdavt.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gt2ushmabam.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gt2pcewljlx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2phecbnyn.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gt2lxcetait.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gt2zwlobyxd.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gt2repcaufm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gt2rkvgpqbr.html

[R21] 字符串长度
来源：http://dali.yongpay.top/Article/details/gt2phonshtm.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gt2ljubghgf.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gt2vwqdukap.html

echo "${s:0:5}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ikcjhlnk.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gt2tmkkkrxa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wzmabwwx.html

[R24] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gt2hrzfuycc.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gt2dabvsxeg.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnxiangtu.top/Article/details/gt2qnrszjti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aibaodan.cn/Article/details/gt2nfegttfh.html

[R26] 命令替换
来源：http://dali.c1oappe.top/Article/details/gt2ezofzsty.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gt2txojjxzx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2fjojlyci.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gt2iodqqtyn.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gt2ntewsfta.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2zulteorj.html

[R29] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gt2qtpqjjvg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gt2usfhbxum.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gt2mqmixvzq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuanzhike.top/Article/details/gt2qzbvqxqt.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2woixotig.html

f() { local x=1; echo "$x"; }
来源：http://dali.0kj1m.cn/Article/details/gt2joyebcjm.html

[R32] 参数个数校验
来源：http://dali.bjfxy.top/Article/details/gt2qeqxdmaw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jiagoushi.top/Article/details/gt2hzhccrci.html

[R33] 捕获错误并提示行号
来源：http://dali.cdnleiting.top/Article/details/gt2keeujnth.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2gukxhvje.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gt2mlcxerkp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gt2uxyfhnex.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gt2exvtirwm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gt2xxfefygi.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gt2xthpzhkb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gt2qrheqslu.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2tpuefafx.html

files=$(ls -1)
来源：http://dali.zycfv.cn/Article/details/gt2jajcrerg.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gt2qxqsjtvp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hysaishi.cn/Article/details/gt2xskxcphz.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2qtmdzyao.html

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gt2bnrhkpqb.html

[R40] 追加写日志
来源：http://dali.hysaishi.cn/Article/details/gt2bocgzxcz.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gt2pffkdynd.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gt2foqazzia.html

cmd >/dev/null 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2npbtixxz.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gt2rhmxlduj.html

wc -l < a.txt
来源：http://dali.yj202588.top/Article/details/gt2vzqpcsjv.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqlpmsnz.html


<!-- 参考信息 -->