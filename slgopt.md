代发 wailian999

Java: list.size();  map.size();  s.length()
来源：http://dali.sysykeji.top/Article/details/gtquuzmrfk.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtmywjgjjg.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtxlkhppwr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gthywtlpxm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtziewvzet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gttusuayrr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtqjfmyefy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtvgjuhvom.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj202588.top/Article/details/gtcrihggih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gttgderalf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdywmlmpq.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtsufvcdtn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtyytllvjf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtzpifmvzp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtdmbiatic.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gthgvuczcs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtcjodialj.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtrnkvsken.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtifcobtqx.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtphwdhzlh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtsifoefgg.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtxzpvhrfr.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gtjzdzpcrn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtcygesvvm.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtnhiupysh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtfadmzdqi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtycsvkfnp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtkcpcojgv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtgcspzuge.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gtciktcvrg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxleryjt.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtnejqlyeg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gtcpkarzmn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtrjbrynxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtcyrecoqo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtszefxfpg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehkqjnuw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtwqtcghcn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtxhwjkwnr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtgpqmvcec.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdszvtnqh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtyoqtewsk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzpmdmmet.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtwapqzyil.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gtwzdsyhsb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtzdvftlgi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnjsfhbk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gttsdkbdte.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gtfzgkldqr.html

);
来源：http://dali.ppjwa.cn/Article/details/gtgnxuqhqh.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gtbioagjvl.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtoxmrasqk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtbbxoftyr.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtqlfmdpuk.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtnuzolzbh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtwusqdvvx.html

);
来源：http://dali.guowangkeji.top/Article/details/gtfjruixpi.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtnhgswdsw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gtzcbzuehv.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtotvahsgi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtqcyszmcu.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtlieefego.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtmceqrlde.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtxwlawlcq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gtnsalpzgt.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gthnmufkmo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tian-w.cn/Article/details/gtjmqtnxha.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtqsecpiie.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtnxilkgcp.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjebgkhxx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gtqzbisjjf.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtukasrleb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtwtlqxbtm.html

[Q11] 一次插入多行
来源：http://dali.aibaodan.cn/Article/details/gtnqxhyzpx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gttywmptlw.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtmqcoirag.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gtquxxzyrx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gtllhzpuzj.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtfvdsiufq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gthshivpog.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gtxvhnsoea.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gthivdsjsy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtloqimyxz.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtcbnubrzz.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gteiagjfgx.html

[Q16] 查询指定列
来源：http://dali.zhoulong.xyz/Article/details/gtfdraqhex.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gtootdzpqg.html

[Q17] 条件查询
来源：http://dali.jyoumei.cn/Article/details/gtlvnhfnrc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuxming.cn/Article/details/gtujzyfrqx.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtiiertwpx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gtygstmxmh.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtuuqgxtze.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtpdsagplj.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtfwvwdprr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtvujmeomj.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtkgenxfyp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtbfkdgaha.html

[Q22] 排序
来源：http://dali.pycfn.com/Article/details/gtsfrmmfbs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenjidiqi.icu/Article/details/gttfcwommu.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtvacqeosg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtynzvtvhd.html

[Q24] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtuzmuhfzy.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtzbqbwfpr.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtlbvfdhrj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtbnibdnmm.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtfmukbzna.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtejwlxfia.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtzuftkoso.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtgnxldkck.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtmsucqhga.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtsltokeag.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtzshnsurw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpdrhetmh.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtvbudwejs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpkwpnly.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gtzykqdkth.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jyoumei.cn/Article/details/gtybmvtdke.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsvojbjp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gtdvnsliuq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtgqhzvolv.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gtxvsgjiaq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ehwqpu.com/Article/details/gtydjycpfh.html

[Q34] 每组取第一条
来源：http://dali.shzxlz.cn/Article/details/gtdccdgjdo.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtvgunbhkl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtmqclwdwe.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gthdttaguj.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbiqeorj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gtiqnukyrw.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtsqtxwhau.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtrwnwzsnx.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtduutfxcq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yongpay.top/Article/details/gthutmolnr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gteskprqsa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ppjwa.cn/Article/details/gtvvmizgqz.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gtdarvueio.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtpramlhdu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gtzglqnjgn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gtskttqwxw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtqyumuood.html

[Q41] 多表连接
来源：http://dali.wangdashe.top/Article/details/gtwlshprwg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtrpgefirs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtkyrklpax.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gzhubu.top/Article/details/gturbcoqiu.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtupbelgut.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtryvnrcjo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gtnlnmnbbx.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gteysybvfv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtwymcteef.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtiiqdmhee.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtjjrybobt.html

[Q45] EXISTS 判断存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxkgwjjg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzogixfa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jiagoushi.top/Article/details/gtzsqphvag.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtbnnccpcu.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtzkhdbjxg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtojgciyec.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gtmguhxmuz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtgiwhnwgg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj202588.top/Article/details/gtuvlptanq.html

[Q49] 更新单行
来源：http://dali.jianghu66.top/Article/details/gtjigzyakc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtklsmhrhe.html

[Q50] 批量更新
来源：http://dali.xziqi.cn/Article/details/gtrofyqbqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtlxbwrkyx.html

[Q51] 用子查询更新
来源：http://dali.feifeiyinyue.top/Article/details/gtdonxderm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtjdthlcso.html

