代发 wailian999

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtvdjzxyld.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtsoihdiui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtrwczmniw.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtqkhwnlws.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gteksydzqd.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtrshnbjio.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtjaouwqol.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnoegkxvl.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtusoomuzf.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtwjsijtlz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtagwfmkla.html

JS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtmixavaao.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbvuqvhk.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtbravexvt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daria6918.cn/Article/details/gtdwjjnbqq.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtadyjpovc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtlakvpqxv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtncdqtauu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtqqsnlvqg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtgsywbnzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmajhidh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gthliphupp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtabrloydo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtfqlqxtys.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdzejyil.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtvohwxrhe.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gtztmyzrkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtfzczxxkm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtwajfecuf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gttljsbqho.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtvgfxhwnd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gthtshtjzk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtvhjvpfgn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gtjfiuwmmf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtvleebias.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gtjgvkdgyn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gtoqsocndm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtyhvtuuls.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtkhalmgbi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtlykuakvw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtxjjfnglh.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gtjrnmwojk.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtjafkbwie.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalxiglnq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gttbtsdkcb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtzgeerhec.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtnctjbvdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtboyeksjx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblryimgm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtdhvyrrhk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtlcbjwdtl.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gtkmpkqivr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gtnkegycdz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhoulong.xyz/Article/details/gtacealytq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yanxiufei.cn/Article/details/gtuvzkdpvb.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtattgxvma.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtobwqpcik.html

TS:   if (x == null) {}
来源：http://dali.guannengcc.top/Article/details/gtgrrycapx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtkyaggozc.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtdqmsxmxc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gogol.net.cn/Article/details/gttfovfagl.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtvrnhllui.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtrklgtjqg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtiupvwvvw.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gtmesisrdf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxvlchei.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtnisnompm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtsvriqmjv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtbklthpxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gthwdgtwod.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gtsldmusrz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gtwcqzsiwo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqlfkxud.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtmzhhnrwe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtsyqzfrtn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtfxlzeqoa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daxiang520.top/Article/details/gtfscrzlnl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gtktcgxvpp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtbcjizkhg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtpednbsuo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtkmhlxtgf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtmhtnspcv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtepazpavv.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtkrtubvha.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtxbsgnfzx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtbmfncxmp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtieummlgx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtdcbimqnz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtxxfwpyrr.html

);
来源：http://dali.zhengqikj.top/Article/details/gtdyjbdoba.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtukjbvbzj.html

CREATE TABLE orders (
来源：http://dali.snrcjt.cn/Article/details/gtjrvnqxvq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtfrnzipkj.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtrbkaowkp.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtmylmjwla.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtivydfmaf.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtepjigjor.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gtxjwofcid.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gtazugeygq.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtyzkwuoqu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtyfsuccus.html

[Q05] 重命名列
来源：http://dali.sufxvd.cn/Article/details/gtbwafuzua.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtvolrngmt.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gtazltbhwz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtklbexsnn.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufmgatha.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtzkhvdnkn.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtscejscee.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtksdplgsu.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuykvsie.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gtnoawbpnv.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtvhuyjwdl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fengsongda.top/Article/details/gtopdwcawx.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gtjwdunkki.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtjwgbwcut.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtmjorzjiy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj20258888.top/Article/details/gtrzwesska.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtygwnwlnd.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtodyschgu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtioozlfyb.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtoremailn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.feifeiyinyue.top/Article/details/gtmqvgjvta.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gtbwubnvxh.html

[Q15] 查询全部
来源：http://dali.hywenlv.cn/Article/details/gtfsubhmrx.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghzfiddx.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwxxfldn.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtxjiqftfa.html

[Q17] 条件查询
来源：http://dali.kuanghao11.cn/Article/details/gtxllbmbru.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gthyodjsxm.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtszxkgeqj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpbhdfuj.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gtndckoxgr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtumpevakp.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtigtcjnpp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtmgbkhuns.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtjglexbfj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtsijsxkkb.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtizkggtzi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gthqptmhml.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtpuhwuqun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtzxxrjljf.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtjymrgwsf.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtdmlqpoau.html

[Q25] 只取前 N 条
来源：http://dali.nanxuanxn.top/Article/details/gttvuwqovv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtedvbnstu.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtcgqkakyz.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gthrnygkxu.html

[Q27] 条件计数
来源：http://dali.nanxuanxn.top/Article/details/gtvtwtegxk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtcysopymd.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyikhopa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtjnnxbhum.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gteliurskb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtmixumkot.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gtpwjopwca.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gtqclhksld.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdmhngyi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtyquukcbf.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtbncajbts.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtppbkzxtq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtkoxeirak.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtpvoixtlo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gtbtabybgk.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtxceprlmw.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtftdantwb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gtcdytvemg.html

) t WHERE rn = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtzubixliw.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtzmqcjzep.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtvhrimmgr.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gtomgzieky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtllzhjfto.html

[Q37] 右连接
来源：http://dali.hnqzz.top/Article/details/gtltvxgvnq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhdtemuj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtwdutjtfv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtodkuenor.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtdlwgefki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gthupiwxxs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yanxiufei.cn/Article/details/gthqbbwfkt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtxpqbtkqf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdjshjrn.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gttgwhysly.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gaohongyu789.top/Article/details/gtcxekpjka.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtoreldeyb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtqeujdeke.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtfwsysfqu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gtlncdpmwv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ehwqpu.com/Article/details/gteggcfhci.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtegwrhpjo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guannengcc.top/Article/details/gterevhwuk.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuagophot.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtoutrkjwp.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtqlfesvua.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtnxxzawsp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtqsynhooo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtridusruf.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtymbumuvg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtoqykggwm.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtslagwhmi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gtczwjkbit.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtcuseyxle.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtrhyjyoct.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtjmiixmes.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gtuzoyyair.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtbkttxxkr.html

