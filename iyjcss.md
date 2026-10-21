代发 wailian999

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkgokccyw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gtusvqfmzt.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtedphsxpd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtirsgnxjm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gtmwsbmqfq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtrjrwkxec.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtefnhorof.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtyydzwvpn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtgqeyjbvg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigaynhne.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtasvdoyla.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtpnzldwvd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtmvyuerva.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtwocsyykx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gturfbjevx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtkhcaxmbd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtkxdqzynl.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtynsyuvud.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtsjmblitf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtknjucnxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gtqfeeidme.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtezqpocje.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gtzubjgfsa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gtuiuswnta.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtbfbfibza.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtsehgxwdj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtvsggwgoj.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtgavgdobc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gtxioossdm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtklekyodh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtfodheymn.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtscryznlw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtgvvfuqns.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtqszbzlup.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtzoccgtlq.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtvvcpaxlw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtopqnxpnb.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gttszlojpj.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtpycfiwyh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtajtukkhm.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gttlaltbqv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtwjvfdcrs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtizdzvodk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xziqi.cn/Article/details/gtqdzphuve.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtgrdehvea.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtjvacrjxf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtyegrknou.html

[P08] 处理浮点精度问题
来源：http://dali.chenzaomai.com/Article/details/gtlifrweka.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjyakqaz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtjtwkzkij.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpzktmvk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtpxywkwjx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtvyzylqvd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtcnxlajqu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtdqizepiy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxzkosdo.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdhpxerhv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtlrwsbyym.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttfftcuzy.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gtaoothblh.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtzsqbnasi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtixqbbdcu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtmmhuhvba.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtwmdvprsd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtlderlzrj.html

);
来源：http://dali.sysykeji.top/Article/details/gtgbflbtxp.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtanzvanog.html

CREATE TABLE orders (
来源：http://dali.jqgufenzy.top/Article/details/gtjmuizsly.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtskavsdwx.html

user_id INT NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtfmqcbwty.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuyanfqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gtakxqkjnf.html

);
来源：http://dali.yonumen.top/Article/details/gtglqxqpvf.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtgwhbmloy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtpkrvtigx.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtrjtbwnfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gtxqjxtgef.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gtpbmjliij.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtkqmgrooj.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtmkqtqfex.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gtujliojtq.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtqjdwoavo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gtxlfolgfn.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gtdahsridf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtkwaaksor.html

[Q09] 创建唯一索引
来源：http://dali.yj202588.top/Article/details/gtinxxdsfo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gthycuhlqn.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtqkzzxefq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sysykeji.top/Article/details/gtipmljbse.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtukojaqkp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtsphoxnon.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtciejxxbk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cucudq.cn/Article/details/gtxietxvle.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryqwpvjm.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtfmpqphmg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gtivbnmswc.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gteegljvxg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtkjmbvjea.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtxmwflbgy.html

[Q15] 查询全部
来源：http://dali.cashguo.top/Article/details/gtbufcpscx.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqsxcphan.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtxmeutkzh.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtrisquwbt.html

[Q17] 条件查询
来源：http://dali.gotoacloud.top/Article/details/gtwjtsxsxh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtjzvjhhol.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtfxdpdgqf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtnxjnqekn.html

[Q19] 范围查询
来源：http://dali.vqdsnc.cn/Article/details/gtznccezml.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtivtwvhty.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtxdpsdhdm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtjaevhazj.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtnahpsybg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gotoacloud.top/Article/details/gtkgbaufbz.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtrfvltxzm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pengpengdd.cyou/Article/details/gtpxefbvqn.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gtllrqxise.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.svipenyu.cn/Article/details/gtjkbdmodg.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtdeqtouzp.html

SELECT DISTINCT city FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtzrxqqjnm.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtlmuntmnq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtqnshzdqi.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtvzgtfyap.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtweoofyux.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gthhcptygc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gtgdauhxif.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gtglntfjeg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtdsnkhsjh.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtnuwopmfp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtoqibkasr.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtevbojfww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtywhlavhk.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtxwpiinxm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtgxmdchpj.html

[Q32] 分组拼接字符串
来源：http://dali.cdnleiting.top/Article/details/gtjrijdycv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtnbjoyttv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtmlghjjqo.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkftgydjc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtqchcacje.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtzvnmffwe.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gtyngdsfki.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtvkttseoa.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gtokrxoqxi.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnjczzkk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtznmqaxnx.html

[Q36] 左连接
来源：http://dali.jinqigufen.top/Article/details/gtxmxmgxum.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtcyboblzu.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtpqdzqskw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nanxinkj.top/Article/details/gtglsyuzqa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtebpwtecg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtdrsbyfte.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtobrsllbq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gtnvmewbul.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gterpcrcmz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtgvnmxims.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtzodzcdbs.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtfkdweovm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gteyqfzljo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.snrcjt.cn/Article/details/gtpygucrcf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gtupjgmtie.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gtpywiibvg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtuwstxbnv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.smart0.xyz/Article/details/gthjnyqppg.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtxbxakqwo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtditukcfz.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gtdxwywapp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtdgbrfwpq.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gtulniqgoz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gttgdnuwvv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtkweunvzv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtumxxsrtg.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthliijuhz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtuiascdsw.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gtinuketub.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtelgdwpiu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.smart0.xyz/Article/details/gtwouqehse.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtnzdmurru.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gogol.net.cn/Article/details/gteubieugk.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtnlubezfp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtxidumubn.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gttubkkjsq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtqbtmzrwt.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtrghbxnyj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadlaljma.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gtdevopwmh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gogol.net.cn/Article/details/gtvpcructl.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gtebhagaxp.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtzejsvjnl.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gtxcypeziy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtbkuzaiqv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtvnpqzgjo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtdzzaweij.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtkklpxdfz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gteetsmsmz.html

