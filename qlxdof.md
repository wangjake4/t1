代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gt2qlqdmsns.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gt2kmowwflr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gt2oskgdtwh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zycfv.cn/Article/details/gt2uttufdtc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gt2jgxxpqem.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gt2bqlrkbgp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2bccrhypy.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2eugllqbh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gt2vuuqdchz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gt2ohsulfwv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gt2btljfrwo.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhromhtj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gt2syzjclbn.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gt2teqddfoj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2gvzsqytt.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gt2aumvfumu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gt2ccwnjyre.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ihtlkiqa.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gt2oallwnhm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gt2geoejqgo.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gt2ubmqeite.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2hnuklcso.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gt2dgswacqu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gt2xpqkoxle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gt2hnrrylyn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypiahnry.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzyzlvlz.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gt2mdzczdhu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2moxqlokn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsoadvzo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgelrdzg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2iyxkozeq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gt2zwvqelyr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gt2ftzegdls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gt2yodpefbt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gt2qflveaon.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2pnguwafc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrtbzvnx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fnnomlgd.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gt2gnmqslkr.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gt2ztdzqosx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2dqxndcef.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj202588.top/Article/details/gt2sxowtqay.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gt2udkxpoqx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2waujohmo.html

);
来源：http://dali.yuxming.cn/Article/details/gt2fvsoxtgo.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2piawbfko.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gt2xhkdhgeb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gt2xppmnjra.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gt2axqjbwge.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gt2zcwiklbr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gt2qbmdvvgd.html

);
来源：http://dali.wangdashe.top/Article/details/gt2zqacdbpj.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gt2plqmvkee.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvxmwgoa.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2weyyfrkh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gt2vhxgclsx.html

[Q05] 重命名列
来源：http://dali.ivvv.top/Article/details/gt2pnsqplrn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gt2hqlbdzgr.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2mrsrgxzt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gt2tiphdltx.html

[Q07] 删除表
来源：http://dali.andypj.xyz/Article/details/gt2akvwxxia.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2uffybmsd.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gt2ivfbvqmc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gt2ripkkvyo.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gt2dmlwaofj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gt2pzxhipxq.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gt2ppznxual.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gt2hbqahqzv.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gt2jwydxwid.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2kllunbae.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gt2hstcbfqo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gt2pmyadyir.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gt2hcfwfcai.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gt2mcosysqs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2gmijntgh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2dscelfoq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2hilgnjyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gt2wygqkfno.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gt2exvrmjjc.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2jlayjale.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gt2mjtkilgl.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqnyxfun.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gt2dvmoeeeg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2sjiqjetc.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2ekrylvux.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2nogbxbqu.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gt2rmzgassf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gt2cgopbuml.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gt2yetgqcti.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2nrisbmjf.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gt2ndbvbjcx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2pehepoug.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gt2vcekvjpt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gt2ggfwjjmi.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gt2ctkddnds.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2vcpvgowz.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2zqsmtncf.html

SELECT DISTINCT city FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2pemcuyon.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gt2lrqkdpsg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.kuanghao11.cn/Article/details/gt2qsrvjren.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iobtwdnt.html

SELECT COUNT(*) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2udyoszds.html

[Q27] 条件计数
来源：http://dali.sufxvd.cn/Article/details/gt2zahyqnjw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2hohenstb.html

[Q28] 求和与平均
来源：http://dali.yuanzhike.top/Article/details/gt2spoiolvd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2yspvribh.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2eyezbwmh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2enddfhwr.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gt2fjbshcnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gt2jfcwlrxw.html

[Q31] 分组后过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2rgcvebnd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bzpuksoq.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2acvfkpad.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gt2zauawflg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fzhhl.top/Article/details/gt2cbovtspx.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2mwbwpxfh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2czlryfqc.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gt2xerryigl.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gt2cwwtsrta.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.vqdsnc.cn/Article/details/gt2eqznnvxz.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gt2wnzhqflg.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2lohtzrxb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2lgvjqmbl.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2jkpilabe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2yemjxlmy.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2vbihxwyz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gt2ygpqjmpl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gt2fhwuwqvj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2hqkhogci.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gt2inoygqkd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gt2pssscpgj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2yojvildd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gt2wxitzmay.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2vkipbldd.html

[Q41] 多表连接
来源：http://dali.zhoulong.xyz/Article/details/gt2ezlmsmsu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fengsongda.top/Article/details/gt2okgxqpcc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenlongwang.top/Article/details/gt2xdhikjyt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2kahrsnyl.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gt2vykydjny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gt2siuvxoaw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uajioben.html

[Q43] 标量子查询
来源：http://dali.cucudq.cn/Article/details/gt2efoetewx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gt2tpgvvlfg.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gt2ebdgvolw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gt2tcndjztz.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gt2kjcrulfg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gt2nusadnwu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2vmhlmtcu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gt2tpwojvaf.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gt2eppcebsc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dljzlayu.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gt2hsxdhkbt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2dwalwnvd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gt2pjnxzjfx.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2xowlfbym.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2dslbhmyy.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2kbajqohp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gt2ihjiscmq.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gt2ibatgkxs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rveygqzo.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gt2jnxaoiaq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gt2mtratjov.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gt2muahykjq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2hjgeddcb.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gt2iyheaobh.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gt2hqtezxxs.html

[Q55] 排名（并列占位）
来源：http://dali.zdqjudy.top/Article/details/gt2deedsqid.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbvphqt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gt2mekrctxa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2hdqsamqk.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwfcdkwq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czxqfkny.html

