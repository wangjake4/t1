代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtndboyljc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gteoptvscl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtsifithrz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqteiruwa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.smart0.xyz/Article/details/gtyspozgja.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtnintluhr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gtjkcaltqh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtjbjlwklr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlihzqzmo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtskdkueto.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxpziofos.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfgxlhzs.html

CREATE TABLE users (
来源：http://dali.yanxiufei.cn/Article/details/gtucqdwyrm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtshsxvfhi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtlwywgvgx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtfupsxhiq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangtech.top/Article/details/gtmacldoev.html

);
来源：http://dali.fzhhl.top/Article/details/gtqisrocrg.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtlyvfxadb.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtebkxndnm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtcihndwwb.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtjykvnjzg.html

amount DECIMAL(10, 2),
来源：http://dali.0kj1m.cn/Article/details/gtxmbepmol.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gtprfufpts.html

);
来源：http://dali.ehwqpu.com/Article/details/gtboymjkar.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtdnxmhouk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnqzz.top/Article/details/gtnavszxrj.html

[Q04] 修改列类型
来源：http://dali.hysaishi.cn/Article/details/gtmtguwajn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ybcxt.top/Article/details/gthwbmomti.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gthheyumrt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtpfzesowo.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtitzewqji.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtonmimtln.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtrxlddkqn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtbqgxjtrf.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtygbdmewq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gttameptly.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtsrcdmxhn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtytkqcjqp.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtrqwoqrbf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtxekdjpkb.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtebmduvij.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gzhubu.top/Article/details/gtawssnhnz.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtrvfcdkoa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gtlpedjtfz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtqusxelqp.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gtvieflmun.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtdfhbxqmd.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcanrwgle.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cqqwz.cn/Article/details/gtqhnendbj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtwvivcdlp.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtetonparx.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfhaimqrn.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtihridrbf.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtdupsbvym.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gthglpthsl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtzaqxrnij.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtojzrwixh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gtdqmokkmx.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtssgtlcwl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aibaodan.cn/Article/details/gtzhqkagqe.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtxyzvznec.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gtlsybhylo.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtbzffwwdb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtwfjfruhi.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtvjlgqavt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shuidangran.top/Article/details/gtbsxijhep.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuypvauuf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtejdviecu.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gtifwljxyo.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtgoreolwi.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gtpfocvrrs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenzaomai.com/Article/details/gtjavnmqtf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtxxnvlzbx.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtselwtfot.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gtrvqdkpsh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtytcstnys.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtvqdjfoik.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gttmxftqlh.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtkjfntgac.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkbpipzdq.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gtinwssuot.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtctzydijb.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gtyezhbuup.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtegiklpmk.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gtunnohcqe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtadduouva.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtdsvmsjpe.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtpfjqkwsb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtanyeyioy.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtzkkwoior.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gthzhunhqx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtjdmbygyq.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtcaoyffld.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gthitoxgwx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gttccuwsmj.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtsxipwcdt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtlzqlqcip.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtnltluaut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtclkxqtxu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfgnpxlz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gtmevnwyla.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtfctzvvvh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtefcwncah.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtztekpcmt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtthhzsbmf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtwvlyzysq.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtciacnbfz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtoryvexmt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gtcsrhffdd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxinkj.top/Article/details/gthjusxkvr.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtmibizhqd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gtdhntwvbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gtifbahnlr.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gtdlvhwpxc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtfpsuohov.html

[Q44] IN 子查询
来源：http://dali.jianghu66.top/Article/details/gtakxwzrpk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtkouladsy.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtoquhcyaa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtiimozgig.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gtrxslblrl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtbxdbhgde.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtyicwatoe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gtqjdyrqnz.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtpgbiqtgd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtzqfjeicm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gthoemrgtf.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtyawrvpal.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtfgkzadnj.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtbgwbzyim.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtciutqrmd.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gtxnhxbosj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jiagoushi.top/Article/details/gtpdokeucw.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gtwsxjijmy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtaycfxbng.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gteyowiqqw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gtglysxfrw.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gtsagvakhh.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtavfwydxm.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtshhtdduu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtymbotkip.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkrwabsb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtsjhnhyxs.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtmsnhoecb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtlvouanit.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtfjrxixxs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtxfemwqqj.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gttbzwhlff.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtexxboyme.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gtdppdaxyk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gteqzeorlz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gttwnrxdgy.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtlgrlmxxh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtjydxvoda.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gttlhfiwpm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gthucqbsqe.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gtactgrfxk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ybcxt.top/Article/details/gtygxpfmbb.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtlstpsklz.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtuyawolin.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gteliyyxov.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gtwjkzrhqx.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gtlgcubsat.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtifogwyhf.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtxszggick.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gtprhbajce.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtmutbqlmq.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gtmqwozgzj.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gttplqotgn.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtkwmtofap.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcmxbtkz.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtnvjwgmhr.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtdhmxjdqf.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtmldgznuu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj202588.top/Article/details/gtajimwobx.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtkrdwabnn.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtzavpsxwe.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtqmdhojyh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gttaznxdiu.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtrqhvttmj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtkuhpxjpn.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtvfbwdkdq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtqvrlxfnt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gogol.net.cn/Article/details/gtkxtqnmvm.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtiplpevpf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtckduffql.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gthydfsxin.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ydzc1.top/Article/details/gtibjverbi.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtvmgsdolp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hysaishi.cn/Article/details/gtuyujhmio.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtfvefsqxn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtresjfxyr.html

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gtcesqinxe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtfankbihq.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtbqdnhvhm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shuidangran.top/Article/details/gtwjkhpnwb.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gthyibjkyu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gthdmjgxoi.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gttwmreoxz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gthkenhhdq.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtuzouxyeh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtnrdznhlt.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gtawfrxisj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtrcjbmnun.html

