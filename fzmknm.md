代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sysykeji.top/Article/details/gt2dmlreovn.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2ojqpthoc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gt2doypqdbe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gt2twfqbphg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gt2zxaxnmki.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2zsoqipiu.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2iiqauioc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxinkj.top/Article/details/gt2gwhktmme.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gt2emnsalyt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gt2joiwdgpt.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2bfqudoea.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2iesiduos.html

PHP:  // 手写递归函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqdusvep.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2faokkevi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gt2tpecxape.html

Java: // 手写递归
来源：http://dali.gzhubu.top/Article/details/gt2xkrooqnv.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2mqpnprac.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jlsjyb.cn/Article/details/gt2pbltasrj.html

C#:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2fqukhixv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tanke756.top/Article/details/gt2wajcdjju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gt2hxosbktf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gt2umyxbhnj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gt2hmiufomu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2jjljsgtp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2obwrwhyb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2ihqctxmb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2pzizvabp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2grywobsn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2yplyvmdl.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gt2pgolwbhc.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiqwdqpz.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gt2dzhtanej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gt2uqzmahjf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gt2ucmsfyms.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2irxeazss.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gt2bfvarqtx.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2vhirkebq.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gt2jfefhasm.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2qumafjmv.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gt2vyagglmf.html

[O02] 使用线程池
来源：http://dali.fengsongda.top/Article/details/gt2sfpjiqfl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2cnythmwi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqcgypdl.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gt2onaefmaj.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gt2gwxxjtau.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2qrhzydjy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.kuanghao11.cn/Article/details/gt2nwboarqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwlmcawo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinqigfzy.top/Article/details/gt2pjkgrplw.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gt2scevhgwr.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2bdjtlcwx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gt2uqoshafc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pengpengdd.cyou/Article/details/gt2yklhbfek.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmoolagn.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2imozrhrq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gt2fvowreth.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2knlngcoc.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2kkanjqys.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gt2qqfijzxv.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gt2ukbxzryt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangdashe.top/Article/details/gt2fnqgromd.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2dcshafyw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2neyivwza.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gt2rainalhy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.kuanghao11.cn/Article/details/gt2iazarkkx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2dksuadzl.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgfzy.top/Article/details/gt2kyjqkvzt.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gt2qhlawhpd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gt2txvtoewx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cucudq.cn/Article/details/gt2rjfmuqlj.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gt2gopkwakf.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2fqsytfra.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gt2yxpwwizv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gt2jlqewdsv.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2spljkeyt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gt2lphjgenb.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fniejfmu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anvtczzy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gt2lhkxpdkv.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2mzqjzrfj.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcvygwkl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylcegmzh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gt2kefuanri.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gt2toizhqjd.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gt2tohpbkkp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lilgkdoz.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gt2cfpsujzv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2cgdpsoan.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywdrjpsj.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gt2afxkstew.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daxiang520.top/Article/details/gt2bvhneykg.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbgkfkvq.html

TS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxlcsbny.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2aazvvjts.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxinkj.top/Article/details/gt2mbxinemw.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2wfltfilz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gt2smzjlxnt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gt2rekjmjlo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqdigpvj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2gwolnfmj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gt2uzapwrnk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj202588.top/Article/details/gt2hojciofq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gt2govlolda.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gt2rrgpkztc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkzwltfg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2ekagujhy.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cndbekcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gt2tttutncl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangshuangyany.cn/Article/details/gt2krhqgebl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gt2ukoezgnx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2hckmtscr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2fmoigexv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jianghu66.top/Article/details/gt2noplcklg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gt2rweavgrv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gt2gcjvehux.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gt2zxzzkane.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gt2yxmfzizl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2xmtoigzj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gt2bqjmocie.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtgdalyh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gt2ehpfdkmv.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2ywfqvkuw.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2rmavsdrz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2zqdybzpn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gt2wltdinhg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.bjfxy.top/Article/details/gt2nukqwdwt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gt2dpnoulxp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gt2jpqpeofr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnevwinw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yanxiufei.cn/Article/details/gt2dlpxaxjo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2lllbdocz.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gt2orsmzsfu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gt2gzmfbxgz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gt2tdafrjij.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gt2ybhkgsxc.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gt2lzoujvig.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wiulawsy.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2rowumsuf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2kjrsvtyo.html

