代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gttdgsdawi.html

user_id INT NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtpznweycb.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfqtmdvy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtwoybfdtm.html

);
来源：http://dali.xuanzx.com/Article/details/gtipujehei.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtyofttviq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtsblndtam.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtjuuhyhxg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtdoikoerf.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtjwqmudjf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.meibo888.top/Article/details/gtfipgdswj.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtpeftpqdh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.birdmap.top/Article/details/gtkctufkkz.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtafxoklot.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtxcfceout.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtpleqprvo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gteojfutlx.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtvnpsiwxc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtvjzzgtxe.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtvmfsjtnk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtsfgpbbqm.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtjxtnlgxr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtkepyqcyx.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtqeohsogq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtbaekxdzg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gtdeymvokj.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkqqzaiy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtnclpavpi.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtytvanaso.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtyyexecls.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtnbiloiiw.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtafakaofj.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtyroscnmn.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtlcjvvjtz.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtvrysvsze.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtegdqstre.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gtxouychmd.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtftywvzpv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtndudgzxj.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtanqmovsh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtgsfvlhou.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtaqwbslwm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtjyktokfs.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gthuucfxrf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtxbpvxdah.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofotefaf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gtungorexr.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsedsltar.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtduejcani.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnahiucl.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcytllhji.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtgooqgiyk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtvdyttten.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gttwollyzl.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtwxrkuamg.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtqoqinrfw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtllrytipc.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtwfkvmchs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtmkckzqic.html

[Q29] 最大最小值
来源：http://dali.jlsjyb.cn/Article/details/gtjdxkdzbb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtiyggtsuz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtbreqixha.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtmxnjvodb.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoslzctoj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtaiceijae.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gtxvemciii.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtsucahzka.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtxleyvson.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtytsywjmg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gtrhwxtmhu.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gtyhozkhxn.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gtgwwqeicf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shangyingyoupin.top/Article/details/gtkiidvtts.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtvdiqgqrm.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtsnycjnnb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtlwtogqln.html

[Q36] 左连接
来源：http://dali.chenjidiqi.icu/Article/details/gtbracoxiv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtzufpuhsp.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtnecxlgmt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtsuuyohvc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gtdmroxzml.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtwgnkgwhw.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtudxyabqk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuanzx.com/Article/details/gtukzdbcgw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtwxqfwzya.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtzrwuvvxu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtdgogkgov.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtlfpokunn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtrrcisfwa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gtlrhvbzqf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gthkuttykg.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gtjaiqkyda.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtthnkbvik.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gticlpulbc.html

[Q43] 标量子查询
来源：http://dali.zhoulong.xyz/Article/details/gtagkrzhqi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtlqnyqrbc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gthwhkddmg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtrismlmta.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtpgfxwcxu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtbmcplzav.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtfnzwhtmv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtvsxduphw.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtaenucizk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daxiang520.top/Article/details/gtcegvhmal.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gtttvytndo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gthepontuu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtlvdubreh.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtmruwelgl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtyoyppbsy.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtoqhczyrw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtwwlbvsqm.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtdpurprby.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtodtrigpl.html

[Q52] 删除指定行
来源：http://dali.hywenlv.cn/Article/details/gttwvjzmmm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtgkxwwvri.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtdwpfwoam.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtiksumown.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtlyluxlkf.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtujzhhaag.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gtaljjpdtf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtutzjhixq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sxryk.cn/Article/details/gtcpqnniil.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtrkmtfgip.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtwzkhohjb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtrvqkrqtn.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtsbdojukn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtpnkwcqzf.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtpqmcxsbl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtwrmwvqup.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangshuangyany.cn/Article/details/gtrtohstlt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gtchrsacwk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtejjozgmq.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtqwrrgisr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtumvrynjd.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtipdmnibv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtenjtneqi.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtawpnanpn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtlmxtxugr.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gtuqojgwbl.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtqhjvuico.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtmylzvkzh.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gttsnpufli.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gtrjoqkulz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtvltrolyh.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtgaphhbyo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gtmaiomqhq.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gtkgxwdnfb.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gttgjxpwne.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtjykpacqo.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtjyvymxzh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gtgikmcoie.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gtaieodwuf.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gtzzweydvm.html

[Q71] 查看建表语句
来源：http://dali.0kj1m.cn/Article/details/gtgzapyzno.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtdzvdrnus.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtfcrnwgsu.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtezsgftsl.html

[Q73] 查看表状态
来源：http://dali.gogol.net.cn/Article/details/gtsbtizydk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gteuvvhiot.html

[Q74] 强制使用索引
来源：http://dali.zhixingplan.top/Article/details/gtxudlvbst.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pengpengdd.cyou/Article/details/gtzwrwyoof.html

[Q75] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtpyoiwheu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtqvhghgnd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hysaishi.cn/Article/details/gtctibibpg.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtympzecga.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtxhvhansp.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtmjttydmo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtilgwmoug.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtkfsapaxq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.haohaochexian.top/Article/details/gtwzogjhhi.html

[Q79] 字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtpoynrvlj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxinkj.top/Article/details/gtzpbindca.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtvkabrqbe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yvedp.cn/Article/details/gttxjtmtvj.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtsdbfxnya.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yueranfly.top/Article/details/gtvsylmiuq.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gtyoaglngm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtsjkrvcnh.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtkygirlpj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtwruelpbz.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gthrnnprap.html

