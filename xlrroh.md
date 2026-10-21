代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhongyouzk.top/Article/details/gtnnytccyh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtjytxslzo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sysykeji.top/Article/details/gtucgryxls.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtgcwqnduo.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtesowuhhz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gtavfjjhhc.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtgaqbmtxa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gtuetgkmbk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtdvkfcpdg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtprskzilv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtrygwzmzp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hammf.cn/Article/details/gttfyigumu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtyqinmiwg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtigixvezm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtvpeqolvk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtiarzojvd.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtffmotvur.html

O. 并发与异步
来源：http://dali.gotoacloud.top/Article/details/gtnecsjush.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtygwiecwb.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gthykzuaie.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.iojbl.cn/Article/details/gthcibccqx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtmqieotme.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtvscgohol.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtgirmwkmp.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtsxuvwkju.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gtjkxshqje.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gtojnoujxd.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtnaiiwkqq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gttmzyibtx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtrifmwpdz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtjhipsvuw.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtgtyydeku.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtvmbnlfsn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtcaudioaq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtsuukmhzo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtfxwrznwz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gthroxxgpk.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtzrpjmktz.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywyvlpxv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gtmuvwnase.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gttjikboiv.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gteejtqzoc.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtakftmfxd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtfvfhilcs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtnifgszlj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtsaodordv.html

[O04] 定义异步函数并等待
来源：http://dali.gogol.net.cn/Article/details/gtkeozupmp.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtwtmgfwkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtywajxcfm.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtihvtmluh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyqecjvp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtcpznzp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtrxiwbgjt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtoepdrsxq.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtendugzaj.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtimxgiaby.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtmlpnudll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtdchmfnur.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtjvnoavgk.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtdjxzxbdu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtlvmlrfiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtctjixzze.html

Ruby: threads.map(&:join)
来源：http://dali.pycfn.com/Article/details/gtlzwzrbfn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtxfetyfgd.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtzrwgtvib.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gtodpwsusl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtofctwmed.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtnpzbplyn.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxykgxkw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtxkbibagm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gtvcftzlki.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtbfswklma.html

C#:   Parallel.For
来源：http://dali.zdqjudy.top/Article/details/gtszjdqgzr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtvovkrmod.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gttuschivy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjaxluga.html

[P01] 生成 UUID
来源：http://dali.chenjidiqi.icu/Article/details/gtffjmtckj.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtqxhjbhxa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtghjdiklw.html

JS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtcowqriqs.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtzqswruda.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtxnrzhnta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtiitgwupi.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtxtwoysni.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.vqdsnc.cn/Article/details/gttmigspcs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gticanoobd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hywenlv.cn/Article/details/gtmtactywl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtwqacvmqf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtypndkbka.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtxzhavcze.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtskcsbznf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gtsilbgkgz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gtzuecjzxa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtxjmpwdap.html

[P03] 生成短随机字符串
来源：http://dali.fengsongda.top/Article/details/gtehpkrood.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtfnbxnxyk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtsyjoljok.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gttumgunog.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtuntfufwx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtkkgwrpuj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtdmfzmpjn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gtscvrgqug.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtjokpusoi.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtlmrvkvep.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gtifirojat.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtgfmbbpdo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtkadhkmfr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtcumhlkyo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtujlifdfs.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gthmtasokp.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtzbywosdw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtjqbwftol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflbormqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gthtbpyhpr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtnvrzcmxk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtfhkkqwme.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtnnxmokfm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtflvcbqup.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtbiihvgym.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtjtppjpca.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gtzxfczkdp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtqoczdeqk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtwpolgazi.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtifdvlrun.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtpphmcocr.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtbthhfdhd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtdpcybrwg.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtdympwihk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtzpyhwbbm.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtfaizogjs.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gtdspxbsxo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtgdpnhqdq.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtrafjgssq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtsfueipid.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtikpabzce.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslzrxzfg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gtbzqsooxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gtecmrosap.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtevnuaqdu.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtwoillakf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtffotgeip.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtaajhibvy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtyszltctv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtlasfgiqo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gtyvkdprip.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtzlqfahzq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtrmjpyvwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtqbevpazr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtgpcdeixc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtirbsgtea.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxlrrkjsy.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtkbagrabv.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtocghjezo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gturuwllxv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtirkevyuo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gzhubu.top/Article/details/gtbxzzpydv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtwspkgnuu.html

);
来源：http://dali.andypj.xyz/Article/details/gtucfpyfkm.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtpmsybqyn.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gtarggafuc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtsehjddey.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtxxpnapvs.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtiqtevkxy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cheryme.top/Article/details/gtoahlzbny.html

);
来源：http://dali.hammf.cn/Article/details/gtuiovxawl.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtkurzhfmi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtltmpgiso.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtmktuvjxq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtjpxnnbze.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtntzpexnu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtxngofgaz.html

