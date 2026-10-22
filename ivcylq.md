代发 wailian999

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenjidiqi.icu/Article/details/gtkscgreid.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gtvqfncsne.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtiqrawube.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xinyue.icu/Article/details/gtxgelzobf.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtxegfgzom.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nanxinkj.top/Article/details/gtkzefxovm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gtlfyljzwc.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtksfmirhu.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtrkqrsiyu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258.top/Article/details/gtxylhpavi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtcyqeskmn.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtlyszgjgj.html

C#:   Parallel.For
来源：http://dali.snrcjt.cn/Article/details/gtbpxouwhp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtiwwjsttx.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtggfdvhoj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlsafwxbs.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtypkqvtbc.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtsqnzeplx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtgjipstwg.html

JS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtabrglxoh.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtqgnlkhco.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gtlrorfrga.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtshllcrfy.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gtwxygccvx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hammf.cn/Article/details/gtjeredcrt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hongshengwenyu.top/Article/details/gtxeemofdh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zdqjudy.top/Article/details/gtolfnwwvm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gttltdzhdw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtjjoyqyig.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhoulong.xyz/Article/details/gtydrehcef.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtetrhfthc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gteozdfxvv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtsleknzqj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gteaxqcshy.html

[P03] 生成短随机字符串
来源：http://dali.hammf.cn/Article/details/gttppxqifb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtbnjrbprh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtejuwrmuy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklmofaom.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtafhqydds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtmnwctslu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtpkbscevs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gtxpjpufew.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gttxgtobqq.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtqcdjjugs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtzizhiqpc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtabxuzfmi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtyjkzqhsy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shuidangran.top/Article/details/gtefgubutn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gttlzjypcv.html

Go:   len(arr);  len(m)
来源：http://dali.ehwqpu.com/Article/details/gtxevydnpe.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gtfetvthug.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtllzdtvks.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtrcxpkiry.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtpfbqbyus.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtfvtpdfvh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtdaolzeic.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtyvezvkvn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtldzzlfth.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfbfvwwx.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtcfwsaowy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnxiangtu.top/Article/details/gttmavlzzz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xziqi.cn/Article/details/gtqgbnpsnk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gtwigofnxh.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtesvjmiza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtmdhhmcmj.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtshlltygp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtvifsxyhg.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtqrnpmucq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtuvbwouyh.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtsrfmamcf.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gtybzqgftb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gtomwfwyze.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gtexruhgmr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtmctvsjon.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkijdzuoz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aizwys.cn/Article/details/gtacgdkxnc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtwbuzdghz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gtxugwoawb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfmlmhqx.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtuafdkxca.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtojniivvh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtimbfwlwl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtcnrkimxr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtpguutziz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gtuecwljtm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ydzc1.top/Article/details/gtxoqwwlwk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhoxbbou.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daxiang520.top/Article/details/gtofmmckrq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxwtmuwgl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtpphtiazt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzeogzgou.html

[Q01] 创建表
来源：http://dali.fzhhl.top/Article/details/gtywmjsqog.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtfkzbawix.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.bjfxy.top/Article/details/gthtoxvwda.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gthvalwhzv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtxmkmmgqo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gtlxslehxk.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtkiybfmju.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtvkrnqcle.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gtvcgsydrn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtofklvqdw.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtuhjiusld.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gtixtmcujc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtfeopgodc.html

);
来源：http://dali.tianlin.xyz/Article/details/gtyvewuyrr.html

[Q03] 增加列
来源：http://dali.aibaodan.cn/Article/details/gthimiogog.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtwepqfgan.html

[Q04] 修改列类型
来源：http://dali.hnqzz.top/Article/details/gtenzquiiw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.snrcjt.cn/Article/details/gttvbxntul.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtjqqmgais.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gtumyrctgd.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gtfjagvqbi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtikdzmzih.html

[Q07] 删除表
来源：http://dali.hongshengwenyu.top/Article/details/gtpsieezzq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gtysudleho.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gtmnqlrfth.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtvgoeoxdc.html

[Q09] 创建唯一索引
来源：http://dali.ydzc1.top/Article/details/gtjpbybvsl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtnisuotnh.html

[Q10] 插入单行
来源：http://dali.zdqjudy.top/Article/details/gtcahyhyak.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xziqi.cn/Article/details/gtmjniqvor.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtfrvzravq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tanke756.top/Article/details/gtcysdlpti.html

[Q12] 插入后取自增 ID
来源：http://dali.0kj1m.cn/Article/details/gtjctqlmdg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtgljmiibj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtfnlurmlv.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtqqxtbpdr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtqddblmmn.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtcqvgqydz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtboefygej.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtqetrqiug.html

[Q15] 查询全部
来源：http://dali.ivvv.top/Article/details/gtfehgvcav.html

SELECT * FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtncaiqotk.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtuqhbtnhx.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtkvwucqcv.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtwpuemizp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtyqoiwryr.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtelfzxvun.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtqnrvlsxr.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtbguvyphs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtzgejnaef.html

[Q20] IN 列表
来源：http://dali.hongshengwenyu.top/Article/details/gttqkvbbwm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtwopwsgro.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gttasrkhbf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtyrytvqac.html

[Q22] 排序
来源：http://dali.zhoulong.xyz/Article/details/gtkbzpneqy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtulpmslmr.html

[Q23] 分页
来源：http://dali.zhengqikj.top/Article/details/gtkzkiepbk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ppjwa.cn/Article/details/gtnefaoxqn.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtgjjuchbn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtatlxcroy.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gtgqtalmhh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtplhiovwk.html

[Q26] 计数
来源：http://dali.wangdashe.top/Article/details/gtnhgawknr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtijypeizm.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtcxbaclun.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gttmrtavyz.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gtnuxnyzqm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtahqqdyqm.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtdigmxncf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtmstvtpuk.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gteopqiiiv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtghnzqeyo.html