SELECT TRIM(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtsvaahztj.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtlwxdiidq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtrbyxdjrp.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtlfmzbbmd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtypurowkb.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gtgfqcoroj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jqgfzy.top/Article/details/gtqwgkmfej.html

[Q88] 行转列（条件聚合）
来源：http://dali.gogol.net.cn/Article/details/gtkjrhafwn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtnmnbtoyu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtezfyduqh.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtvpiktgkd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.redwolf501.top/Article/details/gtljipgjvw.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoikvyffa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtnveerdrt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuzwfghmp.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtoqnljurd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtpqeafjdh.html

[R01] shebang 与严格模式
来源：http://dali.jinqigufen.top/Article/details/gtfueapqly.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gtuwaoqjbo.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gtsgalmpxv.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtgcsgfyxt.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtbbczxnhp.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtektkwwkm.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmedculkc.html

[R04] 位置参数
来源：http://dali.tanke756.top/Article/details/gtjbdftihl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.feifeiyinyue.top/Article/details/gthtzqznks.html

[R05] 参数默认值
来源：http://dali.yueranfly.top/Article/details/gtyxuzxobv.html

name="${1:-default}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwjkltet.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gtblgvxllx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtsoykijlm.html

[R07] if 判断文件
来源：http://dali.haohaochexian.top/Article/details/gtzpbesyhv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gtblalunrk.html

[R08] 数值比较
来源：http://dali.cashguo.top/Article/details/gtudqqehxx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.fengsongda.top/Article/details/gtsvegroln.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtvqzwglvf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gtqcbqvzqa.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslgkkruw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gttpglupxk.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtalfwazor.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtukmvomyh.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtyqjfostx.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflfdnsip.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gtdnrcdvza.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtavghdkdr.html

[R12] for 遍历文件
来源：http://dali.hnxiangtu.top/Article/details/gtlfcjfrlr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtbfbsyxdy.html

[R13] for 计数循环
来源：http://dali.yj202588.top/Article/details/gtaclcdwml.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gtpltpnhyr.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gtbgzpmucp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtzkkzjpwy.html

[R15] while 逐行读文件
来源：http://dali.tanke756.top/Article/details/gtglllyxyp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.bjfxy.top/Article/details/gtahtejiqp.html

[R16] until 等待条件
来源：http://dali.xylfe.cn/Article/details/gtkhxjjxtn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gtrykkcwyy.html

[R17] 数组定义与取值
来源：http://dali.xuanzx.com/Article/details/gtqqnqxybx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtzbwkcawm.html

[R18] 遍历数组
来源：http://dali.shzxlz.cn/Article/details/gtmpdzuvsu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gttogcunis.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtflaaoqab.html

echo "${#arr[@]}"
来源：http://dali.yj20258.top/Article/details/gtfdygmwpv.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gtsesgnyxw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtsljaesyo.html

[R21] 字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gttztvfcli.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gtmllqjzrw.html

[R22] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtfwfumpnl.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtsacjzahe.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxbvgvaz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.andypj.xyz/Article/details/gtqjffmzui.html

[R24] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtaypgulrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gtmuunkozh.html

[R25] 去后缀 / 去前缀
来源：http://dali.sweek.top/Article/details/gtnczkalkb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gtrprxkpci.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtjahjcxtd.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtswipczds.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtatsqsmor.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwoxvnwo.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtuaplqbne.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtzqxhvjwe.html

[R29] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtriqpmqet.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yangfankeji.com/Article/details/gtekulzzxt.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtsqiynhyn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtqtbpspsp.html

[R31] 局部变量
来源：http://dali.guannengcc.top/Article/details/gtayeqehtq.html

f() { local x=1; echo "$x"; }
来源：http://dali.cheryme.top/Article/details/gtfevaefaq.html

[R32] 参数个数校验
来源：http://dali.yj202588.top/Article/details/gtaabjsksy.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtadndyczj.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtqmnvupuf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.havefunace.top/Article/details/gtsbnfwarf.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtlyhqjgvy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtijvoelwo.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjxgsnhe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlagbonsd.html

[R36] 并发执行多个任务
来源：http://dali.xziqi.cn/Article/details/gtfsdsbluv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.quarkkingdee.top/Article/details/gtbvpkojzg.html

[R37] 把输出赋给变量
来源：http://dali.yuanzhike.top/Article/details/gtnhipgnux.html

files=$(ls -1)
来源：http://dali.yongpay.top/Article/details/gtvrmpemqa.html

[R38] 管道串联
来源：http://dali.tanke756.top/Article/details/gtojzlbfgj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhongyouzk.top/Article/details/gtrjqtxlql.html

[R39] 重定向标准输出与错误
来源：http://dali.cdnleiting.top/Article/details/gtvmtbnqre.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtjfflmbms.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtrzvyekgr.html

echo "log" >> out.log
来源：http://dali.xylfe.cn/Article/details/gtsvdnhnug.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gtxaolpwhf.html

cmd >/dev/null 2>&1
来源：http://dali.gzhubu.top/Article/details/gtvjabfiwj.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtbomsngsy.html

wc -l < a.txt
来源：http://dali.zhixingplan.top/Article/details/gtumfnulfi.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtvqtwtsbd.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtqtfndjgg.html

[R44] 按修改时间查找
来源：http://dali.hongshengwenyu.top/Article/details/gtknlfojmq.html

find . -mtime -7 -type f
来源：http://dali.guannengcc.top/Article/details/gtpwnsetak.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gtszofpolq.html

find . -name "*.tmp" -delete
来源：http://dali.chenzaomai.com/Article/details/gtcumcfyhw.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gthieqqzpl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtfenuhxba.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtjzphaouf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.meibo888.top/Article/details/gtupqowgmp.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtinoagfep.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtgohrbqkn.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtqifmsxdz.html


<!-- 参考信息 -->