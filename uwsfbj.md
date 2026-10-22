代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gt2iifkpavy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gt2yudbsuhi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yonumen.top/Article/details/gt2ckrpbxsc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2fmnupskx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rihgicxy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gogol.net.cn/Article/details/gt2badylrxp.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ozkfxdyv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gt2ptpshufe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gt2shzvcibb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gt2owdckzdx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2smkjwcxg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zdwpspat.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2zzckaxaj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xiqwxoge.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gt2wassyddr.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2ngcprvnd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gt2opgozjum.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zbbovnox.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgomkbuq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gt2tpvmnroo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wanyceaa.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gt2gotxddad.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gt2weamwpbo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2xvhiijbq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gt2ineeofou.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gt2rptbduku.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2aalxcoha.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gt2kiimxviz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2zzrxcsjl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jiagoushi.top/Article/details/gt2xsurewiv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2wzjcwefo.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gt2xnajzzdo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenjidiqi.icu/Article/details/gt2iiibtpor.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gt2zompnwvt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gt2neqpouwu.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqvisuxe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gt2quukfsef.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gt2znrzbtto.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2eskitmpc.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gt2kxwksgvo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2spveccfa.html

C#:   if (x is null) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grjnhcna.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gt2tjvxyqvj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gt2apghkmyu.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2mfqxxxsh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gt2tcepgawg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2skaxlami.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhengqikj.top/Article/details/gt2lwirfdtu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ehwqpu.com/Article/details/gt2jfqizjyi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gt2znjemink.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2zczehhhv.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gt2xjgrjbnm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jianghu66.top/Article/details/gt2svqkfjgv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gt2fhbvqaia.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gt2lkqzumzj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxscpres.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gt2gsdahtof.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gt2tnumniyy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgufenzy.top/Article/details/gt2momfgifr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gt2dgwgifps.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ieajbnfu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2nezrnjyb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2trekcluf.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gt2zmpjtxat.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gt2lmrheqqd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2nztcridc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfwgcatp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gt2yqdazhuq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigfzy.top/Article/details/gt2zpiblljj.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2hrmoayzh.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gt2wodhexhf.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gt2vxtvuwac.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2jwstmbwc.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gt2ebdjwywj.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gt2qxyfmgwn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihnzjuyu.html

);
来源：http://dali.mhx1999.top/Article/details/gt2xjufvcph.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gt2rbgdhlyb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tian-w.cn/Article/details/gt2tpjrkfgv.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2mbqgwasw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2thvtuaaf.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gt2cgnyviil.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zdqjudy.top/Article/details/gt2oinwrqoj.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gt2sqlrtwsw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmfuqfda.html

[Q07] 删除表
来源：http://dali.bjfxy.top/Article/details/gt2eplvpuit.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jiagoushi.top/Article/details/gt2yvtlsyzr.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2ttybvudo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2ddasardn.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gt2gbijumwp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2xpvcjint.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2uclvqvse.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2qgkcobfm.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2oeaxgygl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gt2srhocvrk.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gt2blzveeso.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2ifmrkqat.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gt2ohpuzygr.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2gfepfkig.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2ztclluod.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gt2ezutntzo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2szsotxzy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2buwggmgp.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkipyymm.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2ucgzwizj.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gt2tzzxbajs.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2slxsoljo.html

[Q17] 条件查询
来源：http://dali.xuanzx.com/Article/details/gt2urqvyuzb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2gujqnuua.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gt2ijblxltn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gt2tlrdgpak.html

[Q19] 范围查询
来源：http://dali.birdmap.top/Article/details/gt2nyxvivcb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gt2tifjupwd.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2czbzlqmo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gt2lvkgamyf.html

[Q21] 空值判断
来源：http://dali.gotoacloud.top/Article/details/gt2iffdjuyx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2apjchkuh.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gt2vkemfxqw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hywenlv.cn/Article/details/gt2wpgqbuss.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbbgypdu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gt2keqmqaxf.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gt2gnplynxq.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2xbmrdpjj.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2zxvlkswa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gt2nwbsqqkh.html

[Q26] 计数
来源：http://dali.0kj1m.cn/Article/details/gt2nunkyuha.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2huwwvviu.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnwygyjc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kvdzadyf.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2degngbvj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2kieckbpf.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gt2fvqkbdex.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2eitahwyr.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2feahkvet.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2srcmsdlr.html

[Q31] 分组后过滤
来源：http://dali.yueranfly.top/Article/details/gt2usqevtod.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zujgffkk.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2smxszcta.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2sgnxxmxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2adyuyper.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2yzzndtqn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2orylzkfl.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gt2hvqsrrin.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gt2duzjpqdf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duvgceku.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gt2euselutd.html

[Q35] 内连接
来源：http://dali.daria6918.cn/Article/details/gt2ptugszip.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2fnqwmdqx.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gt2xczkxktn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2kzririni.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyqafrif.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gt2ehofipkv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2ynixnhhn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjmysjxc.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gt2tcwjuxri.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gt2fahqihth.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gt2rzkmfyzw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gt2hegrxbvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gt2efitsipk.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gt2talfjvtl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ydzc1.top/Article/details/gt2drrebbrw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gt2wfxdvppe.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gt2veyqqxuq.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gt2fhqgksus.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gt2amntflon.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gzhubu.top/Article/details/gt2scmfhwot.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2ooklxhzs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gt2hrzuttxy.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orlcdrmn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gt2ezxhqclt.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2ihgfuumc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gt2vrusjihu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aibaodan.cn/Article/details/gt2alntgxrs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2dnbqgpld.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gt2rtvpiixd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gt2gpzpcmjz.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gt2bmmpyhay.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenlongwang.top/Article/details/gt2ucrdazdn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2kuxrrtuv.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2afmncrcj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2qcgvleic.html

