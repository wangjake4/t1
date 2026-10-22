代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gtmgwdyntb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gtutrllhih.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtikpfrxbq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtgyxlfkdb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtehmvjhqs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtrplmnxpi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtbvwkheyw.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtyuregeve.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtqlyarumv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtnegxkfdh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktvwkhyh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtisjwckyy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtrhqqvcve.html

);
来源：http://dali.jianghu66.top/Article/details/gtybvkmlqb.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtcavavast.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtuurhyley.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtwetrrjev.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtesqsopzq.html

amount DECIMAL(10, 2),
来源：http://dali.tanke756.top/Article/details/gthrgfpugi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gtzvowclrx.html

);
来源：http://dali.yuxming.cn/Article/details/gtdvcgvnba.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvlitxpt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yueranfly.top/Article/details/gtqdbbhnji.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtnfpohhls.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtrronfoph.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gttcrgsyuc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gttnxwsylx.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtcjarkkju.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtctguvbyr.html

[Q07] 删除表
来源：http://dali.aizwys.cn/Article/details/gtyqmjxwpe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gtwjhqejbt.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtbmegojlz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtfreosnxj.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtougbaoek.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtepgicqat.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gthvcgkiuy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtujklrulg.html

[Q11] 一次插入多行
来源：http://dali.hnqzz.top/Article/details/gtnymdqwwg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gtlotqqqzl.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtqzzxhgsu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtykrwhbxc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.redwolf501.top/Article/details/gtkqcypjik.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtopdhqdvn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtgwhxwhld.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyimyliot.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtessrbeje.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtqgkhixyt.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtsyesmyii.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtccursokj.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebzzestm.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtfjzeicdt.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtxocivght.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtczjdctms.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtlxvzeptr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtpayyxusa.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gtlyijjsfz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtosunkteo.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtylahjzao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtipfssiii.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtvilwnnxj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj202588.top/Article/details/gtjkrtanla.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gthjqzlvun.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtrukfspna.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gtwwqjhyfu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.quarkkingdee.top/Article/details/gtvyvzpnvj.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtsxpdvzwa.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtmhttysof.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtaqcklqce.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtphxxzflt.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gtlfydaixx.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfyttjyxo.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtijezqcpx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtouulkpiw.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gtmmnhmjzh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtjkkzofsj.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjlgotsm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtqthkowvj.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtgjwtwbuq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwwtxrcp.html

[Q31] 分组后过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnllkdpnr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtsujycpui.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtsdxmfxvg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtowcizsly.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pycfn.com/Article/details/gttvwyilru.html

[Q33] 多列分组
来源：http://dali.jiagoushi.top/Article/details/gtillheulg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtgwfwmzla.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtezytrxqx.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtcrndbail.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gtynmhexus.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtlqbewxki.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrvwrrgb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtynojdjgk.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtoisfknew.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtjgdmvlwa.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtgabnqfsa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtsvcpxmvi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gtoouqdpoo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtaexibzyd.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtwmgkaemm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtepqiyqtt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtvgiqnabm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gttnrlnben.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gttketzlzk.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gtdwmbwazk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwrtezrn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtmrurjnqb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtddzugysv.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcnkggcj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtrrgtemvv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtikcucpny.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtuietwhkg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtborjvamk.html

[Q44] IN 子查询
来源：http://dali.ppjwa.cn/Article/details/gtijypophg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtlkghpcin.html

[Q45] EXISTS 判断存在
来源：http://dali.yangfankeji.com/Article/details/gtoecbxegv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtbeszsoaw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gtuvnyiyfo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtyhrkyicu.html

[Q47] 与平均值比较
来源：http://dali.yongpay.top/Article/details/gteaakbvma.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gtucuzimcv.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtguktqtuc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtjrylmoxz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtjkndxbuw.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtkswjxfmh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtzoivzzwx.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtoqbyymzn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtdjvagroc.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtontisanw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcdpnayx.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtzlwrvekl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtwgyiscrb.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtnafyxysh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtyvjdfyul.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtcmamgtol.html

TRUNCATE TABLE logs;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpmimqcp.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gtaikzscnj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtnyyyjurw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtijxzubjj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtaeqftdhr.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtyycyoflw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauvgccqz.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtyybcjvpx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghmquyse.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtbibeetzj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtpwkvgcey.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtmnepymue.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtvrnsexfm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtwdvymdsf.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtfdgjpcmy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtlftmjnwn.html

[Q62] 分组占比
来源：http://dali.chenzaomai.com/Article/details/gtqdvrwqsk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gttmxxlfgg.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtdhllxyos.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtwjhwbesd.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtvigyqyog.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgwxlhme.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtlgzfawyb.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtkfjbohjg.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtnsganqbh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtnjyedmcf.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtostzssrf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtyjcxneik.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtieoyqbyq.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gttrqxnzmz.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtsfinxlei.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gtumevxmab.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtqgagclko.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gteagnpjkw.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtzbhibfii.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlklegvh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtcggthklq.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtnsmxhbcb.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtezglmlbc.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtluruoqid.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtngzflizb.html

[Q74] 强制使用索引
来源：http://dali.daria6918.cn/Article/details/gtqvgychsw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gtfzlldpoq.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtskifjjlu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtgtdgotnh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.birdmap.top/Article/details/gtixhgubrz.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtqeharzje.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtayucrskn.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtgmowtwtm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtsyrnmlet.html

[Q78] 当前时间
来源：http://dali.xylfe.cn/Article/details/gtmquuuxhz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtkthcuvkt.html

