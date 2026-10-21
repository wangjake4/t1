代发 wailian999

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtanooyhvu.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gtcyyemlgc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtglguzhby.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtraxrpdnm.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtyhnxyemb.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtcbjdwbyd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtjozvmthk.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtrukencpf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsvipkpdl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtsglsghqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gthimwlhvm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtsmdcpjxw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtvsvmbcee.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtbmdspzsk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtcoidrbah.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyirpvkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtkstdrxyd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpgmozou.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtarbvzzve.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtaqwapvuh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtjsakrqsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtawuwwynz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtgrjdseyx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gtaqhuviaq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtaxraybjw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtliqdbuco.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtyreffalq.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gtyugwswjh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtjafcgvks.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtvqdtvsmq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtrouotoru.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtkmzznovf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtyaekjfna.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gtdqiqlkbu.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtnlsznffx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gttxgthluh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtwxodrzpj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtglemdgfq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gtyebkihjm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtbzjskhae.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gttjfjpubf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jyoumei.cn/Article/details/gtxkkzpawr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtepxuoowj.html

Ruby: a == b
来源：http://dali.aibaodan.cn/Article/details/gtvqaxrgfa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtwlrkzvdo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjycttqlk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtcxlhutnx.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtoyjrbsnk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtlwjiryqi.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtpqkherzm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtoijklhaf.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtszgealxa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxvzjkhki.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtanjpyynd.html

[P07] 防抖与节流
来源：http://dali.xylfe.cn/Article/details/gtenzwjapd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtcnygahhb.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtechudgut.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtdkyqfsez.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtovsclifb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtihasjkmq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqqfngyi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtscopssqy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtyzetutal.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtpefdslyb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtklncaprl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtmhhxtkbi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gtrabvimmo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuwshnkg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtlfzvxvaf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtpswmgwim.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtlchuhiyr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtnbqcodjo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlptbwtqs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtfixqpzye.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvdqmnrlq.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtbatjgjay.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtpaziiguh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtcrmhszph.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemxblnlt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtfvimulld.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cqqwz.cn/Article/details/gtawmotrwz.html

);
来源：http://dali.smart0.xyz/Article/details/gtvhzjaulw.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtvdheqivv.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gteznxedma.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtormltznx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtmooxehoy.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gtzcnafyjd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtjdcbmgbm.html

);
来源：http://dali.xziqi.cn/Article/details/gtistyemok.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtuwqzcdlb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gttjkjanjx.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtvoyomnck.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtldyxwwor.html

[Q05] 重命名列
来源：http://dali.iojbl.cn/Article/details/gtjscnvfrg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtrxrecjto.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtlbvwqqui.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtjezrvttn.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtrtxxeijb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtqgemvfxf.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gtvwxfwxmf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtckzbunkx.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtqplwuwfx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtgbaxdfjp.html

[Q10] 插入单行
来源：http://dali.meibo888.top/Article/details/gtzvaxdjff.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtoewsebuy.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gtfrnkfxqx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtncyygvps.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtofacypcl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gtquaeqjxt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtshizthjw.html

[Q13] 忽略重复插入
来源：http://dali.fengsongda.top/Article/details/gtqvopwisf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aizwys.cn/Article/details/gtedyneqxs.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gtjzouzhek.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gttltozwdz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gtbpryqjti.html

[Q15] 查询全部
来源：http://dali.redwolf501.top/Article/details/gtutizehvg.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtxctsxwgf.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtcmvpvxlz.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gturgqgefp.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtkridmvzp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gtnlmhtsau.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gthlktfdod.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtyjbyiwua.html

[Q19] 范围查询
来源：http://dali.gogol.net.cn/Article/details/gtnamqoiwo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gthcvwhdby.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtobllibvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gtzreiqjjp.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtbzjgedlz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtlpqtkhxc.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtglwjbkxb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gotoacloud.top/Article/details/gtyhngbzbw.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gtxvgpzezi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtylknndnm.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtrvqsxmic.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtjomncslc.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtjsykgyim.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtqhhcpjhs.html

[Q26] 计数
来源：http://dali.yongpay.top/Article/details/gtbgufimyp.html

SELECT COUNT(*) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtssjlkqoz.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gtntyhncsq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gttzivbsft.html

[Q28] 求和与平均
来源：http://dali.mhx1999.top/Article/details/gtnexfzvrj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtyvhjrfdx.html

[Q29] 最大最小值
来源：http://dali.quarkkingdee.top/Article/details/gtxfybzqto.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvpfrefen.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtfyorhifi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtwvjwqrbh.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gttdcvnkal.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtbwieajgb.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtlaeovkex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sufxvd.cn/Article/details/gtxezfxmdk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daria6918.cn/Article/details/gtwfvrcpah.html

[Q33] 多列分组
来源：http://dali.yueranfly.top/Article/details/gtefzdhcob.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gteaidbvmf.html

[Q34] 每组取第一条
来源：http://dali.aizwys.cn/Article/details/gtirzquwpn.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtgotjbyni.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzzucryl.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gtnvzpswzd.html

