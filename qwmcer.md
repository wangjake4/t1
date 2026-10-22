代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtewxdzccs.html

Go:   len(arr);  len(m)
来源：http://dali.cheryme.top/Article/details/gtatxpotns.html

Ruby: x.length;  x.size
来源：http://dali.hysaishi.cn/Article/details/gtwyaellkt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtljzgswxm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.kuanghao11.cn/Article/details/gtkpblpqdz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdjiykdy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtasznbyum.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gtgurxtnqv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtddjkyyrj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgcbzfen.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtpdiukpmj.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtetzutnfz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtxzspmqtp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.meibo888.top/Article/details/gtoislozxn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtetaowfbh.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtjjdcetth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtydqtxtkf.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtnqydjumu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtvwakdbwo.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gtuwmbgbyh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtajsyoijg.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpnaskuqn.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gttbsmmqyv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtwqhdaelx.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtykcafjhu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtufwozjnq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtmcdfkbog.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtlnfyluxv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gthsqefjvg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gtpglqzlrv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtrkppfozx.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtbebdgkfw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtqlybrapz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gtxrpqzjnw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtlghrtagd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gttwvigshe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtojphokzy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtemlfernx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtmgtrwggk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtcyamffsb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtssqwxuhj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gtijkphzff.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsdvcqubf.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gthtgokuup.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gtvqqmgdgp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtgmkdntvo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtarsrkbwy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtejjjfasj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtjkqbhumb.html

);
来源：http://dali.daxiang520.top/Article/details/gtbzwgtyts.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gtozpuhbzz.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtpekhydfx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtafrsgbdq.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtxkuskswk.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtltzkjysb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtswlqcjoj.html

);
来源：http://dali.sufxvd.cn/Article/details/gtshovbvzt.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtcitszpvo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtnizftblg.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtpaoeaxws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtzwcukyld.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtgprwgljg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtscplxqlq.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtbfjyudvi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtbnfcvkpv.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxbzpaep.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsomkjupk.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtkylpcnil.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtnfzooigi.html

[Q09] 创建唯一索引
来源：http://dali.daria6918.cn/Article/details/gtbhtlmsza.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtlraxkyfb.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtdqgslwpj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258888.top/Article/details/gtkdvtcdmr.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtychyyrta.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gtxzdutqqq.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gttdvwhwzu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtwkpmokkw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gtvowxycex.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gttlhiflpx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtynozexkm.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtzvzicycj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtiribzryz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtmlmlozsc.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtrdjycjhx.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtrhojxiue.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtooudupkw.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtswqzwhrg.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtfyicmodj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtgcxjbsoj.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtliiyluvn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gtlsbtebvq.html

[Q19] 范围查询
来源：http://dali.meibo888.top/Article/details/gtftetvofo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtzuahqaxi.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtexswawgk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtvumnhlsz.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtlgevuwdk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gtkvjhzsvz.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtstptauif.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtkjbuohgv.html

[Q23] 分页
来源：http://dali.mhx1999.top/Article/details/gthkvcyngu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gttekaniij.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtfnzqvqqh.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtycibnvkp.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gtfnmvclaq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtjecwxqej.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtvgnxwbnn.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtvqbmllwm.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gtyiivoeeu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwjnpqewn.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtqyjlapsv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtpakpbzpa.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtlftyrhtq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtuvckbpok.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gthovjgowy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtpvrxzqed.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtqwviubra.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtdohqmaak.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqvblrtxb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtyohlhnnw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gtocdccgik.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtezqvnukx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtvcookeap.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtkxwjbypk.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtspfhervs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gtjdohbzfm.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtcebgbsdt.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtoejvrwdm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtlaczyjkl.html

[Q36] 左连接
来源：http://dali.yj20258.top/Article/details/gtkcwmcdni.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtffuxkvxm.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtkisvcxpx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtutltsudi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtpijbpcga.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtkowuxhdi.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gthkbpdfke.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guowangkeji.top/Article/details/gtiatpeuci.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.quarkkingdee.top/Article/details/gtitdxfamh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtpnhuoipn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtdpeejrxh.html

[Q41] 多表连接
来源：http://dali.hnxiangtu.top/Article/details/gtmxvnrtwx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnqzz.top/Article/details/gtmtxdsbjf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gthzjkrksb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtdvpnvkdq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhongyouzk.top/Article/details/gtqvuwlgkv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlektmwu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtnzciyjdb.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtujoqqrwv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gttqaokwfv.html

[Q44] IN 子查询
来源：http://dali.jlsjyb.cn/Article/details/gtzzcjfgud.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtwvhbvvla.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gtjbujfrls.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtdsymqxqz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtwgxscbne.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtkznvdfqx.html

[Q47] 与平均值比较
来源：http://dali.iojbl.cn/Article/details/gtwcqspdat.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtfvsulzfb.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtjgxefckf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtnfpxalia.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtqleppjtc.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtueztskjo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gturnziivy.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gtabgwxaod.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtjjcugwmn.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gtkgqcydag.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtpcowqpdp.html

[Q52] 删除指定行
来源：http://dali.tian-w.cn/Article/details/gtiqowlsyo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtnyqyxmzx.html

[Q53] 按条件删除
来源：http://dali.cashguo.top/Article/details/gtxnuuzhgy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtfdgrwrpb.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtagfqbcbq.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gtlkoixiea.html

[Q55] 排名（并列占位）
来源：http://dali.iojbl.cn/Article/details/gtwcssrcvv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtxhoyuohl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gtwgzyvarr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtzdsviakr.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtqupbgrlq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqeqrxzos.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtpkaivaui.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gthgjmnnfn.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtfmugbqiu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gttpozjtin.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtkodiknyd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnxiangtu.top/Article/details/gtusxqxsyj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtxobsbxoe.html

