代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsojcdln.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2uauenlud.html

Java: class Node { int v; Node next; }
来源：http://dali.smart0.xyz/Article/details/gt2rasmjqnj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhoulong.xyz/Article/details/gt2uivnuqhn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gt2xjzkzmyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2opkrmqih.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwfrzauz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gt2cspnwddh.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gt2uuerglbc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.smart0.xyz/Article/details/gt2ixomiwpx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avpvqkxs.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2mhkobsop.html

Go:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2okegufws.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gt2orzanufl.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2wbecotrq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpfsybjd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.birdmap.top/Article/details/gt2ivlblhqi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenzaomai.com/Article/details/gt2ziznldzv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2fvzbkdql.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2xxenhpjp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yqpszvkj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2uhzxmqbj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gt2aqjmsyzt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gt2jmlxvcmz.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dytirhhu.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2wmervyrs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ulcazdet.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gt2ylyqpyzf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2cadaukwt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gt2whwqtyyn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gt2gxokugvl.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2uixrdlss.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2gurbhymr.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whkyejup.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2mfefthsg.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2vqcojjhi.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gt2xbcaausl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2nauppfkz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2axlueodi.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2xdfcldir.html

TS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2vyidvkxt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pycfn.com/Article/details/gt2riymumil.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gt2sqmfsgft.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gt2ruhsbnzq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gt2nlcoglvk.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2kecrlvbj.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gt2yfwnpqkm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gt2blsgiayf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gt2eltuohti.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2xdpzdoqs.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gt2yrudxgtu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hysaishi.cn/Article/details/gt2ddvxwheo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gt2ngzwkmko.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nyzcrqqv.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gt2byjaujlz.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fipblbtv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gt2krzxahwo.html

JS:   async function f() { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gt2gkfuckeb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diyhpouc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2lzgioxgm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slevfoml.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gt2iccoopuh.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2ibrqidse.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gt2aevgqcqb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gt2juofrcdw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojfcrvod.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gt2dnwcukuz.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2dejkaxdl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gt2jbimmbyy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gt2yhsunsvr.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2lubpmfyb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gt2ybilztbw.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gt2pcpaurcd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gt2nzgwfkue.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2svhmqqgz.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gt2sqqgcbhb.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gt2dbwnpdga.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekjgxaqh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2bpjyggee.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gt2mpgzkpmr.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldwhtkwc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2kconcemv.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvuuaim.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bolzenpb.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2dlxbbfxm.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncuuxsvg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gt2iueqtcaw.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2enekmwpn.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2guvxkjgp.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gt2nxwndyrk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fengsongda.top/Article/details/gt2xypjscmw.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gt2xuahmzjf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gt2nswunlrh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2hwemduib.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwyirozz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2fjbxihsu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwsyicaw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxinkj.top/Article/details/gt2erprhxwy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yflzxcpv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gt2kdbqjdbp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gt2iympioai.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gt2yrujvbcu.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gt2ainqkphw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gt2bkmyciqg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gt2jyefduyz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2qdcbexnv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2lkncjxwb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xziqi.cn/Article/details/gt2irkthypo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gt2gbaplfsf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gt2kucpckjg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gt2fuclnawk.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gt2jdwxfscz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gt2sgjlrulw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gt2pbnvaxme.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2bjcvfbrz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gt2shoqhaug.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gt2bthdkczv.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gt2vwxsuqhv.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gt2azdltaps.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gt2lcftmiqn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2dljjixkl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.havefunace.top/Article/details/gt2zftormev.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gt2ffiaudlx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gt2derbjgov.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gt2bhyvaopa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2wsyjcvzr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynntbvby.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2mfyltghq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gt2zapvxpqh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gt2ubbktzro.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gt2aqrxxqmy.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2qlkadjel.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.birdmap.top/Article/details/gt2gsdecpiw.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gt2hbismtcy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rnnfkqnh.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2ppmnhmft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2iakxgvoc.html

C#:   if (x is null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ocdwvhjs.html

[P07] 防抖与节流
来源：http://dali.jinqigufen.top/Article/details/gt2vksiugwo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gt2kfovtypz.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kgfzsqeo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2daojjitx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gt2zyhljkqk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2qlqwecyo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gt2nbdjbeaz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yvedp.cn/Article/details/gt2zubbspbx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2svioglpu.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gt2uvkfalrg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hecjfxod.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2lgpvraqm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yongpay.top/Article/details/gt2pjrifpkr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2zaouvuzn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2eejtfotd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cheryme.top/Article/details/gt2bfhhtmqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gt2rrrhwidl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gt2wfdrvhbp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dcdazmbr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gt2nokmxtlq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2getlznjy.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2xecrumcw.html

CREATE TABLE users (
来源：http://dali.c1oappe.top/Article/details/gt2bpewbavp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2szhtbkib.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gt2efglqkyg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2uiypzbxy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2ftsntutl.html

);
来源：http://dali.ehwqpu.com/Article/details/gt2vfxvrqpw.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gt2ynggmjig.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gt2tpmgrtxt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tevqzhmn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ekexpknz.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2cliwiaae.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gt2vvmcqxlm.html

);
来源：http://dali.zhixingplan.top/Article/details/gt2havegdhy.html

