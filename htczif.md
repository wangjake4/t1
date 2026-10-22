代发 wailian999

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gtlejjwzso.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gttoisdlry.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtkjewchjg.html

PHP:  if (empty($x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtlogbzyag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.andypj.xyz/Article/details/gtusipgaer.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtkkisyfer.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtepswmlzc.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gtxclcdkwx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtomeqntgc.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gtbfilhskx.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gtnqichjtz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtrtlvzucs.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gtlcmwyhmx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gteyulokic.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gteuccribh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gteproxiiw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xinyue.icu/Article/details/gtdyeujfto.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fengsongda.top/Article/details/gtvvavctnp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtlyrlijzx.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtoixzuhej.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gtfoikcdqj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtlwrlbilg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtkjufoynp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtccqxofmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtsgunqxke.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gtinahjegi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gthfmvkjeo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xylfe.cn/Article/details/gtpizkystx.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtibcogpgx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtqbsrcikp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtroeblbzb.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtcvixivgw.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtnjbznzjd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtwxfrteek.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtwjtdlceo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gtcyogxqxv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtgtbtuhso.html

);
来源：http://dali.nwbrower.top/Article/details/gtbflkoylb.html

[Q02] 创建带外键的表
来源：http://dali.yonumen.top/Article/details/gtslosxggb.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtbtqfwfgg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gttfiltpdj.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtnedmrltj.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpoywiap.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtexewrfgf.html

);
来源：http://dali.zhoulong.xyz/Article/details/gttrushtvi.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtvtbddiap.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtaannkgkd.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gturwvhpzr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gttvmpaawt.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtdomwkeuw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtoukzuvph.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtycbblvnp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtbadmygen.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtjcampjld.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhongyouzk.top/Article/details/gtarndkhpk.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetimzeqm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtojmnyjrj.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtocrfwxjs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtziqvhkcz.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnbavzbc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtktzpfthz.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gteziajdti.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtilxzwxap.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtwsftviwe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtiekymqau.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtmzzijnep.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtjejljchw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtegslcppi.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gtmhbrwabz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtbofyvfmj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtlhubvqzb.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtpmfvbuap.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gthtaxqdso.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtepfnmyzx.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtisdoxrsz.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtxhbqsghv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.haohaochexian.top/Article/details/gtyzvebiky.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtccnbmgdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gtonscoqkx.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtwonryykg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gteywnzowh.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtgwcnhkeb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gttzdbergz.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gttrenfzge.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtfjfjaten.html

[Q22] 排序
来源：http://dali.xinyue.icu/Article/details/gtnpgmkuni.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtywvljgfz.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtcgrphzvg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gthlrxyevl.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtbbqmwayc.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpemvmorh.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gthenuordg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtjrvfofvv.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gteqqwcbun.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtyiuuzxrs.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtfgsiiknw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtndvyvdkx.html

[Q28] 求和与平均
来源：http://dali.aizwys.cn/Article/details/gtznqkbbnk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtimwrteph.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gtyvcbugup.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtgeosjcze.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gthcgrpzxb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtlqeztfps.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtlrisgjcm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkbjwvsr.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtzymspebs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtzahaarry.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtbafwauxi.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtkzaspwct.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtmqsictqd.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gttmqzogig.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtdilcvkur.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtzuqxluce.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtoemjvkjw.html

[Q35] 内连接
来源：http://dali.chenjidiqi.icu/Article/details/gtiwechuox.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtkcfljifj.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmvvqpqw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gthmkpolma.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtkuvousoq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbpmqufh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gtgmqokokz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmmiabta.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gthwfdynzj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtmjhmzvyy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.andypj.xyz/Article/details/gtqqrxlamc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtoasparwg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtrdowpuoo.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtivxeuxlh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtvbjnzspo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtlwygbqiz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtojipntsv.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtjuofryjm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtjkngizoa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpbkqeao.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtdgxilemd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gtjdpafnrk.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtykfeofuz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xziqi.cn/Article/details/gtpughflfn.html

[Q45] EXISTS 判断存在
来源：http://dali.ppjwa.cn/Article/details/gtgjjhwiqs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtbzmgrmpi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtbujywuie.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcopsxpg.html

[Q47] 与平均值比较
来源：http://dali.hnqzz.top/Article/details/gttdtsmujz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtwruzyvdb.html

[Q48] CTE 公用表表达式
来源：http://dali.fzhhl.top/Article/details/gtcksshgee.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gttcrhedve.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtghcvlmth.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtxycmcngu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtjshekojy.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtnhxyadtg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gthsclohbi.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtumdlkalg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtycndbgcq.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtkndydlcx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgfzy.top/Article/details/gtlqvpswbc.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gtahgwutsw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtmspccvsx.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtkqxffecs.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtbgswpklw.html

