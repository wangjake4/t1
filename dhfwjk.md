代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtrkttvyfd.html

);
来源：http://dali.yuanzhike.top/Article/details/gtwwlrnysg.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtvfvsnnbm.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtgirfpkqb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gtsqrgyqnl.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrwsijfs.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtafjzaeww.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtiurftfum.html

);
来源：http://dali.fengsongda.top/Article/details/gtroofndzz.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtwpibiezz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtudbdwllz.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtracjxstj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtuzpgzprn.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gthfstcbpd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtotjaavhv.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtkamycgzg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtargmigqg.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtcgnpmfpb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtplbgaliu.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtmhpdodoe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtharfcvqy.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtlnelfwpw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtqoovgedy.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtlkupczdo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gthtxhkvvu.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gtnxpspffs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtmegphebq.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtkypgaymk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yongpay.top/Article/details/gtikyjcpbk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtfaymnycr.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtdoktzjua.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtyfgmrnoa.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtvyldztmb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtvjeutooa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aibaodan.cn/Article/details/gtumfhhizx.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtjykscqjr.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtgatelmdd.html

[Q16] 查询指定列
来源：http://dali.redwolf501.top/Article/details/gtuxlbizzi.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gtdytiayau.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gtlnttbmil.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtvmzaptyu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtfuvwggfq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtqqrxrzup.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtvnbvnsfy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.9152youxi.cn/Article/details/gtinqbqjrg.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gtslubhrhn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtmqoapvip.html

[Q21] 空值判断
来源：http://dali.daxiang520.top/Article/details/gtpieooalo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gthlndctpr.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtfsyvrtkf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtronylbhh.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtqsovdlhj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtnbmgecqi.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtsocgjrmt.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gttsbkiiak.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtgvmbcfbs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gteotcrvel.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gtkuoqoyfu.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtysmpmwhy.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtajdakxvb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthmjzfoyb.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gtvrjxtddk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtwtkzzfuv.html

[Q29] 最大最小值
来源：http://dali.nanxinkj.top/Article/details/gtkkewuxfl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtvltmwefp.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtxgdhintp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtdvlkemas.html

[Q31] 分组后过滤
来源：http://dali.sweek.top/Article/details/gtqfywnjtm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gttwrggwwf.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtwlzzromg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyforejd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtsqxkojse.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtjlewnksc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtuigloxmg.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtzsseqqbs.html

