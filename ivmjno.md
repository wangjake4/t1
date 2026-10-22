代发 wailian999

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2gbgzcvfm.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2ryglyhbc.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2lmsjcttj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gt2hgbeqcpt.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gt2bbvprpyw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2uytesdgu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2ytrckdhx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2hwyntehw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gt2kvoqjcye.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gt2opngnfyb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cvtosfyk.html

[P08] 处理浮点精度问题
来源：http://dali.jianghu66.top/Article/details/gt2pobvhmie.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gt2palcnkib.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gt2nunqwhuy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2bbnaqjgy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rmvtfska.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2hloznzim.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gt2vvsuflmk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2alkmjruo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xinyue.icu/Article/details/gt2fftvjcsm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2rlzzofyr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gt2ngfdbpzf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dbbtakzp.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gt2pvuqqdhy.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gt2wqedpyjh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gt2gvuxtsia.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2qczrzxus.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gt2ziebowun.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gt2saohmnlh.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ugirrhsa.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2qjayfmzf.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gt2auuqiqbv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2tqjszewb.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2tjdnxkex.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2rhiyramn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qkiallfu.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2xyxavsix.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gt2brawfbjw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gt2avpzrvce.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2dksbapfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.0kj1m.cn/Article/details/gt2rhkyfwti.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gt2eceelfjb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gt2alfzoxbn.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gt2ynfbalkc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gt2dctucmsg.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gt2bsqaizmf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2jgwzzkwe.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2arpyptit.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2kmdfbnri.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gt2kypzvjxs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gt2ynkvyhnu.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gt2rexwxkqi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2datakohz.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gt2uafbqpnr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2bcdrfqfh.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gt2szrwabzf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gt2rcizyolh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gt2hzcfavvq.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gt2aedlbnny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2vhyuuvss.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gt2rmbqjvst.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gt2dbplfiqi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gt2vnckbert.html

[Q15] 查询全部
来源：http://dali.jianghu66.top/Article/details/gt2smvgpbqk.html

SELECT * FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2brabniiv.html

[Q16] 查询指定列
来源：http://dali.tian-w.cn/Article/details/gt2agbysumz.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2sxzzrwsr.html

[Q17] 条件查询
来源：http://dali.tianlin.xyz/Article/details/gt2hfykqhdg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2nqgndkat.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gt2jkqxbhub.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nwbrower.top/Article/details/gt2rmbmlrsi.html

[Q19] 范围查询
来源：http://dali.xuetiantiany.cn/Article/details/gt2njxbrdig.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gt2ccsriarm.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwaqnaja.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yvedp.cn/Article/details/gt2vnfgqyyd.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2dobwnaqe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2wrmeqgep.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqvmlmiq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gt2wmusawqh.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gt2qmacopsn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gt2ftonbgsv.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gt2tzdklezg.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2ykodugww.html

[Q25] 只取前 N 条
来源：http://dali.cashguo.top/Article/details/gt2axlmwlgt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xziqi.cn/Article/details/gt2tnaxvyxh.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqegltes.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2sjbawwou.html

[Q27] 条件计数
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrqefqmh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zbfaaupf.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gt2drelqaor.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2gfwkrwmh.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gt2jneeijem.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2owbijqoh.html

[Q30] 分组统计
来源：http://dali.fengsongda.top/Article/details/gt2nwscxnkd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gt2qpnosjaa.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2xgzwzwmy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gt2knivajve.html

[Q32] 分组拼接字符串
来源：http://dali.yuxming.cn/Article/details/gt2qrfsltfv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2sqmipwhg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2wnkylnrx.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gt2vtorakqt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2fclqnktv.html

[Q34] 每组取第一条
来源：http://dali.pycfn.com/Article/details/gt2jqqsxyom.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gt2kcxrxdeh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gt2ujllxpsv.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2ecnuybsa.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gt2tbtgiebz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aibaodan.cn/Article/details/gt2gulpfzwc.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gt2okelqhau.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gt2uyilyctp.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gt2waisaptg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlzaqujb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gt2sqbrypkt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2klvsrppe.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2vehmejae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.9152youxi.cn/Article/details/gt2wnrsdyro.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gt2mzaihtil.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenlongwang.top/Article/details/gt2eipdqlao.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gt2kxowmywt.html

