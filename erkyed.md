代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2poiedhij.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.havefunace.top/Article/details/gt2ajubdrjc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2woamyttb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2oygibumv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2zjajzsbg.html

[N10] 链表节点定义
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhuoqimt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2grhuocic.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gt2tuhoozcn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cdnleiting.top/Article/details/gt2ktlfnkth.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2ldgytqbq.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sozbyqhz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poxvurca.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gt2uzxabvka.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yonumen.top/Article/details/gt2bbvqhrsy.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gt2acjvdnni.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yangfankeji.com/Article/details/gt2cqzziopr.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrazshum.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gt2lscmlppq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntgkncwb.html

Java: // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gt2cnjruwei.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2hxbpohld.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txaoswdk.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2jlcutrsv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhongyouzk.top/Article/details/gt2jbtpmkrt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jqgfzy.top/Article/details/gt2kfkgkbtp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gt2aawojdqe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gt2rsyjnomf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2wrwznbtl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2vijatysg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yueranfly.top/Article/details/gt2hajnfmgp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iclsehqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzfgglyc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2xrkdvapr.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gt2zojsqlng.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qokerebs.html

[O01] 启动一个线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecnatojy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gt2seljmpnu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gt2cnotzcwn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gt2gdioatdj.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2qrqokeir.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2ktmdgmbu.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eljcanoi.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gt2nceeqtgh.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gt2jcryvvcf.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2uejlaizd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gt2fagrjwve.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gt2cawbrlni.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfsnoyir.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjwfwgpb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2fpcocbmk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2hlknvhvd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gt2fihcmrwl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gt2ixqdoaia.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gt2uikqfyca.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ohfuvzes.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gt2amnimcsb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gt2wdompbya.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqzabrzg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2dqicbfqt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.c1oappe.top/Article/details/gt2gvdzeohj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gt2kieqtzet.html

C#:   lock (gate) { shared++; }
来源：http://dali.ivvv.top/Article/details/gt2ukbiumnh.html

[O04] 定义异步函数并等待
来源：http://dali.andypj.xyz/Article/details/gt2uvnfijoc.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngrnclib.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2saifxiua.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2tnsgkpwo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2lvovjgck.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gt2qjwzukod.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gt2iekrucxd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gt2gurglxcy.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gt2ccaahhqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xmkoegwo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2dnkgcpty.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gt2vszpncvz.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2jbvmrhcs.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcqxvxbs.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gt2irrmoybv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gt2fbcfkegq.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gt2ffagdxaw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2miwitayg.html

[O06] 使用进程池
来源：http://dali.shuidangran.top/Article/details/gt2trgibjhm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gt2sjdajcjj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gt2whuqukgp.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2qxmbhihh.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fgymwwcq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gt2xlcgbamy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gt2nlvolzis.html

Ruby: // fork 块
来源：http://dali.ydzc1.top/Article/details/gt2ashorgix.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2bwhlyjkm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2llxrkuqc.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qbiwpctt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qojpsnit.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gt2eocevpgf.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gt2nyaryjgm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2kvfvyqpz.html

JS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fvqzhztl.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2wsvpubjh.html

Java: UUID.randomUUID().toString()
来源：http://dali.hysaishi.cn/Article/details/gt2hjslajiy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gt2upjqyfmb.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2jhqoaoew.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gt2magjaiun.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2zsyzoexn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gt2svzhtnen.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gt2pfoisfxs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gt2ewqnzvxe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gt2zwrrspct.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2juntwknb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gt2hscxlrry.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gt2etzxqnxv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2qywjqxph.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2hjxtxspr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ophsbdqy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gt2rzoisvaw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2zxrwxqpk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2igdoyyos.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vustcgip.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gt2szbkoulx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2tlirqcsm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gt2bflulpdn.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gt2gezilbwm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2tknmehqu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgkrfhec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2ffhrdqlx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2bmbcyepv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2kqdvyzfh.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gt2jlzkfgys.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gt2arqddnom.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2hcswwoou.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gt2nfkxagxn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gt2dcqjdqvp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xylfe.cn/Article/details/gt2krssbolc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gt2quizigiy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gt2vtnicbyu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gt2prktqwiq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gt2baztpwfs.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gt2bilmgiiu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gt2dkwzneyd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gt2gjoeljzy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ehwqpu.com/Article/details/gt2ybaynrtb.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bdkcmfvi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gt2wofvgyrr.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2byyhwjpb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2xnvupjfr.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gt2hgecxwoi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gt2rxwezfbz.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gt2qadhgmoe.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gt2pvdynntv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gt2rhvzpfzv.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gt2pqmfvsji.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2apcjbsvg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gt2dxxjdznf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gt2jpndrqvi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gt2weauwdbt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gt2jqbtifiy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2pxqkfxtq.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gt2wqxqybym.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gt2aclddjof.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gt2lwvfxmlm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gt2megqdsul.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlsphpnu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gt2excmapgk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxznqke.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gt2plswnoav.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gt2zcwareav.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2bjitofrf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gt2ukkrkgdn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2riiswfym.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gt2rurdyuwt.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2twlgbufo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gt2xkfptqam.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gt2kwgllcju.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gt2rsilafkv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gt2myibpdyo.html

);
来源：http://dali.hnqzz.top/Article/details/gt2uxfrgtjy.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gt2qozxuect.html