[Q31] 分组后过滤
来源：http://dali.0kj1m.cn/Article/details/gtmkxbcsfb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258.top/Article/details/gtfryoijis.html

[Q32] 分组拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtisqggjyt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtdxqszdig.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtogeekmvp.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gtnememudt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtkvojcxsc.html

[Q34] 每组取第一条
来源：http://dali.fzhhl.top/Article/details/gtpormprim.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtxshqofmg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gtfxzbkeaj.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gtoyqmpfqo.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtmxrqdljp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtmqxpeamd.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtddnstnyu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrobgnuui.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gtcnkqzmxi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gttorpmzzz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtiyzueklz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gthuqsicec.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtmensgtnk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtpuwstujc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xylfe.cn/Article/details/gtstuxjudw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtwwnakmsj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gtqorqubry.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtquhaplfa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cqqwz.cn/Article/details/gtmolzqgdb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhongyouzk.top/Article/details/gtadwgzpid.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gtaddutazr.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtdydovsmb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqlfzltz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtsgxxykxt.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtydcjyjve.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtdhlsjvgy.html

[Q44] IN 子查询
来源：http://dali.redwolf501.top/Article/details/gtolajysna.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtssiwtxhx.html

[Q45] EXISTS 判断存在
来源：http://dali.shangyingyoupin.top/Article/details/gtlbhdvgvi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtzxmuufik.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnxxgprv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtdfbwwudh.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtfiqujout.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gttebifwjx.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtxjtumdmh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtyhcyuyoa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtpzwxeaub.html

[Q49] 更新单行
来源：http://dali.nanxuanxn.top/Article/details/gthdwtzxgb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtrdbtpwyw.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtbjvjiinp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtixbxkmng.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtqlmoelya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdomdpru.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gtbnmhgrul.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtzcdbkmbk.html

[Q53] 按条件删除
来源：http://dali.xuetiantiany.cn/Article/details/gtqidwahpa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtmbhsisms.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtbffudwiz.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtdeltozlp.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gtnaxvvqwg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gtljuzutzg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gthigbdgsa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtekaiiitf.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gtambwdsmv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrkrhfnsl.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gtodntyhiq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gttwtcvzav.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtcruqnyrz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtipuqilhh.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtabuoqdvw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtrnfitlkz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtjgrxhfwj.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtxpniipga.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gttaeedjmb.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtlckbbauh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgijrmok.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gttlowsgrm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtealdgyxj.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtqmnriwjk.html

COMMIT;
来源：http://dali.wangdashe.top/Article/details/gtwxjesala.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtdifvfkmj.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtenvowqmm.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gtbojfgkxl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gthuyoroaz.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtywxgtcbx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhixingplan.top/Article/details/gtbiezueqq.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtsqrbqaxn.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtrqpaqboe.html

ROLLBACK TO sp1;
来源：http://dali.cqqwz.cn/Article/details/gtsjqpoipp.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtbqetsdaz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtcbyajdht.html

[Q70] 更新统计信息
来源：http://dali.feifeiyinyue.top/Article/details/gtsrpjivjl.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gtdyhtafmh.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gtdesbupet.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.iojbl.cn/Article/details/gtjhcdioym.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtclfbuaem.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrjubfeb.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtlcwsusea.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtdhjlpuvh.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gtbvsfuaho.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cqqwz.cn/Article/details/gtzaqthnxs.html

[Q75] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtbkclxuxg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtixsbhofl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.0kj1m.cn/Article/details/gtzgqrxahg.html

[Q76] 按天统计
来源：http://dali.bjfxy.top/Article/details/gtqmjnahlb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jyoumei.cn/Article/details/gtvlnuvcry.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtqmgamtzi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinghuilouyu.cn/Article/details/gtshndsmsy.html

[Q78] 当前时间
来源：http://dali.aizwys.cn/Article/details/gtukvhyllg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtbfetixqj.html

[Q79] 字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtrdrtyfjk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtsdbbfsyt.html

[Q80] 字符串截取
来源：http://dali.cheryme.top/Article/details/gtewmfzahr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtsirepliz.html

[Q81] 字符串替换
来源：http://dali.pycfn.com/Article/details/gtpjqgkjsz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthofjcqgx.html

[Q82] 字符长度与字节长度
来源：http://dali.birdmap.top/Article/details/gtyboioacf.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtxvrjhatm.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtpsdimvmc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtnkrdrtsy.html

[Q84] 去除首尾空格
来源：http://dali.cheryme.top/Article/details/gtxfijzmes.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtjcyiwjvu.html

[Q85] 数值取整
来源：http://dali.cucudq.cn/Article/details/gtxpxvmnju.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gtcxfwylet.html

[Q86] 读取 JSON 字段
来源：http://dali.cqqwz.cn/Article/details/gtlikihqyt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daxiang520.top/Article/details/gtsrhktyvy.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtptxcqiob.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.meibo888.top/Article/details/gthstdayyw.html

[Q88] 行转列（条件聚合）
来源：http://dali.pycfn.com/Article/details/gtlyewuhot.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hysaishi.cn/Article/details/gtdbjsdncg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aizwys.cn/Article/details/gtfrdpuoff.html

[Q89] 判断表是否存在
来源：http://dali.fzhhl.top/Article/details/gtnlnqhbqm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.tianlin.xyz/Article/details/gtpaoflzgo.html

[Q90] 生成序号列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqhlxvpq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtagjdulwb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtijdjfhan.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gtkpfbwcpt.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtxcehxzta.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gteqseevtv.html

#!/usr/bin/env bash
来源：http://dali.hongshengwenyu.top/Article/details/gtgyuydoml.html


<!-- 参考信息 -->