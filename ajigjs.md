代发 wailian999

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ybcxt.top/Article/details/gtjqsdyaun.html

);
来源：http://dali.mhx1999.top/Article/details/gtnvycgwud.html

[Q02] 创建带外键的表
来源：http://dali.ivvv.top/Article/details/gtevazkacz.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtavhjlntx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gticppqzhv.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtcccxgbun.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtldrrohci.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gtmjbuujnf.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtepguabqa.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gtaortodgq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtktbkpdyr.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyppywes.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gtilqvesii.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtlhqocndq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258888.top/Article/details/gtxkkdgkqf.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gturlglfmo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenlongwang.top/Article/details/gtwsgkinar.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtvvlwkitr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gtxeokbxnv.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtfytmqlpj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtfgmvowsd.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gteaosiath.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtctomgppj.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtfbmiueno.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gttadgzjwe.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtytvfrumc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgonyedqo.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtbxfvomor.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtippburtw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gthaiyfrvz.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtrmrifjbp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtzsojxbfn.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gtvdxyxbhd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtshzpcpcn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnbxkpzb.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtdbkmagmd.html

SELECT * FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtqobbrnef.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtrutvojqq.html

SELECT id, name FROM users;
来源：http://dali.redwolf501.top/Article/details/gtnggeabgl.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gtsqdtrute.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gtvdxngrvt.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtschaxqip.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtlouecpxc.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gtsrgazhar.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtprqhpabe.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gthlkfgplw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttclplxzl.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtkchjauyt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtxmpukogp.html

[Q22] 排序
来源：http://dali.nanxuanxn.top/Article/details/gtdbhhunpw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtsartnxdk.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtmoxnvlts.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gthufabfms.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtstxbksko.html

SELECT DISTINCT city FROM users;
来源：http://dali.nwbrower.top/Article/details/gtavylsquv.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtdembfshz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtiivyvnrh.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtfeimtfra.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtgdyngjok.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gtykwgfhwn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gthwhmcfid.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtqclvihkj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtmokyvzpd.html

[Q29] 最大最小值
来源：http://dali.smart0.xyz/Article/details/gtodjpsoyy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtsxtcsxfp.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtjakdiihb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxkxlmous.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtqjthsrpa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtrredzpmu.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gttsszzsrx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtlhnqvvjb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtfumtaxhw.html

[Q33] 多列分组
来源：http://dali.hywenlv.cn/Article/details/gtffvzlrdh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gturwexydi.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtmpuqglpo.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtggopzobn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gthywsqwln.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gttgsfdjtg.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gteqhtfhdw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtvhvntpco.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gtfsaznpeq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtypbpirxu.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtuqgsxmqd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gtyxruiium.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtnfwbigrh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gtyqjsraxo.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gtoqodoenw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtmybiieak.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtvuwjfiop.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtqhcdzjcx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fengsongda.top/Article/details/gtymexuqdq.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gthfkbxsco.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtoqqdkmhn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gthpfzuwyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daria6918.cn/Article/details/gtolfxhkis.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtbruflwch.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtrndpvjps.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtrnsrpnoh.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtecakitbu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtnxtnhcnf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gtjomcnmic.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtyasikvdc.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtaobcgbkd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtnnkhmmyt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gtobcpeyza.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtaxlaqglj.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwljecrs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtolfmgvmd.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtwsowbonq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gtxilwozub.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.redwolf501.top/Article/details/gtxvletrip.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gthfhwcuhr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtqdbmlmht.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkhjcyry.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gteqzegpoq.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtxhgeqyej.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvhfmfnw.html

[Q52] 删除指定行
来源：http://dali.iojbl.cn/Article/details/gtbwdflicf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtzatqdjvz.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepuxezss.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ybcxt.top/Article/details/gthfjrgmzx.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gtbytdawjg.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gttjawnace.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtsjyxdvue.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtglwgcppj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shangyingyoupin.top/Article/details/gtuzpnteox.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtajkcfrzw.html

[Q57] 行号
来源：http://dali.wangdashe.top/Article/details/gtzcvjpmms.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtprzzuzoe.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gttiknewhh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtycahjhbc.html

[Q59] 分组内累计
来源：http://dali.yangfankeji.com/Article/details/gtcxhplbwg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtwcifijte.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtdwhlmcnw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtfqhpdzdd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcedtytw.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gtiaenmgwr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtjibavtyh.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gtnbycuckm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtrxtxjsfz.html

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtixlbwbfz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gtakcvidms.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtxywapfsl.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gtmzvrsmnk.html

[Q65] 回滚事务
来源：http://dali.shuidangran.top/Article/details/gtgdfyvjom.html

ROLLBACK;
来源：http://dali.birdmap.top/Article/details/gtgdjbrbwt.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtegfrtlqy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjunpqfc.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtwossfzzx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.smart0.xyz/Article/details/gtuukorfsm.html

[Q68] 保存点
来源：http://dali.yvedp.cn/Article/details/gtylnkyppb.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtsiwuuzov.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtyaxfmnjy.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gtaotxpqkt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aizwys.cn/Article/details/gtfupcnely.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtixiugndj.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtuovwhahc.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gtigcoosmi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtksmhboei.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gtshwcjfom.html

SHOW INDEX FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtxvmkqdpq.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtleglqrrr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtwbmyhfbh.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gtiadbddqq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtenebwvhf.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdxuatva.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtxrttewvy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aibaodan.cn/Article/details/gtfjfxocbu.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gtkciiyaso.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbnhqeqr.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtrlrpkogh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtyqvwtxhv.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gtkwtsmqli.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jianghu66.top/Article/details/gtefjwcjhy.html