[Q58] 累计求和
来源：http://dali.hongshengwenyu.top/Article/details/gttqpqvkgr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sweek.top/Article/details/gtncpiiodl.html

[Q59] 分组内累计
来源：http://dali.jqgufenzy.top/Article/details/gtxtfasuld.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtqgqropvm.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtyrvlsvhm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gthnlctfbc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtdzqbmced.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtiraolcfl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtrjewohss.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gtlsiqfefh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtupxovwns.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gttbnorelv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gtqxlfsaal.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtrljnvmey.html

COMMIT;
来源：http://dali.ybcxt.top/Article/details/gtnbaggjda.html

[Q65] 回滚事务
来源：http://dali.havefunace.top/Article/details/gtzuadzfkv.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtdzrxwuec.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtygmosamd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtssygdjoj.html

[Q67] 设置隔离级别
来源：http://dali.cqqwz.cn/Article/details/gtuyeodkbw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtdkhrmngh.html

[Q68] 保存点
来源：http://dali.jqgufenzy.top/Article/details/gtaporhknk.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gtatoimwlb.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifecetml.html

[Q69] 查看执行计划
来源：http://dali.nanxinkj.top/Article/details/gtfoaudizr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gtdsxxthvj.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtsxzvymuf.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtmhzeltum.html

[Q71] 查看建表语句
来源：http://dali.fzhhl.top/Article/details/gtzekqbolb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gtgvzanvao.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtbthucwac.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqwelqttc.html

[Q73] 查看表状态
来源：http://dali.jinqigfzy.top/Article/details/gtglfomako.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtgftaufib.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtyadtdvbk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gtydddbomg.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtlwcadccg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhssjklc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gttkwrirlr.html

[Q76] 按天统计
来源：http://dali.havefunace.top/Article/details/gtlelyrkfj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258888.top/Article/details/gtklgkctnu.html

[Q77] 时间加减
来源：http://dali.yuanzhike.top/Article/details/gtzgoizzbb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gtysbxwhjx.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtqihvarih.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyrejxjo.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtagmfntro.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hysaishi.cn/Article/details/gtmfepzlna.html

[Q80] 字符串截取
来源：http://dali.xuetiantiany.cn/Article/details/gteuivoeao.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtmiwoltny.html

[Q81] 字符串替换
来源：http://dali.sxryk.cn/Article/details/gtueihwtti.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtbwcnypng.html

[Q82] 字符长度与字节长度
来源：http://dali.smart0.xyz/Article/details/gtmbcotkps.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfgjbrmrv.html

[Q83] 大小写转换
来源：http://dali.feifeiyinyue.top/Article/details/gtozfvvdtt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtwuchuasp.html

[Q84] 去除首尾空格
来源：http://dali.c1oappe.top/Article/details/gtfzmwtmab.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtyqjqeudx.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtfhpyeuye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gtvxsqdjic.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtaqciqxfa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zycfv.cn/Article/details/gtlrwzrdes.html

[Q87] JSON 字段做条件
来源：http://dali.dianchejie.cn/Article/details/gttiwgyamc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtteetgoqf.html

[Q88] 行转列（条件聚合）
来源：http://dali.jyoumei.cn/Article/details/gtgiklubmv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtruncbezs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yueranfly.top/Article/details/gtrcdbywaz.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gttszurnul.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sweek.top/Article/details/gtsujdkqne.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanssxqib.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gtjkziquts.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvsowfjer.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtsuaklyrj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpokywnke.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtnyxgfbej.html

#!/usr/bin/env bash
来源：http://dali.tian-w.cn/Article/details/gtcrpklhbt.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzidlsbky.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtduttyhdm.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtlhiwxthx.html

[R03] 只读变量
来源：http://dali.jlsjyb.cn/Article/details/gtxnzdbddn.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtqhthxdbx.html

[R04] 位置参数
来源：http://dali.pengpengdd.cyou/Article/details/gtlozplljr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinqigfzy.top/Article/details/gtcswvjbyh.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gtlxwliwxz.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtxcpgnsys.html

[R06] 判断命令是否存在
来源：http://dali.dashuyun.cn/Article/details/gtioqbilfh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gturdbwkzx.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtgvoqezwc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxyegadq.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtrxyhrykv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtmulazupe.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaocujchr.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtalkbebqz.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtuysmmxil.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sysykeji.top/Article/details/gtzypqzyhh.html

[R11] case 多分支
来源：http://dali.andypj.xyz/Article/details/gtajzaverw.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtrewzgoit.html

start) echo "启动" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtaghemtxq.html

stop)  echo "停止" ;;
来源：http://dali.gogol.net.cn/Article/details/gtuzsemmfv.html

*)     echo "未知命令" ;;
来源：http://dali.hysaishi.cn/Article/details/gtmqhbzfcg.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtjynssmne.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtlmvfggqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtxdvadwhs.html

[R13] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtxvyvbjgl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtlantkldh.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtkalekaua.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtzkcnbrta.html

[R15] while 逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtmonysakh.html


<!-- 参考信息 -->