代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbqoplrc.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldtfnuit.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtwbguwisn.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtcooffhfv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtcxuozhex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzrhkhjo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhmglmbu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtkuwgqpmy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtsedhwrbc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtojjnaoyq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gthjzjqqrw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtphrwkmfr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtaidhuxku.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtnouyemee.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtmlxnxide.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtzfdcjffk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fzhhl.top/Article/details/gtadigpccx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtnirlizde.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtuzvjpbjf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gtcvadvpix.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtplsrplva.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtxxkoojnl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtbjpnjqhc.html

[P04] 求长度
来源：http://dali.kuanghao11.cn/Article/details/gtvhngchga.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtkpinxkly.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtkdurqvic.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtxipkavpf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtjvwudlah.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhsdzzpz.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtdspfwcuj.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtaxzpfibx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gttulpekke.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtgzzfwfis.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtbfkfrgpt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtazhjxdvo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtcoiqbvsb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gttncimuhs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guowangkeji.top/Article/details/gtsrbqyrbi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtkytvmkuk.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtwswehpfy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtvmnjlccc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtyerxiyrl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sweek.top/Article/details/gtxovglbld.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtwieunsua.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtqssmdqfi.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdmxrdmfh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtuinbvggw.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gtvdeyhkzp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gtkdpuanfp.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtsqthrmgg.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtmbodfsjj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gttivfatcp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtxlgsbqxb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtsxjjtqjv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtbbzcbwxf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtdjwyhznd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nwbrower.top/Article/details/gtjhhjrfwh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtpxowgbqn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtntuqyxca.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtkrelczxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gteupmcbzu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtuwjfbqfv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nwbrower.top/Article/details/gtodvnomlw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtqhrpznvn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gthmbetgxl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtcfhcniea.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gtkaphcewd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gtiawaayhy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcjnllhxv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtrkransqn.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtyemtvxhl.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtbwqrwqyf.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtdtxmfhax.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gtylsnnthy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gtmadvcybq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gthlzmiwol.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtrtbxwhdd.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtjiqksmhc.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtllnoxiqu.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtokgwkzzt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtflnxxtli.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gtxxdlpexm.html

amount DECIMAL(10, 2),
来源：http://dali.gzhubu.top/Article/details/gtnfqiadif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.bjfxy.top/Article/details/gtgnggcrfd.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtqccoevgc.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtvtxguolt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj20258.top/Article/details/gtwjhygdnj.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtnbiolcxh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtgdfagqrg.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiamoxrie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtvkpupnqo.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtmdzsmmnn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtiwspdjyx.html

[Q07] 删除表
来源：http://dali.xuetiantiany.cn/Article/details/gthlvnsoty.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtngkebtdx.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtfrwkpvwp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtyfqkqhnq.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gtlgswuszv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtdkbwmihg.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtyoznmjyu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtlqclpiau.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqofqwgyb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtcjglayqd.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gtqoiqmxgt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtqabztglp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gtfjhrsexo.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtsskuvgfd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtvofgsifj.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtnldbzbhz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtubxqeoag.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtrilppwri.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtaxqklmke.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtpjmvwivq.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtcyiahxbh.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtjxzaocww.html

[Q17] 条件查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsvhtvrw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gttbecneik.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtxemdgpcx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gtjsupvkmz.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtxdlnlshi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtwymageus.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjqjqxul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtprmetuoa.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtgniryeuj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtjenlpefd.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtvoxpbkeb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtbclirebx.html

[Q23] 分页
来源：http://dali.sufxvd.cn/Article/details/gtqxgulzsr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gtcmzfowbg.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtlqxyfmlj.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtubhsetrf.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtmmjbpysz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtkojuspug.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtihrkxbbj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmqsmgiyy.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gtpdjdlkly.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtptnraxzt.html

[Q28] 求和与平均
来源：http://dali.0kj1m.cn/Article/details/gtnrwypian.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gttcjxmdld.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtxquvtaej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtohlghooo.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtgccslidp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtalkkfnrh.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtqbgfooat.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtcfezswsb.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtnrhleqfz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtelguytnc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtsxteffps.html

[Q33] 多列分组
来源：http://dali.yuxming.cn/Article/details/gtrxzwxjnk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtzqvfejvx.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gtdwtrefml.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtqjtwhtpo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gtangvycbs.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtrfacftcv.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegmouoex.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtguldwiww.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gtftahcnah.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtgfhcrbrq.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtzbdqdqdm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxuanxn.top/Article/details/gtclxbvoxc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtxvofkizn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtrziklnsi.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtbzhsqdjg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigfzy.top/Article/details/gtddphjqge.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigfzy.top/Article/details/gtdgtzhjby.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtbdpwxxfc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtiwtityfs.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtunrvgqdx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhixingplan.top/Article/details/gtdzjrbang.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangdashe.top/Article/details/gtkpxfqdzg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtsbzvklxq.html

