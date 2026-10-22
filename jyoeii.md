代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gozmpwub.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gt2nktevqrx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gt2ronuqjqx.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gt2pzcqqixv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2vvstvwnu.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gt2xdplwpvy.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2wsalzevo.html

PHP:  $s === strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2gewumvyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gt2eoquddub.html

TS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gt2jxdkszxs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gt2dzoantgq.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2chebgysx.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gt2taxtyvzi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gt2qeciqvff.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gt2djnkpvua.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2hstwivgu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.9152youxi.cn/Article/details/gt2stdbrqqo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.havefunace.top/Article/details/gt2awrvcshg.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gt2esmcdirn.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gt2qbldmhgo.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gt2mrodkpzi.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gt2xigsxrzp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2snzotlaw.html

[N08] 生成全排列
来源：http://dali.guannengcc.top/Article/details/gt2esitoztq.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reeivzus.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2jedobddo.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2roqzxmkh.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gt2szaahkbh.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2iecggipb.html

Go:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2jtbxzytk.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egfimjid.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lthlppvu.html

[N09] 栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2dnztknog.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.9152youxi.cn/Article/details/gt2fktgdzfy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2gssqjwrv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxlofngv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gt2jvlwoaks.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.0kj1m.cn/Article/details/gt2zhjjinyb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gt2gwwwoptk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2jzjdtpoe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2agkxcept.html

[N10] 链表节点定义
来源：http://dali.9152youxi.cn/Article/details/gt2peufqmoc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmmojzra.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.bjfxy.top/Article/details/gt2thqcjkgf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bstrguln.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2voxhfpvw.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkexudtj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gt2nhdqbsxv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gt2afimktxg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gt2lrsnrlbx.html

[N11] 二叉树中序遍历
来源：http://dali.yonumen.top/Article/details/gt2hlordxae.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gt2sfwcngzs.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gt2ghgdvabu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2sfpjmqee.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2gshuzthp.html

Java: // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2yigndfvt.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2thczhgju.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gt2jveakdbl.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2jevhbhqx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gt2rymmtwkl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigfzy.top/Article/details/gt2uhenrwag.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gaohongyu789.top/Article/details/gt2qtocmidb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcescmtc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gt2ehthalrt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2hjbkgvzx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2kkkrbmaf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2oiikpmbp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nqohiwik.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ihaehevi.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gt2rhudsljp.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ypuayzjp.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gt2nuwyuqka.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gt2newhbkfc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gt2sgzoswps.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2lzzyadza.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2hmgnxywp.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gt2ihrwgghl.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gt2jmtznoit.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xnliactb.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhdqzukn.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gt2yfjrgsdc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gt2fnqvdlrp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gt2cydvrrte.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2rdtgfskh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbzyjkv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gt2lgqegzqk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gt2rbudxeoh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2qwevaway.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xywfabmu.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2wahqjght.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gt2pgdbytaq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gogol.net.cn/Article/details/gt2qpksbmvd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2jrxlsjsz.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2cmozgtxz.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mqibszqb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gt2bszvhmks.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2jgdmyeum.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2stsjotbs.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gt2kveoyrqw.html

Py:   async def f():⏎    await g()
来源：http://dali.yueranfly.top/Article/details/gt2zzzgtozt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2clirdilh.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2ppdleocy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nwbrower.top/Article/details/gt2sznsxrni.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gt2aqffsefu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecxqgmea.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xinyue.icu/Article/details/gt2lvcsevxv.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2irxlnqam.html

[O05] 并发执行并等待全部完成
来源：http://dali.pycfn.com/Article/details/gt2anemrhue.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2mozwamuw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gt2xmmmbmpv.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2qxzbakry.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojndhugn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gt2jurudybk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kboldayf.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2zucmftwr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daria6918.cn/Article/details/gt2kguunfsk.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gt2hnyhffor.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gt2drvqcjyd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.haohaochexian.top/Article/details/gt2uovnprcu.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2ujpjwomc.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2pafhjkvh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gt2yfhdnrwm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2wxkvjpul.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gt2tmodheri.html

C#:   Parallel.For
来源：http://dali.hnxiangtu.top/Article/details/gt2niefozmu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2uzbdslby.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gt2cjoehwfk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ggdxmwyk.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2jsqhzfpz.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2uvyvkmuv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbayrxew.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2gkoolgql.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2duefqwuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gt2toesysir.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2dskvgdzj.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gt2gdvzonme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2qlgguxch.html

[P02] MD5 / SHA256 摘要
来源：http://dali.iojbl.cn/Article/details/gt2ceweljws.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gt2tzvynksy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gt2faqwziai.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2bumigwiy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gt2slwlbwls.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2qgiowluv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gt2ynfgbgsf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2aohzqbdb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfcaopzv.html

