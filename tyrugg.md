代发 wailian999

[P05] 判断两个对象内容是否相等
来源：http://dali.snrcjt.cn/Article/details/gtbbjlqima.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtjjwitcwy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtdlqhkqua.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtgsopodwv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtwfcbecxb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gtmofumgnn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchlkebel.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtioyyozdf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtluztqiva.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtpqwxjdml.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtpwzwkpkr.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuhderwit.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtrzjyosgm.html

TS:   if (x == null) {}
来源：http://dali.dianchejie.cn/Article/details/gtfipflxzi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoeymscdi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtyhjfzzbo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gthdccowji.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtgcxvfvwh.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkewapmy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtxugtetdl.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gtwmazhzul.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtzkxzneyc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtpvesmwxf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtcqagbuwr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtoobezoyr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtuowsjmzi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtyggvchmh.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gtylwmikzv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtvfisdkmi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.snrcjt.cn/Article/details/gtbhudjfed.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtvnciixqu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtvoplwfwj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtajqeqebo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtzikmyyeg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtgpfkqiba.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtrdtcfodn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtplvejmje.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtixyqnqxy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtfjcrdgtc.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtxhalmdnx.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfscpmxg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtjjydswwu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtbcjxcoou.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtvxpjpqqh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gtcvnvyczt.html

);
来源：http://dali.nwbrower.top/Article/details/gtkaocqncn.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtdbjrejfu.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtuagszlgt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtgfaoxajn.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtovuzfsju.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxphlxsy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtyoyolfmo.html

);
来源：http://dali.9152youxi.cn/Article/details/gtnuzdtold.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtbppvdehr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xziqi.cn/Article/details/gtpzqbklzl.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gtmdwdxesk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtdewqctpi.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkohzsmwb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtlevamqhv.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtctnolplf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xinyue.icu/Article/details/gtmopvdrbo.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtfkhdaubn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.meibo888.top/Article/details/gtsyvwrsqi.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtnelzwnqe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtxworooqi.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gtjzwnjngr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutyksxoa.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gtkaeagpja.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtywzwgljh.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqznnypr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtmdpohtgs.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxpikxnn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtlfgvmzgp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtrfqpnkyw.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gtuzkhrnst.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtvgyckywb.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gtzxwqfkgh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtplvobsje.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtauipyeva.html

[Q15] 查询全部
来源：http://dali.feifeiyinyue.top/Article/details/gthjhvjaoc.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgzufufge.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtbxrzemtm.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gttdtphlap.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtivfmwcms.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gthektyslu.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtxizcptkp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.svipenyu.cn/Article/details/gtlzbcsevp.html

[Q19] 范围查询
来源：http://dali.guowangkeji.top/Article/details/gtfnjufchu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtcwxcyfiy.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtjnbqgupq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtmcbullkx.html

[Q21] 空值判断
来源：http://dali.zhiwuduotai.top/Article/details/gtshsrpxyb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtyxgkpiaw.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gtcsjqixel.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gthhmgiorg.html

[Q23] 分页
来源：http://dali.vqdsnc.cn/Article/details/gtrtxxkxtn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtyaosmphm.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtisgiymac.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtyunodted.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gtmodsfwgp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtcxyrxqia.html

[Q26] 计数
来源：http://dali.chenlongwang.top/Article/details/gtnxvbsacy.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnkhzbnxs.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtsfltzfls.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtidpnhjwf.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gtezbsedqk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtjbgmpxef.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtrdsolbxp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gthbxpoffk.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzwihjuv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtwwgmiwja.html

[Q31] 分组后过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteabpjzrw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtigzwpbed.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtubwryjab.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtnzhzzxpp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtaqauctxv.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrwnbuxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtzigypdeq.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtlnswyaud.html