[Q79] 字符串拼接
来源：http://dali.jiagoushi.top/Article/details/gtlofktvwt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuetiantiany.cn/Article/details/gtkgamkkys.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gtljgbrayf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtenzkqgtg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtgrsptygs.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtgxszzlgy.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtzzfkoquq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmvfedpcf.html

[Q83] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtcfatulzi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtvcuswfzm.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gtgjhmpjoo.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbfncnrfe.html

[Q85] 数值取整
来源：http://dali.jinqigufen.top/Article/details/gtygjwgquf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gtwcubjszr.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gtsqbbjyre.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtwlpkzlyb.html

[Q87] JSON 字段做条件
来源：http://dali.mhx1999.top/Article/details/gtsppayizy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gthxuaodbq.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtberhaqrr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjpsvwdz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcsweccc.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtbbsutwio.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtzbozdndt.html

[Q90] 生成序号列
来源：http://dali.yonumen.top/Article/details/gtzpoflrms.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gtwwdzeast.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtppgsjega.html

R. Bash 专题
来源：http://dali.jqgfzy.top/Article/details/gtmrajlbuw.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtezaugpmn.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtqggsootm.html

#!/usr/bin/env bash
来源：http://dali.dashuyun.cn/Article/details/gtwqaqtxvf.html

set -euo pipefail
来源：http://dali.svipenyu.cn/Article/details/gtsarnltrq.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtqjbhozet.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtaajhtkgr.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtuojexvqy.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtcdmwohlo.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtktupnahv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhengqikj.top/Article/details/gtnczcugtr.html

[R05] 参数默认值
来源：http://dali.iojbl.cn/Article/details/gtkmldxxtv.html

name="${1:-default}"
来源：http://dali.cqqwz.cn/Article/details/gtwlseqpxv.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtgxictffl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtjdnhjmwq.html

[R07] if 判断文件
来源：http://dali.pengpengdd.cyou/Article/details/gtczgdizou.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtpevdmvqr.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gtobgqtkwg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gtldjvrwgb.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtjaejrtsl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtzmiunwnl.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gtoblrmxrt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtbcmmeoou.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gtppdflwnd.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtherhibrl.html

start) echo "启动" ;;
来源：http://dali.cheryme.top/Article/details/gtyzntmtpn.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gtziezgqdm.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtjyhvoxvc.html

esac
来源：http://dali.hongshengwenyu.top/Article/details/gtvvcdesqn.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gtugvvexwp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.316326.xyz/Article/details/gtujyxbhtf.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gtdganmkav.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtexsrbvuq.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gtpnwkuplg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtuowslwaz.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtbjkqyvcg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cheryme.top/Article/details/gttrahnipn.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtsskfbisu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtspjgnlph.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtbldjjhac.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwikoaep.html

[R18] 遍历数组
来源：http://dali.hongshengwenyu.top/Article/details/gtxblfwnpc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.dianchejie.cn/Article/details/gtgtatwxyr.html

[R19] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtyxiuxfmv.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchrrvomb.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtfbllasdg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtnyumnito.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtvtjyxcyh.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gtpghucpct.html

[R22] 截取子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyfmvjzw.html

echo "${s:0:5}"
来源：http://dali.zdqjudy.top/Article/details/gtrmjovswt.html

[R23] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtgmwgungn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gttkzgczeb.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtkpbwkrkv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtwypwztuv.html

[R25] 去后缀 / 去前缀
来源：http://dali.shangyingyoupin.top/Article/details/gtyqjzjfor.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guannengcc.top/Article/details/gtwqkwfxyc.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtigyolqke.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtzgejcgpq.html

[R27] 算术展开
来源：http://dali.guowangkeji.top/Article/details/gtcxmsbjth.html

echo $((1 + 2 * 3))
来源：http://dali.wangshuangyany.cn/Article/details/gtspyyobpa.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtkvcoznlp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtbddlptox.html

[R29] 定义函数
来源：http://dali.wangdashe.top/Article/details/gtilgyizdo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmhwjyrr.html

[R30] 函数返回状态码
来源：http://dali.sysykeji.top/Article/details/gtgephfwau.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hammf.cn/Article/details/gtyoeewfqo.html

[R31] 局部变量
来源：http://dali.havefunace.top/Article/details/gtjrmisbnr.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtudjtvtgq.html

[R32] 参数个数校验
来源：http://dali.fzhhl.top/Article/details/gtgrtecftd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiwqytqeu.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtjrgxtzpc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gtfcyjxtby.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbyltdbk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gtipmdakvi.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoqkjjwn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtwjkpskdx.html

[R36] 并发执行多个任务
来源：http://dali.yuxming.cn/Article/details/gtrwbvccdj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtkqnrvnwk.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtxftjtkox.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gtukzkrupw.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gtqlejjcwv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gthljqtjey.html

[R39] 重定向标准输出与错误
来源：http://dali.shangyingyoupin.top/Article/details/gtlyutffwz.html

cmd > out.log 2>&1
来源：http://dali.sysykeji.top/Article/details/gtrwccherz.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtuksixpls.html

echo "log" >> out.log
来源：http://dali.mhx1999.top/Article/details/gtaibostef.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtpthbuzlp.html

cmd >/dev/null 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtnqspjjbt.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtziogwygz.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtqdtpdyan.html

[R43] 按名字查找文件
来源：http://dali.cqqwz.cn/Article/details/gtulrgapqn.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gttjxgyksu.html

[R44] 按修改时间查找
来源：http://dali.cashguo.top/Article/details/gtkvlzxmwm.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gthcuscjxg.html

[R45] 批量删除
来源：http://dali.jqgfzy.top/Article/details/gtqdqaixkh.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gtbqftnnry.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtucfuzyyu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtebzgmnqy.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtfgaqaytw.html


<!-- 参考信息 -->