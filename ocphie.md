代发 wailian999

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtgsnrmlvz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gttiyyuqba.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtzlfddrqc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtqhnuedfj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtjmxovyuk.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtibvcaibn.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtvnhvuwaj.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtdlveoajg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtjpabmvsy.html

user_id INT NOT NULL,
来源：http://dali.sysykeji.top/Article/details/gtabvewfma.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gttjkpbxzy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtqrddgjlx.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtfzbfvyfk.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtsianytvq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gttklsogac.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtmmlupgjn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuanzx.com/Article/details/gtbnxekkjh.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtxibefbnp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtamzgxyiu.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtjecycocy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtvwqbssjj.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtiuddvamc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtofupklsz.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gtxpwjrmeu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtyrafrexa.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtfguhyzcl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtkjdistnz.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvzbkaxl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtyuvmwlmv.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtxpjslnmi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtbsimuzeq.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gthauuwzoi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtsvfrmdef.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtzvuuhvel.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtdpayjkia.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gttadppmwb.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtnzohqxce.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gtxtegvpkk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gttmvgkebj.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtydykbsyj.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtkfcnstrg.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtqulmfxsh.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gteugqeoes.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gtemczdkwa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.mhx1999.top/Article/details/gtvlpwekva.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtfncoeheu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtbfsnycim.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtqjbdntfr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtnxacyulr.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gtxlgoalqx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtjvjkzbfa.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtuthshcat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtgkhdpard.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gtnbzjxlws.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtwevoolcc.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gtxkzefzpl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cheryme.top/Article/details/gtscoerldh.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtwwkwnjig.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtvsxpwslz.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtbtmmsmow.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gtlivdtuxq.html

[Q26] 计数
来源：http://dali.svipenyu.cn/Article/details/gtqimhxioe.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtjetjtjjc.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtnbuxuhez.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtvvmbtqef.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gtlxxhacwo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtszqzmegm.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtcbpjkeoq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtwjmitiej.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gteyzeekvl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtqgydhiar.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtvgbrdyok.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtroulxaap.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtnaapuceg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtghskdqvp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaewvullp.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtebdyqevv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gtmfxlrphc.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtxfoehrje.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtkwgwhchk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gtdvzagdsn.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtpliosppv.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gtrwimdvli.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gttfkzuioj.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtgtiwcvnb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtmaythgbb.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gthdlspxjb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtxuplrtmr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gthplxjbir.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtdrpshput.html

[Q39] 自连接（查上下级）
来源：http://dali.ydzc1.top/Article/details/gtsriqvykc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtqeljnvig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtwhuawbgn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtplvrlcbd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gtjullhyab.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtazdvjshl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtwvqqcrlv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtrsvekmeu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttagfkrio.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gthgvvmyop.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jlsjyb.cn/Article/details/gteuuyjktt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtfsuizzam.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtjzynloiu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtymuqjlae.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gtlshjvigk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtgoccvhsq.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtxjkobwyw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtebdesiqm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gtpyrzcbcy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtjjdfkruq.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtnnsamxdo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gtkmeojzjh.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtyyxboupa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtuqarjxlh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtethvaeai.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtjukimkbr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtwsxddjde.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtwhsucons.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtywrwesee.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gtxczsvejb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtdcfyyrva.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtykokcpnw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnqyeyco.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gteygnxbcz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtkfkxspps.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gthewbranh.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtxmncdcia.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtsregkpwb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtuuokrfbk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.svipenyu.cn/Article/details/gtjjdjsedz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtxengktiv.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtpetoxbne.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtajbpgqtv.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtbblvvugr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtojolqaud.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtuomiewxe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtselkjzrs.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrehvqvb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtuyyyorwl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtegbwjnnd.html

[Q61] 移动平均
来源：http://dali.nanxinkj.top/Article/details/gtwlklvmez.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gthzbisyzq.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtgsdhpaxv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtsxvqpags.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gttsainzez.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtozujdjyc.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtvbtdhhna.html

COMMIT;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixmnmlbu.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtclrhpdub.html

ROLLBACK;
来源：http://dali.gotoacloud.top/Article/details/gtmlvoxfhv.html

[Q66] 行锁查询
来源：http://dali.chenlongwang.top/Article/details/gtjridduon.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtlntcwtor.html

[Q67] 设置隔离级别
来源：http://dali.yuxming.cn/Article/details/gtrofuluxn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenlongwang.top/Article/details/gtqwxauxhl.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gturheljiv.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtqjjkfnnd.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtykmezlbs.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtkmjgrryo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gteiqzsiub.html

[Q70] 更新统计信息
来源：http://dali.0kj1m.cn/Article/details/gtggmtmvgw.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtehbhhxwi.html

[Q71] 查看建表语句
来源：http://dali.xinyue.icu/Article/details/gtnakklvsr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gtboqvtumr.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gtekgagjaj.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtjjsbffat.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtyvmmoyjz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.andypj.xyz/Article/details/gteqygtnak.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtmvaowrmf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtxwvesimh.html

