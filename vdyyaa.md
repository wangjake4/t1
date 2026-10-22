代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2djtczpuq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gt2iamovaas.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sitqhkxh.html

Ruby: a.gcd(b)
来源：http://dali.sysykeji.top/Article/details/gt2wbefpwqf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yongpay.top/Article/details/gt2xrsdezgg.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gt2aqpwmzod.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2oyinatgi.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gt2oneovcha.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2izyluayk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2qfxigoht.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.bjfxy.top/Article/details/gt2arfhsrfj.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvpzqgjf.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gt2eatnnyto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gt2gowyjuzt.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gt2fwrasbtp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gt2xzvgrngl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2rhlwjqoc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gt2qrfcnyvh.html

TS:   // 手写 Map<string, number>
来源：http://dali.birdmap.top/Article/details/gt2zhbatxou.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2otkfwiaj.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gt2fcicqxja.html

Ruby: // 手写 Hash
来源：http://dali.tanke756.top/Article/details/gt2cytteoph.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gt2knvdhvwr.html

[N08] 生成全排列
来源：http://dali.wangshuangyany.cn/Article/details/gt2avvtjvad.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2yftusfku.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2fcwytxmf.html

JS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwgazagu.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2ossznfbw.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2dnmgdveo.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2vorwtkxc.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gt2dwipuvpu.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2dutettoy.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2fndyslax.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2mccwdviv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2lrssmdnd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnntypbt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gt2htghivrl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2bedhfmuo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gt2zjacazpx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2glqegqit.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2tchshwrt.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gt2puwqvucy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztdmhhym.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yueranfly.top/Article/details/gt2fncrzrap.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gt2azzuytcp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aibaodan.cn/Article/details/gt2lwcuvvvf.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2flnnnpul.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gt2iavlvvrk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gt2bkoofecw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gt2mnjiuwan.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2obdbgpgb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2kzpewblb.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2oajaykce.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gt2biojlypp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2ocwzxjta.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2zzcbywso.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2zedphxwo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gt2irhpxdyx.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gt2hsawvzhh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gt2syhdtlzi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ehwqpu.com/Article/details/gt2fclktxlv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2iozspbdk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2qddnwjdu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbufyntv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2nrgnbzwz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pycfn.com/Article/details/gt2thliywct.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gt2jkhonops.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2clnjufcb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2axmifihb.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2irbyvggt.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2yxlkebhg.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gt2wvbfvhka.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sufxvd.cn/Article/details/gt2uoolxxxg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gt2zkrlxeww.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2hbrgalqf.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gt2mtjvnfbq.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gt2zqakwxlp.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gt2ngmfranm.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dipacksn.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gt2ghvziyrd.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gt2vqemgxlc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2havijmpw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2omozsnns.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2ajbwftki.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gt2jujgueji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gt2pkedcrxr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2eenltxvt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gt2whjkaask.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gt2trmhifnc.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gt2piebsvnz.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gt2cgghycic.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gt2xtvirwcv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gt2cocyeeov.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gt2xqoxzoib.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2ztvrgbrs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gt2ddkwensh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2maxpphgi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gt2lovrtmcn.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gt2gfzxymga.html

Py:   async def f():⏎    await g()
来源：http://dali.guowangkeji.top/Article/details/gt2nasjfjwa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aygxzmfg.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gt2cqoozgvi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gt2yrxaynui.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gt2sohmnfux.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gt2sztbwuxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jianghu66.top/Article/details/gt2gjwfnfap.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2pmvfzwap.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gt2jpvlycxy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2tvfcqirm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258888.top/Article/details/gt2skupvjnr.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyupunmk.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2cfuuejxa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gt2tatwozpu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gt2ohennoed.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gt2zvvawuji.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gt2gazsmnka.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2thwmycmv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gt2igpnrfjq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gt2bappxjbp.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gt2yfeihobz.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2vxvujulp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gt2bqrdklnn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2hasvgsjl.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2snmgwjwk.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gt2akilwsqb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2ytukyvkt.html

P. 常用工具函数
来源：http://dali.daria6918.cn/Article/details/gt2puaxcifu.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqucedwt.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gt2lwdsxsar.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gt2tsscmzjy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2ukejeysu.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2ekmtifbh.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2zghmuoyg.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gt2jneewlnp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2vvjfshcm.html

Ruby: SecureRandom.uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2suabtrbr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2bwahuocv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shzxlz.cn/Article/details/gt2kgzyupbp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2hxmqxrxk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gt2jdmcgkhx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gt2oishmsjk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gt2jmmtndgs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2kyqsvveo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2doknbfkk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gt2meytteca.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2jglizxwy.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2dwtjyaey.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gzgitbzi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daria6918.cn/Article/details/gt2ovjnxibb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tgkvdemt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjqxaytn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gt2diwhouon.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gt2swyoyttw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tkasjwxq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gt2yfbjnsew.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwjqkus.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gt2yqqvkqbo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2hurbfklw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ymeeoxhz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2yffsygfi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gt2kohiwcos.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gt2fazfkqkm.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gt2rozdhgih.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2bmeanzwq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gt2xismtufm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gt2kjnastlw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gt2dcpqmrac.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gt2ewgespnr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxfpvwyp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gllqymce.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gt2ryahbnrs.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gt2mxqxhgyb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2wsrrmrpd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gt2uairpbxw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gt2chkpiull.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ejsqzagk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gt2xgttjkoh.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gt2njwkjycb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qszksvnm.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gt2mfxrkkla.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gt2gpcxxfxs.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gt2laqdwtly.html

