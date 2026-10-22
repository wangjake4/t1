代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtijrompsd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtcmfbngdg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtumksmlhf.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtwuuydnca.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gteenmfzaw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtlmnozcim.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihxpxoyr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkspceemc.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtqmpayuom.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtoiafivnm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtfzdbuixm.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtxhkfkkfl.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtxvqtijjc.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gtrtdtnfqd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtxiisdvbs.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtjvbtduyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtumwkyhvq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtnfmdteha.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtfaemujix.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtqapoiuwh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhixingplan.top/Article/details/gtknbjhqja.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtvlfysqzo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtxvpmfkan.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtgtsbnjdd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtlznzaqwt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gtdkvefqnh.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtgngmrmht.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtluaulgiy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtrrpeawbz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtdfdvokdl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtneawjtmm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtdpqmfgdu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtfphjfcpx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtuzvppqli.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtcmbabjvl.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gtsirxnypi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtowfmkggb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtbivgyfzu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gtmzbilcqs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtxavvwlag.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtnzybibsh.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtnhbhifsv.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtkajrymnx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.c1oappe.top/Article/details/gtscckejzk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtqcneeiqz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gtxedwreqt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtoyxzukbi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtygchdrpc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtaigtbikw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gtzdzpudnj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtpsuahmqj.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtziujndql.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gtdkagfxlu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtnxpfoxho.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtxukijbxi.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdhsqfjz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtwfjmiajp.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfioaunrf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtwdnmxkyc.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtonmudire.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfegcbqpu.html

C#:   if (x is null) {}
来源：http://dali.shzxlz.cn/Article/details/gtpjkkayjh.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtsmsbnigg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxyrwxzx.html

PHP:  // 手写时间戳比较
来源：http://dali.guannengcc.top/Article/details/gtxwxwbtra.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gttooxincz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtfchqkwge.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gtduramfeh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gttigybnba.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtwvfvsqrd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtovmtipcq.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gtzkbknozp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtphtujmhd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtzzfvhami.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gtqkkansgy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtbikyfeuk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtatsaifbd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtywnvjwta.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtoaqhalha.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gteczcbhxe.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtebuovhiy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjayiezxk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgdwmhjtc.html

[Q01] 创建表
来源：http://dali.zycfv.cn/Article/details/gtejszfepi.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gtqvoryetd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcucfrgw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtbihfklbx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.haohaochexian.top/Article/details/gtfnklbwyh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gthwzateky.html

);
来源：http://dali.havefunace.top/Article/details/gthbzeutoi.html

[Q02] 创建带外键的表
来源：http://dali.jqgfzy.top/Article/details/gtpapgkbdr.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtdkbqojlt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiyoxomk.html

user_id INT NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtjkuksgwk.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtufanbhtq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtjsblhhpt.html

);
来源：http://dali.wangdashe.top/Article/details/gtjznyvpjh.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtqhcwhecd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtxoujgzog.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtqgajduvg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtldmoszqa.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtctcmssnj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtmhgdjvrj.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtajmgogli.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemqgqwmh.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtdniaevei.html

DROP TABLE IF EXISTS orders;
来源：http://dali.316326.xyz/Article/details/gtsqeeojar.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtbfdiebln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtoqxosztd.html

[Q09] 创建唯一索引
来源：http://dali.0kj1m.cn/Article/details/gtblytxsbh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtleaidmfm.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gterppnqir.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtnjyxsfue.html

[Q11] 一次插入多行
来源：http://dali.316326.xyz/Article/details/gtnjvgegpp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtmcmfcojp.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkmrpqea.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtdnecsldy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gtmrhqgqlm.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtnnqtcpja.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtijtxsnnd.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtuqdsvuls.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gthseffulq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtbqptyfon.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtjenhtnxi.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvbdbjnuy.html

[Q16] 查询指定列
来源：http://dali.ppjwa.cn/Article/details/gtqgmkfgxk.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtkcslfdvk.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtwmmeeypb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gtyvlpwfaf.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtpwknwhbu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtesykjbzn.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gteqekccea.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtxwcjuabl.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtlhqbrscn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ehwqpu.com/Article/details/gtqvjfjzln.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtyicukfxh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtfgznepqv.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtwbwrbejc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtozilobrm.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrezffuu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtdosgjbhi.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtpdterpae.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gtvfohxzul.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gtlpzdtrrw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gthvucssvs.html

[Q26] 计数
来源：http://dali.tanke756.top/Article/details/gtvjwusihm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtzxttxouq.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gtaycbjell.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtplqvjoex.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gthhiyxjua.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtjbqbpues.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtrdilrbij.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjvohbeg.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gtcwjjeclb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtjdcmkoic.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtmajiyxld.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtkebncwii.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtsmxftzoj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtrboerdjy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtcumvttgj.html

[Q33] 多列分组
来源：http://dali.redwolf501.top/Article/details/gtjfgqshrk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtbrzjccbe.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtwdmqhjdl.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtlpllapyq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtnjrysfya.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtvtqjgbpt.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtjxiiklmu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtijpebrlc.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gttvmgykdc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtdnagdnaz.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gtdtmoapvy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtngmjqigi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtwdgiyduc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gthlduvvdz.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtlcubpjog.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtecnuodbq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dashuyun.cn/Article/details/gtxxebdqth.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtokvcsbke.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.daria6918.cn/Article/details/gtggreeycz.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtblrkhuzu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtijnvfmcb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gtbtbkwegi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ehwqpu.com/Article/details/gtlnuzxhfz.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gttthslpkb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gttuqfgjot.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gtervekcoq.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gtsvziwvoj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtgbuvedoj.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtmronwigx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pengpengdd.cyou/Article/details/gtzmdewlwm.html

