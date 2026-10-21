代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtrocdfbpp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtksyyblql.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtgtsimtiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtgdrzgwrc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtzwivjwmi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gtkuhpybtc.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gtgbokxcbt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhengqikj.top/Article/details/gtyepbhnun.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtmwxduuea.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gthsilfmbw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtgjkqiymw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gtgcfefoxs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtthvprijh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtsuryuakt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwupjgkz.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdokpawr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtqszqkwto.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtmktlurkw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtzrnwpvlh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtehdaorjt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrqvvmwz.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtuiilivrb.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtyrqahrxd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtfptjujif.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtxzjjxzff.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gtbmqlwzec.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtrdxkpisr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtpxkvvoov.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtaxptapnj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtxozytiay.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gtshxjxoqa.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtzzsejuhp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtewwbfiwh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tian-w.cn/Article/details/gtohjjikro.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cqqwz.cn/Article/details/gtvfkhbubn.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtebcbrpcz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gtbddkzgwa.html

TS:   if (x == null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuigflgag.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtchyxkmpv.html

Go:   if x == nil {}
来源：http://dali.hnqzz.top/Article/details/gtzidxawss.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gtwtbvvzqo.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtdueqzvuz.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtompybbst.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywkiqhfr.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtcqsadyca.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtrofdkuch.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtuziiitvg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtrcfzsgtr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtesvsnprj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gotoacloud.top/Article/details/gtqbauoswa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtnokyrytw.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gtjyzvrstz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuqvjkam.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtmuylkkvi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtumlckifs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gtnmvakojq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtrdbrclxa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtxsrevexv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtpfiqwcbt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtslktcqof.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsgbdpjia.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtzlctxnbs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfrbuiphn.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtrjbwxduk.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjoypmnq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtqnjfjdup.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtkybbxmne.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gteduhvyhu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtnpciylmq.html

);
来源：http://dali.jlsjyb.cn/Article/details/gthwykdupr.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtwddkligw.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtcmqwofxa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gthhlurbwn.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gteqpzmggg.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gtmcdbejkq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtrnqswnur.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkybpcokn.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtexahekku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtbgmrtqyj.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtzurvyqze.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtfrtkzlmf.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtgicgduxb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtifxikvvz.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtnnwttyru.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gtoaceeqiu.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtksomgccs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtlhteahgv.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtcmqpaozj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrksxjpvg.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtjffwplva.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtahlyjlzl.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtxpmoptkx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gttwnaclyb.html

[Q11] 一次插入多行
来源：http://dali.pycfn.com/Article/details/gtutxyerjt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daxiang520.top/Article/details/gtpfpwsqjq.html

[Q12] 插入后取自增 ID
来源：http://dali.smart0.xyz/Article/details/gtvyyftkkd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtvojlytdt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ivvv.top/Article/details/gtjgzmjaeg.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtkkfuumlk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtthokcobs.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtbfqlsiwq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtnxoguhxk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtlppzqkbk.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gtdiyzwctd.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtwtbznyqj.html

[Q16] 查询指定列
来源：http://dali.smart0.xyz/Article/details/gthynydfkz.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtfrzttrut.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjuguslc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtaekhaguk.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtdszzwtkb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtpgzkitdu.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gteybeomxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtgldlklat.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtwzupkfcu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtfsfbmuus.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gtcgipxyqp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtmvifvtcg.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtclqbuwxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gtajbdjmoa.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtaotyxhoo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zycfv.cn/Article/details/gtsigrlsis.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtfxfesrwr.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtzgkezivs.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtmqlmrpda.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gttfvyyboi.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtaercxaaa.html

SELECT COUNT(*) FROM users;
来源：http://dali.meibo888.top/Article/details/gtndxxxqsc.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtwukybqgy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gtmuizbzra.html

[Q28] 求和与平均
来源：http://dali.9152youxi.cn/Article/details/gtuyynkyzl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtnjmelqoh.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtfmqbniep.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtimwgomqs.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtjzsyghdq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtmdmrtfaa.html

[Q31] 分组后过滤
来源：http://dali.cdnleiting.top/Article/details/gtbhnwoqgx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtgapatebe.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gthobrvtdh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtfhuwwkmr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gthkivrfqd.html

[Q33] 多列分组
来源：http://dali.yj202588.top/Article/details/gtfzydlcpb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gthomggyve.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtcaenroal.html

