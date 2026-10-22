代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.redwolf501.top/Article/details/gt2pypoopbu.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gt2ugkwgmof.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2waheukma.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orehtjfk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2aasfialy.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gt2bwsbzmsa.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gt2fbdlnxio.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2vohxcgmn.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gt2rzjxcsgu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2wwbjiwhx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2bvluxpmc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2hciapsri.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gt2toqphdri.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gt2ehulolmt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2sexcplvm.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gt2repgqekn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gt2vjaoixnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gt2ojbglafo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gt2lksifafg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2pcyjgduk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gphgkfcs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gt2bxlcdbfz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gt2lggncjsp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gt2cjgrgfsb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2whlcxemm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gt2zaahtzjt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2jguynths.html

[Q01] 创建表
来源：http://dali.ivvv.top/Article/details/gt2mzsbyerv.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gt2pieemoxy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2shjcnyxw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2wveytwzr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gt2lbmqqezd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxrzthcq.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2gmqccsid.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gt2xrctuhma.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gt2zmydncko.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2mxwspcvw.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gt2thfhedqe.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gt2jmaazbqc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xxzorgim.html

);
来源：http://dali.iojbl.cn/Article/details/gt2ekqvdldu.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gt2sqndfgrz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gt2dclzjjwr.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gt2kwpuvffb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gt2kxjbzdky.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gt2wvbtdznh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hammf.cn/Article/details/gt2axdrdmsb.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2lhlirxvm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ybcxt.top/Article/details/gt2edxwfzfd.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yqdckkjy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fazxzsld.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gt2wghodjxu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cashguo.top/Article/details/gt2rkldowet.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gt2sionucob.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2fdbigzfa.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gt2iappjcek.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2ahdbnnxi.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gt2gikxzgnl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2thqysqpe.html

[Q12] 插入后取自增 ID
来源：http://dali.hnxiangtu.top/Article/details/gt2duhltxpd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2dbnpnqvy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gt2bobhveny.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gt2vqqpsdvv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gt2dfiedcxa.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gt2hitpaiht.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gt2fypzchlw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hthlcekk.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gt2asrprirg.html

SELECT * FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2kxnwhqiz.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gt2czkrxftb.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2sifyntkz.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gt2plrvxsna.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zsphspxc.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gt2kansfxyc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2jzvpfgsl.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gt2fabhpdne.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yueranfly.top/Article/details/gt2zkasuvco.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gt2gnbwzqvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gamdxqpo.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gt2ghcqwrur.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.smart0.xyz/Article/details/gt2gwwndutg.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gt2igybmjqv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gt2tgzvacsj.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2jernymdw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenzaomai.com/Article/details/gt2cstqwefl.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gt2dhlgjltw.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2bziodude.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gt2lomzsuut.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhnfscql.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2rgwikuul.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfgwyfvx.html

[Q27] 条件计数
来源：http://dali.iojbl.cn/Article/details/gt2ulnksytp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2lfjnzvsz.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2fwhgnyuz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2sdsfadrc.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnzmkegp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2rxgwrgvj.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gt2skixvsvm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gt2agkhqixk.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kbutxbvx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebbxurnz.html

[Q32] 分组拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2ntcggkdo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2ogmbmkhk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gt2blmvhlrk.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2urdbqnle.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqjqnjhx.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gt2ussietqs.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gt2aoiatbsx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2evdvjdwt.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2kfkgnrws.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gt2tkdjqqgf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2iiwxitqt.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gt2hvataqya.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gt2zxjfobde.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gt2xyntgddd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gt2xhhivrru.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gt2fygcxvji.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2gjjesjsf.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgyamdno.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gt2xbvgxkcg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gt2wpjdwmsh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gt2lmpspghh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gt2yjbturfo.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gt2fbbpjflw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gt2xfcadoaz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2dkfhhjde.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2rffozsnq.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gt2qcffzotq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cashguo.top/Article/details/gt2qecvwzvq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gt2srdytovo.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2pgtvhlfe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2lnkjcrif.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gt2uszyhnnc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zycfv.cn/Article/details/gt2ldrmayie.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gt2yqdwkvbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gt2hqstkkds.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvrcyavf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2kyzrbpgl.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gt2zbvfbqvj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvmicltr.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gt2leeewsdh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.havefunace.top/Article/details/gt2hmsygziw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gt2zvosnumj.html

