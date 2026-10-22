代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gt2oaaieaek.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gt2irvskzji.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gt2akrttgyx.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2vnezteih.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cdnleiting.top/Article/details/gt2aolznzzi.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gt2lomsgalo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gt2ujsdujal.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjuvrklc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2cfjnmoeg.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2hwcmihwd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gt2ocwrmyvs.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awfoclio.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2lmmskqol.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gt2hyirgupy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2pphhtpkp.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2ibkjtchs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gt2qjztcxhv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2ebuixuek.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gt2rtndbxxq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2otkfexdh.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gt2vfmnjzuf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gt2aedmfhfy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fqnlmhqu.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gt2gcxglotc.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2gyrbrxsz.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gt2oicfjtpr.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2fhlrnvbw.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imwklffn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2vlmqqgms.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gt2qlsytmzw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gt2xhltazsu.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gt2oticwjvt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gt2qetumqdn.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2ralaigpf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gt2vdjbjssu.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gt2srrgpfli.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gt2bjvnzmyo.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gt2lxywljhg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgufenzy.top/Article/details/gt2fyrkhswf.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gt2ynfrzgjd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gt2onlnjmkz.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vvrrmuuq.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2emuihmxj.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gt2fegxhwzz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2smjncqez.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gt2njiqfcgf.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2yieybkmn.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2knbfzppm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2brsezgbs.html

[Q28] 求和与平均
来源：http://dali.cucudq.cn/Article/details/gt2gtqglsjq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2qgebqttl.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gt2rizqedqk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fxrlvuxj.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gt2ejmicaht.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2gdzmtfkn.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gt2knzkaxpg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qxrqwrsx.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2wlhtxdur.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gt2awtludwa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gt2paoytrcc.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gt2eeirpnzs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2jzlxcjej.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2wgltkugb.html

