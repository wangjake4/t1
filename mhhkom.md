代发 wailian999

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtykenpwcs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gtdarpkjgw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtdoedrhyi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtbzhgojba.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtximeyimn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ppjwa.cn/Article/details/gtzrdftamj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtewljulea.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtmgginjjg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtaoriwnhs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtqpefekrs.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtycclnybo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtvnjwwren.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsymwufv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtfuglqfqf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtkykdkquc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtoaodxegn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtuxstjotx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtrfxnybhj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtobzwkjtv.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtxmuujcri.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtwnqkipzx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtoodxbnlu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gtsqkfhxyx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtagtoiipq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtvyqtbvsp.html

Go:   len(arr);  len(m)
来源：http://dali.redwolf501.top/Article/details/gtulvycytc.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gttofmkrbv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtxqavlmhl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aizwys.cn/Article/details/gtogzxetpq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwgfmowl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmihpxxj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtklvmtsqo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtcvzmqrrc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtkbpkdaqg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gtrbkzhunq.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtlyzyewim.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtxweytjpd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtpghcojso.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtosozkoal.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtciuvinoz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtnaqkhrls.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gtrktfyotd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbssoxjxq.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtbmxlbxjk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gtmvfcnvhb.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtgexljtmv.html

[P07] 防抖与节流
来源：http://dali.sufxvd.cn/Article/details/gtbkiikmca.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtjfsipahd.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gtqymwbrpd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtpnxwcxzw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtadihuvls.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtxxsqemls.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtagmlkrxz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtmeqlktqd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.kuanghao11.cn/Article/details/gtnavxnplm.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtgwpujzto.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gteuocajyh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gthexsyzvn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtnkojrtwq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ppjwa.cn/Article/details/gtohgzdtri.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtfhlszbkn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueeyklni.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnqzz.top/Article/details/gterynvajx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aizwys.cn/Article/details/gtrvndlxcv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaxnocflg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtlhqefsgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcjhalxbk.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtpryhzngo.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtkyhcitin.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtzoqzbdyt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtsfxrufoq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtxtzknefs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhengqikj.top/Article/details/gtrjaggraq.html

);
来源：http://dali.havefunace.top/Article/details/gtkqayrnmr.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtcqznnlgv.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtdrhgxjpi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtexuernhl.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtandzuuup.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtodryawho.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtiaixygqr.html

);
来源：http://dali.sysykeji.top/Article/details/gtudpmngsn.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtrumaytxa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gthdjkssct.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gthoihioim.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtiowaadfn.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gtzogfejog.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtfknkcdxt.html

[Q06] 删除列
来源：http://dali.cheryme.top/Article/details/gtnbzbyygp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtkedqgdov.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtrvqrkfbb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtbwzhjpnz.html

[Q08] 创建普通索引
来源：http://dali.feifeiyinyue.top/Article/details/gtcloiqxko.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtcjkhiytd.html

[Q09] 创建唯一索引
来源：http://dali.nwbrower.top/Article/details/gtbmmeobcl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtvllsypyi.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gtkqbvgykk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkbyknbw.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtckknnzqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtmlvcvchx.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtrjwnmerq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtroyvxdki.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtkqjnnpfj.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtztxzllwf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gttrdkmbdg.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtugsqexyi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtesatpwgv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sweek.top/Article/details/gtsmunbwzb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gttsorukqy.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtqajkwnti.html

[Q16] 查询指定列
来源：http://dali.havefunace.top/Article/details/gtbfgrrieq.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdyojbzlu.html

[Q17] 条件查询
来源：http://dali.hnqzz.top/Article/details/gtbchdaixt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gtkgbvephx.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyybobcw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hongshengwenyu.top/Article/details/gtycvwmifw.html

[Q19] 范围查询
来源：http://dali.yonumen.top/Article/details/gtrlqhkymo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxuanxn.top/Article/details/gtqbjyrylh.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtmoqzxbqy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yangfankeji.com/Article/details/gtwsppfdfd.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtccffmfba.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtraeemekj.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gtpmcrxjle.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtfnbticfv.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gttigjuoyy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtrlkajbse.html

[Q24] 去重
来源：http://dali.sweek.top/Article/details/gtcoffhqle.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtuccqxfzp.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtznboxuku.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtozjeqnui.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtizvbrkav.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtxcamhkem.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtkgxnkplk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzispivda.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gtghdhjmyv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtnvpdhktx.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkmmqhxk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtfmbgnjvh.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtnolhxnhw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtxjsyasgk.html

[Q31] 分组后过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtktzcmfui.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtsdjhwmau.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtcsrsoiql.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtagekjaes.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gttvqofwls.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtgdylvegb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtnqoosgeg.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtvcpojbns.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gttjbqiewm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gthzrtwtuh.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtorcxszfc.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtvpbhldwh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtvggmnpwb.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtnhbdaczv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtnxctjean.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gtlbotihxy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscalxekk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtdinecqus.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtnndoryku.html

[Q39] 自连接（查上下级）
来源：http://dali.jiagoushi.top/Article/details/gtratabopp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yvedp.cn/Article/details/gtkoinsooe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtakymqgup.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtcppivdrd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtxzidssmq.html

