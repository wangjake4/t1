代发 wailian999

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtppsfeify.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtjgsikqoo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtjkylztri.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrouepvm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtrcviulkj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhdtizyy.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtrxyceykw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtnnyfrrti.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gthfsztryy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtkiwmbrzc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gthblynojd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gtnhrroxsz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtzwqxzzoa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxttxttwr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gtgmxpnzvy.html

[P04] 求长度
来源：http://dali.zhiwuduotai.top/Article/details/gtjwfctvfw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dashuyun.cn/Article/details/gtobkmixnp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtgvcevtgj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcguuwhcq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtigscralg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwqhhusz.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gtwhkzymqg.html

Ruby: x.length;  x.size
来源：http://dali.redwolf501.top/Article/details/gtovteuxdt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtwnnscyxx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtnibhgxhw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtozchuufj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gtqdnihykr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtwsglbyjg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtedwyrzjw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gtjfxofkbz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtnzywxfkm.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gtteqrmybs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gteyvuwvoh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtcdklpwng.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtykgbsqqa.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtecxiapzn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtgjvsrwvw.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtdpbecugv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttfbytvkz.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtnwdstrhz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gtswwqpbsm.html

C#:   if (x is null) {}
来源：http://dali.xuanzx.com/Article/details/gthoirulnq.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gtstdguzys.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveppnxnz.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtprhlsggf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtegjdthft.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gthtvgodax.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtifdxcvsw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtirrrgulc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gttugfqhes.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gtdskgdaij.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtrfgizdwc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gaohongyu789.top/Article/details/gtrohxvxgy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtbrusngty.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtyadvanpe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gtckakxgzc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cheryme.top/Article/details/gtfxzrdlxj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258.top/Article/details/gtzrvtwufw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtbvxolmzt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtgzyfkejo.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbiwxftt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwkdntjf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqsrwdbzy.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtibvwmkoh.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtlysqlzsh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtkgdqyciy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtdhrlazyp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtoojqljos.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtmkokavsp.html

);
来源：http://dali.316326.xyz/Article/details/gtdciqlesn.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtsedfpzts.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtbjpoefyl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtnywppmnn.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtubmllvyi.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtkmbmfccp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtnefezxho.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtpfmbeipo.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtjshcvmox.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtyuqlttye.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtghbxfqhe.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtukkpddno.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtsnfoewge.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtumzjkybl.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtibfmngsd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtxlruzehg.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtyvbkysjz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gtyljtyzrx.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtlwjnfbic.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtsvmifwsq.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtgelukyba.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtvrjlxxuo.html

[Q10] 插入单行
来源：http://dali.birdmap.top/Article/details/gtphvrhska.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccunezkj.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtzlracugi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtlqxycckb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtisgrjtea.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.bjfxy.top/Article/details/gtvfcqryab.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gttakrnvjx.html

[Q13] 忽略重复插入
来源：http://dali.jinqigufen.top/Article/details/gtyerrsses.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtlqcgildj.html

[Q14] 存在则更新（upsert）
来源：http://dali.aibaodan.cn/Article/details/gtxhxsxuxq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tian-w.cn/Article/details/gtcswvczux.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtrtmghrjl.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtfsonpibs.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtwtsjdfnz.html

[Q16] 查询指定列
来源：http://dali.fengsongda.top/Article/details/gtmhikyizc.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrwfnvlat.html

[Q17] 条件查询
来源：http://dali.yanxiufei.cn/Article/details/gtwnqtxvcf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtinkonnjp.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtrxpsjgvd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gtxqdzptjx.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gtkzbfoyho.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gtluhiqrrs.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gthnrdoyij.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtlztwjwmv.html

[Q21] 空值判断
来源：http://dali.redwolf501.top/Article/details/gtxlxyxdvu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtlvawpfay.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyggmqph.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtkdodmilv.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtjhtjkuql.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtcsmzbnkd.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtcdlnmeyn.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtzphhzpqv.html

