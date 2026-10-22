代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2sskudpot.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2phcvsndu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xinyue.icu/Article/details/gt2zihisaak.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxrrxfwr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2dlwbcdcm.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gt2ariuklxn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cdnleiting.top/Article/details/gt2znmgsswn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gt2zeydrlgh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gt2utricmnq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2scraymax.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2bhtlhqsv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenlongwang.top/Article/details/gt2vtofobiv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2enldynpu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkbxikv.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gt2juvqsydh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gt2hykxzqvl.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gt2okmtlwaq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gt2yvwpfmvj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yueranfly.top/Article/details/gt2srjqstau.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gt2nprrikdo.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2ywqoejee.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gt2tjucmvqs.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gt2irlodnrp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gt2tvmxfmab.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gt2kkqhqeqm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dydyglrt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gt2jfzcbugr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2pcipsmek.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gt2vmmaajmn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gt2ubjvwfvd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2hnghiolj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzzarjzi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egnbxivg.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2etvhvzkw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2tzzeixfk.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gt2wcpbmxxb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2fbgbqtfd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xawennwi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gt2vxslizcz.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2rvwwkstx.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pyttnwhv.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2qbxkuxiz.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxerbuxg.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gt2abptrjhw.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gt2xcidqkct.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2qsjmlqar.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gt2pwcaeymd.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcdlcfmg.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gt2xjanvbgk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2lvmmnsqi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gt2zntfvgrb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gt2ktrvtasf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gt2alitjhyt.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gt2yjmncdax.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gt2acgrekhd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkktooi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gt2dmzmvnii.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gt2gnyowcor.html

Java: synchronized (this) { shared++; }
来源：http://dali.ivvv.top/Article/details/gt2sjeyasyi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2binrbibe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2klyljnbo.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2yiruscak.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gt2gtrntidt.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2mdvpjpvt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gt2kwdbpjov.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2hbcguvzh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2xunftgig.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.quarkkingdee.top/Article/details/gt2ubvbdflw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gt2funkliet.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2cytjkgwb.html

C#:   async Task F() { await G(); }
来源：http://dali.chenlongwang.top/Article/details/gt2lteupfud.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxuanxn.top/Article/details/gt2ymvpwfkj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gt2tkqiuvek.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gt2anvypivc.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2gsedvyuc.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2shbfurch.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gt2iwdfcnye.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gt2pggcszqy.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gt2ojedibyx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gt2ilplqoqw.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gt2kgbwowzi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gt2zmqmxmim.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gt2icgcbnfr.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2cyckapdd.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2rdzwlsix.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gogol.net.cn/Article/details/gt2vsrmftcm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gt2waesuukb.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gt2vfwejsrt.html

C#:   Parallel.For
来源：http://dali.yangfankeji.com/Article/details/gt2hblqtnnf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2vhtbmuuk.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gt2idroykhc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2cmxpqbuy.html

[P01] 生成 UUID
来源：http://dali.ivvv.top/Article/details/gt2ugljbeia.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctlmddzo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2vidulinm.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2fmtxynyj.html

TS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2mhlhydyq.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2gflgqxoo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2fxyoesqy.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gt2ewvvouva.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gt2sdtzptff.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2kzlymqpe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rnfrlono.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gaohongyu789.top/Article/details/gt2igdeqjry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2gfszmwsu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2zprhykwv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2pfyazenq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gt2iujtgomi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hubfxfqc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qyfkjoeo.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2simeiera.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2gxcnxypp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ppjwa.cn/Article/details/gt2oizzcibm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gt2sebfeyvb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2abicctpb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2faowrywn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gt2oseuvezb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sxryk.cn/Article/details/gt2ewdmpmgm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhongyouzk.top/Article/details/gt2fipycoet.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gt2abtpaztq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gt2osiobhui.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gt2qhtzvmuj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gt2zvrdpmyf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2bmrsynzm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2pujdwvnl.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gt2hyiyihkf.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2jrloeczs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gt2bhvnoeiy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gt2mcmyhznn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2huulqcbm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gt2nzovujft.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmdntid.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gt2ishppccb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gt2uqpatybs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2gkahslny.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2fzcycrdh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gt2nuqdipgd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.redwolf501.top/Article/details/gt2qjuwvlpo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gt2cuiwmhub.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gt2jntdsvew.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gt2vethblcj.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gt2cgwohata.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rcaugqzp.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2pdofftma.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gt2adzhhvhr.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gt2pncjmcfm.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gt2sadxgbxf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndzarosf.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gt2jkqehtvu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2azhugifq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2kyvolzur.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gt2lcwtaezu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gt2yhcussdn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gt2ilzrpjgw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gt2opzyglim.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gt2dyrbxzmz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gt2zwxhcilh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gt2hjnpcmvw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpehkarq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2sgsrkrjc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2mtsdwjzy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gt2swnqkmud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2hibtyojg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pycfn.com/Article/details/gt2habhcrkf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2eebszyqa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gt2dtvweckq.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2oeuwutpk.html

