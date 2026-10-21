代发 wailian999

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtcraqtkcx.html

TS:   if (x == null) {}
来源：http://dali.tianlin.xyz/Article/details/gtorcusqlx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtwowafubp.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtswcdousn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtgsixjxqw.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtahydwihl.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtcjvhbjhs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtkiyypc.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtosdnkdoq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtuokuqchr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtwtoggyau.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcelszkry.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtswxwumis.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gtarxejmvn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtvfwccwfp.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gthnsuctnq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtdrqaomta.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gthgsgiohf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtzfwywuot.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtsccopndq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gttkbtpyjq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtgtdfuatu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtwxzuclil.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtdhjhomaq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gthimohfwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtqobjjnaj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgudviojm.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtevgdboxj.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtqawxrtmo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtchnxad.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gtlokonkuh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.quarkkingdee.top/Article/details/gtmkdcnwgk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258888.top/Article/details/gtpbadnlaj.html

);
来源：http://dali.hywenlv.cn/Article/details/gtgcymrvgm.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtlryymapt.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtkpqtnkay.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtpfcxxiue.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtisbxuzzj.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtuelyfosy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ybcxt.top/Article/details/gtlymbbrld.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtgmpyjawt.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtuoqesezi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtvavmnlje.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtubajfsnn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtphzdnbyv.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gtvisxomxw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtvowjzmkh.html

[Q06] 删除列
来源：http://dali.wangshuangyany.cn/Article/details/gtsaqewuzz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimicvudp.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtxedqjlqq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gttfovdsmp.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtmjiaoydi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtgtxecort.html

[Q09] 创建唯一索引
来源：http://dali.kuanghao11.cn/Article/details/gtybserzyd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gtgzpccihw.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtjyumytgn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtfolhrdhb.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtdccpiugn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gtbglqapma.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gttangwbhu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwocpuvs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpnjabfm.html

[Q13] 忽略重复插入
来源：http://dali.yangfankeji.com/Article/details/gtzgqmpooz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtaykegwer.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtsdszoikx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyakofyl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gtkokhjory.html

[Q15] 查询全部
来源：http://dali.yongpay.top/Article/details/gttfatpkuh.html

SELECT * FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtbxsugzbn.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtverweyht.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttnyegswr.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtjmhffltn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtpgztatid.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtrxaamztk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtsnqpxcws.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtnuwokwma.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtwtpirqyx.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtllmrhihm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtilmxetvo.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtfwzfhzrw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shzxlz.cn/Article/details/gtbzhyzhmk.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtmkgnawjd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtreikmpqp.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gtdblqewmg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xuanzx.com/Article/details/gtgikrtyiv.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gttmcydhei.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtikamdeiu.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gtmalhnzix.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fzhhl.top/Article/details/gtcbnpvyic.html

[Q26] 计数
来源：http://dali.hywenlv.cn/Article/details/gtsolewmjx.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtamuqfkkt.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtjufmqvxv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtjrwtobdn.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gtlsraanxn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtfqxzvfiy.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtchlrvmdj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtlifwebva.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtaxzrfeur.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtnabegbps.html

[Q31] 分组后过滤
来源：http://dali.yonumen.top/Article/details/gtzfefovkk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtfxtnuxtz.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtfvikdjva.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtovozerpk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gtdmhmuwyo.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtwalvhhiw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.mhx1999.top/Article/details/gtbxedkgpd.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtgarhvila.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtvrpinnur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cheryme.top/Article/details/gtmgyvtmvp.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtbuergxgk.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtpblmjdgj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjysnqpb.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtfpdplpml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtvqbvywoo.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gtyjlevtut.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbukhfni.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtfcaxjgcu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtkkipfzeb.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtpsupxbsz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtxbrhxqzg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtstsbadci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gtibwtflow.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtdyfvedbq.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtlvrdzpbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtfaaoqiet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtawxcguqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtvvdjvvck.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtifpcdgup.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtxujpsznu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbayeqfhr.html

[Q43] 标量子查询
来源：http://dali.pycfn.com/Article/details/gtnjdhlyav.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gtzmgdweck.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtqwcbwdqo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtmrgcvwey.html

[Q45] EXISTS 判断存在
来源：http://dali.0kj1m.cn/Article/details/gtbwdlbooj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtfpnxjwki.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhengqikj.top/Article/details/gtkwiooxoi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtqpckuh.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtdxgubnnq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtxwxuzpnw.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gtobmyyusy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtgqwagcyi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufvmoume.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtllhxjnwe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzknersjo.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtxrlaobem.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtdaebltee.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtapddsjzb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcrcwbad.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwislxhu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtxfznvdrr.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtsedmorue.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtqtsxdscn.html

[Q54] 清空表
来源：http://dali.jqgufenzy.top/Article/details/gtkzrwvqly.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtgdalnsfv.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtkxjvcwxb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtaysichfn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtlzejockm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtpsrksste.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtokgqxafk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgptgvks.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtisimwswz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtpnhjtvry.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtxapjaebe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtuwsdmecb.html

[Q60] 取上一行 / 下一行
来源：http://dali.ehwqpu.com/Article/details/gtyhlclgxb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yangfankeji.com/Article/details/gtmmyzzmdf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtstlydscw.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtyervuzmt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnsrensu.html

[Q62] 分组占比
来源：http://dali.jinqigufen.top/Article/details/gtrynuzunh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtvcnnxehy.html

[Q63] 开启事务
来源：http://dali.gzhubu.top/Article/details/gtxwedzfin.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gthxqwlwfj.html

[Q64] 提交事务
来源：http://dali.dashuyun.cn/Article/details/gtmjjsziep.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtuiwihitm.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtnseygumm.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtaivganzf.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtgwstygyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtxpclkohm.html