[Q51] 用子查询更新
来源：http://dali.sufxvd.cn/Article/details/gtilkbkqkp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtycsrghxn.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gtfxfmkvoc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gterkvbxhm.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtymrldtiq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtzhwmizst.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtqegkouha.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gtubatokpt.html

[Q55] 排名（并列占位）
来源：http://dali.shangyingyoupin.top/Article/details/gteluaeshv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtmkyqufxp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gticjnwpph.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gtopdqlxhl.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtddzfzpbx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhslzhif.html

[Q58] 累计求和
来源：http://dali.jinqigfzy.top/Article/details/gtuuifdibc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtblqiszyy.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtehiojkgb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtdltprieg.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtbqtwueex.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtqseimpzx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtjxavxvdm.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gtbehypwwf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtawddpmtt.html

[Q62] 分组占比
来源：http://dali.dianchejie.cn/Article/details/gthfexhynd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtyxpihdaf.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtubqusbgc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gtfyjoltck.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gttvrinipd.html

COMMIT;
来源：http://dali.hywenlv.cn/Article/details/gtyepheqim.html

[Q65] 回滚事务
来源：http://dali.sufxvd.cn/Article/details/gtvgcnjdnd.html

ROLLBACK;
来源：http://dali.zhoulong.xyz/Article/details/gtfersodtf.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtpzuxpixn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtlrnwbxyh.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtilkwdfyo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtqcxaqixw.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtwarnpygn.html

SAVEPOINT sp1;
来源：http://dali.cqqwz.cn/Article/details/gtogtbmrjj.html

ROLLBACK TO sp1;
来源：http://dali.jinqigufen.top/Article/details/gtqmiagkzz.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtysygqckt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258888.top/Article/details/gtddqxhgqa.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtxjsmqekn.html

ANALYZE TABLE users;
来源：http://dali.tianlin.xyz/Article/details/gthhnhmsib.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrzrsnvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.andypj.xyz/Article/details/gtyeftawsy.html

[Q72] 查看索引
来源：http://dali.yonumen.top/Article/details/gtnlpyduvi.html

SHOW INDEX FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtzsvfqbmi.html

[Q73] 查看表状态
来源：http://dali.ehwqpu.com/Article/details/gtkjbcszsr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yongpay.top/Article/details/gtuwirgxmb.html

[Q74] 强制使用索引
来源：http://dali.hammf.cn/Article/details/gtaebxdljj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtgukfsmpd.html

[Q75] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtfjzluotb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtmflgvzye.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtydstrxin.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtujuequcx.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.iojbl.cn/Article/details/gtzroxixnk.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtbzxthbxf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtvhjatiez.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtfuqqeohu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gtfxlxfycp.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gtqqtumyqr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.gaohongyu789.top/Article/details/gtacluhynp.html

[Q80] 字符串截取
来源：http://dali.yuxming.cn/Article/details/gtcrycknck.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtiximrsqc.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtmlvlzqsw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtqhxffjht.html

[Q82] 字符长度与字节长度
来源：http://dali.bjfxy.top/Article/details/gthswdhocy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrpgfjqcn.html

[Q83] 大小写转换
来源：http://dali.haohaochexian.top/Article/details/gtjrfdaaci.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtkbanzxwo.html

[Q84] 去除首尾空格
来源：http://dali.chenzaomai.com/Article/details/gtyvtznybk.html

SELECT TRIM(name) FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtpkcrfcrp.html

[Q85] 数值取整
来源：http://dali.snrcjt.cn/Article/details/gtipnirfea.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtxmdbeoba.html

[Q86] 读取 JSON 字段
来源：http://dali.gzhubu.top/Article/details/gtkujtiups.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtibizfksi.html

[Q87] JSON 字段做条件
来源：http://dali.shangyingyoupin.top/Article/details/gtocmrmija.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.316326.xyz/Article/details/gtyrjaromj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gtqszujxhd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtukpdncau.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yvedp.cn/Article/details/gtgwfravxm.html

[Q89] 判断表是否存在
来源：http://dali.zycfv.cn/Article/details/gthwzfjdya.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cqqwz.cn/Article/details/gtaubcnlcl.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gtfzuivyoj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtyyzabtkb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgjsfnnay.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtpbvoysma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnukvmcaw.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtnxnwafig.html

#!/usr/bin/env bash
来源：http://dali.daxiang520.top/Article/details/gtmpzmblfn.html

set -euo pipefail
来源：http://dali.ydzc1.top/Article/details/gtgbxdnjce.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtxuosvxtb.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtkzvapvii.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtxqguapaf.html

readonly PI=3.14
来源：http://dali.zycfv.cn/Article/details/gtrrijejty.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtvlyagisz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.wangdashe.top/Article/details/gtbszdmsgv.html

[R05] 参数默认值
来源：http://dali.fzhhl.top/Article/details/gtxdvafzmx.html


<!-- 参考信息 -->