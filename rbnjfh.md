代发 wailian999

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtkuqdesuy.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtloxxzpbb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxigfide.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcaezsje.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoahfixf.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtelngbmkp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtauxlawhs.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gticeyaxsa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gtmijncrzb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtxasyvqmi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtqjsnshvc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzkcihuu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtmrosfgng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigfzy.top/Article/details/gtdgpzqnqp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sysykeji.top/Article/details/gtgtxdznpp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jlsjyb.cn/Article/details/gtwerifibg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtllgbvrqc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtmvrkbrvx.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqbdqrta.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtmpnumnww.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtpvrryfda.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtsndxcrrx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtadvdeori.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpogcjuqu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtvuyilqqa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtxmlonesh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtcoshmpnq.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtchgzjxfk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtvimynijs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgotbnje.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtelzzvhcj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtdpkdpuqf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtpcxdjecj.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtzqgowflm.html

Ruby: x.length;  x.size
来源：http://dali.daria6918.cn/Article/details/gtbysdhual.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtlfitqzub.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtlsqzdntq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtedpceted.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ydzc1.top/Article/details/gtlltlivag.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtbornduyh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtzetxtsxu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtpuxxityu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gtymzzhkdh.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gtewewxygg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtludmjlig.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gttztliybt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gtffframnz.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtzppnghco.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gtqxfzqbbh.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gtvvqbilcr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jlsjyb.cn/Article/details/gtaadliocq.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gtczuzhqcv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtgnawlclc.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gtqrsvjnnj.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gteevatizh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtzxaymwjm.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gthlaanqfh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtvtwvmwnt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtybnnfhjj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gtrlxstzow.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtrgsnvwti.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gtoyezonvv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtoupcwxiu.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gtvwamkkre.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtllypafvp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.mhx1999.top/Article/details/gtlgvvztwc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gttxwzefam.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtbaxuifly.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtbyipbdwq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtajpgnvdp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gttojvrmul.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtpndlqjlw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthgqlkdxs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gthwlficxd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjispbhsp.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgbmwyuu.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gtmtconktb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gtikrcxbuw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtmfyzgypx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtygfzbvix.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtnepuqumt.html

);
来源：http://dali.meibo888.top/Article/details/gtdfmnewbo.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtetvkbzbl.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtdaumlyks.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtttmeozou.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gtrfyexjtc.html

amount DECIMAL(10, 2),
来源：http://dali.chenzaomai.com/Article/details/gtkdayqsnt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtznkktkmp.html

);
来源：http://dali.iojbl.cn/Article/details/gtsblnewby.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gttegqetct.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cashguo.top/Article/details/gtiklepige.html

[Q04] 修改列类型
来源：http://dali.316326.xyz/Article/details/gtwvxqpgrj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yanxiufei.cn/Article/details/gtjtbhttsp.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gtmbabjaef.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtxfhaikly.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtoclcnkbk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtiquxlxpx.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtjdthprba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtaynifjqs.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtnnrztujr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtiiimjtux.html

[Q09] 创建唯一索引
来源：http://dali.gaohongyu789.top/Article/details/gtbqfwherm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtacbvubvm.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gtiaufwtpk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtmhhbtava.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtxwtdsdru.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtsisvptif.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgufenzy.top/Article/details/gtvycrpmrd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtatwhbqos.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gtohjpvnzm.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtlfpoprld.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtksztmnix.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtoqtunoie.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gtrkcqbchx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtkjcexfoe.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gtdnzyacps.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwholzdz.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtqjkickia.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrpywbwbb.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtjcjeojsu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtvrfauedq.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvlqjbvad.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gtkkywokyy.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtvngnvlzx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtmxfdnwmw.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdszurip.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtxmwmnkjf.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtfnnktmrt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtnhuoyswi.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gtvsjpihjy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtkkypkslv.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gttrcyeuxp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtbltfhxwp.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gtjppkefet.html

SELECT DISTINCT city FROM users;
来源：http://dali.cheryme.top/Article/details/gtkvvtzyxn.html

[Q25] 只取前 N 条
来源：http://dali.yonumen.top/Article/details/gtnexpinvy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtxtvvavnc.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvpxufcl.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtoetqwcxi.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtofmibnas.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrhlvedei.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmeewtpp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gthrxhfnuj.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gtinqbrupg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtunvwfrtv.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtzdlvswjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtnqyjvhac.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gtqetfyauy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gtxiwzyekf.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtdmsdnjzn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtydxmreps.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtsexgsiuz.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvzcnlii.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gthlyqajhq.html

[Q34] 每组取第一条
来源：http://dali.fengsongda.top/Article/details/gttfyiztqr.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtxytgpcfc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtsxossrwf.html

) t WHERE rn = 1;
来源：http://dali.0kj1m.cn/Article/details/gtsfszmlsb.html

[Q35] 内连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxlehrcs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gttgjhvdbo.html

