代发 wailian999

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gttfpftofz.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gtjrhyjduw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gtafcvgwha.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gtlqlwdtpy.html

TS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtljjovege.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gthbzxcybr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gttsdszjbu.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtstlwlssi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtbikgevgt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtcdwfcztg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtmooamhho.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yanxiufei.cn/Article/details/gtxefwzcsf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtmsljkwin.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.snrcjt.cn/Article/details/gtmhnjwrlb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtjmjarqzg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtamdxsjmi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gttyxyumao.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtxocueule.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtkyfuzlwh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gtcpuwgwpf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gttcukifnc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtlnpeeidw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtzpqpvoyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtmaeswhgg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtpywekwqd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtufrrqgcl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzkhpzva.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtvakyhyzl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtwfuabtir.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtavgddxqm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtiqezxdth.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gtdcmmykax.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtvhmcinow.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtziicvkxa.html

Ruby: x.length;  x.size
来源：http://dali.chenjidiqi.icu/Article/details/gtydccmyqb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gtcrlidkrk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtvwlcnjuq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtqhqqtase.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtbhmorltv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtysqklr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtsnjmmcij.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtuidtybjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtxcrfkwgg.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtwesybpaj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gtiyiddfon.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gtnsimnqof.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gteanexlnq.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtokxjudsu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtlcvkncqd.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gtfnkidzfx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gtxhjbmcqt.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtqextmhiz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.birdmap.top/Article/details/gtsgkpemza.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtlxmpmuhn.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtecwmwmwl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtgsxwdeir.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtpkxsgewt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtqistxpjf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtuftqxatg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtoabjgehd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtzeymjmug.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gterpxznuy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtlwulhrvw.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gthxhyvnop.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gtthibseno.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtcmzqlphe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.vqdsnc.cn/Article/details/gtheozwgih.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtffyigesm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtqswphxng.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cashguo.top/Article/details/gtohyyczww.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtlcxpkugk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtqxjqrsoa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtembikuhb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtcloewwio.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgqenguto.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gtbdpdepdy.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gthzztrquc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtpgafwfpt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtkcgimlia.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtmnljcawj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtqtpjyzai.html

);
来源：http://dali.jinqigufen.top/Article/details/gttzmevvpv.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtcesfwntx.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gtnszomkqh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtcrxdlkyr.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtpbpvipyt.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtjekojkwx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtoehrpgxo.html

);
来源：http://dali.ydzc1.top/Article/details/gtvfzzpged.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtdenuivke.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtdqzojcjv.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtkldvzfbz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnqzz.top/Article/details/gtuwexnako.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtuqockbns.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtfyvqmher.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gtwgpebdrt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sufxvd.cn/Article/details/gtcitnkrhr.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtziujyeea.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlknjxjz.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtcracppzd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtbmjoiazr.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtpkleewvn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnakjxvlp.html

[Q10] 插入单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajvrbevq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtlzjmmkdt.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gtmhpmhzbg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gtrhynutrg.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtpawxilbm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtfxjxrmeg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtbqkctxfk.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtwpkuzqut.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtumqxgvra.html

[Q14] 存在则更新（upsert）
来源：http://dali.jianghu66.top/Article/details/gtepvkpsai.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtngqwasfl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtefahrcfq.html

[Q15] 查询全部
来源：http://dali.zycfv.cn/Article/details/gtpkivedzw.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtmqyaoxfa.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtkihqsali.html

SELECT id, name FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtpmppjqlb.html

[Q17] 条件查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtraabhocy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtqokhppsh.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtjoupxhdr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtudgwhfmq.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtdzbdqhuo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gtlqgepocp.html

[Q20] IN 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkqkjcrp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gtvaouuwlq.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswxlbzzr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gterjxhjgs.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtxikwdktl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gtsqjgykto.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtwgmdidvy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtuwejxwqs.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtgguhweho.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtuuwqcowc.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtxilmhgnr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gtlttomazi.html

[Q26] 计数
来源：http://dali.gzhubu.top/Article/details/gtbblgqqeq.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzvltjczg.html

[Q27] 条件计数
来源：http://dali.gaohongyu789.top/Article/details/gtupabkoof.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangdashe.top/Article/details/gthrbviuze.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtoxflsnmf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtkehktjzr.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtvyehpmaq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttckonkmk.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtqhxybuaw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtfneostkn.html

[Q31] 分组后过滤
来源：http://dali.snrcjt.cn/Article/details/gtivjamgnu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gtvgrfzfku.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtaunfxxnv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukmffmbx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ydzc1.top/Article/details/gtbqhmoggt.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtqrswqldk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pengpengdd.cyou/Article/details/gthfgrvicb.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtclkajbrw.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gtaktxiwqp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.snrcjt.cn/Article/details/gtepbkqfpa.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtlimvgtog.html

[Q35] 内连接
来源：http://dali.guannengcc.top/Article/details/gtkbnavwle.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gthgusjele.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gtvidlmvlv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtplzdjzwk.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gtqvzbdmjv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aibaodan.cn/Article/details/gtahwgcjua.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgufenzy.top/Article/details/gtrabrcxhn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.mhx1999.top/Article/details/gtvduajjha.html

