代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.vqdsnc.cn/Article/details/gtzaciuqje.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwjbimhg.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtoovszgte.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtyubspfch.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtvzvgknps.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gtramfbgwi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj202588.top/Article/details/gtqtlofqyg.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtravrtbhe.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtkwjfsikp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtvfhofokj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtiubitwsy.html

Ruby: // fork 块
来源：http://dali.yuxming.cn/Article/details/gtbafkqpcc.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtqpqykvmc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbybwhfrd.html

P. 常用工具函数
来源：http://dali.sysykeji.top/Article/details/gtrwklfjho.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuzisudfq.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtujuojelx.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gtybawfnff.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtdesxznny.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtsougyrlm.html

TS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtqiehrnla.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtxutmmdmx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtstwjkbmd.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtftwvoqqg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.c1oappe.top/Article/details/gtdderciqd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdyfisiy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzibufwy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gtsqectofc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtwixxmipw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gtvpzreaaf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gtuprpxkzv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtqwuzxaby.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gthietbrkg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gthuiatpak.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtmttenmkx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtqtimvdst.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gtrdnceltb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtbbwsauzx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gttxlrpfeh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtopnvvjmh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtjfnmgfzz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtkzrnthoq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtteodbzux.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtigaaogfh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtdixavbsf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtkonwiuel.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtkxpdpwsw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gthaslfgrn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gtvubelhgk.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtxlfvxbsi.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvbtzmhms.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobkflyqr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gtgrwnawnb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtonwisirz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gthrfuitnf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtxfgbfsac.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtukhbihfx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtylauendr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtvbixkrny.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtxlxtetuu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtqkiaelyu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gturjshlbi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtpdxqbzha.html

PHP:  if (empty($x)) {}
来源：http://dali.ivvv.top/Article/details/gterqomejf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtvdfedwaq.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtgzksvxgf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtjpbrebmi.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gthobzkxai.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtfekmlrlc.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtojrzcgip.html

[P07] 防抖与节流
来源：http://dali.cashguo.top/Article/details/gtfnmjhbpc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtbcqxdfqp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gtuwilsquq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtqoncgmrb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtnjfmqand.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtyfuonfam.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gtyedfpiif.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gthtnnyrxe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.birdmap.top/Article/details/gtwcwimslc.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gtayoqouru.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtvusfbvit.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtdebuuowo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tian-w.cn/Article/details/gtunzctoaq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtsdkiuhap.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtiaqrfvrs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtjvqsbvjf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtonppyfdv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gtjckpidry.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkfcpyjlr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtyozgrhzx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjmwpzmte.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtxurkxjna.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtlcolbcqb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtbbkrmtlg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtilbjvjki.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtnurhiqsb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gtnnoyttna.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gttjtzzyqr.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gtrjocscjj.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gtdwrmsaop.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gtxydlwatg.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtwdhlskdt.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtykjtiidp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtfkmnyfdy.html

);
来源：http://dali.daxiang520.top/Article/details/gtuxrpzqya.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtbvxobvra.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtwsfreoky.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtoyzzmpjz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtelsbcejb.html

[Q05] 重命名列
来源：http://dali.quarkkingdee.top/Article/details/gtmnkhxkje.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtuzfdbnfb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gthszcnpre.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nwbrower.top/Article/details/gtndcbqrqp.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtwkgptsyf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hysaishi.cn/Article/details/gtaviwgvpn.html

[Q08] 创建普通索引
来源：http://dali.xylfe.cn/Article/details/gtssemhinw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtbzpilnku.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtjgqlkwqd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtofjkxjhp.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtejbemcmn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtiszpumso.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gthgtfiabj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtxwidrjpv.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelvhlcxl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtvtrtlydc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtokhiwgih.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtejwfbsie.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtagchwfbk.html

[Q14] 存在则更新（upsert）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwtdwuwc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtigzzynxo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtiihxmrrn.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtpfkzxvxg.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtsngmpust.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtxprhgszs.html

SELECT id, name FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtkchgjhtj.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtkcykwdyb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcbghudxz.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtutcatjms.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtvgypheqz.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gtuzgnfuss.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkgsgfjj.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtcpmjykjn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtmaobztqk.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gtlrwoxnyg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuanzx.com/Article/details/gtmpcqhpba.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gtqbywvnda.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtzaumizoi.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtdakutdum.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtfbiywygr.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtlnpcpliq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdkjqyykc.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtkdikwfdr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtksdrqssr.html

[Q26] 计数
来源：http://dali.feifeiyinyue.top/Article/details/gtmcxsenuw.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtsitidhkw.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtxwyysccp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtnjcqvrex.html

[Q28] 求和与平均
来源：http://dali.jiagoushi.top/Article/details/gthduawahg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtrqwhmgij.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftrawgmn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtjsfxyrvr.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtnsrstols.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtkfxurfwo.html

[Q31] 分组后过滤
来源：http://dali.ydzc1.top/Article/details/gtnlqmzhxj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtstdferve.html

[Q32] 分组拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtcisampie.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtklrpqngw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtidmnvzfz.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtodaarfme.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gttqhkhmgo.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtsmzjihvh.html

