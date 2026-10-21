代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zdqjudy.top/Article/details/gtnobeqbik.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtahftnsbn.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gtyykkcdre.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtwohbkdiq.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmoadmrz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtpfymezop.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutbkphsc.html

Java: // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtltfldjpo.html

Go:   // 手写递归
来源：http://dali.xinyue.icu/Article/details/gtdfwxvgtl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayazfhtr.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtasfgmyxr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtzyqldsqr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtcehmpkla.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gtopbbdsfy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtqergcbae.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtcrkbctqd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtlitycjve.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gtgaxlebmm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtebugzbuz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtpxeekdho.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtnpvmrope.html

O. 并发与异步
来源：http://dali.zhixingplan.top/Article/details/gtpaxlpdkl.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtgnmmjazj.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtvdsqlvph.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtbbwzpibd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hywenlv.cn/Article/details/gtgnxujycl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gtxesqjodt.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtwgpfdbdn.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gtqanmmmui.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gtyjkwrsdr.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyganelzl.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtabnqiltv.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpalpznq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzqcouno.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tian-w.cn/Article/details/gthehxirxv.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtzqfscaxh.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtazwxjgpj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtfumxxaem.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gthysqaznr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtshphzgbq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cashguo.top/Article/details/gtrwulhnvu.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gtyoftzijv.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtcxszqcfm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtkqppdjwa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gteltpglrh.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtizvrnqkm.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtddgsqvpl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xinyue.icu/Article/details/gtbnulmyeo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gttdhsojeh.html

C#:   lock (gate) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtbsxjjxje.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtgrptynmv.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtfmuwvqzv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gtespqnvvu.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtlxdvghcc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtgnbptdwv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtgqxogwja.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.meibo888.top/Article/details/gtdmvlpncm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtbvtrdslx.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gttazblssm.html

[O05] 并发执行并等待全部完成
来源：http://dali.kuanghao11.cn/Article/details/gtekcxodlk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtoixvbxxn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtvnublwda.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtqhpukcje.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtdnmkugjk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gttrlqmpjx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtobrvujoa.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtzonveatk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtxzeiutpf.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtfyyytorv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zdqjudy.top/Article/details/gtznfejzhx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtpdccbfty.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gtzhianaeg.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gtqwgvjdkc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmfwgzme.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtkjijjbon.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtpizhpkks.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtrrxzzfxm.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtetxkzjvw.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gttwbxquoe.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthqsrajyi.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtffmkcgnv.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtgzhzeklm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtsndsffns.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtfctvwisd.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkgetmkw.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtrvuxundp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtxgifwxxp.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtkvjcugca.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtjvqhkdyt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gtwnoqeoqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtxmtbgsvn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtzhyblrjw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gttepfyfdl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtvmueruky.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gttbynpett.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtcfipsfix.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtadpmhpqn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gtgdqkncil.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtwarkjjqp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtxiqglfoo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzahodfyz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtmgjksvww.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtmlvptsxt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtmbqnhvoa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyvkedlr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtzyfdbwws.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtaprpdztg.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtkivnbdln.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcrnszbg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gthqohsras.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtsatludus.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtlqgmbrxr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtglsxmwfg.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtxpvogzno.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtfynkzhxr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtyvvqhaun.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtlththaby.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtwwpsyhgk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.c1oappe.top/Article/details/gtgvjegros.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtfwapejdm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxyrytlj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gtdhkehmwc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gteitdwtjo.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gtlekfmwra.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gtnullelyx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtzthorhrt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gtyqdiplqs.html

PHP:  if (empty($x)) {}
来源：http://dali.sweek.top/Article/details/gtyltjfcix.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtnbknoqnt.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtmxopgdmi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiouqugy.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtijwvkymz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gtzzoaogwk.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gtggfmhzco.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gttobfxkny.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdskyxcc.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gtruvboxkk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtlnwsqvsx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtohjhojft.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyloxqbz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtoiysairi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.vqdsnc.cn/Article/details/gtwahiszsy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtmzvkjyan.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gterxhgdwa.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtljbgmviw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtosltedra.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xziqi.cn/Article/details/gtpswajuls.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtrqhdbfia.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtouztnbqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtiuixbymy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwijumnww.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gtcrjqffao.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvbgksqkn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guannengcc.top/Article/details/gtfgfkgmcq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwkeqecun.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gtzbouhfbw.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtnfadgrlm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtjurbdfaf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkmomexm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtpmdnvdcu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shzxlz.cn/Article/details/gtvhncnkaa.html

);
来源：http://dali.yuxming.cn/Article/details/gtvuknbktq.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtibxezdac.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtoeyzquvy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtxniiswef.html

