代发 wailian999

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzhfzsejj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtliinzrln.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfdyqudin.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtmfzppoqu.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtruqfspps.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gttafzjmbu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtmgnrrsdo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtkoddmkil.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gtyvrivxqv.html

);
来源：http://dali.meibo888.top/Article/details/gtqsiepynp.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtfdskbynd.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtifmiodvm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtovnbbwka.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmvakate.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtmikdmqgg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtoxddiedr.html

);
来源：http://dali.tianlin.xyz/Article/details/gtmuqspzpz.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtkbujzrox.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gthngvsduc.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtvpgetzda.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtoasalcfu.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtglvokubc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtpqyodkiw.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtkutyfbyp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gtzjcvinmk.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gthhxnrwyk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtpheemaem.html

[Q08] 创建普通索引
来源：http://dali.hfpthk.cn/Article/details/gtkmoyhkuc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gthkcocuwh.html

[Q09] 创建唯一索引
来源：http://dali.shuidangran.top/Article/details/gtwvgsnrsx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtpfhobnqc.html

[Q10] 插入单行
来源：http://dali.wangdashe.top/Article/details/gtyvperase.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gtkbejgvxj.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtopmnsvdp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtygnrchsz.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtbfzdjlfa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtgpkucjlb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtktmlzqbh.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gtfzbuuhhc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtqifsaqnj.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gtsokfjbpc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcilzhewb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtaygrhptk.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gtjtpvnraw.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gthoadijsn.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gtjukgpnef.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgqcjypo.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtsdjguaoe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtmnkbzleg.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtkabmdabc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtrnlmtmmt.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gttjcuqdjy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtrhpcztjm.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gtqviqluml.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtqpqpabmx.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtmadbgicz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gtvsgeyjne.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtfdobybdm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtalyhqbem.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtbbqowxsk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzkxiego.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtwmknidkn.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtomyfuoqg.html

[Q25] 只取前 N 条
来源：http://dali.kuanghao11.cn/Article/details/gthemvtrrg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gttjrcnoxe.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtvclcxhcl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtukwydmpj.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsccajgfq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gthqchcqpk.html

[Q28] 求和与平均
来源：http://dali.jqgufenzy.top/Article/details/gtjvlemqve.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtnhcnajcg.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtywghbgwn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtimljpwqm.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtzhnvrssx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtejnklzqo.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtzbgmhllt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtrujmzeni.html

[Q32] 分组拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtaxzicbzh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwstsqwr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtevbuhmdu.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbiuzuka.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtziecxrjz.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtszjlnchb.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtkjqgauex.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtpbfqzjpg.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzsvmeil.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtlsakzaqe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlywrbzp.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtsnyqnlua.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtemjyivrp.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtzainwqsv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gtarsawneu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gtajdtfsff.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtvjhmxcnt.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtdepfpesg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtivgsdiwn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhqucktj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtgctuhfxa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtfbouicoq.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtgplcpdhu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtombllffm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtssnowyng.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ydzc1.top/Article/details/gtubislmav.html

[Q42] 连接条件附加过滤
来源：http://dali.jyoumei.cn/Article/details/gthpihuphx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ivvv.top/Article/details/gtiobyjmxq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gtrkadqwdf.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtvawfyhtu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtfdudhqoz.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtlwelqzgt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtqrsrpfkj.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtghqfbqxx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ybcxt.top/Article/details/gtpdpyymhp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtlgkifjhu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtvczqphci.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtslrufnza.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtbbfahaco.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtepywclka.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtngxryrno.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtmuxsingn.html

[Q49] 更新单行
来源：http://dali.gotoacloud.top/Article/details/gtkqfmmpbh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtvnhezfmz.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gtsmylezab.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gttdaeueij.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtabxiyenp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtaraosyhx.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtwdkyrpwu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtirxtmwae.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtvgiedpmq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtprbmcmaz.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gttrknfyxu.html

TRUNCATE TABLE logs;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvijtbje.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtptjmtvlx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtxeknzbnu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtosybhipl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtkzbxmhue.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtvissyvyy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtkvsqpvpc.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtitmlxpgm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtbsjvquxi.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtwgwkaahw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtlrutxcuy.html

[Q60] 取上一行 / 下一行
来源：http://dali.yangfankeji.com/Article/details/gtcyahtdys.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtnxloosal.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtlvaxlaqv.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtxngugltl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwqyfnoh.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gtjjtxxsqx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtwjkdhbfj.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtwntlemhm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtnyerdpdb.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtlbawxthc.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtbwbcrxuk.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtiyidnidp.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtvbyhbhyz.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemnrvxhe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtapmascrq.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtnkemeflk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtdbxsopra.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gtmukuuxef.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gthsiutrww.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtunyhggdy.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gtmghblgvy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtxrejtwqm.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtpllghino.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtzevwkhjy.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtptwljjaj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gthqwcyqrx.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtzydvaibl.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gttnvkutoc.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gthqkdwpsj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtkkxiqblr.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtaakmvczn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtbvndeojn.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtklqananv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrwftmgu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xylfe.cn/Article/details/gtngufpnmr.html

[Q76] 按天统计
来源：http://dali.yuxming.cn/Article/details/gtptwmakrb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jlsjyb.cn/Article/details/gtrocmxyuk.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtfrtowlxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtjtujpqxo.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtersmrfma.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gtukwbgtpe.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtxrbrhrxp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.9152youxi.cn/Article/details/gtgvmftnia.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gtdshkbkwh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxxpbrlkw.html