[Q42] 连接条件附加过滤
来源：http://dali.xylfe.cn/Article/details/gtrtbhrhxt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtmcadtmuc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gotoacloud.top/Article/details/gtdargaeno.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gttnttodcn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuanvkyol.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtafdukbhb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gtzenfvyel.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtgkukbbbb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtaxvzgyeb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangdashe.top/Article/details/gtjwbgitte.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtuywvxfpc.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtemaxebxo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtkfpwueof.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtghpjrbjq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtpaihkiaj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtxpxlcpvb.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtczcwtboz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtlowhavgs.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtomfggdkz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtdjtyhtac.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtzqnzmazl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtkxgxwsko.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gtvdplgklq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtotqddfmt.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtgratkutv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gtmpgofyjk.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtwfzinurg.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtpvuemmbe.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtcauikdre.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtypkqiwgg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtjkynwxoe.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtjqmdwckg.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtsodrhuzw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtcfsycivz.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gtypjiumgq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hammf.cn/Article/details/gtbvpaecfc.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gtftpvbkwi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtanjnlblf.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtoqcbkpci.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtxhzizapp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtzkpoecvj.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtyccjypdq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtptsonwih.html

[Q62] 分组占比
来源：http://dali.shzxlz.cn/Article/details/gtvvzvbolr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtjgokvbpb.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gtjaareeze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtgdbygqrf.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtacfgqsbl.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtdnpkpmhh.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtavqnatbu.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtsiwuonmy.html

[Q66] 行锁查询
来源：http://dali.ybcxt.top/Article/details/gtetwkcxcm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtxbkpggzu.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayzjnbjz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtogtkytmt.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtmjzztjnj.html

SAVEPOINT sp1;
来源：http://dali.smart0.xyz/Article/details/gttgmdnhuq.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtzpozvjtj.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtotegqyjt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtlrgqlcge.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gtbvcxwqpr.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtsdrjyvrm.html

[Q71] 查看建表语句
来源：http://dali.yanxiufei.cn/Article/details/gteotxgcyt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnqzz.top/Article/details/gtutlosneo.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gtdpppwqos.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmqxzeuda.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtvbjtivpg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtmbeuycsr.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtgwzwbigl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtnrhbvsar.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtwpwzfcwh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnappkoe.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtshkmvslw.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtojxhjcxg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gthphsuvnq.html

[Q77] 时间加减
来源：http://dali.andypj.xyz/Article/details/gtkxvsimcm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhongyouzk.top/Article/details/gtkfngvreb.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtutjxabua.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtjquuniuy.html

[Q79] 字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtdzafswws.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnqzz.top/Article/details/gtgvxromhf.html

[Q80] 字符串截取
来源：http://dali.hammf.cn/Article/details/gtlunvchqn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtpeeifmpn.html

[Q81] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gtkgeaejas.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtgwlfupyl.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwsxfpty.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtqzhfndgf.html

[Q83] 大小写转换
来源：http://dali.yonumen.top/Article/details/gthrpvatwf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtdphfuugo.html

[Q84] 去除首尾空格
来源：http://dali.xuetiantiany.cn/Article/details/gtgdmmfqvu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gthlwgthvq.html

[Q85] 数值取整
来源：http://dali.zhengqikj.top/Article/details/gtpwarnlpo.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtvblwnmng.html

[Q86] 读取 JSON 字段
来源：http://dali.hnxiangtu.top/Article/details/gtealiasnv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hfpthk.cn/Article/details/gtxmxxvjpo.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtqsjhpois.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gtaluucnpq.html

[Q88] 行转列（条件聚合）
来源：http://dali.sweek.top/Article/details/gtsgsrhmjq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gtrloktssr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtrwgpqkpu.html

[Q89] 判断表是否存在
来源：http://dali.sweek.top/Article/details/gtfgegtmeg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtrqnuoaxy.html

[Q90] 生成序号列
来源：http://dali.xylfe.cn/Article/details/gtodtvduiz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cdnleiting.top/Article/details/gtarduvkjr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdytrnrao.html

R. Bash 专题
来源：http://dali.tianlin.xyz/Article/details/gtealatell.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtczurlwiq.html

[R01] shebang 与严格模式
来源：http://dali.hnxiangtu.top/Article/details/gtmhbfgohy.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gtinnqiosy.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gtcspswnzw.html

[R02] 变量赋值与使用
来源：http://dali.zhongyouzk.top/Article/details/gtpkouebhx.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtjkhyhzbu.html

[R03] 只读变量
来源：http://dali.birdmap.top/Article/details/gtckaylabe.html

readonly PI=3.14
来源：http://dali.sxryk.cn/Article/details/gtxbsalhft.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtqlnrxpnd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gtylhpxfii.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtztrqrngb.html

name="${1:-default}"
来源：http://dali.ehwqpu.com/Article/details/gtlwmcnzaf.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtytjqzarj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtkkxzrvbw.html

[R07] if 判断文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbywwctq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtiilepbwx.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtgwahryhr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dianchejie.cn/Article/details/gtjrommdpj.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtjgwpgkex.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtokekjzck.html

[R10] 正则匹配
来源：http://dali.xylfe.cn/Article/details/gtgyhevjgx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtxoufhmyu.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gtqmlfccef.html


<!-- 参考信息 -->