代发 wailian999

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfinezvh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gt2tvspbgmu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2dwisobbw.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gt2nkjqcqyw.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2mdrmkfof.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gt2emwcnobs.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtyppkpc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gt2ejfbnqcl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2fdojoaqm.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2bxpygxme.html

[Q02] 创建带外键的表
来源：http://dali.hywenlv.cn/Article/details/gt2oitfpjgb.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gt2khghalnb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztrwkkic.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2pwceaqwz.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gt2aolkvhtf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2jgdfjody.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2wbsessbj.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gt2rdjqpgiu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uamakovz.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gt2asnelyhb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gt2tsktjnlf.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gt2jdpyuptf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gt2aamtmwkj.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2vtlzofzp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gt2riptkgsv.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gt2pdzmoozh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gt2wrsmdweb.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gt2mnhzkcls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gt2kyemwxjc.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gt2mvcyvfij.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gt2sllyhlce.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gt2rcfmtavw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2ouxjjodn.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gt2vbtfanwi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2eqpxduus.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gt2uhvishnm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gt2wytjqfxa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gt2wtqlckrp.html

[Q13] 忽略重复插入
来源：http://dali.wangdashe.top/Article/details/gt2rgtgdiuf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gt2pllszzlh.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2xiqgixwj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2ozcxnamk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gt2lgkmcrzq.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gt2sobkmzuy.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2ttwcoqlo.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gt2kyhsqkoi.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2djzbucvl.html

[Q17] 条件查询
来源：http://dali.zhengqikj.top/Article/details/gt2kpwmddfz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2tvlvykrp.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2nsnfcqui.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gt2lmgewmex.html

[Q19] 范围查询
来源：http://dali.cqqwz.cn/Article/details/gt2gkyvamgd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hiiyqdwe.html

[Q20] IN 列表
来源：http://dali.ybcxt.top/Article/details/gt2pqljvpvc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vtgzqnpa.html

[Q21] 空值判断
来源：http://dali.wangdashe.top/Article/details/gt2jxveujeq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2roesgnbj.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gt2yvpedczw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hfpthk.cn/Article/details/gt2uhziwdzh.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gt2sjxjidns.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdxdgibe.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2baeqrhqx.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2ejphimcp.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gt2necazhmc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gt2roostwvt.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2ugigmzdu.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2woaqoaea.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gt2yqzqqcwy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2sqljvuzp.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gt2pryftfph.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2ozihvuun.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2yabnwjih.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2amlegbjt.html

[Q30] 分组统计
来源：http://dali.zhixingplan.top/Article/details/gt2uzjmegpq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2jlbjobbd.html

[Q31] 分组后过滤
来源：http://dali.andypj.xyz/Article/details/gt2dxwcbcfq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2zfrihzji.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ouzxzyas.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2fpfgcqkt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gzhubu.top/Article/details/gt2zwyiohby.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2sinjbqfr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkvilche.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gt2ozqiookw.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gt2kdbontza.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gt2pfvierkm.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2gomcwoii.html

[Q35] 内连接
来源：http://dali.zycfv.cn/Article/details/gt2avuqcrar.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gt2hjhfpqui.html

[Q36] 左连接
来源：http://dali.jinqigfzy.top/Article/details/gt2svacdukv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zksauuws.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gt2ufvyscox.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djpbduwm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hxzwrfod.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gt2ofklelqj.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gt2brscmthg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gt2wbxyvzwh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gt2thqmoykk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gt2bsxbqibi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gt2uncxpptr.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gt2rdebzjpw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gt2gxupkrgb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gt2prbcfbvm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gt2uvqutnzx.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gt2rengmxje.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gt2bcruspbz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gt2cjeiffcb.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gt2ocqopxrn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2owispghu.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmuvipwp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gt2rhlbelkb.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gt2jihgtacc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2cdidcngg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2qbvtdhpe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gt2yhgbxjxg.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gt2wfgdhhcf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezptplvm.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gt2mvaijwfw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gt2smvgdfpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2etuzgxxr.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gt2ubpfqjva.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2slegraqa.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gt2sgfjvdsa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gt2mrnliztl.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2ndgrqlla.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gt2xlrbdzdt.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gt2jlgncagq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2vtcokqtx.html

[Q53] 按条件删除
来源：http://dali.ivvv.top/Article/details/gt2lpqtsngj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2hckiulli.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2suvuoprq.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tvmzzgpz.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2jsrtblxh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2zgiyrtmu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gt2pjpvcymp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2wrdtlcse.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2jyfhdajn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xgbmdqua.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2smefaxjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2erdxpqsr.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gt2ysjzvqcp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2waebvpez.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gt2bhdeogdt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kegcdaaq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2eqwogxkf.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gt2gwsijaii.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2rqglyahp.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gt2ncthjzup.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gt2rogkspfv.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gt2slamrual.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gt2vkvospiu.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gt2ejdmppkq.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gt2saoilgrd.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gt2ewoflrdd.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gt2rfviyyei.html

[Q66] 行锁查询
来源：http://dali.xziqi.cn/Article/details/gt2dcjzbgwi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2fqwhejjj.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2vnndwzxd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2velfnzjl.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2fvnczjfd.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gt2hjxeqoqw.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gt2jwwzeonr.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gt2ipmymytw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gt2peruvdop.html

[Q70] 更新统计信息
来源：http://dali.aibaodan.cn/Article/details/gt2mrjwjtjm.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2pctktltg.html

[Q71] 查看建表语句
来源：http://dali.chenzaomai.com/Article/details/gt2udqnzejt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2ocmgetul.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gt2rsyczczq.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2suygtndf.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gt2joyeqxlk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gt2eqqqzyhf.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gt2ejyiirxt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cashguo.top/Article/details/gt2ppquodvo.html