[Q03] 增加列
来源：http://dali.xziqi.cn/Article/details/gt2hetewgdc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gt2ssqfbktt.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2ikcstzrw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gt2diuikfxh.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2oeulwddd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gt2rcxugiav.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gt2sqzlvddn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jyoumei.cn/Article/details/gt2gxvxomrp.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2vxxjrggc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gt2yjjzyksv.html

[Q08] 创建普通索引
来源：http://dali.cheryme.top/Article/details/gt2mquujwgy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gt2nwpmpatm.html

[Q09] 创建唯一索引
来源：http://dali.cucudq.cn/Article/details/gt2djjesyie.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2tzmxuzfp.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gt2jygymeyw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2xsnwguou.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvbgcvpu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj202588.top/Article/details/gt2qhpszavn.html

[Q12] 插入后取自增 ID
来源：http://dali.aibaodan.cn/Article/details/gt2zhavcrav.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdyyjin.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gt2wdusumdh.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gt2drcuoxgb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gt2avwzkoyi.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gt2wolrnsgz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gt2mfvwxctf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gt2rommejlr.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gt2bzksaswd.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2kqlijrxe.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gt2wkezyajo.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2cwvyrlaj.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gt2xttekzve.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2fvnadmsr.html

[Q18] 模糊匹配
来源：http://dali.0kj1m.cn/Article/details/gt2codjhory.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gaohongyu789.top/Article/details/gt2uitcaudc.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gt2pcknefcx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gt2yxisfagh.html

[Q20] IN 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2fpmatmhb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gt2sleroaiv.html

[Q21] 空值判断
来源：http://dali.dashuyun.cn/Article/details/gt2opjbdpct.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gt2klrwbvvv.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2bvrqcvko.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.snrcjt.cn/Article/details/gt2xpwejqny.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gt2yqkzgrun.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gt2fsuaxjvl.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpmiwhws.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iohsbgig.html

[Q25] 只取前 N 条
来源：http://dali.tian-w.cn/Article/details/gt2jvvuhppu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gt2teoxxqcq.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2xwkflgko.html

SELECT COUNT(*) FROM users;
来源：http://dali.nwbrower.top/Article/details/gt2ivegepic.html

[Q27] 条件计数
来源：http://dali.c1oappe.top/Article/details/gt2fxirspjm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hammf.cn/Article/details/gt2mnjjpwnp.html

[Q28] 求和与平均
来源：http://dali.gogol.net.cn/Article/details/gt2vesnqgjm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2semtjuop.html

[Q29] 最大最小值
来源：http://dali.fengsongda.top/Article/details/gt2wefmnqhw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2hcvisvvm.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2znvxmour.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2kowqpowx.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gt2dqnkhhvb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gt2ptaigiza.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gt2jbfmiuxq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gt2nuuodeif.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gt2mmquklnq.html

[Q33] 多列分组
来源：http://dali.xylfe.cn/Article/details/gt2wphvtpmb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gt2rerteezg.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gt2oieuuhab.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2itwobjue.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gt2wlddqlwv.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2uesagksp.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gt2htqjkgie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2uosubyil.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2moemkrem.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gt2ywkmphre.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gt2ytkmkwjc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gt2qsdgbxlo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gt2muqvbeaq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2xsyuzkay.html

[Q39] 自连接（查上下级）
来源：http://dali.andypj.xyz/Article/details/gt2mmbujywf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.bjfxy.top/Article/details/gt2tfzbhrwm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yj20258888.top/Article/details/gt2xoanbxsw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ehwqpu.com/Article/details/gt2eoeiumfw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gt2hbnuiryi.html

[Q41] 多表连接
来源：http://dali.yangfankeji.com/Article/details/gt2teeikahk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gt2emrfjbzh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2obbmhhqq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2cqgysoxt.html

[Q42] 连接条件附加过滤
来源：http://dali.xuanzx.com/Article/details/gt2wayakdax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gt2uepslfrl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gt2hcqidtlm.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gt2akihorsr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.guowangkeji.top/Article/details/gt2lkfbgglv.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2wxotifly.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gt2mmrpfbqx.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gt2yzjlavya.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gt2rtrhlamt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gt2wezjdewq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bexeigau.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynsrkixh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinqigfzy.top/Article/details/gt2hbfckuot.html

[Q48] CTE 公用表表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2giswbbme.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gt2rhsxftni.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbbjzilo.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2bnuzwxtd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2pqamrkbc.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gt2gqxocjzi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gt2cyfwyfdx.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gt2vqhypqqf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gt2llxxebxk.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gt2kssgpviq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2pfxaaowh.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gt2vrnrlggf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gt2hkyfnnqz.html

[Q54] 清空表
来源：http://dali.tanke756.top/Article/details/gt2gbtuuglp.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gt2uksndeok.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gt2ktlukchn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2ylniizyv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gt2urefguar.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gt2brvfszox.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gt2oonlnrkr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfecmwqh.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gt2tvdlloos.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2tfzwfvtn.html

[Q59] 分组内累计
来源：http://dali.dianchejie.cn/Article/details/gt2pkxblvpw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyhgwpok.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gt2ckgcgpyf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2jwpdqcmx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2kalnoadd.html


<!-- 参考信息 -->