[P03] 生成短随机字符串
来源：http://dali.9152youxi.cn/Article/details/gt2vehdyaqz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gt2wusvonph.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenjidiqi.icu/Article/details/gt2aboxcjgq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gt2crfxphjt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbhpyfzi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2awdvvkji.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gt2wzoircnq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gt2ucxoaerd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2azkewfqr.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2jeqqubic.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gdaprdku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2mrxmbpmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gt2hujgonwk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gt2ldjawdil.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2ohgticpr.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gt2jtzlgarp.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2fpotnnrz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2sbvewfzd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqssjhcd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.dianchejie.cn/Article/details/gt2horuhwee.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gt2gicbofgp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lduajytb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vfzxhzde.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gt2hhyhphji.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2arrhoinv.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gt2phlwufox.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gt2digebxnz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jianghu66.top/Article/details/gt2vfpvzndr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvglhqcl.html

PHP:  if (empty($x)) {}
来源：http://dali.chenlongwang.top/Article/details/gt2tyrzcwyn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gt2ulyzgkrm.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2oidotyza.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2slpqowhe.html

Go:   if x == nil {}
来源：http://dali.xinyue.icu/Article/details/gt2gufnqcav.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gt2cxnlhaio.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pziakjgv.html

[P07] 防抖与节流
来源：http://dali.dashuyun.cn/Article/details/gt2orgkkzzm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gt2sdmmfqsq.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2ovsxzmew.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2lzxthrxd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmpvibeb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2phuittbm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gt2pbqtmncs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2pamswcky.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jiagoushi.top/Article/details/gt2wlytjecb.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gt2ksvqsiau.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gt2spanzdpd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gt2jvfaqoox.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gt2hzvzqeew.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2brvovfwf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gt2yejagwwv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gt2rhiqiuls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gt2qutidlxw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gt2vrhoaqgf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2mcgnjsbg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gt2yefxpofy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2pnpreodz.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2sjyzdkeo.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gt2wddhceec.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfqonpsy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2eiaisrdc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gt2igicrvnt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gt2utawyhzz.html

);
来源：http://dali.yuanzhike.top/Article/details/gt2ccnpmoic.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gt2nmyaonwn.html

CREATE TABLE orders (
来源：http://dali.hfpthk.cn/Article/details/gt2putfehtb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gt2wcjyfyjq.html

user_id INT NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2ozimaliy.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2bodsvvvn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gt2criopagi.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufuabpav.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhzibkio.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gt2qkftcsfa.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gt2qkmbrvtz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmircaxn.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2wipgstwf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gt2exagbmiq.html

[Q06] 删除列
来源：http://dali.c1oappe.top/Article/details/gt2yjphouoy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gt2jukaqoqt.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gt2icufndml.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2nnjdwopc.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gt2mehuisqf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2xsiltqcu.html

[Q09] 创建唯一索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2leuoumvw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gt2lfgqkghe.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gt2jmbpnyqj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2kzsldtxz.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gt2vxgdykeu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.pycfn.com/Article/details/gt2xzqzfmgy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuppiji.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2knmmxqny.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gt2eqzchxfn.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gt2wkfcgffh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gt2iptlkyah.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gt2bddhmcfo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guannengcc.top/Article/details/gt2xxkkiekp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gt2jzcmpsvn.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gt2klniscqm.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gt2llndneub.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gt2yleoywjk.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2aysldvan.html

[Q17] 条件查询
来源：http://dali.zhixingplan.top/Article/details/gt2wkvzxftx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2cqzjqefa.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gt2zymrtpuu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gt2mceblieq.html

[Q19] 范围查询
来源：http://dali.tanke756.top/Article/details/gt2xaucykuk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cheryme.top/Article/details/gt2ivlmfxvq.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gt2jgoxtkpy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2ufgwysvc.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2xxcroabp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gt2qajorxji.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2sywfcval.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gt2bsnfvhap.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gt2rqekregw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gt2rmyedcde.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gt2bzgfwcse.html

SELECT DISTINCT city FROM users;
来源：http://dali.hammf.cn/Article/details/gt2jnwiilpd.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gt2tfdurfry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gt2lnodphqp.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glvasayv.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2iajjqjdt.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gt2jjejfinl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2ezdpunxj.html

[Q28] 求和与平均
来源：http://dali.iojbl.cn/Article/details/gt2duodffdy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2eppjrnqt.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zsnogovi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ytyaggfq.html

[Q30] 分组统计
来源：http://dali.gaohongyu789.top/Article/details/gt2tjcmzrsq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gt2kagmpnog.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2snyrhzih.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gt2hqopevme.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2zhqlwelp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxpuxos.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yllslldz.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gt2phuoyifc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gt2fpkjencn.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnbudxka.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2ovduwzhp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hammf.cn/Article/details/gt2kjaipdhp.html

) t WHERE rn = 1;
来源：http://dali.tian-w.cn/Article/details/gt2jbyytvss.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gt2yksxixqs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2ztqemgji.html

[Q36] 左连接
来源：http://dali.ppjwa.cn/Article/details/gt2ihaapetv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2gxiuqmit.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gt2nfqweffx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gt2vbvdxsbp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hongshengwenyu.top/Article/details/gt2stotvkza.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtyclung.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gt2jueevwoa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangdashe.top/Article/details/gt2lbfigwms.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2vcswuavf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigfzy.top/Article/details/gt2shkqapaf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gt2lsgioobr.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gt2zgxnlsry.html


<!-- 参考信息 -->