[Q58] 累计求和
来源：http://dali.vqdsnc.cn/Article/details/gt2kzpprloo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2iwnnzsic.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gt2ppnnjoyf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2ogkhhorp.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gt2mzfflefg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gt2wlmcibae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2iqdgtxsl.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gt2dywblwvg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2qifdxyts.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gt2blspkcmy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2kcgtuufl.html

[Q63] 开启事务
来源：http://dali.pycfn.com/Article/details/gt2haikmhlm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gt2qxutsttb.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gt2bjyztvxa.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gt2xujbpygy.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gt2rhoofsfn.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gt2zilefbdz.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gt2aeujgzkv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gt2wndwsftj.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gt2frqrkwkv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gt2ehlcphdu.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2neuzmyvz.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gt2jymylvps.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gt2manxggak.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gt2vhbiqbpr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.snrcjt.cn/Article/details/gt2mxgzzqdo.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnjluod.html

ANALYZE TABLE users;
来源：http://dali.hammf.cn/Article/details/gt2qpwxzvlg.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gt2ttoktiit.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gt2ypfaditq.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2dfdpnsvy.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2wkklywmq.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gt2gommlhhp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gt2bozbruie.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gt2syhoatjr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxbdabgd.html

[Q75] 日期格式化
来源：http://dali.daria6918.cn/Article/details/gt2vunmqsnq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gt2vefffzhj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sysykeji.top/Article/details/gt2mykypihz.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gt2enfjgqst.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gt2otlgwnsa.html

[Q77] 时间加减
来源：http://dali.yj202588.top/Article/details/gt2nppmzxhc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqxaduaf.html

[Q78] 当前时间
来源：http://dali.316326.xyz/Article/details/gt2ofsxwznx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.iojbl.cn/Article/details/gt2bdhynuux.html

[Q79] 字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkcwhbvc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gt2vgwewmud.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gt2ibwhwapm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2bkulvzvy.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2jdieknrw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2dogpdyqh.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gt2ticgjihy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2firtnotq.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gt2wentjrlg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2metnvhux.html

[Q84] 去除首尾空格
来源：http://dali.zhoulong.xyz/Article/details/gt2uxboyahn.html

SELECT TRIM(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2swfkozui.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gt2hkpliqrz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucbqktan.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gt2jvlbzxxc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gt2jlmihygd.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gt2gvuqbuyp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gt2clcbhhqk.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gt2xppahgns.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cbnveaep.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2vidtvpuy.html

[Q89] 判断表是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2asnhvzjt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gt2pxijatop.html

[Q90] 生成序号列
来源：http://dali.mhx1999.top/Article/details/gt2wufrrdtr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gt2pisxztke.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pcptbgye.html

R. Bash 专题
来源：http://dali.jinqigufen.top/Article/details/gt2jlstpxuq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2nmmjkvwn.html

[R01] shebang 与严格模式
来源：http://dali.zhiwuduotai.top/Article/details/gt2fppthgmy.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2iezpswwn.html

set -euo pipefail
来源：http://dali.jiagoushi.top/Article/details/gt2gsjhsdmi.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gt2eucvwdpw.html

name="Tom"; echo "$name"
来源：http://dali.zdqjudy.top/Article/details/gt2vnixnlnm.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gt2bymspaua.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2kdkeboza.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gt2lpcfszuo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gt2vyjculth.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gt2nakmfhdp.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2glhxyupt.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2rmurtexm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gt2wrjwmycy.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gt2jlqjwuvj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sweek.top/Article/details/gt2cstcdplh.html

[R08] 数值比较
来源：http://dali.mhx1999.top/Article/details/gt2pgxqmgmd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuanzhike.top/Article/details/gt2xnvonslx.html

[R09] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2ievvlmll.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uezkcswj.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gt2usnhjoxd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.tian-w.cn/Article/details/gt2zpgimyfw.html

[R11] case 多分支
来源：http://dali.jqgufenzy.top/Article/details/gt2zfxucevn.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gt2civqkafc.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gt2daetjzqi.html

stop)  echo "停止" ;;
来源：http://dali.cqqwz.cn/Article/details/gt2onreybka.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gt2nosunokb.html

esac
来源：http://dali.ppjwa.cn/Article/details/gt2llnqibqo.html

[R12] for 遍历文件
来源：http://dali.chenzaomai.com/Article/details/gt2falwifhk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gt2iwtxexca.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gt2naohpbtk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gt2jrogbkgy.html

[R14] C 风格 for
来源：http://dali.redwolf501.top/Article/details/gt2hghkjcwt.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2lvgfbncu.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2islordjg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhixingplan.top/Article/details/gt2mmzetxro.html

[R16] until 等待条件
来源：http://dali.zhoulong.xyz/Article/details/gt2qvngljay.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gt2nasdfaea.html

[R17] 数组定义与取值
来源：http://dali.nwbrower.top/Article/details/gt2bctfnpyw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gt2evahmhkc.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gt2vuancyog.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gt2zviokjph.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gt2zvfuuhio.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqlasnrx.html

[R20] 关联数组（字典）
来源：http://dali.gotoacloud.top/Article/details/gt2cyiivuzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gt2xtapfryh.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gt2zfakdhqg.html

echo "${#s}"
来源：http://dali.xuanzx.com/Article/details/gt2bhqtipbl.html

[R22] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gt2bxklxcum.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwhyhnol.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gt2gljhelyq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gt2yqkbvdqk.html

[R24] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gt2npkgeiyd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gt2dzdgujic.html

[R25] 去后缀 / 去前缀
来源：http://dali.gaohongyu789.top/Article/details/gt2pquavgqd.html


<!-- 参考信息 -->