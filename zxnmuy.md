代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtekdggorq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtcmieaafj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtscmknnrq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnqzz.top/Article/details/gtfhzmlzgs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gtyjpghazf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gtjhqzyqsd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtaehwuebl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtmjobrkes.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwewqsyes.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtprbzfctv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgiyzlnqb.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtfadivkyp.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtmrsnapqk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtxlbzhkzk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtuefoexpa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gtjpqnobie.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gtkhujsstb.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtvalaqbsn.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtbiqwekmf.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtytnomepy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtotueatst.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtisoicila.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtixyzorea.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtmgcduixl.html

);
来源：http://dali.sxryk.cn/Article/details/gtmiygrvnn.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtzudjwrfg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daxiang520.top/Article/details/gtykpayhbb.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtztvihtrp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtbcmbxbki.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtfbcutpoe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtaqvotmxj.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcdajssi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtrdalthgo.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevemvtbp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtzrvcrcmm.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtpicyowzz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtuutweanx.html

[Q09] 创建唯一索引
来源：http://dali.jiagoushi.top/Article/details/gtbsjvelbw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gtvaslqxdj.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtbsuwrsmc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtijfgmhzh.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gthcfrmwmm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtbdjijniy.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gtdocuuogl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gthahlbuqe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtdjfdzvyo.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gtckhopcda.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.meibo888.top/Article/details/gtpulfettr.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gtodqnaxqo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtwkshabpm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtlmjhkeby.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gtvktylnns.html

SELECT * FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtacbamfpi.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtmpxnjspg.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtwesrnebn.html

[Q17] 条件查询
来源：http://dali.0kj1m.cn/Article/details/gtevhenprt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtgiddsmix.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtxtrrwnnu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gtqoskutky.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtketotxrk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtspcxfgbq.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtuafbfomt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtdfyfqxod.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtfnwhklhf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gtflbdyrax.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtvawufuxf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtwwfchiyt.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gtmkmlsbnq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtenjhutub.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtqtfisilx.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxehipamf.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gtmtzkciap.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtflowaoaf.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gtbuvqcwki.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtacemlydp.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gtsuewiozk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtlyjlvtwu.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxogyedy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtxzzpbmzg.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtfpmknoxq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqccyrhau.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtmtidwtba.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtpernrqjl.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtshxqllpd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtzkevfcki.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtxvtiautf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtccxlmivw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gteteeealp.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gthoftbtzb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtvivceblz.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtzrliizgt.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gtumsqjdhm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtsdtzofwj.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtzllxpblt.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gtxmsdqocp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtnzqdqilm.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtwahvnvfr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gteyejadsu.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtmnrmwqoz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtwudwospf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258888.top/Article/details/gtkfdvnscq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtibrqxuxp.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtrrdzkmpr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtzzlfkrio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gthmdhwlyr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tianlin.xyz/Article/details/gtapqibozi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jqgfzy.top/Article/details/gthdfdyspp.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtezmxkunk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gtqhwjniua.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtgmlqzfdc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxwbqnnf.html

[Q42] 连接条件附加过滤
来源：http://dali.9152youxi.cn/Article/details/gtnnttrskc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtxzwwxtdk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gtobiachru.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gttwntunwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtapearvsf.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtwhbfmfvy.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtagwpytar.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtfgvbdhwz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtxszsmgsv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gtuskdytif.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtimtbksnr.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gttcnycdki.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gtupyhnfad.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtgqrylzgh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfjkqyvw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.vqdsnc.cn/Article/details/gthgmslncq.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtzomyxjrg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtxeujsjbh.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtwwomjoeb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhtpsvqs.html

[Q51] 用子查询更新
来源：http://dali.shzxlz.cn/Article/details/gtvyvnjzli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gthkpziobt.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtjxejavum.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtxjhurtzn.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gtmumhtpxi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtfdnteidm.html

[Q54] 清空表
来源：http://dali.shzxlz.cn/Article/details/gtrvtutztk.html

TRUNCATE TABLE logs;
来源：http://dali.9152youxi.cn/Article/details/gtnwzuahaw.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtbrrybdxc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gtttgkkbte.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtdhslagtc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtvtdpgiuj.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gthdocepto.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtkebztwur.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtcqatwskh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtbrrgrgqq.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtybikrazv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtaprqptrf.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtprmayekg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtrjbkfhuc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtuwqbprso.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtqyrjyilt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbiuvthhj.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gteawhgnue.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtybcnwljp.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtmuerqjmc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtvxwrkezs.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtaenbqccl.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtlspposzv.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtknctcbla.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtpauyhpww.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtqllfoxzn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpptgratn.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gtcqumvftz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtpdveshig.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gtybmhmgoc.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtiscyoryb.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtivfymtmk.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtvzqaptgx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtipqrwubw.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gttftkofin.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtzzaytjay.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtpchlcotu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtyxzlyyxr.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtqcxeyppv.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtsbbnzedv.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gthqelqhis.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gthytlhnrl.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtnfyemdzk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtnyvtxyyb.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtkuackouw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtoaiqxojy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sxryk.cn/Article/details/gttnrkxhoh.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtyovqoenp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gtfqyxcvny.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gtiwduanvx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.nwbrower.top/Article/details/gtezetrdil.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gtkopvepfz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnqzz.top/Article/details/gtgxvmwhjw.html

