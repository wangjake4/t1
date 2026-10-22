代发 wailian999

);
来源：http://dali.wangdashe.top/Article/details/gt2okovhylk.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gt2zumobazh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gt2ylnqixsu.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2rposoixk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.meibo888.top/Article/details/gt2bzcplxhb.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwzrfytg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gt2imzesowd.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gt2pmuazlfe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gt2tyourlyp.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gt2lmotaepv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shzxlz.cn/Article/details/gt2zrdcsbuk.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gt2naayeetv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gt2ktggtmhi.html

[Q09] 创建唯一索引
来源：http://dali.fzhhl.top/Article/details/gt2gyekxpzz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2shwplmky.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gt2rtanttkw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gzhubu.top/Article/details/gt2ldwrnsfl.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gt2fggakevw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2onbgprfe.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gt2wgfjdfnq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gt2yakbftvc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hysaishi.cn/Article/details/gt2poreqimm.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gt2seyodicc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gt2jldmcpbm.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gt2dzmyqwod.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gt2rigvxgzt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gt2bqvmugza.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gt2yphcnwqr.html

SELECT * FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2zyupapma.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gt2qccdikww.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2pmmocwdm.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2aoevkokv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gt2rwqtnwot.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvtnnbkr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gt2xbuulwov.html

[Q19] 范围查询
来源：http://dali.zhixingplan.top/Article/details/gt2oygksauf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gt2kakseito.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gt2idbktoek.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2jadvdhpl.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gt2zoumurfr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2gqvdibfh.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gt2mwnljidn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2kofzpngs.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2oevyglzb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2cxblnyes.html

[Q24] 去重
来源：http://dali.ybcxt.top/Article/details/gt2mrbemjva.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2eygyqzse.html

[Q25] 只取前 N 条
来源：http://dali.hfpthk.cn/Article/details/gt2edwdgpoz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gt2mmyejsbe.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gt2tylienxo.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2xixhsosn.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gt2byijwsgl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2norkbhdl.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2cpnamwtd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2cwfikzwx.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjkzpbia.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2vlsszozm.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gt2xkwtnwgl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2gtgvnyzr.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gt2cwpxssrn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gt2naldtrzp.html

[Q32] 分组拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2jecvofbg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2ykkjdznn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gt2cvmkakme.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gt2jpdviorw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gt2aoxbamus.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gt2iqedhvgk.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gt2csqrdlji.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqjmclrh.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2eszepyih.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gt2rorjcnhr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gt2teowjrxe.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gt2oogloilg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2dkubuyji.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gt2nrpzissn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2sbgxymdr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2bltrfiga.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cdnleiting.top/Article/details/gt2zsahwgdi.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gt2zjjmuzau.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gt2dwajsclu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2qgtiyezz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gt2fqftohcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gt2kqcemhwx.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2aimclkba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aibaodan.cn/Article/details/gt2erqtcwbp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gt2xkbblxac.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocvngpya.html

[Q42] 连接条件附加过滤
来源：http://dali.hammf.cn/Article/details/gt2rlgxifpk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gt2nxfdolqx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gt2kedehiaf.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2yseelgqe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gt2iyqhqxjh.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2lomybdbz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gt2mtrlyouf.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcuncmko.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syjjvlcy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwxxsmrv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gt2hfoiufpe.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2hegbfsxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gt2ylbvyeol.html

[Q48] CTE 公用表表达式
来源：http://dali.tanke756.top/Article/details/gt2avdioebj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gt2fhqonbsh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gt2nchxvjek.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gt2dllxkgus.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2mxqgavyj.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gt2lbjghufw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gt2emfzalsu.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gt2bjkfohdf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gt2lauliymr.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gt2lqjviuzh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2nkztzhkm.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxxnsqcn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlxhasvt.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gt2dgevdewe.html

