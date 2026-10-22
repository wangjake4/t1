代发 wailian999

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtgpgpuqgi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtzuzqgszv.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtwabrmmxj.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtkdnenqkx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtfgbfnnou.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gttxzkqgiv.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtazsgrrgi.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtjkihkqei.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtfspgiyor.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtcemvotnr.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtryfydumr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtnjalhnyj.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtzscjrihj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jyoumei.cn/Article/details/gtdcinzaiz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtrfpalxdm.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtnhlxhhpj.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtlkmhvblg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gttuhsmwcr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gtpfmjuvlt.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtchzdyqco.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtqjoqkeeh.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbkqpskam.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtecyiiyrd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgkvzxvks.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtjlnqeocd.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gtxgabsxwq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtvmvpritx.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtqcdljwvz.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtyxoytrdp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtcifcoxli.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtiktecuje.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtthxpfvcz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzozdfqra.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yongpay.top/Article/details/gtkiqvmoqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtuqalqsiw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtbyjvthni.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtjrrqbevj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gttcrxsgao.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtjraspmdf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtxjosyuaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtiihgclwe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gttgozjtsm.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtwajtdqnd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtcyrqbwgi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.havefunace.top/Article/details/gtnqgborqt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtkoskykif.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtbyzalnwz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtbofmdbva.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gtvghqclko.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gtuftdshsk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gtdocmgswa.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtehngyovk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gtyrgvjiuj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtzinxzyjh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtnxwpkphr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtygtcercv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmwbwksg.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtjjtxahze.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtuvyjfdqs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtfptpeyif.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtwykqvank.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ehwqpu.com/Article/details/gtmpzfsllw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hammf.cn/Article/details/gtbhyakeyt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtldstepyd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtdlrzpsxg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtshileycw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtblqsecgs.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpadsikth.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtkknjkcmh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtgmqujukk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtiivrrard.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gthfwioshv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gtpedmuwia.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtjjtcsawc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtalkhchsy.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gttbayeuar.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtnpbonesv.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtenkgwyjq.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvhzlhwv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtlhbqdqya.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtuvqociqn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtmizkzgxd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtertvtmub.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndfeygmt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtocjjzlev.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtgioeblvw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtlpqlgvep.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtvaixqawk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtniuywldx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtkmrnptsq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gtnfzrdtkg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sufxvd.cn/Article/details/gtdfyeppfn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtnyubkngv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtuhhughvi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtuvhtaasi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gtglbxuvlu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevyjshdd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtziebwrpl.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtaqvytqhz.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtrdgnufwz.html

