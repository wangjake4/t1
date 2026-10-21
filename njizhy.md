代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gtvsniuefk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gtntouqkcr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtjgumnjih.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtqakpgmxc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtgagikxxy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtfzxodzaz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gtqzvgzydn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtgapbsljg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtecyngtqr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtwtggwwwb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtcynfwncq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtgeukbmuq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbyieusql.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangshuangyany.cn/Article/details/gtwmwrwwnv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtevhuhblr.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtxsrnbshf.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtrwgawcti.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtzzdssmkd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtzbsallaf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtdosxahqi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtuaiogunb.html

);
来源：http://dali.ehwqpu.com/Article/details/gtpnuogngh.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtuqewwzkn.html

CREATE TABLE orders (
来源：http://dali.smart0.xyz/Article/details/gtywfinsyg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtkrvwzmdv.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtcxpnvnlh.html

amount DECIMAL(10, 2),
来源：http://dali.ivvv.top/Article/details/gtgvcybbjm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtjfduczvj.html

);
来源：http://dali.bjfxy.top/Article/details/gtczoozsbo.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtjdlgmdmu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtaoynuydy.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtmcthzkqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtqrbsnbya.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtcmaymeqh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtemobhsrp.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gthljevmsg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gttmnwxbew.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtpwmudkvi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtszsaeqgn.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtumyyuzvy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtkunjqnlz.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtppmspyyo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtdbhwzexi.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gthyvhtkut.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtuizkkegi.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gtwhhjgvcj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gttsqehttt.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gtvbrcyrqm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtiawwepiy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gtekfdrdcn.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtkgbnrtpj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtlzjnuerw.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenlongwang.top/Article/details/gtjfzqyohx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtjocazguq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtdwcfuuzh.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtpsjddkef.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwrgjshix.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtqoptilmj.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtpospfxkk.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gthixqvlmh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gthzcslpwt.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtsuaznyhj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtzgptphab.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gtfdyfcyig.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtztizibfx.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtnecgocff.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtfyahujcc.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtjblprgwq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gtjdthdaot.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtchazgavu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtoifjwpsm.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtubcpkpew.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtmioqetmj.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtayoygrma.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtzmgidihu.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtbuoiaizy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtvehwvuoi.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtnupffdli.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtynpbacsk.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtjhmghtck.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtncrunzwz.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gtzalqpgvd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtkjdxrzmo.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdrxumkf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtnlepokwq.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtisavfkag.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtxjfycxnt.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gtmezfurrq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtdbvtvnhn.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcigybldd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtflhuxorq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtgdyxvkil.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gtzkzrgarj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtnmdblexn.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtdohsmcyx.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtsemgvhoa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtfriidrkz.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtwckdmgad.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtdiddlhlb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtvbapefuf.html

[Q36] 左连接
来源：http://dali.shzxlz.cn/Article/details/gturninich.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtojcghjyu.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtoiuonxij.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gtvrovwpfy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtnkazkrlg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtuaigkupd.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtrdcolnwv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqndhpfja.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtigvoxqda.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtpvsflizo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtpiyhgoug.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtxbimmcbv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtudmrdwah.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dianchejie.cn/Article/details/gtyaxqzpam.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmapzmgyt.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtnxyqeicc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gttubhnjop.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gtupbqqldi.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gtiiwhvkvk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ehwqpu.com/Article/details/gtetgjdcux.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gtxidlzbgn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtgwhymlhi.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtbiwdwbva.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtocvjdpdr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hfpthk.cn/Article/details/gtmpzsdlyw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtphhkjjrl.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtuzpmfpzp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gthswvbwnd.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtiiofxkgs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtqbmdhiwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gthxrpvzmy.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gtqvzvrvwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtcyevjpeb.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtdswzhbqn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtccvnvgzq.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gthlomskya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtlhbkiuer.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtbizarixa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtqquaanuv.html

[Q53] 按条件删除
来源：http://dali.sysykeji.top/Article/details/gtxlovjzjy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtxcgtxsfw.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtmckxlqzv.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtfjumtrtx.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtulwjmnfc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtyyqpbxhs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtjbdisyrf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cashguo.top/Article/details/gtqsyyezpo.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtwyynhsup.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtkvozegyx.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gturbsjqhx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gthcgfpxnp.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gthvhihobu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtxfvkgflm.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtdzxfqtrx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwblrpwnx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtaftpjpaj.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtusliqbjw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtblzciimj.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtfzjbgqas.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtcuzgktjr.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtzousosbr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gzhubu.top/Article/details/gtbnrytumv.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtyamhptiy.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gteuxfqomz.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtacpiqjme.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtygkimctj.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gttugcjkcm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtotwsscqw.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtxcqshqgi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuanzhike.top/Article/details/gtqheegqbu.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtknkevyyo.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gtvnddvlrf.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gtyhschzoy.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrakimjbl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.havefunace.top/Article/details/gtoxyyjpgh.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gttolupzuc.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtqyzltajb.html