[Q41] 多表连接
来源：http://dali.hfpthk.cn/Article/details/gthpklpedt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.svipenyu.cn/Article/details/gtdqoigacx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.birdmap.top/Article/details/gtubxzwqkr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtmwjdjjxj.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtcbfmtlkx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtvtihcpll.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtmupacble.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtwotshapq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtcotsupte.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtsekzsipf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtrthjkhmt.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtuayuytmd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtetojboqr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jianghu66.top/Article/details/gtsmmhagvm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtcotasdnk.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gthobwnrlp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtrqpsfqoz.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtqoblvyzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.feifeiyinyue.top/Article/details/gtrpotqhdz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gtqhdiwyru.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtpxnndzhz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtzaltsuyg.html

[Q50] 批量更新
来源：http://dali.jinqigfzy.top/Article/details/gtvxfexgof.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtpwawejkl.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gtmbtwqehn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gtovvwjbdl.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtgtfikosa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtssigwptp.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtnfaraabq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzopyjtv.html

[Q54] 清空表
来源：http://dali.mhx1999.top/Article/details/gtogegdkso.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gthmctrefo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtimrtgyry.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtuqtdsxia.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtixpksedc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtblphifyp.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtazapprzv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjzfwcoiy.html

[Q58] 累计求和
来源：http://dali.yonumen.top/Article/details/gtdtcqpdjz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtkyyljsrd.html

[Q59] 分组内累计
来源：http://dali.hnqzz.top/Article/details/gtpcpchtbt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtfodmbhay.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtuolpvorj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtsqckhtyx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gtitmrcfrl.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtdivicact.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtcsdehpmh.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtfukxbuqd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtmahzicem.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtxatyaltg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pycfn.com/Article/details/gtbihckisn.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gtopqmecxa.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtxubdjbvv.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxhcqrsc.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbsgsfkk.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtqxsurwwp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtiejmxnel.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gtbeyplzcy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtpwokgpev.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtwrnltlxu.html

SAVEPOINT sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzsrbnmah.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gtidykirap.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtuviqqftj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtqvtkgbfe.html

[Q70] 更新统计信息
来源：http://dali.daxiang520.top/Article/details/gtpxgmexit.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtjslsplnm.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtmcskoazr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhixingplan.top/Article/details/gtvcmorhho.html

[Q72] 查看索引
来源：http://dali.gotoacloud.top/Article/details/gtyzottwzz.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtooxthrfm.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtwbfkterp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtpmhemdmz.html

[Q74] 强制使用索引
来源：http://dali.dianchejie.cn/Article/details/gtfusyyqxf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhengqikj.top/Article/details/gtxlcjtdkr.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gteshsmvuo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtfnpyucey.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guowangkeji.top/Article/details/gtpqfjjemu.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtzjegvttt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtpbdfvsxh.html

[Q77] 时间加减
来源：http://dali.hywenlv.cn/Article/details/gtfnylrnhi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gteymnpofi.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gtphylhnoa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtrybipmvj.html

[Q79] 字符串拼接
来源：http://dali.shzxlz.cn/Article/details/gtvrebgcyw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtbfxdezpc.html

[Q80] 字符串截取
来源：http://dali.jianghu66.top/Article/details/gtjemdsgii.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtihsuqhcp.html

[Q81] 字符串替换
来源：http://dali.daxiang520.top/Article/details/gtzoniflem.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yuxming.cn/Article/details/gtnnlgfatd.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtcohlyldo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtwsufnbic.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtxliqyrvl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtkbgdzaoa.html

[Q84] 去除首尾空格
来源：http://dali.fzhhl.top/Article/details/gtzsgzagmt.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gteiqtrutm.html

[Q85] 数值取整
来源：http://dali.hnxiangtu.top/Article/details/gtldndsoyv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jianghu66.top/Article/details/gtkdcswtsc.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gteaithhii.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gthsxcfuem.html

[Q87] JSON 字段做条件
来源：http://dali.xziqi.cn/Article/details/gtcisberps.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gtdpnjtkmo.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtqulffteq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gtzelvqbty.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkfeywoq.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtiheranfs.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtmfxsbepv.html

[Q90] 生成序号列
来源：http://dali.havefunace.top/Article/details/gtlffwsgvk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.snrcjt.cn/Article/details/gtxlkxqxvy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftxmgfxb.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtgftthbiv.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthflanghz.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtgdfkgvpo.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtyevbjriu.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtilxllskh.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtvuzjehcb.html

name="Tom"; echo "$name"
来源：http://dali.c1oappe.top/Article/details/gtlixygbzs.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtikjxyztu.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtybdwmoqz.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gtteeknbux.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gtriqkoimw.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtxpdkopuz.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtzghaymeo.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtrpdzjetl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtjncgqoeh.html

[R07] if 判断文件
来源：http://dali.zhiwuduotai.top/Article/details/gtcarzmoua.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shzxlz.cn/Article/details/gtveuodjtp.html

[R08] 数值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtnzohtpqu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hammf.cn/Article/details/gtpfxaadgf.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtylevesqh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.andypj.xyz/Article/details/gtvwjdeopz.html

[R10] 正则匹配
来源：http://dali.jinqigufen.top/Article/details/gtwciujpxr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gttuyeamnx.html

[R11] case 多分支
来源：http://dali.dashuyun.cn/Article/details/gtuteqcnqj.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtrgjuehcc.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtosgrhzxz.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtfvbgpgmf.html

*)     echo "未知命令" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtdwljfnmw.html


<!-- 参考信息 -->