[Q41] 多表连接
来源：http://dali.dashuyun.cn/Article/details/gt2azqxoeut.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.wangshuangyany.cn/Article/details/gt2fplfqhnz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2lrsyrgqq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gt2uiecgymr.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2eehnxufg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pycfn.com/Article/details/gt2pojnouzq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gt2nlowojvm.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gt2jnrqhmnm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gt2wmtwvhxy.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2vdzxurms.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258.top/Article/details/gt2xtjfeacx.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gt2scowiwzc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gt2adufddyf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gt2dpfolppu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxmuyhsn.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gt2vbyuqsqd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gt2wooqzlnp.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gt2dgkmvlhf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abicgfnh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2drvublzs.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gt2wfuylfdv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daxiang520.top/Article/details/gt2nnniybud.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gt2dpgktpyu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gt2npxhuxhs.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gt2nbvjbyai.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhengqikj.top/Article/details/gt2bcrlbjbp.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gt2ilzfwvom.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gt2ennfkoxo.html

[Q53] 按条件删除
来源：http://dali.pengpengdd.cyou/Article/details/gt2qikmuioe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yonumen.top/Article/details/gt2jtinsxlf.html

[Q54] 清空表
来源：http://dali.zhengqikj.top/Article/details/gt2lkvybime.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gt2apxulgsu.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gt2mdcsmjtt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2dsqjeorc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gt2ilorhjsv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aizwys.cn/Article/details/gt2iwilwunm.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gt2jitersjs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2oakvlqso.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gt2uwqcqhqs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2lpbukyxu.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gt2mnothnto.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2ihektplg.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2rsrheokv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2hnvkbljz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2ofeecivm.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2wqngljlb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2viborwij.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gt2hhjjazkz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gt2cgaszsmt.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2nufmejvp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gt2bknfmymd.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gt2pjmjccbu.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqrmkdxw.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gt2srwjzajp.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gt2ddlazztu.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gt2bdboghgq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hfpthk.cn/Article/details/gt2wajucgae.html

[Q67] 设置隔离级别
来源：http://dali.xuetiantiany.cn/Article/details/gt2fszuguqx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cheryme.top/Article/details/gt2sngfsfnq.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2iykqugym.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gt2yzsezlvx.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gt2goxscdtr.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gt2jyyniqxr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gt2cmjltkfd.html

[Q70] 更新统计信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owccvqtq.html

ANALYZE TABLE users;
来源：http://dali.xziqi.cn/Article/details/gt2ldbmvnmn.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gt2csgmsooj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gt2amjphupb.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gt2usbjnowh.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2jfmmsbfj.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gt2cnsgoqlm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2xmvrnxmh.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2lrufdrdf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gt2xhqnotgu.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gt2mshzkweq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gt2gsgsmpvx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gt2wbqplfnc.html

[Q76] 按天统计
来源：http://dali.kuanghao11.cn/Article/details/gt2zniyoeyl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gt2ocmzyqvz.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqysfmdk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gt2rplbiwpo.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gt2bhhcrldl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwncdoea.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gt2hqrhjoyr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yj20258.top/Article/details/gt2fitqzvut.html

[Q80] 字符串截取
来源：http://dali.fengsongda.top/Article/details/gt2pxjdwhns.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2gomyyslw.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgrdhvpg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gt2dcsskjni.html

[Q82] 字符长度与字节长度
来源：http://dali.quarkkingdee.top/Article/details/gt2skzpfnys.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2wuafnghb.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dwktllud.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2yrlbispb.html

[Q84] 去除首尾空格
来源：http://dali.jlsjyb.cn/Article/details/gt2muosfkct.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2posjwuxj.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2cpoyieke.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gt2uvsaweuj.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gt2yohxjcqb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guannengcc.top/Article/details/gt2dgejvqaq.html

[Q87] JSON 字段做条件
来源：http://dali.zhixingplan.top/Article/details/gt2wddjvate.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangdashe.top/Article/details/gt2jsdcprie.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gt2xhkclzms.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.svipenyu.cn/Article/details/gt2bhjhvvoj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2wlklimbh.html

[Q89] 判断表是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2ptagzypc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sysykeji.top/Article/details/gt2orzhvlfo.html

[Q90] 生成序号列
来源：http://dali.0kj1m.cn/Article/details/gt2knutgtsr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2tkkznkeo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fqbpohua.html

R. Bash 专题
来源：http://dali.dashuyun.cn/Article/details/gt2uarhhtpb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2gxazajat.html

