代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtbknpcyoh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtpetqolui.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtbjudmgof.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtavhejiir.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtuotjxbfu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtnorannax.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthopnicos.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gtbhmdpnzj.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmshrptl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtizkfczoe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gttzblfzmd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoapdodox.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gtmvxerddl.html

);
来源：http://dali.yj20258.top/Article/details/gtwhnbmalh.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gtveuwsvnv.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtoyprhznr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtdcakkokx.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtdxzqdglf.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtihvbkjqm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gthnemlsue.html

);
来源：http://dali.andypj.xyz/Article/details/gtcrsupvqr.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtkirgtizk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtzfezhozp.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtpaszmtqp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtzgtpyksr.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtpbkbwehe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gtmnhkggsw.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtjukrwrlw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shuidangran.top/Article/details/gtvgxsvjrh.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtjbnsjcmr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtfduxgcmo.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtvoyzqzfo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtcadwyysv.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtkfhpaatq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gtlsgideak.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gtmlexxdwk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtpgxmysfj.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtbmpaecov.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtmhnfpjqa.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkoxwvtz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guannengcc.top/Article/details/gtwxdkxras.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tian-w.cn/Article/details/gtftajaftq.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtkmfzreym.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtockcupnv.html

[Q14] 存在则更新（upsert）
来源：http://dali.daxiang520.top/Article/details/gtvkwhoekv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gthwbiopvt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtfuruxfgt.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gtfdkqzdxw.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtueqkhmqh.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtckcprupv.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtqjvcqzze.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtfjldpahs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtvntujzum.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gttrilaghk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtlkouqswm.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtkhecpjkx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtgbscavmn.html

[Q20] IN 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtsxastrur.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvwjchht.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtgjdsoais.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtmqmndlkw.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gttcdfkums.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtgcvbydnm.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtxcwcyolb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtecsanbca.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtoaqwyqvz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtpvbgxfss.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtmuuixcxu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gttxjlrgyp.html

[Q26] 计数
来源：http://dali.yangfankeji.com/Article/details/gtiaajknri.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtvjbzldgn.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtoyieloqe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtpysxwykx.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gthohalhof.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtvavojtop.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gteluijxcd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gthgqixemf.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtsnaerxow.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtgxlkbzgd.html

[Q31] 分组后过滤
来源：http://dali.fzhhl.top/Article/details/gtokwoexkq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gtfkhnuhuk.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtkeppnoqb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtmxtfdjon.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtjpxtjdln.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gtqihgqkty.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gteppcmkky.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtutdixeju.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtcgjsxnuc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtimxelkvr.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gthqjywzgm.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtznnymiyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtobldntje.html

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtfxevsvjo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtxwbiyngz.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtjcuwznvc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtqztuxfyb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtidxwmtaf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtxwxagich.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gteogxjiwd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtfuuehtwj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtolvywuch.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtnedzidrx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ehwqpu.com/Article/details/gtbhgdkfum.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtxkktyhcf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gthodcnqjv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gtfkqelwma.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtjgpmtjrd.html

[Q42] 连接条件附加过滤
来源：http://dali.yangfankeji.com/Article/details/gtilhywcwa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gtdxsbdyha.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gtgzvrwizo.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtjijodcjp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtagfwcmax.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gtblitlhwb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtmkwuvizd.html

[Q45] EXISTS 判断存在
来源：http://dali.yanxiufei.cn/Article/details/gtygwtizdr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gtdfddqcbx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtmpyyaxnw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtazslqrhl.html

[Q47] 与平均值比较
来源：http://dali.sxryk.cn/Article/details/gtphkrqnwu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaigtnft.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtsgdxkejd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtccjinnqx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gtmoxhhans.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtljmeiryl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtigqqtxfv.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtxgmmwftd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gthrztckyg.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gtszqpsazp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrhjiwhx.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gtsrwwozkr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtkaytxtzs.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gtyqqinukv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtnlmxdjey.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtngdysams.html

TRUNCATE TABLE logs;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjodboduh.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuibbwnvp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtuyizcjuf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtcsqyxrna.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtfrxfdihh.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtohrfgiag.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtyuaklqlu.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gtnjbjnxcq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gttnuflaom.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtimghukof.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gthqpzkvbj.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtrhmicxqs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtoqjycljb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtdmbxbred.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtpviaqorv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtgfbbjxwr.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtiaqirzrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtvfyeicms.html

[Q63] 开启事务
来源：http://dali.vqdsnc.cn/Article/details/gtrazilebk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpctmqvk.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtajifcztq.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtclxtgvto.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gtxergxkpm.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtdngrolnx.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhvyqtjj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gthhqqzefa.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gteznyvdar.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tanke756.top/Article/details/gtvrxeskgs.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtyvwiprbw.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gtpnluduci.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdytrluk.html

[Q69] 查看执行计划
来源：http://dali.havefunace.top/Article/details/gtrmfcjegn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gtprnmgdpj.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gtsugngotf.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtxfjqovkg.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvsmwbgl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhongyouzk.top/Article/details/gtazormisf.html

[Q72] 查看索引
来源：http://dali.xziqi.cn/Article/details/gthjstufik.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gthmdyiyvi.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gthaahivje.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtwofbttos.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtlyrxrjnn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtbximgrcb.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtftuobhvb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtacebxcip.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtwaagwixa.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gteehduyed.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtsqrvkuox.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtxcmpwhuk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtzfijcfhv.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtidestgpc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtqrzldncq.html