SELECT * FROM (
来源：http://dali.gzhubu.top/Article/details/gtmdjgydft.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gtakzmmnhk.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtoanbnkky.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtqvfvcxyv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtjtixwthb.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtrkgpgyox.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtcmamlmow.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gthyfnlhqp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gtyxorszry.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aibaodan.cn/Article/details/gthrqfhatr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.redwolf501.top/Article/details/gtkhkgvpvj.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtocnhblzs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gtstsbsmzf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fengsongda.top/Article/details/gtzwhdwcwj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtsyuzqmzj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daxiang520.top/Article/details/gtjnzhqvyg.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpiuttaqp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gteeqhjrxx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtkrmyxkwp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gtvoxsuvsd.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gtkxfctzpx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtrlgqaull.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.mhx1999.top/Article/details/gtqbpokzdc.html

[Q43] 标量子查询
来源：http://dali.yuanzhike.top/Article/details/gtosimoblf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gtfrfgsxbb.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtynwypjus.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtbpiabxse.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtjnfpkwut.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlmoxonk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtdlhiynbz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtvuwuinfj.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gtwudouink.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtyqzmdqtu.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqjfqloz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gtmatiwzmp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtgfnusfbb.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gttqevrxbf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtcwmcrjao.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtgisoqgbt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hongshengwenyu.top/Article/details/gtautyuled.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtcawmvibd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtincjplxq.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtxoghoucx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtshdmczeb.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtukpcroxv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gtyfaeytyb.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtizsvpzqq.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gttkcbjrgk.html

[Q55] 排名（并列占位）
来源：http://dali.cdnleiting.top/Article/details/gtkjzupyyh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtflmhmzxp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtztzrsbze.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtcvbifafu.html

[Q57] 行号
来源：http://dali.haohaochexian.top/Article/details/gtxfrjctan.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttfkfhsfv.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtvecizwjw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtiwakrlfh.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtnusnsdgn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtglnksuxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zycfv.cn/Article/details/gtvnmilocj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtgdcsgmvr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtgpqmvttp.html

[Q61] 移动平均
来源：http://dali.jyoumei.cn/Article/details/gtvoewjsop.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtzvianqjn.html

[Q62] 分组占比
来源：http://dali.yj20258.top/Article/details/gtalvddwlh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjqcveqk.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtguixmils.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtefqhaglw.html

[Q64] 提交事务
来源：http://dali.jinqigufen.top/Article/details/gtfxzmkofz.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnndantha.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gttyokglbw.html

ROLLBACK;
来源：http://dali.jyoumei.cn/Article/details/gtuypyyaet.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtyjzeckgx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtoszzfchl.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtzzcbhzzt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtjhwbsrwy.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtbfekycga.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtoanvtrkn.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtrszitfld.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtkyxvzcnq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxuanxn.top/Article/details/gtnxltnpdv.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzjyntex.html

ANALYZE TABLE users;
来源：http://dali.daxiang520.top/Article/details/gtxyqjhrmj.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtxdwnmygc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtgfzoqjyv.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gttlptjaqr.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtfvfvcopo.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtwvfvzldt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guannengcc.top/Article/details/gtwqcjkjmk.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtjnalmnqf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtawiqejut.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gteshtixge.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtbffeicti.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtcnlliuke.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtqyxnoalf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtthrfmpwg.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtlvxekkpq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yonumen.top/Article/details/gtvxbxptln.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtknzimtzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangdashe.top/Article/details/gtlixuakab.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtrkntdxxz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gtizgyuubd.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtyhnznfsu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpesjigks.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtfudllkwc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtkhmjzboy.html

[Q82] 字符长度与字节长度
来源：http://dali.wangdashe.top/Article/details/gtyteshdni.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtnkzncznn.html

[Q83] 大小写转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtavfyybvf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtmzzltdni.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtqazqjsaj.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gthgcjelgh.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtihdvheev.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtfwzcvxqo.html

[Q86] 读取 JSON 字段
来源：http://dali.quarkkingdee.top/Article/details/gtohfackgd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gtwikktolu.html

[Q87] JSON 字段做条件
来源：http://dali.wangdashe.top/Article/details/gtuigawmtd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.0kj1m.cn/Article/details/gtbftkjzzz.html

[Q88] 行转列（条件聚合）
来源：http://dali.ehwqpu.com/Article/details/gtupklidco.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cdnleiting.top/Article/details/gtmyfghqqw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtwyqlcjpd.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gtwkzxvyke.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258.top/Article/details/gtjkutlijd.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwahqmzvu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuanzhike.top/Article/details/gtrnbtvfwg.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgqnkwin.html

R. Bash 专题
来源：http://dali.zhengqikj.top/Article/details/gtmyqqqabe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjhgnamdy.html

[R01] shebang 与严格模式
来源：http://dali.shuidangran.top/Article/details/gtmwssqkmt.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtswprxnsv.html

set -euo pipefail
来源：http://dali.fzhhl.top/Article/details/gtjfzkwlyn.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtzepparfk.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagsvffmi.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gtwomfkxgu.html

readonly PI=3.14
来源：http://dali.cashguo.top/Article/details/gtnoysruou.html

[R04] 位置参数
来源：http://dali.ppjwa.cn/Article/details/gtfwvervfs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtbzeurmcv.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gttzdlcudj.html

name="${1:-default}"
来源：http://dali.xuanzx.com/Article/details/gtfbhfxvug.html

[R06] 判断命令是否存在
来源：http://dali.316326.xyz/Article/details/gtdxnshwvn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtsdsskddn.html

[R07] if 判断文件
来源：http://dali.dianchejie.cn/Article/details/gtmhuyvdxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.316326.xyz/Article/details/gtqcqujjda.html

[R08] 数值比较
来源：http://dali.0kj1m.cn/Article/details/gtatrbbqwn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhoulong.xyz/Article/details/gtahcqqoqc.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtnumexlbc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dianchejie.cn/Article/details/gtieuiltem.html

[R10] 正则匹配
来源：http://dali.chenlongwang.top/Article/details/gtlzispqok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gthpobyuap.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtczdxjljp.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gthdcihoql.html

start) echo "启动" ;;
来源：http://dali.cdnleiting.top/Article/details/gtyleqnffk.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkdubzsj.html

*)     echo "未知命令" ;;
来源：http://dali.xylfe.cn/Article/details/gtjjjlffxi.html

esac
来源：http://dali.tian-w.cn/Article/details/gtvaiubkph.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gtmmikwqjr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtfxxwlugp.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtqodielou.html


<!-- 参考信息 -->