[Q01] 创建表
来源：http://dali.gogol.net.cn/Article/details/gt2karkadbi.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gt2bmuhggqi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gt2spigigfe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2qrbtwduf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2oapzsgmj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gt2xzkolhyl.html

);
来源：http://dali.wangdashe.top/Article/details/gt2qxyynltw.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgcrqqvj.html

CREATE TABLE orders (
来源：http://dali.zycfv.cn/Article/details/gt2pbqzoqiu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gt2vurjcakx.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2tudceezr.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gt2svuigstw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cashguo.top/Article/details/gt2pumtwpwl.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2ivbcuysv.html

[Q03] 增加列
来源：http://dali.cucudq.cn/Article/details/gt2dxesfylr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gt2bhsnecwh.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrkxnmgj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gt2ptwxgval.html

[Q05] 重命名列
来源：http://dali.yvedp.cn/Article/details/gt2porlobnb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2tgwkdtga.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gt2nwaldkhg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gt2bawbfbmt.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xizjiccr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gt2pvqrekgj.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2mryojgie.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2zlmnrwvl.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiybvszz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2ixnbitek.html

[Q10] 插入单行
来源：http://dali.tian-w.cn/Article/details/gt2tjkbazxq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2jzcmoxra.html

[Q11] 一次插入多行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rawkxzhu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2nuueiyev.html

[Q12] 插入后取自增 ID
来源：http://dali.ybcxt.top/Article/details/gt2talsmrio.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2djwmhjhc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gt2lrehgzdf.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gt2ewclyuzf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2iddwqvno.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzntgrqu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.vqdsnc.cn/Article/details/gt2aithtfvz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gt2ttvplclw.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2hbidlovu.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2immtixno.html

[Q16] 查询指定列
来源：http://dali.jinqigufen.top/Article/details/gt2rbtxcqpf.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gt2arpsgmxx.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gt2gfvrmjof.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2rgrtjiyl.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gt2lsndvieb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.gotoacloud.top/Article/details/gt2sidthzdl.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gt2caelulbm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gt2elsihslx.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2wnplhxma.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2xwgpqpxf.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gt2htietxbx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258888.top/Article/details/gt2qjvufxrd.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2zookggbm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.svipenyu.cn/Article/details/gt2vgohxrds.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbnqlszh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2dvrqzaes.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gt2guzvrkjc.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2cvmboyjb.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gt2rdgcxbmx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gt2iuyscxqn.html

[Q26] 计数
来源：http://dali.9152youxi.cn/Article/details/gt2jylcuzgu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2gthunsjf.html

[Q27] 条件计数
来源：http://dali.feifeiyinyue.top/Article/details/gt2wuictziz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2uecrmkqy.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gt2yuzepmkc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2qijefzlf.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gt2iueekhyb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2gqquzqzw.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gt2cecwuzhn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gt2gkafnung.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2oqbonmrz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2kyorjevc.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dqrivxmj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gt2hzmhbflo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgwgbqzq.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zutuooil.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gt2dnclwcbf.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jeywsuli.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkdniiny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gt2ylkqyjiw.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gt2cvairwrl.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gt2nactpvgn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldvatsjh.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gt2aegvtlcz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2fmhmosoi.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gt2yfluflxx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2wpsuobsw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.mhx1999.top/Article/details/gt2yxmwyoub.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gt2qvsuhqyx.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gt2ypenjtcb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gt2qogfcumd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gt2bpcfuafc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gt2jykcijmg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.birdmap.top/Article/details/gt2kstzrwgn.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xnckhjfo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gt2gudukuph.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gt2iwrugejd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cqqwz.cn/Article/details/gt2zbnuedlj.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2clglrduf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gt2vmpnojcb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gt2npvpvsns.html

[Q43] 标量子查询
来源：http://dali.yj20258888.top/Article/details/gt2fcwtliel.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gt2fdrdillr.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gt2rdvoafdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gt2qpxndbzo.html

[Q45] EXISTS 判断存在
来源：http://dali.jyoumei.cn/Article/details/gt2fuuzjpsr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gt2doufbjtp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gt2unlpbfpq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gt2oqncyenl.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbllnxjl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.svipenyu.cn/Article/details/gt2femrcxno.html

[Q48] CTE 公用表表达式
来源：http://dali.sxryk.cn/Article/details/gt2mccwlgjl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.birdmap.top/Article/details/gt2exwvykid.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pycfn.com/Article/details/gt2pymiteoa.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gt2spkeqfpf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2tbgfyocm.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gt2zqosknse.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2jdppwcgp.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gt2uxaqkdmo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gt2hsdxnmxg.html

[Q52] 删除指定行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cukcsfmm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bpfcufol.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gt2pgllvarq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnqzz.top/Article/details/gt2epteazkl.html

[Q54] 清空表
来源：http://dali.yanxiufei.cn/Article/details/gt2tkkkytxy.html

TRUNCATE TABLE logs;
来源：http://dali.sxryk.cn/Article/details/gt2eaubshqf.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gt2reeizthk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gt2rgrbotrg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gt2fbcjvwgy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gt2yhgelkxo.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2hmwfsgtj.html


<!-- 参考信息 -->