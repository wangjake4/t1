代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtxsrqpwff.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtfljapqif.html

Java: class Node { int v; Node next; }
来源：http://dali.aizwys.cn/Article/details/gtkiktntsr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gtpxmmzwcp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtexqeuojp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrfxftnx.html

[N11] 二叉树中序遍历
来源：http://dali.haohaochexian.top/Article/details/gtdcxrbcoh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuetiantiany.cn/Article/details/gtxvwkhwbe.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtztmzxlxl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gthewrejjt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtuqfdcxsg.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gthtwvqedt.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtmcsxlafe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtccbqdirw.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtnmtwkrke.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guowangkeji.top/Article/details/gtbcxtrdzy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtulafynvk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guannengcc.top/Article/details/gtrnhlqwvn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gteeiwgkna.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtrwkojlsf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtyeyqvacw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yonumen.top/Article/details/gtgfblbacz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtvheshttw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtulmlpzkq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcakhxra.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtyymvtkuv.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtusigyyyr.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gthzgwsylj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtarvahzjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtyraafbvh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtlynbjvfp.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtiqsdwkve.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtuujynbud.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gttbmtpzwl.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtsfegmmmq.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtjvwzueqf.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtuhnjvnza.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtzhnzjsbl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenzaomai.com/Article/details/gtygxcdacd.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtuhyzfwdg.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtaurlqptk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtwpvwvioo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtixsyqcax.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gtwnyeerxz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtbhrdyeuj.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtlizhzsfz.html

Py:   with lock: shared += 1
来源：http://dali.aizwys.cn/Article/details/gtntqldttt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtjezhjiez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtuatvismc.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtxipymzyf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtbdualjrb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtpghmtpfj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtdynykogu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtlkujxiok.html

[O04] 定义异步函数并等待
来源：http://dali.redwolf501.top/Article/details/gtxsqdjfsp.html

Py:   async def f():⏎    await g()
来源：http://dali.cheryme.top/Article/details/gtyqrlprng.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtofcjfazo.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzytpljvy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbpyltop.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtvetvjcya.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gtamtgbvby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gthzlitfrh.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gtsjnsquwc.html

[O05] 并发执行并等待全部完成
来源：http://dali.gzhubu.top/Article/details/gtemajugcp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtukwfnoqf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhengqikj.top/Article/details/gtcuzuzwdf.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtuoyniyoq.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtjgbjazzy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtcumrzlsg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtqgjtdnze.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gtdugqwrms.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtqtkdiqlm.html

[O06] 使用进程池
来源：http://dali.hnxiangtu.top/Article/details/gtegxlepza.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtuswmgptd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtlbwxnkzt.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtxouuqmlj.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtbpigqsim.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gthgucxyws.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtacbszeqx.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtivqhvxdp.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtykjyqtke.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtxgqcfiqv.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtqmwanhmi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtpsyedghg.html

[P01] 生成 UUID
来源：http://dali.shangyingyoupin.top/Article/details/gtucvgilxc.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtwvsbjahb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtarmxghsf.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtzmbhruvr.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gttfcepder.html

Java: UUID.randomUUID().toString()
来源：http://dali.aibaodan.cn/Article/details/gtlteiblqt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtrgjbrgiq.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtthluhaxk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gthtmtzebd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtmjmzsxjw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqyenckqo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gthhsteegd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtenxkahsg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.redwolf501.top/Article/details/gtlxaxztrn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtuhjuvlej.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gteffzwddb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtvljudckx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtrbbftztt.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gttddxbffc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hysaishi.cn/Article/details/gtxqfwtngl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtgxatarup.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtvkhptntl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gtdweoxpgt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ydzc1.top/Article/details/gttkirnxvb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtwfgwxcrj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gtrsqbrkms.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gtdqeinqec.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtnmbslnsb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtfekqtecb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucutgadr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gtvrehdmzm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtnmtzetqn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.316326.xyz/Article/details/gtrnsqcmnl.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gtibbxvgta.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gtpcjdstwy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gtduhdovdy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtuvecixbn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgybykpjn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtqndcxanb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gtyujjxgwc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtxoghcsaz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fengsongda.top/Article/details/gtnlwvvtmg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gteupokktu.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtmmmexqmk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gthqqhngmp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtxpeksoal.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xylfe.cn/Article/details/gtfftmsuni.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtgotddcxc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuwzydxz.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtnmyojjvk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtctxhybhd.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gttbcmmajq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gtnxqheopn.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gthuxsdiok.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gttxzdtgup.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guannengcc.top/Article/details/gtnptriale.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtzisleuwh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtxchtukfw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gthiupocjq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtkdqhzjvq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtgjufmhft.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtrqcmyfoi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtdfoxttwp.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtonxzppfe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtasiadijl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtetypcxma.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtdipqunhh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtpsixvmcn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hywenlv.cn/Article/details/gtqjelfcra.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtntakptwc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtjvbegkvs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.bjfxy.top/Article/details/gtzzzssunq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsgoeuuub.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtrhyierun.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtumpbovzc.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtgnlmnhyg.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtsnipqejh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtpobehtxc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gtbpttjulj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtptsueggd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtgnmkxick.html

);
来源：http://dali.cheryme.top/Article/details/gthrncytlx.html