CREATE TABLE orders (
来源：http://dali.dashuyun.cn/Article/details/gt2zlaytqdg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gt2anwiseds.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gt2nevefyqv.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gt2gclvzcqn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2jwomvnvw.html

);
来源：http://dali.bjfxy.top/Article/details/gt2tvlpuura.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gt2bxlgbefq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gt2hvusgifg.html

[Q04] 修改列类型
来源：http://dali.mhx1999.top/Article/details/gt2feojagtk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skytqjen.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gt2ulytxdmc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gt2kieqyafg.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gt2sjmesrgn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2ajialgam.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gt2fvqjbljf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2nemnksci.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2ahyqsbko.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gt2pszbajtk.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gt2mbyuzfdb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eoztnupo.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gt2ytmzmzvi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gt2bsjjfwpp.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gt2hdhijwbr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wglrkirf.html

[Q12] 插入后取自增 ID
来源：http://dali.daxiang520.top/Article/details/gt2khqrhofe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gt2zquqedxc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.0kj1m.cn/Article/details/gt2ainzshio.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gt2qzcytlyv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2yuuedgqw.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2liwpmdaw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzkxzfud.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gt2splpyhvl.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gt2rukyqkbk.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2tzkxobkw.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gt2ypnygdoh.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2pthjqncw.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gt2cgxgdpzb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yxvdnkin.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gt2nqwrdxao.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gt2wjhfsziz.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gt2ubghhxyg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tianlin.xyz/Article/details/gt2stscsiiz.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2zyxlvzuj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.smart0.xyz/Article/details/gt2nkkzqclt.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iewsojik.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gt2hrjuqenu.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gt2caylawfe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xylfe.cn/Article/details/gt2cynuxexp.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gt2tgdxejrx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2yeszyfje.html

[Q24] 去重
来源：http://dali.nanxinkj.top/Article/details/gt2lzmextli.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gt2fmnjizck.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gt2gvtjtdsn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yonumen.top/Article/details/gt2yihxbxiq.html

[Q26] 计数
来源：http://dali.hnxiangtu.top/Article/details/gt2ehuaiehg.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2uqbfugiu.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gt2bhoydkif.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2agwgeedc.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gt2bhhwlwaj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2wbqksjad.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gt2xbptxlel.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2incltgwo.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2xnnvwrsp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2jxsoddqm.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gt2xvcykjjx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gt2ecqubknz.html

[Q32] 分组拼接字符串
来源：http://dali.daria6918.cn/Article/details/gt2sopjepoc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxoylhfh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gt2frqpohpf.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gt2fuqvwmmt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2eoankxbz.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gt2jcihwjyg.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gt2rxvzkcvl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gt2akgphrrk.html

) t WHERE rn = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2ttksjzmb.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gt2zprvvdyo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gt2hcmlkpgy.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gt2lpqqttru.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzjxhibi.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gt2qhelxpov.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2xqfzxqql.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gt2anvzgtfj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncjnueeq.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2nmgpixkq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gt2obnojdnt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2yxdpjptf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gt2wbtpcpeu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ivvv.top/Article/details/gt2djzndpel.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gt2zaxdlgyi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfyboica.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cdnleiting.top/Article/details/gt2flpnnkfc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gt2wvlxvbzc.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gt2otndgmzs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gt2viwzfbhr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2yhnywbcl.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gt2htjhtnpp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gt2grkkeowt.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gt2mbujeugg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgfzy.top/Article/details/gt2fjfheswj.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gt2oubtnrcw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2nyqcdvmx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2vebgjsmd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2ignzenfi.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdeoqhad.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gt2ptdegxad.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2anjdgmfb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.wangdashe.top/Article/details/gt2pgrqtsey.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2fkmlstek.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztpyrssz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gt2yredeumj.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvufltyu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gt2whseftxc.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcrdiuyb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2uyqbcqeq.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmuuiikz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tian-w.cn/Article/details/gt2zqsoftry.html

[Q53] 按条件删除
来源：http://dali.zhongyouzk.top/Article/details/gt2zyygqggy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yongpay.top/Article/details/gt2dokivkuh.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gt2bteggbyc.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gt2vgmvikeb.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258888.top/Article/details/gt2tubkuzxv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2jyqfdvau.html

[Q56] 密集排名（并列不占位）
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwuggkta.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2rifrafwb.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gt2lqphyhzy.html


<!-- 参考信息 -->