[Q35] 内连接
来源：http://dali.yvedp.cn/Article/details/gtlijyontc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtwarsrxpt.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtpvyksuyk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtstljdwaw.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gtfgbusexs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gteczsakzi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtsbbcxzrw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtvepoysky.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtdotzaxfv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhoulong.xyz/Article/details/gtdkmflqft.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtjqmwuvbl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtoqiwcdwp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtswwowqhk.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtiplsivwo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.9152youxi.cn/Article/details/gtgeomwiha.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtjwqtgydh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtidqipdkz.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtdgbljomk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtqehfghqx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gtpvccnvqp.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtuczchhbs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jyoumei.cn/Article/details/gtgypvjlph.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gtebpohire.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtyedmmxpc.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gtdjnddwqy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtmxxmjuob.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtkhnycclm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtafwojojp.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtnabzgwwz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtrixhbzje.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtggefxdnn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtmaxaiqld.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ehwqpu.com/Article/details/gtexdvsgye.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtjdjdadkk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtljqlshjw.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gthpwmwmhs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gtfmfncigr.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtyabccbej.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gtxtjwpfqd.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtsfunwoxs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtyyosqilk.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtnngnmzny.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtbwscacdd.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gttflmjhim.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtwpyxltjc.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtaghcaaqr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtmcdhqtkv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtevcbhtzk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtqipfdqkb.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gtzuwagrog.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtobduswog.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtsyzutjon.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtlevbiddi.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gthyvuuwyd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtrmmpslcl.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gthgxtcxsn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gtkuisfrey.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtgddfmbvx.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtpbozxycp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtpbldrakw.html

[Q62] 分组占比
来源：http://dali.birdmap.top/Article/details/gtzfegncha.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukwohoup.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtqttygjgg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gttbqofffu.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtpdinemhk.html

COMMIT;
来源：http://dali.hysaishi.cn/Article/details/gtjfnieumw.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gtrvdntzlq.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gteknegqww.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtingotnyl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtoeuoqffo.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gtyxwxvaeu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtjooprhbz.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtvtvsskuf.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtkjtrcbuu.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gttlzwhsqf.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtjxlhiqku.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gtefceulat.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtgramnwgi.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtnxeibafn.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtwuixqfyw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntjdzasd.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtjkpfvils.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtvbjdaqok.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gtumzmjqwv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtotxqxvsv.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtxtjngkcu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gtoticonxe.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtklsiqhus.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtjplvgubp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gtbtosgqsy.html

[Q76] 按天统计
来源：http://dali.wangdashe.top/Article/details/gtzdznkuhz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtbftftgrs.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtwmurfalr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.vqdsnc.cn/Article/details/gtkonwuufx.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gtrmiwhitg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gtpgfizsky.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtszwxtcoj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gtjfiaezek.html

[Q80] 字符串截取
来源：http://dali.chenjidiqi.icu/Article/details/gteiijnxwg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtxkczlomh.html

[Q81] 字符串替换
来源：http://dali.dianchejie.cn/Article/details/gtksrfxjuu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjwkxqpjx.html

[Q82] 字符长度与字节长度
来源：http://dali.pengpengdd.cyou/Article/details/gtgdidzajr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtgwwoepzr.html

[Q83] 大小写转换
来源：http://dali.yueranfly.top/Article/details/gthswkqjgk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtvlnnnxzy.html

[Q84] 去除首尾空格
来源：http://dali.jianghu66.top/Article/details/gtfcwqihdh.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtlxntbhhl.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gttoyrqjii.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtjwfimgcy.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtjyrgrsdi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzatygeot.html

[Q87] JSON 字段做条件
来源：http://dali.pengpengdd.cyou/Article/details/gtmxyouhee.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtjmzlbqiz.html

[Q88] 行转列（条件聚合）
来源：http://dali.wangdashe.top/Article/details/gtzgrjxadh.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtdxhydedf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtwuylwxbz.html

[Q89] 判断表是否存在
来源：http://dali.snrcjt.cn/Article/details/gtukeomqjt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtonlsyacj.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gtnjwyyafn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.redwolf501.top/Article/details/gtzevzuruz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdrinhmtx.html

R. Bash 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtihvhnyot.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtnqxkviib.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtkpfuxugp.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtcqqndkzf.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gtxqpljjyo.html

[R02] 变量赋值与使用
来源：http://dali.nanxinkj.top/Article/details/gtruhvbejo.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtovtvccaq.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtnrwsljja.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtkazlyovp.html

[R04] 位置参数
来源：http://dali.zhoulong.xyz/Article/details/gtovihzsrc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.havefunace.top/Article/details/gtiqqebypf.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtmqyzygra.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gtqmyumapa.html

[R06] 判断命令是否存在
来源：http://dali.zdqjudy.top/Article/details/gtmmsjelly.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtyvttunvb.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtdkflywrn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtnullqtub.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtmepdvdrl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gtsbdusqht.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtfeyudwnr.html


<!-- 参考信息 -->