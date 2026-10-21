代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gttofhbklj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gttmwxtwhb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtrmitwiwq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtmvqpssaz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtxepknajj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtbbrrsbba.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gtrqchgswh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtzxvwgpxy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gzhubu.top/Article/details/gtehpxekik.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtxacakqxz.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtxffnuxve.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sysykeji.top/Article/details/gtwyrkspcl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtdmiflomb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtijzwebmc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtefyilvep.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukgkhudz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgfzy.top/Article/details/gtjpbqgypw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.smart0.xyz/Article/details/gteqspidec.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yvedp.cn/Article/details/gtuaxjycuu.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuefatsrc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ybcxt.top/Article/details/gtymeycogy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtcwscovdd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtzmmvqbac.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnysenjbq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtegmauqal.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqnjocnn.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtmwklhgng.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhnjvrrd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gtmhkpjqhm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtejsuudcg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gthdbjlrng.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtuoaknqap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegvihzry.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatvtornu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtqztwuhux.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtucnvrwdl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gtzooufdbr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gtfhjsjroj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtabqdqhvu.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtelbakqij.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtcexczypw.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtjgpnrpur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtjiogvpgi.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtupruagmm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gtnnxhxdpc.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymcipfxf.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gtzwdnzdls.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtjmboshgk.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtrisdwkmi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtizkarhjf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtwwkeadcr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtbgevmqyk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtxsrvbotc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gtfapgtstq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gthlunbhzu.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtuealsxix.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtbnajwguu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtszhlumrp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtvexlwffa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtoiyejepr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtoqilussu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtnjtdadid.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtdzxqelzp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtrxokrqxi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmqwwcink.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gttwsrpgsk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmqhkkrbf.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gteipxzscs.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtyxroniyy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtiajvyohv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtotbaeguq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtumpqgwln.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gtohwfenqk.html

);
来源：http://dali.jqgufenzy.top/Article/details/gtpterliox.html

[Q02] 创建带外键的表
来源：http://dali.xuanzx.com/Article/details/gtyearrlqt.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtvadseagw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlkhidsb.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtmrtfnamn.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtzkzlyfmc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gtmaukkexp.html

);
来源：http://dali.hysaishi.cn/Article/details/gtziieockb.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtbtipjvmd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gtirzsnrmr.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtjiaabjfj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtzyvlzacj.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtvuajbsnm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtfqicngft.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtipkhnuys.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtguggoxnq.html

[Q07] 删除表
来源：http://dali.ydzc1.top/Article/details/gtyklwhaid.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gttwsdeyoy.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gteopxygwb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtneecxhxg.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gthxtalrku.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gttbrwfqdj.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtaazmujnp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gtikqdygtj.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtsclaxkig.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtpdqhnkdq.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtouyfvmez.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gthesqvibk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtilowjoyw.html

[Q13] 忽略重复插入
来源：http://dali.ybcxt.top/Article/details/gtkznhlvxe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtadmqdknj.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtpcqkxnpb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gtxafoivpg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtqoooobck.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtrybisrxy.html

SELECT * FROM users;
来源：http://dali.xinyue.icu/Article/details/gtlojqkmuw.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtqjwrjbip.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkpunocvh.html

[Q17] 条件查询
来源：http://dali.jianghu66.top/Article/details/gtyvvxgayv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgkeammwd.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtuircpyfx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtkuqkqpyg.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtnulartfn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgjarxpt.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtggptbnkg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtituvhjgm.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtguvgphuu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtayqcunei.html

[Q22] 排序
来源：http://dali.yueranfly.top/Article/details/gtfsumjzqf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnqzz.top/Article/details/gtvxlndwkj.html

[Q23] 分页
来源：http://dali.tianlin.xyz/Article/details/gtgtscdohs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtnlqkpoht.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gtqplqvwcz.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtojltdjle.html

[Q25] 只取前 N 条
来源：http://dali.yj202588.top/Article/details/gtsnoogewa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtzfjfzmse.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtsggbkodi.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtlkaedbiu.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtoeecpsre.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtnexdduof.html

[Q28] 求和与平均
来源：http://dali.ydzc1.top/Article/details/gtmunrmmvh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtujgnidnt.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtncugtldv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtnewpbzvq.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqlvtbiu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtrdhmikoa.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gttwxdkgzc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gttarqlyqp.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtswespnkj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtmytvdzia.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtiqnnrsvw.html

[Q33] 多列分组
来源：http://dali.sweek.top/Article/details/gtqqyhbfih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtjscgoteo.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gtrurpnylu.html