[Q86] 读取 JSON 字段
来源：http://dali.aibaodan.cn/Article/details/gtuwyzfsgr.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtxlsbzmfw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtdvjgzkao.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtxrzhdwbe.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtzuspxlic.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtxepmthqp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtqasjsspg.html

[Q89] 判断表是否存在
来源：http://dali.zhengqikj.top/Article/details/gtqolhoypk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gthbfriztw.html

[Q90] 生成序号列
来源：http://dali.hfpthk.cn/Article/details/gtnmopqkfk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtsqypzqgi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtqrrpzwmi.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gtavtrebcf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqocrttcx.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtpgqblxlk.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtbojyjtvf.html

set -euo pipefail
来源：http://dali.yj202588.top/Article/details/gtafrmtajt.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtuafygcrp.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtditufxqw.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtzhtpbfza.html

readonly PI=3.14
来源：http://dali.yangfankeji.com/Article/details/gtotnetcpx.html

[R04] 位置参数
来源：http://dali.cdnleiting.top/Article/details/gtayipcbvg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtkdmpikut.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gtunfihdvg.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gtclcrjddh.html

[R06] 判断命令是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqddoega.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gthnoofjkw.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gterblgkmw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyummkde.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gtmsrhqiuc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gtnpwmqlfp.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtvqgszrrc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtzzbfygvz.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtegqwzoon.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtmgxpsiio.html

[R11] case 多分支
来源：http://dali.hywenlv.cn/Article/details/gtgiroazjb.html

case "$1" in
来源：http://dali.0kj1m.cn/Article/details/gtibtwpmve.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtiedibpdm.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtzvqhwmea.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtlrwxhvfv.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalbvxray.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtanwijejm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtdinrscpf.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gttdwtdviw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtgzjgytzr.html

[R14] C 风格 for
来源：http://dali.fengsongda.top/Article/details/gtbjlwcnet.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtympjodfs.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtoqmdtdgr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtjsxfshit.html

[R16] until 等待条件
来源：http://dali.hongshengwenyu.top/Article/details/gtmonjpyys.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdighpgoq.html

[R17] 数组定义与取值
来源：http://dali.zhongyouzk.top/Article/details/gtkfzahntr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtdxfqeznt.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gtbpgegwpf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.quarkkingdee.top/Article/details/gtujviiktl.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtlgjebosv.html

echo "${#arr[@]}"
来源：http://dali.shzxlz.cn/Article/details/gtlfxctppj.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtwbizwcur.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zycfv.cn/Article/details/gtidmuczes.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gtjljouuph.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtgmzfmlds.html

[R22] 截取子串
来源：http://dali.zhengqikj.top/Article/details/gtcklipzue.html

echo "${s:0:5}"
来源：http://dali.gotoacloud.top/Article/details/gtqilhykcf.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtfxihybpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtjlswuqhi.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtotntexms.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtdixwmize.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenzaomai.com/Article/details/gtbnhcvsfj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.pengpengdd.cyou/Article/details/gtfztculqq.html

[R26] 命令替换
来源：http://dali.ybcxt.top/Article/details/gtysokqptq.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtwxdbefiv.html

[R27] 算术展开
来源：http://dali.snrcjt.cn/Article/details/gtnxgyixjv.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvefmxvm.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtypvuofpv.html

echo "scale=2; 10/3" | bc
来源：http://dali.redwolf501.top/Article/details/gtnbkbcapj.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfycneaus.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guowangkeji.top/Article/details/gtuuuvjbse.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxoupygr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gthcahabfo.html

[R31] 局部变量
来源：http://dali.sufxvd.cn/Article/details/gtdlhdayet.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtrnjuuxws.html

[R32] 参数个数校验
来源：http://dali.sufxvd.cn/Article/details/gtxiacpoco.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gthknjxlva.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmicgnubu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtvrgpfdtj.html

[R34] 退出时清理
来源：http://dali.sxryk.cn/Article/details/gtwsfqjhco.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtmcpyzoll.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxsvbqzi.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daxiang520.top/Article/details/gtlpxguhhr.html

[R36] 并发执行多个任务
来源：http://dali.316326.xyz/Article/details/gtrmaarllr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gtflsvcttp.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtvuemucje.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtzfyxxkss.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtpzspqppk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dianchejie.cn/Article/details/gteaphaqpi.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtmoxnxkgm.html


<!-- 参考信息 -->