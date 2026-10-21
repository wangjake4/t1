代发 wailian999

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtahirdsjb.html

Py:   str(uuid.uuid4())
来源：http://dali.0kj1m.cn/Article/details/gtpfobtsnv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtmzbtfvff.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gthlclsevm.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtyvdeokdt.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gthygmbwtr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gtcwgzllbq.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtlrkqsuii.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenzaomai.com/Article/details/gtilvfguml.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtjkhcrzuq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtudvstwug.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbjvrgbgy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnkxenpr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtvfouxuye.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtryrdlfuw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gtbdfzjvaf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtrohdonle.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtelyfvuqc.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtuxjxjrsr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yvedp.cn/Article/details/gtxiobxrfh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gtfgautxpc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtgcmvuzjn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtyckcujdq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyrbufdb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtvfrtrkmd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gtncmseeya.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtdhqtzpmi.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gtezqegomq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yueranfly.top/Article/details/gtnobglmzq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjifbchu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtklkfwtkv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtikadeaaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gttdrnkqzw.html

Go:   len(arr);  len(m)
来源：http://dali.zhoulong.xyz/Article/details/gtpbkjcqwb.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtjtkwfsvq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtesfgwhqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtqhclpfsz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtrudxopwn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtvxqkdmjy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gttpnwduvu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtjfbetzey.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gtyacuhefl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtwqlayigj.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gtxdnexqqh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtfoiksjqk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhongyouzk.top/Article/details/gtaqbhyrbj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtndifryrp.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gthknguavh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gtwweyodjk.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtjdjvuopx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtvprgsnqc.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtvjhopqkg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtkoqklryr.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtmddrzwvx.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllacwnxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gttlckvozp.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gttwhusdcm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtoyzvqbnj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtqxamnwwi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtqjtzjnvr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtxdwmldne.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtmyspaefv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gttgswszzm.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtkudgxwhc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigufen.top/Article/details/gtgqybyjrg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gtjnecrbap.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtcxafkjrr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtcdshxwmh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtfwdmftpc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtnbvbkevh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtbgyetxld.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtzqshkmkl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwqlfdxbw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtsguxigmp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtybezluzh.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtofahwzqv.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gtryquilop.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtmryrscpe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtdvvwecqu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtstmjgmif.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gtzorodqvf.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtkkxbfphu.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gthwwgwuvm.html

CREATE TABLE orders (
来源：http://dali.hysaishi.cn/Article/details/gtkiqqdpbd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtexcfpkbw.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtsiptboht.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gteudhvcsv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yanxiufei.cn/Article/details/gtahrzapwx.html

);
来源：http://dali.yanxiufei.cn/Article/details/gticxludqs.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gtmglxkuno.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtdarpfiap.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtkweakuev.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtfjlncach.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtygkmppdo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shuidangran.top/Article/details/gtbrbzcmlq.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtvrcsckua.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gthtqnirck.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtcljssbxa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtddedrnbq.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtbzrhtsqv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtwxvqgxga.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gtedostmjc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtxibldaef.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtrqwhzeok.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtzemnjlwo.html

[Q11] 一次插入多行
来源：http://dali.jlsjyb.cn/Article/details/gtnufboxkn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtvmujtcvq.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxxyvybl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dianchejie.cn/Article/details/gtedhapsez.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jyoumei.cn/Article/details/gtwyjcmsqw.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtlsqyuyhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtxmwcaadi.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtcybremwe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gtquwlbini.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.andypj.xyz/Article/details/gtdtzxvbne.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gtnwxtbkxr.html

SELECT * FROM users;
来源：http://dali.sweek.top/Article/details/gtevmtfgdz.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gtasjitrwt.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtchmjhugq.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtlnenudmw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gttmooaytl.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtdefidzxh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgmijkmd.html

[Q19] 范围查询
来源：http://dali.pengpengdd.cyou/Article/details/gtaafgbkje.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daria6918.cn/Article/details/gtmwmidudz.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtadhlfpdo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aibaodan.cn/Article/details/gtdczpqhvx.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtrntvtbcg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gtsufbbgkl.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtucakicye.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gtvzrvdnon.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gtmcpbmfhl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.mhx1999.top/Article/details/gtymdiyzwk.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtwzcnevmw.html

SELECT DISTINCT city FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtttuypahd.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtxntzanvj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtlqtldlwn.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtymfwmbsd.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtqepleqyl.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtimkdhzts.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtcynralhv.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtawvlkvgz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gthxsxmcwg.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtnkuxqmaa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtslemghvf.html

[Q30] 分组统计
来源：http://dali.guowangkeji.top/Article/details/gtagaqbygd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtudhijwwv.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtrfbejvxy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtagbpptxp.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtzzmbuvxa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gteuwsvycl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtmsubsxnj.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtvmxfehzv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenzaomai.com/Article/details/gtvaaytusq.html

[Q34] 每组取第一条
来源：http://dali.daxiang520.top/Article/details/gtrbrkxpki.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtsdygnyda.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtdlwedkhn.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtudyjlvic.html

[Q35] 内连接
来源：http://dali.wangshuangyany.cn/Article/details/gtaialrwxp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtxktggmys.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gthsndjmsp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtvnmoywnq.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtsbygjrni.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yonumen.top/Article/details/gtivwmoviq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtmsilreee.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtrxorpvyj.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gthdlazryb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtxfuqfgce.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtrhljegbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gthztfimzt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtlqllkzxm.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtcrcdihrl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtcihmcxsx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.andypj.xyz/Article/details/gtftzvccey.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gtdqptexiu.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtvddkisqg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ppjwa.cn/Article/details/gtbajfoyty.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtvjsivfmx.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gtgjlnksfl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtbhpcjvvm.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gtnpjuxsjh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtryektszh.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtxbcapztf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtvstammwp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hammf.cn/Article/details/gtrbgbinda.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtbuwznmpz.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfibftvmr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gtlhxbalse.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gtipgssghe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtdydglqju.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.316326.xyz/Article/details/gtuqdrhvsz.html