SELECT * FROM (
来源：http://dali.ybcxt.top/Article/details/gtqnzzmmhp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtbfznfmaz.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtkrsetstw.html

[Q35] 内连接
来源：http://dali.nanxinkj.top/Article/details/gtxuzzonkh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtedqibjlm.html

[Q36] 左连接
来源：http://dali.yanxiufei.cn/Article/details/gtomnwugya.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjqxpqav.html

[Q37] 右连接
来源：http://dali.ehwqpu.com/Article/details/gtyrqpeybk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtfkykctob.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtxzrhuegq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtlwdjdhjd.html

[Q39] 自连接（查上下级）
来源：http://dali.daria6918.cn/Article/details/gtnvshqamk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gzhubu.top/Article/details/gtbjaduuyd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtjqipsqtb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhixingplan.top/Article/details/gtsprjvzlq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkgupckh.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtzzmojjwe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gthjpelkmq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtgniezzeh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtmabsdocp.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfjsvxlp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsmhhjnc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinghuilouyu.cn/Article/details/gtamkzgvdi.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtnqvtnsfd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtatzlkthf.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtdrfpgsos.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtacvjpnem.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtldtcitfn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtxhtyqoqd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtxsqifqzx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhklqtmh.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gthbvkjdkx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtficffujf.html

[Q48] CTE 公用表表达式
来源：http://dali.jiagoushi.top/Article/details/gtmqaibqcy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhixingplan.top/Article/details/gtzllhlldt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtfcftzlcw.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtjvbpamou.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gthfcmdmdg.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtoimztdca.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtmtenaasq.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gthjxknnhp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtodzsmryj.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gtygayacer.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtzrfnvgky.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtqollwheu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtzrlqspnp.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gttyfltsjt.html

TRUNCATE TABLE logs;
来源：http://dali.daria6918.cn/Article/details/gtqmijjedv.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtaovcxmdl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtkmrnbiqq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cheryme.top/Article/details/gtfferyswt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtjiwwbnvh.html

[Q57] 行号
来源：http://dali.shuidangran.top/Article/details/gtlvewsqnh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtovbkguiw.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtilxxpwva.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnpfvfrm.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gtkompxfnj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtjfqnzalm.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtypmihvoy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtzahpuyht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gttvzioamy.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtncowcbsj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtestjrsnk.html

[Q62] 分组占比
来源：http://dali.jqgufenzy.top/Article/details/gtcfvluwif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gttzfjvrkn.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gttlntrtlc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtrwikdkuz.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gtpxbmbqxu.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gtxoreqzjx.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtyejseved.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtzofhfhcy.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gttvmygmnq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhongyouzk.top/Article/details/gtggyvgete.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gtudypazoa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gthcrfhwff.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gttkynkbqb.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gtilsraktu.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gtuhzmlhfe.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gttdmrveia.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtfsnmubam.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtgokqowvl.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtgkfbcqgd.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtatrjvhim.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtehrmcgzm.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gthtwyfqba.html

SHOW INDEX FROM users;
来源：http://dali.sysykeji.top/Article/details/gtbgqyxzxn.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gtczdnfiia.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtinrutmra.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtwzbyfzmo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gogol.net.cn/Article/details/gtoadxwbbl.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtjqoqthia.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtwjspcuus.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtmvpjkfpt.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtnpxpqamc.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sxryk.cn/Article/details/gtcxrvyock.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtlaoomhhd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jqgufenzy.top/Article/details/gttkbvflrh.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtahkccgfv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtmzzgaxss.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtrmutdcku.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtieyezjga.html

[Q80] 字符串截取
来源：http://dali.cdnleiting.top/Article/details/gtgjyktrpf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtmdzkuroh.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtfczmjqec.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtwltknkos.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtmpogqlbl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtxwbsebta.html

[Q83] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtngpisjuz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtgnipfyfj.html

[Q84] 去除首尾空格
来源：http://dali.jyoumei.cn/Article/details/gthizdjwvp.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtxovacsxr.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxezidgn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.feifeiyinyue.top/Article/details/gtlnbnquun.html

[Q86] 读取 JSON 字段
来源：http://dali.jyoumei.cn/Article/details/gtmhabbtfc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtxhnualpg.html

[Q87] JSON 字段做条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzxsypxn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtckhxfztu.html

[Q88] 行转列（条件聚合）
来源：http://dali.daria6918.cn/Article/details/gtingqbykm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gttenvdamj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtmaeokuvi.html

[Q89] 判断表是否存在
来源：http://dali.tianlin.xyz/Article/details/gtsiolkhsg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlosfyzkj.html

[Q90] 生成序号列
来源：http://dali.fzhhl.top/Article/details/gthhpnxdzn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hammf.cn/Article/details/gtvvbgislr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcafwbtez.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtczihbaem.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttghlbvqn.html

[R01] shebang 与严格模式
来源：http://dali.xuetiantiany.cn/Article/details/gtesgrlwrr.html

#!/usr/bin/env bash
来源：http://dali.ybcxt.top/Article/details/gtjypgdfkf.html

set -euo pipefail
来源：http://dali.yvedp.cn/Article/details/gteixctfec.html

[R02] 变量赋值与使用
来源：http://dali.316326.xyz/Article/details/gtfrpxvzax.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtzrikzyaf.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtttuwxgts.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gteptcdddr.html

[R04] 位置参数
来源：http://dali.daxiang520.top/Article/details/gtehqxuqmf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtuwlrgrcf.html

[R05] 参数默认值
来源：http://dali.hnxiangtu.top/Article/details/gtsxxsbojq.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtogzxvlod.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtnscsllzw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtievlovwd.html

[R07] if 判断文件
来源：http://dali.yanxiufei.cn/Article/details/gtwfnsdsxx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtegoeyfqa.html

[R08] 数值比较
来源：http://dali.gzhubu.top/Article/details/gtqftrofeu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gogol.net.cn/Article/details/gtbsggfxgm.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtlejgnhmk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtqshgfedk.html

[R10] 正则匹配
来源：http://dali.snrcjt.cn/Article/details/gtgebljpts.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jianghu66.top/Article/details/gtdnqppjub.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gtzymxtvxk.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtqqiwvfux.html

start) echo "启动" ;;
来源：http://dali.svipenyu.cn/Article/details/gtoqufdcjn.html