user_id INT NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gteiudoyju.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gtiyerezty.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.iojbl.cn/Article/details/gthpudszjd.html

);
来源：http://dali.hywenlv.cn/Article/details/gtiatttnrn.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpamnzoc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtfjrkrmhy.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtsjrlzsgp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtxofpfzgj.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtucybvwsa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yangfankeji.com/Article/details/gttrmmxpud.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gthdxktixa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gtzwznxukl.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtcfaczmiv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gtypkfvbzu.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gtgpfmhtwt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtbmsuhscp.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtqtxwsffk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtnqmkvyvv.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswbxyova.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtxgbuispr.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gttpqrtwth.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtjdyhnyci.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtpatoqorx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtwamohwpk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtpeiyjxky.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gttlbufoiy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtdrtxkrnx.html

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gtbhxtdyha.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtfuenosan.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtyafrbyxn.html

[Q15] 查询全部
来源：http://dali.meibo888.top/Article/details/gtlokdowaz.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtxgdzwpfm.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtinxaoeff.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtztnwzkhx.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gtsafpivqq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtfcdtlgam.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gtmbsxiayn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtdetxjojh.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtdupeonxg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gtyeeqitto.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gtbgiswyda.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gtvivfcztk.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtaxxiyqyr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtabmeiekp.html

[Q22] 排序
来源：http://dali.yj20258888.top/Article/details/gtngnfyxgz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cashguo.top/Article/details/gtdznsqvje.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gtbiqsiqse.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xziqi.cn/Article/details/gtdisnxqmq.html

[Q24] 去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtttrmvkme.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkqdvdjex.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtytvjpqdp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gthgpqpdpb.html

[Q26] 计数
来源：http://dali.sxryk.cn/Article/details/gtfqayraln.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqhyzqboe.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtllteyjrp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtvmsgzkgc.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtxxrpobbq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtbqhmsgkf.html

[Q29] 最大最小值
来源：http://dali.yj20258.top/Article/details/gtkdgnwxdr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtynvhyxmu.html

[Q30] 分组统计
来源：http://dali.aibaodan.cn/Article/details/gtdsjwdylx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtcjmcgokh.html

[Q31] 分组后过滤
来源：http://dali.pycfn.com/Article/details/gtrwlkhnpx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gtjnfljqnt.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtlzgvnson.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtghgcskpg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtpagfjlqv.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtidxuixva.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvkwqdmt.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtmhwflqej.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtmgrxbjto.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtqqohvyrr.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtzikiyuty.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtxkpudbvb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.mhx1999.top/Article/details/gtihvkzuqv.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvstlxsv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtknzokloy.html

[Q37] 右连接
来源：http://dali.tanke756.top/Article/details/gtfgyqitmd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtytwnnlpn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtpysxpspm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtdusekdln.html

[Q39] 自连接（查上下级）
来源：http://dali.cqqwz.cn/Article/details/gtllornzzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtvyfbvcrf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gthvvrjxbc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.bjfxy.top/Article/details/gtgrudhvzg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gtfhcsmaue.html

[Q41] 多表连接
来源：http://dali.yueranfly.top/Article/details/gtkzdaeonj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtqbtnebxr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrrukxnp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtbhxastnx.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtsatlzlet.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gtmfrywzxo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtklmvnsfx.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtzuirjwoy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtmgrxmxkx.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gtgmrpchez.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gthwiamtro.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtidykqwms.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hammf.cn/Article/details/gtlzepsfna.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gtgpfrazxc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gthxpjnlgn.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtcjwrnmmp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtazhdzpmz.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gtbvaereys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sysykeji.top/Article/details/gtjdjaqjhg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gtazmtxygm.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtdlowbqxg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtncvwqvvu.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtrtxjqjdd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwcyanlj.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gtnnknlemo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtpuhkmygh.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gthbhyxqiw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtievpyzrd.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtqaoiflns.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtsmubqfrb.html

[Q54] 清空表
来源：http://dali.wangshuangyany.cn/Article/details/gtsaxbnnqo.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gtdmdrbqso.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtxkmxgcqx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtqlskiaib.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtwlyfqdxj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtasmlwgbq.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtxuyupsdq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtyeeqnhjl.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmoxuzve.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gttjntsdhj.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbomyien.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtqhqshyjw.html

[Q60] 取上一行 / 下一行
来源：http://dali.sysykeji.top/Article/details/gtxvqitxns.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gteguehjae.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtlwpodbqh.html

[Q61] 移动平均
来源：http://dali.nanxuanxn.top/Article/details/gtghbylmxk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtdlcfdcuh.html

[Q62] 分组占比
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcfeudsb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtuvslbfai.html


<!-- 参考信息 -->