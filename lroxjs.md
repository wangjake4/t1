代发 wailian999

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2obexpkdd.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2etlxnibc.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gt2qdkyqzoy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gt2hbhdfvzo.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2wzyczqpv.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gt2ssedaija.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2hduasswo.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ngsmjkkp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2gjatuxag.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gt2dhbepggt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqvhtwgu.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gt2vnmhxkzc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gt2vcqadkdo.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gt2cnnafwzz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gt2qxidpjwd.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gt2nevgshbm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gt2uvybwhns.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gt2nblbpbpr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gt2uixehxuk.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gt2xyvqjuzk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2lpkoryqn.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gt2gbjbwsmb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2ssagmycp.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gt2mffciczd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jmszivcj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2suhzusoi.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gt2pbxrteou.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gt2qskubmlw.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eoyafvgz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenzaomai.com/Article/details/gt2zbfutfhg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2wpibyotj.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvglrjec.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2fstaddmu.html

[Q16] 查询指定列
来源：http://dali.9152youxi.cn/Article/details/gt2javwiuai.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2ukmmkrnt.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2rqjzagkp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2bctekvqs.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pchjcxox.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxuanxn.top/Article/details/gt2zpxmndvf.html

[Q19] 范围查询
来源：http://dali.haohaochexian.top/Article/details/gt2pfcdiyfc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nimqgulf.html

[Q20] IN 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2twopmbei.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gt2auaxfcyd.html

[Q21] 空值判断
来源：http://dali.yuanzhike.top/Article/details/gt2xicertvp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gt2qvanhnjm.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gt2jfzlhqgv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenzaomai.com/Article/details/gt2gmlsannk.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gt2ycjwiqxh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gt2zmgnpoff.html

[Q24] 去重
来源：http://dali.tanke756.top/Article/details/gt2phpwdplr.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2fsjjrxad.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gt2embelyef.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibdfktmq.html

[Q26] 计数
来源：http://dali.shuidangran.top/Article/details/gt2ziwkevrt.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ndvtieal.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gt2bajhetay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2xategkvx.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2heqpsrzl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2mlzzdlcn.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2brhumuax.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2lpbgxtbv.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gt2fxwluhln.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2utevgcwg.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gt2bcvqtnsr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2kcbsnshj.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2zlhwfxxu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2tyszkmzf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gt2lrqicvyu.html

[Q33] 多列分组
来源：http://dali.jinqigufen.top/Article/details/gt2pazbatxo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gt2indwaneh.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gt2wvswvbvo.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukkfcvcb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gt2jiapoqrz.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2dkrjprnl.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqyvslcp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gt2unuyibwp.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gt2sxabmlbf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2euhdstgp.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gt2zmjlizao.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2emepybaq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sxryk.cn/Article/details/gt2eidjyaci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2qqgjuefa.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gt2ametswam.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yueranfly.top/Article/details/gt2wzrhdofo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gt2dozijruy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gt2ahyqhoet.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gt2qauvlpnz.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2thgrqcap.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gt2inpsjawi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gt2tmozkbxk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gt2unfajepj.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gt2osicjwdl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrhavqzk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2cgauwnqt.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gt2rqfbklni.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2jzfocakn.html

[Q44] IN 子查询
来源：http://dali.tanke756.top/Article/details/gt2weqzcmxd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gt2ppnnyrmn.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gt2owhmxnpe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gt2cntgomrf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gt2rlzfkkvv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2qaxtpnqj.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gt2rtwerrag.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yvedp.cn/Article/details/gt2nsszasiz.html

[Q48] CTE 公用表表达式
来源：http://dali.hywenlv.cn/Article/details/gt2wwehqosr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2toqeewfr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gt2sldgtesj.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twflhsep.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gt2gdwalkdm.html

[Q50] 批量更新
来源：http://dali.hysaishi.cn/Article/details/gt2ltoktsvq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gt2iirtqtcu.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gt2argzjgnm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2urvxjhfo.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gt2mxrorxvz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxzrrexl.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gt2kngylvvl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gt2ypucaskk.html