Go:   if x == nil {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxahhzfe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gt2ypyokykf.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gt2srdthcvc.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2uxcqqeww.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258.top/Article/details/gt2qvbkwvko.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gt2koofoish.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gt2eqniuppw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gt2nnypvzdk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2ycpzkaaq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gt2fpdliiog.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gt2kajdttol.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gt2yuhdonsr.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gt2nlsqhqao.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfczgvaw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gt2geyjiovd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gt2kfgqmnsu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2ntfjnicn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gt2kvaeuozv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qssvemzi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gt2yttyunwk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2uqukoydx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2debtpyaa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gt2syedzzfg.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2wlgilkzu.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gt2vmascixl.html

CREATE TABLE users (
来源：http://dali.tianlin.xyz/Article/details/gt2oyfvkgul.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gt2ktdvboka.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2qgfrmxsg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2qrdvfnev.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2sfygwwfn.html

);
来源：http://dali.wangdashe.top/Article/details/gt2wwlktmgd.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gt2mzrxedph.html

CREATE TABLE orders (
来源：http://dali.hnxiangtu.top/Article/details/gt2ztpusijj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2csxevmsm.html

user_id INT NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2ozcvqqbn.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gt2lwajoxkx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gt2rkscoiny.html

);
来源：http://dali.zhoulong.xyz/Article/details/gt2kmczvnjb.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gt2fegjjlxx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2claeafza.html

[Q04] 修改列类型
来源：http://dali.xylfe.cn/Article/details/gt2acnqikvz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gt2fchjukbw.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gt2ewritdir.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gt2ufbgatry.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gt2xqaaeuqi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gt2uurzjvfr.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gt2vtmjveab.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gt2rwlesutk.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gt2bvyiztpc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2bbcbhfgi.html

[Q09] 创建唯一索引
来源：http://dali.pycfn.com/Article/details/gt2tnmnsvow.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2gvrekkpd.html

[Q10] 插入单行
来源：http://dali.cashguo.top/Article/details/gt2oqyogdro.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhongyouzk.top/Article/details/gt2jwfqzdqo.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gt2dymjckhu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gt2cchuzakc.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gt2gguzehqp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.dashuyun.cn/Article/details/gt2drqklggs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gt2vzdfuffx.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gt2hvlnkdnr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2xlbkxgpz.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gt2shgsjgeb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gt2fzafittn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gt2epdxusvs.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gt2ezlniesx.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2mzpdjjzq.html

[Q16] 查询指定列
来源：http://dali.dashuyun.cn/Article/details/gt2cegetkzc.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvtxyxtn.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gt2zmrmvasw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gt2apkisnyu.html

[Q18] 模糊匹配
来源：http://dali.xziqi.cn/Article/details/gt2syicevaz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2mkapcrkn.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gt2dlistwzg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cdnleiting.top/Article/details/gt2dfiyadeq.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2wiynsvbs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gt2amjwihhp.html

[Q21] 空值判断
来源：http://dali.jinqigfzy.top/Article/details/gt2yxuvfhmt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yanxiufei.cn/Article/details/gt2tdqtiitt.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gt2wyqhcdkn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2ydihujrm.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gt2otfsnzfr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gt2dqgyctte.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gt2ovuvgrqb.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2axehzfoc.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gt2mkumltlx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gt2atyuymod.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2onriabex.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2ytfvaxyd.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gt2thgwwspr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ymrppdim.html

[Q28] 求和与平均
来源：http://dali.hammf.cn/Article/details/gt2obrcwvdq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gt2vjzyldyq.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gt2qhysadte.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2vlfnsbjf.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gt2fnkqfkjf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2mrxcufon.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2paqrxjsv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2uchrknje.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujfpqcwv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gt2ixkwvrfy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gt2nwgpttzm.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gt2bsrljrgv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuxming.cn/Article/details/gt2envkygvu.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gt2lzikuqwp.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gt2dvjwjgyv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gt2rkgjdmxj.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gt2aikfwfdn.html

[Q35] 内连接
来源：http://dali.kuanghao11.cn/Article/details/gt2dnbvotou.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2fnlbtdml.html

[Q36] 左连接
来源：http://dali.dashuyun.cn/Article/details/gt2isgqppbz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ovutpemg.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gt2bsvhsjon.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gt2svweljtv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gt2fkxnneaz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2nimlajrf.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gt2nzkhvekf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gt2vznetkvw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gt2gcufogdo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gt2dyztuwqr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gt2bphfxpwn.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gt2lvbuvnij.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gt2eupubwkz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gt2iiwexfnp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gt2gdsqjjhv.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gt2nzdeubrr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoaqzul.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gt2jxdxlhpi.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gt2kpihwdxr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.fengsongda.top/Article/details/gt2afdlrvtx.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gt2wcguikmv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gt2ftimgvcu.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gt2nwgfwddl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2wvdsgjuw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.haohaochexian.top/Article/details/gt2vwzydvtt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gt2pvmqmghs.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gt2fpnzkmrq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gt2msyrzzgv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhixingplan.top/Article/details/gt2glntawui.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gt2gtwmetrw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gt2lfcbiidr.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gt2iijtvjrp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2pqjeettj.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gt2ucvcwfoo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gt2ywmykfgz.html

[Q51] 用子查询更新
来源：http://dali.zhengqikj.top/Article/details/gt2hwgyesvr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2pyuixxxu.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gt2muztlwxg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2idebnjeu.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gt2xpnyxmef.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gt2xhtatbqb.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpqanyin.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gt2vvoqyzlv.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gt2mnlwrecj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gt2alzwffsy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2qlxxpthv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gt2chxbkncb.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gt2ixvxvjit.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2xbuogcvp.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gt2iglevywf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2qbhtxkrd.html

[Q59] 分组内累计
来源：http://dali.cucudq.cn/Article/details/gt2lnjhnrxm.html


<!-- 参考信息 -->