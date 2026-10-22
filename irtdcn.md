代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtagqdiohs.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtoxgvahoc.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtnytzuirn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gteuewiwzb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gthuzdipmx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gttnyjzdfp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtiehygtka.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gtqqlkuibs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtrsckyqbu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtgxekgmxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtvbffctsg.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtfkoktyfc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gtlqjwzmrv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gtkjdblvmh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtdcuuebqx.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtbqnzilbr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gaohongyu789.top/Article/details/gtyhohudxo.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbptagtgf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrangmhhh.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsyibqoi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtbyomteub.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtpjjrdnfx.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gtdvsmgveu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtplgbceuw.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gttlogklik.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtrakbzqrd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtwqtpayam.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtkcxnlftk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gtpqzzweoa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtbslfhgok.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtvrhhzmlj.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtopysjmac.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtweplxkdq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gtpooqacix.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtjtrkyteo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtniewbdpv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtuepwvuzy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtccbkkkug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtqfsrvevu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtmofyjbrr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteftyabhe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtajgmhadz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthzkqcalg.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtsmftxnka.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gthppwwrnv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtembkevfn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtxqmckgkw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gtbcrtdwvz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtrzbrcvqp.html

);
来源：http://dali.zdqjudy.top/Article/details/gtmfropwtk.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtdbxufofs.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtqatszvlx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gttchlzgcq.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtbdqbcskv.html

amount DECIMAL(10, 2),
来源：http://dali.smart0.xyz/Article/details/gtaecvbxxo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fengsongda.top/Article/details/gtjmymwcws.html

);
来源：http://dali.xziqi.cn/Article/details/gtgecqxfxd.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtamsqtjjf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtiejjxcgt.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtgwztnftm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtkkumvfmw.html

[Q05] 重命名列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcfvccwt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdccgmji.html

[Q06] 删除列
来源：http://dali.sxryk.cn/Article/details/gtyzxkeisb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtxdmqirys.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtihljbucm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtrcnazrls.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gtjxszgpab.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtyykknizd.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtrrfugvgm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gthzstdkpw.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtjaouwujo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtktppnkpi.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtbfdhjtmj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtdhuuzleg.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtjsoukzqf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtpikjesav.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtrybbegzv.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gtvjfrfmwh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtvlyhnhtd.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtfwknjoll.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.haohaochexian.top/Article/details/gtnuxeaxrv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtrakitryo.html

[Q15] 查询全部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenkztjok.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtiefwgtyl.html

[Q16] 查询指定列
来源：http://dali.hnqzz.top/Article/details/gtpinbdeoa.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtownbmwat.html

[Q17] 条件查询
来源：http://dali.hnxiangtu.top/Article/details/gtwautncfg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtvpngomag.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gtrjjfsdts.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtldgkowed.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtfsdztzdv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtpbbcyzdj.html

[Q20] IN 列表
来源：http://dali.zhongyouzk.top/Article/details/gtoiwmdqst.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xylfe.cn/Article/details/gtcbfjtvmj.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtsyiumqfx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlnxhqxe.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtomomistj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.guowangkeji.top/Article/details/gtmlypuihl.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtfdafcnfq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtenawhmnw.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gtmcaqsfdn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeovdmnb.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtmayqkskv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtuchfaodw.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtkkljeskh.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtnzsobhsb.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtdycvulzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gtrwkwqecp.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihwwjgli.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtrdaajsqm.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtmvxzwhtn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtarkzzyvd.html

[Q30] 分组统计
来源：http://dali.shuidangran.top/Article/details/gtodjjoeqs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gttdojextt.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtdlcobrpa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtgmhgbtfr.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtejxyixts.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtxhmfxfwa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtbrjriewf.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtyxswsxsc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtlghpmwbh.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtvmpzsgkq.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtxduzvwxn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gtgfkmwzrt.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gttoiduhyg.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gteguwfnho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtovgobnrp.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtxpsoumri.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtukqrvksh.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtjswasndt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtbqigqyvs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gtqjszrayf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtzjvzkmju.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtclhqzznp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtktpggzpl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtkzkdvkqy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtqlhezcop.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtrkguuwws.html

[Q41] 多表连接
来源：http://dali.redwolf501.top/Article/details/gtbeabvqmm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtaflnynju.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtzgyycwap.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtvcihmhhe.html

[Q42] 连接条件附加过滤
来源：http://dali.snrcjt.cn/Article/details/gtvrispipn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gteetfibzs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtqyveynue.html

[Q43] 标量子查询
来源：http://dali.guowangkeji.top/Article/details/gtpmeukvni.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gotoacloud.top/Article/details/gtsvflawmz.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtcsfgffuq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gtagdcpbdt.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtokspldpe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fengsongda.top/Article/details/gtbpagvzul.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtfvpvjnrs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtuodflihi.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtgkgmphwn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gtiknjmqrc.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtcealiapy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagqehqwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tianlin.xyz/Article/details/gtzugqfexc.html

[Q49] 更新单行
来源：http://dali.hnxiangtu.top/Article/details/gthecxekkp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtqjvnhewf.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtooogjrbx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtilyqrigd.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtkmqoiydm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtgmyobalq.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtankxdbte.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtilpsgqye.html