[Q54] 清空表
来源：http://dali.vqdsnc.cn/Article/details/gt2uqebtwsw.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2ptjbcwtw.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gt2ktkcfkjd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gt2lufsqxui.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gt2hlxosxef.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhvwxcb.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gt2lgiwhqdn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2zemslafa.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gt2mladproq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gt2ebopibmp.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gt2utjdgmxb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2byaoyxlj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gt2lywimnxl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.havefunace.top/Article/details/gt2jjmzzrjm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2revwugne.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gt2efknibhl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2chnlvesd.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gt2dusdabsl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2aygnjevh.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gt2cxxfsjjs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gt2crinsarl.html

[Q64] 提交事务
来源：http://dali.xziqi.cn/Article/details/gt2gmshxala.html

COMMIT;
来源：http://dali.chenlongwang.top/Article/details/gt2lvydstxy.html

[Q65] 回滚事务
来源：http://dali.xylfe.cn/Article/details/gt2yhpyclih.html

ROLLBACK;
来源：http://dali.sxryk.cn/Article/details/gt2brcnlvzm.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gt2wvfbiliv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangdashe.top/Article/details/gt2oswccmtp.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gt2cvtmscqw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dikxmgws.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2klnonzeo.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gt2xsfmfefs.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gt2fuuebomm.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gt2hekzagjo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.redwolf501.top/Article/details/gt2dukhgmoa.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gt2anrpzdhx.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gt2nnbtueds.html

[Q71] 查看建表语句
来源：http://dali.hywenlv.cn/Article/details/gt2jeoiuwol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gt2dsrforax.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gt2cyehwmjr.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdznvpnm.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gt2wyuhxszr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gzhubu.top/Article/details/gt2qfpvtlil.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gt2xgcnypei.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.0kj1m.cn/Article/details/gt2rvnwlleh.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gt2vhrmxhoa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2sucizorh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gt2tfrhmttg.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2msxtopme.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2foyyiskl.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gt2nccjqtsc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.birdmap.top/Article/details/gt2zfdqhiif.html

[Q78] 当前时间
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2poxbmhgs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gt2mrnembke.html

[Q79] 字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gt2qkrngnor.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2lturrvhh.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gt2irztnzfg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2lllktqnl.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2mpyccptg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ayhaxafi.html

[Q82] 字符长度与字节长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsrmwmma.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jixbzgdy.html

[Q83] 大小写转换
来源：http://dali.jinqigfzy.top/Article/details/gt2trlfiugi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2xcftyuui.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gt2rsrvzkdm.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kxrtmdkk.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gt2qgivpwhw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rljieqge.html

[Q86] 读取 JSON 字段
来源：http://dali.cdnleiting.top/Article/details/gt2fyjjaafk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gt2fgymyaya.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2umymhqyr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258888.top/Article/details/gt2lerlyrok.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gt2kxousogk.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gt2qsykpniu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj20258.top/Article/details/gt2bmbpybmc.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gt2nzpaupbv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2rweqsbtz.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2jvcauknb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yueranfly.top/Article/details/gt2duzmuwyd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fpwrlfnp.html

R. Bash 专题
来源：http://dali.yj20258888.top/Article/details/gt2fafxrspk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2lwrkbvda.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gt2bhtgzvib.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rxglqqtj.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gt2hamjybrb.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gt2tuuutfhs.html

name="Tom"; echo "$name"
来源：http://dali.pengpengdd.cyou/Article/details/gt2irkzfyac.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gt2kwopfryd.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gt2dsbkrtdf.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gt2laalynsz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddyqqfiz.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2smzqmsqk.html

name="${1:-default}"
来源：http://dali.ivvv.top/Article/details/gt2oivxcwdx.html

[R06] 判断命令是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtdfazjj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gt2labmcpnx.html

[R07] if 判断文件
来源：http://dali.zhengqikj.top/Article/details/gt2oxnsoawx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhixingplan.top/Article/details/gt2rhmrizjs.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gt2zseffcst.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.redwolf501.top/Article/details/gt2merwjptt.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2tbchjhhb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ydzc1.top/Article/details/gt2rzifrtgr.html

[R10] 正则匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2cixodlnf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yanxiufei.cn/Article/details/gt2zcjzzgcz.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gt2jgavmtlb.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gt2kzdlaahn.html

