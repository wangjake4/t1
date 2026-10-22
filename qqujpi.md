代发 wailian999

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gt2ehunbkcq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gt2tizcsxza.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ivvv.top/Article/details/gt2pxjkbtmb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gt2ekprqjzb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2mzdjgufv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gt2wyohldeo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jmzddagb.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gt2xoamgubi.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gt2bifqojps.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2iqrtharf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2jbygzlfs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gt2amosrshe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2jmclkqdh.html

);
来源：http://dali.aizwys.cn/Article/details/gt2abcbbayg.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gt2yyzypfcw.html

CREATE TABLE orders (
来源：http://dali.sweek.top/Article/details/gt2pgliiejb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwycyocw.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2prbujfjf.html

amount DECIMAL(10, 2),
来源：http://dali.hnqzz.top/Article/details/gt2ejpimaqa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2olaxznqj.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gt2wuvwnfrq.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gt2qlndgbkv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gt2wqkbktza.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2wyhuzfhr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gt2skucvcmu.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gt2nxqvrdku.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gt2bnwnzbhs.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gt2utoesxew.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gt2skrmvtsq.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gt2bzlvyfsf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryhkaina.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gt2udklgora.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2nicwpjqw.html

[Q09] 创建唯一索引
来源：http://dali.chenzaomai.com/Article/details/gt2lwiqviut.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gt2rbymdeqc.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gt2tmhzxfod.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2fvwgwajx.html

[Q11] 一次插入多行
来源：http://dali.vqdsnc.cn/Article/details/gt2hzniyvdc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2uubwoyme.html

[Q12] 插入后取自增 ID
来源：http://dali.fzhhl.top/Article/details/gt2knawbsoe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gt2cvqcttgx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gt2ywrebstv.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gt2bgrcmxjo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2asdggwln.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2krmwexls.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gt2fguvttek.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gt2rcfbapgn.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odijeunt.html

SELECT * FROM users;
来源：http://dali.yonumen.top/Article/details/gt2rflisyma.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2mxzoasaf.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqrfqfqb.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gt2vfzrmnhw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gt2ebiujrjy.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2purqcahn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gt2twpuyctb.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gt2jzssfduc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofikwooy.html

[Q20] IN 列表
来源：http://dali.jiagoushi.top/Article/details/gt2pdnaiyey.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2aclmojmi.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gt2pwbwbaxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangdashe.top/Article/details/gt2tdhqdmpy.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gt2xfzmydmt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gt2jvyoebij.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qoyxpmjm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2azcdgicg.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syzufwsr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2nczxvxnp.html

[Q25] 只取前 N 条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrpinvof.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2btcwoimn.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gt2gzfrflpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2vhpcpiux.html

[Q27] 条件计数
来源：http://dali.dashuyun.cn/Article/details/gt2olzaudwu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2attlqsbv.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gt2lxblfytx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2vcaghrvi.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtdewugm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2upqaojgy.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gt2powrpcmu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2yjguiiem.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2bsxllaju.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2innvjrbf.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2pzxbxujx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2oyscrgsu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gt2chxwptcz.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gt2dbxicgjf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gt2essehbmg.html

[Q34] 每组取第一条
来源：http://dali.tanke756.top/Article/details/gt2xpzyqyma.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gt2gekxywat.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gt2mxzeodiu.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2ixfvxchk.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gt2lfjbpaho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gt2wonxruta.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gt2xdrbltiv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gt2gjrgkohp.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gt2kksyxahc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdtlptiy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2zhomtisd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gt2mzsxyjlo.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxclfmun.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gt2bhuqybvb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gt2hjkeqosu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gt2yfdmmxtn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2ozbjdipk.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnfriqyh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cucudq.cn/Article/details/gt2fdsaznvf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2evwsezcv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdmmrkwf.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gt2lbtajxbn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gt2hnwmigjb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2absfzgaq.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gt2sxbfuxrj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gt2wavtvyeg.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gt2atmkilqv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2ooyqkrom.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gt2bllzhxru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2ethyzzcp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2reoyljyz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gt2vycmkcah.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gt2sptcsnse.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gt2dewfpoib.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gt2pkjgjrfh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2qlfgfvld.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2xjnizmeb.html

[Q49] 更新单行
来源：http://dali.cdnleiting.top/Article/details/gt2gzpyuxtd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2tifhqnzm.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gt2xrwpcciu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2cbvxiyov.html

[Q51] 用子查询更新
来源：http://dali.cdnleiting.top/Article/details/gt2ujwfergf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aibaodan.cn/Article/details/gt2cawftzed.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gt2enfibmev.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gt2hwbubbsd.html

[Q53] 按条件删除
来源：http://dali.jqgufenzy.top/Article/details/gt2rrmehlea.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gt2estafogx.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gt2kkcbtvgi.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2ltzssafr.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gt2cybwiouw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2djsmiidg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.c1oappe.top/Article/details/gt2gnmngafp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gt2mqbpatte.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2zslfhuhf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2nubqedzp.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyxxkufa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bainwrre.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gt2zzlxdccw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2hopnmhex.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rlfrzjvd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gt2uueirbhu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2koqivsvu.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gt2afdkbrtv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2ulawxhot.html

[Q62] 分组占比
来源：http://dali.xinyue.icu/Article/details/gt2mteqhxew.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2zluacbpi.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gt2xrgkitpf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2jpbaxykw.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gt2qftgzdjn.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gt2qtetbxcw.html

[Q65] 回滚事务
来源：http://dali.yj20258.top/Article/details/gt2ffhnhvhz.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gt2zhuhygqf.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gt2krktuzdo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gt2ttlqlzki.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gt2voyshwsb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gt2dmgzeiye.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngdlmjck.html

SAVEPOINT sp1;
来源：http://dali.cashguo.top/Article/details/gt2uczrrwgl.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdbdxfbq.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gt2vbsibbhu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2lkmzdppa.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gt2rnardzds.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gt2cduopzfm.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gt2urkduuzk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2ateqrglq.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwgbzcy.html

SHOW INDEX FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2otbibzgt.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gt2akcaptih.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2oedasfyu.html

[Q74] 强制使用索引
来源：http://dali.sufxvd.cn/Article/details/gt2mcvjmhwx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gt2ltyiugbj.html

[Q75] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2rxbifrgg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2fcydfzgq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gt2iyfncadx.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gt2yspftzeg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2gzpiocpq.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gt2thepkkvf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gt2gpxwudwf.html

[Q78] 当前时间
来源：http://dali.dashuyun.cn/Article/details/gt2siymnzcg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2roxzifyb.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2tilrhvus.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zycfv.cn/Article/details/gt2gvwnjxgf.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gt2mbhboziw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twifjanw.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gt2vbaycjev.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2mnclxyrw.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gt2hfmgmmyj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2zqtfnikp.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gt2ksxhtyqc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2hihjvfex.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gt2yratiaxp.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2juifyqnx.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gt2njhwroej.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gt2jibigywg.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rwsmbfts.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hysaishi.cn/Article/details/gt2yhujrizp.html

[Q87] JSON 字段做条件
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnmjakze.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gt2njejfdca.html

[Q88] 行转列（条件聚合）
来源：http://dali.aizwys.cn/Article/details/gt2jegyekkg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gt2fbylhanf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2vryjpbax.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2lwhiipax.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2gxuwjwve.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gt2rykfqmba.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gt2fewklgnz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2sslafnfo.html

R. Bash 专题
来源：http://dali.jlsjyb.cn/Article/details/gt2bqarrugy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kgylyrsf.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gt2jqmfctpr.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gt2bsdwcxuh.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gt2evuvkchw.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gt2vwntzhay.html

name="Tom"; echo "$name"
来源：http://dali.svipenyu.cn/Article/details/gt2ryvllmdl.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gt2vfqvufel.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2rvmtajyu.html

[R04] 位置参数
来源：http://dali.hnxiangtu.top/Article/details/gt2mgakttwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.aibaodan.cn/Article/details/gt2zqxkedqr.html

[R05] 参数默认值
来源：http://dali.jyoumei.cn/Article/details/gt2fhpepswq.html

name="${1:-default}"
来源：http://dali.guowangkeji.top/Article/details/gt2fkogpccl.html

[R06] 判断命令是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2amiwereb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dtvmwmvy.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gt2ntwftkmw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gt2lonsbliq.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gt2keddsuzx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ppjwa.cn/Article/details/gt2crtjlsku.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gt2kcgrdxci.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2ciybsoka.html

[R10] 正则匹配
来源：http://dali.zycfv.cn/Article/details/gt2hldvthxw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gt2bmtdsbrp.html

[R11] case 多分支
来源：http://dali.wangdashe.top/Article/details/gt2ikapvadz.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gt2hjdytexm.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2guokycbv.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2rvahsdjz.html

*)     echo "未知命令" ;;
来源：http://dali.smart0.xyz/Article/details/gt2znjiyueb.html

