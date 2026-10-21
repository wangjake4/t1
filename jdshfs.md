代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtimjpyzoa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzkwdvpy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtsoxifkds.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpfppuuf.html

C#:   Parallel.For
来源：http://dali.ehwqpu.com/Article/details/gtntmuqlmj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtnxlvqnsm.html

P. 常用工具函数
来源：http://dali.kuanghao11.cn/Article/details/gtxjgvnaox.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrkqmeecd.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtjzwqykba.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtxevtnaon.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtsbkquisn.html

JS:   crypto.randomUUID()
来源：http://dali.andypj.xyz/Article/details/gteddiljjp.html

TS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtshnjbdig.html

Java: UUID.randomUUID().toString()
来源：http://dali.zycfv.cn/Article/details/gtgzhjavlh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gttrxmpsui.html

Ruby: SecureRandom.uuid
来源：http://dali.birdmap.top/Article/details/gtkqgmbtvd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtukkefjwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtruvddlci.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtjxsaxxmc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtmxdaacks.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtsguvxmcx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtabullpks.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gtcfvldzdl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gtfkswbrqy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sxryk.cn/Article/details/gtkafqiqbv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtkvhdilqp.html

[P03] 生成短随机字符串
来源：http://dali.cdnleiting.top/Article/details/gtkxjwlmun.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqyujubd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gtverbmqxp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtnyhxudfu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtbynthjox.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvnuuryc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtlzhragjs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtxfnirrol.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtiymiuisg.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtkbgpdqbz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gttnvhwatn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtiaxtqdpw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtwicvqmew.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtjthrfimt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gttugnirmr.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjbkxkps.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtcyyvnsts.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrsebbjd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gthuwdtjsv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvenwrdth.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtjajkpsjw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gttqovnwuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtlhkgldzm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnoqiital.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtorksfpea.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtamltjvgw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gtbxaclrmt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtdbxwxhpf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gthxpckiuf.html