[Q55] 排名（并列占位）
来源：http://dali.dashuyun.cn/Article/details/gtlvglfkqh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtjuihojwy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtbbmvvzcr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtrsxxvtqv.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtmjkltpns.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpivppzat.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtducrdhqh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtaeioccsx.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtiyqngbef.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtbbgujlwe.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtedkyrquf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtnixictew.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtgbmfdwxh.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtducntmob.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbwxvizky.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gtjhrzgsdu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtorbrqngl.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gtjfztanjx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtaokcqdsv.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtechyyagn.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtlkyidypw.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtfbvwjhsm.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtyfmyqryw.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyjihsle.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtcartfbaz.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrbnefgb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shuidangran.top/Article/details/gtmagxzkxp.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtaryvjxgr.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gtqgthjfus.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gtbugthvls.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gtsiwrulcj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.0kj1m.cn/Article/details/gtinsfyimc.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtlwgxfzms.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gtbqkdvhpz.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtkiqvxkgc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtgzbigtgn.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtlbnhgceb.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtpzqbptwj.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtqptiqbru.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.wangdashe.top/Article/details/gtixodawrt.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtgrtuajvh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gtmvmdlqcl.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gtuemlzauu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtryizkbla.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gtnwsxuiwx.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gttcktvpey.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gtyhzubbmh.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxcgduuv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtpbxluigk.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gtejhewzmg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtmrkydsoh.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gtwklugpws.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtcuacoqxl.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtgfvzqsan.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtikihfiok.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtkacddnkl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtpkksvobg.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtipmqvyic.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gttwsqwmhm.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gttatwplju.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtuothcetq.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtbpqvdefm.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwsvxwcw.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtlhzyxhyg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258.top/Article/details/gtinknctjt.html

[Q86] 读取 JSON 字段
来源：http://dali.snrcjt.cn/Article/details/gthtlsmjxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.mhx1999.top/Article/details/gtlmfsqtmg.html

[Q87] JSON 字段做条件
来源：http://dali.jianghu66.top/Article/details/gtbvsxrlmn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jiagoushi.top/Article/details/gtdgwswgiu.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtkjpfgjba.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtlffztwav.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gttekeoutb.html

[Q89] 判断表是否存在
来源：http://dali.cdnleiting.top/Article/details/gtsefbteac.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shuidangran.top/Article/details/gthqlxjics.html

[Q90] 生成序号列
来源：http://dali.jqgfzy.top/Article/details/gtlfkjjksq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtwncdnjkx.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtzufyyqpy.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gtjvddsmec.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxhpinusr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtuuoitcvn.html

#!/usr/bin/env bash
来源：http://dali.cucudq.cn/Article/details/gtwzbuukty.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtekhrdgye.html

[R02] 变量赋值与使用
来源：http://dali.bjfxy.top/Article/details/gtfbvabeym.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtbzydbdjc.html

[R03] 只读变量
来源：http://dali.yj20258.top/Article/details/gtmjlnxjmb.html

readonly PI=3.14
来源：http://dali.jqgufenzy.top/Article/details/gtlrhhexxv.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtebouuisy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuetiantiany.cn/Article/details/gteudckztp.html

[R05] 参数默认值
来源：http://dali.cqqwz.cn/Article/details/gtdyesfrpf.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtybproegf.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gtfhiqdrmv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtevhcpetc.html

[R07] if 判断文件
来源：http://dali.yuxming.cn/Article/details/gtqzzughjt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gogol.net.cn/Article/details/gtdalhdaya.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtveupbpfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gaohongyu789.top/Article/details/gtjclygici.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtaynqkfse.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtcbyashxs.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gtsqtpmviy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gtbylmiurh.html

[R11] case 多分支
来源：http://dali.quarkkingdee.top/Article/details/gtpbtpdykt.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtvgfvrdze.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtnoyqfckj.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gthxacgfoy.html

*)     echo "未知命令" ;;
来源：http://dali.quarkkingdee.top/Article/details/gthamwpats.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtxsvolneu.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtehfedqfd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtumcriwlj.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtthsuzwok.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtczmpylcw.html

[R14] C 风格 for
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkvdvxsx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtvjkksvoh.html

[R15] while 逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gtdmkagjds.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gtxkautqqc.html

[R16] until 等待条件
来源：http://dali.yuanzhike.top/Article/details/gtbmxfsxby.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtlaemgfpl.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtdflscmgh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhoulong.xyz/Article/details/gtpxvylekk.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtpgpybgkc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfslpjru.html

[R19] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtqcickdik.html

echo "${#arr[@]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrbpoiwy.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtybycaech.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.snrcjt.cn/Article/details/gtetzlanwy.html

[R21] 字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtjrzqekln.html

echo "${#s}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbszdcdjw.html

[R22] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gtgczszbcv.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtbmxkenmc.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtkwpblqrt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtzjfxaxsl.html

[R24] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtprypxsvo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gtzzppyide.html

[R25] 去后缀 / 去前缀
来源：http://dali.ybcxt.top/Article/details/gtmjbaqjuk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtailbntfb.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gtuyhczbhb.html

now=$(date +%F); echo "$now"
来源：http://dali.zycfv.cn/Article/details/gtmeoatdfs.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtherffjxx.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gtodudewsb.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtubsnpxna.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtehypdbwl.html

[R29] 定义函数
来源：http://dali.meibo888.top/Article/details/gtshxawhkp.html


<!-- 参考信息 -->