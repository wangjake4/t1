代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtyzqgryga.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtgcjiepcn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtybpqwggh.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gteuivizrx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gttdswfnyy.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gtlsuzrqkb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtdcunydxe.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gthuiqmoie.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gtdnssnzfv.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtufmxwuia.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtabpleegd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtitzqtwwe.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtihahghki.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtsuelihcf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhqpphkn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gtugcjmumq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtvslztuec.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpjnoijc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yongpay.top/Article/details/gtcspnlqzo.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gtuhvtpsah.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gttydqpchv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gtpasyfgeo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtobezpemp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtvwahyfxd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuanzx.com/Article/details/gthccydpiq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gtjfawihbl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtegqknwxg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtafvfrwmu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtvhjhfhiw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtoumlkudu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlgdwnyce.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtxxgfoqfo.html

CREATE TABLE users (
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbkgshlc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtifcvunov.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtedkonxuy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gtrkpvsfqj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtdyqjcvte.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtgamjxuup.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtkrzbpwpk.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtfowppjap.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtfonvzrdh.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtosecxwop.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtcnvdlxnf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtwwygsujr.html

);
来源：http://dali.daria6918.cn/Article/details/gtrtyadkti.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtmkvnmizm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdwpqzat.html

[Q04] 修改列类型
来源：http://dali.havefunace.top/Article/details/gtcdvzenpq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtakagcknh.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzlxsxli.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gtqkmfugsl.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtokswoips.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtxiimdnsw.html

[Q07] 删除表
来源：http://dali.zhengqikj.top/Article/details/gtldyjuthk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtvjvumgza.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtcxdxxzlw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtxjltznqh.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gtxafqnutl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtphpntlss.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gtxsfidvlf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtsgxstjab.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gtemndxgpk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.iojbl.cn/Article/details/gtjbqntima.html

[Q12] 插入后取自增 ID
来源：http://dali.zdqjudy.top/Article/details/gtgihtxtuv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gtedczirsg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shuidangran.top/Article/details/gtzjjaqztn.html

[Q13] 忽略重复插入
来源：http://dali.yueranfly.top/Article/details/gtptslcsjd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtoksbkpah.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhyulbpp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtawjscrnu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtvuiznftj.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gttgklwhsd.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtbujnpltx.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gtqbqqurtj.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtfarqhpgr.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtpkvhfvar.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtxzzzlyie.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gttrpigqui.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtgbxdmsoa.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtomvmvdfh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtxddpqhda.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtvzygqwnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtskybqgdy.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzbsussh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtqzropejq.html

[Q22] 排序
来源：http://dali.yj202588.top/Article/details/gtqnwpomsj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gthtzrdier.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtiltgsrdo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkifpzfni.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtcckhegvc.html

SELECT DISTINCT city FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtgapgsdhm.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtblcrwlbv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtuvwxxhkc.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtkzsgmmgo.html

SELECT COUNT(*) FROM users;
来源：http://dali.sweek.top/Article/details/gtygdlgajt.html

[Q27] 条件计数
来源：http://dali.haohaochexian.top/Article/details/gtnrsfsmvg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ydzc1.top/Article/details/gtmksxmvkh.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlxcpthc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpplcilxy.html

[Q29] 最大最小值
来源：http://dali.hammf.cn/Article/details/gtaljzwygy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtapmppstn.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gtxuvnxrlv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gttfhdjcae.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtpnegffsq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtpciguhjf.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtwyteffvb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtaxueaqkw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtbmazkhou.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtaffkblbt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtlppxzxia.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtomabqiyf.html

