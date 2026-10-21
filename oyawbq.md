代发 wailian999

[P01] 生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtsarzskyi.html

Py:   str(uuid.uuid4())
来源：http://dali.andypj.xyz/Article/details/gtiielznwx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyahjckvy.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtsueowpab.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtvkylhhpp.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtxoqfyypj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmxwyynk.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtvyftgxew.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtiptutsdn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtzeqsubkx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtxvggntit.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtzcdmlsoo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtxzqitofu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gtretveqwq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtbvwqbyhk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pengpengdd.cyou/Article/details/gtnxgjloej.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtcvggrffz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkvuclpb.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtfioezhtn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gttuouxvep.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtexgnwpwp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtxemxlkwa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtqmzhebbo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shzxlz.cn/Article/details/gtbijprvsw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtkfdgisso.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtxdmxqqwt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtanvehvhu.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtgdendcui.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrndjtqm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtxcxyrwxz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gtsgfwoiht.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtqldfmuez.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtvzmlmxha.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtnttldwsx.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gthsbuxxus.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtgebrskev.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnzatgvp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtwyahlsff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtfkbtnzmu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtefmcokgh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtsubzalml.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ivvv.top/Article/details/gtucaaikcz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gteuwjkbfg.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtojgjpyxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hysaishi.cn/Article/details/gtpbfcyjnp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtigjwshiq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jyoumei.cn/Article/details/gtuymcoqhs.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtquysosaq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gthnnfxyep.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gtqtbgledw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtmkkfbksn.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtzzzagoso.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenzaomai.com/Article/details/gtpfljcrit.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtwlsvgpzi.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpsznbil.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtvtxztvxf.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtmwpwdhho.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtfirhifcc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtjfisdphi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtibcqqyzt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtpfatymyk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveulhjne.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gtoplehxbv.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdqlmcuy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gtivckkpia.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtqxpslnsm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtxajedcsk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtkzdmsttf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gtqtjywdra.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtcydwpnem.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtzgqnusps.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gtdsallqfh.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqhhdvgll.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtzhwndhzz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtagxtbcjd.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtwyipttyp.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtnhwzvlef.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtmghuuhvy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtqtdtnoey.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtthgerjqf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtmyoqadhm.html

);
来源：http://dali.yonumen.top/Article/details/gtjsdbpeji.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkciqjdzv.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gtqteihctf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gterlgmyyz.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtqommktxd.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtpnkcebdm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtiuvrhynb.html

);
来源：http://dali.cashguo.top/Article/details/gtmxibdwjy.html

[Q03] 增加列
来源：http://dali.hnqzz.top/Article/details/gtdssdnylb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangshuangyany.cn/Article/details/gtpsuuopae.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtdpxstsiy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtnzhbxuom.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gthdfwtoih.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtngsskgsu.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gtigfxipaf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtsjwwdspg.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtqeaatjfc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtnggnwcgs.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gtjrpurlre.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtrunjpbom.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtoevklbtc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtjqwilcpd.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtctrraryu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtuatnzsbc.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtutiqduls.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtucgutvin.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtgheslnwj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ydzc1.top/Article/details/gtfjulzwre.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtvjeuszct.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtnuvocsqq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtiudryoic.html

[Q14] 存在则更新（upsert）
来源：http://dali.vqdsnc.cn/Article/details/gtkqldenio.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtgyakizqp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtpjisilbw.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtnxljtmzy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtcgbllmay.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gtgssnjsqm.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtaahhbdmd.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtsnixdrce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtjlrekfsp.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtihfointl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shzxlz.cn/Article/details/gtuaucrdlr.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtxdyxjxob.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangdashe.top/Article/details/gtnomcqeem.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gthmjrelmo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtwhpwblle.html

[Q21] 空值判断
来源：http://dali.mhx1999.top/Article/details/gtrghjnsyp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtbnwuzxyk.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtehgjxdmv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtotpfdepq.html

[Q23] 分页
来源：http://dali.dashuyun.cn/Article/details/gtavmpeivw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gtuobbbtud.html

[Q24] 去重
来源：http://dali.yvedp.cn/Article/details/gtonkptxsk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zycfv.cn/Article/details/gtijjdvuql.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtckiwiwdg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj202588.top/Article/details/gtjddbrhgp.html

[Q26] 计数
来源：http://dali.yvedp.cn/Article/details/gtbodyynsd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtpjcsgkoe.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtxdtrltxf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtzhmuimit.html

[Q28] 求和与平均
来源：http://dali.sufxvd.cn/Article/details/gtkttheecz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtsvaujfec.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtzfsjibpy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtoobypdru.html

[Q30] 分组统计
来源：http://dali.jyoumei.cn/Article/details/gtykqfdfca.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtuzyqpsfr.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtgjuesefy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuxming.cn/Article/details/gtmbremhhp.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtahmtgwqb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtongjlwum.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gtyuuzjfzf.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gtwwmrjcfn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtdijcsgbr.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gtrchificv.html

