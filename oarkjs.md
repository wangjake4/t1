代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtutlljbbs.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gticuyumyz.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtzngioebx.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtdvideari.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtruyjyaox.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtnnxylfpq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtnqdjgxjd.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gthgijmyww.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtzkennxbw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwftbvmc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtyyfliotg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtrektgdcf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtzktrlcol.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gtrtqxftmd.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtijsqamvg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtvckugrnr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovtqlvig.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtwkziyoux.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtmggflwlh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrtkjvha.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtrxerfcgk.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtrrgbtzoc.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gttswhlzfl.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtefircnag.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtstgtzcez.html

JS:   async function f() { await g(); }
来源：http://dali.tanke756.top/Article/details/gtxdqzahxy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtetgmpdmz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtkomfujqn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gthujfnxar.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtjjciouul.html

C#:   async Task F() { await G(); }
来源：http://dali.jianghu66.top/Article/details/gtvsijsxwf.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheebnmiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtbbbokzrh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gtdipoqwdz.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpcbuhra.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtbefhmolu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gttutpwwnh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtqsvhwzil.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtlmrwevai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtylowpzpl.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtxljcfjuo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtwetilcaq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcsaboxv.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtidzkqivw.html

TS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtkdoovmcx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtfjkdxbyz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrajhnsgs.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvigjsewt.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gtjjtgwiyo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmzyqdpgj.html

P. 常用工具函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwyzadcmk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjdbnosry.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtjeiafoel.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gtnesnimzv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj202588.top/Article/details/gtelhyknwz.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gthzybomjs.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtypkfqoxh.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoldtmshl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gttwsfwjpn.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtewenzvzs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtknfvuzbp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtdstxrlwh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtqupymrvv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gtsqadtqfl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtxfaxkbwb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gogol.net.cn/Article/details/gtsdbbponx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtgclhtvqr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gtkrgjwapg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtdjuvvvzr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tianlin.xyz/Article/details/gtgjnoqqac.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gttgoqgnqt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gttxyaeqpd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtysmwzcrd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtdagnmivs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gtzzckgqky.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtewjecfwu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gtqkrnhxrt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gtxshenuln.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gtmwalhelc.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtgeruvgkc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtswrxfihu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtdppxknfs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtcgxgsxaa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtotycavyp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtbzsmrsfu.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtqunqwdhk.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtjaqpkztf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtzcnmzkat.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtbowmnvrr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yangfankeji.com/Article/details/gtldcrpmez.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtyczuinoy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtjuvcaeoh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtrnpvocfa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gtawkoljsw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtdbtmheus.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtugoevuiq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenzaomai.com/Article/details/gtwyuqmfnw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gtczdfgmzb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gtgeeqixfd.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtgjshtgqc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtaxxsplvp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnatxqnkb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsajdleei.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtbwyaomvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gtdtskhggq.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtqhjedxbs.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gtfcwfyyjf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gtwjubbhpy.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gthgusfizt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtpufnubyt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtvxqyffxq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtaimbdqfm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtyuumbqif.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtztmbahcg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtirozbfun.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtacjkwwwa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtrxsdupbe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtvsubicup.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtzzpyswwf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtrlhprcky.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtvwnpruab.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gtgivdpaqr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gtcazidxfb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gthcswwxlb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtywhvbkeb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jlsjyb.cn/Article/details/gtcgnbkqgu.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuhtjfngg.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtzudguspy.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtagiyyiau.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gtnivzwecc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtmrlntzle.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gtccydrbav.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtrtmgtvsh.html

);
来源：http://dali.0kj1m.cn/Article/details/gtkyykkmap.html

[Q02] 创建带外键的表
来源：http://dali.wangdashe.top/Article/details/gtudnzqfsu.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gtzdhuupto.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtwbjygmks.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtcjuujmtk.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtvxlhfoay.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtfyrgkmuw.html

);
来源：http://dali.yonumen.top/Article/details/gthcmqafgp.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gtwmfjykoz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdwxzdeep.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtyktdrnnz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtbfutcfjw.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtiuwcmrue.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtprkhkivd.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtjpjinoon.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gttgqgzurf.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gtxjyokjcs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtitdynyql.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gttbzpavxf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtcbqitual.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtixzqelou.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcokxaxls.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtpfowmkcm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtptfpyidz.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtmdbwhikb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtzhftsaze.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtgdgrpmrd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtvtxnshna.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtcsgzqwcx.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gttvpilfcl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtcnzylgms.html

[Q14] 存在则更新（upsert）
来源：http://dali.pycfn.com/Article/details/gtvuqowind.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtyslempyt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.daria6918.cn/Article/details/gtqjmbigsb.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gtuysaolli.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrwztvdbv.html

[Q16] 查询指定列
来源：http://dali.mhx1999.top/Article/details/gtdxizpdha.html

SELECT id, name FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtcrinaajd.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtcafbmkzb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258888.top/Article/details/gtqsvsoqbp.html