[Q45] EXISTS 判断存在
来源：http://dali.dianchejie.cn/Article/details/gtyegpiwqg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtmrpziavv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtgsplyutm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtxhahxwqi.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtydrwlcer.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.bjfxy.top/Article/details/gttqqaukgd.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtmggpylhu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangshuangyany.cn/Article/details/gtktfwlygb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtjbmaeoly.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gtafxcexrp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtjwrvuqvf.html

[Q50] 批量更新
来源：http://dali.0kj1m.cn/Article/details/gtvseofsue.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtwmssdpdt.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gtkfdsyavx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtcfeimysz.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gtajntxcim.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueeqxxcq.html

[Q53] 按条件删除
来源：http://dali.cheryme.top/Article/details/gtdxfmubhn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtrxmixlgb.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtokhpyobr.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gtapjrueqe.html

[Q55] 排名（并列占位）
来源：http://dali.hfpthk.cn/Article/details/gthfasztkz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtbohhiuhf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtbgbaiquy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtroihhrao.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtvxgdyuzk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzxxxgvb.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gtwhciysrp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtnewivtei.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtlqroxgxe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtowtdexhe.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmpqbzpv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtcciyakzf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgxnrtyz.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtwcgjwktp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtexpmtplq.html

[Q62] 分组占比
来源：http://dali.zhiwuduotai.top/Article/details/gtnfkldfmg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtediozpxx.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtsssedcje.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtflzacanm.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtxpnehjdj.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtaxczfbyl.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtyjeqjehd.html

ROLLBACK;
来源：http://dali.havefunace.top/Article/details/gtiodhyibg.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtxayjwlhn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gtgyveitqn.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtdplihbai.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gtfdorfknt.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtdwsehgiw.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtvdgqttkt.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtjgfqqwhg.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gtapnwrgoy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fengsongda.top/Article/details/gtuwaujarg.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtyudilvtp.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtagssljrw.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtuopyeasx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gtwqbyxbqq.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtreshsxrh.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtgrpvxykz.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gtrwhwrwph.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtaaojenok.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gttannkoff.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtzmxxobhw.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gttsvmpniq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtafowmlsz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fengsongda.top/Article/details/gtlwgutbwk.html

[Q76] 按天统计
来源：http://dali.haohaochexian.top/Article/details/gtonmkxqzi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.mhx1999.top/Article/details/gtyppmjdgh.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtwjqwokfo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hysaishi.cn/Article/details/gtbcuzobpm.html

[Q78] 当前时间
来源：http://dali.meibo888.top/Article/details/gtlhniulag.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtsosfekir.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gttezwtoci.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.svipenyu.cn/Article/details/gtkvvcckro.html

[Q80] 字符串截取
来源：http://dali.pengpengdd.cyou/Article/details/gtmdsrtdds.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbiazfsbm.html

[Q81] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gtiopbsyec.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqjxuypc.html

[Q82] 字符长度与字节长度
来源：http://dali.jinqigufen.top/Article/details/gtgsymghai.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yonumen.top/Article/details/gtzrfpmewu.html

[Q83] 大小写转换
来源：http://dali.hnxiangtu.top/Article/details/gtlhhldaut.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtjhvcfgqm.html

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gtgllgtbmg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtsezpdlju.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtutudyoyv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtivosnefb.html

[Q86] 读取 JSON 字段
来源：http://dali.mhx1999.top/Article/details/gterugnynm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtdlqbwqyw.html

[Q87] JSON 字段做条件
来源：http://dali.yanxiufei.cn/Article/details/gtlacsndlo.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtmncdcoze.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtlaeyjnso.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtvktxehnk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtrbjwbpyv.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtkwfqvfoq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtrkkvqlpr.html

[Q90] 生成序号列
来源：http://dali.chenlongwang.top/Article/details/gtwdkulami.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nanxinkj.top/Article/details/gtvhmdczcy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbolfzumm.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjtajwmq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtejlfllmw.html

[R01] shebang 与严格模式
来源：http://dali.cdnleiting.top/Article/details/gtokjyniss.html

#!/usr/bin/env bash
来源：http://dali.yj20258888.top/Article/details/gtmzvufjtb.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtxvegagdg.html

[R02] 变量赋值与使用
来源：http://dali.cashguo.top/Article/details/gtfelfbywa.html

name="Tom"; echo "$name"
来源：http://dali.smart0.xyz/Article/details/gtvrjdihuy.html

[R03] 只读变量
来源：http://dali.zhiwuduotai.top/Article/details/gttwbfslyd.html

readonly PI=3.14
来源：http://dali.zdqjudy.top/Article/details/gtgiosvdpt.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtgfiyhyga.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ivvv.top/Article/details/gtcagwuuyh.html

[R05] 参数默认值
来源：http://dali.hywenlv.cn/Article/details/gtbatcnhxj.html


<!-- 参考信息 -->