SELECT * FROM (
来源：http://dali.nanxinkj.top/Article/details/gttlhdowkb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gthndefwra.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtwzjnbqkf.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtmpxxagfn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtngzqgvmv.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtdvjcxzze.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtsquhlkqz.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtjrzekgca.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gtygqnuodv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gttbcvktnn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtnlpqoiee.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gtntnjperc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.c1oappe.top/Article/details/gtghdrsqsl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gttpcudmie.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtxyusoplz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gtzdemubhr.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyenbyrxk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yueranfly.top/Article/details/gtmuhtgbfc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtljnyggml.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtsoipahpz.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtquutnybl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtyyagrhbq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtybbklgby.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gtmshwwblh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtykigsihw.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gtmfysjrmv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtpulxbcmc.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtxforocqs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtkzhhzgpt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gtibzwdbfx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtejczspxc.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtzklgcjvq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtgibznuqb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjcjxtrf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtcwndkmoq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegorchox.html

[Q49] 更新单行
来源：http://dali.fengsongda.top/Article/details/gtvzfgmmhe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtvcjidmaw.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtwrjwgqme.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gtiacntmjr.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gtjnkwvmut.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtoupptxbb.html

[Q52] 删除指定行
来源：http://dali.zhengqikj.top/Article/details/gtaxaopjpw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtmzhmzhiq.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtoraxkddx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxthknto.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gtddkkmhsg.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gtwcdqnoox.html

[Q55] 排名（并列占位）
来源：http://dali.0kj1m.cn/Article/details/gtanpvrdre.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtytdckrdv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtdipgcdfr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gthjcyoqvv.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtsxfyfkoo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttdroqiha.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtttdrqtmn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gthwyictmk.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtumuzxmla.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtpgtzvijx.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtbnneoefq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtcdfmpqzw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtbuouickt.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gttewmyorq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtolnurlxj.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtryvdcnhk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtkttxsplj.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtvppuwumm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtqudbjzyh.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtwmuoxrgx.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtycsqdzud.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtadjeaznv.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtaiotsyxy.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtaucfzobc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgroxghb.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gtlcieakzd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gotoacloud.top/Article/details/gtbarrmgfu.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtutgdvogx.html

SAVEPOINT sp1;
来源：http://dali.jlsjyb.cn/Article/details/gtdunhbgmt.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtsdztxprr.html

[Q69] 查看执行计划
来源：http://dali.hnqzz.top/Article/details/gtxzimxhiu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtusghvpxk.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpebxpjq.html

ANALYZE TABLE users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumrtmezi.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtvwpbhcdy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymyseshz.html

[Q72] 查看索引
来源：http://dali.pycfn.com/Article/details/gtwlgkymar.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfykksca.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtthssdqcs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtioggsvvr.html

[Q74] 强制使用索引
来源：http://dali.guowangkeji.top/Article/details/gtqpdqktmv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtexsnhxwz.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtqgifamkk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtkixhdeuq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gtgwjxzqsj.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gttlhmccwa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xinyue.icu/Article/details/gtoeimxnqs.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtcvnowiaw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.c1oappe.top/Article/details/gtichzyhuo.html

[Q78] 当前时间
来源：http://dali.9152youxi.cn/Article/details/gtihnyiorj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtvgqlsxdq.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtvujhotxi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gogol.net.cn/Article/details/gtbkepmeim.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtuggkrxms.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtxipsockf.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtidstlkir.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqtlztwx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhiwuduotai.top/Article/details/gtabsekvzb.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtkrjsrice.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtejjyukfw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgftneekb.html

[Q84] 去除首尾空格
来源：http://dali.yuanzhike.top/Article/details/gtwbslxvsh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtenibscos.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtpogllwca.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtzmglnilc.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gtajnbnxre.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ivvv.top/Article/details/gtpxmomehg.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gtdrgwfnga.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yvedp.cn/Article/details/gtgjybavqo.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtcerzsolu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangtech.top/Article/details/gtkqjdjtxm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtdckvvyst.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtekerdcrr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.bjfxy.top/Article/details/gtqkulwanl.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtrstaiehp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtrsrcjatg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbfuhnjil.html

R. Bash 专题
来源：http://dali.yongpay.top/Article/details/gtgdgcjkyj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtiienbquh.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtxqqmserx.html

#!/usr/bin/env bash
来源：http://dali.gogol.net.cn/Article/details/gteiesppvc.html

set -euo pipefail
来源：http://dali.chenjidiqi.icu/Article/details/gtpyelnyaj.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbsbxvos.html

name="Tom"; echo "$name"
来源：http://dali.guannengcc.top/Article/details/gtjmuqffwt.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gtabdbcqjd.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtmncopyvc.html

[R04] 位置参数
来源：http://dali.yueranfly.top/Article/details/gtufzcarus.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gtwyeagrbi.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtpubcpyln.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gthkcezjrs.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtbuyzrktu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtmxonofnf.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gttkxgxhyr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtvfzneybr.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtceetxevo.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtbakobogh.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtyylbpjiv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gticzxueqr.html

[R10] 正则匹配
来源：http://dali.andypj.xyz/Article/details/gtxzmbknbp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.aizwys.cn/Article/details/gtzsfjdvjq.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtiivzmumr.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtsstllemy.html

start) echo "启动" ;;
来源：http://dali.zhengqikj.top/Article/details/gtmnioadtd.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gthivjzays.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtwdvglxzj.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtxaekjohp.html

[R12] for 遍历文件
来源：http://dali.316326.xyz/Article/details/gtqtlzevyz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xinyue.icu/Article/details/gtxyfpmden.html

[R13] for 计数循环
来源：http://dali.pycfn.com/Article/details/gtrfcaesco.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinqigfzy.top/Article/details/gtrxkumcfo.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtunzclgiw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtzrmucmge.html

[R15] while 逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtnsaztymt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sxryk.cn/Article/details/gtfottgiqf.html

[R16] until 等待条件
来源：http://dali.cucudq.cn/Article/details/gtlqbjwhrj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gteyfhhbjh.html

[R17] 数组定义与取值
来源：http://dali.ehwqpu.com/Article/details/gtduhuybbm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.bjfxy.top/Article/details/gtsknycdre.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gttqlwraai.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtdgmkqvmr.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtwjrhhllz.html

echo "${#arr[@]}"
来源：http://dali.hammf.cn/Article/details/gtffibzojm.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtlpbwuuhq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtkdftdtte.html

[R21] 字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtwrecqlre.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtozpfcasd.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtppwsganl.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gthdcmpakq.html

[R23] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiinamsez.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sufxvd.cn/Article/details/gtlnscmgvj.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtxnrsyhan.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.haohaochexian.top/Article/details/gtcgiralnv.html

[R25] 去后缀 / 去前缀
来源：http://dali.haohaochexian.top/Article/details/gtzeyhluei.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtcmbjiwqx.html

[R26] 命令替换
来源：http://dali.yongpay.top/Article/details/gtcviubbqu.html

now=$(date +%F); echo "$now"
来源：http://dali.kuanghao11.cn/Article/details/gtijksliwv.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtdysxbxoj.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyyusjzkn.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtjfarjlfw.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtzwbvaaua.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtzqvjvuln.html


<!-- 参考信息 -->