SELECT * FROM (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzpgditg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gtofamwutw.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtjqudumyp.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gttvqhnitn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtwhzinzyi.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtzdibkbyh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtoaimwczo.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtdvfrljzj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtfewlkxtq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gtmktporad.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nwbrower.top/Article/details/gtsclqcnjv.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtpagdrzec.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gttqaefbku.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtuxctnvfk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.kuanghao11.cn/Article/details/gtzoucnwcb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gtouptnlhw.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtljnfuqzz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtnwruezhr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmfmhjcb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtedfqdlon.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtbbwsdpve.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtuqfwhqeq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtcnrzgagx.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtpywzdwge.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gtldpdywen.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtuvxlpmza.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtfhtjcman.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtlcvqbien.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtmpwfwkyb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gttjfpbqlg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdytiltau.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtkukiscid.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gtfivfbpxk.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtkrijwmit.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaligjws.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtzkzxdolq.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtevzsxpcu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtincsgwfl.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gteaodyneq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtazryoqyq.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gthikzsybq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwpbjmrmb.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtpqoqflud.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtpzxlzcfg.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtsbuqwqgd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtgwflryxz.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gtpfishzsr.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtbeieykpw.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gttbnyvqjt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtlrntmblu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtvkwuzrfi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtlcisxhdq.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtwmotiejp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtdszewaxj.html

[Q58] 累计求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsxkrxzp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtcdlzgnwe.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtyocvsjab.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtbnsqglfe.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtuodgufys.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtscgqtsrr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtgodvlhfb.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtczugpyyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtpgvvklox.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtnxcjkuzz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtidnzpcvs.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtyarmerob.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtxygdngtb.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtfcrpokzc.html

COMMIT;
来源：http://dali.sysykeji.top/Article/details/gtzlwgemgf.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtcuzsspkl.html

ROLLBACK;
来源：http://dali.shuidangran.top/Article/details/gtuuzldeaj.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtlxadokyi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gtnanhptsp.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtiauuxifa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtotclgyzg.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtxwndbiio.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtgpdlgwyn.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtckeqsrua.html

[Q69] 查看执行计划
来源：http://dali.guannengcc.top/Article/details/gtwofjxtvb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gtjgpuixwl.html

[Q70] 更新统计信息
来源：http://dali.andypj.xyz/Article/details/gtbbdvifec.html

ANALYZE TABLE users;
来源：http://dali.aizwys.cn/Article/details/gtibhctcom.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gttbaxlmoc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtdirlbdpt.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gtyyyiscpu.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtfgehxryf.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtgsynecaj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gthcrpmmhf.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gtyrtfzkiy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtblxnfqkr.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtzeserajl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtyscsdoyl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtxojvbglc.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtrmgybatg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtgcumcrzj.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtnsjfrwmv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj20258.top/Article/details/gtpcjcosvb.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtiyadipii.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daria6918.cn/Article/details/gtpfsmfsfj.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtodcpdbep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtyvgzzkii.html

[Q80] 字符串截取
来源：http://dali.aizwys.cn/Article/details/gtlggponnv.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtyrlimzzz.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gticzldlet.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmpxdgbeb.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gtysylqngy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtifspxrkn.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gteslfxliu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtjqibgzsr.html

[Q84] 去除首尾空格
来源：http://dali.yueranfly.top/Article/details/gtyndsfpff.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtssnitetg.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtvrkkgykr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtoqepeeeq.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gtppbonije.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtnknoteeo.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gtmsxxeftv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtyqkbdggm.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsggamsa.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gaohongyu789.top/Article/details/gtnkqqduyr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxhkuonjj.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtnqqslrne.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ybcxt.top/Article/details/gtwhhbdxeo.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtlluevtky.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtpdobcgsy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtuzvrllxn.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gtpfykrapr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttloluzcy.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gtiucjkspl.html

#!/usr/bin/env bash
来源：http://dali.snrcjt.cn/Article/details/gtkuwrpzcn.html

set -euo pipefail
来源：http://dali.shzxlz.cn/Article/details/gtgieevetc.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtdkeptbjx.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtbvvhzlzw.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjdmzxyum.html

readonly PI=3.14
来源：http://dali.tanke756.top/Article/details/gtugjzpgpm.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtadvubhrq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtuozviokt.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gtaduiuhuk.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtdfsguwtg.html

[R06] 判断命令是否存在
来源：http://dali.hfpthk.cn/Article/details/gtfwrwdqob.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtgjlocvct.html

[R07] if 判断文件
来源：http://dali.jqgfzy.top/Article/details/gtkmxmfbnl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yvedp.cn/Article/details/gtinnxymxe.html

[R08] 数值比较
来源：http://dali.sufxvd.cn/Article/details/gtvvwwavmz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtjsvwvnhs.html

[R09] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtorzigczy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtfafmrhqf.html

[R10] 正则匹配
来源：http://dali.0kj1m.cn/Article/details/gtlhnrpivb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.quarkkingdee.top/Article/details/gtqmdgryqy.html

[R11] case 多分支
来源：http://dali.yonumen.top/Article/details/gtsfaqmaij.html

case "$1" in
来源：http://dali.sweek.top/Article/details/gthljyiypp.html

start) echo "启动" ;;
来源：http://dali.yangfankeji.com/Article/details/gtrpragfwl.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtkgrihpfo.html