[Q71] 查看建表语句
来源：http://dali.jyoumei.cn/Article/details/gtidrzjgub.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtjwdkwlen.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gthjiyauyn.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteecdyitp.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtzcjqmhxa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtozjtnghd.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gtkaxyvefw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrmgbzpj.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtdbgmakvj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtnylrajez.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxhlbwga.html

[Q76] 按天统计
来源：http://dali.dianchejie.cn/Article/details/gttxjvxonr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtotvyhnxh.html

[Q77] 时间加减
来源：http://dali.snrcjt.cn/Article/details/gttjelxgey.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gotoacloud.top/Article/details/gtuiqbmhlt.html

[Q78] 当前时间
来源：http://dali.havefunace.top/Article/details/gtnoxjzftr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxuanxn.top/Article/details/gtkpmsmkeg.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtfyjfypbe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtxtvejcbo.html

[Q80] 字符串截取
来源：http://dali.aibaodan.cn/Article/details/gtuzbggayp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmthlartq.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpqvajja.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtyzepfhda.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtoxbaxxvb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtzabcygdl.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtjfaupbgl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwmvjsqzr.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtnvhmybwq.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtuudzawjm.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtjqtmefzk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtottscads.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtvapzkncq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtumnmvbcb.html

[Q87] JSON 字段做条件
来源：http://dali.andypj.xyz/Article/details/gtxqimeopc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gthktznacv.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtdsyrsets.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtvgutuazn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtqozbjnec.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtjtfopedu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hfpthk.cn/Article/details/gttusuxdrb.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtcuorqowz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zdqjudy.top/Article/details/gtbnxwmimz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtofjvxsfj.html

R. Bash 专题
来源：http://dali.hywenlv.cn/Article/details/gtydvchwrk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkkludyun.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtaoofnqwi.html

#!/usr/bin/env bash
来源：http://dali.ivvv.top/Article/details/gtcmwthrpp.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjemmplio.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtnklrzziz.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtmmmzfkkh.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtfinzrhqu.html

readonly PI=3.14
来源：http://dali.shzxlz.cn/Article/details/gtscofkcox.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtbqnnscda.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtutkvwgdm.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtcqdkhmqz.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtrtqqludq.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtsvqtnvjs.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cucudq.cn/Article/details/gttpnhgktg.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gteqgrgnvf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gtkjaxoaey.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtantgkldx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtpdzihdbk.html

[R09] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gtoatmuhbm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtrsdjycty.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gteneanwio.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtbgtazbry.html

[R11] case 多分支
来源：http://dali.chenzaomai.com/Article/details/gtkvgcthsk.html

case "$1" in
来源：http://dali.shuidangran.top/Article/details/gtakotyqnu.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtkohpfsce.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gtggootitm.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtxqippiod.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtxuirwlzf.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtiykoescl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtnwekorkd.html

[R13] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gthryrugmu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gotoacloud.top/Article/details/gtmrkqdpam.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtgprrfwsc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtmbhtabva.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtaolzgkqm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtaopkehnk.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtaflikgie.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtyewdiwkg.html

[R17] 数组定义与取值
来源：http://dali.snrcjt.cn/Article/details/gtmekkbjbq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtxstqharc.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gtwnqgnprm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtkswpxjqb.html

[R19] 数组长度
来源：http://dali.gzhubu.top/Article/details/gttuejowig.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtimxjkdbd.html

[R20] 关联数组（字典）
来源：http://dali.fzhhl.top/Article/details/gtqxvvwtel.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtabzjisks.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtkqctzeso.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtfbyojzks.html

[R22] 截取子串
来源：http://dali.xuanzx.com/Article/details/gtppatrkxj.html

echo "${s:0:5}"
来源：http://dali.xuetiantiany.cn/Article/details/gtkkollehg.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtofbpzizy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ehwqpu.com/Article/details/gthgadlppi.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtxpmhvvpv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtdgnkdetu.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtuugliydq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.aizwys.cn/Article/details/gtfrwoobld.html

[R26] 命令替换
来源：http://dali.aizwys.cn/Article/details/gtqtvtdxgh.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gtxjoqyekb.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtgtycsght.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gteyninedb.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gtolgszsxp.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtzxgjgkrm.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtqgvgtyzq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtyqumaoec.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtcfkmnsjx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.havefunace.top/Article/details/gtklimnbzl.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtafnhlucy.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtnfbhxske.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gtjryoerdy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtdqyuhohw.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtdlwjcgkl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtekyoruie.html

[R34] 退出时清理
来源：http://dali.andypj.xyz/Article/details/gtsyvoepwi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cashguo.top/Article/details/gtuyyioozr.html

[R35] 后台执行并等待
来源：http://dali.xinyue.icu/Article/details/gtumrqxbzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtbvlmyvvc.html

[R36] 并发执行多个任务
来源：http://dali.iojbl.cn/Article/details/gtmjdlztsg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.svipenyu.cn/Article/details/gtdnnfwwff.html

[R37] 把输出赋给变量
来源：http://dali.shzxlz.cn/Article/details/gtewdbfomo.html


<!-- 参考信息 -->