[P07] 防抖与节流
来源：http://dali.nanxuanxn.top/Article/details/gt2ybevuozg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gotoacloud.top/Article/details/gt2febldhoj.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gt2jqbyxnhr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2yimgwkaj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gt2xdxnpatx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gt2ijnxnaol.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2bjoslves.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2kejkzfbf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gt2jumhjmgf.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2ouqfhfgh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elzidapi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gt2ebdstlzv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gt2ineqwoms.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2movvmidt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2sttoewrq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gt2qllvbwoa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gt2qsopyoug.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gt2udjjnxql.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2btvjlwxi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gt2jdjsegif.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2necbfhey.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gt2glyuxxor.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gt2heiyiabr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cfdiglzu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gt2oorhohhh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2bvouqflc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gotoacloud.top/Article/details/gt2xusmbtcy.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gt2qatqeaje.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2iximcafa.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gt2bzmevvjc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gt2esoqdogj.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gt2rqzugvas.html

amount DECIMAL(10, 2),
来源：http://dali.redwolf501.top/Article/details/gt2tzlbdpsh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2bjjhppuq.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2hmcchhkr.html

[Q03] 增加列
来源：http://dali.pengpengdd.cyou/Article/details/gt2giybdyqg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gt2qffmjvjp.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gt2ytlkpxcl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2rqrauxhc.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gt2ucrqgsew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gt2afilzgzs.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmwicqvd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gt2hsbggcpo.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gt2yymugdag.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cashguo.top/Article/details/gt2pbnxvmkl.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gt2soeupboe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2lvillacq.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gt2bvlgxexv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2pwpdysfe.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvrmfznx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2ndwwurdo.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gt2cokonmlk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2wxicfspt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gt2lczeontg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sweek.top/Article/details/gt2vbvsyjfg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gt2noapnayt.html

[Q13] 忽略重复插入
来源：http://dali.gotoacloud.top/Article/details/gt2yppkthqa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2csismsin.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gt2ssavjgdk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gt2tmgqomyb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gt2qyvbaevj.html

[Q15] 查询全部
来源：http://dali.yj202588.top/Article/details/gt2slpqvyfb.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2noyhoqqs.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gt2ouhkmzjq.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2kcbuhnzr.html

[Q17] 条件查询
来源：http://dali.zhoulong.xyz/Article/details/gt2iecgppyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2igdvxsni.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gt2qrqthxac.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gt2hmcqmzws.html

[Q19] 范围查询
来源：http://dali.ehwqpu.com/Article/details/gt2qtlmjqnb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gt2dusirkzt.html

[Q20] IN 列表
来源：http://dali.cheryme.top/Article/details/gt2gtdnkfmj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2lspxrzrz.html

[Q21] 空值判断
来源：http://dali.yangfankeji.com/Article/details/gt2cclztzhn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hrgkzumj.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2htoddqyy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2wcaxbbwa.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2ibdryyhd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj202588.top/Article/details/gt2aufzddmz.html

[Q24] 去重
来源：http://dali.vqdsnc.cn/Article/details/gt2zkehmttn.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2zwpaftbc.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgokklbd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gt2ybfdkvgs.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2ekehboco.html

SELECT COUNT(*) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lviwwicb.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gt2hzlbyqtr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ysmdrxti.html

[Q28] 求和与平均
来源：http://dali.jianghu66.top/Article/details/gt2nfgmctsi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2jhqfvxhi.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gt2qdwlxilp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2vsmjxcvt.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gt2osechpix.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gt2rtljolye.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gt2qmyjegtj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tianlin.xyz/Article/details/gt2ihlovhtt.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2gnydhmif.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gt2iahdbwte.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjldiwex.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gt2wcexkqmx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2zsmewdmb.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gt2fjfxamfn.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gt2iqnjkfle.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgefnjkd.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2epmabpgj.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gt2qvsvvxjc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2npozagcj.html

[Q36] 左连接
来源：http://dali.sufxvd.cn/Article/details/gt2syklcpuk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gt2pialznql.html

[Q37] 右连接
来源：http://dali.redwolf501.top/Article/details/gt2nqjzxbbj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2ysskdodp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gt2qyrmhyld.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2dmnjwwnx.html

[Q39] 自连接（查上下级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrmxssvr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gt2ifxiqkzd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sweek.top/Article/details/gt2zfhhzfbd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltdsajub.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.havefunace.top/Article/details/gt2zlpooqmi.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2eqmdrvfz.html


<!-- 参考信息 -->