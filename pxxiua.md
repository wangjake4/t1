代发 wailian999

TS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gttxhvmxut.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvtezbet.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtdvheufca.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtgxhktart.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtizeysudt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyerwfve.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gtakdgsrfv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gtvuyckdun.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtfpslgziv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.svipenyu.cn/Article/details/gtcxlwjjly.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtkeakvycu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtlqpiipxx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gtxvgneiiz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gtagmghfxv.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gtjrcqstpa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbnitpuf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gtguivaemx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtzyqkacuc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtdomnozvr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtpouwpmwk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hysaishi.cn/Article/details/gtyxlmmgkt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zycfv.cn/Article/details/gtjqobbfou.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtgvxhftyt.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtvqunyofk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gtywvadebv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gttzdxfqls.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtxdzeewwn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtcuxoijtl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gthceolaod.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtdrxsrzug.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtcecyyhnu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvbetqup.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtsqqxlhyx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtmyyzwcvz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtmqyoytfz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtlvmlnnfv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtglptoujt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtaalvwwhv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtgzgrmmii.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gtuciusigv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gtwszrmwmi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtyyhbhxzh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtyclbdsyo.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtdjurrusd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258.top/Article/details/gtfistrdez.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtqdlillxe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtxmibqxlh.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtzkmtuzbc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtkpidsbtb.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gttrcqzldl.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtseuymgfd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtujehaupy.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtoxssqddw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtkfzbykjj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtebzouqbg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgbosqolo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gtpgxwgtyo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtgcixlkcw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtoksjrnla.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtzpypawqq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtlwigjkel.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtoycomoev.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtiswgwkde.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkmkzfznv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtbppfahkk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shzxlz.cn/Article/details/gtygkcsdtb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtgbzbxzju.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtvlbkxoyt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtzfshtmis.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtfkmupjdx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtmpwkkbmy.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtvwyzranj.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtldpgibjc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtxicsisdf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtuzwljqxt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtstehlnqx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpggmkqqd.html

);
来源：http://dali.meibo888.top/Article/details/gtjqqszbgt.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtsxydkqgi.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtkpqbczpk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtnplxaumt.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtmesvkprj.html

amount DECIMAL(10, 2),
来源：http://dali.xylfe.cn/Article/details/gthwemkygs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtebpnsgsm.html

);
来源：http://dali.redwolf501.top/Article/details/gtcsvyvqin.html

[Q03] 增加列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoyyfoiq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtskaeawbt.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gtxpsyhwll.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.iojbl.cn/Article/details/gtpkqnvpmu.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtzkashajv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gthbemqtbd.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gtjtdlvjyt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtxjwqqibh.html

[Q07] 删除表
来源：http://dali.pycfn.com/Article/details/gtahwzmrjw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gteshnuiuh.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtsnkitxfb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtknhzmgva.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquuwxqqp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtfalbdrqr.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtmelevsik.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtksbfvfgf.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gtzwuorvhh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gtfsyhxzqb.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtbwmbeusw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtefaigkws.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtuasbhbmi.html

[Q13] 忽略重复插入
来源：http://dali.jianghu66.top/Article/details/gtrbapilfm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtzwvsxsxe.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhlzjsen.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrxgbdxp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtpkbohkbp.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtquemoiym.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtarirntil.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtpkcivzul.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gtvebvcvlg.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtedbluqpm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtogebumfr.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gtlkqbirzu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtmatmgudo.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtjmjeemlc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtmvlampxz.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtcfmgbojh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hammf.cn/Article/details/gtkseippyq.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtmndufstf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtdjthcwmi.html

[Q22] 排序
来源：http://dali.zdqjudy.top/Article/details/gtqltnbqhx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtzihnkafr.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gtcevvfukc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtujfyailu.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtbencrlbr.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtigcbclrf.html

[Q25] 只取前 N 条
来源：http://dali.chenjidiqi.icu/Article/details/gtobvsdofe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ybcxt.top/Article/details/gtbeqcddae.html

[Q26] 计数
来源：http://dali.zhixingplan.top/Article/details/gtfkkizjnk.html

SELECT COUNT(*) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtophglbgc.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtesxlhiwj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtmdedvdwq.html

[Q28] 求和与平均
来源：http://dali.cdnleiting.top/Article/details/gtimxghcuu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtfptoawec.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpbpxdkm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtyhcggebn.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gthtanjzkv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtlhadowrv.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtespalafh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtmeejhhgh.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gttaeekecc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtugbposwf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sweek.top/Article/details/gtgcytvyjq.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtblphaodc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtnmyluvvy.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtpuudfqiv.html