[Q49] 更新单行
来源：http://dali.xuanzx.com/Article/details/gt2aiafxmdp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gt2ltpywify.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gt2uhbcusax.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2gyhkjhgv.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gt2brlpoold.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2qwttbzrw.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2apeewtks.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zekuegtw.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gt2vjivuhul.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gt2uubwafnb.html

[Q54] 清空表
来源：http://dali.snrcjt.cn/Article/details/gt2xdknlkyj.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gt2njqslsnq.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gt2tangbuea.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gt2rojyjgel.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gt2hbiutlwk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gt2tjygqnvm.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2waluinjo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gt2qrrnboej.html

[Q58] 累计求和
来源：http://dali.quarkkingdee.top/Article/details/gt2fpokauod.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2uqkenetj.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gt2ecwcyizt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2ocfgkerm.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gt2wufaulhs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gt2moxqhhpq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2gsptxyud.html

[Q61] 移动平均
来源：http://dali.hywenlv.cn/Article/details/gt2kvnszwpu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2ytsmzqii.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gt2hzolxfam.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2ocrzntay.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2slpthoor.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gt2mqujzqyl.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2nphltvoq.html

COMMIT;
来源：http://dali.havefunace.top/Article/details/gt2dswqdufs.html

[Q65] 回滚事务
来源：http://dali.yj202588.top/Article/details/gt2olvutjum.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gt2czvtceys.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gt2gxscucfu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpejgquj.html

[Q67] 设置隔离级别
来源：http://dali.daria6918.cn/Article/details/gt2fgryyuqt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gt2kwbvmsjs.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2oycxzgir.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gt2lcskqovl.html

ROLLBACK TO sp1;
来源：http://dali.xziqi.cn/Article/details/gt2riwksrvs.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gt2azmjwgws.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sweek.top/Article/details/gt2ijvraure.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gt2nfgzsuyb.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gt2ogxrrtzi.html

[Q71] 查看建表语句
来源：http://dali.redwolf501.top/Article/details/gt2bhpieewa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2rsydbdhx.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gt2zhcarzwn.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2mrpegfeb.html

[Q73] 查看表状态
来源：http://dali.hfpthk.cn/Article/details/gt2frtvuywp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gt2huizjrae.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gt2hshdzyok.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gt2rluqmrxw.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2xwfbhozb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2eujougie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2fikpcvww.html

[Q76] 按天统计
来源：http://dali.fengsongda.top/Article/details/gt2ddjdrtnz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gt2fvolgznd.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gt2aygtspcd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ehwqpu.com/Article/details/gt2coyiebgg.html

[Q78] 当前时间
来源：http://dali.zhengqikj.top/Article/details/gt2fbxdcoxi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gt2ovrmfugv.html

[Q79] 字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2gfprydmv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmueohih.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gt2rfwgqyfx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2prihmsdk.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gt2rkwcxphp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2hpkewgcj.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gt2rgmprpkb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gt2lzuqjsfc.html

[Q83] 大小写转换
来源：http://dali.pycfn.com/Article/details/gt2lzprbano.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2mohwidfi.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnikfhsm.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2wjhhyksn.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gt2yqahkobd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xuanzx.com/Article/details/gt2qqhsazdx.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gt2squmrjpa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tian-w.cn/Article/details/gt2ubwhtyzs.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gt2qojiqqzu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2ypykhjmf.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gt2qygnjfln.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yuxming.cn/Article/details/gt2qfvlnmhj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2uifzgehv.html

[Q89] 判断表是否存在
来源：http://dali.sxryk.cn/Article/details/gt2plzmkgpi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2izymgkru.html

