代发 wailian999

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahhfajvj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtprhatfwm.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtphgqtthl.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbuybxzaz.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtdebhwiba.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtnnqhoqmc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtsphenisw.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtfjkrlkfl.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gturzyhlwr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtgyouledb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zdqjudy.top/Article/details/gtovatcrcl.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtnqafdndn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yuxming.cn/Article/details/gtpixmbrmd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtdzknhyms.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtjztbxynt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gturyjtmuf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shzxlz.cn/Article/details/gtxjvdbtqm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtzovwekut.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtyiaykoos.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtecolkcbf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhongyouzk.top/Article/details/gtzximpwmy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gtqsswuuiz.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtcpxlldir.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtsrxwbzci.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtardvthlg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtmhcwqrii.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjknuartt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtdalnonvv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.andypj.xyz/Article/details/gtqrqrufvd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gtxrbudlkm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtwsgvrxjq.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gttogkczgr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtkeyokgei.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gterlqitwn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtdhzkqtfo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtbmshzyzd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtocdtuwkd.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtssusslwb.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gtttosnjld.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtifagugds.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtzqqubrlw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtfergnqrt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gtzmkpvzoc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtbwmyefaz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gttahpcavs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtkhilxrvs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtnvppvddo.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtqfpkuvdd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtomocwhxg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtipegetli.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtilijctgm.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtqvxxifcu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gtbnlbjzyd.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycigkeew.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvsbyhkkn.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtlaqdrstr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtpunjcasl.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtfvghtloa.html

[P07] 防抖与节流
来源：http://dali.aizwys.cn/Article/details/gttpqwiwrt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gtwetzmjqr.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtlwavizzy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gttxbnmmvk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtibbhxovw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtoypalbcq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gtgnzdadwv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ppjwa.cn/Article/details/gtluwpmqlq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gtidpqpyux.html

[P08] 处理浮点精度问题
来源：http://dali.jqgufenzy.top/Article/details/gtxxsqjguz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gthdwdwyyp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtuozmwjzw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtatawjjqn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtcbwsmhzb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtxtsecobo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtgroodqjh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sweek.top/Article/details/gtowflhxql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtiplajsff.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrxojvvju.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtswwipure.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtdcnbefpu.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtrtdfcdgu.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtzmsosoxw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtiykutnfz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtowxzfwbl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtwmeokrcb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gogol.net.cn/Article/details/gtaysdixux.html

);
来源：http://dali.yuxming.cn/Article/details/gttpswzxws.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gtfregjrbp.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtyyjzwwdz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtopivjkep.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtazltjful.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gtdmldkvzh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtfkjxaeuq.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbzuamxh.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gttfiqwhdx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtbgsmtayn.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtrifhwhzu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtlxcqfrne.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gtgatiyttz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtlqogfbin.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtefstqjui.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yvedp.cn/Article/details/gtsejufvrv.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gtivrlsngp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cdnleiting.top/Article/details/gtkezxhwtu.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtyoszulwj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtmoojekqe.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvzzhfkf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtyibxxvrz.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtmrmcwvkj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtfccmzetn.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtodzkohli.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gtntewesgb.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtfltdgmem.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gthxvyfdxw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nwbrower.top/Article/details/gtcpelcngy.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgyunrne.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtockulnqz.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtgqgcyjwo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtaomfcipu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtaxkkytzh.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gtfbckhzsh.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtoltzcysb.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gtcbsbxxdg.html

SELECT id, name FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsufoprau.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gtjbnuerdm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gthbnrfqit.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtawvwzzdc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtlukiswvr.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtgqsrqeuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuanzx.com/Article/details/gtxboiunuf.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtfbqglqti.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtpqugdzux.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gtupgfgnxs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gtddqekbek.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtegovzfza.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtesuvnflu.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzzhwwov.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtdsemkfdv.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gtyujvivid.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtfittcwug.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtypoqjjsu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gtvkryfucg.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopvpkucs.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtbwylnimt.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqkiejqb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtymfbuail.html

[Q28] 求和与平均
来源：http://dali.dashuyun.cn/Article/details/gtqrmnlzwm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gthjdvyjys.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtmphjrsxz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gthzzqjosv.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtmzujihlo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtckphbond.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtoafiztxe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gtdaxnxpqh.html

[Q32] 分组拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gthurottgr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtuwtoehrn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gtwzkdejkr.html

[Q33] 多列分组
来源：http://dali.daria6918.cn/Article/details/gtamheovcj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gtjfhcmyzv.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtozccdbby.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtkwtshlol.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtvapufzjo.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtxjyipvqt.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtviahssqv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtmmaignbx.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtkfowmzib.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtfocdunhf.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gttklvbuge.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtxjhoktlm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtkrkphpgs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtmsvarlop.html

[Q39] 自连接（查上下级）
来源：http://dali.jianghu66.top/Article/details/gtrupufjct.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtluzuepys.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gtlpdcmsuz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtirrbcqip.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gthosjdxtd.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtkdqqeiuh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtsvvwvopl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtzxejtkkb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtbwyoupvh.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtucngxnff.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtppzvbkcs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgufenzy.top/Article/details/gteubsjpfg.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtuwtwuzpr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtbzkqorve.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gtwwfwyjxp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ppjwa.cn/Article/details/gtvajbohtq.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gtpsbjioku.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtuqmvvwdo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gtoewqmqua.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtnpyxoigw.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtwdxlxxtk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gtxheuxduh.html