[Q49] 更新单行
来源：http://dali.smart0.xyz/Article/details/gtynlirxco.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtjmhtvhme.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtbnasduzd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gtarwmloka.html

[Q51] 用子查询更新
来源：http://dali.nanxuanxn.top/Article/details/gtkghqldaq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtvgujnuzd.html

[Q52] 删除指定行
来源：http://dali.yuxming.cn/Article/details/gtuughiqvv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gttlrrfaip.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtdrgtzljt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gthytvxjmm.html

[Q54] 清空表
来源：http://dali.xylfe.cn/Article/details/gteuwqqdah.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtyzthojyw.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gtwnaocwvj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ydzc1.top/Article/details/gtdvatdsoi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenzaomai.com/Article/details/gthsavoshd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtfmhotwrk.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtmimiyiev.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnryhjmqu.html

[Q58] 累计求和
来源：http://dali.tianlin.xyz/Article/details/gtidazqrpk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtnhoaevtd.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtdxrdokci.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtmrcohdts.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtdzbvmovf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gtvkefuehz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gthgyggvtn.html

[Q61] 移动平均
来源：http://dali.zdqjudy.top/Article/details/gttreltjwk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtswfhgrik.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gttgwtwraq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtafebfpwk.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtyhyizvbc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.c1oappe.top/Article/details/gtpxggxfmj.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxcbabuh.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtmbkulkyg.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtkodwfbeq.html

ROLLBACK;
来源：http://dali.mhx1999.top/Article/details/gtwshciwqh.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtblyfryyq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtrafvxdqg.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtdbnvwymc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtkmetvqde.html

[Q68] 保存点
来源：http://dali.c1oappe.top/Article/details/gtwzuvhrnh.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtsseccfbp.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtksmjwjub.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtduyfqvda.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gttjadzynh.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gtpjbipxju.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqcynnte.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtxlnveoqa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtutxoaqqy.html

[Q72] 查看索引
来源：http://dali.birdmap.top/Article/details/gtvhuypuwa.html

SHOW INDEX FROM users;
来源：http://dali.birdmap.top/Article/details/gtbbeslnno.html

[Q73] 查看表状态
来源：http://dali.c1oappe.top/Article/details/gtkrkmmnjs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zycfv.cn/Article/details/gtkxrknzsk.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtvsvfsmyp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jyoumei.cn/Article/details/gtxjssztxe.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtzlxphajq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtuadclrhu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gtwnorhore.html

[Q76] 按天统计
来源：http://dali.yueranfly.top/Article/details/gtzjmzadlr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gtwqyxyzag.html

[Q77] 时间加减
来源：http://dali.yongpay.top/Article/details/gtomvkckbx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gttmemytqq.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtaljwactp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtindmxgxp.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtvlqahzpv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ivvv.top/Article/details/gtoshxjove.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtxahvgsls.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.pycfn.com/Article/details/gtwsljxpgc.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtvbnvhhwt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtswopvtzh.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigfzy.top/Article/details/gtzzffnbxf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtqwvvnaqa.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gteofbewvr.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtnpigcqoh.html

[Q84] 去除首尾空格
来源：http://dali.sysykeji.top/Article/details/gtobghyhsg.html

SELECT TRIM(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtcvxcjhrb.html

[Q85] 数值取整
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpxkbmrg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtijkvlekf.html

[Q86] 读取 JSON 字段
来源：http://dali.nwbrower.top/Article/details/gtcrspqdov.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxuanxn.top/Article/details/gtacamkiwf.html

[Q87] JSON 字段做条件
来源：http://dali.haohaochexian.top/Article/details/gthohcwhny.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ybcxt.top/Article/details/gtjxpwksyu.html

[Q88] 行转列（条件聚合）
来源：http://dali.hongshengwenyu.top/Article/details/gtayckxhem.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhoulong.xyz/Article/details/gtvfabdxmf.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoejdtsvf.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gtqapdjswg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gtxqbafbpi.html

[Q90] 生成序号列
来源：http://dali.ydzc1.top/Article/details/gtrdowiglr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhengqikj.top/Article/details/gtixqoktcv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttnoqyqor.html

R. Bash 专题
来源：http://dali.hammf.cn/Article/details/gthagaltfx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgpgnijom.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtulvdlbce.html

#!/usr/bin/env bash
来源：http://dali.hammf.cn/Article/details/gtcjdqqhom.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtwweicnvc.html

[R02] 变量赋值与使用
来源：http://dali.0kj1m.cn/Article/details/gthorkdoxz.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtosdtmnou.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gtkbfbmuky.html

readonly PI=3.14
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgclvitge.html

[R04] 位置参数
来源：http://dali.gogol.net.cn/Article/details/gttvfnvoty.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtgajgjqza.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gtkknmwgoc.html

name="${1:-default}"
来源：http://dali.bjfxy.top/Article/details/gttcoxpbzo.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtdbhenebk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhuqktdr.html

[R07] if 判断文件
来源：http://dali.birdmap.top/Article/details/gtqltcepmw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenlongwang.top/Article/details/gtnrmwyzxi.html

[R08] 数值比较
来源：http://dali.hywenlv.cn/Article/details/gtasjhebqk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrqkuorl.html

[R09] 字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gtwoqvbekf.html


<!-- 参考信息 -->