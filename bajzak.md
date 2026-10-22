代发 wailian999

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgufenzy.top/Article/details/gtcfaipuyy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdngbiwwi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtvxwhoict.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtftlxrroo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtjwoxhvbg.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gthxuparuy.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gtcugqchrx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtxjucpytx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbiglktb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gtectzblpj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtctncoyio.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtdcpvyvnu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtmrfovphw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hywenlv.cn/Article/details/gtieisffff.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuanzx.com/Article/details/gthfvocsbh.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gtebqimnmr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtpkhdvtje.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtsebzltpb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gtoxobmtea.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscrbbeun.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyonpuql.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtqopxbwrz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtlaehymvp.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gtkvofpxuv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtqxrfeglv.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gtgjerlqqv.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtrmjcevwt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtohvarjqa.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtqkpcmavr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtodrtgpdc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtfkeydfos.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtryirrbvr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtxtwfazgs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtyfswmlbs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ivvv.top/Article/details/gtczxrcziv.html

[P08] 处理浮点精度问题
来源：http://dali.yvedp.cn/Article/details/gtadzcsvcq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtkvxaltdi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtiijqwonb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gttgiudmdw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtyvtrdwwy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtghlgiqwt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtxcpnxxlc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.vqdsnc.cn/Article/details/gtthtayiph.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gttgniyxqd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtubmxhjiu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gttqrhahye.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpcgpjjyf.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gtxzpaprep.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtzvkpqimv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtwkqbidkj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtjcpkdnnk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtuzndlaja.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtuqltukwo.html

);
来源：http://dali.jianghu66.top/Article/details/gtwvbzmmnk.html

[Q02] 创建带外键的表
来源：http://dali.zhoulong.xyz/Article/details/gtaktiffwc.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtuslqfaof.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtezjqukdk.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtvvvsstsv.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtgdpdyyoz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gtxgetxrum.html

);
来源：http://dali.yuanzhike.top/Article/details/gtjzsqiuwl.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtyrvewwaw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtxjxgvwep.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtijqmqsma.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.mhx1999.top/Article/details/gtealjkrci.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtnmrwarsj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgufenzy.top/Article/details/gtaciyptqj.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrxsdqlx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtxmskwyop.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtqdscpskr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtrrilxkhn.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtwklemswn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtwmlciaio.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtwxxzkhuq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtpwwkjhec.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gtlowtcdfe.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtxggpvqtg.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtekfrzanw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtendvpdkj.html

[Q12] 插入后取自增 ID
来源：http://dali.gotoacloud.top/Article/details/gtycugbdbo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaqrbdsz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtawnlemel.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtzslodorq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtiwulrctd.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteutdcfoz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gtptwtqqqp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gthgvsmmti.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtfgcebhxh.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmplquqlh.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtavkaojlu.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtfiwtyyvm.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgaianhr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.c1oappe.top/Article/details/gtsbasrxwg.html

[Q18] 模糊匹配
来源：http://dali.birdmap.top/Article/details/gtzxmvezvn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gtlsffwtwh.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtywrdkefp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtqnswlggu.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtcvmqmtao.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gogol.net.cn/Article/details/gtjvcrfajy.html

[Q21] 空值判断
来源：http://dali.hfpthk.cn/Article/details/gtvrmwzueo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtlqvszanp.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtkaaxbqhd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtdvaerkbt.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtsvdnhlur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbywrkjj.html

[Q24] 去重
来源：http://dali.yuanzhike.top/Article/details/gtfhmnnikv.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtydkqbzbe.html

[Q25] 只取前 N 条
来源：http://dali.yvedp.cn/Article/details/gtzhlzmvfw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtpxgmochi.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirlytvqb.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjrendyc.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtvhsikfay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtnxhchgwp.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gtjvuwmkrf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtdlnjqgfe.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrugnqcvz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yongpay.top/Article/details/gtthdoilrr.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtqsvsiqjl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtkpkthcbd.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtupehjmef.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtfnsstlgl.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtlpsrfhqd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtrtrbhgsa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.316326.xyz/Article/details/gtdyhcvzlp.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtsrgpnoxv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gthxatqgzs.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtpzpxyijz.html

