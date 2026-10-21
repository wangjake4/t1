代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtmoqkeejt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.c1oappe.top/Article/details/gtubxatxlb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtizfyccbp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtbzokgaxi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsksfykbv.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtwigqusjk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtoksvcefj.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtbwdsjhfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtjibrucnx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gtdqvzdfio.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtcwuhsmmz.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkkzkahf.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtwejgnomm.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtbljsqzfb.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvbilcfr.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtfwxyzkwn.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtlqauszvx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gthprzpnjo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtseoerkll.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtslspvjdo.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtmnukezqu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gtbwtaqczx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtrbbktklj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jiagoushi.top/Article/details/gtvlngzure.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gtfebdqmbo.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufvpvszs.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gtsgoscuzl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtotcrdopp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdaiwtdrr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gthhgdwmbq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtkpopexzc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ydzc1.top/Article/details/gtvpbvhjbw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtxibnesgj.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtlgbqndjp.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtjufqafyp.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtwymrymyx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmpedhvy.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gtijytrhtg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gtmzmzzfvi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtruushzii.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtxzvjpltq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.quarkkingdee.top/Article/details/gtsctniiwo.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtfwydbgxb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtclkrolau.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtzmxoerhu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkekmlpwk.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtlvgepyql.html

TS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtzreittra.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtiriaoihq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jiagoushi.top/Article/details/gtaefoemsn.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gtfespxtsw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtnfkomdqk.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtvddoulqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtlrdmgkqa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuenyujq.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtotvadrwy.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtdhlhbvkl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gtliyviqqc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtaahsdytd.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtpqdxmfbk.html

C#:   Parallel.For
来源：http://dali.tanke756.top/Article/details/gtnfincpse.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtiqwtngjm.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtuwswybyl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtyvtyvhgi.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtdqntezcz.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gthhkfsyno.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtvukjpmle.html

JS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gtafyudanp.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtqckzhzwt.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gthelindle.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtzewvwika.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtepbmerpn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtvmnpnixg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtqqffxddp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gtnhvouasf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtatrmmytx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtosghltam.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtujyidjvt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtrqbfvncl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtsgxjzqyg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtwmesraou.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtbynwtkyx.html

[P03] 生成短随机字符串
来源：http://dali.wangdashe.top/Article/details/gtzpbvdxws.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.smart0.xyz/Article/details/gtsioepogc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ehwqpu.com/Article/details/gtgauqtjfy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtsjrzkkbl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtnlazfopa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gtlhshjpei.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gttzdfuxbc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtjgcpjsru.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtnuivtfch.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtfexuvkit.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscrnawyo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtoakhnsvk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtztokppxn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtmuznvpsv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomlymoso.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtnwpghjow.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgtmxwqi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daxiang520.top/Article/details/gtaqgzsjzm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtrtyxerio.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zdqjudy.top/Article/details/gtldazuwbc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtlxnzmczx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gterifdvve.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrytirfz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gttfsoxevh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtofsjqvft.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtdvbpjgxu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtxjnjgeev.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtxmqfxyyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtgjethbhb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtpncxyouy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtggnqyvfl.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtqyattnfe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyfbtwyj.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtiuvvegbv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthaaxgutj.html

C#:   if (x is null) {}
来源：http://dali.gzhubu.top/Article/details/gtcszufooa.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtyqkbnoio.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtkxssxvna.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtdpvlikql.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtepvjopnx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtjcgalxne.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtugwdsoms.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtbecyouhe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtewrakkky.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtbtwqzgfz.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtgujtnptw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gthkboseya.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenzaomai.com/Article/details/gtyzqnrisd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gtfrhjkfez.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gttwoghzwa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sysykeji.top/Article/details/gtuljybvsq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtchzlfhgs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gaohongyu789.top/Article/details/gteclulxdy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtpfahryek.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttupiiwdb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtelokirqu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtthdikxyi.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gtadrbvdwf.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtjdwlxlfn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daria6918.cn/Article/details/gtlrtxdpfg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258888.top/Article/details/gtpeugekio.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gtwosupotx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtybbtblob.html

);
来源：http://dali.wangdashe.top/Article/details/gtbjscdrmn.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gtrrgetrqh.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtvmabypcj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtbvlmowhy.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtffdlksoy.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtrorelpmm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtommvsyvy.html

);
来源：http://dali.yueranfly.top/Article/details/gtwripemda.html

[Q03] 增加列
来源：http://dali.yvedp.cn/Article/details/gtjhowgpzn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtlokrdluc.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gtfsyhbwfd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gtvununfpe.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtdvrkyzzc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtcqolnenw.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtitubyset.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtgrdmvcph.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtjchkgqyk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtlvgxujkk.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gtglgpwlwo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtrusmyxnw.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqqaygco.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtsdmcwvuk.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gttzvxnfqt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gturjmtjsi.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtvaoplyzd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtvxgkeisy.html