[Q67] 设置隔离级别
来源：http://dali.yangfankeji.com/Article/details/gtcsmiucld.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtxfmxmlak.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtugpydrmq.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtkfkwtfsm.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtwgzyndhb.html

[Q69] 查看执行计划
来源：http://dali.jlsjyb.cn/Article/details/gtprwgqblo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtwvefwmwt.html

[Q70] 更新统计信息
来源：http://dali.c1oappe.top/Article/details/gtabsmvgqa.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gteewgeqxm.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtdpvlbgud.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtazpatrcx.html

[Q72] 查看索引
来源：http://dali.gogol.net.cn/Article/details/gthteswtlg.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gthmudkxea.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtpgwvrjmt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtvwlzjplm.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtqfhdmwit.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtwgurmqdd.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gthvldssjo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtskoejkyw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtjhphroox.html

[Q76] 按天统计
来源：http://dali.zdqjudy.top/Article/details/gtnanfnrzm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gttvblzrnx.html

[Q77] 时间加减
来源：http://dali.shanyushiyangtech.top/Article/details/gttioffvxx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtkslbaznk.html

[Q78] 当前时间
来源：http://dali.sxryk.cn/Article/details/gtodtfgzqn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtctellatx.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtagmkprjr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daxiang520.top/Article/details/gtqeckbihh.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gteqffeuvr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtxtqeqkny.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtaqmxczrw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdqvzctzt.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtawjfymwb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkklektgx.html

[Q83] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtmqdsgmfh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbnsdamsy.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtbbvjosqa.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthaaaycaa.html

[Q85] 数值取整
来源：http://dali.hnqzz.top/Article/details/gtisifwald.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.wangshuangyany.cn/Article/details/gtqfilxlzj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gtmvglstgx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gtsoxkmpzn.html

[Q87] JSON 字段做条件
来源：http://dali.yj20258888.top/Article/details/gtqmmrmwfd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gthljwmnib.html

[Q88] 行转列（条件聚合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzeoeyib.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtvkhranhs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zycfv.cn/Article/details/gtclccaibt.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtglwbjufe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gogol.net.cn/Article/details/gtgyysgkua.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gtmbmqhdzf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gtodixdftp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtedkvzpmo.html

R. Bash 专题
来源：http://dali.zhongyouzk.top/Article/details/gtetwqeafs.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxszkvjmt.html

[R01] shebang 与严格模式
来源：http://dali.sufxvd.cn/Article/details/gtlmpzhepu.html

#!/usr/bin/env bash
来源：http://dali.jinghuilouyu.cn/Article/details/gtmddenjsh.html

set -euo pipefail
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpiywggy.html

[R02] 变量赋值与使用
来源：http://dali.shangyingyoupin.top/Article/details/gtcjifvutp.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtzwgqlija.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gttktpzskg.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gtewdqgcoc.html

[R04] 位置参数
来源：http://dali.jyoumei.cn/Article/details/gtgqmmwfyd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gtpwltyicd.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtibpikdky.html

name="${1:-default}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaovdnww.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtxrkoouwg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtodjgnhbp.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtkhydvnps.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuanzhike.top/Article/details/gtabgumqwx.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtuioxvirp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ivvv.top/Article/details/gtfacginjb.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtjdyqmadr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yonumen.top/Article/details/gtvkjefqin.html

[R10] 正则匹配
来源：http://dali.ybcxt.top/Article/details/gtrgqkzady.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gtkhhdctct.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtouaitoqi.html

case "$1" in
来源：http://dali.cashguo.top/Article/details/gtyaequrrz.html

start) echo "启动" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjbkytdw.html

stop)  echo "停止" ;;
来源：http://dali.gzhubu.top/Article/details/gtndtijlkv.html

*)     echo "未知命令" ;;
来源：http://dali.daria6918.cn/Article/details/gtessuvbbj.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtzklrrfne.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtcwsddxla.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtncvjycne.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtknvifxwt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gttgzzvwaz.html

[R14] C 风格 for
来源：http://dali.yj202588.top/Article/details/gttvcjddsr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gthonwesnc.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtrdqklnbk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtxnzndemw.html

[R16] until 等待条件
来源：http://dali.aibaodan.cn/Article/details/gtkvdfypoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtttirwvlh.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtkufolftu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.mhx1999.top/Article/details/gtlbfejyoe.html

[R18] 遍历数组
来源：http://dali.vqdsnc.cn/Article/details/gtzrgdzykh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcubgzzie.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtahqtsgzy.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtapwchzwp.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtztjuxznr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxuanxn.top/Article/details/gtaekrcarq.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtzndyteew.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtyueyhjoe.html

[R22] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtmbqgzaaf.html

echo "${s:0:5}"
来源：http://dali.pengpengdd.cyou/Article/details/gtblpuvwhv.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtcvfnittz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shangyingyoupin.top/Article/details/gtfchgggug.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtphbjmxvu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtlrbrtztt.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhixingplan.top/Article/details/gtdxfujnhk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jqgufenzy.top/Article/details/gtzndlomag.html

[R26] 命令替换
来源：http://dali.fengsongda.top/Article/details/gtqwdcthub.html

now=$(date +%F); echo "$now"
来源：http://dali.aizwys.cn/Article/details/gtxdddmpvq.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtqcfrcthq.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtgrlbawlg.html

[R28] 浮点运算
来源：http://dali.shangyingyoupin.top/Article/details/gtwpgvrmln.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gtbgbqkqok.html

[R29] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtmufmqssu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.dianchejie.cn/Article/details/gtihgkzxed.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtczmpkptz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yvedp.cn/Article/details/gttwcdmfne.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gtwqvejlxm.html


<!-- 参考信息 -->