SELECT * FROM (
来源：http://dali.fzhhl.top/Article/details/gt2jdnsrbmp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zdqjudy.top/Article/details/gt2jymcwoqu.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiahofqg.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gt2ddqjghdc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2arerekwk.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuzrhikj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gt2llkumncv.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gt2pscjthvl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2cvydlsng.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gt2xbcqtkgg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gt2dgprwkwy.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gt2jgjxxvot.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2dfeujjsq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gt2ucrohlwu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gt2iauwxsjd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gt2izfhjvmb.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gt2dqhorjxw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gt2dcvhiicg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gt2fhduinco.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gt2vyzqeqei.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2xfxfvghq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gt2wsftzgxn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gt2gqicfcmb.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gt2pbxnuwek.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.haohaochexian.top/Article/details/gt2yajqemsd.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gt2escremuo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gt2hfivuwkz.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gt2sqxppllx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gt2pggymxnl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2wlczvfnx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gt2cilrnfah.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2eekumrak.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gt2zilnaibb.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gt2foypyftc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gt2ldalqand.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2dtycwppp.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2usdwdbdi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lsemlakc.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxqnzpjo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2bpkdibye.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gt2tsnuzoyq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xehqcbgm.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gt2midfxqmo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gt2ofgwwmrx.html

[Q53] 按条件删除
来源：http://dali.quarkkingdee.top/Article/details/gt2qaqytifa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gt2pkuiennq.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gt2hjovybww.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2zwaybxpr.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gt2zvvjzixs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2xqsjlwdl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gt2whfzmagw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdgrxmez.html

[Q57] 行号
来源：http://dali.yueranfly.top/Article/details/gt2wovrwwtp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gt2shmkysbe.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gt2lgcuwslb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2irnykobv.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fxqgrpse.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2weomhrlv.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gt2bsonkccb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gt2mzymtdua.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dgcsuelf.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gt2bmolgtdz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2bwnyepsa.html

[Q62] 分组占比
来源：http://dali.tanke756.top/Article/details/gt2qmkyzwgo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gt2lxdicwhe.html

[Q63] 开启事务
来源：http://dali.dashuyun.cn/Article/details/gt2zpqfcgzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gt2bltepgzp.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gt2liqjnstw.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gt2sghawkwn.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2hhrpgfoh.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaqnyfjy.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2ftxptzru.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gt2uknphjxs.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gt2xqbnlhza.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gt2upwadtpm.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gt2ivhivdbz.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2umxlpkky.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gt2zwqvbfvx.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gt2fzjnxzbt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gt2vxuuejzs.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2wkthhdhy.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gt2qsxhvooc.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vphdjvbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.meibo888.top/Article/details/gt2sgbjeyzk.html

[Q72] 查看索引
来源：http://dali.jyoumei.cn/Article/details/gt2bnhektxm.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2rpgqsujh.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gt2qczprzdj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gt2dxcilrxm.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gt2qnaqbnag.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gt2rrfeeris.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2ubehriwd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2oskbdidu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nbwopzia.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gt2pobfvgbf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gt2vctzwvbg.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qypwydak.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.iojbl.cn/Article/details/gt2psnvpgzt.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gt2phbjyndp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tianlin.xyz/Article/details/gt2jietieel.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2iwpsiolw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gt2olnhkchq.html

[Q80] 字符串截取
来源：http://dali.nanxuanxn.top/Article/details/gt2flgoiwmw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uswlpqko.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2fcoeamgn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2fftvfash.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gt2nmqiogic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ycgbfuxf.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwgkfvyh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2asjrjiiv.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gt2jywxxrua.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2knuhmjsf.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gt2lgrzpthh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jqgfzy.top/Article/details/gt2ghetpkbe.html

[Q86] 读取 JSON 字段
来源：http://dali.ivvv.top/Article/details/gt2pnnnsrxq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gt2bnishkvy.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2qkfnzufo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.vqdsnc.cn/Article/details/gt2vpyejcjy.html

[Q88] 行转列（条件聚合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzaclicp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zycfv.cn/Article/details/gt2enyyvoqh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvefrlbc.html

[Q89] 判断表是否存在
来源：http://dali.hnxiangtu.top/Article/details/gt2rdkdnfbr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2xbjtpqlj.html

[Q90] 生成序号列
来源：http://dali.wangshuangyany.cn/Article/details/gt2kxpduqyu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yangfankeji.com/Article/details/gt2zickuxnp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2dkjglekk.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gt2anmtavjv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2huwrpfea.html

[R01] shebang 与严格模式
来源：http://dali.jlsjyb.cn/Article/details/gt2dbrvzcph.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gt2misdpiks.html

set -euo pipefail
来源：http://dali.vqdsnc.cn/Article/details/gt2wqaeqazj.html

[R02] 变量赋值与使用
来源：http://dali.cucudq.cn/Article/details/gt2opfmpqhh.html

name="Tom"; echo "$name"
来源：http://dali.guowangkeji.top/Article/details/gt2pulxgjqc.html

[R03] 只读变量
来源：http://dali.hnxiangtu.top/Article/details/gt2sbjqkmmv.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2wgvrvzuz.html

[R04] 位置参数
来源：http://dali.quarkkingdee.top/Article/details/gt2tlfsbnat.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gt2thmovnom.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlpqzaol.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gt2ybkkwetv.html

[R06] 判断命令是否存在
来源：http://dali.andypj.xyz/Article/details/gt2oyaxyfib.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gt2rkcnprzv.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gt2gjhbbxoc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gt2yeupsdlz.html

[R08] 数值比较
来源：http://dali.quarkkingdee.top/Article/details/gt2vauobmxu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2gjpblfpb.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gt2uuglfpdw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkxgpzob.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gt2muktonpp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gt2ryqerjca.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2pcadpfgs.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gt2jqsbutne.html

start) echo "启动" ;;
来源：http://dali.yj202588.top/Article/details/gt2rwurqrmy.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gt2nomyirku.html

*)     echo "未知命令" ;;
来源：http://dali.yj20258888.top/Article/details/gt2kbusingp.html

esac
来源：http://dali.yanxiufei.cn/Article/details/gt2kkvhljcu.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gt2lurvyija.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gt2abbnjiwv.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gt2usogucko.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgfzy.top/Article/details/gt2thjomxoe.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gt2darktzsk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tptipleh.html

[R15] while 逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2irczdcdp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2uwqldtxs.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2juwayqkb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gt2pzchmlit.html