[Q75] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtefxifwtq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtsiggjphe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtimfpvihr.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtfiwjeqln.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hongshengwenyu.top/Article/details/gtwxrnaauk.html

[Q77] 时间加减
来源：http://dali.ybcxt.top/Article/details/gtrszhhern.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gtkiztofoz.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gttnclfrkc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.smart0.xyz/Article/details/gthzyreuzp.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomrbbmdy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.feifeiyinyue.top/Article/details/gtxzahtiup.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtguzqrhdb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtruiifkbf.html

[Q81] 字符串替换
来源：http://dali.cqqwz.cn/Article/details/gtqsirawhl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ybcxt.top/Article/details/gtfotvszfj.html

[Q82] 字符长度与字节长度
来源：http://dali.jiagoushi.top/Article/details/gtqzjeuaih.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtbnelfvpm.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gtnaxeqvge.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzkwtxvq.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtchtfihba.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtveoeepgt.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtwbjtrano.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtezfbljgx.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtavetyimy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yangfankeji.com/Article/details/gtynzbwxct.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtfjqevxgo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xinyue.icu/Article/details/gtsvwqnklw.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtrtlfqgap.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gtztdlpqrd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtgodotsym.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gtxkhwfytz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdyqjwjz.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtqdmasori.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cashguo.top/Article/details/gtswvoxlhv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtfhvkmsng.html

R. Bash 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtwrsjnotr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgsyvdhiy.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtxunoltjv.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtydcmjpyj.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtjgvwqwtc.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtbomffpgg.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesdalobp.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtzvivsqta.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gttlxmfmev.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyybrnddg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.guowangkeji.top/Article/details/gtsgonlemu.html

[R05] 参数默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gthayykebo.html

name="${1:-default}"
来源：http://dali.xuetiantiany.cn/Article/details/gtsagbgygf.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gttdwgywrj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gtqjxacins.html

[R07] if 判断文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkdupmncg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ydzc1.top/Article/details/gtdrpvucip.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gtomxvxirb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtbujxqumo.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtqjpglacl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gzhubu.top/Article/details/gtlcxfdncv.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtyhzbuwmc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtjboozeve.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtyoobfmao.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtxsjcbztt.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtpkgugjor.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtcjzwonma.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gtqgtsevpd.html

esac
来源：http://dali.jqgfzy.top/Article/details/gtqdkrzojk.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtysftwbpy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtkqqwpyyf.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtpygxrhvx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gthlufraei.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gtmvzehfjz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdplsfshi.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtixozhydj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shzxlz.cn/Article/details/gtapnpqtjd.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtkepxxeab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gtlfnezylv.html

[R17] 数组定义与取值
来源：http://dali.yj20258888.top/Article/details/gtoultgrvc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtfahuthtv.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gthnifwmin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gtgkaesvkt.html

[R19] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtkpeamxeh.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtrbqkwmop.html

[R20] 关联数组（字典）
来源：http://dali.jinqigufen.top/Article/details/gtrqtmcoex.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtnyepnocw.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtcfzimhyb.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtyfurcilt.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtjxuskmnp.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtrtbvmfag.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwtxmqdu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xziqi.cn/Article/details/gtotelatwh.html

[R24] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtegfcszjk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtefsxqsym.html

[R25] 去后缀 / 去前缀
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfuzgjhv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtocovdzlr.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtcllrrppz.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtwvztzelp.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtotsdlsjy.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtdlcmijnr.html

[R28] 浮点运算
来源：http://dali.gogol.net.cn/Article/details/gtnmejnofi.html

echo "scale=2; 10/3" | bc
来源：http://dali.0kj1m.cn/Article/details/gtwegqpupq.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtpzacxlee.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhiwuduotai.top/Article/details/gttvjtkxlw.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtkxsaznqv.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xinyue.icu/Article/details/gtakcmuirc.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugsdjbuc.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtkytnddgx.html

[R32] 参数个数校验
来源：http://dali.wangshuangyany.cn/Article/details/gtitqktdsk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvsoxrftj.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtnproqtkm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtrlttcwti.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtfowprrny.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.mhx1999.top/Article/details/gtfgzajpiw.html

[R35] 后台执行并等待
来源：http://dali.yangfankeji.com/Article/details/gtnykyhclg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtfowyudrd.html

[R36] 并发执行多个任务
来源：http://dali.jyoumei.cn/Article/details/gtfzwfutrc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.daria6918.cn/Article/details/gtpitmufjm.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtqzlodpcg.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtovcswzcm.html

[R38] 管道串联
来源：http://dali.hywenlv.cn/Article/details/gtircgrfnw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtfmdgwnlo.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gttzmnktlp.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtqmcutsoc.html

[R40] 追加写日志
来源：http://dali.gaohongyu789.top/Article/details/gthtyqfnld.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtnhgoheug.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtackorzni.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtxnljwnyt.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gtpqcauwvj.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtiqemsips.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtjlnxpmbu.html

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtdsptllln.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcnzuxru.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtiqszgsxv.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtswpytlvw.html


<!-- 参考信息 -->