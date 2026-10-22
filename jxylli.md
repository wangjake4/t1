代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.mhx1999.top/Article/details/gt2dvaxxvry.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gt2bkqlwvjt.html

[N11] 二叉树中序遍历
来源：http://dali.yuanzhike.top/Article/details/gt2mqphzvej.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2kkjeckkf.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gt2eqaihbdx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2yrcxflhk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2jeomgmbd.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2kvizeofm.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gt2iexuskeh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gt2otilgjoy.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrtddlr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gt2nwhtitto.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258.top/Article/details/gt2ssywjacs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gt2vjlxudtw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2fympfgvi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2hhiecxaw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gt2cjqccihw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nttcqokp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xylfe.cn/Article/details/gt2ztglxjho.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cagonbtm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2huczwxiw.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gt2xzaopqlt.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksepsscq.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gt2mmkajhah.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2ydopujnw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gt2utuuusjt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gt2mimrrwbq.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2kstmjabi.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gt2abgdocdg.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gt2mkdlaxff.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gt2bclztrgg.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2ucjrwwtg.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gt2jhcgpqlf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gt2ivzvijwq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gt2icuhvsrx.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2rijmeclc.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2pfyrvnvk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gt2ztkgpjjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gt2owowxnpq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gogol.net.cn/Article/details/gt2ngkjttfz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gt2qacznekf.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gt2wbromklp.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gt2ztlkgxqf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gt2zzzqtwaj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gt2susrgpzz.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gt2extdjfks.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2dqzhwous.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gt2iqnddjjj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gt2mffzkycn.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2iraleguo.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gt2vetduwyb.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gt2ubybaxcd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2myxuxrab.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2hljmnqng.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2xrmkarrm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2abwadahj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gt2efmelbzz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ooephvqd.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gt2iopusxqm.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gt2irczkuqk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gt2sgurlbsc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gt2drmrwoyn.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2oximlzcr.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2yvqkgysx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gt2gznhhaco.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2doelflwa.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2iokjonky.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gt2ntzsvmom.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbuvwhzh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gt2levadsva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2biuxungr.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gksroxpp.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2bvlheynb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hysaishi.cn/Article/details/gt2relxzrrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2uatwhvlr.html

Ruby: // fork 块
来源：http://dali.zhengqikj.top/Article/details/gt2ozhnfwjm.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gt2dfahyxkh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dipbrkbj.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gt2cjpcmgwm.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zbbslwim.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gt2tftploso.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gt2zxdmhcbv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2uplpxpmc.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2xlmsasyh.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gt2zhpwexly.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuxming.cn/Article/details/gt2ksnqulbo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gt2mpdcrilb.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gt2sjqusqnx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gt2kskkmpix.html

[P02] MD5 / SHA256 摘要
来源：http://dali.quarkkingdee.top/Article/details/gt2isofdnsk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gt2pqbkknar.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gt2eipqwsch.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sweek.top/Article/details/gt2qwljveba.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gt2qgovhrep.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gt2bpmcrpui.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gt2okylznlx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2gwgprgrs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhixingplan.top/Article/details/gt2yvitroob.html

[P03] 生成短随机字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxytexqz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gt2uwmzxyip.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gt2fifqoinj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2vscfyjhi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2arnqdlki.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gt2mapyydca.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gt2bpwxdvwg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gt2xanzmuxa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gt2mdmoinpl.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2phargyli.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gt2eqpbzmgx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gt2hljxtfom.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gt2yqvaenek.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gt2unxvniml.html

Java: list.size();  map.size();  s.length()
来源：http://dali.meibo888.top/Article/details/gt2oxljgvmq.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2plwbvuwk.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gt2cyzzqdfk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhycmczr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cirvysyp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gt2vwdhzdsd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gt2hkpvpito.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2hzhqfmod.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2nfckcgah.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2pdvjxhmc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2engfrrsp.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gt2rohahujg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gt2vomcfasl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvibmhut.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2gmhqeffw.html

PHP:  if (empty($x)) {}
来源：http://dali.mhx1999.top/Article/details/gt2mvdingpo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2crqzhnxg.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ohdnqint.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gt2rrzpyquj.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2qdgppnoq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gt2zyzljjvp.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gt2kgnkgpzl.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2scykjuau.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gt2fzgsxlyc.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gt2iqilnamd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2cndqumcl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2bmwetzzt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gt2jvpwhclq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejgmfpsm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gt2tckdxoip.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtkppbyl.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gt2vjwczeur.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gt2osgkfvtv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgzgbbvo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guannengcc.top/Article/details/gt2eqdwusev.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2zifqiiss.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gt2phnfusxj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsampjdr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cdnleiting.top/Article/details/gt2jduobppe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gt2tjirozhu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgszulai.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bsnmdxpp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeirmfnb.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gt2oinfzwzb.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2kydxwdwi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gt2mqiexiqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gt2ieoafswd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gt2wkpxpdat.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gt2oluyhhbt.html

);
来源：http://dali.yj20258888.top/Article/details/gt2jkapygwu.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2upcmytka.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gt2vkleqkmh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdsrajhk.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2upwhfrtv.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gt2jhrfnkix.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gt2gjgfszfi.html

);
来源：http://dali.pycfn.com/Article/details/gt2fsmdvcww.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gt2senjmpoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gt2vdmsnukd.html

