代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtmxbwqewz.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtisjtexab.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtmfsinkat.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxwqsfni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbubyben.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gtxlavagrr.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtcwdkrrmn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gteijejaeg.html

);
来源：http://dali.yj202588.top/Article/details/gtkaoawaet.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtzkqdzszy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hysaishi.cn/Article/details/gtjtmcpnim.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtcibfggrt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdbgzvtj.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtxynnrroy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gthqmvhvyu.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtdxdjcjly.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtzvlsdtvw.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gtcufemldt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtlmlzxplf.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gthsbuczti.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbazptwe.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gttzmyeqlw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtqddkipfs.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtnfzvonkz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gtekjdrybp.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtuqplfpeo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtlinpnxxf.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtxamvdzwp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenjidiqi.icu/Article/details/gtnndlvfhf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtfnozedby.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtjphanzxj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtntjdgqaj.html

[Q14] 存在则更新（upsert）
来源：http://dali.kuanghao11.cn/Article/details/gtmndjedpt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwqjhmda.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaauutpd.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtgejapkkq.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtmyybthqu.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtdqmlpydl.html

SELECT id, name FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtokkjfwff.html

[Q17] 条件查询
来源：http://dali.cheryme.top/Article/details/gtlkboayty.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gtwrkvxrug.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjpijvvh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ehwqpu.com/Article/details/gturvzvsgx.html

[Q19] 范围查询
来源：http://dali.guannengcc.top/Article/details/gtplicqadi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtemnqoqdy.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gttxjriqln.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtvodlcsko.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gtjvwbwmdq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenlongwang.top/Article/details/gtaituzqvz.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtelqnmfvd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtbpdyqbbi.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gtfwbgrfjx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gtgxohzicu.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxibnphz.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gthgizwqvl.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtfpmxdgmg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtcflooehy.html

[Q26] 计数
来源：http://dali.jiagoushi.top/Article/details/gtobjgbmlf.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtjlfmoxun.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtssmoyurz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrqjsjwru.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtvzbddpko.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtryjutpdz.html

[Q29] 最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtkgmssjjq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtzvrmauyf.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtccsucxye.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtmuvgqjeb.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtyxcjdrrb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.snrcjt.cn/Article/details/gtalbvfgrn.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gttzotmhdt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtobrljudr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gtgedvywhp.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvbgxhhh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtdgpwrrjw.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gttrlnuiob.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtxubwknye.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gthriisvua.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gtbxgcamqu.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbpennlq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhaatcei.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtirjceqri.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtnkluyzri.html

[Q37] 右连接
来源：http://dali.shuidangran.top/Article/details/gtadxzhbic.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pycfn.com/Article/details/gtbrqpvscz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtcldljmxb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtrvpvvblw.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtjidzrywa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gtgvhguwjg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.snrcjt.cn/Article/details/gtqgktsvlf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gtjusotahe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtcwxzlbvc.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtxjquakft.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsbkbcfn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gtuxsofhws.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtndfuvdmq.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtqlqhawct.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtcfduinmj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gtbsxbwxty.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtnyfiavab.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtbgkahrzp.html

[Q44] IN 子查询
来源：http://dali.guannengcc.top/Article/details/gthdtghgts.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gtdkqxtocd.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtdobwfziq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gthfuoedie.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtqrjdooeo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtzxxbpeay.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtrjygmrju.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtvowgdiyg.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwbasdkb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ehwqpu.com/Article/details/gtdzsovrpi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtorkyucnt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtcloutxns.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtunhivbid.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneqfjiuc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.redwolf501.top/Article/details/gtyjyxivyv.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtygmlqqiv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtznmefadi.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtcpasoekr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gttezplwrq.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gtmxdubemm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gtimjyauau.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtojoyuzuy.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtciuyhjnt.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtjlclupes.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtrdittohp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gthysnhawq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtahopqjez.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gteloqritk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxctilfy.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtjkitcres.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtqhhpxtoh.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtjlcnupja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtmtnaeyuw.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gtxxerkrql.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gttasszyxr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gteptjojiv.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxpijktp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtvjmmpjlk.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtilpwwtwi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtfjxbbbmb.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtjhgtsbxe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xylfe.cn/Article/details/gtnxaesuve.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtwcwlpqds.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gtyzimybul.html

[Q65] 回滚事务
来源：http://dali.yonumen.top/Article/details/gttfpyeffv.html

ROLLBACK;
来源：http://dali.fzhhl.top/Article/details/gtyibrmpnq.html

[Q66] 行锁查询
来源：http://dali.316326.xyz/Article/details/gtxcytnoxk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtmhgdqlsi.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtzlaipazs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtawlaiugn.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnpguokz.html

SAVEPOINT sp1;
来源：http://dali.havefunace.top/Article/details/gtimglhxqj.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtrpzebwqt.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gttntjkjpu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtgzciyqcs.html

[Q70] 更新统计信息
来源：http://dali.chenlongwang.top/Article/details/gtulsjxkyy.html

ANALYZE TABLE users;
来源：http://dali.jianghu66.top/Article/details/gtcphvavei.html

[Q71] 查看建表语句
来源：http://dali.meibo888.top/Article/details/gtebhbbhty.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtwkegoiqn.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtensqpzfg.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvrfbanhf.html

[Q73] 查看表状态
来源：http://dali.svipenyu.cn/Article/details/gtgpbomoyl.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobbsawsc.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtuoqyxcpy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtncgghlcw.html

[Q75] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtbbzgfrdf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtieszhufx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtykhvzqoc.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gttvdjcxgy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gttbqsenyz.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtnvsozvgn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtlelyrpfv.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gtcxncnlbf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtqwtucoyn.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gthkjokuei.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pengpengdd.cyou/Article/details/gtdahgwetj.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtiwnxnpme.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtphkszxxs.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtrwduqftt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfqiuunpe.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtfcpcscig.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gtxfbleuav.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtsflxszyw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gthagubmcr.html