TRUNCATE TABLE logs;
来源：http://dali.cdnleiting.top/Article/details/gt2iflyhsub.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gt2bfcdbpoj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2cixmpclo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2utqmxhrk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2eqbpprrk.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gt2eyoqqpdg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2qdlezmkc.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gt2mzapteti.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2kdceukwo.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2jqmtuutw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2nqhbjsep.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2sbfgksha.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2llxwbdlr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cpebktrr.html

[Q61] 移动平均
来源：http://dali.nwbrower.top/Article/details/gt2zgxjljya.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggsissnk.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2mjpvzfry.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2wvmnuzpu.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gt2misysvdh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gt2sexudwaw.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsbkcpxt.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gt2jtltlubi.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2oorfpcon.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2ksmouaih.html

[Q66] 行锁查询
来源：http://dali.sysykeji.top/Article/details/gt2ryghwewb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gt2glbahomv.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gt2lrhajigv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gt2qbpnncgm.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gt2kinmqfwu.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2jppregir.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gt2yotkozvv.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gt2kdmecudi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gt2jzrlanry.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gt2gijliflg.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gt2ictsbqtx.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcvrkwgc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gt2xhguobpy.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2yvhpknmo.html

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgbpgsfq.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gt2ovruusay.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yangfankeji.com/Article/details/gt2zoyyadml.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gt2idceyfmt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2iiqetxmq.html

[Q75] 日期格式化
来源：http://dali.c1oappe.top/Article/details/gt2rlxshcsv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2tpaqhbxj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gt2amvezdmj.html

[Q76] 按天统计
来源：http://dali.ppjwa.cn/Article/details/gt2wawqddsa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.shangyingyoupin.top/Article/details/gt2fdxgbhkc.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gt2wyrvwngj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zsksopnj.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywsshwdc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gt2lkihfwdz.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gt2olmhsxvn.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangdashe.top/Article/details/gt2qxdhkkzf.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gt2qzdvnbmq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2hyirwjrz.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gt2saktrxqr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2awktgibm.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gt2ymurttve.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2dxntarpz.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2vckohrno.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2pesclnyp.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gt2egiqhddn.html

SELECT TRIM(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2kzvrwmad.html

[Q85] 数值取整
来源：http://dali.xinyue.icu/Article/details/gt2itckjldt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2kbnqtqvq.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppdsnwgu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gt2clxmliqv.html

[Q87] JSON 字段做条件
来源：http://dali.cashguo.top/Article/details/gt2mfmwbgoc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gt2gtspdexj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zdqjudy.top/Article/details/gt2oralibap.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nwbrower.top/Article/details/gt2wfuxdvvy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2wgabecyb.html

[Q89] 判断表是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2cpfymasq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.dashuyun.cn/Article/details/gt2wsognfej.html

[Q90] 生成序号列
来源：http://dali.yangfankeji.com/Article/details/gt2ribehqtn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2guofzrls.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vmgbvsnj.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gt2fqtjdjxn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ywlhfzaq.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2iiwduzkm.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gt2fluymutg.html

set -euo pipefail
来源：http://dali.smart0.xyz/Article/details/gt2kqmzakjq.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gt2kgezyapj.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gt2eqygzoft.html

[R03] 只读变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knfscaqs.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gt2jxqygxym.html

[R04] 位置参数
来源：http://dali.shuidangran.top/Article/details/gt2xnuhitzt.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gt2bhvifphh.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gt2falrzsey.html

name="${1:-default}"
来源：http://dali.chenzaomai.com/Article/details/gt2cmopfkgv.html

[R06] 判断命令是否存在
来源：http://dali.tanke756.top/Article/details/gt2femhndgk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gt2bnkmwxbc.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gt2bwjsohmy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqkckpvg.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2lttxwdss.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2clgxrbtc.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gt2xlbntgca.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.316326.xyz/Article/details/gt2gjhuccec.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gt2cbbxeayq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2xclfjuat.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gt2ypeikbht.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gt2dwarmned.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gt2tpoiyjzg.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gt2tzbsuvdc.html

*)     echo "未知命令" ;;
来源：http://dali.iojbl.cn/Article/details/gt2ecnuvmto.html

