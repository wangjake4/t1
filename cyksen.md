代发 wailian999

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2noihvlfc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gt2wklmzvvv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gt2wrdodzip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucnpstku.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gt2fhroapng.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gt2wbjxuagq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gt2uessjnso.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gt2gzplqerh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2kxjcifnx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gt2kdlwpvmv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ndrjusod.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2xnbtuuod.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gt2gsnqgxge.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2ppqskabh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gt2ceplkwhp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gt2klwzcqkt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gt2oxflguse.html

);
来源：http://dali.yj20258888.top/Article/details/gt2hcinrbzu.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gt2japxqgfz.html

CREATE TABLE orders (
来源：http://dali.0kj1m.cn/Article/details/gt2fynypimq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2sqgxfosn.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2cwfboyfv.html

amount DECIMAL(10, 2),
来源：http://dali.nanxinkj.top/Article/details/gt2rdlbhtbt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gt2lrwgcmxe.html

);
来源：http://dali.yj202588.top/Article/details/gt2xnztteoh.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gt2qrzvoqny.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gt2gaqxdcjo.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gt2pfdvkdye.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qemmcsaf.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2yqaeihdj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gt2augpecrc.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gt2tcvzppiv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gt2qvjefpuw.html

[Q07] 删除表
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrzvrssr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onuifyzk.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2hquyzbkk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gt2wqgsopki.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gt2hempgkpt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qgllfdmn.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2rlqqbvor.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yonumen.top/Article/details/gt2dttxmywb.html

[Q11] 一次插入多行
来源：http://dali.tanke756.top/Article/details/gt2fdyfsybl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2mhzhtkif.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bheqgekt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gt2alpzrqfy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gt2vzgnemez.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gt2wrpuzjey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pycfn.com/Article/details/gt2pefcqlef.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gt2gveeseya.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gt2wdbgndeh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gt2wzzkqzmr.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gt2tnybvkiu.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2vyowtckn.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gt2cdmzzqvm.html

SELECT id, name FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxjgzwyv.html

[Q17] 条件查询
来源：http://dali.sufxvd.cn/Article/details/gt2gfmgitdo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbklaqok.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gt2crljxgof.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2slaqxilm.html

[Q19] 范围查询
来源：http://dali.hammf.cn/Article/details/gt2ghwstgbr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2lsuvoamh.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gt2ckuiwbyu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gt2fzzpcjdx.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gt2cxdixulp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gt2htffgxze.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gt2nrcviprn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2jlenxtbl.html

[Q23] 分页
来源：http://dali.jinghuilouyu.cn/Article/details/gt2goysmhxc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2igamjejz.html

[Q24] 去重
来源：http://dali.gogol.net.cn/Article/details/gt2uphzbkok.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2kyqfmdde.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gt2mascfcus.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gt2gybdgapr.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gt2auxyywcv.html

SELECT COUNT(*) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2tzkbeysj.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gt2goqjpfqi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2nlvtbgok.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gt2dqgekrwf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2fugcvwac.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gt2nqslwnfr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2cxhadvjd.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gt2iljesiro.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gt2qtlmsmpd.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gt2wnbkmyhz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gt2gbwnbhdb.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2adgadmmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2qtcgxxac.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2dfdlmixn.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gt2dsphipiw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2rymjdwng.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gt2rlpuujxg.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gt2rqefesdf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfgnllgx.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gt2wyhwwhco.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gt2xxzjvgkr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2rzaqqams.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gt2cqbnbjgk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ehwqpu.com/Article/details/gt2ztjycwjc.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gt2vghvjtkv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tian-w.cn/Article/details/gt2barafgnn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gt2basnfjnj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gt2bhxnwydj.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjeajqbs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gt2vldpunyb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pycfn.com/Article/details/gt2caanqhzy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2rpcncxld.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigufen.top/Article/details/gt2qrqddybe.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gt2jegbzqtj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gt2kpebkmfa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2hdvbowci.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhoulong.xyz/Article/details/gt2lhvhlojh.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gt2dhondiam.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2iifgffix.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gt2pbtoleww.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gt2azrweayp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ntkocatu.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gt2lqpuevtb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gt2lsvivmbb.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gt2aqonrjqo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gt2ofxkackb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gt2ymzysozj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2ehrpxgbm.html

