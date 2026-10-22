代发 wailian999

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2mufmumac.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gt2fbyjdgze.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gt2klwnlurc.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gt2ghpxyyzi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gt2clcuhmhf.html

[Q07] 删除表
来源：http://dali.jlsjyb.cn/Article/details/gt2vqstjfnx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gt2kjdacmbf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtscbdr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2rngxbpmj.html

[Q09] 创建唯一索引
来源：http://dali.nanxinkj.top/Article/details/gt2jfqbbyzj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2vdcnzkgz.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2vdsvmvmb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gt2sdgkckpf.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2sukiugkz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2buztefil.html

[Q12] 插入后取自增 ID
来源：http://dali.yonumen.top/Article/details/gt2fbovuzgr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gt2exiqtvwb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsyotuqn.html

[Q13] 忽略重复插入
来源：http://dali.yanxiufei.cn/Article/details/gt2jwmwxmzd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhengqikj.top/Article/details/gt2ilxqvpcl.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gt2lsjeullr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gt2epqpjkjo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoinnjkh.html

[Q15] 查询全部
来源：http://dali.pycfn.com/Article/details/gt2zkgjbhja.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2wnobbocz.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gt2lwpjqdqg.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2owsfskec.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gt2rwqtfivj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hednfdwr.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gt2samryvid.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2asglgqmy.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gt2ebavczno.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.birdmap.top/Article/details/gt2bkutinqv.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2pcskerro.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gt2bcvwdrwz.html

[Q21] 空值判断
来源：http://dali.cdnleiting.top/Article/details/gt2mqafhfxv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2gzvnagci.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gt2lrrsgbco.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gt2ausgnlts.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2fbadojro.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gt2qccqcqgf.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbnhecyx.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2twowkouj.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2looimrze.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gt2mmbbjplq.html

[Q26] 计数
来源：http://dali.jianghu66.top/Article/details/gt2ovhrdnlx.html

SELECT COUNT(*) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2vyzhbkoz.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubkvdefi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2ozidjzem.html

[Q28] 求和与平均
来源：http://dali.tian-w.cn/Article/details/gt2qnxdpimt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2cquefpnz.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2aulxcdwh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2zjqhundq.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gt2ubkkjtgy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2axxphxkj.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2oowvpjem.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2hamcklff.html

[Q32] 分组拼接字符串
来源：http://dali.c1oappe.top/Article/details/gt2ksjutpsz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2iljjibwb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gt2tyzsgfab.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gt2lnxngjbe.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gt2llftxmfl.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gt2iyczzqkd.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gt2uxmroxgj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gt2dijcgozb.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gt2nimwehpq.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2gwhdxgpp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2djirejrj.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2fmvawqfp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzqunpdr.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gt2mwxydgbw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fzhhl.top/Article/details/gt2vdygdckp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xinyue.icu/Article/details/gt2hsgdzhnv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2xaszcpiz.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2ahnqfeje.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gt2sutocklf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gt2ygaggkey.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2mruvtcoe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gt2jubovwaq.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gt2kskwqggd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gt2qvfrqqmk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gt2judajpzb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gt2cbcxjjgi.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2cukbuefn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gt2usdlniji.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gt2idnzeobo.html

[Q43] 标量子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rzokwpad.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gt2utmltpac.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gt2kfgebjzm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvgdgouu.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gt2vtyinajd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2inzfqtbw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gt2qwsyeuvr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2tpvqetiy.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gt2hazbpevu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gt2avnyjzcp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfunuhg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2hbaupxxx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gt2gsstupbv.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gt2kvbuxzqq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gt2lhxgsgbv.html

[Q50] 批量更新
来源：http://dali.chenzaomai.com/Article/details/gt2glyhceqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2liovaetf.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2wavbzzuu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2wvcekzvd.html

[Q52] 删除指定行
来源：http://dali.xylfe.cn/Article/details/gt2zauakpot.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gt2eavnkknc.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gt2qtgugops.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2dlfobabr.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gt2bghhywkf.html

TRUNCATE TABLE logs;
来源：http://dali.sysykeji.top/Article/details/gt2rccpnjet.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2lvvbnsws.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2jekkuqmx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gt2mhilzlfz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gt2qmggfegl.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2stztidfs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2jtsfgwml.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gt2tbtxqzgo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2liakeijw.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gt2dspfslfc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2ecyipuih.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gt2msbmejec.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sxryk.cn/Article/details/gt2feqjztyb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2ckefsmbc.html