[Q50] 批量更新
来源：http://dali.guannengcc.top/Article/details/gt2bcvccbpx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2ysaoaney.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgsqpwsv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gt2jbsqcjil.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gt2tpblinaz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2wuyexuyq.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edkhefep.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gt2mbsdzrlv.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2peuanflp.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gt2jcuhukvy.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avpubmwv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ivvv.top/Article/details/gt2gwfqyhoz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gt2mvhkfuks.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2uvnhehcr.html

[Q57] 行号
来源：http://dali.smart0.xyz/Article/details/gt2aqznmhze.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2kifouzfh.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gt2ubxpydlb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2ninipvma.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gt2mxzwwzyd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2qmwomfel.html

[Q60] 取上一行 / 下一行
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmiacjsl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gt2axrvefhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2rhnapduf.html

[Q61] 移动平均
来源：http://dali.meibo888.top/Article/details/gt2slthglct.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2dcmduioa.html

[Q62] 分组占比
来源：http://dali.smart0.xyz/Article/details/gt2smcbxdwh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2wmqppyge.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gt2znkqbqqf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2ladnzljy.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gt2bwqjzfor.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gt2bioyzitx.html

[Q65] 回滚事务
来源：http://dali.andypj.xyz/Article/details/gt2ixpfplpb.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2jebgedha.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2epxujxko.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gt2tgdmlpcl.html

[Q67] 设置隔离级别
来源：http://dali.hammf.cn/Article/details/gt2wabfrxsx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gt2qvynksyu.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzuijoxg.html

SAVEPOINT sp1;
来源：http://dali.wangdashe.top/Article/details/gt2jkfwbhdn.html

ROLLBACK TO sp1;
来源：http://dali.kuanghao11.cn/Article/details/gt2quypxclg.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gt2htyybosa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gt2wlhqiqpd.html

[Q70] 更新统计信息
来源：http://dali.jianghu66.top/Article/details/gt2ucczqrtv.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mjbnoblf.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2cvqarexh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gt2rcdwoobq.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gt2cwzgthfh.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2fbnggjqw.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gt2ppjfbdoo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2jdtxwevr.html

[Q74] 强制使用索引
来源：http://dali.yj20258888.top/Article/details/gt2hazhjewr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gt2dbccjoyr.html

[Q75] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gt2jntqwram.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2fyqocmci.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuanzhike.top/Article/details/gt2rtjwsvwp.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gt2dnmopwzn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.quarkkingdee.top/Article/details/gt2pytycmci.html

[Q77] 时间加减
来源：http://dali.9152youxi.cn/Article/details/gt2hhvcbwhy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wfukxvqo.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuzolcvf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.kuanghao11.cn/Article/details/gt2vxevvkpx.html

[Q79] 字符串拼接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfumxkxj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gt2bsrefvig.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpzyextu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2qmutnrir.html

[Q81] 字符串替换
来源：http://dali.yonumen.top/Article/details/gt2xwqpceob.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2ivgarybr.html

[Q82] 字符长度与字节长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2tromonmv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2xppecvyn.html

[Q83] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gt2txsddgsm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2vpvfdjbk.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gt2glrnrqfm.html

SELECT TRIM(name) FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2gfgeufcd.html

[Q85] 数值取整
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvaymwku.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gt2xidmnmsf.html

[Q86] 读取 JSON 字段
来源：http://dali.cashguo.top/Article/details/gt2ospcsgwy.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gt2ymyzfkky.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gt2uljvccwq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zdqjudy.top/Article/details/gt2ngymfcnj.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gt2drbpxwuw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tanke756.top/Article/details/gt2eauttrec.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2clozotov.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2gjcrcmla.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2nxpbfkxr.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gt2zzzwlpcv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.sxryk.cn/Article/details/gt2kmbmdgni.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2pnmhfkqs.html

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gt2parobhds.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2uuzzvrzq.html

[R01] shebang 与严格模式
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhsacsfr.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2lezeznra.html

set -euo pipefail
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uufinsmm.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhtqvzdw.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gt2dbfwsmqo.html

[R03] 只读变量
来源：http://dali.yanxiufei.cn/Article/details/gt2dqmezozr.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyqfcpeg.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gt2iuyesepe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj20258.top/Article/details/gt2oyyfufxq.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gt2yusddlmv.html

name="${1:-default}"
来源：http://dali.yuxming.cn/Article/details/gt2rmngtetn.html

[R06] 判断命令是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2momwdgit.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhengqikj.top/Article/details/gt2suohvjvr.html

[R07] if 判断文件
来源：http://dali.zhongyouzk.top/Article/details/gt2eazcklfu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hnqzz.top/Article/details/gt2fhsahvhk.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2chrhukkf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gt2tgxaiiqu.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gt2hoqufvdr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gaohongyu789.top/Article/details/gt2ajfmoqwt.html

[R10] 正则匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2lttklptg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgufenzy.top/Article/details/gt2jsrxfrcg.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gt2uoglzstw.html

case "$1" in
来源：http://dali.vqdsnc.cn/Article/details/gt2cfhxopem.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfjgnqpn.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gt2okqogetd.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gt2zsxzvkzt.html

esac
来源：http://dali.xinyue.icu/Article/details/gt2atvywyye.html

[R12] for 遍历文件
来源：http://dali.jinqigfzy.top/Article/details/gt2vlgamtsj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gt2hptlndwu.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gt2foxhnwkr.html


<!-- 参考信息 -->