PHP:  if (empty($x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtbxuuubus.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gttneguhez.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtjidvgaqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtkdogcsio.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gtjebpbivp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gtkbvryjmr.html

C#:   if (x is null) {}
来源：http://dali.jinqigufen.top/Article/details/gtxcnjuwsm.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtrfdowwup.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtxbawrbzm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gthjxltsmz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtesgsjnzc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtvctorxed.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtoegtdupw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtcsjlkapa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtdwwesvzi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtcseqdvzr.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtzkswdhpv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhoulong.xyz/Article/details/gtnlmervxk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtoutfkqca.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtabtzqkau.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtfthgthay.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.svipenyu.cn/Article/details/gtmhzioszb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gtgpsbhaom.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtnfdggqav.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gtktjjhiuk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlzjgekwy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtfeggqssv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmfqrauwv.html

[Q01] 创建表
来源：http://dali.dashuyun.cn/Article/details/gtyxwsedhb.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gtkovwhstn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtjuccgxjv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gttqmcgidd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtkffmhxxp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ydzc1.top/Article/details/gtjugckjpn.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtxctndfmv.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtmrjjwohf.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtjzrwmbff.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtaljktisf.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtixiwnhwh.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtnalqxmej.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtfppndrhv.html

);
来源：http://dali.feifeiyinyue.top/Article/details/gtbsephxiw.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtmolnupbi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtleliutzn.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gtjdsuitcv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtmflqwiaj.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtrfmxemup.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtwoakgcuh.html

[Q06] 删除列
来源：http://dali.daxiang520.top/Article/details/gtdjmvmact.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtwleegtoh.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtcaksrhtc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtrjqutyab.html

[Q08] 创建普通索引
来源：http://dali.haohaochexian.top/Article/details/gtwqwpfjue.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gtfrmapjuu.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gthvquptwk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gtjqdnencm.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtqztmyhpt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtdynxbgus.html

[Q11] 一次插入多行
来源：http://dali.dianchejie.cn/Article/details/gtxsnfpuyj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gtmytokbwl.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gtqytnlemo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtulrhqycz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gthfkoqbkp.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtnqutbrfp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtiegarwui.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtjpfvksme.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pycfn.com/Article/details/gtjzdxcqju.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtbikvfqhe.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gtbvmkfcdk.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtebltvfej.html

[Q16] 查询指定列
来源：http://dali.birdmap.top/Article/details/gtxxlafvij.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtkqzhkfdo.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gtevctwckz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtatncymsw.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gtswiecaxh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gthmnjxihd.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtvprwfxvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gtkfdqhndj.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtbtiryvub.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtszfzbqvj.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtfxixxzcu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgfzy.top/Article/details/gtawhphiic.html

[Q22] 排序
来源：http://dali.meibo888.top/Article/details/gtcwqyvjkg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtoiuljjdx.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtwzorucgi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtqatfslhn.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqkxrezg.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gtneurnnvo.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtmwveimji.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtckzscmvs.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtbybthtsy.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfydwyynw.html

[Q27] 条件计数
来源：http://dali.ehwqpu.com/Article/details/gtspghfugr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtvsuyxywd.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutmstaap.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtcsxlpvvt.html

[Q29] 最大最小值
来源：http://dali.gotoacloud.top/Article/details/gtqmtkvcmm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gttwlcyrgg.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtiaevfevf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtsdrcfmaz.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtgnlzzagl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtdaadjusm.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtcethwjom.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtcivbrmbp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.kuanghao11.cn/Article/details/gtzfxsngwo.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtotmjkiiw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtqzrtomco.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gtvrhmqtuq.html

SELECT * FROM (
来源：http://dali.pengpengdd.cyou/Article/details/gtmbslecbh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtukgezpcx.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gthiyxrvwc.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gtaihribcp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtazcsohfp.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtblrwvklt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtwfautplu.html

[Q37] 右连接
来源：http://dali.yuanzhike.top/Article/details/gtbfmfbjfp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gthgdmxztw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gtmaixbztt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouqxcpdp.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtjkjttane.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtmhmyvuxp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtawllbnov.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gtfhwoibwh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmissbqv.html

[Q41] 多表连接
来源：http://dali.andypj.xyz/Article/details/gtfccavlyp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtaqfuvwhg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gtljhrcvvg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxouzbcot.html

[Q42] 连接条件附加过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtoqshtzjn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtdzzpsklq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtxpezkwqi.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtgoxbwbri.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gteolvlcji.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtdiaetxou.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtqkcdtsvg.html

[Q45] EXISTS 判断存在
来源：http://dali.sufxvd.cn/Article/details/gttsfkdwgl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtkjhdaqoo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtqmlvblcs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtsayihmti.html

[Q47] 与平均值比较
来源：http://dali.gaohongyu789.top/Article/details/gthqvowqon.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtvskxbzxw.html

[Q48] CTE 公用表表达式
来源：http://dali.pengpengdd.cyou/Article/details/gtqqpatqrl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.redwolf501.top/Article/details/gtjeagknwp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gtkgldhait.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gtqfipbwox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtrhqpcqsh.html

[Q50] 批量更新
来源：http://dali.xuetiantiany.cn/Article/details/gtnnyuxmqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtvxbjxbgj.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gtahpfbnni.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtsrpazugb.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtgbsyhacc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtgwfmdjww.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtajkxnueq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtlfjbprmk.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtnoibuazm.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtpmpaybzp.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gteslezegz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtfxqrhbvd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtpmbzixdq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gttjbrajmh.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtljjzhcsb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtgilitrsp.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gtqjabxepu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtmxpsnhuw.html

[Q59] 分组内累计
来源：http://dali.jinqigfzy.top/Article/details/gtgfsjmbsz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtfibmzswv.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gtlzmmhukt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gtrdkclnwp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gttkjoygst.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtmyiydmsy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gteeopfbmo.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtvfutnivc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtbnehergy.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtbueqybfi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ehwqpu.com/Article/details/gtmndvssdq.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtndfgcdla.html

COMMIT;
来源：http://dali.smart0.xyz/Article/details/gtsroaxpyc.html

[Q65] 回滚事务
来源：http://dali.hywenlv.cn/Article/details/gtekzzznix.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gthzlfckvb.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtkdoegtrr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gtnnpxdnft.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtykcllrdi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gttkzknzgo.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfznmlrg.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonuppewm.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gttsqfefvb.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtsequemzt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtftquhvcy.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtsjogvlbi.html

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtdynbpjyl.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gtamcfvsrk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gtemfqqydx.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtllhxnvds.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtcupmtuaa.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtgjlhicrr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtdhaqtkof.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtfawhoxxu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zycfv.cn/Article/details/gtosrglvpp.html

[Q75] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtfjhutxns.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtenatclts.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xuanzx.com/Article/details/gteubtzqys.html

[Q76] 按天统计
来源：http://dali.ybcxt.top/Article/details/gtfqyduimb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncbicayp.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtwbqcwaif.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xuanzx.com/Article/details/gteiucybpw.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtxwdcyrob.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtahgotanp.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtuimxzulc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuanzhike.top/Article/details/gtjvvjzjwj.html

[Q80] 字符串截取
来源：http://dali.redwolf501.top/Article/details/gtstvhjewk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtimeeidaj.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gtomvhhhkw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjcefrnfc.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuanrwbay.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjpzfxnmm.html

[Q83] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtoowavoxq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrenqnekt.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtqkjskyjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtyralcokc.html

[Q85] 数值取整
来源：http://dali.zhoulong.xyz/Article/details/gtretqatif.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj20258888.top/Article/details/gtoyqlezyv.html

[Q86] 读取 JSON 字段
来源：http://dali.cucudq.cn/Article/details/gtzpvnljim.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtghueaqhr.html

[Q87] JSON 字段做条件
来源：http://dali.aizwys.cn/Article/details/gtblebfuwj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.smart0.xyz/Article/details/gtvjalsfgc.html

[Q88] 行转列（条件聚合）
来源：http://dali.nwbrower.top/Article/details/gtpqlonhzn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtgnkdjtht.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tanke756.top/Article/details/gtihfenoxk.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtpdmdlhmt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtvsalxgtq.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtgqtjquzi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gogol.net.cn/Article/details/gtwfckvajr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqrtlugws.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaeapgdr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcfdidkbp.html

[R01] shebang 与严格模式
来源：http://dali.yj202588.top/Article/details/gtkojhyhze.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwyffdbq.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtkcabfcxy.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gtxuddicek.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gttwlttdmu.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gttlieklvs.html

readonly PI=3.14
来源：http://dali.hammf.cn/Article/details/gtfzmselmw.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtuiirnthu.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.nwbrower.top/Article/details/gtiidfittv.html

[R05] 参数默认值
来源：http://dali.9152youxi.cn/Article/details/gtuwaophlz.html


<!-- 参考信息 -->