stop)  echo "停止" ;;
来源：http://dali.shuidangran.top/Article/details/gtjnxiilsy.html

*)     echo "未知命令" ;;
来源：http://dali.mhx1999.top/Article/details/gtxhxjzpyr.html

esac
来源：http://dali.ivvv.top/Article/details/gtvvlgqzus.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gthtpbsjbh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtclwittak.html

[R13] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtnhcdblvj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtyqubktqh.html

[R14] C 风格 for
来源：http://dali.snrcjt.cn/Article/details/gtriudyttz.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkjkheyjv.html

[R15] while 逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtjczsbblf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnqzz.top/Article/details/gtazjiycbg.html

[R16] until 等待条件
来源：http://dali.meibo888.top/Article/details/gtzflpyawo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.birdmap.top/Article/details/gtxvgdnlux.html

[R17] 数组定义与取值
来源：http://dali.pengpengdd.cyou/Article/details/gtkrricfpj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.c1oappe.top/Article/details/gtwpwxmezk.html

[R18] 遍历数组
来源：http://dali.ehwqpu.com/Article/details/gtcvpzybln.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gthhsczhbd.html

[R19] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gtznfmpzif.html

echo "${#arr[@]}"
来源：http://dali.cucudq.cn/Article/details/gtsxdrxlxh.html

[R20] 关联数组（字典）
来源：http://dali.hysaishi.cn/Article/details/gtjpxhgnzo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtzqfgykse.html

[R21] 字符串长度
来源：http://dali.mhx1999.top/Article/details/gtypfbxthh.html

echo "${#s}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdymsgrxm.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtstnbotwi.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtlmgdezpo.html

[R23] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtpgwoitth.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtygkkeckr.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtffpacrnq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gthprtpvpp.html

[R25] 去后缀 / 去前缀
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsffmvfn.html


<!-- 参考信息 -->