[Q79] 字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtkltsorhc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtamopjdos.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtcdpxidzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtcbnyijql.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtdnbnyymu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gttjjoanye.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoarkpqa.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtkpvlndyv.html

[Q83] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gttwgueguw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtcpvtuaxf.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtcohvsrfh.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtfisoyxxg.html

[Q85] 数值取整
来源：http://dali.yongpay.top/Article/details/gtkgoanozu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtuwquqrhz.html

[Q86] 读取 JSON 字段
来源：http://dali.hammf.cn/Article/details/gtmtlqvkqi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.bjfxy.top/Article/details/gtrethzywh.html

[Q87] JSON 字段做条件
来源：http://dali.kuanghao11.cn/Article/details/gtnurlpsow.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtgdvgjaxc.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtdkmkbvdg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtvkwbmzwj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttishvsfv.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtuwgojuvq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtpeiktzbq.html

[Q90] 生成序号列
来源：http://dali.jqgufenzy.top/Article/details/gtdygevxyy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfqhuitx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndlceylw.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gtiyezctil.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtotfmudpm.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gthiznywzx.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtdakzjtam.html

set -euo pipefail
来源：http://dali.cucudq.cn/Article/details/gtskjutols.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gtngumsrez.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtqhfttvrz.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpftvzloc.html

readonly PI=3.14
来源：http://dali.ppjwa.cn/Article/details/gtlaowahsj.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtlciknugh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdyrabva.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtzwzncbzu.html

name="${1:-default}"
来源：http://dali.sweek.top/Article/details/gttjfredql.html

[R06] 判断命令是否存在
来源：http://dali.sxryk.cn/Article/details/gtxjakzvgq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gtrscmweee.html

[R07] if 判断文件
来源：http://dali.yj20258888.top/Article/details/gtobteykok.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtpjkeokip.html

[R08] 数值比较
来源：http://dali.dashuyun.cn/Article/details/gtrwzcgprd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.iojbl.cn/Article/details/gtpjnyukwi.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtzitrpazy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.meibo888.top/Article/details/gtmqlboetp.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtrztdnnbc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tianlin.xyz/Article/details/gtlmabbndq.html

[R11] case 多分支
来源：http://dali.yvedp.cn/Article/details/gtexmilwdw.html

case "$1" in
来源：http://dali.ivvv.top/Article/details/gtrgsrszng.html

start) echo "启动" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtyxvcyziw.html

stop)  echo "停止" ;;
来源：http://dali.haohaochexian.top/Article/details/gttvkrtuol.html

*)     echo "未知命令" ;;
来源：http://dali.jyoumei.cn/Article/details/gtucknfott.html

esac
来源：http://dali.aizwys.cn/Article/details/gtukohhyeo.html

[R12] for 遍历文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvohmnbe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtojbfmrvo.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtxwnfilwv.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jlsjyb.cn/Article/details/gtkijrayxa.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtiznsjymc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtnbnnehzc.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtmynvyrlc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtxvsluswq.html

[R16] until 等待条件
来源：http://dali.zhengqikj.top/Article/details/gtizifmayp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtntvffcmm.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtuetwulyj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gttpwzhize.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtcjciulmf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtrijiexhi.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtwxfynlnh.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtjjldrgek.html

[R20] 关联数组（字典）
来源：http://dali.daria6918.cn/Article/details/gthdmxqvql.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtmekygrod.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtwzhbrqne.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtqouaufyc.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gttfefquxc.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtjkqnkdei.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gtnlvvsixi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.vqdsnc.cn/Article/details/gttkvqnmoy.html

[R24] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtpsyicoid.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj20258888.top/Article/details/gtvqxvhqnb.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtbcgbmtdj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gaohongyu789.top/Article/details/gtcahvuisf.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtgnkwuyki.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gthfclqfjk.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtqwhyrmez.html

echo $((1 + 2 * 3))
来源：http://dali.zhengqikj.top/Article/details/gtxavakodk.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gtwztnvsni.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gtwlacukiy.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtqoavczom.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtvvolnktl.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtpwyektvl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gttndrjijt.html

[R31] 局部变量
来源：http://dali.ivvv.top/Article/details/gtyzvdpxiu.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gtxfyxlnof.html

[R32] 参数个数校验
来源：http://dali.quarkkingdee.top/Article/details/gtckuystgk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdebpflgh.html

[R33] 捕获错误并提示行号
来源：http://dali.yangfankeji.com/Article/details/gtjvzxqivi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gtlnzxvpud.html

[R34] 退出时清理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngwdzsso.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtzmhczjps.html

[R35] 后台执行并等待
来源：http://dali.hysaishi.cn/Article/details/gtynejqayh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tianlin.xyz/Article/details/gtnsbhuqjj.html

[R36] 并发执行多个任务
来源：http://dali.hammf.cn/Article/details/gtkqascegr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gtzpnzlbah.html

[R37] 把输出赋给变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccttzbzt.html

files=$(ls -1)
来源：http://dali.fzhhl.top/Article/details/gtzlmaueee.html

[R38] 管道串联
来源：http://dali.fzhhl.top/Article/details/gtexvfdgvt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gtprjxpmle.html

[R39] 重定向标准输出与错误
来源：http://dali.yonumen.top/Article/details/gtrixubwlx.html

cmd > out.log 2>&1
来源：http://dali.hammf.cn/Article/details/gtjxazykbo.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gticnhzjha.html

echo "log" >> out.log
来源：http://dali.shangyingyoupin.top/Article/details/gtehikpnss.html

[R41] 丢弃输出
来源：http://dali.shangyingyoupin.top/Article/details/gtrwyxankm.html


<!-- 参考信息 -->