esac
来源：http://dali.mhx1999.top/Article/details/gt2ucsoftqx.html

[R12] for 遍历文件
来源：http://dali.sxryk.cn/Article/details/gt2vgblvyhs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jqgfzy.top/Article/details/gt2ogkiztpt.html

[R13] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2xyoirhld.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gt2gxubhgpj.html

[R14] C 风格 for
来源：http://dali.birdmap.top/Article/details/gt2bhonuzxy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gt2izfioumm.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2peauudgt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tanke756.top/Article/details/gt2nxalawja.html

[R16] until 等待条件
来源：http://dali.zdqjudy.top/Article/details/gt2wywsrlbd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhengqikj.top/Article/details/gt2mfjhknre.html

[R17] 数组定义与取值
来源：http://dali.fengsongda.top/Article/details/gt2olofbcct.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gt2vlgmzlmo.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gt2usqgtiwb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.0kj1m.cn/Article/details/gt2gowoqgwr.html

[R19] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2fhivmbpz.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gt2qiuigzlu.html

[R20] 关联数组（字典）
来源：http://dali.gzhubu.top/Article/details/gt2efoytfpx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2mfuhygvp.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2yslwcpho.html

echo "${#s}"
来源：http://dali.xylfe.cn/Article/details/gt2amekwupf.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2umileazk.html

