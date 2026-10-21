代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtuctdshtm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.kuanghao11.cn/Article/details/gtdvvwtnjl.html

Java: class Node { int v; Node next; }
来源：http://dali.daxiang520.top/Article/details/gtjoignsiu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gttbroourj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkkaprnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtwycjcoxm.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtfabonffs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xinyue.icu/Article/details/gtbqcorpdu.html

PHP:  // 手写递归函数
来源：http://dali.nanxinkj.top/Article/details/gtbaeiiydc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtfrsaqike.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtrjbwocex.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtwcvrxoyw.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtfyukrnbb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nwbrower.top/Article/details/gtecpehbxn.html

C#:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtnhyyccgo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtpnachkwm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtzapijkls.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.mhx1999.top/Article/details/gtgcqbqbsu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.c1oappe.top/Article/details/gttpszxbzu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtczlvhpua.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fengsongda.top/Article/details/gthukelyiv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ydzc1.top/Article/details/gtlhqhtdea.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhlwxrly.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtjmobyhrg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwponyawt.html

O. 并发与异步
来源：http://dali.chenlongwang.top/Article/details/gtaqhkyjyk.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtghumcshe.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtjhjawwlo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtxyoxqehe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gtmrodnawb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtkkupvwjc.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtknxgmulq.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtdmzyxspm.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtjonkvdmd.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqzjsmgt.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gtncejskco.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtxkkpiaum.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtvjxbjgrv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.9152youxi.cn/Article/details/gtvxzhmsut.html

JS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtskwgpphe.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtgjpfkapl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.andypj.xyz/Article/details/gtilevborx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtfjyxscvn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtwdiacbng.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shuidangran.top/Article/details/gtpctyeiyo.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtjfgaiwmo.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gtzzjcykoz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtygylwgpm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtcesmbybk.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtyllqumqn.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtsljywmku.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daxiang520.top/Article/details/gtefsuwzjr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtuixxrglg.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtqdhqlfes.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtyegluvyg.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtbpuowtfc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtugkmwbig.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtzjrcaure.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtnijndwle.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gtpvpkwjsr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenjidiqi.icu/Article/details/gtaozbjzsa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtgqymwrkq.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gthmxkxnht.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtnghokotu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtailxckke.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtcgkbxdqn.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtimovsoii.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtzttpwzdk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gteuxxwyhd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gtvxtfwuhi.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gtfkknakle.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtvcqogtjn.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gttceqbvju.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtxfzmooop.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtwshesnfx.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gteoliingj.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjlrhekt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtrtmllyvq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtoqugxfqz.html

Ruby: // fork 块
来源：http://dali.hfpthk.cn/Article/details/gtxartjlco.html

C#:   Parallel.For
来源：http://dali.hnqzz.top/Article/details/gtqdepjvzo.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtpnmmwbho.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtzqdyljhu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdgxanykp.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtryavdhdj.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gtifjrdgrk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuyrgbcx.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtetnuglml.html

TS:   crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtyoayonve.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtodmzomla.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtsoipuuag.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtqyrqivfq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtomgwajsn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtgnxjcpqa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtuljpocaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtjymtyojb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtasafatis.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtivsjohuf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gttayzjkdy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtzrcankho.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtslmsltkg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtujpguivn.html

[P03] 生成短随机字符串
来源：http://dali.fzhhl.top/Article/details/gthouyaroh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.iojbl.cn/Article/details/gtheetklnx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtcmcgpeaq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gtqnqyucou.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtwlwsgpzc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gtskkmdnam.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gthulyholz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtfbeptgjj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtwmhxgrch.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtrnwoduhx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtamjeunvs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdjojaxg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtkwnbcxvm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtwkarrpgs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cucudq.cn/Article/details/gtcfinbhkv.html

Go:   len(arr);  len(m)
来源：http://dali.hywenlv.cn/Article/details/gtgifrpqid.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtvdozacnp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhixingplan.top/Article/details/gtjexmcgeu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtokpeidju.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtiarwvuaf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtzjzfhini.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gtyuazbpko.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtnnvmqzrz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtwzewlxch.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtovvjfzrv.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtpxlmojgk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtdclnolmp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtsgegzpft.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtqpunfikw.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtiflzlybr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxccswikz.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtizmkuqqz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthlkxaggv.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtuokxqyog.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtodimdyqa.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtptvqsjpu.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gttsjlwmwl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gtqazwqkvg.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswxxowxq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtgsuatdmu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtysfpnvnv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gtnnumfszi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hongshengwenyu.top/Article/details/gtwvgfoobj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtxeomoghp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcxlmxvn.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtjfjtrhea.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtzxsqaqgb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtooktwedf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtducoeuco.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gthrsjfthz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtblmyunho.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtcetfjoca.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gtppjcmelf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtycyvbdtr.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtflxxmtfo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtlbscxamf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnicxihqa.html

[Q01] 创建表
来源：http://dali.zdqjudy.top/Article/details/gtshertftq.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gtfvrsgzwe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtktejlbbp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtklfauwth.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xinyue.icu/Article/details/gtvnwqoxeg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtlcqyphqz.html

);
来源：http://dali.kuanghao11.cn/Article/details/gtibvtwkdz.html