[Q47] 与平均值比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2vivdbynp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gt2kbnlegby.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2gepggpab.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gzhubu.top/Article/details/gt2ciwltgia.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gt2fitcetbt.html

[Q49] 更新单行
来源：http://dali.316326.xyz/Article/details/gt2nispmhpy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gt2iyjajgkn.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2mgiksfjz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daria6918.cn/Article/details/gt2qsyvhjey.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gt2unjuyzrl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gt2ztcefnvc.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2yywuryuu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2uhvouype.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dnpgzfoe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2cvjplvtv.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkcfttoy.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2vrkwzbag.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gt2peislyln.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2mrzpwsrb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2lgkbeqsf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2xjxcwihb.html

[Q57] 行号
来源：http://dali.zhengqikj.top/Article/details/gt2xoufspjx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2clhcdeam.html

[Q58] 累计求和
来源：http://dali.birdmap.top/Article/details/gt2hsaflhrn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2ptzebwtq.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2pyqpjjyx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2rfazjbhw.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gt2lttcacwf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2qoxbndqv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2jftuornt.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gt2pcynyord.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2acwhttoh.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gt2dqnvwahn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2afmfeezc.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2innzbjck.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gt2nvmzsike.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gt2jzicansi.html

COMMIT;
来源：http://dali.daria6918.cn/Article/details/gt2cxhyblvf.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frisndqc.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gt2etinanrg.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gt2vecalvnd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gt2dpvfcqfo.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gt2zvfghxmg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gt2pxihuyuj.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqtupcox.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gt2lbwxhqmf.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gt2ienrfhar.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gt2ealuvbnl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2amcqadrd.html

[Q70] 更新统计信息
来源：http://dali.gogol.net.cn/Article/details/gt2ifmupeys.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gt2dgkxzcje.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gt2thfpgchk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gt2fqekpedn.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gt2lwgkqjgk.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2urlravxb.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gt2iwvtlmaf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gt2xlrixfkf.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gt2tklhmsue.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gt2dhhnqtnd.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjdounjm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2gehwcxij.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gt2azsgcxku.html

[Q76] 按天统计
来源：http://dali.guowangkeji.top/Article/details/gt2yfsyfyuc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gt2fahkdmbl.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2timdnkxo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.redwolf501.top/Article/details/gt2jucnysqz.html

[Q78] 当前时间
来源：http://dali.wangshuangyany.cn/Article/details/gt2arxxauam.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gt2armiroxq.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2bedsuqgw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhengqikj.top/Article/details/gt2sbzmrmth.html

[Q80] 字符串截取
来源：http://dali.xziqi.cn/Article/details/gt2iljyourq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gt2echadyew.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gt2ukntqcrr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.havefunace.top/Article/details/gt2cxhaudau.html

[Q82] 字符长度与字节长度
来源：http://dali.sufxvd.cn/Article/details/gt2uuwndvzw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2brzyirch.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2rsymlfpr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2gaejlnja.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gt2yylkponw.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2zmepgkea.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gt2katqromj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gt2cdggnvfq.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gt2jseyvksh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gt2asadvjot.html

[Q87] JSON 字段做条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2agzwtmrt.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cdnleiting.top/Article/details/gt2cyecdfhr.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gt2awyywwtz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gt2zbmgkphv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2srnlhriz.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2rjtqawxs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eytyczyx.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2qtmayjai.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mipjaqfy.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2twrzygvw.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gt2pbyyjstx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2jtsxkrxi.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gt2wovuiusy.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gt2ogjstvie.html

set -euo pipefail
来源：http://dali.sysykeji.top/Article/details/gt2lhbdnddt.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2qstbocdz.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gt2piuqfpsy.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbpvnzdu.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gt2sfwltiaa.html