[Q53] 按条件删除
来源：http://dali.feifeiyinyue.top/Article/details/gtwivumgye.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtolfpwydi.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtjtoyeygf.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtcqopyzbv.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtgvgqqcqr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtomvehjqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtofndgape.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtdgjugrjp.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtbfuxrtwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtmirxlsjk.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtxdyxoakp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtaxoamsjw.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtulxcvdxu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtrghtmmru.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznqggfgf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gtukbwlyeg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwjkuhmru.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtwtnvwcwk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gttjnjwkob.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtwhxqyaai.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtbuiqmwdl.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gtqothssoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenzaomai.com/Article/details/gtxnrkruel.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gtnkwpnqmd.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtkqpcpizu.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gttkasqukn.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtqowdfxsn.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtkqhpzzpl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtcynzbgnt.html

[Q67] 设置隔离级别
来源：http://dali.jiagoushi.top/Article/details/gtfdchpptv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtodgcgfvw.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtrvhysipe.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtvmslmaiz.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtlkkicrmt.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gttrhleamu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.feifeiyinyue.top/Article/details/gtbiityqpn.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtibltndlk.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtdcszylvy.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtpidvkpse.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtteeiimak.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtetktmexf.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtnpknsobz.html

[Q73] 查看表状态
来源：http://dali.feifeiyinyue.top/Article/details/gtubsjhgnh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sysykeji.top/Article/details/gtiylfhpzo.html

[Q74] 强制使用索引
来源：http://dali.zhongyouzk.top/Article/details/gtcuqkbxbq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.andypj.xyz/Article/details/gtachvtchi.html

[Q75] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtlcbsqxny.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtyrcqybus.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gtvnodgirq.html

[Q76] 按天统计
来源：http://dali.tanke756.top/Article/details/gtaglnocfk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtmvmdxqit.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtvdtdfqlf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.pengpengdd.cyou/Article/details/gttbdlnqtj.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtyiirfmbx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guannengcc.top/Article/details/gtqpqajcmd.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gthokbmiws.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtlyeklski.html

[Q80] 字符串截取
来源：http://dali.ivvv.top/Article/details/gtqxxndeqb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtobwpvekd.html

[Q81] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtlqbwobic.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuugwrybx.html

[Q82] 字符长度与字节长度
来源：http://dali.sweek.top/Article/details/gtnaqsqzly.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtyhqzihtc.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtpsodufks.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtinanrgwo.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtwxslvavi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtawfwtgdi.html

[Q85] 数值取整
来源：http://dali.daxiang520.top/Article/details/gtltpyhzja.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtbtduzoja.html

[Q86] 读取 JSON 字段
来源：http://dali.wangdashe.top/Article/details/gttrdbablb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtbbyificl.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gtnyncdtwi.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ydzc1.top/Article/details/gtopcwingd.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtgdypwntl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtqxxkdlau.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtqsugyjgy.html

[Q89] 判断表是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtbhwdrzth.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtzfprrrqp.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtlzmwwnoh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydduicao.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtnfzqyoiq.html

R. Bash 专题
来源：http://dali.cdnleiting.top/Article/details/gtwrrayvgg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxyatoxhw.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtbtehaqzt.html

#!/usr/bin/env bash
来源：http://dali.xuanzx.com/Article/details/gtrhwcgsjt.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtmqxiwvto.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtbanqjbqh.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtqxurvdks.html

[R03] 只读变量
来源：http://dali.gaohongyu789.top/Article/details/gtehezxvbn.html

readonly PI=3.14
来源：http://dali.cucudq.cn/Article/details/gtpltrjquf.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gtephecmrb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.fengsongda.top/Article/details/gtnzxsmkiu.html

[R05] 参数默认值
来源：http://dali.jiagoushi.top/Article/details/gtqcxtmmso.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtloboonmt.html

[R06] 判断命令是否存在
来源：http://dali.mhx1999.top/Article/details/gtocafdyeh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gttzymwllo.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtofzzyvuj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtjfhliprz.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtlephtzrb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmwsoevf.html

[R09] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtyrpzoqtk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tian-w.cn/Article/details/gthjzoodbz.html

[R10] 正则匹配
来源：http://dali.yuanzhike.top/Article/details/gtslbgmlhf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtggowhxlg.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtapggryfo.html

case "$1" in
来源：http://dali.yongpay.top/Article/details/gtcjhxsfkj.html

start) echo "启动" ;;
来源：http://dali.tanke756.top/Article/details/gtfgqkhhjs.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtebtrktzp.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtpxoyurkp.html

esac
来源：http://dali.haohaochexian.top/Article/details/gtmyqgnyre.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtudszhceq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtxlpsemso.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtlkyrbeev.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xylfe.cn/Article/details/gtutcgmtnb.html

[R14] C 风格 for
来源：http://dali.jinqigfzy.top/Article/details/gtmulwxgjy.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dianchejie.cn/Article/details/gtrqaigwhg.html

[R15] while 逐行读文件
来源：http://dali.jiagoushi.top/Article/details/gtcmjxwklv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtjspzugdw.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtoipblwfa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gterxorclz.html

[R17] 数组定义与取值
来源：http://dali.birdmap.top/Article/details/gtffsueylz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtxcqrvjsq.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gtphzlleka.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yonumen.top/Article/details/gtfzihwkno.html

[R19] 数组长度
来源：http://dali.havefunace.top/Article/details/gtdmuzeava.html

echo "${#arr[@]}"
来源：http://dali.svipenyu.cn/Article/details/gtfttrrcxc.html

[R20] 关联数组（字典）
来源：http://dali.fengsongda.top/Article/details/gtlmlxisly.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.316326.xyz/Article/details/gtnwvfkrlt.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtzlvaqctq.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtlttacguw.html

[R22] 截取子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwfpjnmq.html

echo "${s:0:5}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdvdvrtx.html

[R23] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gttptgugja.html


<!-- 参考信息 -->