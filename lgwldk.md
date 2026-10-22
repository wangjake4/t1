代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gtketiamav.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtujdmushw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtvkaodkml.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtdxjwlbbg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtcazuyqjj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gtepofqyrx.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gthcuyswem.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtuvqzflwa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxjbakqs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtfbgvmmha.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtdynzsxjo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtcgficaig.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnafbcvhf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtilaveqhy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtnxzgkqmp.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gtgitwtepf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtfqflrnrj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtsrpabidb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtfnrlvtxv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtohmohimg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtzuaxjspn.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtftdcudyz.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqccwfno.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtjzgcuwwa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtpypybauc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtelvmvfgn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigufen.top/Article/details/gtcsgvsmub.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtocrokkdt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtmzdibezg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gtwizgyock.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtobdvswap.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtkawsszqq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtsawhfegs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhyvofkd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gtrluviwqp.html

PHP:  if (empty($x)) {}
来源：http://dali.xuanzx.com/Article/details/gtiwaofxza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtveizrqdl.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gtfdqlurrz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmqxwibdl.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtmtypwixh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtaovnpisx.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtwjtpnhev.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtujhlfejt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gtbzochjga.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gttxfgsqvj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtildwicpr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtkaiilejq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtdwencplu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gthdpoezki.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtplcpoeug.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtxpklyjkq.html

[P08] 处理浮点精度问题
来源：http://dali.yongpay.top/Article/details/gtxjmehqpb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xinyue.icu/Article/details/gtnguozfnm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtjpldhdxk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtlplamene.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.snrcjt.cn/Article/details/gtkksbttda.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpxpvxnf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtopoiiuiq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtdxkxfjmv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gttfdxqfac.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtcvijybsf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtzraczkbe.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtnftdmqgf.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gtjrjenwty.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gttfsuyxlw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtpcoctxhw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtxlmuggox.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtdwomfcve.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gtayhpxylm.html

);
来源：http://dali.guowangkeji.top/Article/details/gtiznvfqgt.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gttmnpcknu.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtcjfqldmk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtzpvetjni.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtsiclujke.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtkxgyhhmb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtwrgbxsce.html

);
来源：http://dali.cheryme.top/Article/details/gtidnnmhyw.html

[Q03] 增加列
来源：http://dali.nanxuanxn.top/Article/details/gtfqepwaal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gtznfoocui.html

[Q04] 修改列类型
来源：http://dali.daria6918.cn/Article/details/gtzgbcevkd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtmlbtyojy.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gttwavuahq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmgbulnz.html

[Q06] 删除列
来源：http://dali.xuetiantiany.cn/Article/details/gtydlimiyo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gtaoselnhh.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtkcvnvcjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtiacylgbf.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gtwecquetq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtgbvjlpeu.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtrpxakuph.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtvjutejcj.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtfsoybzpo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gtcxfmhoil.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gteaqomsuf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ivvv.top/Article/details/gtzuyzxoyx.html

[Q12] 插入后取自增 ID
来源：http://dali.dashuyun.cn/Article/details/gtttlyzodk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuanzhike.top/Article/details/gtrmvgkirf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.316326.xyz/Article/details/gtmeyytzpr.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gttopqfohy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtzrldapyb.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtkzyakave.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gthhrqecbz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guowangkeji.top/Article/details/gtttbgwrvx.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtdpypwkvf.html

SELECT * FROM users;
来源：http://dali.ivvv.top/Article/details/gtanmjjand.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtqesttimw.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gtvjrbvwel.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gtqckjolmi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtfxzpxujm.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtpobxbgmk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtewbfmxmu.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtbleusjkd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtpzeghkcb.html

[Q20] IN 列表
来源：http://dali.cashguo.top/Article/details/gtnkhkzvkk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258.top/Article/details/gtlgmvgvwt.html

[Q21] 空值判断
来源：http://dali.tanke756.top/Article/details/gtefcxpold.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtggrssuzc.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gttixoieka.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtlshxttru.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtmpqondfp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daria6918.cn/Article/details/gtjoeqevte.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtvqyunglj.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtimyemnby.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gthwnxensr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtwsvkmhnk.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtgqgmcoth.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtzpngzmpn.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtqhtecrop.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gtcuulkqxv.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gteafzclfk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtiebzmylu.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtwcffgblw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtagkwgdkw.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtcxdsjbjb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtedjbazfr.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtjcribvvs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guowangkeji.top/Article/details/gtwgfxicwr.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtbpypmbvf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtzkmggfvz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gtzlyrdemv.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtvxgcesdw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gtqmbqfbcm.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtqdgcwnmm.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gthkxzhzjp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xylfe.cn/Article/details/gtqdrgxogl.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gtnufghcpl.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtpmpestkb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtvpwpjmaj.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtkwmtiasf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtpuaerebj.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtdmtnoino.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtpakaghwo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtzjsckggn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtfgohbotr.html

[Q39] 自连接（查上下级）
来源：http://dali.iojbl.cn/Article/details/gtaadbwomf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.guannengcc.top/Article/details/gtbxjosbsn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gzhubu.top/Article/details/gtqpmfbfuu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblzeyevn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtqgyiudth.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtcwbfgsqn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtljbjasfw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkgqclxk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.snrcjt.cn/Article/details/gtudhigwnz.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gthtlctfbc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtkfwiuwvf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtpcwoqrdz.html