[Q75] 日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2eevtqjvd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gt2sbvkkrkv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jiagoushi.top/Article/details/gt2wwimzczq.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gt2qetubnjp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oimdismy.html

[Q77] 时间加减
来源：http://dali.zhengqikj.top/Article/details/gt2aytownal.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangshuangyany.cn/Article/details/gt2shguksth.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebeizfdk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gt2zxhhayni.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gt2ktjnmkfe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2nmrrtixy.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gt2ihyyqjkr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2sxeleeyd.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gt2smabgfqq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2fdhlmwng.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gt2rdfdzmzs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2bfijkdza.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gt2cglswwuq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2ahruovjh.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gt2raqbarkl.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gbhtoodn.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbfdyemv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.meibo888.top/Article/details/gt2qvbxouxp.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gt2zivkmehl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gt2psownbqt.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwijdtph.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yueranfly.top/Article/details/gt2ltsqbqeu.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxxfyblz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gt2wjwcjkib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2bfnztwnc.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2nddgabtx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gt2jkrhoyyd.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gt2kuyhbrow.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqmuzzqj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ahitfwia.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gt2npbvnimz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2xypvffqc.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gt2wvldkrus.html

#!/usr/bin/env bash
来源：http://dali.havefunace.top/Article/details/gt2tynxysun.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gt2oxqdheqi.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gt2lwjijbzr.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gt2vdcasvix.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gt2ztmuhtpj.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gt2brgcaiuc.html

[R04] 位置参数
来源：http://dali.dashuyun.cn/Article/details/gt2ygmzujcr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gt2enhkzkts.html

[R05] 参数默认值
来源：http://dali.0kj1m.cn/Article/details/gt2vmrpnrye.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gt2okzrzkes.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2jronuric.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2cjvetfvk.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2emipjkuv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2meymvsei.html

[R08] 数值比较
来源：http://dali.jyoumei.cn/Article/details/gt2ikqdjxdo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gt2nexgoqey.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2tsyvbzvi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqchvwlt.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gt2himaskon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gzhubu.top/Article/details/gt2ozkaxghx.html

[R11] case 多分支
来源：http://dali.xziqi.cn/Article/details/gt2ajxasdkh.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gt2pgrgwmuj.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nitrlkri.html

stop)  echo "停止" ;;
来源：http://dali.guannengcc.top/Article/details/gt2qrgmclpr.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2bgtumfwd.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqnjpjhg.html

[R12] for 遍历文件
来源：http://dali.cashguo.top/Article/details/gt2srymtwqv.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gt2xadrhzxw.html

[R13] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gt2dntkenuf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gt2eawottik.html

[R14] C 风格 for
来源：http://dali.jinqigufen.top/Article/details/gt2dnfzutyv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2gjhtxlnq.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2fksaimho.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhengqikj.top/Article/details/gt2dfjfbzkc.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gt2qbaqgvls.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gt2niozzztf.html

[R17] 数组定义与取值
来源：http://dali.svipenyu.cn/Article/details/gt2rjcftnsp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gt2qkdbpyfg.html

[R18] 遍历数组
来源：http://dali.xziqi.cn/Article/details/gt2jbgqnkrl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aibaodan.cn/Article/details/gt2ihqohabz.html

[R19] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2uqdokxdh.html

echo "${#arr[@]}"
来源：http://dali.sxryk.cn/Article/details/gt2qnorswyd.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gt2gmisormm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2floufygz.html

[R21] 字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqfqauno.html

echo "${#s}"
来源：http://dali.guowangkeji.top/Article/details/gt2dcpyyxxk.html

[R22] 截取子串
来源：http://dali.vqdsnc.cn/Article/details/gt2mmrkzgqc.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2lfgawvdp.html

[R23] 字符串替换
来源：http://dali.sysykeji.top/Article/details/gt2jklgkqax.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fzhhl.top/Article/details/gt2hhgshasy.html

[R24] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gt2yyakqzkn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gt2kqjiwxsh.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2pptyeali.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.dashuyun.cn/Article/details/gt2sckcfank.html

[R26] 命令替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqqnbrxm.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gt2gahkbfqx.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gt2yxtunxju.html

echo $((1 + 2 * 3))
来源：http://dali.xinyue.icu/Article/details/gt2virvgaaj.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gt2ylnvvjjb.html

echo "scale=2; 10/3" | bc
来源：http://dali.yueranfly.top/Article/details/gt2trdkjhhv.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gt2hfmqswvy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gt2tnbnuipd.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gt2nupmdgfg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258.top/Article/details/gt2mfsaelqw.html

[R31] 局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2uazpwffs.html

f() { local x=1; echo "$x"; }
来源：http://dali.zycfv.cn/Article/details/gt2ttmqczox.html

[R32] 参数个数校验
来源：http://dali.cqqwz.cn/Article/details/gt2jzqdhimp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cashguo.top/Article/details/gt2hhlgsyyi.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2padepirk.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gt2aybpubqg.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gt2wvklmcig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2xtkevjlq.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gt2zhbecarp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gt2yuncfgkh.html

[R36] 并发执行多个任务
来源：http://dali.vqdsnc.cn/Article/details/gt2vmhoyjon.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenlongwang.top/Article/details/gt2inoxglay.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gt2ndljbnbf.html

files=$(ls -1)
来源：http://dali.birdmap.top/Article/details/gt2oxmetjog.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gt2rrvrvwao.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gt2fdgbxtly.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gt2bkedtibr.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gt2zjidvuwt.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gt2puvssbzl.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gt2arxcgmzu.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gt2oyrldoae.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upxvnazm.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gt2ftwyhdmr.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gt2xmzqlbda.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gt2bsfobahs.html


<!-- 参考信息 -->