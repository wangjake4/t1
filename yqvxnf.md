代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gt2rfnzladh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gt2vkjnurae.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gt2kmvcboom.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gt2abdixcoq.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gt2pnbwcljx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2axxfpgym.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2pxfppiqh.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2fniekbjx.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2jusmrutm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gt2cvurycdb.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gt2eruigtvm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gt2svdywuqu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gt2gwqnqjrq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gt2zkyjcyxv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2jagobxlh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2byudvxjg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2xdtshxor.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gt2slimujzk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rskndqop.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2odafomax.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2itjlsfsn.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2owwqjjxv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2vfmgxdfv.html

[O01] 启动一个线程
来源：http://dali.tian-w.cn/Article/details/gt2vizhjoac.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gt2jwvfgpux.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gt2znyrecad.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2xcpoamec.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2ljmtkqxu.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2bdtmfkad.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2uivmkzar.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2xvppypna.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ggtqrhdb.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gt2ewskqmsa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2dktkxpdp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gt2atqjudlf.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2eiagjqei.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gt2hvrdiecr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gt2vgwnpzct.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gt2qtdusxmk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihyoahwx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwbtzgtb.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2pjzzhjnb.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gt2ehcrwuyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gt2szgnuckn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yanxiufei.cn/Article/details/gt2kshvzzpw.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gt2hawuwkol.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ivacvbaw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2marzjham.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gt2zrchczib.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2xxnigjny.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gt2vowuolcn.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gt2azmkyvwc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gt2vpygvqwh.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2wihjuxhl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2yulpyvhs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2euoivaon.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixvasdcf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gt2cdvphumk.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zkalmwfa.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gt2pxrzykdt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2ucamsxfw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hammf.cn/Article/details/gt2oliwdnoq.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2gprrroop.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2nzjbaswo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gt2dqsjzymm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibhxoirq.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2dbedadnp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gt2gsspatcw.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gt2cgdweugb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zcaoyfuj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2nbhhjmdf.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gt2wxsgdmod.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2wgliutcq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sweek.top/Article/details/gt2lpuhbfon.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2qpldmyli.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2ejxjtqql.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2hsacwtgx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2hzpibdsr.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gt2fekutado.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2mfujdmon.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2oethodyd.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gt2jxmdifdi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gt2jtjiigxx.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2qnqjzjak.html

TS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2wnbfdeqb.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gt2ozgkjdpv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbtocfep.html

Ruby: SecureRandom.uuid
来源：http://dali.sweek.top/Article/details/gt2qjtljmvd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gt2qvnwsmut.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbytexyo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2oionkcto.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gt2axkleilr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gt2thqhllcb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gt2kowidznm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gt2socpqtfy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gt2azjkusue.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gt2zhxrpkaq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2uqhpjzda.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2zxiqlgqd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2ymiyvynj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gt2qdbhmbos.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2spbuuquw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ayjfjrmk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shuidangran.top/Article/details/gt2ycxnghei.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gt2ynwzalhf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gt2lzkmyrcn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycnxvrzb.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2hhqmgkmp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gt2lnyefirk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2eipaqcoa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2olculywy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gt2zxyodlyj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2gikpbndc.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2caikgtok.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gt2gxuvviax.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gaohongyu789.top/Article/details/gt2wmkyfqbz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gt2nfkzfeoz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gt2xgjozgdb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gt2wvrjreks.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gt2uyufymxi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2qqhqvzeu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2fdwbfdxd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2rmplsljj.html

Ruby: a == b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iubsojek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gt2gnhzvjnw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gt2ttukdhwe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2ynjjchzh.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xdblpjrg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njybwafe.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2aorolgbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hxvwktsx.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2uxwufzyk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gt2lvuapbqb.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvdznqpm.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gt2hlsoiwvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gt2qinpekmc.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gt2anoipyox.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2qrzaucpz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2ffsglonw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gt2ksfimxhs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gt2yugbgvxx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cucudq.cn/Article/details/gt2iekqmsvk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gt2evklkpcw.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ancrztbb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gt2cqrywkku.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2fqvqaley.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gt2nvrvhokw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gt2ncecutyp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gt2mfbykxac.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gt2uyiqwarb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gt2xikvxbvk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gt2koiqibwl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2vjmqfkgq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gt2marjpmcx.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2bioqcnmk.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2pugeejbl.html

CREATE TABLE users (
来源：http://dali.yangfankeji.com/Article/details/gt2bbjygmph.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2vkbekrmv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gt2mknqxnft.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gt2wqilyaqe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2pfwgmcte.html

);
来源：http://dali.fzhhl.top/Article/details/gt2kzwcmxls.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gt2dkrhyqps.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gt2ctynlztg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2zmgfkaot.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gt2uyzxwjhe.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gt2mntungvq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gt2ijzskxau.html

);
来源：http://dali.gzhubu.top/Article/details/gt2qohdxbuy.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2qvznwcpw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gt2wgqrnfsq.html