CREATE TABLE users (
来源：http://dali.xinyue.icu/Article/details/gtkilboyex.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtispitlnd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gthrhubymw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtosduoifp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtjqitrvim.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtuvuftrks.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gtndwmvums.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtavtokxaf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtgxmowwky.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyifxfnj.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtjmzeyjdy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtqhesbktr.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtpvvvthra.html

[Q03] 增加列
来源：http://dali.ehwqpu.com/Article/details/gtxmspqdlu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ivvv.top/Article/details/gtdfisdtil.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoalctla.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtqlzlclxv.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtphefvkpp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gtgdfnbscc.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtjoupslpw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtifaxoyzy.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtyqvuwabd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gteuhvypvs.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtlpkjmruu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gtflxqfoob.html

[Q09] 创建唯一索引
来源：http://dali.c1oappe.top/Article/details/gtnezemhmj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtbiljguut.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtggjmmsgw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtsfacxfvy.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtafnxifbu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtuhopckme.html

[Q12] 插入后取自增 ID
来源：http://dali.iojbl.cn/Article/details/gtaetpdmze.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtkxkxirya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gtrxswqkzv.html

[Q13] 忽略重复插入
来源：http://dali.shangyingyoupin.top/Article/details/gtyuknnbey.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtxagwckvm.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gtsffbwavj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gtrsggbjhh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfjsutye.html

[Q15] 查询全部
来源：http://dali.jlsjyb.cn/Article/details/gtrsghtirk.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtjfhmrgnk.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gtvqncqjxy.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtigosysqq.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtkerkpolz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gtmtjloenh.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtaybuuwfh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtalllmuvj.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gthdkbswof.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtmaibkwvo.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gtagcodwqe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gtrdgebgza.html

[Q21] 空值判断
来源：http://dali.jlsjyb.cn/Article/details/gtwvccxmte.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinqigufen.top/Article/details/gtkomupbjc.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtrmascoxv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtvkvchjym.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtjohgvbff.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gtokdnigoq.html

[Q24] 去重
来源：http://dali.ehwqpu.com/Article/details/gttcbnnhoc.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqrahzivi.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtizewlger.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.andypj.xyz/Article/details/gtutfshqip.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtagnvgulv.html

SELECT COUNT(*) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtstvhrnml.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtsougdgsa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtyzyynbdv.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtzfyhqjis.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtbebgwrge.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtxbzszrby.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtzcnvvlif.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhmhqqvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtbmwghmap.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtddfuvzzn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtsdlpumxz.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gttjaovvok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtbsatlwig.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtndsfaxaj.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppxggaus.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hammf.cn/Article/details/gtnqynnddc.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtgkjcysrf.html

SELECT * FROM (
来源：http://dali.aibaodan.cn/Article/details/gtywbqcrhz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtnhkroagd.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gtssndxvpp.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtxqjelhma.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtaycfkoet.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbumtwdpd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtnvhuayey.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtazmorolo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtjxpvfjpg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ivvv.top/Article/details/gtuuyaneiv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuxming.cn/Article/details/gtkdxlxtpc.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtqaexepdp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtagvdfude.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258.top/Article/details/gtegvohwtu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yongpay.top/Article/details/gtbaehyyrv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258.top/Article/details/gtcstozpha.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvepjpefw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dianchejie.cn/Article/details/gtrlnvrwuk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwbmyggy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtspgomxjj.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtszwklrfl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtmenufyue.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtemnanxcl.html

[Q43] 标量子查询
来源：http://dali.jinqigufen.top/Article/details/gtmayoezmu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dianchejie.cn/Article/details/gtwcceomct.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gtxbaiwjtj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtcwqqbwlt.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtpeiredxz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtufvypxjr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sxryk.cn/Article/details/gtbfxietew.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtnzpfeiyi.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gtueeaboep.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gthyixslfq.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gttxbbtpdc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nanxuanxn.top/Article/details/gtfdgwktqq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gtmmllqyfi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gtokroqzhf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yvedp.cn/Article/details/gtovdpstso.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtlwdlcbog.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtthckejmz.html

[Q51] 用子查询更新
来源：http://dali.hongshengwenyu.top/Article/details/gtbfpozauk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtjpyldpdo.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtdhhmsufm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtfoalnttp.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtsloogglm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtllqarsap.html

[Q54] 清空表
来源：http://dali.zhixingplan.top/Article/details/gtfyifxxks.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gtmomukuju.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtnyonbwwz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtorhdwssi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gticjntnml.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtkpjnlaat.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gtpshbbbrw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtosudxevn.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtdmvycjsq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtcnyppqhz.html

[Q59] 分组内累计
来源：http://dali.shzxlz.cn/Article/details/gtkaegsmlr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtaikzzfmy.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtsqldreol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hywenlv.cn/Article/details/gtdnmknovz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdhuuqqqu.html

[Q61] 移动平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzofslca.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoomgftzx.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtwfdjddvz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtairvnloz.html

[Q63] 开启事务
来源：http://dali.birdmap.top/Article/details/gtwufwtimj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtqsdqajzl.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtmlatikcv.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtyqkjivru.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gtpkxomwlz.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtfeeubdsa.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtljylgzti.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtimwzxqgc.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtsyylvlfr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtdgpyedml.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtvwxxoenb.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gtuezkeecz.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtaqvvxwpm.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtrpvdhxur.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtqkgdbdop.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gtfzdhpkag.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtxzkevidl.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtihbbhsyl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gtinlnziql.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtjfadhxmp.html

SHOW INDEX FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtqrbikcfb.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gtevunphhw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtuqmrnboy.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gthhbgokou.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dianchejie.cn/Article/details/gtryoqhkbo.html

[Q75] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtyhuiglfr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtnniksdwh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gtildtaaqy.html

[Q76] 按天统计
来源：http://dali.hammf.cn/Article/details/gtbsajlbgh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtdnwwnhoq.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtwrxzbvgb.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtdtjbgolt.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtwypipouh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtabvbrcme.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtfpdhoyxb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gtrdpddysr.html

[Q80] 字符串截取
来源：http://dali.meibo888.top/Article/details/gtdtequjtf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtqdpmbbja.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtmrgrwemv.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszqtroxq.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gtjclyuzmu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtyhuxmich.html

[Q83] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtoswmqrhn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtstfnavid.html

[Q84] 去除首尾空格
来源：http://dali.yvedp.cn/Article/details/gtxikgayxi.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtddqvdgbd.html

[Q85] 数值取整
来源：http://dali.dianchejie.cn/Article/details/gtcgwagtkx.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvnzzlfc.html

[Q86] 读取 JSON 字段
来源：http://dali.yuxming.cn/Article/details/gthhxocozd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ybcxt.top/Article/details/gteuggttle.html

[Q87] JSON 字段做条件
来源：http://dali.cdnleiting.top/Article/details/gtdixqyqlj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtlnngccef.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtxewrmkkv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hfpthk.cn/Article/details/gtaetlnogw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtpharkotu.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhejpkzl.html


<!-- 参考信息 -->