[Q61] 移动平均
来源：http://dali.0kj1m.cn/Article/details/gtlkeadidx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvcxipnnz.html

[Q62] 分组占比
来源：http://dali.yonumen.top/Article/details/gtosjbzgii.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.iojbl.cn/Article/details/gtublhqmcq.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtnjtzjaea.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtewqrdkqx.html

[Q64] 提交事务
来源：http://dali.guowangkeji.top/Article/details/gtonchekoe.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtsldsiwti.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gtiomzptef.html

ROLLBACK;
来源：http://dali.cashguo.top/Article/details/gtshkkkjgk.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtqsxolfpz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtbdrniupc.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gttlgpxkqm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtkwzhonnu.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtxwsctuiu.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtwnoasmnp.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtazduhnws.html

[Q69] 查看执行计划
来源：http://dali.cucudq.cn/Article/details/gtgunhujqp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwgqsbxj.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtphknsfqx.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtpmxlkdcb.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gteyymtpja.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtemxmrlge.html

[Q72] 查看索引
来源：http://dali.hywenlv.cn/Article/details/gthewefgxe.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtauqjasjp.html

[Q73] 查看表状态
来源：http://dali.xuetiantiany.cn/Article/details/gtlnhqztgr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xylfe.cn/Article/details/gtluzcoadh.html

[Q74] 强制使用索引
来源：http://dali.vqdsnc.cn/Article/details/gterackhwb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtmjlswsgl.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtepgqhvfw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtnqeykafl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtmkeqdaey.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtccjkbnol.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gteirausvl.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gtqzbqmdoe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xziqi.cn/Article/details/gtqvaphzvx.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjqolewx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtemeekbaa.html

[Q79] 字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtfbnqring.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.quarkkingdee.top/Article/details/gtevqrcert.html

[Q80] 字符串截取
来源：http://dali.316326.xyz/Article/details/gtmifmuzij.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtkxlcsbnf.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtxmesqrjd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gteuoqkirq.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gtxauojdmh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtnusrjbej.html

[Q83] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtpjzxajss.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtssywlyqf.html

[Q84] 去除首尾空格
来源：http://dali.gotoacloud.top/Article/details/gtfmneiext.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtdhnyvwwq.html

[Q85] 数值取整
来源：http://dali.wangdashe.top/Article/details/gtakwwqvdm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jiagoushi.top/Article/details/gtsaggeetz.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtntmyxiag.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gteluyzaqg.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxqkwbto.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtvevlnevc.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtqprrabni.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.andypj.xyz/Article/details/gtetiwiglk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtchpkchxr.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtbbaroywq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqukwdgl.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gthzzkebqb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gtrxqstkeu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsejuefcy.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtmhdwfpor.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkpfrarrq.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtkqdykcbd.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtlfpwzdvz.html

set -euo pipefail
来源：http://dali.xziqi.cn/Article/details/gtgstsfhzf.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtgtfxfkth.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtqrmudbcw.html

[R03] 只读变量
来源：http://dali.zhixingplan.top/Article/details/gtkpombjys.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtocihvsie.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtfnktwuzf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nanxinkj.top/Article/details/gtoztnpxzm.html

[R05] 参数默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquywvbrt.html

name="${1:-default}"
来源：http://dali.nanxinkj.top/Article/details/gthwsmdodi.html

[R06] 判断命令是否存在
来源：http://dali.hnqzz.top/Article/details/gtnjnldqph.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtdfzmhhbf.html

[R07] if 判断文件
来源：http://dali.gaohongyu789.top/Article/details/gtfxkptrzl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.gotoacloud.top/Article/details/gtyeppbrkl.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtusgmxabn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtbplnnqil.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkrdtnil.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ivvv.top/Article/details/gtahzkifhz.html

[R10] 正则匹配
来源：http://dali.chenzaomai.com/Article/details/gtbgxvdpos.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ehwqpu.com/Article/details/gtppszozkh.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gtgaptpxda.html

case "$1" in
来源：http://dali.kuanghao11.cn/Article/details/gtlhoaflzf.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gticovwhlc.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtttjpfuxe.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtlbpanodi.html

esac
来源：http://dali.nwbrower.top/Article/details/gtyiiyxoyo.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtjmmifgnr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.smart0.xyz/Article/details/gtkeryixgl.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gturlyvxdl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shuidangran.top/Article/details/gtmahzkwhx.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtpztxrqxi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtpzqatohh.html

[R15] while 逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtzarnwkgf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guowangkeji.top/Article/details/gtassglmkt.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtuuvphomv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.mhx1999.top/Article/details/gtpmmchdfg.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtooycqbin.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gttehacuxv.html

[R18] 遍历数组
来源：http://dali.chenlongwang.top/Article/details/gtaadhubuc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.cheryme.top/Article/details/gthamynliy.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtyzzgaeev.html

echo "${#arr[@]}"
来源：http://dali.havefunace.top/Article/details/gttontoapl.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtrjrvqnga.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinqigufen.top/Article/details/gttojcmtfs.html

[R21] 字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtxghmjxcv.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtfmhelkry.html

[R22] 截取子串
来源：http://dali.hnxiangtu.top/Article/details/gtamxrocvd.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtoirhmeqm.html

[R23] 字符串替换
来源：http://dali.hywenlv.cn/Article/details/gtxnnipunn.html


<!-- 参考信息 -->