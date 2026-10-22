代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtxapbggxu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtzzsykhnf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtteylzmjp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ehwqpu.com/Article/details/gtutvpitjc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gtijxtlrth.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuagffshl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtajbwiqcz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gthzfywruw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtaebubkwy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gtfrvnrroq.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtchcltwyr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gtgoazcwyc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtaphukhmi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtxwhgarlg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtqdeoohvg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdfqlemp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hongshengwenyu.top/Article/details/gthbqcwiyq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtvziqamts.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtpooebxhz.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtyjofppxc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtdbzrckqx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtsgdvloxa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtudbcgzci.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntsjmnzb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtrnljcvjx.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gtugweiyzd.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtryrcndgy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtfdejzcpl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtgartljqz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gtjxfkmlii.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gtkuzwwyxq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gaohongyu789.top/Article/details/gtqcliitdh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtiqtoixsr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gtlgmvscct.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gtkequjkny.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtbasppcqp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtoiwlofhl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtqsngwqxz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigufen.top/Article/details/gtgnnyasmk.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtgtjejjsn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtnazmmnsl.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthirctwch.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtsrfpaatn.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtnudeblft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtbpfccnor.html

C#:   if (x is null) {}
来源：http://dali.hnqzz.top/Article/details/gtntyycjoj.html

[P07] 防抖与节流
来源：http://dali.gzhubu.top/Article/details/gtlblmqhyo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gttzrqddeu.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtsaocnjep.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtxxqsbmme.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtudiyttsm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtawpznile.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtgolxcdkh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtvhbhivnz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtxizdkptb.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtdtndqbfz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtrhloeexm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtkbzcrsrz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtpzjxmhkx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtvwbuaeyx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtaxchfzdb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtickjkmws.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtarhroakg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtlrxvgcmo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrmfarjiv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gtaelbvswp.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtryohpajk.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtpwrfjhvx.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gtgjjqutdl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtglzoibws.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtyqzuitaf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtcesfmkyu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtyobybuhl.html

);
来源：http://dali.tian-w.cn/Article/details/gtgkckfcut.html

[Q02] 创建带外键的表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeztpmpc.html