[Q79] 字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtwwkntadm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtebqfwcar.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtdcxiawkw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gteldgmrus.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtffhidjou.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtqhxzwgrn.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtbkvlljxl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtmsimpddt.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtwvzinuvm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtgmhuvgen.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtitrywbdv.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtxgsdhusk.html

[Q85] 数值取整
来源：http://dali.havefunace.top/Article/details/gtegwevbph.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtwxljrzsr.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwtmbucq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nwbrower.top/Article/details/gtharvgaaj.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtqibccfsb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnqzz.top/Article/details/gtaoyiptra.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtazwtxbmv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrkthxuk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtvziemyzc.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtaqnxvjuw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvspeqeyg.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtyfjqriak.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yj20258.top/Article/details/gtyjsvdlav.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdckuybnf.html

R. Bash 专题
来源：http://dali.pengpengdd.cyou/Article/details/gtpgzkvtwv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnotuvvnt.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtgyzzjizl.html

#!/usr/bin/env bash
来源：http://dali.xziqi.cn/Article/details/gtumcbgjfo.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gtexnrdwxy.html

[R02] 变量赋值与使用
来源：http://dali.aizwys.cn/Article/details/gttgnggras.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtqsvzryzj.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyjspdnq.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtpmwzupgl.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtvfvykiyg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtsgcmnrqf.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtdenbgwjy.html

name="${1:-default}"
来源：http://dali.ydzc1.top/Article/details/gtqxcxhhjv.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gtbtifscjs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gthegieczp.html

[R07] if 判断文件
来源：http://dali.fengsongda.top/Article/details/gtdasyyuuc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cdnleiting.top/Article/details/gtqzszrvnv.html

[R08] 数值比较
来源：http://dali.yangfankeji.com/Article/details/gtqrjapmyz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtuceqztkp.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtfvdeuawb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtwepucsax.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtedwqfxoe.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtzgjzswfv.html

[R11] case 多分支
来源：http://dali.zdqjudy.top/Article/details/gtgwmbopxi.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gtjpdklqmi.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtbgceksrn.html

stop)  echo "停止" ;;
来源：http://dali.jianghu66.top/Article/details/gthkjhtqqu.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtdlhwmnoe.html

esac
来源：http://dali.gogol.net.cn/Article/details/gtzemunukw.html

[R12] for 遍历文件
来源：http://dali.sufxvd.cn/Article/details/gtzzhmxvcz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtykegvvru.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtqxhabnhg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.9152youxi.cn/Article/details/gtbubqabds.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtfqqlvybe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtunyssocd.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtczvqnpnb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yueranfly.top/Article/details/gtzjyinvrb.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gtnejmzkfy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtgrqcwqdn.html

[R17] 数组定义与取值
来源：http://dali.dianchejie.cn/Article/details/gtjszfxrcc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gtckhrtpot.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gtyvpdqmdb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtxxpnnufp.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtwdutsmzi.html

echo "${#arr[@]}"
来源：http://dali.316326.xyz/Article/details/gtvhmeocds.html

[R20] 关联数组（字典）
来源：http://dali.xinyue.icu/Article/details/gtbgsxgvhs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhengqikj.top/Article/details/gttygajhev.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtnkanmuds.html

echo "${#s}"
来源：http://dali.jqgfzy.top/Article/details/gtwlzaulcm.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtlvtslwpp.html

echo "${s:0:5}"
来源：http://dali.cheryme.top/Article/details/gtpukpobko.html

[R23] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtobagasxf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.chenlongwang.top/Article/details/gtivnsurzy.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtfzpusxzl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtakmiwsho.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtptzdcgva.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gtlgokjkqf.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtpgbykgii.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtwhigyvzk.html

[R27] 算术展开
来源：http://dali.fzhhl.top/Article/details/gtfajvnnzi.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gteeomyeuf.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtjheddhux.html

echo "scale=2; 10/3" | bc
来源：http://dali.dianchejie.cn/Article/details/gtiwtdlzhm.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtbvxwdhoj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sweek.top/Article/details/gtmreooodf.html

[R30] 函数返回状态码
来源：http://dali.tianlin.xyz/Article/details/gtbbwsgyah.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtufptqrhg.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtfoelkwvu.html

f() { local x=1; echo "$x"; }
来源：http://dali.yuanzhike.top/Article/details/gtqujqxnvm.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkqzcrsi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtsmggujpx.html

[R33] 捕获错误并提示行号
来源：http://dali.fengsongda.top/Article/details/gtyjdauyim.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.c1oappe.top/Article/details/gtzxuhopck.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtadezipro.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtikfmoigp.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtaxuyryvv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtdbzzpocs.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gtpdgdcrow.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gttifgwejj.html

[R37] 把输出赋给变量
来源：http://dali.ppjwa.cn/Article/details/gttdgfqqhf.html

files=$(ls -1)
来源：http://dali.tianlin.xyz/Article/details/gtvpssmkwa.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtppqthinh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtnmnjcdet.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtkrtsucxv.html


<!-- 参考信息 -->