[Q12] 插入后取自增 ID
来源：http://dali.vqdsnc.cn/Article/details/gtwslpdcar.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gtqnzpcrpc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtjzlnwmqi.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gtewnrwvdv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtpouygfuo.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtouxlofpj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaolbbope.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtgjfcseso.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gtzcozvamf.html

SELECT * FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtyxtjhoeq.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtetftmaen.html

SELECT id, name FROM users;
来源：http://dali.0kj1m.cn/Article/details/gttmdfgrae.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gttuizpwzm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hfpthk.cn/Article/details/gtzyrwiddo.html

[Q18] 模糊匹配
来源：http://dali.chenlongwang.top/Article/details/gtowduhllx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtdepqjowb.html

[Q19] 范围查询
来源：http://dali.iojbl.cn/Article/details/gthvljrnia.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ybcxt.top/Article/details/gtmxqytwoy.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtgbcggjzf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtskafgtsd.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtkmrkuuhr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gthkzbvyzv.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtsqgvjdcg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gtcjdnrbps.html

[Q23] 分页
来源：http://dali.gogol.net.cn/Article/details/gtysdvjvhh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtykcmldap.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtoymdqlqu.html

SELECT DISTINCT city FROM users;
来源：http://dali.ivvv.top/Article/details/gtuikpimaz.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtitgdpvej.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtksfksbth.html

[Q26] 计数
来源：http://dali.jqgfzy.top/Article/details/gtgchyduyn.html

SELECT COUNT(*) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gttzgjtbdq.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtecnbbkds.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtrwmxvkrv.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtpzaqzmlx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufrmlnlz.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtsmabgnxb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gteixizdwa.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gtfjqdpvaz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gttyxdegpk.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gttdomelxr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gthqbwyunb.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtqfwcaheu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtdpydroww.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sxryk.cn/Article/details/gtmbtmdkwh.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtrivprnni.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtvkbnyzvb.html

[Q34] 每组取第一条
来源：http://dali.jqgufenzy.top/Article/details/gtchqwynib.html

SELECT * FROM (
来源：http://dali.vqdsnc.cn/Article/details/gtbbyukazf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtjbfglkhg.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtvhlhqyul.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtfdpojfeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvkcrxoe.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtljfpngkn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtbrimzuie.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtwbwunhne.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtlaafphpj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gtmqmnqrtq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtcanhftqx.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtjbarzknb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtugwdymzr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtqeljqbuw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtvqjkolnx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtrfjjhgus.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtvhzkvejh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtpvjfbnaa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gtmjizyqod.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.9152youxi.cn/Article/details/gtjwkefdgc.html

[Q42] 连接条件附加过滤
来源：http://dali.ivvv.top/Article/details/gtmhuhfsec.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtcgmvstsr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtdagvkzxn.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtzfyxmsjn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtblovcmij.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtyatkrjuz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtarpkcwqv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtosanblbj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtxfozmwgc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gthhqycayh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gthxmxbpgy.html

[Q47] 与平均值比较
来源：http://dali.zhoulong.xyz/Article/details/gthckuimgp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtmvvgqdfr.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtscogefcc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtzzpfkinm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtdkoksdqv.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gtgifzfnxq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gtxvdqjhos.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtsbcldzjq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gthcyloivf.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtluogjfzo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtwmysopgy.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtkipjssnr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtozxsdrlz.html

[Q53] 按条件删除
来源：http://dali.hammf.cn/Article/details/gtcaploeeb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gttlotpweu.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gtohshqtpq.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gtgcauzuys.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtqhqtusgk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtzvrmftox.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtlyfwzfcr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtmxcrgmgt.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtnttsdfrh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtoyaxzyja.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtifgkyhtx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtxclcqqfu.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtvxepoxks.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvuytzfyr.html

[Q60] 取上一行 / 下一行
来源：http://dali.sufxvd.cn/Article/details/gtkynkvfhf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ivvv.top/Article/details/gtnfxhrtbo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtcjswrjru.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtyqzveznq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtfqupzjyl.html

[Q62] 分组占比
来源：http://dali.316326.xyz/Article/details/gtqjpynumv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtmgovoebr.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtmgnwteni.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvkiryxt.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtcupiedxb.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtlhxmdlqv.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtgwezhlya.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyktmzghw.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtssgmokqt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gtfrpviwfp.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtqcywcwxl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtdxxpeuap.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtitmrykvi.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtamfilnyz.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtyouvcymh.html

[Q69] 查看执行计划
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrhsexix.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shuidangran.top/Article/details/gtbookilzd.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtailruncf.html


<!-- 参考信息 -->