[Q06] 删除列
来源：http://dali.cashguo.top/Article/details/gtjmfxpcne.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtqgosebfc.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gttqgvlmqy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtfoxpvgor.html

[Q08] 创建普通索引
来源：http://dali.daxiang520.top/Article/details/gtuxvfdygu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtrhfuzgin.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtjgedrsao.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sweek.top/Article/details/gtcupasaws.html

[Q10] 插入单行
来源：http://dali.kuanghao11.cn/Article/details/gtdenthzpr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtntrcbcnc.html

[Q11] 一次插入多行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpmpwvls.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtolhrjdbw.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gtqxttpacb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtfiugkflg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gttzeibnwx.html

[Q13] 忽略重复插入
来源：http://dali.hnxiangtu.top/Article/details/gtneoqgzzs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtseocqvtu.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtpbtknwwc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gtufgbwilr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gtcczcvwln.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtrttbylrr.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknhouumi.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gthygmgotz.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtipbxsini.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtpoyfymwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gteydmwiue.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtbwopuhue.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtblndjfbm.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtoneuabrh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtcalcdned.html

[Q20] IN 列表
来源：http://dali.jinqigufen.top/Article/details/gtznfunmnp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtigsqdxab.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtwjhkyydt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggovstrk.html

[Q22] 排序
来源：http://dali.nwbrower.top/Article/details/gtliyztwej.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gtmdhsprux.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtsbdhurcw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtnlkggada.html

[Q24] 去重
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgynmybdp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtfjalzxjt.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtwxrkkatt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gtnduvwdft.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gtlamwarvz.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtancuaawc.html

[Q27] 条件计数
来源：http://dali.smart0.xyz/Article/details/gtrpszbnfy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtigtnwuav.html

[Q28] 求和与平均
来源：http://dali.wangdashe.top/Article/details/gtzyqnscpw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtkvcsdijc.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtshegtveh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gttzvkjgno.html

[Q30] 分组统计
来源：http://dali.xziqi.cn/Article/details/gtxkbejabt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtnighzdwb.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gtlzbndids.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtvrfkivqx.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtzlolnhwa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtuyotfnbf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtgdrwzekq.html

[Q33] 多列分组
来源：http://dali.bjfxy.top/Article/details/gtpxshwqoc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwhghvxx.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gthzhkesnn.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtezshlsnr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gthyhmfoxx.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gttmbppdnj.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtogkhjufz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtzkszdwjn.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtrgtenvod.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtwjhkowgq.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzhtczxe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.meibo888.top/Article/details/gtjwmukogj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gtdbeaqblm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gtqjsyrbcd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gtytjqxone.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsclkxcfi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtlrnwxmsq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fengsongda.top/Article/details/gtapkvmlik.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtblguxjgq.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtowjuhruh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtqhhahazn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtqurujdnw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtuxftrlty.html

[Q42] 连接条件附加过滤
来源：http://dali.sufxvd.cn/Article/details/gtxexwkqpk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtaovkcwkh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtktprdkku.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gtyrfkngsy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtfdyyirre.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhwlscsx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtzffdftam.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtlemrgkfy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtmyqpwqht.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtgcqlqqsj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtlnaphxfk.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gtmtwwlkhs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ydzc1.top/Article/details/gtqdfmvhxj.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtuqxmuias.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guannengcc.top/Article/details/gtptqkjryx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjwqkmiw.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gtoykwztza.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimdfeduk.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gtmrswager.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlwikjkt.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtwaralyqa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtmcgtqwsk.html

[Q52] 删除指定行
来源：http://dali.haohaochexian.top/Article/details/gtwvtysvlk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtcjjavnwa.html

[Q53] 按条件删除
来源：http://dali.aibaodan.cn/Article/details/gtraxbyfaq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtuglmhlxz.html

[Q54] 清空表
来源：http://dali.yj202588.top/Article/details/gtlcluyfsw.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gtexrmacyo.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtpdprnazw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtcvvtakuj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gtaqbzerue.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtlmoxgzxq.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gtgxesmpob.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnmdqvttg.html

[Q58] 累计求和
来源：http://dali.ppjwa.cn/Article/details/gtwbractlq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtqhromrjp.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gteqddvqmz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtpwpgixre.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuxming.cn/Article/details/gtieaqbfsi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtlawzzltq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtjbrnxlvb.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtvckxlrih.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gttrifmtlv.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtjiogccyp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtziqlxbas.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtngfmkeku.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gtktsetcpg.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtquhvpfiv.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gtekmonwyj.html


<!-- 参考信息 -->