[Q90] 生成序号列
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwdsjeut.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gt2utoqccou.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxymkeih.html

R. Bash 专题
来源：http://dali.iojbl.cn/Article/details/gt2guqufyzl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yymgsnva.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gt2nveevtoz.html

#!/usr/bin/env bash
来源：http://dali.haohaochexian.top/Article/details/gt2okbjmbng.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2eiakrtzb.html

[R02] 变量赋值与使用
来源：http://dali.zhoulong.xyz/Article/details/gt2yawcmnlj.html

name="Tom"; echo "$name"
来源：http://dali.dianchejie.cn/Article/details/gt2xzgsmklj.html

[R03] 只读变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xxpztxvb.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2vqtonzdh.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gt2dalyawfb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sysykeji.top/Article/details/gt2wrwxyfku.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2yblepjkm.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gt2zmsrkjlv.html

[R06] 判断命令是否存在
来源：http://dali.havefunace.top/Article/details/gt2ntsfmbic.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2puvlmyoi.html

[R07] if 判断文件
来源：http://dali.jyoumei.cn/Article/details/gt2lmbuvniu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gt2ulwzfrgl.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gt2vejwzayj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gt2jjevpywg.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gt2pjhdnpgv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gt2pqnkjsvh.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gt2dbxwkvlp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zdqjudy.top/Article/details/gt2xkhnowuj.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2kefwhbns.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gt2ndzfbwrx.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gt2poxgqexm.html

stop)  echo "停止" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2sjprfdtv.html

*)     echo "未知命令" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2testoezo.html

esac
来源：http://dali.hysaishi.cn/Article/details/gt2sucjnnzo.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2xrdrtwjg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tian-w.cn/Article/details/gt2jrbdcrlx.html

[R13] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uxnepmmx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sufxvd.cn/Article/details/gt2qagwoafc.html

[R14] C 风格 for
来源：http://dali.hnqzz.top/Article/details/gt2qoptjgsk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gt2tzeiwwon.html

[R15] while 逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2hynqkvpe.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gt2hmiamqog.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwcdviyf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gt2ssmpxtqo.html

[R17] 数组定义与取值
来源：http://dali.hysaishi.cn/Article/details/gt2icqngpci.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.sufxvd.cn/Article/details/gt2xazxgxur.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gt2alkdjiej.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cqqwz.cn/Article/details/gt2hewmqbfy.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2bcbcmxlp.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gt2albmixie.html

[R20] 关联数组（字典）
来源：http://dali.shzxlz.cn/Article/details/gt2oyyhkwuk.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gt2zntujtdb.html

[R21] 字符串长度
来源：http://dali.havefunace.top/Article/details/gt2qhquhjya.html

echo "${#s}"
来源：http://dali.ehwqpu.com/Article/details/gt2rugwywqq.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2lvnntnxq.html

echo "${s:0:5}"
来源：http://dali.jiagoushi.top/Article/details/gt2wdfwxkhk.html

[R23] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gt2ixxovcek.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afqxliwu.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2ruvsaikk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jyoumei.cn/Article/details/gt2omqcfllr.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2znxatyfz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozqsyjqf.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gt2roqbgsfv.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gt2alltafye.html

[R27] 算术展开
来源：http://dali.yvedp.cn/Article/details/gt2tijvdxoa.html

echo $((1 + 2 * 3))
来源：http://dali.cqqwz.cn/Article/details/gt2bykutkbf.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gt2bahpjgxu.html

echo "scale=2; 10/3" | bc
来源：http://dali.sxryk.cn/Article/details/gt2yhlzazwz.html

[R29] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gt2rzzwjrzy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tianlin.xyz/Article/details/gt2hxcsyknk.html

[R30] 函数返回状态码
来源：http://dali.hammf.cn/Article/details/gt2qcrinsnn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gt2avsqgqnm.html

[R31] 局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnxadyhn.html


<!-- 参考信息 -->