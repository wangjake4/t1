代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gtomselkul.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtokkkdlhr.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtrrekgqfy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gtbvqdjqfs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtzzfpgrxo.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gttuzjvvia.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtjamapvda.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtzmoumgmb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdietazpw.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtmnghcnvc.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtremcevel.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtendsqspx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtfnyvjbgu.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtueqcilnf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtwwkhfkdn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtgkgplrux.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gtslgvdkhe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gthfbanrha.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtiruqurlv.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtyzvascou.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtesyhjkik.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtrqzdfill.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gtfmixktpj.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gthbflpssx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtqidgfvun.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtswfdybmq.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtxvlmljbc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj20258888.top/Article/details/gtslgespgx.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtmiqbeudt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtphtfovrw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gtvnbehrxa.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjziozjl.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtxhrtsldn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gtrtngrdcd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtmknmuzwa.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gtytcbxhhx.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gtjsagplzg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxzirdzkb.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtzddmhwtj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtyiacolbd.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtgxnxuhyd.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtzqezcfbu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gttokapayk.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtnjrocqjh.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtlfnhzytq.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtkirjzlul.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtdafhjroj.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtgvaltnwg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywciqtdc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtvqkxmyul.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gtaajbhzcj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtiyiaylwe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtzbdeugtn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shangyingyoupin.top/Article/details/gtykjatsnx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtlyzcinzd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gtmwqjonzk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtezybmadm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtwhfsxeht.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtbezwquts.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtjsupcpfn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gtpggatgvb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtuorlpbuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtgqomebam.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.mhx1999.top/Article/details/gtjmtgrtwf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gtbrwkodcc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtvsanfpdy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdqkozlo.html

[P04] 求长度
来源：http://dali.shzxlz.cn/Article/details/gtyihvkduc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtqgicrjvc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtykhlbvek.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtfprcnpeb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxizishs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.c1oappe.top/Article/details/gttfzetfuc.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gtfdptlcav.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gtwyjfbaqb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtsboisnzw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtvlubnpsz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtswelpdsv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtvbnvmkpl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtiwtpxtyp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtfuujimbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtkyhcwyiq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtyvnladye.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gtsrimmiwd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gtghgzahhy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtvgryrbuu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.meibo888.top/Article/details/gtwvoeodvt.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gtybxdmipf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtxkptlgfg.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtjivhdile.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtywgggjjg.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtmahipzev.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraghodst.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gthlisgusm.html

[P07] 防抖与节流
来源：http://dali.zhengqikj.top/Article/details/gtuxhsnrft.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtritdskmd.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gtdpfhifhn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyipxdck.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtuohvvwcz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtisajpima.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtyrfiiumg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgyxqhhe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gthjjsdfvn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gtayldvfxj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtorshkxos.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gtyfsaxedy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtwoccnwqw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gtsvrvqiir.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtzhztufxg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtqdlcnsxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtwejhqgvq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hywenlv.cn/Article/details/gtdjmeyywt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnqxlrfse.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtwzktiqnt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtaqcjqevq.html

[Q01] 创建表
来源：http://dali.yueranfly.top/Article/details/gtazgetgvi.html

CREATE TABLE users (
来源：http://dali.hnqzz.top/Article/details/gtgubukrbl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtxariqtak.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtxuxyoszf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtuftcytiv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtbwqibwsy.html

);
来源：http://dali.ybcxt.top/Article/details/gtixaxmwtx.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtwndgvoge.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtnhajpkze.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtykykfwbv.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtzypetjec.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gtsogjtrgl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtxnssuwlj.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtsejfdrsb.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gtgwrypjxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuanzhike.top/Article/details/gtdnsfpclv.html

[Q04] 修改列类型
来源：http://dali.xziqi.cn/Article/details/gtfxxpufen.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gtdsydsajf.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtvomxiqfy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gthnncxmdg.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtvuehehwx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gthmuncxqq.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtvnkpvsmx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtpdyzewvl.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtatrhivdr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gtqtjwwiwn.html

[Q09] 创建唯一索引
来源：http://dali.feifeiyinyue.top/Article/details/gtddinvteb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtelcnjloy.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtfaedcuoo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoibpabiy.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gtzgredryn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtnaxqxqcf.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gtcsagdzjp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtgbdfnjpp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gtkmowzzqi.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gthbfbgevf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtixociamo.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtwohlkzrd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnwkxpwe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtljfbozqu.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtzmbfbszp.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtjsaisgmt.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gtkmcolsln.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtarlibbaf.html

[Q17] 条件查询
来源：http://dali.c1oappe.top/Article/details/gtaribmkvf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenzaomai.com/Article/details/gtfaryvmcc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtjvcfhfef.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xziqi.cn/Article/details/gtrptznrin.html

[Q19] 范围查询
来源：http://dali.wangdashe.top/Article/details/gthghjjzio.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtfjbvbqbu.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gthvqmqdka.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj202588.top/Article/details/gttsbiokzw.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtawhdpbst.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xinyue.icu/Article/details/gtgpbvgqra.html