[Q39] 自连接（查上下级）
来源：http://dali.pycfn.com/Article/details/gtfkvoboqm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtsmescypf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtiqhxzvtb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gtfuufueye.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtwwzfpqrv.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtniefxcni.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtjtneriwr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtmtiewanc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtipnjwpvr.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gterxmifuf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtdsptfkcj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258888.top/Article/details/gtujajsuhj.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtskbpyyip.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrikoqxcv.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtmyxfcdam.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tian-w.cn/Article/details/gtxbufjcch.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gthmducnzs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtaafcgarz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.aizwys.cn/Article/details/gtbffipzwo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gthhqmftsr.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtlldnljqe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yongpay.top/Article/details/gtrrheuijj.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtbkfckprj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtvtggjggl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtywvwgvdp.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtahdrxohb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtxnevzona.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gtfjrudrkh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtnxyjwuja.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtoviedbzk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtxdcjzvqf.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtdtueinct.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtuwaokoiu.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtdvvkesou.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtlsyzpijw.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtsdkrsbjp.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtboojahyq.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtyzlwhvvx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtbmcjvkns.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigufen.top/Article/details/gthxiseuxk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtyyrxwkdm.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gttgcsclul.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtermvpaat.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtoryyveju.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtcputwytm.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtzqvkfqft.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtrzjthjnq.html

[Q60] 取上一行 / 下一行
来源：http://dali.ivvv.top/Article/details/gtxledulnd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtojbfmpid.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtrtcprvhp.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtqcrmvbyn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sweek.top/Article/details/gtwqqkagtj.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtreizlxmt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtgynvhpjh.html

[Q63] 开启事务
来源：http://dali.hywenlv.cn/Article/details/gtshdakahb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtkynvfwdk.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtnvbfgdno.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtbozyzjiw.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtowrkeopg.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtadjgawby.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtnqejcaqh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtciguuezk.html

[Q67] 设置隔离级别
来源：http://dali.hfpthk.cn/Article/details/gtkhjyamhv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtlpgkskon.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gtpftupkzj.html

SAVEPOINT sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtgreaozyu.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtrgpknzgd.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtebpavael.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.c1oappe.top/Article/details/gtwynposoi.html

[Q70] 更新统计信息
来源：http://dali.ppjwa.cn/Article/details/gtgghnauwu.html

ANALYZE TABLE users;
来源：http://dali.nanxuanxn.top/Article/details/gtstczpwva.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtliqvnnjx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtqhucornt.html

[Q72] 查看索引
来源：http://dali.xuetiantiany.cn/Article/details/gtywuxxnjk.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdomfgeti.html

[Q73] 查看表状态
来源：http://dali.zhengqikj.top/Article/details/gtpyavfkgv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfehffaon.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtgwjboxge.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jlsjyb.cn/Article/details/gtkwvaqbmy.html

[Q75] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtobmlvikc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtcwuwwhav.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhixingplan.top/Article/details/gtqbcexyiv.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtpplxiozl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxinkj.top/Article/details/gtzopukaeg.html

[Q77] 时间加减
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdofozle.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtfizdmevr.html

[Q78] 当前时间
来源：http://dali.hongshengwenyu.top/Article/details/gtgtzzmxbg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtakxfxhdc.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtbicmgten.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yanxiufei.cn/Article/details/gtvkbhtibk.html

[Q80] 字符串截取
来源：http://dali.ppjwa.cn/Article/details/gtzkcdzroe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yongpay.top/Article/details/gtxaadafxt.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtotinexeu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtnyrerqrm.html

[Q82] 字符长度与字节长度
来源：http://dali.ybcxt.top/Article/details/gtxowgptst.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtxrqrfvxv.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtnwwppvun.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gttwfdjnfl.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gtatafbjlt.html

SELECT TRIM(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtwxjtbzcv.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtffgnhhtq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.tian-w.cn/Article/details/gtefdpdiym.html

[Q86] 读取 JSON 字段
来源：http://dali.sysykeji.top/Article/details/gtvhnrlbbo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cucudq.cn/Article/details/gtsbyrxyss.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtauwdgtki.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gtumeweaas.html

[Q88] 行转列（条件聚合）
来源：http://dali.dianchejie.cn/Article/details/gtwcgkqols.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj20258.top/Article/details/gtltiaqdjs.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtzhrxdtlm.html

[Q89] 判断表是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtesqiyihn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtdwsunfnn.html

[Q90] 生成序号列
来源：http://dali.daria6918.cn/Article/details/gtnjvxsdjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenjidiqi.icu/Article/details/gtnvfeqjfc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkmemlmij.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtdcozaynv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtecirtsfl.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvlhwiuw.html

#!/usr/bin/env bash
来源：http://dali.pycfn.com/Article/details/gtzqebykgg.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gttbotkdzg.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtsnekhlkk.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtnebuhabg.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtbhxlsrwo.html

readonly PI=3.14
来源：http://dali.yanxiufei.cn/Article/details/gtnhipnlbf.html

[R04] 位置参数
来源：http://dali.ybcxt.top/Article/details/gtlenfneyu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtkjsmdtgt.html

[R05] 参数默认值
来源：http://dali.kuanghao11.cn/Article/details/gtmbqjmdpy.html

name="${1:-default}"
来源：http://dali.cdnleiting.top/Article/details/gtqywcvapk.html

[R06] 判断命令是否存在
来源：http://dali.nwbrower.top/Article/details/gtsjkhatqx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxunydcgz.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtpqwjsfew.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daria6918.cn/Article/details/gtmcvupttt.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gtjqecloty.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtoaguoaef.html

[R09] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtkxpcaygd.html


<!-- 参考信息 -->