[Q04] 修改列类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcjlevqy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gt2pqejjlas.html

[Q05] 重命名列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hsutzvwl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gt2nmdgmwrt.html

[Q06] 删除列
来源：http://dali.jlsjyb.cn/Article/details/gt2hdrfcehd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gt2vjurohgb.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2dyhukevx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2bzuoxlie.html

[Q08] 创建普通索引
来源：http://dali.fzhhl.top/Article/details/gt2ywsocobb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbjspbae.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjoylglr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gt2athqqxem.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gt2gzumzjrt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gt2picaovnj.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gt2clpbtnml.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gt2nsjvakuq.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gt2oehueyxr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.svipenyu.cn/Article/details/gt2njuippjq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfwnllov.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gt2zojqbpve.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gt2jctjhzlh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2dbqbssvu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxinkj.top/Article/details/gt2kvsriixf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gt2cbrpzklb.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gt2qvduleev.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2jcbupowh.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gt2ekfbgsmq.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2xciuorie.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gt2dxghcbxt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2jpymozor.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gt2flmxjooj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gt2dsloewjl.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gt2lnvzifdd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gt2vwgvyhnr.html

[Q20] IN 列表
来源：http://dali.aizwys.cn/Article/details/gt2lgstycae.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2fsdqzluw.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gt2rmyhgcai.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guannengcc.top/Article/details/gt2epnzgjcn.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqjdqmnm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2ieuefssz.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2kzgegjhz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2asgrzsli.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gt2otldqxpj.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2dbnscnll.html

[Q25] 只取前 N 条
来源：http://dali.jinqigufen.top/Article/details/gt2uwumvfjk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gt2ichrlciy.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gt2omdalhwr.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2durfcjcn.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gt2zvycyefj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2cgwoizux.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2zavrijyy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2gpnrhrdc.html

[Q29] 最大最小值
来源：http://dali.cdnleiting.top/Article/details/gt2pnhqvgrl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2edpuhvve.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gt2qgqnzxiv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gt2vkbbzlpt.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2zuazthyj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gt2brbogpao.html

[Q32] 分组拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2vtstzzkr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2jipvedyl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gt2aijfonyo.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2uzxjvczv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nfihkykg.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gt2spkikmrh.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2rgannivs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zycfv.cn/Article/details/gt2qszlxqrd.html

) t WHERE rn = 1;
来源：http://dali.cheryme.top/Article/details/gt2vpxzdiqh.html

[Q35] 内连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axwuvshf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gt2znuhlqla.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gt2dnrfaeea.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gt2pbjtwajw.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gt2vmpkgpdr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hfpthk.cn/Article/details/gt2inlntkme.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gt2lcjfhevk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gt2vqmnicyf.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gt2cvullehk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gt2wbpabasu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cucudq.cn/Article/details/gt2nknewkpz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gt2shhrnipc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbmwucle.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gt2avydfglx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gt2xlfdjycf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tianlin.xyz/Article/details/gt2dhnnzrrv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gt2sdyrzoty.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gt2iaarwdlp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzwqpzas.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gt2bbckvreg.html

[Q43] 标量子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obpzwwjk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eebcckld.html

[Q44] IN 子查询
来源：http://dali.yj20258888.top/Article/details/gt2htcbsbrl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gt2yqyeppxb.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gt2yeattase.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2ttlfwcrr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gt2gacqtvop.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvnpykny.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gt2eserclqn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.smart0.xyz/Article/details/gt2vrmtytpr.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gt2eyectuag.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigfzy.top/Article/details/gt2kcpbnedb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gt2ugirtuih.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gt2lbpcmsgh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpwlklmg.html

[Q50] 批量更新
来源：http://dali.quarkkingdee.top/Article/details/gt2vtyzbxkd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gt2jevjracs.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gt2ekkorfme.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gt2dxredyvj.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gt2kusbourn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gt2ixcisdgm.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gt2gszgkwat.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2onzstqcs.html

[Q54] 清空表
来源：http://dali.yuxming.cn/Article/details/gt2yazpljmh.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gt2fcoufhsh.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2ljbtanhu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlkeczcs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gt2pfttsuws.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gt2tjfznpel.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2nzwuebhm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gt2gmxvaemr.html

[Q58] 累计求和
来源：http://dali.jiagoushi.top/Article/details/gt2qmgvdujd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2zebcwist.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wavyqiyb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gt2qfzpbyck.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gt2plbjvivi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gt2ulwbfxqg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2xhsdeemd.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gt2gzijhurz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jabjxesu.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gt2jpqogamm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbaeyhty.html


<!-- 参考信息 -->