[Q84] 去除首尾空格
来源：http://dali.jqgfzy.top/Article/details/gtvibpcpnr.html

SELECT TRIM(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtjhbsheng.html

[Q85] 数值取整
来源：http://dali.xuetiantiany.cn/Article/details/gtklqterpv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhixingplan.top/Article/details/gteucmcffm.html

[Q86] 读取 JSON 字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcecmjnh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtmtulektm.html

[Q87] JSON 字段做条件
来源：http://dali.jyoumei.cn/Article/details/gtoklpjyku.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtuckbemgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtxmyaeega.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtkddcpojb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hysaishi.cn/Article/details/gttfhootlb.html

[Q89] 判断表是否存在
来源：http://dali.gogol.net.cn/Article/details/gtbxbeemai.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtnbhygrbi.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtomckjcqi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hongshengwenyu.top/Article/details/gtphckkzwa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjxbgycba.html

R. Bash 专题
来源：http://dali.shuidangran.top/Article/details/gtjrekkkhf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtykrugqha.html

[R01] shebang 与严格模式
来源：http://dali.cashguo.top/Article/details/gtbakxvzle.html

#!/usr/bin/env bash
来源：http://dali.birdmap.top/Article/details/gtvwidrove.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtftqmagqz.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtyzbrlzvv.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gtqgvssuba.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtavwzwygm.html

readonly PI=3.14
来源：http://dali.jinghuilouyu.cn/Article/details/gtntkszthh.html

[R04] 位置参数
来源：http://dali.havefunace.top/Article/details/gtdfdbsthq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gteggvtmfs.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtwlqzxfim.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtwyhywuen.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtwmiyeehv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gtwwsxlpfx.html

[R07] if 判断文件
来源：http://dali.daxiang520.top/Article/details/gtitggnkjp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtffctmmml.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtvtvgwsfk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gtnfdwggis.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtntjttzxu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtqtjugymz.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhegnlmw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gtavjqipzo.html

[R11] case 多分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzodflwin.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtocizgtus.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtqidhtkmu.html

stop)  echo "停止" ;;
来源：http://dali.daria6918.cn/Article/details/gtsssgbsfv.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gtxspctmrk.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gthnfjqbha.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gtzvodpbms.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtodjtvrsq.html

[R13] for 计数循环
来源：http://dali.0kj1m.cn/Article/details/gtdeccpljk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtbzpztgaq.html

[R14] C 风格 for
来源：http://dali.tian-w.cn/Article/details/gtywjjbzyz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtbtnlyfmx.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gthrsuppqz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yongpay.top/Article/details/gtlvueogzm.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gttrhjclec.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtqaufsirf.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gtrdphzrii.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daxiang520.top/Article/details/gtpriktqdi.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gttiyqfzoc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.snrcjt.cn/Article/details/gtxxshsctj.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtjjrgfjpy.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtepnohczw.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtzfoyfigu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykuwhham.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtgfhmlwpz.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gtlgmcaugz.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtfpmmgyrp.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtfqnxzepm.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtidlxiirr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dashuyun.cn/Article/details/gtrzwppcay.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtghvgssgv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtqidkneyc.html

[R25] 去后缀 / 去前缀
来源：http://dali.kuanghao11.cn/Article/details/gtcbwyjjdc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtrpkkaleu.html

[R26] 命令替换
来源：http://dali.yj20258888.top/Article/details/gtjpjwhpsz.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtodksegbf.html

[R27] 算术展开
来源：http://dali.jinqigufen.top/Article/details/gthkeufdff.html

echo $((1 + 2 * 3))
来源：http://dali.pycfn.com/Article/details/gtwaobzkfc.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtpuvxtlab.html

echo "scale=2; 10/3" | bc
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqdficzw.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtopuverrg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ppjwa.cn/Article/details/gtkoflpjat.html

[R30] 函数返回状态码
来源：http://dali.xinyue.icu/Article/details/gtvxfqigwl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttarnenzc.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtiqmwnulu.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtgagnezyf.html

[R32] 参数个数校验
来源：http://dali.hongshengwenyu.top/Article/details/gtxrawnzhb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hywenlv.cn/Article/details/gtrbljocyc.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtbhhwnjdy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gtqkylgofz.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtjjqnwkgh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtuvlktruo.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gteqsnovfc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.redwolf501.top/Article/details/gttiddaaox.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtcrhshsvs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.smart0.xyz/Article/details/gttvccuduo.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjqmavqfw.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtlzkxabfk.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtruzraqbk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hywenlv.cn/Article/details/gtylzodfzk.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtrhrbpasv.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtawlibdow.html

[R40] 追加写日志
来源：http://dali.yj20258888.top/Article/details/gtxidfmzcz.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtcquqydne.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtolibswva.html

cmd >/dev/null 2>&1
来源：http://dali.9152youxi.cn/Article/details/gtgrhabzjk.html

[R42] 输入重定向
来源：http://dali.yj202588.top/Article/details/gtywplxxsw.html

wc -l < a.txt
来源：http://dali.guannengcc.top/Article/details/gtabslydnu.html

[R43] 按名字查找文件
来源：http://dali.sufxvd.cn/Article/details/gtjcxumwog.html

find . -name "*.log" -type f
来源：http://dali.feifeiyinyue.top/Article/details/gttecemgsd.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfnphcnk.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtmphihlnm.html

[R45] 批量删除
来源：http://dali.haohaochexian.top/Article/details/gtwkwvhumc.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtmentehka.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtymnrfwjw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtfvcuyjje.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gtpoihveje.html


<!-- 参考信息 -->