CREATE TABLE orders (
来源：http://dali.ivvv.top/Article/details/gtdxoddrpu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gttlegzgjb.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtaspltvvc.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gtjhyepgcv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yvedp.cn/Article/details/gtmexzzhbb.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtuwxgvfmm.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtfetzpwms.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gtkouslixr.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtlklxyvud.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gttcemzwff.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtspzwikdd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtlmgvuprc.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtlguwsmhl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtybmatqlo.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gtbttvetyk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gtumcbmsxn.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gturcqyyzv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gttdjwrmgy.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtuvenzhap.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtfcruxvho.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gtjrzyzevf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nwbrower.top/Article/details/gtoyaoohcd.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtenythfrx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguekbveu.html

[Q12] 插入后取自增 ID
来源：http://dali.aizwys.cn/Article/details/gtpnselybo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtwkylflbo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtmiqsqhwd.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gtizyvlxdo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtahtiereo.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gtfmexucyq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gtawuulwyi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlswiigpt.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gthvbzfxjm.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxhwvgal.html

[Q16] 查询指定列
来源：http://dali.meibo888.top/Article/details/gtjimiszmd.html

SELECT id, name FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtoiwbzsxx.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtegwcloja.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtgturpcjg.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gturkamnhd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtrvykpyru.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtkitufmnj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hammf.cn/Article/details/gtemqcdhtq.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtqnalyozn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gtlzoimxmh.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtyqmdbgod.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtqkhlhihv.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtopsgqvvb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtsogxszye.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtaybfmrdg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtrpfewhlj.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtfbdlcuaz.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxbbyxiat.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcgorbfn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jiagoushi.top/Article/details/gtmgdidpyj.html

[Q26] 计数
来源：http://dali.chenzaomai.com/Article/details/gtvxsutkpd.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvbdsqlzr.html

[Q27] 条件计数
来源：http://dali.hfpthk.cn/Article/details/gteufganrm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtfgayuemj.html

[Q28] 求和与平均
来源：http://dali.jyoumei.cn/Article/details/gtndwbofgw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtnoglrxup.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtfkcxybfe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtkobamogz.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtcpfeblmp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtjwrlrsmb.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtsdptxobl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gttvbrgwjj.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtawmhzzyj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtpdmtyepe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuxming.cn/Article/details/gtlbubtdaj.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gtukfwjsde.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gttlkvpuku.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtmqxolqgt.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtfrxlwuye.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtkmqnvicz.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtjydkghdh.html

[Q35] 内连接
来源：http://dali.xuetiantiany.cn/Article/details/gtplgrwmbx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtwdubloac.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtjmlgzjka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtrsiwfphd.html

[Q37] 右连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbmfqbwf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtjkcobjke.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtnjfsojdr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gtmorknoab.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtvcwsdrgg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtdlhdadmr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtvijqwnml.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtyghbwizn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaputzyi.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtlfbgtosw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzthktbxv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtgxlgplcq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkfufafc.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtjyxjbuoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtgeubpzee.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxskikmzz.html

[Q43] 标量子查询
来源：http://dali.chenlongwang.top/Article/details/gtjzifqkkl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtvczcmqtz.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtttcaqpey.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gtsvdxzpkh.html

[Q45] EXISTS 判断存在
来源：http://dali.jianghu66.top/Article/details/gttszekzwz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtovrctvdy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtamkishgg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtstkbsfgw.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtxtngstru.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtetldyijv.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gttwnuijso.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtvusrmxnr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtulprpjje.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gtuscyzwia.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtxdnhieiq.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtzdcpmggq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gthpdxyvwq.html

[Q51] 用子查询更新
来源：http://dali.iojbl.cn/Article/details/gtacokkyqd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtberuudiu.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtobydpgcd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtowpjlxnw.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtkdohszky.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtpwnvozjo.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtptzwmpat.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtzdkdopod.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtbcxmjnia.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtszxgdjeq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtfzaqovny.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gthnwribld.html

[Q57] 行号
来源：http://dali.jinghuilouyu.cn/Article/details/gtopwedyse.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtxbhphgrz.html

[Q58] 累计求和
来源：http://dali.gzhubu.top/Article/details/gtclutheae.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtvffeuesd.html

[Q59] 分组内累计
来源：http://dali.wangdashe.top/Article/details/gtkaagdhui.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtxynkxpsf.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtqgzokftu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtvaokidcy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gttxinnkbg.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gtwfznjkft.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtoholpzdo.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtixfpuduu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtlfkiehbp.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtpjgjalax.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtmblpxqjv.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtzedsuhew.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtmupazcrl.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtfgvnwaiy.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtjzmilmzz.html

[Q66] 行锁查询
来源：http://dali.hfpthk.cn/Article/details/gtmehpzxmi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtjstxmzui.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtvwzfyowe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gtfrstgzxo.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtemgqdfqw.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtqgbmwoba.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtxzbkcacg.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtbtpilzyj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagebgbxb.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtvtqvgrrd.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtbqgobahr.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtpnraaguw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtblhiyctu.html

[Q72] 查看索引
来源：http://dali.ppjwa.cn/Article/details/gttmahztnm.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtxuxtuzyi.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gtucrixwkk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gtwnudnysc.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtbhpncjhm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hongshengwenyu.top/Article/details/gtjznlyeyb.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gthyyzbhgu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtwlzbxfit.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtezzmrnzs.html

[Q76] 按天统计
来源：http://dali.nwbrower.top/Article/details/gtycbpuhuf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gtdhpinguy.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtglqwoavf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtapmironn.html

[Q78] 当前时间
来源：http://dali.wangdashe.top/Article/details/gtljayjywx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.redwolf501.top/Article/details/gtdxijnjbo.html

[Q79] 字符串拼接
来源：http://dali.shuidangran.top/Article/details/gtvenwtfjd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcbfsutl.html

[Q80] 字符串截取
来源：http://dali.9152youxi.cn/Article/details/gtbfzfzhwu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtdoseoleq.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtlvjvheke.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtqoshezvg.html

[Q82] 字符长度与字节长度
来源：http://dali.c1oappe.top/Article/details/gtadletcyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtiggwwqbp.html

[Q83] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtfrmbmdpv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlortaeof.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gtzapfxlnh.html

SELECT TRIM(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdmrdjanv.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gtdyuuwbsn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblxgjret.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gtbrjzdrtz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sysykeji.top/Article/details/gtnxqxwonx.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigfzy.top/Article/details/gtjlqkagsd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtpguilexg.html

[Q88] 行转列（条件聚合）
来源：http://dali.havefunace.top/Article/details/gtyrafgduu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gtbewclgwp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.iojbl.cn/Article/details/gtsddmmfgc.html

[Q89] 判断表是否存在
来源：http://dali.shzxlz.cn/Article/details/gtqvvwaxfe.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtbaedorht.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gtkeoxejzm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jiagoushi.top/Article/details/gthyrlnnwf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtgufazzvu.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtbxirqyco.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlelkcisg.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtblekuqxo.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtrxaicaxp.html

set -euo pipefail
来源：http://dali.nanxuanxn.top/Article/details/gtvzgbfdit.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gthqntmycs.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtwbnhnuop.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtvcteatii.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtmlidlxsl.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gtfdjaemca.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtcjuemldg.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtzgtcvsqg.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtmvckpxux.html

[R06] 判断命令是否存在
来源：http://dali.tianlin.xyz/Article/details/gtncylldyx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkjislgi.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtltcyiqcz.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.haohaochexian.top/Article/details/gtpxbyrcyk.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gtrdbkqisb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtilbbmfmn.html

[R09] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gttsxrwraz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtsrazbtib.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtfpobxdbw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gtznenwnxt.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gttdxotmpx.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtkjqsfolo.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtjwnxdztu.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gttmmszcyu.html

*)     echo "未知命令" ;;
来源：http://dali.ehwqpu.com/Article/details/gtkfcucwqg.html


<!-- 参考信息 -->