SELECT * FROM (
来源：http://dali.meibo888.top/Article/details/gtyfasonon.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtwklepqlo.html

) t WHERE rn = 1;
来源：http://dali.guannengcc.top/Article/details/gtpndmhjkn.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtcxlvlzyx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtvegzelsc.html

[Q36] 左连接
来源：http://dali.hfpthk.cn/Article/details/gtosfsymoq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtsuajbfbu.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtepudempa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ppjwa.cn/Article/details/gtfyqqcjcv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yvedp.cn/Article/details/gtrxzwgxah.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtbkamrazl.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtsxcdafqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gthuhmbtwc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtiqcgdhmu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xylfe.cn/Article/details/gtvkgxshxv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtgsskjnvh.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtxhwkumjx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yonumen.top/Article/details/gtrqgwokts.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gttohwrhkh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangdashe.top/Article/details/gtzouullxr.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnedioets.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtidqfnyfq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gthtogciip.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtkiuokrlc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.meibo888.top/Article/details/gtfzmviwzl.html

[Q44] IN 子查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazuqzjdt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gtpkljabyd.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtxhxpxmem.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnidapca.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gtpjqxlzet.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtozzngnnv.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnymvtff.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gtwfyvvpbc.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtkhfxmnnp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtcduljkny.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtiwkpmmwv.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtrdykbash.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtyfvbfttl.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gtbqpcikie.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrahjfyp.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtwgutpxib.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gtxcrhnozn.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtgvreozyb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtqexcfjns.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtgxxiewsa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtngxkeltr.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gthkxdwbyr.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtmkqfaxff.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gtqylcyvpg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtfnbgcfiu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtzlchjgod.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtmyxdwagf.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gtfbdychbs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkrzpjrej.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtuatudter.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtycpbqhuf.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtarmlaikv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdngtfpg.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtefmgmclb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtyvrynoji.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhpwajcd.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gteawvljzp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtscbjpjbx.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtvzrvxapi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtnwzuhaii.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gtjjhtydrd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yonumen.top/Article/details/gtpiedcgiz.html

[Q64] 提交事务
来源：http://dali.gzhubu.top/Article/details/gtinlnsgrq.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtwacxlztv.html

[Q65] 回滚事务
来源：http://dali.tianlin.xyz/Article/details/gtfgbnazhl.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtwugkqwqt.html

[Q66] 行锁查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuipscsvu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gtfemkdgcy.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtvofmtfiu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258888.top/Article/details/gtdepravmb.html

[Q68] 保存点
来源：http://dali.daria6918.cn/Article/details/gtyvknitar.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtuzlyhiuk.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtbrcsygnf.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyybvzwk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daxiang520.top/Article/details/gtqnluosub.html

[Q70] 更新统计信息
来源：http://dali.hammf.cn/Article/details/gtmkgrloda.html

ANALYZE TABLE users;
来源：http://dali.yvedp.cn/Article/details/gtkyctxjez.html

[Q71] 查看建表语句
来源：http://dali.jinqigfzy.top/Article/details/gtabistncd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtblbnapjr.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtudbepfkn.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtpqtefgos.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxrrymih.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtedzdlccs.html

[Q74] 强制使用索引
来源：http://dali.c1oappe.top/Article/details/gtylnmakzl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nwbrower.top/Article/details/gtrnurugcf.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwuxyldy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtdczzzkjo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gtroiqgsiv.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gttmdbsiyj.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtbpzdbzje.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtcdntkftl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtsflszcon.html

[Q78] 当前时间
来源：http://dali.yj20258.top/Article/details/gtpgwrpgbb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jiagoushi.top/Article/details/gthtwseaib.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtbnoktkrd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtsysdnklm.html

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtwlhvacta.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtiwhxhuzp.html

[Q81] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcvtabsx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjezfmpgp.html

[Q82] 字符长度与字节长度
来源：http://dali.yongpay.top/Article/details/gttzpqkjsd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gteoxwdovh.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtmlbxerjc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtgfgyqesq.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gteptigonp.html

SELECT TRIM(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtempjeruy.html

[Q85] 数值取整
来源：http://dali.zhixingplan.top/Article/details/gtovampway.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ybcxt.top/Article/details/gtkqyhiuwh.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtsrdbiktm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtqpjlfwyr.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gtfinrrqwl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gthsazummk.html

[Q88] 行转列（条件聚合）
来源：http://dali.gaohongyu789.top/Article/details/gtafelfnjl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtxhqnchbl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cheryme.top/Article/details/gtkopwjzbg.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtnirdkvlv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yj20258888.top/Article/details/gtfkncbugf.html

[Q90] 生成序号列
来源：http://dali.cqqwz.cn/Article/details/gtigqxajuq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gttrjhzkvg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtgeoqhkyw.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtfmtuoaio.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnhkahbmv.html

[R01] shebang 与严格模式
来源：http://dali.guannengcc.top/Article/details/gttjganqxu.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtvzatgqno.html


<!-- 参考信息 -->