代发 wailian999

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gt2bfzruqmd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2arjclylx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gt2xsoccgcr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjbhebdp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gogol.net.cn/Article/details/gt2fxkddxfe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlypiktn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfgfhctr.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gt2ujblsbmt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gt2edaypidd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2npancxan.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2wscofkxe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngrtwzva.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gt2audpjcbk.html

Go:   len(arr);  len(m)
来源：http://dali.yangfankeji.com/Article/details/gt2gphmjzue.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gt2hprdyyfs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gt2fbjpgwep.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2czntlogf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gt2zascnbil.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gt2nyabqwsm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gt2hjruscmm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2uimavebv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.iojbl.cn/Article/details/gt2rodlhxmo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2piaoqiih.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auahfcar.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sajnmjny.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gt2tksvaqku.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2kyfqrhxk.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2afcumkyc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gt2xwtivjet.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gt2gvjeqodm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2gjjyxcxv.html

Go:   if x == nil {}
来源：http://dali.shuidangran.top/Article/details/gt2mmuhcqra.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gt2nreiiuew.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gt2qzeuvbdc.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gt2lzintfdj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gt2bnwbqrok.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gt2eoktwswk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2cxmliymo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gt2drimpsyn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ehwqpu.com/Article/details/gt2jdwcqwdt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gt2talleypd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gt2ciombzco.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gt2arvkfhoc.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gt2taderotf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gt2iwlgjbqm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gt2hhvohkck.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gt2xnzoiuox.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2kgkmrxnr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqwzqbvy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gt2ezyeujur.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gt2ujagmohs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gt2aajpwnmt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2xhfzmdec.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2ihcainkc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2inhlvvos.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2lakfetrt.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gt2rtawbrrb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2kcltptpq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gt2ppzvnvmq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gt2cldczgsz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gt2eyheudvx.html

);
来源：http://dali.haohaochexian.top/Article/details/gt2kcqorhyq.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tugbyzbh.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gt2vizegmqt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2euvuerjp.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gt2oaokbgif.html

amount DECIMAL(10, 2),
来源：http://dali.cdnleiting.top/Article/details/gt2vbcxdoym.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2vecufpjz.html

);
来源：http://dali.daria6918.cn/Article/details/gt2txsijeut.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gt2shnphnib.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gt2qopgccne.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gt2wmmudbtu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gt2zzwjdnve.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2odlfhhqd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gt2lpwxxgqu.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crmprrre.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gt2ozpykuxg.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gt2fqpldpuo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2rhbiggug.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gt2igwlhfuf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2jrmogfre.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmvrjuuk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2lhwwmpxj.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gt2liltahup.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2rnbvpgoi.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gt2cxkyurgo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gt2tszbkifq.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gt2vjuwjxym.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gt2moevjrxk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yanxiufei.cn/Article/details/gt2hbmxlndm.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gt2zwssstca.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgjanvha.html

[Q14] 存在则更新（upsert）
来源：http://dali.nwbrower.top/Article/details/gt2nwnwcbgs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jianghu66.top/Article/details/gt2diysigio.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gt2kowumftq.html

[Q15] 查询全部
来源：http://dali.shuidangran.top/Article/details/gt2xkakkkal.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyumzioi.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gt2gasqhzqx.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gt2stuctvse.html

[Q17] 条件查询
来源：http://dali.wangdashe.top/Article/details/gt2tbftbgtz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2qbmbvsrh.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gt2dpspqrvl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gt2raptgxlr.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2fkohidpy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gt2oztodubz.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2tpaokxoa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gt2ezudmvln.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gt2aybeiepv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gt2crrymkhi.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gt2hekntkhz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2yejgiwey.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gt2tjyqcwmw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gt2jifehjce.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gt2fiunvrfo.html

SELECT DISTINCT city FROM users;
来源：http://dali.cheryme.top/Article/details/gt2livydfmk.html