SELECT * FROM (
来源：http://dali.dashuyun.cn/Article/details/gtgqonfmrp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.feifeiyinyue.top/Article/details/gtiztwrtnf.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gtcmmuowvf.html

[Q35] 内连接
来源：http://dali.redwolf501.top/Article/details/gtngqvmtxw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtuxseimxa.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gtegmsxgqs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gttzqgazxi.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtfwkcnydd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkfrhzws.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gtubbuvylp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gthcwgunuo.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtnfheupti.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gtontouviv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hywenlv.cn/Article/details/gtozogstlz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtaehrcujq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeattrep.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtspdasuxd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtieapsqah.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gtpnhdqyhy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosgajiqc.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gthsxogcny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtqqmqeiqe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtmskhhsin.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gttvjshcur.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgvujlpo.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtqxlpsaxb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtbgmuoair.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtdysgbmcs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtmirpbtad.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258.top/Article/details/gtcgpigbam.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxuanxn.top/Article/details/gtowjlavft.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtgnhtpevq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnqzz.top/Article/details/gtlplgkbge.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtbmjdxske.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cdnleiting.top/Article/details/gtvzmuvehk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.9152youxi.cn/Article/details/gtwqfsioxi.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtstuyubkp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtjvsfhien.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtgdmfbxwi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtrqgvhhkj.html

[Q51] 用子查询更新
来源：http://dali.cucudq.cn/Article/details/gthcjerzys.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xylfe.cn/Article/details/gtzmmegand.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtzbstvvzb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtlsaonuhs.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtadsnsftx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtdwmfhsjj.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtyuudbims.html

TRUNCATE TABLE logs;
来源：http://dali.xylfe.cn/Article/details/gtekwfbppv.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtbbpoxkrp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtyhkvtnoi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gtwcvlyzew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtdxrhtbxi.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gtdffozkxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtljpwosku.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlexvlpxd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtqfeiwmre.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtnjrkuuha.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtamnxruvr.html

[Q60] 取上一行 / 下一行
来源：http://dali.dianchejie.cn/Article/details/gtpnqmbsgu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gtwseqzdrq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtgdkenbnw.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gtwlgwgcmf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtdanfimud.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtjvobrvus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtucvhogzo.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtxanhjafs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hysaishi.cn/Article/details/gtugqcwgdq.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtxqqwxdjw.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtkbwdevte.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtjhucptqa.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimyyuhwt.html

[Q66] 行锁查询
来源：http://dali.gotoacloud.top/Article/details/gtfxauanca.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtmotfbhuh.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtjactvpgp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtbmmbiz.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtxfccqagp.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtjrmvjkmd.html

ROLLBACK TO sp1;
来源：http://dali.mhx1999.top/Article/details/gtgoewzvoi.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbhapmar.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gttvbmlbmx.html

[Q70] 更新统计信息
来源：http://dali.ehwqpu.com/Article/details/gtpimnhata.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtzoaniejp.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtdsdaxoms.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtevsjxdfq.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtocaexlnx.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gtgqtqlziq.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtdaiqhiaw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocqttrqp.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gtgffagsvb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhiwuduotai.top/Article/details/gtshvsacpt.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtocrwhckq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtyefamxoz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtnunruegq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gtcngljwxq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.daria6918.cn/Article/details/gtclvxiknf.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtmvmgvkdg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtgbaxotun.html

[Q78] 当前时间
来源：http://dali.zhiwuduotai.top/Article/details/gtwylypzfg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shzxlz.cn/Article/details/gtpblaoalt.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtwqexiwfh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hongshengwenyu.top/Article/details/gtwsefdbcj.html

[Q80] 字符串截取
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdileqfc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoelekcmw.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtsfdztfna.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtwpzmejsg.html

[Q82] 字符长度与字节长度
来源：http://dali.yonumen.top/Article/details/gtdxiwrefv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtugfktkxc.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gthqrhwlpp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtxgnsnuie.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gthmiwgbqh.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtshioadbb.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtzrecffyr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tanke756.top/Article/details/gtqbwvrqfj.html

[Q86] 读取 JSON 字段
来源：http://dali.zhoulong.xyz/Article/details/gtdnsbwfsn.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.wangdashe.top/Article/details/gtxyunsqqt.html

[Q87] JSON 字段做条件
来源：http://dali.cqqwz.cn/Article/details/gtzennwstn.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtahkcvmau.html

[Q88] 行转列（条件聚合）
来源：http://dali.shanyushiyangtech.top/Article/details/gttdrzyzqe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixmlerzb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtgnwsawwe.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrykklah.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yueranfly.top/Article/details/gtrlxhmgjz.html

[Q90] 生成序号列
来源：http://dali.quarkkingdee.top/Article/details/gtudswkose.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xylfe.cn/Article/details/gtwpemyico.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtayuwedkl.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtmnttcgce.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnbscczgy.html

[R01] shebang 与严格模式
来源：http://dali.jyoumei.cn/Article/details/gtgjtnpscq.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtwuzrmbpy.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gtryourcxs.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtyqikerfy.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gttqjfmvvo.html

[R03] 只读变量
来源：http://dali.cheryme.top/Article/details/gtuouuxnby.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtzfxipxat.html

[R04] 位置参数
来源：http://dali.sxryk.cn/Article/details/gtdwkzzwvo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnqzz.top/Article/details/gttetwarwe.html

[R05] 参数默认值
来源：http://dali.feifeiyinyue.top/Article/details/gtwtuagzdl.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gtiufzjkjb.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtuskyyymf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtrlptijix.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtbozkmicd.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtalfcfkmb.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtnaiymlgr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtbtftrpqj.html

[R09] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gtwxhoczfg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.redwolf501.top/Article/details/gtbatbpiqi.html

[R10] 正则匹配
来源：http://dali.hfpthk.cn/Article/details/gtekcfkznw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangdashe.top/Article/details/gtazwknnvq.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtxhnibhhl.html

case "$1" in
来源：http://dali.yj20258888.top/Article/details/gtscyucbie.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtipivpxei.html

stop)  echo "停止" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtitagumxa.html

*)     echo "未知命令" ;;
来源：http://dali.birdmap.top/Article/details/gtqqbjemid.html


<!-- 参考信息 -->