[Q02] 创建带外键的表
来源：http://dali.c1oappe.top/Article/details/gtpzcaqagz.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gttkidnqpb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtzzinztkn.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtrejxlgvh.html

amount DECIMAL(10, 2),
来源：http://dali.xinyue.icu/Article/details/gtnsyahpod.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtilzpjakv.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtmpimhppz.html

[Q03] 增加列
来源：http://dali.wangdashe.top/Article/details/gtpwmdnvdk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtdewaxgqd.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gttfpdjiii.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtavvemzea.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtxbzppgjp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtwuqhygxf.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtyzfdsrek.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtawnregqb.html

[Q07] 删除表
来源：http://dali.snrcjt.cn/Article/details/gtxllidzyi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtrbhvzxpe.html

[Q08] 创建普通索引
来源：http://dali.nanxinkj.top/Article/details/gthwygmbxl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtqribmpeg.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtmbvekjdy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtqlrqtryt.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtqdlslojf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtukpubxum.html

[Q11] 一次插入多行
来源：http://dali.jianghu66.top/Article/details/gtsmfhpyaf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabhbaucb.html

[Q12] 插入后取自增 ID
来源：http://dali.wangdashe.top/Article/details/gtnztigcsb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gtvehoxbyu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtmvjgonwm.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtvritxzjm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtjelmxzxz.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtiubqftmp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtwhidzbgw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtpidmbyjl.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gtohfthkfu.html

SELECT * FROM users;
来源：http://dali.yj202588.top/Article/details/gtjjwctjuy.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtrsmjwgdc.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtxqobbnjx.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtkhcqdfhg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtagofcyyg.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtzsqnwgvi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinghuilouyu.cn/Article/details/gtabjigrfp.html

[Q19] 范围查询
来源：http://dali.nwbrower.top/Article/details/gtovrfzsnk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtnssikamq.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtbffsjrgd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtpwgonpmh.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtmkophffy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gtrgxdonpj.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gtuwehlzrx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gtxtwiovom.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtqlpztwro.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtdppracqs.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtdlxbdkqa.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtziiwwqmf.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtlmuburly.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnxiangtu.top/Article/details/gtnaonfzar.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtrubokgpg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtetpczywi.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gtulbacopi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuxming.cn/Article/details/gtdamwyazx.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtzhmceeoy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtqwhhttjx.html

[Q29] 最大最小值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdumsvwww.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtmjnfcjlu.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtvgfhntae.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jianghu66.top/Article/details/gtlzclyzoy.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtyxvzbpqi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gtehbiuffh.html

[Q32] 分组拼接字符串
来源：http://dali.dashuyun.cn/Article/details/gtcgllpgmv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtqyiavlie.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtohygeizp.html

[Q33] 多列分组
来源：http://dali.xinyue.icu/Article/details/gtaqrnnykf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gtprlffmtg.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtoiclrcqy.html

SELECT * FROM (
来源：http://dali.xinyue.icu/Article/details/gttrtkdmcn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gthhhmvvxf.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtuainqhlx.html

[Q35] 内连接
来源：http://dali.dianchejie.cn/Article/details/gtjldmjiea.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gtpkrbhzhx.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtatvuyghj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtkzedlfpu.html

[Q37] 右连接
来源：http://dali.gaohongyu789.top/Article/details/gtjekaevuu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.c1oappe.top/Article/details/gtpxvyodgl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guowangkeji.top/Article/details/gtmbowdazz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gtbxkodcrr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhoulong.xyz/Article/details/gtpwozakgb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhiwuduotai.top/Article/details/gtizjwuoag.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shuidangran.top/Article/details/gteinicmto.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guannengcc.top/Article/details/gtponxbrun.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gtoadmvifx.html

[Q41] 多表连接
来源：http://dali.zhongyouzk.top/Article/details/gtsdopjqsv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gttkmopqlk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gtsiaidzho.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtcopylpvf.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtfmtxkbbc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yangfankeji.com/Article/details/gtynblndrp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtesuofihm.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtcrkqyooc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gtipvwvmnh.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtwqmopcti.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gtmhdxmmik.html

[Q45] EXISTS 判断存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoycuhjpp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtulhutqbl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtdxmnoeaz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtivevfhcu.html

[Q47] 与平均值比较
来源：http://dali.jqgufenzy.top/Article/details/gtaknosymp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hnxiangtu.top/Article/details/gtkkkeqxev.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtftxstjzm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtpormjzod.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtanqvmdii.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtipurozef.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtquyiiqyd.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtkrpuihmy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtckkuslfw.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gtdrevmghx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtoqlaxcor.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtoyibizer.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtipkjeabd.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtjlhaudxx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtrfkliflz.html

[Q54] 清空表
来源：http://dali.haohaochexian.top/Article/details/gtqlznurwz.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtvctignbq.html

[Q55] 排名（并列占位）
来源：http://dali.chenzaomai.com/Article/details/gtqnuqkyep.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtopbwxyks.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtcrrgdvmh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtpzvpzqeu.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtscaosoan.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthklqmshd.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtbazmlfad.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtsvdnqwze.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gtinanlniy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtfvliubvk.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtyjsgpzzs.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtxxybjghd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gteroupebk.html


<!-- 参考信息 -->