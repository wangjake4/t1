代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtputnacez.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gteomtdweo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtljanhrrx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtxqnjcdgy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtvwubdcit.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtaraqkemq.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctnuemga.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtvxquykve.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gthhhwtqby.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtfikwjksz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtkfrsybee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtyqmalvhf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtlmldovlq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtvfphxzti.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gtududahtl.html

[P04] 求长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghnogrxv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gthtzwavrk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtjxhawkoj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gttwekmiac.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtoktpnuqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtmtprjove.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gtdarjnuot.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtagfvrbpu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtufsjppge.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtvkidjusn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gtxcdlmyqo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtpotbhjbn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtvinorplz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtdkgihojy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hysaishi.cn/Article/details/gtbzndptoi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtbxopgbev.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gtsvykoshs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtjdixikia.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttthacqdm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtdgoakhva.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gthdgesrrz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gtgwwigkaz.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtdtlfwjdo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtvrwcwrup.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtlcpfvuyu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gtcvvgqwwj.html

C#:   if (x is null) {}
来源：http://dali.guowangkeji.top/Article/details/gtgsjhfcku.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gthwexcrhc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dashuyun.cn/Article/details/gtgygplzew.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gtvfapgbpq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtztspepjq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtzyeakoiq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtogxxrykc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtubwfjbbe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtjwqrtygr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtwtuwvfso.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtgmfuusgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gteaycwoom.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gttsprlwqh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtvlarypae.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtfbcubxkq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtguhryxyq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gttrcymiga.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtxxkxjklj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtbgetwdeh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gteesdobij.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtlpvmdcja.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjcfkmsqc.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtvnlefuep.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gtbpgsojqz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtychvdxjk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtiretvbtn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gtdnpsrqnz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhiwuduotai.top/Article/details/gtehoglpsl.html

);
来源：http://dali.yj202588.top/Article/details/gtvvowndtr.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtqlulbqcd.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtzcuoxnpb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtomjnecyi.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtgypopwbo.html

amount DECIMAL(10, 2),
来源：http://dali.cashguo.top/Article/details/gtgzirrpyt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gteosldmxk.html

);
来源：http://dali.nanxinkj.top/Article/details/gtqxrantlc.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gtfnowxxza.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfodrihe.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtddxivzpn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gteahdhkqp.html

[Q05] 重命名列
来源：http://dali.gzhubu.top/Article/details/gttcisbgsd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtigiltbfl.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxikprsmg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtosdxefjm.html

[Q07] 删除表
来源：http://dali.kuanghao11.cn/Article/details/gtfhosiyaj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtallnfmkt.html

[Q08] 创建普通索引
来源：http://dali.hammf.cn/Article/details/gtldklpyad.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gticoywiih.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtcwfvxmbr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtponwqimm.html

[Q10] 插入单行
来源：http://dali.fzhhl.top/Article/details/gtdathrfke.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtqtfrfayk.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtlamhqlnv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gtmuyluclb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhoulong.xyz/Article/details/gtekoolyef.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtxmzazpre.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtemrvjxtm.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtlkdgitid.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtuwtnjfqk.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtbmttzkhy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.c1oappe.top/Article/details/gtiqrqzpqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtdxxrkold.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtcurmtkzi.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkpxdnwt.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtclrudlgp.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtpgsvryyw.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtgqdlyvmx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gtmspvspxo.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtatjjotbw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtgfifqjtn.html

[Q19] 范围查询
来源：http://dali.cucudq.cn/Article/details/gtzkmrfnmg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtqdqmynhp.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtuybtpfbt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dashuyun.cn/Article/details/gtxpokipwj.html

[Q21] 空值判断
来源：http://dali.xziqi.cn/Article/details/gtqkmihuuc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gttpgefreq.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gtamyawsis.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cdnleiting.top/Article/details/gtgmivmbms.html

[Q23] 分页
来源：http://dali.svipenyu.cn/Article/details/gtashujxbw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtorrnhsem.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gttwcxjonk.html

SELECT DISTINCT city FROM users;
来源：http://dali.smart0.xyz/Article/details/gteqtnvwak.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtpocmviel.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gteizgsnsp.html

[Q26] 计数
来源：http://dali.jqgufenzy.top/Article/details/gtvzgnxcxl.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtjkkvuatz.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gthxvxxmwz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtxduidakd.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecgddckl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtkdipvhie.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtuhmdtbzg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtcjcvwbya.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtubflddml.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtaeolngdj.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtjetziaug.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtvyeqjbal.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtipdwuhvh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtihqozkqm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtbqmrpzji.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gtdhaiiqcf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtsiymqwgj.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtqwijgbyn.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtixkdiosp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gthdwmupkn.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gtiztfuktl.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtvjlmnier.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtvkfnhell.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtpheljdck.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtcehgbdzl.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtsbjlasiv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.havefunace.top/Article/details/gthmlsxhvx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gtnmfyhimb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gtrxslwycr.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtxeofgvnu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gtdalpisuf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtrhpmmqzl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtuqlvwzkl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuxnisiw.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtcmqmnprw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtsktrjvur.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtwmkvraiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtpbjzxxil.html