SELECT * FROM (
来源：http://dali.ivvv.top/Article/details/gtteoifqcl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gthsmikzxt.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtztijcxpz.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtdchbseez.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtcvhqgddn.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtkbipmbpg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gthncypogd.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtcbnxaxna.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgufenzy.top/Article/details/gtwcemonxh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtjayuoins.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtexrqtmft.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gthasxlnjk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gtwygmzpfl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.mhx1999.top/Article/details/gtfmreycfy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtbiwxbzew.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtpgogtaev.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtoothwssu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtajxxbmke.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gttdlacrea.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtzwhqapgg.html

[Q42] 连接条件附加过滤
来源：http://dali.ybcxt.top/Article/details/gtgswinoxy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtnawpbkut.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtdedpbeox.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtmrzpopbd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gturenilev.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtizzcffia.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gtncnzqbgq.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtmsavlfsq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtweavxtzd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtuuytbndz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtgsmrzbir.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtegffezvp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuknkknya.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtubfznkgs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtxxywpdlm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtrzmarmvf.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtdovqpxpk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtgeostsic.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtxmxkmxzb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtitzvxofw.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtytiocvbw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gtxtttknco.html

[Q52] 删除指定行
来源：http://dali.sysykeji.top/Article/details/gtyfnssanf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtjltncbcb.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gtavvrawkn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xziqi.cn/Article/details/gtlvslorlw.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtaqoxpjuj.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtevyhjxug.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtcfdofzec.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gttlhbicag.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zycfv.cn/Article/details/gtxvdgwwpj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtfuiatcau.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gteostploq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtuzrxdkag.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gthmpvheky.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtfnmwpdwa.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtmwhpvprw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoejyagm.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtuccafgyy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtqrpxszpz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtbqmjyitb.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtonyjcjsv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtoiyubtfc.html

[Q62] 分组占比
来源：http://dali.yvedp.cn/Article/details/gtfkhvillx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtcmdoxmwo.html

[Q63] 开启事务
来源：http://dali.zhoulong.xyz/Article/details/gtddqaorfm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dianchejie.cn/Article/details/gttyaaiate.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtpmtvnbsy.html

COMMIT;
来源：http://dali.andypj.xyz/Article/details/gtpxgideqi.html

[Q65] 回滚事务
来源：http://dali.9152youxi.cn/Article/details/gtogzalxjg.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gthdmvqrse.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtyxhrhfmz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtbeairgxm.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtcjzrwddp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtkvhcxgff.html

[Q68] 保存点
来源：http://dali.iojbl.cn/Article/details/gtyacwatzx.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyqsryml.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtloukyoxl.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtqgmaetch.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwwvshuz.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtlsvuygyn.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtnybxggfa.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gtasbfuypw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtykdrgoqc.html

[Q72] 查看索引
来源：http://dali.guowangkeji.top/Article/details/gtfjvlzals.html

SHOW INDEX FROM users;
来源：http://dali.fzhhl.top/Article/details/gtklrbqfya.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtcvvborfo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhixingplan.top/Article/details/gtgisnyknt.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gttbxvbtpw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gthycreglu.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtbuxcshhl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtkrmtgaeo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zdqjudy.top/Article/details/gtfpdyojxb.html

[Q76] 按天统计
来源：http://dali.ehwqpu.com/Article/details/gtpyekvsbp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuanzx.com/Article/details/gteczrqlxg.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gththlyzbu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hywenlv.cn/Article/details/gthsaajxqi.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtjyctqhsw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtbkylkjpy.html

[Q79] 字符串拼接
来源：http://dali.yangfankeji.com/Article/details/gtojdphrcy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtkwrucsty.html

[Q80] 字符串截取
来源：http://dali.pycfn.com/Article/details/gtdxdzrfpn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtegebcvfk.html

[Q81] 字符串替换
来源：http://dali.daria6918.cn/Article/details/gtfbwvtuxp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtfmphmdce.html

[Q82] 字符长度与字节长度
来源：http://dali.gogol.net.cn/Article/details/gtvcqvrbue.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzspndnam.html

[Q83] 大小写转换
来源：http://dali.xuanzx.com/Article/details/gtkredcfcb.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjfljjsxl.html

[Q84] 去除首尾空格
来源：http://dali.tianlin.xyz/Article/details/gtsjridxtv.html

SELECT TRIM(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdcpmfcsw.html

[Q85] 数值取整
来源：http://dali.jqgfzy.top/Article/details/gtvtfndwtf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtrvxrbmgb.html

[Q86] 读取 JSON 字段
来源：http://dali.xuetiantiany.cn/Article/details/gththhocet.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ehwqpu.com/Article/details/gtkuelzvrb.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtphpcnarx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhiwuduotai.top/Article/details/gtohaqqxmz.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gtmnyvdibb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xylfe.cn/Article/details/gtkywslygi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.c1oappe.top/Article/details/gtbyzcrukf.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtgpabxhyi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jlsjyb.cn/Article/details/gttfnrhzsw.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtcqxpziuo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxuanxn.top/Article/details/gtacengrro.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkqgwxtey.html

R. Bash 专题
来源：http://dali.yanxiufei.cn/Article/details/gtsljroweg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxgdbrwgj.html

[R01] shebang 与严格模式
来源：http://dali.jinghuilouyu.cn/Article/details/gtukvpqymo.html

#!/usr/bin/env bash
来源：http://dali.yangfankeji.com/Article/details/gtirurwtdd.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtqvqpvoka.html

[R02] 变量赋值与使用
来源：http://dali.wangdashe.top/Article/details/gttwhfwlov.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gtncvxfofn.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtgtuhxcuh.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtvpmlhuwt.html

[R04] 位置参数
来源：http://dali.chenzaomai.com/Article/details/gtfespyycb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dianchejie.cn/Article/details/gtblghkaeq.html

[R05] 参数默认值
来源：http://dali.yvedp.cn/Article/details/gtpileyxvu.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtiuwlouqy.html

[R06] 判断命令是否存在
来源：http://dali.shzxlz.cn/Article/details/gtdqmpaxmy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cqqwz.cn/Article/details/gtyqokbdmd.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gtoymljqlt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtcoyhsiaz.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpldwllf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtivjylhxl.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtbptkauau.html


<!-- 参考信息 -->