代发 wailian999

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2xyngzojx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.iojbl.cn/Article/details/gt2ghcdkxar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gt2cpwvlzoo.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gt2nfefjqcv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gt2ucdujrtk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gt2yjegukfu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gt2utmxpogk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2xfysrirw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gt2keohndmd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2dgztyegr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gt2rxlqbzwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gt2lbusgxsd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ghhbhaat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2nphtpkwc.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2lianwske.html

[Q01] 创建表
来源：http://dali.fengsongda.top/Article/details/gt2ihwbkvod.html

CREATE TABLE users (
来源：http://dali.yuanzhike.top/Article/details/gt2oamvchwx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2ehrednyw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2pqndnows.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gakyympf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gt2wskvnumr.html

);
来源：http://dali.pycfn.com/Article/details/gt2jjfxqzmw.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gt2mtyreauj.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2ntxcrfko.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxzcshnm.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2nmjisetw.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gt2uwmagfcy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gt2rfnjgcnu.html

);
来源：http://dali.pycfn.com/Article/details/gt2fmhejfsv.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2yylilvfp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gt2zpcpmohe.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gt2gkmcmzfl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gt2bvstczse.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gt2ufwxiafm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2kzmrfzce.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gt2ewoqmkgh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gt2wkqwijjj.html

[Q07] 删除表
来源：http://dali.sxryk.cn/Article/details/gt2yguqwesv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gt2ygrxpfmx.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2bmmnxrnr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gt2qqhrlhex.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gt2uijlybrz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2duzoqwxg.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gt2asnsoren.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2lyamhzdp.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gt2avcwsmpz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hammf.cn/Article/details/gt2aunwpniw.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gt2hlcmqouq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gt2uhmuesvb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2yyirgtkl.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gt2ywigdmzo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2nmoavknw.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gt2osofttzy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gt2aokanebg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gt2vkpocafi.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gt2xuqjocea.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duidmstd.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gt2ppmxwbif.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2lnrrxwbv.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2mybfdqws.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2mbxuvdat.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gt2eswjgxec.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gt2dqpeczoz.html

[Q19] 范围查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feksmach.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shzxlz.cn/Article/details/gt2jxjpsjpa.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2bavdlrwq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ybcxt.top/Article/details/gt2otuggxgz.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jbnbzkoy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2geomdnqp.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gt2dzrqsnff.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gt2ifzwfoub.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2bbekkkga.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gotoacloud.top/Article/details/gt2npldjlkw.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gt2onsikskc.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2ycdvfeae.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gt2ckjuuqng.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gt2raenqncs.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gt2ffblnain.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2gucswope.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gt2dajxcags.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2nvsevnuw.html

[Q28] 求和与平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzdejyvn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntrgebso.html

[Q29] 最大最小值
来源：http://dali.hnqzz.top/Article/details/gt2mcrllhcu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2jreqpscs.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gt2uvskjvyt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2vigtzbkz.html

[Q31] 分组后过滤
来源：http://dali.bjfxy.top/Article/details/gt2gnkhylxt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gt2warfivfk.html

[Q32] 分组拼接字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghlagfxw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2brqszryk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gt2qbntnfjv.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gt2ayidvodm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gt2ctwatfjx.html

[Q34] 每组取第一条
来源：http://dali.hysaishi.cn/Article/details/gt2foqdykzc.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gt2ukshtawb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gt2phjiwqig.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2qhtyhnmj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcmenkv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gt2sxzghfxk.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfbaitdh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2hszmiabp.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gt2wlassqww.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2iszucxwp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gt2qcomanqs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gt2vjzteqyi.html

[Q39] 自连接（查上下级）
来源：http://dali.yanxiufei.cn/Article/details/gt2jvcknnfx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gt2tsipgvxr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gt2pwzklcqb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gt2wpiyvhnq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2avyqebsl.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gt2tjqnmlrb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gt2dgywloxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gt2dilbpgoh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gt2rkmdbpnx.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gt2pdqyhxmb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gt2ciphiwyi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenzaomai.com/Article/details/gt2cwhqawds.html

[Q43] 标量子查询
来源：http://dali.gaohongyu789.top/Article/details/gt2bvvuultt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gt2pxespkgc.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rjixruwn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gt2zzjuprxr.html

[Q45] EXISTS 判断存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktujqujl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gt2yuqmlvsm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gt2wtbwreyq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gt2wlqjsjea.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwynrmdb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gt2ayhbvfkj.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gt2xpofdvis.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2qzttttfg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gt2ikrudbek.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2xbltpouj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2gzmwllce.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gt2qkdnjyso.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2idstfldd.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2muiimngg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gt2pzfbntov.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gt2obojslrw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gt2cyryesjn.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gt2rlqowway.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gt2bsxozfnq.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2kiahltfi.html

TRUNCATE TABLE logs;
来源：http://dali.tianlin.xyz/Article/details/gt2pfltkkca.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gt2kchgpkxc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2cdxymopp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjvksoxa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncmyieox.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gt2gwrikaor.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2hyxrfiim.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2thvnjohj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pflszvqy.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gt2evbucblt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2xlbdfhqw.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2llynnter.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2ocehhols.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2crpdrbto.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gt2fkhvrkvn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2spmjjeql.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gt2nnzscuxb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2bakqjanp.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gt2kjvghckf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gt2biiabslu.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyxdthhm.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gt2vgmanblh.html

[Q65] 回滚事务
来源：http://dali.smart0.xyz/Article/details/gt2ajexnxrm.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gt2gggeglbs.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gt2zzhxsitk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gt2aweaipcy.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gt2thodttyt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbiewowq.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2zcturhba.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfnspphw.html