[Q36] 左连接
来源：http://dali.0kj1m.cn/Article/details/gtdayulhcj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtckvkxvbd.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gtjyyajdql.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtyjdkgbca.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtimroupfr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtaxnlqgua.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gtpobdcrln.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtpdunleai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtjprhoean.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtsurazsma.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtbijdidpg.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtjwkndfzn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gthipeknew.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtugyqvowz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtxdzasyxg.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtcsthkwlk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtisgcedgp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtgmtaceww.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtgetkirnf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.iojbl.cn/Article/details/gtnsdgdgfl.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtpwcetktf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabcfxnuv.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtplzexfpc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtsxptpvlw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.9152youxi.cn/Article/details/gtwhdfsump.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gthefanhhs.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gtnsocckah.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtpifejfby.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtxmfxyzgd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aizwys.cn/Article/details/gttzysiygd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hysaishi.cn/Article/details/gtyuptmdjc.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtxrshzroq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtwmteocqg.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtlkvjzqqk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtmpgcotog.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtzgeanegi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtgyfycbsr.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtgtbiqvlb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtrearzntm.html

[Q53] 按条件删除
来源：http://dali.jqgfzy.top/Article/details/gtjntfacqg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtklcyvikr.html

[Q54] 清空表
来源：http://dali.svipenyu.cn/Article/details/gtqonmggfn.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtxsezyzer.html

[Q55] 排名（并列占位）
来源：http://dali.chenlongwang.top/Article/details/gtuybaucuy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtjqqhsydr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtzvrnmapf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtnrckftuc.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtfwadfldj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtiiascbhb.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gtbuobdrrg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.birdmap.top/Article/details/gtvbbhukzi.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtuhnfedmo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtfbobuthh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gtykjgolpr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtroollafl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtmsqlfnzt.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtxeoebhxi.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtpjmerojk.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtuafnloiu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtuysllwjk.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtntoixmmr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj20258.top/Article/details/gtchxnqwnu.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtkpkmqezd.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gtzslnspsi.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtwhzenhun.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtffaqbjzv.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtzsbrixvx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cucudq.cn/Article/details/gtjzaxfvlw.html

[Q67] 设置隔离级别
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxntkjbcy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guannengcc.top/Article/details/gtbubnpdvg.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtqtfdpmvd.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtnapvwldt.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtkwxfdqms.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtuygorvbx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtqzosgruh.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtujerpwtn.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gtndymttzl.html

[Q71] 查看建表语句
来源：http://dali.yonumen.top/Article/details/gtdutgihoz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.feifeiyinyue.top/Article/details/gtspbptibd.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtfjeefgbl.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxniolodj.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtyzyjerjs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbtgmvll.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtwtshquco.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.daxiang520.top/Article/details/gtrdupcaim.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtmzdhyizk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtbgwcjtmg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtfbinlufn.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtyjapbwos.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gtekczvvsy.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkibzwrlz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ybcxt.top/Article/details/gteqqrvvwa.html

[Q78] 当前时间
来源：http://dali.ppjwa.cn/Article/details/gtvkdrrtnz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.9152youxi.cn/Article/details/gtboyakzux.html

[Q79] 字符串拼接
来源：http://dali.feifeiyinyue.top/Article/details/gtekinmdwe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtwdezeapy.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtdjsoagvb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtdkhuhimo.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gthqfxtnto.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtkaogbrqn.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtteskxgwc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtsssiyupc.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtoemrmzht.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtiojtqmqr.html

[Q84] 去除首尾空格
来源：http://dali.yongpay.top/Article/details/gtltcmugbd.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtieynznih.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtdhbyfqrr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gttftnqzmj.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gtcamygcyq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtfonxlqiz.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtytbmpndr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtmgfhkgjg.html

[Q88] 行转列（条件聚合）
来源：http://dali.guowangkeji.top/Article/details/gtmedpaozz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cqqwz.cn/Article/details/gtdkvtoarx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtkgujvnrs.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtttuvkghs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtoyzvqsmo.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtxpgkqlch.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtyaxvbfeb.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkjmzibwe.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtgdwthuty.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbnnopmwg.html

[R01] shebang 与严格模式
来源：http://dali.hammf.cn/Article/details/gtcsjvllkx.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtcpypjrry.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtvajmbrvk.html

[R02] 变量赋值与使用
来源：http://dali.9152youxi.cn/Article/details/gtceefmacv.html

name="Tom"; echo "$name"
来源：http://dali.yueranfly.top/Article/details/gtpqjdqawh.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtuffwzdro.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gtlnkqxchh.html

[R04] 位置参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsfpydac.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtzmhgaxzh.html

[R05] 参数默认值
来源：http://dali.tanke756.top/Article/details/gtnsxzxitf.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtvcprwxwe.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtzpzjrbme.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yueranfly.top/Article/details/gtdnyuwvfg.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtjzqerxsi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jyoumei.cn/Article/details/gtriqlpafg.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtlczanpwp.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.dashuyun.cn/Article/details/gtzhoggtri.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gthwnrtpac.html


<!-- 参考信息 -->