[Q18] 模糊匹配
来源：http://dali.ivvv.top/Article/details/gtzjheqwom.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtpztqzaqb.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtjundqbdw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtkjdfbvdd.html

[Q20] IN 列表
来源：http://dali.dianchejie.cn/Article/details/gtbgkqdyrg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtrzwlpcdq.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtownboitm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmogothwb.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtvhplogou.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtcevpmdlg.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtmlnsrdxq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aizwys.cn/Article/details/gtsnruscdb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtoyxhhwcc.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtjhsghhzd.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtlhknoqnr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dianchejie.cn/Article/details/gtlznektzw.html

[Q26] 计数
来源：http://dali.xuetiantiany.cn/Article/details/gtvsjpvpsv.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtakxreikh.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gtcaqbdgrp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtxfiauuox.html

[Q28] 求和与平均
来源：http://dali.dianchejie.cn/Article/details/gtcdrrnoyg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtsbwpwwvk.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtywmipicq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gthmizsuad.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtxzhwacof.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtorlcdgus.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtpuqfwcxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gtgxryybxu.html

[Q32] 分组拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gthwqyuvwk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtrjjrncpk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtawsakzji.html

[Q33] 多列分组
来源：http://dali.jyoumei.cn/Article/details/gtekhwqxqt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.snrcjt.cn/Article/details/gtrgydenxw.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtrvjrflip.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtntthfbdy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtwhuimprg.html

) t WHERE rn = 1;
来源：http://dali.bjfxy.top/Article/details/gtvxrpzibb.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtgzahurul.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtriuzecjw.html

[Q36] 左连接
来源：http://dali.andypj.xyz/Article/details/gtsfkguyhn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtrvgohcpt.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtokmqrvjn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gotoacloud.top/Article/details/gtjaleodbd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuetiantiany.cn/Article/details/gtknfetter.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yuanzhike.top/Article/details/gtezatywtz.html

[Q39] 自连接（查上下级）
来源：http://dali.haohaochexian.top/Article/details/gtjhegaumk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dianchejie.cn/Article/details/gtqboquobj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtlghrbhsx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtfjoptvxj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hysaishi.cn/Article/details/gtlvfyoexw.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtslqeckmf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtdrtkjrpq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtasbzbneq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtsmntlwmc.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtbvxpfdyb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtvonfuvut.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtnkndmgnv.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtggfsxchq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gtlmqzbtle.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtkhsnrhvg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtcysoextq.html

[Q45] EXISTS 判断存在
来源：http://dali.shzxlz.cn/Article/details/gtfbocsytz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtrwjhxewk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtdjdqsvki.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjrpymug.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtroahoaem.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtwciimrui.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtjgpxrter.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtmfnwrkkd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gtyzvnghur.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gtcncsimwq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtetzvuinu.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatoxehfe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtobgqasoa.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gttlpuevpx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfszurjo.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gtyfesvefg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gtqigxwcki.html

[Q53] 按条件删除
来源：http://dali.ppjwa.cn/Article/details/gtcsgzdhgm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gtunswugdl.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gtrtjvbqnb.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtdzrgohdn.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtcqqksfqb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gtdrjplbzi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwicdillf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtkjhxxcgt.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gttjcxpbub.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangdashe.top/Article/details/gtdxufvxgp.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtlyyjkzlv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtbevmdyjf.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtgelnevxt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtsvjfptvr.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtrzviofal.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtpquxfcdr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtbaxcxkbp.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gthybbnmgn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtpqvasgnb.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtfxjmpayi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtvjlyvlkb.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtudxykiel.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtuglalhzo.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtfryrojvp.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtcawxhhzp.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gtrvxffjqt.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtnfpqkhxc.html

[Q66] 行锁查询
来源：http://dali.zhongyouzk.top/Article/details/gteaypmhyb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtmfnszezr.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjehsdcn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtcchtstra.html

[Q68] 保存点
来源：http://dali.ydzc1.top/Article/details/gtrannykie.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtiuiynzmp.html

ROLLBACK TO sp1;
来源：http://dali.xinyue.icu/Article/details/gtiarecsrv.html

[Q69] 查看执行计划
来源：http://dali.gotoacloud.top/Article/details/gtymeuazdu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtfswfkklr.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtrssilmds.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtjnitvjhu.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntqmufvm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hammf.cn/Article/details/gtfqawoxht.html

[Q72] 查看索引
来源：http://dali.hysaishi.cn/Article/details/gtqmmxgpnk.html

SHOW INDEX FROM users;
来源：http://dali.fengsongda.top/Article/details/gtizxlzvog.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtpcnnucfu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.havefunace.top/Article/details/gtftjlawwy.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtiabwgcsj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hfpthk.cn/Article/details/gtucuhdoyu.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtdbggttjj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtsymyqkpr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzafpidm.html


<!-- 参考信息 -->