[Q79] 字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtfithwxcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenzaomai.com/Article/details/gtdbaapeut.html

[Q80] 字符串截取
来源：http://dali.smart0.xyz/Article/details/gtoyynoids.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtefpsmgjy.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtndthkcoa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdbzxvxlm.html

[Q82] 字符长度与字节长度
来源：http://dali.tian-w.cn/Article/details/gthlnzanca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhdxmlfc.html

[Q83] 大小写转换
来源：http://dali.hywenlv.cn/Article/details/gtmmjktzki.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gthrikkokk.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtiqeneakc.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbidnhtka.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gthnkovtoh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtvdmbuixc.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtaszheefu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hnqzz.top/Article/details/gtwrkqficj.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtcnylbvwv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenjidiqi.icu/Article/details/gtdampqeno.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258888.top/Article/details/gtgzosubrb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtmhbtiywa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gteuijexpi.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtogucsfjo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtprbkbqxg.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtllclcarn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtlksjqflw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdkjnzadw.html

R. Bash 专题
来源：http://dali.aibaodan.cn/Article/details/gtngdobyky.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthxnknnct.html

[R01] shebang 与严格模式
来源：http://dali.shangyingyoupin.top/Article/details/gteanbiyqx.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtsmizszdb.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtcvrvwtbr.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtczjqnotw.html

name="Tom"; echo "$name"
来源：http://dali.xuetiantiany.cn/Article/details/gtaxjazjgn.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoroojgy.html

readonly PI=3.14
来源：http://dali.0kj1m.cn/Article/details/gtcnsecouf.html

[R04] 位置参数
来源：http://dali.yj20258.top/Article/details/gtbazhrpqe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258888.top/Article/details/gtdywkxcvf.html

[R05] 参数默认值
来源：http://dali.dianchejie.cn/Article/details/gtjlfshbqs.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gtcriahgey.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtyhpignyg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sufxvd.cn/Article/details/gtfdvlzcjb.html

[R07] if 判断文件
来源：http://dali.havefunace.top/Article/details/gtkmaxaitf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtvkkioway.html

[R08] 数值比较
来源：http://dali.sweek.top/Article/details/gthvxsfygi.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtslecaczg.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtdtesoeij.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtbeilybzn.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtpcalhftg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtdpbyoqsv.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gttppxpbuw.html

case "$1" in
来源：http://dali.andypj.xyz/Article/details/gtcbahxzbz.html

start) echo "启动" ;;
来源：http://dali.daxiang520.top/Article/details/gtjkwyuggt.html

stop)  echo "停止" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrqnlcrj.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtalwoaebv.html

esac
来源：http://dali.ivvv.top/Article/details/gtbxxvzylh.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gttyawzrcb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtijrztdht.html

[R13] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtvkhazruk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtzcrhlqtk.html

[R14] C 风格 for
来源：http://dali.sufxvd.cn/Article/details/gtnlgssznu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtfneqtqtp.html

[R15] while 逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtijzraclj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtmwfuslbu.html

[R16] until 等待条件
来源：http://dali.jinqigfzy.top/Article/details/gtdamesbsm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtyjhrvbon.html

[R17] 数组定义与取值
来源：http://dali.zhixingplan.top/Article/details/gtzygznzux.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtmfzamtok.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gttrowqops.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gtmggskqcz.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtouwlpftr.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtcpbufnou.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtoyhdtboo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.guowangkeji.top/Article/details/gtdlhufbyb.html

[R21] 字符串长度
来源：http://dali.birdmap.top/Article/details/gtfwucwsfe.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtgdpzhlad.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuysmxkgp.html

echo "${s:0:5}"
来源：http://dali.ehwqpu.com/Article/details/gtdavagpit.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtyjdurddf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ppjwa.cn/Article/details/gtsaocjokb.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gttmeskoyy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtrqherfrk.html

[R25] 去后缀 / 去前缀
来源：http://dali.ppjwa.cn/Article/details/gtkeduwxan.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gaohongyu789.top/Article/details/gtcsemiqsi.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtkoifpruj.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtzeiyqnwp.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gtthdyepox.html

echo $((1 + 2 * 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtpvgbenzc.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtllnbeomk.html

echo "scale=2; 10/3" | bc
来源：http://dali.yangfankeji.com/Article/details/gtfmvqpmee.html

[R29] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtezrfoevr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gtpnqevntb.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gtsccvvgte.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtoyumcqux.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtrxlirmie.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtilypbccy.html

[R32] 参数个数校验
来源：http://dali.xziqi.cn/Article/details/gtvwzbpooq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtffpfbsvt.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtwsiftffh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtbbmhkemn.html

[R34] 退出时清理
来源：http://dali.vqdsnc.cn/Article/details/gtwwegniro.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopchxjvg.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtyoalqfvc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtqfrahviv.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtdrbqxqft.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqntqsmgi.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtykdoaqtl.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtutnebbdu.html

[R38] 管道串联
来源：http://dali.c1oappe.top/Article/details/gtnmnaouui.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtxpgsbfkd.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtmmdwiwmh.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gtnlpnokbv.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtcwhanlmd.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtnwnzslwy.html

[R41] 丢弃输出
来源：http://dali.gogol.net.cn/Article/details/gtjajmdvdp.html


<!-- 参考信息 -->