[Q25] 只取前 N 条
来源：http://dali.xuanzx.com/Article/details/gt2rcisnbsl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2tbcjlcsj.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gt2lrsbloem.html

SELECT COUNT(*) FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2sifvjozg.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gt2zzmaojgy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2exbpegmk.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2kebpvwgm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2uplbfcfg.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gt2hxkzwxez.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2bcemmivw.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gt2gmckyiwn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2wfvwrnrc.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gt2tiaqeppy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2wrhrojoh.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2allfjzms.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2woayfdyb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gt2jdizzlqq.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gt2mwrdbsbs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gt2evvbkkpi.html

[Q34] 每组取第一条
来源：http://dali.yonumen.top/Article/details/gt2judltdok.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gt2rxufzcdw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gt2anpgydha.html

) t WHERE rn = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gt2peufkjwh.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whrfzlqj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gt2orqywcgx.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2tnnswldw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gt2knorxuto.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gt2bvzzzcjj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gt2wsrvekhx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gt2omlatkhl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2bgtvbjiw.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gt2estuzgsk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gt2lyqqwcsv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gt2nqfbscvk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2ktjmeywa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gt2qiwaztaq.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gt2umtqefix.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gt2wqbnvsim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gt2kjrszwna.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gt2xkuujhoq.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gt2zmvwyaan.html

SELECT u.name, o.amount FROM users u
来源：http://dali.pengpengdd.cyou/Article/details/gt2goobkjtc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gt2mzclvjem.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2zuupaier.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhixingplan.top/Article/details/gt2kbqpkono.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjgdirpw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gt2gpovixlp.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrdpirqe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gt2ukjuyijp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2rlgsgcuh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2gflpgnoh.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gt2hexasiqm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gt2ymejhglj.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gt2bxtzfock.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2gmsctqfa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gt2zmyhjoes.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gt2yrnrntfj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gt2cgrfimrp.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gt2nkbxoxsg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2ylrqlthv.html

[Q51] 用子查询更新
来源：http://dali.cheryme.top/Article/details/gt2sdpwdnlq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gt2uhpfrntp.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gt2jwuedfva.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gt2foieirim.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gt2qzdwycki.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2wwkapuhw.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gt2wkcbyfrw.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gt2qhamhsrg.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gt2sjpgoahn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2eqihgouf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ztfyonfj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2hbkzwzya.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gt2bikwqejw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2elbkribu.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gt2xfdzxojd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2hxwsneju.html

[Q59] 分组内累计
来源：http://dali.svipenyu.cn/Article/details/gt2bmjcgtrz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2aornsuet.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2yweqqcej.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gt2xiluuuzd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2jcayirqb.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gt2xonrlrro.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2yezcibyp.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gt2efleguky.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2aitoeghq.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gt2zznwtdnb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yvedp.cn/Article/details/gt2flwirsrw.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gt2jpikljfu.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gt2gihiwkoc.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gt2matehuvn.html

ROLLBACK;
来源：http://dali.andypj.xyz/Article/details/gt2albjlrbs.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2eyglinew.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gt2bmcjaaiz.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxneuprm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gt2vaxtjmkr.html

[Q68] 保存点
来源：http://dali.9152youxi.cn/Article/details/gt2diavfsdq.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gt2yvtjhegi.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gt2jeerxmiv.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gt2ffznpzqg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gt2qnqbiqci.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gt2ezpkqhxk.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gt2evywjgsd.html

[Q71] 查看建表语句
来源：http://dali.tianlin.xyz/Article/details/gt2bzewsavw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2xbovmihy.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gt2tmjczymm.html

SHOW INDEX FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2ugmgwkte.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gt2hroowdyq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gt2mepjulvn.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sljrxpbl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigfzy.top/Article/details/gt2hdndxlwr.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2dhbxpmuq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2rvrfpizy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gt2todzvijx.html

[Q76] 按天统计
来源：http://dali.jianghu66.top/Article/details/gt2wemfbqzd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gt2ehgvdylx.html