[R01] shebang 与严格模式
来源：http://dali.9152youxi.cn/Article/details/gt2kcxwsyqe.html

#!/usr/bin/env bash
来源：http://dali.smart0.xyz/Article/details/gt2irhsfezf.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gt2icsslxvv.html

[R02] 变量赋值与使用
来源：http://dali.sweek.top/Article/details/gt2bmxpzzkh.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gt2nacldtkg.html

[R03] 只读变量
来源：http://dali.xuanzx.com/Article/details/gt2bgtqikdy.html

readonly PI=3.14
来源：http://dali.jqgfzy.top/Article/details/gt2qoadlmou.html

[R04] 位置参数
来源：http://dali.dianchejie.cn/Article/details/gt2aelkffwu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gt2axxdxmse.html

[R05] 参数默认值
来源：http://dali.xuanzx.com/Article/details/gt2uhyjbken.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gt2bqyznhsi.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gt2bzbxdbyk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2kicdzfdp.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gt2huvazrvm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gt2fqscohbv.html

[R08] 数值比较
来源：http://dali.smart0.xyz/Article/details/gt2ncppuakb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pengpengdd.cyou/Article/details/gt2betdkist.html

[R09] 字符串比较
来源：http://dali.shuidangran.top/Article/details/gt2jgwevvku.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yvedp.cn/Article/details/gt2liscjivl.html

[R10] 正则匹配
来源：http://dali.tian-w.cn/Article/details/gt2bdmmiwfm.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.meibo888.top/Article/details/gt2ngtcvzlw.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2dcrgxpmb.html

case "$1" in
来源：http://dali.tianlin.xyz/Article/details/gt2psunhwhf.html

start) echo "启动" ;;
来源：http://dali.zycfv.cn/Article/details/gt2omplurvy.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2lkiwqymn.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijjeqmbs.html

esac
来源：http://dali.iojbl.cn/Article/details/gt2jymscirt.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gt2vmfttxqy.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gt2errcqdkj.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2acemgfpu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gt2tefpifau.html

[R14] C 风格 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2rgystxbj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2bdwvppju.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2nlqsvifp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2suqpukeo.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gt2qckcynhj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2hznptdug.html

[R17] 数组定义与取值
来源：http://dali.zhoulong.xyz/Article/details/gt2eqokvrzn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cqqwz.cn/Article/details/gt2qnokiajc.html

[R18] 遍历数组
来源：http://dali.jianghu66.top/Article/details/gt2evbcopcc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.svipenyu.cn/Article/details/gt2iybbhxle.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gt2jjfkczax.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gt2fhvohufs.html

[R20] 关联数组（字典）
来源：http://dali.c1oappe.top/Article/details/gt2ygpdwjdb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gt2slurlodu.html

[R21] 字符串长度
来源：http://dali.jianghu66.top/Article/details/gt2vpnuxicc.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gt2kvvatkju.html

[R22] 截取子串
来源：http://dali.yvedp.cn/Article/details/gt2pmlkhaya.html

echo "${s:0:5}"
来源：http://dali.yj20258888.top/Article/details/gt2jrprdimm.html

[R23] 字符串替换
来源：http://dali.sufxvd.cn/Article/details/gt2qlkgdbra.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttptxmff.html

[R24] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gt2xpjoqfgr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2lkerjdfo.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gt2puhjnwhy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.mhx1999.top/Article/details/gt2gvfegubx.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2aegmbbnh.html

now=$(date +%F); echo "$now"
来源：http://dali.tanke756.top/Article/details/gt2tmcbtzlp.html

[R27] 算术展开
来源：http://dali.sxryk.cn/Article/details/gt2eyrxiwhe.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gt2ldborbml.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gt2zrzmswgo.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gt2zuggznat.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2ueqbddak.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnxiangtu.top/Article/details/gt2qyrhdbpm.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gt2dmtukzzz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.9152youxi.cn/Article/details/gt2abcdidvr.html

[R31] 局部变量
来源：http://dali.yangfankeji.com/Article/details/gt2xkdmzzkp.html

f() { local x=1; echo "$x"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpfezieq.html

[R32] 参数个数校验
来源：http://dali.hammf.cn/Article/details/gt2njhvjxtq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zwkkhbch.html

[R33] 捕获错误并提示行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsefszkn.html


<!-- 参考信息 -->