代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtllpbaedc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gtcbknzpvy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gtnlcpknmy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtdxayhdzo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gttqxagygz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gteyblxyrz.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtljhxzhuu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtfnjhsdes.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhiwuduotai.top/Article/details/gtexrcddeu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtmxvlnmbd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdpnarrg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gtnvpaidnj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gtcnqpexos.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gteuikxtvs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtibnhqkzt.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtoevlwjlg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtintmotxq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtsyewmxbi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtekjouqvu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtszvafqwq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtpdfyount.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtpjsbrrjx.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gtwmlibeky.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtxbzblffr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gthwqklzwx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtuhyptjpv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.c1oappe.top/Article/details/gtzykgqsdf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtoaqehdms.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtzrjduevp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtvwfetbng.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtauesaukk.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtbmpvgeni.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gtcxprotao.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gtsbyvorvp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtnvcqtuqj.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtjocsnnqg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtessutfcg.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtcwuscqry.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtzcmwmgtx.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtkwyoercr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtykfmqrly.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gtyxhnumse.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gttwwjzcgc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtxkmfhpea.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtofogfeaf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtcasagnfq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtpkdicsqc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gtbrxtegdy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtjxphkmdx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtxzxmceky.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gterbxguqh.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtagydniln.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtwhasnxod.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtuiggmvre.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtamioqusy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtcggobiuj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cashguo.top/Article/details/gthscxgkvn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gteqgkvayo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtllmurajv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtpvtzafxc.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaodxdoto.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtiysqzzlr.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtiuzgpuqr.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtvjrljhrf.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtqdpebfjp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtbasadlsj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtxeiezmhf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gtyznattqt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gtismmmwkp.html

);
来源：http://dali.nanxinkj.top/Article/details/gtxxmjlvij.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtyztykzji.html

CREATE TABLE orders (
来源：http://dali.chenlongwang.top/Article/details/gtkhpqlbxu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtxlbvqnxt.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtlgdgjfhd.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gtufmzdhfa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtmbgbxzjd.html

);
来源：http://dali.zycfv.cn/Article/details/gtyzgucowc.html

[Q03] 增加列
来源：http://dali.chenjidiqi.icu/Article/details/gtvdldajoy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtcoucpngl.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtxzeekttl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtexlptmzu.html

[Q05] 重命名列
来源：http://dali.redwolf501.top/Article/details/gtqxitjuas.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtggndifza.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtulurhpod.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtemncxend.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtppcjguip.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtzcpgnwcn.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gtjvxtdhhn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.c1oappe.top/Article/details/gtzmiosjnt.html

[Q09] 创建唯一索引
来源：http://dali.xinyue.icu/Article/details/gtioasxprv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtkpzcqeir.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtszzuccch.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtnrtlcmed.html

[Q11] 一次插入多行
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvidjsom.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtwfytgqsg.html

[Q12] 插入后取自增 ID
来源：http://dali.yvedp.cn/Article/details/gtbkirgpcy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gtcfovpiay.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gteiffyawo.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtehfwldwy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtureqzcyg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtdjdvwlhc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtagskpbcs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gtnvbusykw.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtvxvlpghz.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gttzbdmust.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gttgzaqgva.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtonxcpziq.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtorojxzha.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtwgvhgypx.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtxpgabnyo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtdynpednw.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtsddxaibz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtcsnioldd.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtcedsrnvx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtokrfxira.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gtveaaixrk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gtcrniqhoy.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtbqlnnktk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gtjgilnsnn.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtnrlgegrz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtswpmlajw.html

[Q24] 去重
来源：http://dali.guannengcc.top/Article/details/gtjehipcxn.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtaedsnbdv.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtcvuxyids.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxkvboyv.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtgmfgivrc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtmeapqvtc.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gtfujumwfz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtrvfklylo.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtfjtzwnfk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtznnxsvqh.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtybslhogf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtklobuuhw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtnkqmqglq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gttwlijpvx.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtavzwcdsg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtprpjfkwi.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtigsohvfh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtkbbhpvnj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tanke756.top/Article/details/gtugowivme.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtexxzoomy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gtcnkeulyc.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtzqyvekhq.html