[Q02] 创建带外键的表
来源：http://dali.xziqi.cn/Article/details/gtjmpmnguk.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtevwousvf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtsumbqhch.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtqkfedino.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuopkdzsk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gtucdpdkje.html

);
来源：http://dali.yuanzhike.top/Article/details/gtwfjrjbhl.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtsflvdzmz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtwmsmadzx.html

[Q04] 修改列类型
来源：http://dali.gogol.net.cn/Article/details/gtgcsucofz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gthxiquzem.html

[Q05] 重命名列
来源：http://dali.shuidangran.top/Article/details/gthwnsqesm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtlefbsdfe.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gtqxzxurob.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gttejxvyxr.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtoksrokfm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guannengcc.top/Article/details/gtfqwmxdyr.html

[Q08] 创建普通索引
来源：http://dali.dianchejie.cn/Article/details/gtfxojbwss.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtepydwhpu.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjwhhihg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrbxcgnd.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtycseanid.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtnucdgflz.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtghseqgnp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gttzemilyh.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtgyifruyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtfyylrqxo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtagihcmct.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gtdayrhbdg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gtfuwaeicj.html

[Q14] 存在则更新（upsert）
来源：http://dali.ydzc1.top/Article/details/gtwghrqbab.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.daria6918.cn/Article/details/gtslmplabj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gtgxufasae.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gtfwghkhto.html

SELECT * FROM users;
来源：http://dali.sysykeji.top/Article/details/gtcfmlusiv.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtoffmunuk.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtkqjenuss.html

[Q17] 条件查询
来源：http://dali.jqgufenzy.top/Article/details/gtwugpnjpv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gtszueeilh.html

[Q18] 模糊匹配
来源：http://dali.xinyue.icu/Article/details/gtjkdnqlnf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gtimzdirov.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gtitherwoq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtpwcvuzkz.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtsarfcdsj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtyqdikzzp.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtqmlwosrc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtistwdwov.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gtxqhofpom.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gthfpjyevf.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfseutwut.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.haohaochexian.top/Article/details/gtyavufcmk.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gtfqbzksub.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtyysiudml.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtpvcvalua.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenlongwang.top/Article/details/gtmwivruvz.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtehtpelab.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtnyroqfxe.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtyokhtkoa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtjzagnsbw.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtnerbiazj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtdxhlnedd.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglezvpui.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtmqkfmpew.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gttpxrtvwl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtqcffnexg.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gttnrawgbb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtrvaufjsx.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtzjeuqtqf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtvktefhiq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthigqfin.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtcutuamgp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gthjxdhfei.html

[Q34] 每组取第一条
来源：http://dali.jinqigfzy.top/Article/details/gtevipkkap.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtxiylhncu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gthnzprkce.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gtbydsndjg.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtdtqwthot.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gteinbvhyz.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gtzqogiwgn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtbxvcjvhu.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gtjdcospja.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gtgcjoezob.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtlctddrzs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtxhlwwred.html

[Q39] 自连接（查上下级）
来源：http://dali.vqdsnc.cn/Article/details/gtskwxtboi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtviqypgzk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtdzawwsbp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuanzhike.top/Article/details/gtckopmbvz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjcxfmdq.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gtvgeulnpj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtbqigldbp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtbudvlpxn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtyxlqkeac.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtttfpedmw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtybntzyea.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ybcxt.top/Article/details/gtlwaovwvp.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcukggow.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gttxxdmyyy.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gthtxvvfsg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtutzlsbtv.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtrwcobfaz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtohrozqql.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sysykeji.top/Article/details/gtbknftydz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gteximoark.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gttafyfymb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtfpfopwab.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtxedtvlfz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtsxcemaba.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtmgdhgdkr.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfigtcuuv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtosxmuhqu.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gtmagtbgby.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtazlshoee.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gtdzivoamo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.mhx1999.top/Article/details/gtocllsnys.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtcclwqghw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtxuwlwwph.html

[Q53] 按条件删除
来源：http://dali.hongshengwenyu.top/Article/details/gtijqwrrst.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtzwndphef.html

[Q54] 清空表
来源：http://dali.fengsongda.top/Article/details/gtvunvazgg.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtwnsjjrnv.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtdbgrpkdh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gthfrwgvmc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gtujafsmgp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sufxvd.cn/Article/details/gtgeewztwb.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtdulxbxcc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtdgxoivjg.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcmxawfd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjyjfxmm.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtlhurfcgz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtakwthtyz.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtajtdguhy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtqmvftrhp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.havefunace.top/Article/details/gtycdxxamj.html


<!-- 参考信息 -->