[Q04] 修改列类型
来源：http://dali.yanxiufei.cn/Article/details/gt2ljnpvjcz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gt2salttgic.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gt2bqkgghjq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gt2luwiwpvg.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gt2xorgwqms.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2sybuvboz.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gt2ipfkxssf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2nkzjmxoy.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gt2mueoowyl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2mwtuajjz.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gt2pymgmnel.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gt2hlianpay.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gt2vuxqkiwz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eudeqkos.html

[Q11] 一次插入多行
来源：http://dali.smart0.xyz/Article/details/gt2zhtdsicc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.birdmap.top/Article/details/gt2lgtbwafj.html

[Q12] 插入后取自增 ID
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekfhnmrf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gt2ioooyeqh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kctgtikm.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gt2lputphjb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2yhshgplw.html

[Q14] 存在则更新（upsert）
来源：http://dali.snrcjt.cn/Article/details/gt2enyygdrr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fengsongda.top/Article/details/gt2minwclhw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ydzc1.top/Article/details/gt2owtjkrid.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gt2wbytpkjh.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gt2centoitz.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gt2egnwdutz.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2bsrhdwvv.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gt2yccebvlu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gt2wimqiwha.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gt2qrvgwwrc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2jhacfgvh.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gt2jajhetwg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gt2dcpzpemy.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2xsltasmr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gt2ouhrcaco.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gt2grfzthlf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2ocjrvxbi.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gt2fvlzizrg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gt2odlfczjp.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gt2rftdesea.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258.top/Article/details/gt2zsndarer.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2uizrgzpz.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gt2xnoiabtw.html

[Q25] 只取前 N 条
来源：http://dali.yj20258888.top/Article/details/gt2mtvzlxog.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yiqmhywu.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gt2xzwggagm.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gt2qewbxyib.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gt2vajwktsv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2hmpimunx.html

[Q28] 求和与平均
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtdfgams.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2oqirzzfz.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gt2ypjcylnq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2jjvyondi.html

[Q30] 分组统计
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxirjrrr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2evhztfbi.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gt2hxkvqfxb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cqqwz.cn/Article/details/gt2hiboslat.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2fmpmjkww.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gt2mhfmoonl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gt2outudxuy.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugxpnlkt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oiypssml.html

[Q34] 每组取第一条
来源：http://dali.ydzc1.top/Article/details/gt2bdrwvxbv.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2heetzqqm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2ldxvadql.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2rjjguxyj.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gt2tthstgyp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gt2ombdaacu.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmkctoxa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2mcmtlgxw.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gt2baxosqfl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2lqsxxpzi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gt2vgqwatzv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hywenlv.cn/Article/details/gt2xnzzonqd.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gt2egwqunzx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gt2ozcxqexy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gt2xjgjrbyz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2lzxyprzv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gt2rckjraqx.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2lzzcgzbq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2rziwdzwk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gt2scndkmbm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gt2zxmeieoh.html

[Q42] 连接条件附加过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dosgdttu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinqigfzy.top/Article/details/gt2ufoxpbfl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvxeoqln.html

[Q43] 标量子查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihkyheyg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gt2dwcvgzuq.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2iubgcvut.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.svipenyu.cn/Article/details/gt2swlryzlm.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2fecjjjhd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gt2dnldgyji.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuanzx.com/Article/details/gt2kznbxzcl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gt2mftwwoeg.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gt2alpxumjc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gt2uyvijjko.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gt2leykfoby.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2qmuwecgg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gt2gilprdfl.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gt2ftaibwxr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijqbhvbr.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gt2qbqmydmu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2rwgqqmec.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2icwjocqs.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gt2nverywzw.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xdjavytq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2foysmrsk.html

[Q53] 按条件删除
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fuozlrhn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gt2hbilbnjd.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gt2wwmmwuxj.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gt2sjdkgdya.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gt2tlqctamp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2knqzrtbx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gt2himhsnvg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gt2brbxetff.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gt2gekzegmf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2mvmwoqzc.html

[Q58] 累计求和
来源：http://dali.yangfankeji.com/Article/details/gt2qlrqkqiz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gt2egathvbe.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkfrszfp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2ohdujxbo.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gt2nxouuses.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2dbjmeizl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2cmvoevep.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjsruswr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2zkwzqroi.html

[Q62] 分组占比
来源：http://dali.jlsjyb.cn/Article/details/gt2geuqlixe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gt2jtdoojyl.html


<!-- 参考信息 -->