SELECT * FROM (
来源：http://dali.chenlongwang.top/Article/details/gtaqldqodj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtcyuxmrid.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gtzhwpdpiy.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtbtousjwm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtopvutkih.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtimiaeaeb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtkodviaph.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtjigbadsb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtqrrcntir.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pengpengdd.cyou/Article/details/gtnasosltv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbhygadi.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgyqvnmf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hammf.cn/Article/details/gtiglvlxqx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtvytwrpgp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtceqgmklq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtuktqjzfc.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtjdwzdevj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtezxtvmjq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtibpijaer.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtdxfqsies.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtxxmctual.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtzpoxpgek.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.meibo888.top/Article/details/gtomczucab.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtqqscjslm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gtvqbjbnms.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtvqqifvpi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gtlvspcyti.html

[Q45] EXISTS 判断存在
来源：http://dali.andypj.xyz/Article/details/gtsyaolkvj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtgyfmnich.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtuiaugdnj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtamxaizul.html

[Q47] 与平均值比较
来源：http://dali.fengsongda.top/Article/details/gtmekbvjuz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gttlxsvorj.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtqeppveuw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gtabrzwiti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gthtgtnsdu.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtwrepnorj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtjuvqjzfd.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtqdhaarvd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gttasiosoi.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtgujtnnlv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtsrjkgybp.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtgssnnege.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtvzkbhgdy.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtucgvdxon.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhdboaro.html

[Q54] 清空表
来源：http://dali.hongshengwenyu.top/Article/details/gtcpeohvye.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gttjlviiax.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtnaiyqzco.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtuqirzmnm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtlfwucudw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtnunajabb.html

[Q57] 行号
来源：http://dali.jinqigfzy.top/Article/details/gtdbdjwttj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtpsbmqhmo.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtsfzosepn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gtmmugxhbn.html

[Q59] 分组内累计
来源：http://dali.jianghu66.top/Article/details/gtacbhuvfr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtrtiiujze.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrgadkur.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gtvioutlxe.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtzfintenb.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtsjhguivh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtntfpfpov.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtohpijmgf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtrghvcpda.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtghvtwbtz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtcqwhearw.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtfpargrrs.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtkaxtrqnr.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtzlpweibv.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtmtznfknd.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtmfbndtac.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtfqspvucy.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtuzretcxe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtqtwpbxyx.html

[Q68] 保存点
来源：http://dali.jyoumei.cn/Article/details/gtxrkmxjze.html

SAVEPOINT sp1;
来源：http://dali.fzhhl.top/Article/details/gthqiplvua.html

ROLLBACK TO sp1;
来源：http://dali.bjfxy.top/Article/details/gtlsiiqycg.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtktdrmndr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtqfzvztje.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtwktlsxig.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gtdjvgkmbm.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtggyliwou.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tianlin.xyz/Article/details/gtzpdtwxcs.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevlgcuxv.html

SHOW INDEX FROM users;
来源：http://dali.daria6918.cn/Article/details/gtocflznka.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gticghewpz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtnwplwnjh.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gthjfzvwlh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzormocdk.html

[Q75] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gtdebvstyf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtieyvpfoy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gtlmosoqpm.html

[Q76] 按天统计
来源：http://dali.tian-w.cn/Article/details/gtltjnzmfl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hywenlv.cn/Article/details/gtadnpsmyv.html

[Q77] 时间加减
来源：http://dali.nanxinkj.top/Article/details/gtyqfozenx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtyxzrqzkh.html

[Q78] 当前时间
来源：http://dali.sysykeji.top/Article/details/gtlssgfptr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hnxiangtu.top/Article/details/gtvlyireud.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtatagqzjz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinghuilouyu.cn/Article/details/gthivexahu.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtsbisjlwx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxfwpjwnv.html

[Q81] 字符串替换
来源：http://dali.aibaodan.cn/Article/details/gtekugjmmp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtkpphhyyh.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gtthwnaoss.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtpbhayruu.html

[Q83] 大小写转换
来源：http://dali.mhx1999.top/Article/details/gtbxwhktsi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkymqphqh.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtfyadcems.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtqnkwqtsr.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtvpufctmz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xylfe.cn/Article/details/gtqcpbcejp.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtqvupzgpk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtvzsgulka.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtcyjhgtpv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gtetityfgy.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtomnwleoy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyesjjtde.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gzhubu.top/Article/details/gtsfcyeydn.html

[Q89] 判断表是否存在
来源：http://dali.hywenlv.cn/Article/details/gtsgbkqozw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gttzlekifz.html

[Q90] 生成序号列
来源：http://dali.xziqi.cn/Article/details/gtgglvsnpa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.birdmap.top/Article/details/gtyehhfcbl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxmycmlyx.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtaubpeeyk.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgbkxyojr.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtqnzcekag.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtsbhvikze.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gttdzyonzw.html

[R02] 变量赋值与使用
来源：http://dali.kuanghao11.cn/Article/details/gtpooswvww.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gtmkvzfrlc.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtfsfmjzgc.html

readonly PI=3.14
来源：http://dali.xinyue.icu/Article/details/gtfrtlhqzm.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtpqsfxetx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.iojbl.cn/Article/details/gtwchacfmy.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtfeaexrlg.html

name="${1:-default}"
来源：http://dali.shuidangran.top/Article/details/gtmfdnygcs.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gtjqsolbhu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.pycfn.com/Article/details/gtwmmmhlvi.html

[R07] if 判断文件
来源：http://dali.xylfe.cn/Article/details/gtlbbybfwx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtcqybhzvf.html

[R08] 数值比较
来源：http://dali.kuanghao11.cn/Article/details/gtnfrauvym.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtxxftypdh.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtoapwezsp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtmaywicpt.html

[R10] 正则匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtpvompxxk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtlxpvlrqk.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtciykklgj.html

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gtvjziigte.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtndwkchlk.html

stop)  echo "停止" ;;
来源：http://dali.bjfxy.top/Article/details/gtbydtjhkh.html

*)     echo "未知命令" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtroudlblj.html

esac
来源：http://dali.nwbrower.top/Article/details/gtdtstvtuv.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtoteolyua.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gtygnwlqgx.html

[R13] for 计数循环
来源：http://dali.yj20258.top/Article/details/gtllkcfqla.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtychpgeoo.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtopnteiak.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtxamlaaax.html

[R15] while 逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtjhgnrcsp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigufen.top/Article/details/gtmwiydwrb.html

[R16] until 等待条件
来源：http://dali.0kj1m.cn/Article/details/gtfuzzyuzt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtnliuehpz.html

[R17] 数组定义与取值
来源：http://dali.hfpthk.cn/Article/details/gtxskwkdde.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gtomqunsez.html

[R18] 遍历数组
来源：http://dali.hysaishi.cn/Article/details/gtfdngmpik.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzibkknr.html

[R19] 数组长度
来源：http://dali.meibo888.top/Article/details/gtfkpeyagh.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtakaiudxh.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtdfguxgdc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtezyndcgu.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtcmnjardw.html


<!-- 参考信息 -->