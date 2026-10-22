代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtjrwxmohe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gtjbevzxrl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtqtlxydcl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtskcmvyrs.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlgcojjdy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtftynnjgg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtefaxrsnj.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtmizygeaz.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtmbyoujrn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gterrrmfhf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtyuaoyuql.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtxqxyjpeg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gthmavraun.html

);
来源：http://dali.yongpay.top/Article/details/gtouxtrlsu.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxbjwvgq.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtnmpqverz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtavgukqjz.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gttpqgzjxo.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtuetpncaz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtebullduq.html

);
来源：http://dali.birdmap.top/Article/details/gtaywfsgqx.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtpjvulpis.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shuidangran.top/Article/details/gtqtslystu.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gthqjqmpno.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtyrzdarko.html

[Q05] 重命名列
来源：http://dali.chenlongwang.top/Article/details/gthwrbvmkz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtrpeoqsig.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtooiepgia.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrcvtcel.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtkqqfrefx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gthychlwvr.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtbouldpcf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtqtdudfbp.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtivuckszs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtfscxkbfa.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtxrypijxe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtgumxtjrx.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtyszkbxai.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtcrqwnqax.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtshbadyeb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtqysojtty.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtszldidkm.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gtliredoav.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gttbcvhkxl.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtpycmiphn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtgbtndmkx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gttuvsimbv.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtrfmjpzqq.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtjkgudxzt.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtjnenonbh.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtksyxgdnu.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtrgnalopq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftdomkvk.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtchdokvde.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtjznsmjrc.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtfcjlpxdn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsyrifzn.html

[Q20] IN 列表
来源：http://dali.zhixingplan.top/Article/details/gtyzobkixl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtcsswjqty.html

[Q21] 空值判断
来源：http://dali.daria6918.cn/Article/details/gtezjvckjw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtclfafuyf.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtsvhviiop.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gtehonoobp.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gteesbchog.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gtublmfxvi.html

[Q24] 去重
来源：http://dali.meibo888.top/Article/details/gtwbpexeqj.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfuzgoia.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtaypsatzk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtvbgypawc.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtjgwzabka.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtmolbvciz.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtghgiyzbt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtscaxdgzz.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gttthbzfir.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtquxcuusg.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtkhyomzqd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtlssqjvkc.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gtfryhekme.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtzdyvxsby.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gtukygvdzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtaaxvuyge.html

[Q32] 分组拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtcmwjmoja.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtwqmpwzeb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtoevoqbmj.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtzemlbtfh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtdfuysron.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtxlmommlb.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtrubgasmu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ehwqpu.com/Article/details/gtwdsrapsi.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtfieuubsv.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtwtukzzuq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtrklzrvlv.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtspiiztky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtjzjdtasg.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtnqrmutjv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtkhcrqnbu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gttsvluqln.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtvpfmhklu.html

[Q39] 自连接（查上下级）
来源：http://dali.0kj1m.cn/Article/details/gtgmnawgkc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtqushhitz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtoowjzllj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gtofizbrzf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtzvtgvzzg.html

[Q41] 多表连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhdcworx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtavgpdfwx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtnkwnjhsa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtpyknfaag.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtjqhduhwe.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtctwcsnkm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gtjefdmrgd.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtcnsvmwus.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hfpthk.cn/Article/details/gtofmebxjc.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtsrvxytvw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtyqasixcu.html

[Q45] EXISTS 判断存在
来源：http://dali.dashuyun.cn/Article/details/gtiozhrntp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtkaxhzynd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgkxxytx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrctwypgx.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtqcenkolz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlircorl.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gtgwqakhkn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtirmtslat.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gtgnqosyxd.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtfmoredep.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtsnxffvpy.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtxbxmztpq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gtkigzhqli.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtmiqlaxsr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtcmmhlwtp.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtdoxhtfwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtqbcyoimg.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtohwylnce.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gtgdtvyovf.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gtwxkcyhdf.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtoiiycwwb.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtozmlvfvy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gttebdgaut.html

[Q56] 密集排名（并列不占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtagfnweul.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtvrunzmde.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gtdgqglvff.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtbpelraxi.html

[Q58] 累计求和
来源：http://dali.guannengcc.top/Article/details/gtedddpbxl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtwqgrcdsm.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtwelnlgpn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtruqzkiux.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtxtwczjrb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtdqwaskkz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtcoafxani.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gttdnzvkgw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gthixabxsz.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gthmwolzzg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtatptjipr.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtdwegmywh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtizxeqkwq.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtbzhszmxj.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtvueztxvk.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtatlmxthp.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gtfmxmyovx.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gturptdvcb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtrnejuutv.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtkrcbdbha.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtvklbpmut.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtpedwmjgi.html

SAVEPOINT sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtilbjylcw.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtakrnnsky.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gthycxeluu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtfreezhod.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrwetsbt.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gtimjscbnb.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtlebczsty.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zdqjudy.top/Article/details/gtxpvccjqd.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtjicllbgy.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtexecvfjq.html

[Q73] 查看表状态
来源：http://dali.dianchejie.cn/Article/details/gtkqrekeqv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgpoerbx.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtjtjehjvp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gtbeahxini.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gtnupgoofu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtgyiqctay.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtiapohefl.html