[Q48] CTE 公用表表达式
来源：http://dali.cashguo.top/Article/details/gtjcurblsj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtjhhushhu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtvicgjmna.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtozlwlmbp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gteqxsfbqa.html

[Q50] 批量更新
来源：http://dali.meibo888.top/Article/details/gtxrzynhpy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtzuvubrfk.html

[Q51] 用子查询更新
来源：http://dali.ivvv.top/Article/details/gthtdlfbve.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtjxxcvbth.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtbljqkuub.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtzmdcjldg.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtegkorxck.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtbrigvobm.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtiystbung.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbcciehk.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gtwmpwbyij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtqhinuqbn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtaqefkwdl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtzexnwqtb.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtegfeykij.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtizkeghbr.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtifxyfpek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gtgpjiqkts.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gtdxsopugu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtxvccsrws.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gtxmlfewfb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtlslwvloi.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtgtepzrfh.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtamfqacsa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtglwrqkju.html

[Q62] 分组占比
来源：http://dali.xylfe.cn/Article/details/gtxmecbqzd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtqqkumbcy.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtwyamldow.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sufxvd.cn/Article/details/gtsvfvjdxm.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtmgwbycwv.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gtdpepnhib.html

[Q65] 回滚事务
来源：http://dali.yongpay.top/Article/details/gtvienczhx.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtptqwqdcg.html

[Q66] 行锁查询
来源：http://dali.sxryk.cn/Article/details/gtgpmbpumj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yangfankeji.com/Article/details/gtwfbhjmzu.html

[Q67] 设置隔离级别
来源：http://dali.cucudq.cn/Article/details/gtqnpukmya.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gttwrevyii.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtbovwgqum.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtkbstwfuu.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbxgdckv.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtsoqfqgfs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtxtpjpspq.html

[Q70] 更新统计信息
来源：http://dali.xuetiantiany.cn/Article/details/gtzmjuztqa.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtnkqyucrp.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjzeovlf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtaguhngbs.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtijagvyov.html

SHOW INDEX FROM users;
来源：http://dali.yj202588.top/Article/details/gtbmatlwnl.html

[Q73] 查看表状态
来源：http://dali.yangfankeji.com/Article/details/gtguerrmby.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtrwhpwnih.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtjjdedial.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gticinbffd.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtbxenfjpf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtqeqithld.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenjidiqi.icu/Article/details/gtxnesheud.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtuyncizqv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pycfn.com/Article/details/gtfmxauayq.html

[Q77] 时间加减
来源：http://dali.jianghu66.top/Article/details/gtsvdxvrul.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gtoxqcsudv.html

[Q78] 当前时间
来源：http://dali.svipenyu.cn/Article/details/gtsyptmvou.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gtjefeuxsp.html

[Q79] 字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtdhwtfkgx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtnkjhlxme.html

[Q80] 字符串截取
来源：http://dali.cashguo.top/Article/details/gtlinikbxq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtydyrsvwt.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtmjqqgsnf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtqtmrwnin.html

[Q82] 字符长度与字节长度
来源：http://dali.hnqzz.top/Article/details/gtcfyzojcl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtcaowqmju.html

[Q83] 大小写转换
来源：http://dali.fengsongda.top/Article/details/gtzofwwzja.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtgvlxxfhx.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtascxyvwh.html

SELECT TRIM(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmnuxwuts.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtuiukbwmf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtscdyoncu.html

[Q86] 读取 JSON 字段
来源：http://dali.shuidangran.top/Article/details/gtzbjngvti.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtfqtqfqye.html

[Q87] JSON 字段做条件
来源：http://dali.9152youxi.cn/Article/details/gtehmxxnft.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhixingplan.top/Article/details/gtfkpyupng.html

[Q88] 行转列（条件聚合）
来源：http://dali.ybcxt.top/Article/details/gthopisvdw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtfhvgcikx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtthnmktlc.html

[Q89] 判断表是否存在
来源：http://dali.dashuyun.cn/Article/details/gtmivyfjel.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtyjviieph.html

[Q90] 生成序号列
来源：http://dali.jinqigfzy.top/Article/details/gtafrgdkkw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtcafanjqy.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtuqulzjla.html

R. Bash 专题
来源：http://dali.sysykeji.top/Article/details/gtswnkblgt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxpvwvwxd.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtcnrruypo.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtrgulhril.html

set -euo pipefail
来源：http://dali.cheryme.top/Article/details/gtexdyewcn.html

[R02] 变量赋值与使用
来源：http://dali.pengpengdd.cyou/Article/details/gtmwcvdkha.html

name="Tom"; echo "$name"
来源：http://dali.nanxinkj.top/Article/details/gtchiapwja.html

[R03] 只读变量
来源：http://dali.haohaochexian.top/Article/details/gtmekawbsv.html

readonly PI=3.14
来源：http://dali.xylfe.cn/Article/details/gtutsbcheg.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtzwyltcqd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.quarkkingdee.top/Article/details/gtlcghdldb.html

[R05] 参数默认值
来源：http://dali.shzxlz.cn/Article/details/gtufbfrrnu.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtggtqjclt.html

[R06] 判断命令是否存在
来源：http://dali.yangfankeji.com/Article/details/gtewtxhffd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtiknepxkv.html

[R07] if 判断文件
来源：http://dali.iojbl.cn/Article/details/gtmkjtpdvh.html


<!-- 参考信息 -->