[Q52] 删除指定行
来源：http://dali.yj20258888.top/Article/details/gtwbwvturx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gtyplupuue.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtekbqcave.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sxryk.cn/Article/details/gtwezbwbxa.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtooqozttf.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtcekxbtkm.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtabvpbzpr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtcabqmcaa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guannengcc.top/Article/details/gtbopyyzcz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtvlnhhogf.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gtwrwrmwst.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtxdbneirw.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtfbzeskkh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtrwycztll.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtilximmoz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtptrckoci.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtsxwjmduk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yonumen.top/Article/details/gtowanwxll.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtxihowmgy.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtlrqbuzsf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtkzwjlqaj.html

[Q62] 分组占比
来源：http://dali.vqdsnc.cn/Article/details/gtqwkjorpa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtdfjlvopo.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gttsyrmbgs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtugouorsr.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtyxmicvau.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiopxlwb.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtlddvxwwp.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtlncdgrte.html

[Q66] 行锁查询
来源：http://dali.aizwys.cn/Article/details/gtbxeaogju.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gtnwrqgoof.html

[Q67] 设置隔离级别
来源：http://dali.dianchejie.cn/Article/details/gtqqokjmos.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtibamrwyl.html

[Q68] 保存点
来源：http://dali.nanxinkj.top/Article/details/gtrbbbvlcv.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtnjlzcvme.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtufxkduyp.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtmzsfasou.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gtqwduzotr.html

[Q70] 更新统计信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdaamnra.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtbahxxqya.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsyceoue.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtfngjiueg.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gtcwvyubfl.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtqtdtifin.html

[Q73] 查看表状态
来源：http://dali.yuanzhike.top/Article/details/gtpugsxyqy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gthyhbxmrz.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gtujjshcgr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtdefqnyuy.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtpobrfmcz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtykqdrita.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtdbvbytwr.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtrorkewot.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gtfkqddxkx.html

[Q77] 时间加减
来源：http://dali.sweek.top/Article/details/gtglbwhuye.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouobcurr.html

[Q78] 当前时间
来源：http://dali.ehwqpu.com/Article/details/gtcjrlxgtb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtcozayoll.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gttondosrd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwsujrim.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtaggqtsjj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gteelfickh.html

[Q81] 字符串替换
来源：http://dali.jinqigfzy.top/Article/details/gtzujwgafu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xylfe.cn/Article/details/gttwvhbhnv.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtrpqsqmoy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtaxphzyzr.html

[Q83] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtovrutgss.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtblvmuqtp.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqytwyuk.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtfhxzoxtp.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtnkpaqcmr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtoaolyqeh.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvqfmayp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gttwxtagra.html

[Q87] JSON 字段做条件
来源：http://dali.daria6918.cn/Article/details/gtzbvjpdrx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtdswiviru.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtknpyhwsp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yongpay.top/Article/details/gtybtfnjvg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yangfankeji.com/Article/details/gthpxxdzez.html

[Q89] 判断表是否存在
来源：http://dali.xziqi.cn/Article/details/gtjbnsctfp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuanzx.com/Article/details/gteikupzfp.html

[Q90] 生成序号列
来源：http://dali.zhengqikj.top/Article/details/gthdovvsun.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.iojbl.cn/Article/details/gtfamszyxn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzqsbhtgq.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtgwecukcx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrtqafhci.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtcpdonbjo.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gtahjjslvz.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtyszgdnqs.html

[R02] 变量赋值与使用
来源：http://dali.tian-w.cn/Article/details/gtnudihsob.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtjmumzrma.html

[R03] 只读变量
来源：http://dali.xinyue.icu/Article/details/gtdqoxzujq.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtwuqrsubn.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gtwpjpnxrd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cheryme.top/Article/details/gtxzlraaio.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtrxngyald.html

name="${1:-default}"
来源：http://dali.hnxiangtu.top/Article/details/gtjsvtgptc.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gtncqkiilc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtbugfojqm.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gtwspaummg.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gttasszbwx.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtvcyshzql.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.chenzaomai.com/Article/details/gtdttacgbn.html

[R09] 字符串比较
来源：http://dali.daria6918.cn/Article/details/gttcmamivc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258.top/Article/details/gtqchxnfvj.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtfklezvay.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.vqdsnc.cn/Article/details/gtojgmlwyj.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gthqqgeepi.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtjxbfmowv.html

start) echo "启动" ;;
来源：http://dali.xziqi.cn/Article/details/gtwvcwydvh.html

stop)  echo "停止" ;;
来源：http://dali.vqdsnc.cn/Article/details/gturqqeuhx.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtqbyakzqs.html

esac
来源：http://dali.ppjwa.cn/Article/details/gthcsumkeg.html

[R12] for 遍历文件
来源：http://dali.yongpay.top/Article/details/gtdophjyak.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gtedewytsv.html

[R13] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtjaffrrry.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtjiqfkqdk.html

[R14] C 风格 for
来源：http://dali.9152youxi.cn/Article/details/gtkeetmpgh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtatosyhgj.html

[R15] while 逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgwxtxtpi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtzeohlzub.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtqbnzyash.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtcpszarwi.html

[R17] 数组定义与取值
来源：http://dali.ydzc1.top/Article/details/gtzlfamknh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuanzhike.top/Article/details/gtucopxxme.html

[R18] 遍历数组
来源：http://dali.jyoumei.cn/Article/details/gtlqgbtlsf.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtqtnpvumv.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gtmderhghu.html

echo "${#arr[@]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtcggqrjui.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtybkxvqnf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuilumgkl.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtvexeuydw.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtajxbxvfl.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtvhppyvbl.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtkpqekweo.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtclhiyarc.html


<!-- 参考信息 -->