[Q76] 按天统计
来源：http://dali.cqqwz.cn/Article/details/gtvdensalm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nwbrower.top/Article/details/gtwucxdksy.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gtwmehzyco.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtpnxiprcj.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtgakjxdjw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtqfzpzecy.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtkwmjiuur.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtujyxwfem.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtweegdaaz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqosmbcdh.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtjenfyoce.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtgorglrqq.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gtjadeqbqt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtnwjxthsl.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtjzqszybv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtbejlnuxt.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtzculzixj.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtnoymxxpt.html

[Q85] 数值取整
来源：http://dali.gaohongyu789.top/Article/details/gternltdbm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgufenzy.top/Article/details/gtuwvdanwd.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtxpozkryg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtodtkvivv.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gtqujhoacu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtbcgzzept.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnxiangtu.top/Article/details/gtbqopgbqz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtkbpmlzse.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggycrjoi.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtpageagyo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtnrhihtfy.html

[Q90] 生成序号列
来源：http://dali.ivvv.top/Article/details/gtyprdvnet.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtctokmnbl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtarnqtkib.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtstnqjkwu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtxwnkzkgk.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtqiusrunu.html

#!/usr/bin/env bash
来源：http://dali.hfpthk.cn/Article/details/gtmsotmxkg.html

set -euo pipefail
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiypfjro.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gteoqgfset.html

name="Tom"; echo "$name"
来源：http://dali.tianlin.xyz/Article/details/gttlbuwhyl.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gttlhbauhv.html

readonly PI=3.14
来源：http://dali.xuanzx.com/Article/details/gtoklrovjd.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtknvkuaoq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtwbzdxvgh.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtuaggvpgj.html

name="${1:-default}"
来源：http://dali.pycfn.com/Article/details/gtqznkooiq.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtzoeajbhl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtuptbdnpr.html

[R07] if 判断文件
来源：http://dali.hnqzz.top/Article/details/gttsndnkan.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gturhuwqrd.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtntqvlrdk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gthyyhdrua.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gtvkcnrjkz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.bjfxy.top/Article/details/gtbsthqcvl.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtaocrakcd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gotoacloud.top/Article/details/gttinzjbcq.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtrdmtfrpc.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtdsyiwxty.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gtehkxgdxg.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtuobvvzni.html

*)     echo "未知命令" ;;
来源：http://dali.cqqwz.cn/Article/details/gtyfrseefh.html

esac
来源：http://dali.zhiwuduotai.top/Article/details/gtpkywbkzb.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtxjmlrzgk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.haohaochexian.top/Article/details/gtzdoomvjv.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtjrokihhy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtnxwpshvm.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtwtblgffz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtevavgyjl.html

[R15] while 逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtqccjyahu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtbooyecxq.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtnzfakecx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtgjlwhbhh.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtumlsyiyu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtwsdcwwte.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gttutxgpkl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gtskbcinem.html

[R19] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gtunvjvxxh.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtshbouqyu.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtyxclccki.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtzigrhhco.html

[R21] 字符串长度
来源：http://dali.sxryk.cn/Article/details/gtfnncmrpz.html

echo "${#s}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqwnvoukl.html

[R22] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtpbrgmxfe.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtzkjfryjy.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtbjfwagix.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cqqwz.cn/Article/details/gtvvvwuzvg.html

[R24] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtyjtnnczy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtftxmkszo.html

[R25] 去后缀 / 去前缀
来源：http://dali.shzxlz.cn/Article/details/gtoxeetdac.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbmgwkpdy.html

[R26] 命令替换
来源：http://dali.zhongyouzk.top/Article/details/gtmcimfuyh.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtlzbkecon.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gtihjvjefn.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtlaemmhco.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtisskfoxc.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtlemujpts.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gthmkjwgfz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gtftlzkobn.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtimgmujyc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtkysnnxww.html

[R31] 局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitbjpjmv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcimenuet.html

[R32] 参数个数校验
来源：http://dali.zycfv.cn/Article/details/gtaaitmytv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtzbyypfag.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gthwukyftw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shzxlz.cn/Article/details/gtgqdautti.html

[R34] 退出时清理
来源：http://dali.ppjwa.cn/Article/details/gtclfjhmwf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gtqnmdhhuh.html

[R35] 后台执行并等待
来源：http://dali.kuanghao11.cn/Article/details/gtmktsupgp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtbocywyhk.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqijinsv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtwajpydam.html

[R37] 把输出赋给变量
来源：http://dali.xuanzx.com/Article/details/gtkbzmqrfb.html

files=$(ls -1)
来源：http://dali.sufxvd.cn/Article/details/gtitfqhxsn.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtsezrwett.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuanzhike.top/Article/details/gttbzevwez.html

[R39] 重定向标准输出与错误
来源：http://dali.ybcxt.top/Article/details/gtkoziwqvc.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtpegtghzl.html

[R40] 追加写日志
来源：http://dali.cheryme.top/Article/details/gtbofedumd.html

echo "log" >> out.log
来源：http://dali.ivvv.top/Article/details/gtiojphjtp.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstopvetn.html


<!-- 参考信息 -->