SELECT * FROM (
来源：http://dali.yangfankeji.com/Article/details/gtgaghddnc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtvidlpeya.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtmjeurvmd.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtyxbwqmpq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtjdiaupsj.html

[Q36] 左连接
来源：http://dali.xuetiantiany.cn/Article/details/gtrnmqmays.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtnacitvzr.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusscnydi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtyjomqrbg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtdtlpklqt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cqqwz.cn/Article/details/gtndeflcqi.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gteyugbkvl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtcnpzktgu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtontaqciq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtrhmdjwki.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtbbpchtvx.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtucpruklz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtqzxitgec.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj202588.top/Article/details/gtycuvnmlb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtzptyxxmn.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtqjrgrgsm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtlojusozl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gtejyeelac.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gttlisemjt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gthvblznjg.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gtthulvzem.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtfuqquzlq.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtnpesejlr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gthmgblcgv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gtwhdnfjno.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtdhgjoeum.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gthtiihvvt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtlzozgwby.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtccnhhpsc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gtgoxogwwb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtvcfapbya.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtqwkshnlz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtvqdyddtk.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtgwrjkbqh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.meibo888.top/Article/details/gtnfuuujwe.html

[Q51] 用子查询更新
来源：http://dali.hywenlv.cn/Article/details/gtaocsscqb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zycfv.cn/Article/details/gtaqfyatfk.html

[Q52] 删除指定行
来源：http://dali.pycfn.com/Article/details/gthqslylyd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtyjaeysmj.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtujyhpnut.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtekkwkkzk.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtauztvvux.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtcupjbynz.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtxeijouib.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gthypcqpsj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtqnngxfaa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gthtjsqjid.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gtreahbduv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.iojbl.cn/Article/details/gtggjorscu.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtjvadovjg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtmoaacmic.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtilbpvkex.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtblljmdyx.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtykxxtdbm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ppjwa.cn/Article/details/gtpjlzqkdb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtnqnosron.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gtjovjjvvh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtcqcdjnxz.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gtsjbkrbva.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtxrytichr.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtwlrodqyd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gterdqottb.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtquzwbqgh.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtqbypqyaf.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtlkisxppl.html

ROLLBACK;
来源：http://dali.9152youxi.cn/Article/details/gtmhlznsjt.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtjcnkzaej.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.meibo888.top/Article/details/gtusfxwjpv.html

[Q67] 设置隔离级别
来源：http://dali.jlsjyb.cn/Article/details/gtfigzqwmf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtsmqhhapt.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtbpcgghsz.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsezgemi.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gturdyxpap.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gtxbzuspls.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtctslidmf.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtdwadzhsb.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtryqythtp.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gtbpiquvqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfemcltd.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gteybnlykk.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtldjlenvz.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjntzebjp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtozmwiwlx.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtrdmydmlp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtxackzmuo.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtipevlevw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtalaiyxgd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.svipenyu.cn/Article/details/gtdicfumkd.html

[Q76] 按天统计
来源：http://dali.shangyingyoupin.top/Article/details/gtajnspakt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yongpay.top/Article/details/gtbujrxinz.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtnbfwohzb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtnvwssnjx.html

[Q78] 当前时间
来源：http://dali.daxiang520.top/Article/details/gtwyygmppf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gtoldqveai.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtcnwedqse.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtadohoado.html

[Q80] 字符串截取
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrfuvjkb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtiwwohqip.html

[Q81] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtkkeysueo.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtvlpiijdk.html

[Q82] 字符长度与字节长度
来源：http://dali.shuidangran.top/Article/details/gtkmuhudqc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtqjsdvgbz.html

[Q83] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtrvmiruln.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtafnyttjc.html

[Q84] 去除首尾空格
来源：http://dali.hfpthk.cn/Article/details/gtpfldpmug.html

SELECT TRIM(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtznyzhorl.html

[Q85] 数值取整
来源：http://dali.jianghu66.top/Article/details/gtauelksqk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtggvjxwru.html

[Q86] 读取 JSON 字段
来源：http://dali.smart0.xyz/Article/details/gtjlflrvrt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtgutmirsv.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gtyweztlxd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtdktxmuvu.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtvyublipq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jiagoushi.top/Article/details/gtfyoybvse.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtfscgnkaw.html

[Q89] 判断表是否存在
来源：http://dali.yueranfly.top/Article/details/gtuxonyfox.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xziqi.cn/Article/details/gtkbaelkdf.html

[Q90] 生成序号列
来源：http://dali.guowangkeji.top/Article/details/gtknarcozm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenlongwang.top/Article/details/gtpzxhdznn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtqpoiyiqc.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtqkvjydhz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxpsspkts.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtelovabbk.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gtnqkckkaj.html

set -euo pipefail
来源：http://dali.c1oappe.top/Article/details/gtwqrdqufv.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtwdxflqat.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtpftxzcwj.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gtolbeomke.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtdybknnrk.html

[R04] 位置参数
来源：http://dali.gaohongyu789.top/Article/details/gthktzvsms.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtdntfuien.html

[R05] 参数默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtolazpvar.html

name="${1:-default}"
来源：http://dali.tian-w.cn/Article/details/gtfwsmskuw.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtmjhomfip.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtndlvzgak.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtwknbzjso.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jianghu66.top/Article/details/gtbvyulvjg.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gthlbpfcsh.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtouuotata.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtasuiwupz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtvlxbouzt.html

[R10] 正则匹配
来源：http://dali.tianlin.xyz/Article/details/gtfgujwknl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yueranfly.top/Article/details/gtnnmbiurb.html

[R11] case 多分支
来源：http://dali.ppjwa.cn/Article/details/gtqspxiimp.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gteuzasyug.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtojccjinf.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjswnjae.html

*)     echo "未知命令" ;;
来源：http://dali.ybcxt.top/Article/details/gtvymxexab.html

esac
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcltegsl.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtmkcleiwz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtuliluptr.html

[R13] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtbekwepvb.html


<!-- 参考信息 -->