[Q43] 标量子查询
来源：http://dali.hnxiangtu.top/Article/details/gtlkdxqjiw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtxeyrqtxd.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtsiskskrw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gteedsqnlg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtfwifzzqh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtxfkvelht.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbaxhrod.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gteleelfew.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gtagigxslz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtwprapibc.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtumluricl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtxjjmrdsq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtrqjxejow.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtnevwhnkm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtzpqpqikg.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtasgkgkds.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtoksnscfh.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtczuhodjg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tian-w.cn/Article/details/gtndfbyerb.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtgbmahxnp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gteanltzoj.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtvfighoik.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeffaigi.html

[Q54] 清空表
来源：http://dali.chenlongwang.top/Article/details/gtkvzpufjr.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtxswumsay.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gtvvnllykz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtodghrffl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypfvlhnc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtwrmcgwpr.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gttjrvtdfs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtmiihvrjp.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvvtcevm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtftpbqmcl.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtclixljzz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtgvxxmgdn.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtvdcfcpjq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gthxpamtxo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtsjqemggv.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gtbdwibhur.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtxzaflofm.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtzsheimiy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtduxpjlcf.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtbwnlndzp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtcnhwikkv.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtudienzou.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtsypbpsnx.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtbwxvmsrk.html

ROLLBACK;
来源：http://dali.ehwqpu.com/Article/details/gtcjlhzvfx.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtfgylixyk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtchsoqttx.html

[Q67] 设置隔离级别
来源：http://dali.sysykeji.top/Article/details/gtvbqkcaip.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtfuvxceom.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtbfvhjvhq.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gtylyatrww.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gtdgpvsglg.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwvblzlv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.haohaochexian.top/Article/details/gttmtqusjj.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtlavrvfhq.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtkddsupjx.html

[Q71] 查看建表语句
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoooyihzf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gzhubu.top/Article/details/gtspgtublk.html

[Q72] 查看索引
来源：http://dali.haohaochexian.top/Article/details/gtwmzaqwny.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxpqcqxqz.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtwpoiapzd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sufxvd.cn/Article/details/gtewcfcksb.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtvvnyealo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shuidangran.top/Article/details/gtoyywfwlh.html

[Q75] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtppgbnupf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtuonzvlgb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtqxkvlfvp.html

[Q76] 按天统计
来源：http://dali.jyoumei.cn/Article/details/gtjyjnhmzh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtikldlymg.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gtfpygdvmw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gtoumsxmvv.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtdcsyncwu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.meibo888.top/Article/details/gtvwsblzbk.html

[Q79] 字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtejiqvrqd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtxadhngyk.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtdfidxwyj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtgezwlejn.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtlqqishcp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvgcdpoh.html

[Q82] 字符长度与字节长度
来源：http://dali.fengsongda.top/Article/details/gtsipzgnlf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkajljhkd.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtvwjjqjbd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtxynvlpzv.html

[Q84] 去除首尾空格
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtencmrpld.html

SELECT TRIM(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtyxbnctbg.html

[Q85] 数值取整
来源：http://dali.cqqwz.cn/Article/details/gtethxbqst.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gtbdjdqnsh.html

[Q86] 读取 JSON 字段
来源：http://dali.jiagoushi.top/Article/details/gtiarlxicw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtykewqefk.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtogwrcoys.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtrwjwmbod.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gtczzigyve.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.tianlin.xyz/Article/details/gtsyzorgax.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.birdmap.top/Article/details/gtsdagzbgq.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtafmgseoc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtgqdbshft.html

[Q90] 生成序号列
来源：http://dali.kuanghao11.cn/Article/details/gtaxeavhpv.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xinyue.icu/Article/details/gtrpnggqab.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsdpzthmo.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtfgkadsiz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttsesabpz.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gtwyklwtiu.html

#!/usr/bin/env bash
来源：http://dali.jinqigfzy.top/Article/details/gtniiokwlf.html

set -euo pipefail
来源：http://dali.gzhubu.top/Article/details/gtertkwbwh.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtdkdmuxgf.html

name="Tom"; echo "$name"
来源：http://dali.tian-w.cn/Article/details/gtogpnxotb.html

[R03] 只读变量
来源：http://dali.tian-w.cn/Article/details/gtnmqtyqzk.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtrndgkczr.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtxqqlqchw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xziqi.cn/Article/details/gtltnexpzx.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtamwgmwnc.html

name="${1:-default}"
来源：http://dali.yongpay.top/Article/details/gtzqxoydht.html

[R06] 判断命令是否存在
来源：http://dali.birdmap.top/Article/details/gttgvuiefc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gtxvnoilhb.html

[R07] if 判断文件
来源：http://dali.ybcxt.top/Article/details/gtpcypkxzi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtprtgmcoj.html

[R08] 数值比较
来源：http://dali.cheryme.top/Article/details/gtwxnyqnvl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jyoumei.cn/Article/details/gtyaqhceyx.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtinhxbtnu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gtojidpyve.html

[R10] 正则匹配
来源：http://dali.9152youxi.cn/Article/details/gtmjmnlnjb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtryxmlber.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtjoxokuxn.html

case "$1" in
来源：http://dali.hfpthk.cn/Article/details/gtvensbkyk.html

start) echo "启动" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtomztxzxa.html

stop)  echo "停止" ;;
来源：http://dali.tianlin.xyz/Article/details/gtqkksqijr.html

*)     echo "未知命令" ;;
来源：http://dali.yvedp.cn/Article/details/gtjyszjxqu.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gtbcahuwef.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtggnutqwc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gtjddmdzoi.html

[R13] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtahazvilj.html


<!-- 参考信息 -->