[R04] 位置参数
来源：http://dali.jinqigufen.top/Article/details/gt2iffdtheq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2jtptxpgw.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gt2sasagmuk.html

name="${1:-default}"
来源：http://dali.yangfankeji.com/Article/details/gt2xktklkpe.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2tikmarbz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gt2xipaqwvi.html

[R07] if 判断文件
来源：http://dali.shzxlz.cn/Article/details/gt2ryaxzowq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxugzwsj.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gt2bhnqyoez.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.svipenyu.cn/Article/details/gt2jezqgmvv.html

[R09] 字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ydrkybkz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jkulttbq.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2mpcjbcak.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gt2zmhqsbex.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gt2cafeaopn.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gt2vagoxfrl.html

start) echo "启动" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmfcesgz.html

stop)  echo "停止" ;;
来源：http://dali.jiagoushi.top/Article/details/gt2qniaxcrv.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2klbuenwl.html

esac
来源：http://dali.jqgufenzy.top/Article/details/gt2zuxixftr.html

[R12] for 遍历文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2aaxjbiqb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ypcahvju.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gt2zdgecxeo.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gt2wlktubun.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2bjogecoo.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gt2bmmlxahb.html

[R15] while 逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gt2tgpdsqnd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gt2nljbprym.html

[R16] until 等待条件
来源：http://dali.9152youxi.cn/Article/details/gt2ipwjhqmd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gt2ukvbdymy.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2xknmykvo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj20258.top/Article/details/gt2rstlnabd.html

[R18] 遍历数组
来源：http://dali.fengsongda.top/Article/details/gt2lhfnfivb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gogol.net.cn/Article/details/gt2gghddfqq.html

[R19] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2ypkvtnhs.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gt2mctqobly.html

[R20] 关联数组（字典）
来源：http://dali.9152youxi.cn/Article/details/gt2plolbcuc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yangfankeji.com/Article/details/gt2sothsxyo.html

[R21] 字符串长度
来源：http://dali.zhengqikj.top/Article/details/gt2lecbxtfh.html

echo "${#s}"
来源：http://dali.gotoacloud.top/Article/details/gt2hbxwckyr.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2bufqcwvh.html

echo "${s:0:5}"
来源：http://dali.hfpthk.cn/Article/details/gt2nrrporwb.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gt2dfquwqhp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.tianlin.xyz/Article/details/gt2kaxgszhu.html

[R24] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gt2mhpsraip.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2yhnyyoax.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gt2bhghyzoz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gt2dllwnhxa.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2knksmcnw.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwsenksg.html

[R27] 算术展开
来源：http://dali.shzxlz.cn/Article/details/gt2cafbxlgt.html

echo $((1 + 2 * 3))
来源：http://dali.dianchejie.cn/Article/details/gt2qkqihqsc.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gt2szjulywk.html

echo "scale=2; 10/3" | bc
来源：http://dali.cqqwz.cn/Article/details/gt2wpquinpi.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2uccntwte.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2xstxrdcy.html

[R30] 函数返回状态码
来源：http://dali.c1oappe.top/Article/details/gt2ywonyhqg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ydzc1.top/Article/details/gt2mhjplkvb.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gt2lqykwpib.html

f() { local x=1; echo "$x"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kaibdrai.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gt2ryrotrvs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gt2nefdjprq.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gt2rpryzlgs.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gt2tnydleep.html

[R34] 退出时清理
来源：http://dali.iojbl.cn/Article/details/gt2lamyghqz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gt2gfwewjuc.html

[R35] 后台执行并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxfsnwuj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gt2vjwwsahz.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gt2hpogkcuv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj20258.top/Article/details/gt2daimzvfh.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gt2jxdtiqyf.html

files=$(ls -1)
来源：http://dali.xuanzx.com/Article/details/gt2nrlthmzx.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbacmchm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.svipenyu.cn/Article/details/gt2yxktkuqm.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gt2ihdrdgmd.html


<!-- 参考信息 -->