[Q22] 排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjxsvilm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gtsqwombzq.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtvyjsqcam.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gtoemcvjbr.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtgzfelllm.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtybyaxxiy.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtrqclxikm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgfzy.top/Article/details/gtogjicill.html

[Q26] 计数
来源：http://dali.cdnleiting.top/Article/details/gtziflvymt.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtyznwczru.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtbtfliwrl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhgjzokw.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtanizhbnj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtsbmfbcbm.html

[Q29] 最大最小值
来源：http://dali.zhoulong.xyz/Article/details/gtcfwqrkjo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtoakpyyhc.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gttgwvssda.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtrrtqiteh.html

[Q31] 分组后过滤
来源：http://dali.sxryk.cn/Article/details/gteahhsooj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtbwygmbeq.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gteyerxfsm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtornkxuln.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtrgmaejpp.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtojlbudul.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zdqjudy.top/Article/details/gtsparcaum.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gtubddbcid.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtvnpckheg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtywvorfod.html

) t WHERE rn = 1;
来源：http://dali.iojbl.cn/Article/details/gtjuhdrhjk.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtxqhwmnhg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtoliyzssm.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgfebwdl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtxubcwolz.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gtxyonzpeg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtkfidarbw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtajnsmhlc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xylfe.cn/Article/details/gtjbneotap.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtbcnrdhyp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gtfmknrwka.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtgyyhdqsh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ydzc1.top/Article/details/gtabnemivs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gthwsfhljh.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gttemtvruh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtlypifntf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtsfbaxkhr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtgsyhjipn.html

[Q42] 连接条件附加过滤
来源：http://dali.cdnleiting.top/Article/details/gtweohfjdc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtquwqnskh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthppuaijo.html

[Q43] 标量子查询
来源：http://dali.smart0.xyz/Article/details/gtxmrhjzqk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nanxinkj.top/Article/details/gtprtfkhjf.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtybsyvnju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtlodhtnml.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtpjsvypqq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtzorbvzst.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gttfzctuyi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmdwydbt.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gtwypkmunb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtpgqbeiqq.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtniddsgiq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtahidbkwg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtbsdnfwha.html

[Q49] 更新单行
来源：http://dali.c1oappe.top/Article/details/gtqzsmctgz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtqnuabjoe.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gtnrkzgzht.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtvixtgkpg.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtqejedyzg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cucudq.cn/Article/details/gthezrfxmz.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtgdfapeuz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtnnypwuja.html

[Q53] 按条件删除
来源：http://dali.xinyue.icu/Article/details/gtibmbfchk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtmprmeide.html

[Q54] 清空表
来源：http://dali.daria6918.cn/Article/details/gtmtacsifo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gtsrwrvoon.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtrqbxfsdw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gtupitbblg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtsrodcazm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmeybjyz.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtdkfilaip.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtgvdtpcaf.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gttkzsjyjm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtgyhlzgmv.html

[Q59] 分组内累计
来源：http://dali.yongpay.top/Article/details/gtwatlkvka.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtvbokfmof.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gttzfaczba.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtzmaamcny.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtdopinhok.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtnciaegoz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gttwmhoxkl.html

[Q62] 分组占比
来源：http://dali.shanyushiyangkeji.top/Article/details/gteplulscy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtfehwekgj.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtmdrbegxw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhengqikj.top/Article/details/gtaoeipsif.html

[Q64] 提交事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbbtwjly.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gtybxhbfgk.html

[Q65] 回滚事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtwryzrklj.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gtuuponfkk.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gtwojjuhkp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gtnjofvlsj.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gttywswrse.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jianghu66.top/Article/details/gtqbxbowet.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtzbotumyg.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtyuawkukl.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gtidjhotod.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnblzyeud.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sufxvd.cn/Article/details/gtkktwozbk.html

[Q70] 更新统计信息
来源：http://dali.tianlin.xyz/Article/details/gtkxhrwkcs.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtgdsglinw.html

[Q71] 查看建表语句
来源：http://dali.ybcxt.top/Article/details/gtltfaklvm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.svipenyu.cn/Article/details/gtervzfzoa.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gtdijzyvvr.html

SHOW INDEX FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtpfrcuzko.html

[Q73] 查看表状态
来源：http://dali.ybcxt.top/Article/details/gtijffklkp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtbvurwaca.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtnedpibig.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtytqdzckr.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gthdgpdtzf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtvmzkckuq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xinyue.icu/Article/details/gtoqwbnkvw.html

[Q76] 按天统计
来源：http://dali.zhixingplan.top/Article/details/gtqzifsouh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.fengsongda.top/Article/details/gtpslstrxp.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtgfifrqtm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtctevpmib.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtfmhxzxoh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zdqjudy.top/Article/details/gtuxvgdmcz.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtdgbjsmrg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sxryk.cn/Article/details/gtiorjpzam.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtjoyzwhfl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtieliavid.html

[Q81] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtzhugnbmx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmonsbajp.html


<!-- 参考信息 -->