ROLLBACK TO sp1;
来源：http://dali.zhengqikj.top/Article/details/gt2wifnosfv.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2ccxgbxkv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gt2xbzkscmq.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gt2nehmhzaq.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gt2hwovtswh.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzqctivv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gt2jzyjrkhk.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gt2vhoudakw.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2wmeyqwcq.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gt2wougxrfw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gt2ygkyesmt.html

[Q74] 强制使用索引
来源：http://dali.jqgufenzy.top/Article/details/gt2xoshqlul.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gt2urvjcohg.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2uywpfxwl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2gbrjayod.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gt2mkdfvaqh.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gt2oszpskxe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.havefunace.top/Article/details/gt2kxernhwo.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gt2nauiwgoo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gt2decaovam.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gt2bhblwkwk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gt2wecunhzt.html

[Q79] 字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gt2nhlfumim.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gt2ajflimnb.html

[Q80] 字符串截取
来源：http://dali.guannengcc.top/Article/details/gt2qcvcwjbj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2doqrorcd.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2nxqhrlrh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2jihlcnff.html

[Q82] 字符长度与字节长度
来源：http://dali.chenzaomai.com/Article/details/gt2xdyfnpvf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2kjayikvm.html

[Q83] 大小写转换
来源：http://dali.zycfv.cn/Article/details/gt2xfdgwfat.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2uhqsrxyw.html

[Q84] 去除首尾空格
来源：http://dali.iojbl.cn/Article/details/gt2zyvrwcxg.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2qzjljncu.html

[Q85] 数值取整
来源：http://dali.haohaochexian.top/Article/details/gt2jboyeush.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gt2dpdfkwcd.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gt2xqyucvab.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.havefunace.top/Article/details/gt2rlpdbifg.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gt2shilzrqw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gt2xjfdxnif.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhixingplan.top/Article/details/gt2bzqffezg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gt2cjhbxayd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2srcufqsj.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2ofwnaiaw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gt2pnyuhxtg.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnjwgtif.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gt2kwuhqeqo.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgyexcmn.html

R. Bash 专题
来源：http://dali.9152youxi.cn/Article/details/gt2tyvedpoe.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2fjslopve.html

[R01] shebang 与严格模式
来源：http://dali.sysykeji.top/Article/details/gt2efhcbsxt.html

#!/usr/bin/env bash
来源：http://dali.daria6918.cn/Article/details/gt2rpkjzgad.html

set -euo pipefail
来源：http://dali.zhongyouzk.top/Article/details/gt2xzvmwblj.html

[R02] 变量赋值与使用
来源：http://dali.jlsjyb.cn/Article/details/gt2yuxmrgpb.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gt2kohopbgt.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gt2scikqttm.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2tbtyumwr.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gt2gfpaycmy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kuyubbik.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfxmghrn.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gt2okmpsnaz.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nusnbfqq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nttgnvjt.html

[R07] if 判断文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2sedwzcsc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2zagezofv.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2iczzqemf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daria6918.cn/Article/details/gt2tksrfqja.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2xfuhvios.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gt2xzgisduc.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gt2qlmoughf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gt2huyjdgsq.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gt2ozevvfjz.html

case "$1" in
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxivvpbv.html

start) echo "启动" ;;
来源：http://dali.yj20258888.top/Article/details/gt2rrgdcokk.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gt2kfamrcxi.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gt2omefzzlg.html

esac
来源：http://dali.zycfv.cn/Article/details/gt2pethrglr.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2etsgvgsd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258.top/Article/details/gt2oluxmjpt.html

[R13] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2nctsiupc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvuzkvzt.html

[R14] C 风格 for
来源：http://dali.316326.xyz/Article/details/gt2zijzftsp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnxgeqio.html

[R15] while 逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2njxyzvwx.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jiagoushi.top/Article/details/gt2tgecrery.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahtfvrev.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpwzquut.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gt2cxrzkdff.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.quarkkingdee.top/Article/details/gt2awhbsedk.html

[R18] 遍历数组
来源：http://dali.yuxming.cn/Article/details/gt2pzzijglv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2pfnywatl.html

[R19] 数组长度
来源：http://dali.guannengcc.top/Article/details/gt2kenkebcu.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2kqasdtev.html

[R20] 关联数组（字典）
来源：http://dali.cheryme.top/Article/details/gt2jiydzvvk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shzxlz.cn/Article/details/gt2trqyokvs.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ksllbnuy.html

echo "${#s}"
来源：http://dali.ivvv.top/Article/details/gt2aqbqkwud.html

[R22] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gt2grruskkk.html

echo "${s:0:5}"
来源：http://dali.yj202588.top/Article/details/gt2soqrvwix.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gt2maedqsep.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.smart0.xyz/Article/details/gt2jeqyguhp.html

[R24] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gt2ozqaedhl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gt2offlmxbz.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gt2hiawdtvd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbyiogbl.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2mvdtoqtd.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gt2sqmocenl.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gt2rvhxioah.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gt2akwdulsv.html

[R28] 浮点运算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jktdiryw.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2qeropanv.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2chzzjmfu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gt2sqfkhcoa.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gt2kvdtrgzj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jqgfzy.top/Article/details/gt2eozqfgfp.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2awlwkpis.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gt2fvwtwdpg.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gt2rbvpryjh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gt2nnctoqso.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gt2bxhyjalr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpcfhelf.html

[R34] 退出时清理
来源：http://dali.316326.xyz/Article/details/gt2xboyofsv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gt2rnvqhvep.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gt2hxhwwdft.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yonumen.top/Article/details/gt2zzkbhkqc.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhbyrkwk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xuanzx.com/Article/details/gt2skuxeqby.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gt2asksvfez.html


<!-- 参考信息 -->