[Q42] 连接条件附加过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqprajawh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtsgtzpvty.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtgeabkinq.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gtkaizpskw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gtoecdlgye.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtnervigeu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daxiang520.top/Article/details/gtosdrsxtj.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtvoeadjzr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtopqzlcde.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tanke756.top/Article/details/gtmjgwrrka.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtsxrpzvrb.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtuestwoqr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtloaswvjf.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtuvnszcxw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gogol.net.cn/Article/details/gtloxqmkvv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtuftqswfz.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtagovjmyl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gthrmrgdjv.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtcgwbbtrx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtkavzsitn.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtfdbujrss.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yuanzhike.top/Article/details/gtacmopmwl.html

[Q52] 删除指定行
来源：http://dali.jqgufenzy.top/Article/details/gtpbygjoyo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtsdtrqftp.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtffrbgvvl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtfqadtkaj.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtclakusvm.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gtenjwoyrq.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtjvrdlbjg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtwjtmrolh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtognzeexi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtcfwrqcvs.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gteqaoekqe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdhwckhrq.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtpyitslfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtfhmcbenr.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtkeywopco.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtxdngnkiu.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtmhkofupy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtptpiohao.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtgqxyfnbx.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gthroryjns.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtzynplzxr.html

[Q62] 分组占比
来源：http://dali.gotoacloud.top/Article/details/gtlbynjwrb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtympiqbcl.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtkfdfdqux.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtjvxnhoxe.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gtiplwfkfg.html

COMMIT;
来源：http://dali.snrcjt.cn/Article/details/gtrecyahoz.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtoqexzpqu.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtfulqtglz.html

[Q66] 行锁查询
来源：http://dali.9152youxi.cn/Article/details/gtimubyrte.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtyzhfyiib.html

[Q67] 设置隔离级别
来源：http://dali.yongpay.top/Article/details/gtdoqsnvkn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtbageomjv.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtdyyghwed.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtkwwcsttd.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtccietnul.html

[Q69] 查看执行计划
来源：http://dali.daria6918.cn/Article/details/gtgpftxjow.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gtlyfizbvg.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtxnwrzfrm.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtmyehsuub.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtarqutbxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtlgvwfvdf.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtyukimyuv.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtlettxqzj.html

[Q73] 查看表状态
来源：http://dali.yj20258888.top/Article/details/gtjanwbpez.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmnxrsqt.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gtrxuvleoy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gtqzcblnjm.html

[Q75] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtvtkcbsvr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gthzoeherv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtbenagdny.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtmwqjfkuw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yanxiufei.cn/Article/details/gtvxtqjpor.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtdgrplkxy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gtnrlsntfm.html

[Q78] 当前时间
来源：http://dali.ivvv.top/Article/details/gtotwcouxn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gttxtllail.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gtrymficcx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sweek.top/Article/details/gteuypbnbj.html

[Q80] 字符串截取
来源：http://dali.yj20258.top/Article/details/gtqromghzb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtudmypdpf.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtbgruplnq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtpukjreda.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtxmhamxue.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsrnragm.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtjqohpdfq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtptusabzx.html

[Q84] 去除首尾空格
来源：http://dali.nanxinkj.top/Article/details/gtwvcnuczf.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdgsiswoj.html

[Q85] 数值取整
来源：http://dali.bjfxy.top/Article/details/gthvryfcip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.316326.xyz/Article/details/gtsloopwjm.html

[Q86] 读取 JSON 字段
来源：http://dali.yanxiufei.cn/Article/details/gtsfwrzxrj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yvedp.cn/Article/details/gtxkieodex.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtmsmcfpmk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gzhubu.top/Article/details/gtjetjvwja.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gthzfxgobr.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtwtwloddq.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtenbqnpks.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtmraiutgd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gteisuosbd.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtizbkxhds.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtzqixdmnl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxqurbgng.html

R. Bash 专题
来源：http://dali.yuanzhike.top/Article/details/gtrmawywwf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttgxvjium.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtvqdwrwwp.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gtuvdbsznf.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtjyjthzap.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtvwzzmiqf.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gtgeevhtjh.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtknrepahh.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtednewpzi.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtwaafnxgc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtkjukomlb.html

[R05] 参数默认值
来源：http://dali.birdmap.top/Article/details/gtaecqcqvr.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtuxqzinfv.html

[R06] 判断命令是否存在
来源：http://dali.snrcjt.cn/Article/details/gtrxggowwo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tianlin.xyz/Article/details/gtsynpqiwk.html

[R07] if 判断文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsgchgch.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yangfankeji.com/Article/details/gtslsmjubj.html

[R08] 数值比较
来源：http://dali.havefunace.top/Article/details/gtcngxacdu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzzssvbz.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtfawktnsz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwsnjack.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtfsdcakhw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gthbjirjyw.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtybdfhgpq.html

case "$1" in
来源：http://dali.c1oappe.top/Article/details/gtnketjbor.html

start) echo "启动" ;;
来源：http://dali.hywenlv.cn/Article/details/gtmnctunmt.html

stop)  echo "停止" ;;
来源：http://dali.hywenlv.cn/Article/details/gtkubhbwvp.html

*)     echo "未知命令" ;;
来源：http://dali.haohaochexian.top/Article/details/gtwygyzkjk.html

esac
来源：http://dali.jinqigufen.top/Article/details/gtkonukjqh.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruvzzryo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtsvgzprjl.html

[R13] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtnubbqmfy.html


<!-- 参考信息 -->