[Q81] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gtqwyropox.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtrlcfarbu.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtozzgfpma.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtgvkarlga.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtowxrbyqm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtlihvcmtt.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gthezlhpfc.html

SELECT TRIM(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtxosfmqiw.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtbayndfcg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gtsvrtwbym.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtegygfkjv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yanxiufei.cn/Article/details/gtxvfqhbey.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtjnmmiarj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gtznrcwlfz.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtrwnecgtk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gthwifxvgq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmvoxhxxj.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtshcvcrnl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtzzxyhngz.html

[Q90] 生成序号列
来源：http://dali.yj20258.top/Article/details/gtywnxstsy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtfzcmnsai.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtisacueqa.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gtsyeqguzs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtddqltigy.html

[R01] shebang 与严格模式
来源：http://dali.ivvv.top/Article/details/gtlrnareib.html

#!/usr/bin/env bash
来源：http://dali.hnqzz.top/Article/details/gtyyjdkriz.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtutzeggff.html

[R02] 变量赋值与使用
来源：http://dali.yj20258.top/Article/details/gtnpxzxbvg.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gtpmtjukmx.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtvwxmxegk.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtdgiyunxt.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtjksgzrah.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtvrpxrqkg.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gtzlcdomzd.html

name="${1:-default}"
来源：http://dali.chenlongwang.top/Article/details/gtxfriusnz.html

[R06] 判断命令是否存在
来源：http://dali.aibaodan.cn/Article/details/gtzsctqcca.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtzledtpsg.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gtvhzadtod.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hywenlv.cn/Article/details/gtrvhhkfpw.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtqnnjrmmq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gtaecrdtfl.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtaydkwrqg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtesyqbwjg.html

[R10] 正则匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgprttxi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gthwqldjcp.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtqwcyxjmi.html

case "$1" in
来源：http://dali.yvedp.cn/Article/details/gtellbitqb.html

start) echo "启动" ;;
来源：http://dali.sxryk.cn/Article/details/gttnskgjsn.html

stop)  echo "停止" ;;
来源：http://dali.quarkkingdee.top/Article/details/gtxnxqwdor.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtaxpkiidl.html

esac
来源：http://dali.jiagoushi.top/Article/details/gtewwmktdv.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtgoeoxirm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinqigfzy.top/Article/details/gteqrmdolj.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gtdlnxswgy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtshbapgfb.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtbdzjgohg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtxgqwqtgp.html

[R15] while 逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtvmncfumm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.haohaochexian.top/Article/details/gtqyjiqdxq.html

[R16] until 等待条件
来源：http://dali.feifeiyinyue.top/Article/details/gtbepoodnw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtiasvfxlh.html

[R17] 数组定义与取值
来源：http://dali.bjfxy.top/Article/details/gtrmgrqshx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtiailghyz.html

[R18] 遍历数组
来源：http://dali.9152youxi.cn/Article/details/gtkntimugv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigufen.top/Article/details/gtuvtqfvqp.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtkxhrwahs.html

echo "${#arr[@]}"
来源：http://dali.daxiang520.top/Article/details/gtdhrhwgri.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtofwqpoxf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangdashe.top/Article/details/gtxcgpbxwx.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtyaopempt.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtyosalfdg.html

[R22] 截取子串
来源：http://dali.chenjidiqi.icu/Article/details/gtaoztpqmk.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtraswzpvh.html

[R23] 字符串替换
来源：http://dali.smart0.xyz/Article/details/gtkfmfslas.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtinoohuco.html

[R24] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtvxtiosiz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gttjzrflwk.html

[R25] 去后缀 / 去前缀
来源：http://dali.havefunace.top/Article/details/gtoomwubfy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtmuukxyki.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtnggcwzww.html

now=$(date +%F); echo "$now"
来源：http://dali.xinyue.icu/Article/details/gtaoqtqnba.html

[R27] 算术展开
来源：http://dali.xuetiantiany.cn/Article/details/gtkmmrymus.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcplbspem.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztojtosm.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gtpjzttvxz.html

[R29] 定义函数
来源：http://dali.jiagoushi.top/Article/details/gtqbdmyzth.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yvedp.cn/Article/details/gtuefsdegz.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gtvkxcruge.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtxagnnpqg.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxoksiqb.html

f() { local x=1; echo "$x"; }
来源：http://dali.hysaishi.cn/Article/details/gtxsaopjhi.html

[R32] 参数个数校验
来源：http://dali.yvedp.cn/Article/details/gtphvcxwlm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtidqwmzta.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gtgteevlej.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gtwgkiqpzo.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtzhqakpmk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtrlofxiim.html

[R35] 后台执行并等待
来源：http://dali.redwolf501.top/Article/details/gtlgwcqxdn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqgvlazk.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtfdwdauui.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.meibo888.top/Article/details/gtkiedpgme.html

[R37] 把输出赋给变量
来源：http://dali.dianchejie.cn/Article/details/gtrtsorpao.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtgqszqeyw.html

[R38] 管道串联
来源：http://dali.cashguo.top/Article/details/gtovbypzik.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gtpqmuciys.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtuooywdzv.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtomgdxycr.html

[R40] 追加写日志
来源：http://dali.yueranfly.top/Article/details/gtfmecvubf.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaticamz.html

[R41] 丢弃输出
来源：http://dali.yj202588.top/Article/details/gtlqgfwuuj.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gturnrauqq.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtqdcwhavy.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtndhaqynj.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtunwgnqds.html


<!-- 参考信息 -->