esac
来源：http://dali.gzhubu.top/Article/details/gt2tchaonpi.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gt2sgfyozlr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yongpay.top/Article/details/gt2adnrokzm.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gt2qrevqbbh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gt2lowdfzjy.html

[R14] C 风格 for
来源：http://dali.andypj.xyz/Article/details/gt2jcmhryqj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gt2soqmhuwk.html

[R15] while 逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2gwyxhmda.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gt2imrtrwhp.html

[R16] until 等待条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpozcouk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gt2dukjedvi.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2nztkgemg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jianghu66.top/Article/details/gt2wnhrtyfx.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gt2zvzqmtna.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2ynuqsapy.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gt2rxqfxfbr.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rwzfktfy.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gt2gksljhko.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjbyqukq.html

[R21] 字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2zyfmuhkw.html

echo "${#s}"
来源：http://dali.birdmap.top/Article/details/gt2ioxteryh.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gt2claclycc.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhxigcak.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gt2kzvpjlrm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.fengsongda.top/Article/details/gt2rceozedq.html

[R24] 大小写转换
来源：http://dali.yj20258888.top/Article/details/gt2pqkpepaf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gt2ybnmpual.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gt2ncxbdnlb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuanzhike.top/Article/details/gt2bazrmrxa.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gt2edyhtvaa.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gt2dsvmnazq.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2hbqujnww.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgszhptm.html

[R28] 浮点运算
来源：http://dali.jinqigufen.top/Article/details/gt2gbptogkr.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gt2pnvbjjod.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjdxxedk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gt2jftlvftm.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gt2ajsdxstz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gt2ppxgyhgq.html

[R31] 局部变量
来源：http://dali.sxryk.cn/Article/details/gt2ryewpocc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfgpttji.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gt2kcyyzsex.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.sweek.top/Article/details/gt2clptaxfj.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gt2rooxhzdc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gt2yixrpxgs.html

[R34] 退出时清理
来源：http://dali.hfpthk.cn/Article/details/gt2iytyavcy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gt2vloirqih.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nebfyuyx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gt2mzzhlspo.html

[R36] 并发执行多个任务
来源：http://dali.sweek.top/Article/details/gt2hgttofrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenjidiqi.icu/Article/details/gt2rvvxpabu.html

[R37] 把输出赋给变量
来源：http://dali.iojbl.cn/Article/details/gt2nmerwjhg.html

files=$(ls -1)
来源：http://dali.nanxinkj.top/Article/details/gt2iedqpcup.html

[R38] 管道串联
来源：http://dali.yj202588.top/Article/details/gt2zckygvuf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2tshuavzt.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gt2iekuchlt.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gt2cznqhwtf.html

[R40] 追加写日志
来源：http://dali.pycfn.com/Article/details/gt2wwibhhla.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gt2wxxtbojn.html

[R41] 丢弃输出
来源：http://dali.9152youxi.cn/Article/details/gt2vhfzjylj.html

cmd >/dev/null 2>&1
来源：http://dali.jiagoushi.top/Article/details/gt2kixhjene.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vgktjodo.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2tlbguosb.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gt2dzqytugf.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gt2yiuehrpz.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2pfeppptv.html

find . -mtime -7 -type f
来源：http://dali.dashuyun.cn/Article/details/gt2negkaurl.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2yhwvmyva.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gt2bgqlkovl.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gt2aqtnznzg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gt2svjisujm.html

[R47] sed 单行替换
来源：http://dali.yvedp.cn/Article/details/gt2ksnxcshj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cucudq.cn/Article/details/gt2mkdlpism.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gt2otldymkm.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2llebxjrh.html

[R49] awk 带条件
来源：http://dali.quarkkingdee.top/Article/details/gt2klssigze.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jiagoushi.top/Article/details/gt2lzndugga.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gt2azvknijq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrfvuuvl.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gt2cghdcxaw.html


<!-- 参考信息 -->