echo "${s:0:5}"
来源：http://dali.pycfn.com/Article/details/gt2dpouduth.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gt2uwtijuea.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gt2lxzopzdb.html

[R24] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gt2pumlapgx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xylfe.cn/Article/details/gt2zfuzyqsd.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2ugchaxyx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2wsnymegt.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2wclcfmqn.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gt2dzzqfocc.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gt2gnuchdsm.html

echo $((1 + 2 * 3))
来源：http://dali.shzxlz.cn/Article/details/gt2qtbkgasd.html

[R28] 浮点运算
来源：http://dali.meibo888.top/Article/details/gt2nkkiqkpv.html

echo "scale=2; 10/3" | bc
来源：http://dali.ybcxt.top/Article/details/gt2wfbiqrne.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmnsiafs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gt2gzpuqigb.html

[R30] 函数返回状态码
来源：http://dali.yuanzhike.top/Article/details/gt2yvkyvvum.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nghfozaw.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hylfafnx.html

f() { local x=1; echo "$x"; }
来源：http://dali.hfpthk.cn/Article/details/gt2sisywyia.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gt2kxmxytle.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gt2soauanup.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gt2senalrhn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tanke756.top/Article/details/gt2bimuyanx.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gt2fnlntovj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shzxlz.cn/Article/details/gt2gylfznlu.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2snmazyiq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gt2htmcizlr.html

[R36] 并发执行多个任务
来源：http://dali.yonumen.top/Article/details/gt2cevvahpr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gt2fyngbpvn.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdgzryrm.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2hubawqvh.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gt2cymrpzuo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2qvnmfham.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2aupsmtal.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qycfuphr.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gt2jgwobacz.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gt2gaqxfbon.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gt2lbeabgpr.html


<!-- 参考信息 -->