SELECT * FROM (
来源：http://dali.jqgufenzy.top/Article/details/gtysncieot.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtruuzexbo.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtgkjgeznk.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtajniushz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtehnjvgnn.html

[Q36] 左连接
来源：http://dali.meibo888.top/Article/details/gtoknvvygt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtnejjiqar.html

[Q37] 右连接
来源：http://dali.ybcxt.top/Article/details/gtgwaeczvq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtbofrptaw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtpnoisisn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtsstmvwxi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhixingplan.top/Article/details/gtiieedlzj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gteevvlhod.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtmhahndgo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gtrxducyqc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuanzx.com/Article/details/gtbrdfmyay.html

[Q41] 多表连接
来源：http://dali.cqqwz.cn/Article/details/gtaxjcymgd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtbgnqolqa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gtjyloivxd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtpacedgox.html

[Q42] 连接条件附加过滤
来源：http://dali.aizwys.cn/Article/details/gthcmrqqrm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xinyue.icu/Article/details/gtcyhwinpz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gtcofpptdz.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtrotgptop.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtvunfdssn.html

[Q44] IN 子查询
来源：http://dali.gaohongyu789.top/Article/details/gteevqwvxf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gtwefruklb.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtpydupluu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtvtdtwwza.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtgpvuiiiu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtgepfrqgv.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtnpjprqar.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gtlnfidhzq.html

[Q48] CTE 公用表表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoukqjtcc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gtarzxhkrx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yangfankeji.com/Article/details/gthzxuwstr.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtstuclfpc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtmphxutkr.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtlapsbahj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzkoavjo.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtehtodkge.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtofwfimxy.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtnyftsalf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtrzprotei.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehayvanc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwjidyuh.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtpvscvdnf.html

TRUNCATE TABLE logs;
来源：http://dali.shzxlz.cn/Article/details/gtusirapzf.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtnvmwoppz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtksnswfea.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtuxogsdjz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtivnkfwey.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtglznnvai.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtceljypvi.html

[Q58] 累计求和
来源：http://dali.pycfn.com/Article/details/gtkvdghtqv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtieuhngud.html

[Q59] 分组内累计
来源：http://dali.cdnleiting.top/Article/details/gtmfdkutgt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtiqsuturd.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtmibfvjty.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gtsvggaekw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtyvpdwqmj.html

[Q61] 移动平均
来源：http://dali.9152youxi.cn/Article/details/gtnwacpbnj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtgnutvqnb.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtpferkfja.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtixcwxjuf.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gteurferye.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtkygwxcvy.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gtovtqmypa.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gtnvqtcoko.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtufdipfxa.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtkenfazfw.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtcsdfkyid.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tanke756.top/Article/details/gtwnnzscii.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtsucyrlqm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.quarkkingdee.top/Article/details/gtwosagkao.html

[Q68] 保存点
来源：http://dali.daxiang520.top/Article/details/gtpisnkgan.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtpryshcsu.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljwqmywj.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtqvlaiiru.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtgyncolrp.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtdujaafzr.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gtnvkhilqf.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtofxbjyai.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtgnzwfbmi.html

[Q72] 查看索引
来源：http://dali.wangdashe.top/Article/details/gtkgaccoff.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtpmuzwnos.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtatftuwpa.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hongshengwenyu.top/Article/details/gtwzmfkoxk.html

[Q74] 强制使用索引
来源：http://dali.hywenlv.cn/Article/details/gtcqblzvhk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtkgjyvwwg.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtblozdwdj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtwmsntqbr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtozfekdvi.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtchbgjviz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtvhzcnftt.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtrjfirptw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmgujcpg.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtzntdiljr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gtkfzmpvcq.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtvewmclif.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtpisljkzo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gtfciktkrw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtdaluxhry.html

[Q81] 字符串替换
来源：http://dali.redwolf501.top/Article/details/gterrgfgvf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmaqwbbta.html

[Q82] 字符长度与字节长度
来源：http://dali.cheryme.top/Article/details/gtqzankhmw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtnrfvndff.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtfjfttawe.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtycqvhgmk.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtsrluqonh.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtphixxtxt.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtkodbjnjv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtdicjgnhy.html

[Q86] 读取 JSON 字段
来源：http://dali.xinyue.icu/Article/details/gtkhjfsekh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sufxvd.cn/Article/details/gtemyspwhf.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtxdthvjtg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ppjwa.cn/Article/details/gtcdsfpqqo.html

[Q88] 行转列（条件聚合）
来源：http://dali.hysaishi.cn/Article/details/gtipuudxyq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cucudq.cn/Article/details/gtkqiqwxpb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtgcjpcsos.html

[Q89] 判断表是否存在
来源：http://dali.xinyue.icu/Article/details/gtmsdoltwp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.mhx1999.top/Article/details/gtbaycjmsa.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtxmlvzkuj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtaijnzngw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtayqhzodi.html

R. Bash 专题
来源：http://dali.smart0.xyz/Article/details/gtpxcbkvin.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtoqawexpc.html

[R01] shebang 与严格模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahbxuquj.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtrtypavss.html

set -euo pipefail
来源：http://dali.quarkkingdee.top/Article/details/gttnksyyam.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtdtiflxkp.html

name="Tom"; echo "$name"
来源：http://dali.yvedp.cn/Article/details/gtwdmtehws.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtgxaswhyd.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtujeezorz.html

[R04] 位置参数
来源：http://dali.mhx1999.top/Article/details/gtvqyeevbl.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tian-w.cn/Article/details/gttzqjtmcs.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtagjlxviz.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtagrjwqmf.html

[R06] 判断命令是否存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfuhoxjm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtgdgknars.html

[R07] if 判断文件
来源：http://dali.jiagoushi.top/Article/details/gtcpqrbxsn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtgbpzhbkf.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtvynsgrmf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuanzx.com/Article/details/gttltylzku.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtxeojbrhr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtcnrfusqu.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtueiidldf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cqqwz.cn/Article/details/gtdnkfpgzv.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtjjdbwiid.html


<!-- 参考信息 -->