[R17] 数组定义与取值
来源：http://dali.tanke756.top/Article/details/gt2wnqlpeol.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ppjwa.cn/Article/details/gt2zzuvumnx.html

[R18] 遍历数组
来源：http://dali.birdmap.top/Article/details/gt2paqyhyrd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gt2kgdaothh.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2dzkmiozx.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gt2xozofpxn.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obqxoamu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gt2ufltmgkm.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2wysmwrmk.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gt2fmluinhp.html

[R22] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gt2dylvvbpa.html

echo "${s:0:5}"
来源：http://dali.zhongyouzk.top/Article/details/gt2cnlmwovj.html

[R23] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gt2xasypfgq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.iojbl.cn/Article/details/gt2sgswnaem.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gt2etcgtemy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gt2kopkqwpb.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gt2asdxzajm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ancqgnml.html

[R26] 命令替换
来源：http://dali.cucudq.cn/Article/details/gt2xamwxlvz.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gt2eqvlleae.html

[R27] 算术展开
来源：http://dali.xylfe.cn/Article/details/gt2leovztwm.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gt2xrfytkqc.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uudiemvw.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gt2hpxjcbhp.html

[R29] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2xookmskg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gt2rvzhjtxv.html

[R30] 函数返回状态码
来源：http://dali.zhengqikj.top/Article/details/gt2qdyapfmb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenlongwang.top/Article/details/gt2cpjkvmot.html

[R31] 局部变量
来源：http://dali.iojbl.cn/Article/details/gt2rztiombc.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ceelmdlc.html

[R32] 参数个数校验
来源：http://dali.cdnleiting.top/Article/details/gt2glymtwqi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gt2aefarbqz.html

[R33] 捕获错误并提示行号
来源：http://dali.zdqjudy.top/Article/details/gt2jfkscjkz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrreoqbe.html

[R34] 退出时清理
来源：http://dali.nanxinkj.top/Article/details/gt2fsafgums.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gt2ayrhzohm.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gt2xyntxwpr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2zdjwdyuh.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gt2tzqzvybm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cashguo.top/Article/details/gt2ncamcupb.html

[R37] 把输出赋给变量
来源：http://dali.sweek.top/Article/details/gt2ptzmxblo.html

files=$(ls -1)
来源：http://dali.havefunace.top/Article/details/gt2dvtuvsiq.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gt2zqctlekk.html

cat a.txt | grep -i error | wc -l
来源：http://dali.andypj.xyz/Article/details/gt2mypoxdyk.html

[R39] 重定向标准输出与错误
来源：http://dali.mhx1999.top/Article/details/gt2eavavkkb.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gt2apekvpdr.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gt2iieyqwpu.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gt2gjgogosy.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gt2xfbhogzt.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2dyjoitia.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2wksmoklr.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gt2jvjnezdr.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2dbktgzee.html

find . -name "*.log" -type f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqbfdayo.html

[R44] 按修改时间查找
来源：http://dali.xylfe.cn/Article/details/gt2rfavwfba.html

find . -mtime -7 -type f
来源：http://dali.tianlin.xyz/Article/details/gt2zpjwiona.html

[R45] 批量删除
来源：http://dali.zhixingplan.top/Article/details/gt2aijfgpxn.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnehhuzz.html

[R46] 递归替换文件内容
来源：http://dali.chenlongwang.top/Article/details/gt2uaqzhsim.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxuanxn.top/Article/details/gt2jphzusiy.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gt2vvkpzcen.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2pprgiowg.html

[R48] awk 取指定列
来源：http://dali.sufxvd.cn/Article/details/gt2exwjwbob.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gt2xpphkkdr.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2toalepgn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gt2kvdncohd.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gt2wbylhxdn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2pyvirijr.html

[R51] 排序去重取前几
来源：http://dali.shuidangran.top/Article/details/gt2hzqfhjlw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.bjfxy.top/Article/details/gt2ovikidkd.html

[R52] 统计行数
来源：http://dali.sufxvd.cn/Article/details/gt2guwizzeh.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gt2jnlsyxvl.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigufen.top/Article/details/gt2ayxfyoqn.html


<!-- 参考信息 -->