[Q61] 移动平均
来源：http://dali.tanke756.top/Article/details/gt2aryzwxsq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrcbjhvu.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gt2zbtyfosh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2cjjapgyu.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2ajccbuvu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gt2ejddaraq.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gt2qaxgcvkk.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gt2ibyxdhyi.html

[Q65] 回滚事务
来源：http://dali.xuanzx.com/Article/details/gt2bzyucxjo.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gt2dboiohtf.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gt2ulmtvzha.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2zgujmhxo.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gt2dpkqjqiv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gt2dvqpudky.html

[Q68] 保存点
来源：http://dali.hfpthk.cn/Article/details/gt2vtkgjbcn.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvmvmmfk.html

ROLLBACK TO sp1;
来源：http://dali.jlsjyb.cn/Article/details/gt2yiskdhfh.html

[Q69] 查看执行计划
来源：http://dali.zdqjudy.top/Article/details/gt2ajcpjkfy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gt2kxziqkop.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gt2qfrxyqyf.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gt2icfevpux.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gt2vttbmbua.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuanzx.com/Article/details/gt2ehxcakhv.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2yhwviozm.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2vjzsbpml.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2cboegclv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.9152youxi.cn/Article/details/gt2zfoapaff.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gt2otodevpw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnqzz.top/Article/details/gt2bjppgiqt.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2nhaiadou.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gt2zbfnrpqy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gt2hetyfckm.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gt2exwgicga.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gt2djqujswa.html

[Q77] 时间加减
来源：http://dali.zhoulong.xyz/Article/details/gt2wsgnkswp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gt2xrrzfelj.html

[Q78] 当前时间
来源：http://dali.gzhubu.top/Article/details/gt2csbnaasc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nanxinkj.top/Article/details/gt2coxcvzwv.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gt2btaidfwz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gt2fdpwpxuo.html

[Q80] 字符串截取
来源：http://dali.ydzc1.top/Article/details/gt2fccnlkdq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mbwvjwmr.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gt2lctfjcvx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2stolobnp.html

[Q82] 字符长度与字节长度
来源：http://dali.yj202588.top/Article/details/gt2tyrdtvza.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2divvudsu.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyojnzis.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2fwjvbixy.html

[Q84] 去除首尾空格
来源：http://dali.dianchejie.cn/Article/details/gt2sfesrvjv.html

SELECT TRIM(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gt2rgjnaabn.html

[Q85] 数值取整
来源：http://dali.c1oappe.top/Article/details/gt2slsewmst.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gt2xqmppihp.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gt2ifbpjjav.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.birdmap.top/Article/details/gt2edmameqq.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhadfavu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gt2pqsfqniq.html

[Q88] 行转列（条件聚合）
来源：http://dali.cqqwz.cn/Article/details/gt2ctrotjpi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.wangdashe.top/Article/details/gt2lpumbtur.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2mipfjzpw.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gt2zjsdzlfi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2bqrfqkys.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2pxxzjajn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gt2qwnznkkq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2lknwvuek.html

R. Bash 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adwxzvqi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2cbbrwdpp.html

[R01] shebang 与严格模式
来源：http://dali.yuanzhike.top/Article/details/gt2biiapcma.html

#!/usr/bin/env bash
来源：http://dali.yuanzhike.top/Article/details/gt2raddcykz.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gt2uyzqnmbu.html

[R02] 变量赋值与使用
来源：http://dali.ydzc1.top/Article/details/gt2wwaryxxo.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gt2doxxiaau.html

[R03] 只读变量
来源：http://dali.aizwys.cn/Article/details/gt2edsdeavr.html

readonly PI=3.14
来源：http://dali.hnqzz.top/Article/details/gt2uogqomur.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gt2iftuaxin.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gt2zttpmjvg.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhhxduyf.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzvttqzg.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2dfrtkisv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gt2mgkzyctx.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2uwtlloxl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258888.top/Article/details/gt2pxzvaawz.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2wczppain.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gt2tewallnl.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndfngeui.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gt2eivuaxiu.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gt2yldlcljj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gt2thuxgozs.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2mbsjivob.html

case "$1" in
来源：http://dali.hysaishi.cn/Article/details/gt2bfhdhxql.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gt2pvkbfevs.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gt2jerhqwzc.html

*)     echo "未知命令" ;;
来源：http://dali.svipenyu.cn/Article/details/gt2ybjunjtu.html