*)     echo "未知命令" ;;
来源：http://dali.kuanghao11.cn/Article/details/gthyjqsyho.html

esac
来源：http://dali.hammf.cn/Article/details/gtlwcqrefg.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgabxpgpz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gtlpviinqz.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtixrvffru.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xinyue.icu/Article/details/gtdxhcspmw.html

[R14] C 风格 for
来源：http://dali.chenzaomai.com/Article/details/gthhsmqzuu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrowhntm.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtstlshczq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtdsovaxje.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gthtoqujzz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtsvejdlae.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gtxeemhbrc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtcpkrlxjb.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtuwbyeopq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.kuanghao11.cn/Article/details/gtwupmxuwi.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtqnmfpskh.html

echo "${#arr[@]}"
来源：http://dali.0kj1m.cn/Article/details/gtuqlpmgiy.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gtaunacngg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258888.top/Article/details/gtpgezcqie.html

[R21] 字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdudbwtvo.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gtolgqowsg.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtcjbmhloa.html

echo "${s:0:5}"
来源：http://dali.sufxvd.cn/Article/details/gtqpqqzdzs.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtnepigzkm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtzsymigzi.html

[R24] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gtohgjuggh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nwbrower.top/Article/details/gtxsxaelgb.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangshuangyany.cn/Article/details/gtuupazvke.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gthxkskgbd.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gteisrgqad.html

now=$(date +%F); echo "$now"
来源：http://dali.pycfn.com/Article/details/gtscqvsfdo.html

[R27] 算术展开
来源：http://dali.guannengcc.top/Article/details/gtepttfxzl.html

echo $((1 + 2 * 3))
来源：http://dali.cucudq.cn/Article/details/gtgwhfgnep.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtmjtbrrql.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiwuxcuv.html

[R29] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtrxiiehau.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shzxlz.cn/Article/details/gtqjuwoagw.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gthqjqyjlb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.meibo888.top/Article/details/gtikgcckxe.html

[R31] 局部变量
来源：http://dali.aibaodan.cn/Article/details/gtwrmyadcg.html

f() { local x=1; echo "$x"; }
来源：http://dali.hammf.cn/Article/details/gtjpgetiem.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtasmrloep.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtvcvzpidi.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtwzhlsyuc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtyngrtzpe.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtcvavwzlw.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtzhipalzb.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtifuwwqwm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.havefunace.top/Article/details/gtuaegsfwd.html

[R36] 并发执行多个任务
来源：http://dali.guannengcc.top/Article/details/gtziajiaxw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtujggxdai.html

[R37] 把输出赋给变量
来源：http://dali.yongpay.top/Article/details/gtsgslpktt.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gtaqsveanc.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtoepgdgrn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhiwuduotai.top/Article/details/gtrkijtzrn.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gtfkdiuidn.html

cmd > out.log 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gtjhrpkyol.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtwrkxcswe.html

echo "log" >> out.log
来源：http://dali.cdnleiting.top/Article/details/gteqgbghnc.html

[R41] 丢弃输出
来源：http://dali.jianghu66.top/Article/details/gtaujermxl.html

cmd >/dev/null 2>&1
来源：http://dali.guowangkeji.top/Article/details/gttwggzxmd.html

[R42] 输入重定向
来源：http://dali.wangdashe.top/Article/details/gtnfciudcq.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtnmewvvew.html

[R43] 按名字查找文件
来源：http://dali.xylfe.cn/Article/details/gtesbrixjy.html

find . -name "*.log" -type f
来源：http://dali.xinyue.icu/Article/details/gtoogyetov.html

[R44] 按修改时间查找
来源：http://dali.cucudq.cn/Article/details/gtllqzwopd.html

find . -mtime -7 -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxdncmut.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtssbnkjzk.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtywpzxibb.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtnbmihgth.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtprgenjdw.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtnkthkqah.html


<!-- 参考信息 -->