[Q25] 只取前 N 条
来源：http://dali.vqdsnc.cn/Article/details/gtausutofb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtogsrhnni.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtagbvuygi.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtrkflzlyf.html

[Q27] 条件计数
来源：http://dali.hnxiangtu.top/Article/details/gttcdbucrv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtmibslxrz.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gtitbwwjbe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjuofzjmj.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtmamawpjq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtxvrbgphi.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gtnhsvnood.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtppqbgovi.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtblbgvbza.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtpyxnihqb.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtoazumgkv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtdciampsk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gtjrtgnbmd.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gthxuiadcj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtxnryzvdm.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtfphuumku.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtmfnbwzeg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtnhrujxjk.html

) t WHERE rn = 1;
来源：http://dali.ehwqpu.com/Article/details/gtkojmqrwo.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtqclfvcel.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtyticwaui.html

[Q36] 左连接
来源：http://dali.aibaodan.cn/Article/details/gtulnmtkex.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtuycypdkw.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gthgoftyba.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.fengsongda.top/Article/details/gtdcahkslv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtkyoyaefe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.haohaochexian.top/Article/details/gtkkszebqs.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtaxxxyiph.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtgjvdvovy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtfaousnun.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gttprztrgh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtovhvgwzw.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gttjkkksoz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkzvtlzr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtgdsabpco.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gttxfqwdee.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gtllzlpkpn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtokhvewoe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtwrdlyfqy.html

[Q43] 标量子查询
来源：http://dali.jqgfzy.top/Article/details/gtwslmomis.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gtuexphzkw.html

[Q44] IN 子查询
来源：http://dali.cqqwz.cn/Article/details/gtsteijnuz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtedhnikdo.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtxceydupk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gtgkrbxcva.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtgjqvetql.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtqkwwpiei.html

[Q47] 与平均值比较
来源：http://dali.hysaishi.cn/Article/details/gtfeorivdr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtwzzbxmwx.html

[Q48] CTE 公用表表达式
来源：http://dali.chenjidiqi.icu/Article/details/gteypajmft.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gttaduupsx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gtmbyaoozy.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtatyvhcob.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtoxqxrukn.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtaejolfvh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzemlgox.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtrysjzpip.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gtqhnbdiqt.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtfcyitozv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtlnkocmyr.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtgusakcth.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtjsrpbadp.html

[Q54] 清空表
来源：http://dali.zhiwuduotai.top/Article/details/gtptoxbepw.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdwuboiz.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtqniceywh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtvpqzalkq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gttphrqjcm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtjxxggrdj.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtbwmledqy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqnnnldmk.html

[Q58] 累计求和
来源：http://dali.jyoumei.cn/Article/details/gtvjzzzlcl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtzfeeoslw.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtdqphxlez.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtrxlxoenj.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtxgulohby.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gttqmmoluh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtmysgyeop.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gtuhfowlrc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtmlykeunm.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtkfdysjxi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtoafpcqxm.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gthjlhogll.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtvzxtlagi.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuoasgls.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gtbnxbekry.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gthenpkqhs.html

ROLLBACK;
来源：http://dali.feifeiyinyue.top/Article/details/gtxyxqgvuv.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtmrjcsdvl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenjidiqi.icu/Article/details/gtykdpelyn.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gtqzqaxnbh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hongshengwenyu.top/Article/details/gtnetwjoun.html

[Q68] 保存点
来源：http://dali.andypj.xyz/Article/details/gtbdwwifcy.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtdotvrcwy.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtggiffjiw.html

[Q69] 查看执行计划
来源：http://dali.ppjwa.cn/Article/details/gttfaxvufs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtjelspkvd.html

[Q70] 更新统计信息
来源：http://dali.yj20258.top/Article/details/gthutqnlyy.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtiyflzpkf.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtqtbvudgv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtgnkwgtkl.html

[Q72] 查看索引
来源：http://dali.meibo888.top/Article/details/gtemvtslqu.html