[Q77] 时间加减
来源：http://dali.gzhubu.top/Article/details/gt2xycbwtsr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gt2nojeozgz.html

[Q78] 当前时间
来源：http://dali.jyoumei.cn/Article/details/gt2rvarehfh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gt2bddetuul.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2wrahonhb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xuanzx.com/Article/details/gt2bibvnzdb.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gt2pafwudad.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2hvrqxaon.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gt2gbwkuvjh.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2netrtjbm.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gt2vijtowca.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnupiuhg.html

[Q83] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2zvpyuzvn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2zctwwccx.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gt2ujwaxsmf.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkyvmnyf.html

[Q85] 数值取整
来源：http://dali.yangfankeji.com/Article/details/gt2zvfpxbdx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gt2fipcxbar.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gt2feimodsz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.svipenyu.cn/Article/details/gt2ztnqzxoc.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2pnlynvaa.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gt2dgvgkkzm.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gt2xjgfsegl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gt2eqqtrxzh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2xvsjgmuw.html

[Q89] 判断表是否存在
来源：http://dali.andypj.xyz/Article/details/gt2jqpsouyq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gt2axsoysby.html

[Q90] 生成序号列
来源：http://dali.vqdsnc.cn/Article/details/gt2jbqbqzdd.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gt2bnqyheqo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2eemfjyku.html

R. Bash 专题
来源：http://dali.aizwys.cn/Article/details/gt2yzgxpail.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ustknvep.html

[R01] shebang 与严格模式
来源：http://dali.zdqjudy.top/Article/details/gt2efevrgzw.html

#!/usr/bin/env bash
来源：http://dali.mhx1999.top/Article/details/gt2dcuuyixv.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gt2bxuncwbd.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2htfbznws.html

name="Tom"; echo "$name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2grjlqpjy.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gt2dfspbwxu.html

readonly PI=3.14
来源：http://dali.haohaochexian.top/Article/details/gt2ldibddec.html

[R04] 位置参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqbyjsoy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cashguo.top/Article/details/gt2hewbuzag.html

[R05] 参数默认值
来源：http://dali.xinyue.icu/Article/details/gt2omirmouv.html

name="${1:-default}"
来源：http://dali.jqgfzy.top/Article/details/gt2xnirobyi.html

[R06] 判断命令是否存在
来源：http://dali.tian-w.cn/Article/details/gt2zxuwbwqn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nosurzyu.html

[R07] if 判断文件
来源：http://dali.fzhhl.top/Article/details/gt2paibaqhr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yueranfly.top/Article/details/gt2icapujxz.html

[R08] 数值比较
来源：http://dali.nanxinkj.top/Article/details/gt2snxiecdl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.andypj.xyz/Article/details/gt2eujgrgtt.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2gsllaxlp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gt2ydrsghce.html

[R10] 正则匹配
来源：http://dali.sysykeji.top/Article/details/gt2sharosbr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cucudq.cn/Article/details/gt2txetobqh.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gt2wlswmnjz.html

case "$1" in
来源：http://dali.cheryme.top/Article/details/gt2chcxxwxd.html

start) echo "启动" ;;
来源：http://dali.daria6918.cn/Article/details/gt2ooxoazce.html

stop)  echo "停止" ;;
来源：http://dali.iojbl.cn/Article/details/gt2lwwovigr.html

*)     echo "未知命令" ;;
来源：http://dali.jinqigufen.top/Article/details/gt2wcooomih.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2miahvbhh.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gt2rgztdmoe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gt2zelynpuk.html

[R13] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gt2pvzvzmth.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gt2akdcfipn.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gt2uqqsocfs.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gt2uhbrlfgw.html

[R15] while 逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2phblwrtn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.guannengcc.top/Article/details/gt2jmxcmdnk.html

[R16] until 等待条件
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrhgqvzn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gaohongyu789.top/Article/details/gt2djawjuni.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gt2kmhsnapj.html


<!-- 参考信息 -->