start) echo "启动" ;;
来源：http://dali.xylfe.cn/Article/details/gt2bzvhrqqp.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gt2lgisxeiy.html

*)     echo "未知命令" ;;
来源：http://dali.jqgfzy.top/Article/details/gt2vznydtbo.html

esac
来源：http://dali.hfpthk.cn/Article/details/gt2bushzmms.html

[R12] for 遍历文件
来源：http://dali.pycfn.com/Article/details/gt2thsvtggc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ibbponqp.html

[R13] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gt2cnthyygc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangdashe.top/Article/details/gt2zxwwsczq.html

[R14] C 风格 for
来源：http://dali.hnxiangtu.top/Article/details/gt2siiumbcw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gt2ivahplxu.html

[R15] while 逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2ijkgssrm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xinyue.icu/Article/details/gt2fxqmvvhg.html

[R16] until 等待条件
来源：http://dali.hnxiangtu.top/Article/details/gt2ovirhudp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2iwttbclj.html

[R17] 数组定义与取值
来源：http://dali.daxiang520.top/Article/details/gt2qfwakium.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gt2xqvtwdxu.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gt2qrnrqxco.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gt2rujimznq.html

[R19] 数组长度
来源：http://dali.xuanzx.com/Article/details/gt2qjcqfzia.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gt2qriqyltr.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2ffiobulq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gt2wfpsrwcc.html

[R21] 字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2axcxbmmy.html

echo "${#s}"
来源：http://dali.daxiang520.top/Article/details/gt2ydzcgslq.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gt2bxwlropb.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gt2qiqgfkow.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gt2xrgvzxgh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gt2yawarcrx.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gt2fbpxcyoz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.svipenyu.cn/Article/details/gt2skthdwwp.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gt2kdsworwc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.9152youxi.cn/Article/details/gt2ypqbiprw.html

[R26] 命令替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcdoctmc.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gt2rwinkofk.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2yumdknot.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gt2kujwftyh.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gt2noyldree.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2ktfhgtsh.html

[R29] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gt2blpuujhn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fzhhl.top/Article/details/gt2zergkzfe.html

[R30] 函数返回状态码
来源：http://dali.jyoumei.cn/Article/details/gt2ionlesim.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2ccvnoafo.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gt2ddbdykgg.html

f() { local x=1; echo "$x"; }
来源：http://dali.snrcjt.cn/Article/details/gt2smlhjezq.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2soiokxgq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gt2uffblsdn.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gt2igmqvspy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gt2hydzywca.html

[R34] 退出时清理
来源：http://dali.cashguo.top/Article/details/gt2vzoaozgr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gt2ksmtmnwv.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2nqwexzbl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gt2ysduwmmz.html

[R36] 并发执行多个任务
来源：http://dali.xinyue.icu/Article/details/gt2zihehmmy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gt2ycxfapoy.html

[R37] 把输出赋给变量
来源：http://dali.dashuyun.cn/Article/details/gt2rqnrcfyc.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gt2kaoljnbm.html

[R38] 管道串联
来源：http://dali.zycfv.cn/Article/details/gt2uoigucmo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.9152youxi.cn/Article/details/gt2jdgnbyco.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gt2hkwssepj.html

cmd > out.log 2>&1
来源：http://dali.ivvv.top/Article/details/gt2sgvrhvau.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gt2sjdgbpem.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gt2pktggoko.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gt2dznuzxnn.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gt2kpqvzadr.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gt2irskzgxk.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gt2walcxzqk.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gt2uxvifiku.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gt2alczqeak.html

[R44] 按修改时间查找
来源：http://dali.zhixingplan.top/Article/details/gt2zrczagxx.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gt2oritryzw.html

[R45] 批量删除
来源：http://dali.shzxlz.cn/Article/details/gt2rslabrqj.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gt2ipdyoxeg.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gt2crlcumss.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gt2rfidbzqz.html

[R47] sed 单行替换
来源：http://dali.9152youxi.cn/Article/details/gt2aviaipzk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2ysmyigtj.html

[R48] awk 取指定列
来源：http://dali.yangfankeji.com/Article/details/gt2xfwrxsyk.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gt2mnjsnood.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gt2sselghjd.html


<!-- 参考信息 -->