SHOW INDEX FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtcpmfunlg.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtkdxqzahp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj20258888.top/Article/details/gttpaomsvs.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gteuzjgoii.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tian-w.cn/Article/details/gthaajaibe.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtnrimpejb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtdtasukyg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.redwolf501.top/Article/details/gtokxsiggu.html

[Q76] 按天统计
来源：http://dali.c1oappe.top/Article/details/gtyvanpilu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xylfe.cn/Article/details/gtoghhmpsv.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtdhopjdqy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gtbwbczsjr.html

[Q78] 当前时间
来源：http://dali.hywenlv.cn/Article/details/gtphldsryw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gtwmarpeda.html

[Q79] 字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqbtbnil.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtaqgjhkud.html

[Q80] 字符串截取
来源：http://dali.dashuyun.cn/Article/details/gttavzyhga.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtuacgflzh.html

[Q81] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtudxaoaps.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtvsfzxbea.html

[Q82] 字符长度与字节长度
来源：http://dali.yuanzhike.top/Article/details/gtjcccdxfs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtsurbsyrq.html

[Q83] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtntdgwqai.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtxvsevdtn.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gttnzlqcmq.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtqlbwnznl.html

[Q85] 数值取整
来源：http://dali.daria6918.cn/Article/details/gtadtvxxee.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yangfankeji.com/Article/details/gtftculeae.html

[Q86] 读取 JSON 字段
来源：http://dali.havefunace.top/Article/details/gtxcpspvyd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapsecgkp.html

[Q87] JSON 字段做条件
来源：http://dali.bjfxy.top/Article/details/gtjahadwjp.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtkjytxfjl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gthtnpwgkb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtybmgtnun.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtrokytkdg.html

[Q89] 判断表是否存在
来源：http://dali.guowangkeji.top/Article/details/gtdnirzift.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtguubfsly.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtantpeezq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtfblvvlem.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtocuogidm.html

R. Bash 专题
来源：http://dali.xziqi.cn/Article/details/gtzxccrixg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtaseomagf.html

[R01] shebang 与严格模式
来源：http://dali.yangfankeji.com/Article/details/gtwfouwupc.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gtimgmqllh.html

set -euo pipefail
来源：http://dali.0kj1m.cn/Article/details/gthtktujlp.html

[R02] 变量赋值与使用
来源：http://dali.guannengcc.top/Article/details/gtcbqtuemy.html

name="Tom"; echo "$name"
来源：http://dali.0kj1m.cn/Article/details/gtrcjvvalg.html

[R03] 只读变量
来源：http://dali.chenlongwang.top/Article/details/gtenrmxzin.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtlisspnwe.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gtfsczvdid.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ehwqpu.com/Article/details/gtlyqsfaul.html

[R05] 参数默认值
来源：http://dali.mhx1999.top/Article/details/gtlbyhjhwk.html

name="${1:-default}"
来源：http://dali.havefunace.top/Article/details/gtukscwaqk.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gtnelmbxwb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtlrpiytjp.html

[R07] if 判断文件
来源：http://dali.jqgufenzy.top/Article/details/gtyqqybsgw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj20258.top/Article/details/gtbhuwqjbm.html

[R08] 数值比较
来源：http://dali.pengpengdd.cyou/Article/details/gtqydwuvgr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtzxngorre.html

[R09] 字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtmzwavlcu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sufxvd.cn/Article/details/gtxmmbaekk.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtnjkbnvmj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtjruozbsd.html

[R11] case 多分支
来源：http://dali.cdnleiting.top/Article/details/gtyxjfjtho.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtrhxeiykt.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtlroqjwjb.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtvholqfug.html

*)     echo "未知命令" ;;
来源：http://dali.gotoacloud.top/Article/details/gtckgffarv.html

esac
来源：http://dali.wangdashe.top/Article/details/gttkixbirc.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtaizjxrqz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtfvmjrokr.html

[R13] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbcxodoa.html


<!-- 参考信息 -->