esac
来源：http://dali.tanke756.top/Article/details/gt2cnzdguns.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gt2inpsdswc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gt2vyconmgt.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2vbwrjzgx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gt2zjziupxu.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnrtgror.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.aibaodan.cn/Article/details/gt2fiukrzvw.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2pbhyonjz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gt2uagtiegi.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gt2aocfwnwt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cheryme.top/Article/details/gt2tmueyhty.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gt2mvnzmmux.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gt2gycgnzrt.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gt2kpzzvmxy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gt2eydkmcgu.html

[R19] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2cignmqun.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gt2babyiate.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gt2pwhxrnyb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxrdicjk.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gt2dzystnji.html

echo "${#s}"
来源：http://dali.sysykeji.top/Article/details/gt2mlxcsers.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmdmfxfl.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gt2lpabacjp.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gt2ajfahogq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gt2lahiodxn.html

[R24] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gt2cofhlimu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuxming.cn/Article/details/gt2yqkpskce.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znswxgjk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gt2byloyivm.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gt2fururlgt.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gt2gpoqyeez.html

[R27] 算术展开
来源：http://dali.gzhubu.top/Article/details/gt2lpcmypsq.html

echo $((1 + 2 * 3))
来源：http://dali.snrcjt.cn/Article/details/gt2amlcrvln.html

[R28] 浮点运算
来源：http://dali.fengsongda.top/Article/details/gt2njudturj.html

echo "scale=2; 10/3" | bc
来源：http://dali.tian-w.cn/Article/details/gt2sbzvhtnp.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gt2ysditsyz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.nanxinkj.top/Article/details/gt2awxtrajo.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2juxibxyl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2ciybarht.html

[R31] 局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2srldxwuf.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rqmbimvb.html

[R32] 参数个数校验
来源：http://dali.redwolf501.top/Article/details/gt2hsqekfpg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guowangkeji.top/Article/details/gt2fhishdjr.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gt2mkwrjfct.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2yzegmbre.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gt2lfcpzqbu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gt2prmqozgc.html

[R35] 后台执行并等待
来源：http://dali.andypj.xyz/Article/details/gt2awkmsibf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2cbnkrlhe.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gt2bcnouudm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.mhx1999.top/Article/details/gt2mwspmkjr.html

[R37] 把输出赋给变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksxzbmal.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sgfwvgjy.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gt2iaarwulb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258.top/Article/details/gt2mbkdlpll.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigfzy.top/Article/details/gt2zrfvumkg.html

cmd > out.log 2>&1
来源：http://dali.nanxinkj.top/Article/details/gt2pqbvtvhk.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2qokmnctp.html

echo "log" >> out.log
来源：http://dali.birdmap.top/Article/details/gt2qiplgrjw.html

[R41] 丢弃输出
来源：http://dali.hnqzz.top/Article/details/gt2axyohflj.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2pretwgup.html

[R42] 输入重定向
来源：http://dali.sysykeji.top/Article/details/gt2xrpxqawr.html

wc -l < a.txt
来源：http://dali.jlsjyb.cn/Article/details/gt2cstneryr.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gt2uhqcmkbc.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gt2mzqakoor.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gt2nnakykdp.html

find . -mtime -7 -type f
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmldbual.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gt2wfgjolfc.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gt2mrhlengo.html

[R46] 递归替换文件内容
来源：http://dali.jinqigufen.top/Article/details/gt2uxjdvxve.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gt2kzrpqcef.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2wvnjcncf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2slwolbwe.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gt2qdunuocs.html

awk '{print $1, $3}' a.txt
来源：http://dali.fzhhl.top/Article/details/gt2odswbmmk.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gt2woowqgdb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tanke756.top/Article/details/gt2blebqwws.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2mklfydgi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2exxsyoxr.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2unwvhoox.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gt2xcqtlgti.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gt2dljlxnko.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gt2ufgvnjsc.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gt2poqppxxc.html


<!-- 参考信息 -->