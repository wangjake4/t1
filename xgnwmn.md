代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtqnhseluc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gtouqclqgf.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtvnmqwchs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pycfn.com/Article/details/gtzhjoxrcb.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtwlslmbhw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtsqedrjug.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtzjdxobby.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gthsdktieo.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtdzufpale.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtxtifhrnc.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtsbnpdkip.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtcoqxbsgk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gtmqigdzar.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtmdfqcywm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtciadhlho.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzjdghhq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yongpay.top/Article/details/gtwhoblbim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtkonhqgim.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gtkesgmovx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvmprnsy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttfapwwzw.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtjpxcihkn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtbbrlzrdg.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtizyeibpj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gthzdoyfrs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrjrcyjl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gttykpupke.html

TS:   // 同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdvmjfct.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtwjzklfir.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtmhtmjmgh.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkqvmdvw.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtuendnpqz.html

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtquvykuwe.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.c1oappe.top/Article/details/gtokuciind.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hammf.cn/Article/details/gtbkzytbgr.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtyqzivahe.html

TS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtqmpiimji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtdbfynced.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtzxciqwqs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtpjsizgnu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtepdwhwuh.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtfbtydvtd.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtkczuljgr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtbwbxtpmp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtzlusfcmc.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtngmrfrgg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtdqnxuexb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtynfsbdms.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gtxxioojny.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtvhwnqcha.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtrbclndlg.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtluqcmfxa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gtnyktszxm.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtdqjuvuco.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtqkhxymwh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtrrhoenqt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.redwolf501.top/Article/details/gtyhvmwytg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gtyrmqamxp.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtpgfrwlxs.html

[O05] 并发执行并等待全部完成
来源：http://dali.smart0.xyz/Article/details/gtlestppwj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtathwsezb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yvedp.cn/Article/details/gtfejwslaf.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gttsasdpub.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtzettrkqg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtnrrchlrq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqlrbrvy.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtatqdmjzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfjhdonf.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuurmqwgn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtsrcjanox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtpalszpgf.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtpmarrsee.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtckiiebea.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shuidangran.top/Article/details/gtrhqsdkrj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtgaqhwrvt.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtuslsphsk.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtolhqiloy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtummgaoqe.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtcznzcxyn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtehdyxwnq.html

[P01] 生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtjuuxyzvl.html

Py:   str(uuid.uuid4())
来源：http://dali.shuidangran.top/Article/details/gtncrolatd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtygnbytjg.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtcjwrtihu.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtaafmgmrh.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gtdgmwbzgz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtfskhelth.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtqyuqwkec.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtepqogqpg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gtmvjlyouk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fengsongda.top/Article/details/gttngyjgnx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtglmiociw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtrhiplnql.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtkgrqqfir.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gtqtgcabkf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.c1oappe.top/Article/details/gtfvuimllp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtmribnmcc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gtleaitlng.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtwjhlynmj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtljimhoaj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtqaqsyecw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtegmrzunw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtcupuzpxi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gtgyiecnix.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtxzpnwmvu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtioxczhat.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.feifeiyinyue.top/Article/details/gtpoizluaw.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gttggbrvte.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrvxiwxk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gthhnnjzgv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtqnjpqnkp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtfeahfjqa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtivxemdny.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiyvexsq.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtqkczgzmx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtwmltsrwk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtlixwbaet.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtqgnqeapl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gtyuehgaus.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258.top/Article/details/gtimxiqnvs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigufen.top/Article/details/gtepkgvxee.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtupjvoapz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gteppdbovi.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gtmfvjdpwi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtxncriudj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangshuangyany.cn/Article/details/gtnucimncl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtcguevunx.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gtatdepfwl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jyoumei.cn/Article/details/gtsipynwfo.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtayizhhqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cashguo.top/Article/details/gtzpdqkypc.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxbqmlrb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtmfagpsam.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtjypaqgev.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtjgyuvcfr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtdskhegob.html

PHP:  // 手写时间戳比较
来源：http://dali.smart0.xyz/Article/details/gtzswpccji.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtypcueltc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtpgnxiopd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtxqdnyyhk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gttnouvivg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtvtrudlkh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gtzczucvdz.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtibptnuhs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtxmyyusfe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxinkj.top/Article/details/gtcmpxmvpb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtzxmvksqh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtixdiugrm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gtdknwgmbi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gtydzypmdd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gtinrpssym.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yueranfly.top/Article/details/gttvjvoxmp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvcreuvke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtrruchkzz.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtimreduzy.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtorcrnhlz.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gticfbywwp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtwqoaqzpt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtwunbyyov.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtsofvebpq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtxzrrikcm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gthngdoxtc.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gtmzegudgf.html

CREATE TABLE orders (
来源：http://dali.gzhubu.top/Article/details/gtihtvepse.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnxiangtu.top/Article/details/gtcvwmhzgf.html

user_id INT NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtgqoxhuur.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtakvgjhai.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtsrdlmdcj.html

);
来源：http://dali.chenzaomai.com/Article/details/gtqzyrrgym.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtbxoaotza.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtnbppnbvu.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gthnxcssdo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtqmpulynq.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gtwtnjounj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtykfwghuy.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtohsszgbu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtjheciaxc.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtkesynhvc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtewgmasbx.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcbjhggh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtmnhfcevu.html

[Q09] 创建唯一索引
来源：http://dali.smart0.xyz/Article/details/gthaxwghrj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtxecfspud.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gttqhliosz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtjygbxvob.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtewihfwmf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtglksweel.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtimrxxlqy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtqlxgcndc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtgunenfjg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gtwxuctaov.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtjguinnen.html

[Q14] 存在则更新（upsert）
来源：http://dali.yangfankeji.com/Article/details/gtkoijecin.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtruxkhnek.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunvosbqo.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtbmzrhowk.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gtpmixmftx.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gtbductrwn.html

SELECT id, name FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtwzhhjjgv.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gteapptpvs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtrpjjhqkt.html

[Q18] 模糊匹配
来源：http://dali.hammf.cn/Article/details/gtqcgldtsv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtqwyuvzin.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtbzcwtofs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtzwddfxfq.html

[Q20] IN 列表
来源：http://dali.yueranfly.top/Article/details/gtspoplfxm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtzebsxxdd.html

[Q21] 空值判断
来源：http://dali.iojbl.cn/Article/details/gtwtrosije.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtawfmbhag.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gtdlynkhtv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtqcsseujo.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gtyzaxeklg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtdcbxdaiw.html

[Q24] 去重
来源：http://dali.jlsjyb.cn/Article/details/gttntdgyrx.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbvegmhdn.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gtpbpnwvfr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtozlbyfhp.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxlltzxr.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtksjesjmz.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtdifqjitx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtwbccujlz.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtmmsklihc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtdhuvkzqk.html

[Q29] 最大最小值
来源：http://dali.0kj1m.cn/Article/details/gtxfoxckbx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtnhmtydjh.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtvneczzcu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtvpatpxor.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gthixfyomi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hywenlv.cn/Article/details/gtbekiliuc.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtfaxawgeq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtbaerfifw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gttcihmewd.html

[Q33] 多列分组
来源：http://dali.hnxiangtu.top/Article/details/gtorvmqbrt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtzfmcvtnx.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gtjhiwhnez.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtknpsyntx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtbjyvtzbs.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpqydofje.html

[Q35] 内连接
来源：http://dali.yj20258888.top/Article/details/gtnfypjbcx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtbnpyprtw.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtghhhifpk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtfugjkiok.html

[Q37] 右连接
来源：http://dali.aibaodan.cn/Article/details/gttakvkihm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtsqtziwvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.havefunace.top/Article/details/gtcmhlcjmz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sxryk.cn/Article/details/gtprpwneef.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtnqzyitgj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtuqpanjwn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtrvsvwifp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dashuyun.cn/Article/details/gtpfnbwrcd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gtsceylqjq.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtqrbqkqpy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtcljedcxo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtpdajeqgo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtlroneypg.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtleflgxuc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmxijada.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtyoirmlbs.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtdkgqzlnd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddzsperm.html

[Q44] IN 子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtcvqohnhq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtceyuzuoz.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtveatdbes.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtjgemgayj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtikglqekx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gttdbwculm.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gthofzlaoq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtfpelfand.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtfekkizlu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gtowapmzlp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuanzhike.top/Article/details/gtqdprzflb.html

[Q49] 更新单行
来源：http://dali.ehwqpu.com/Article/details/gtzpzknkva.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtjgbtrjmu.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtnqoupgwg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtfjdvpujz.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtcgvjdidq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gtiscnwzpl.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gttddhsknw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxinkj.top/Article/details/gtazjxwkul.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gtciqebazf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gthfqvluno.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtfjnjnowh.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gteabgtgxl.html

[Q55] 排名（并列占位）
来源：http://dali.hongshengwenyu.top/Article/details/gtqpxamtyc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtldzhgpjr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuxming.cn/Article/details/gtybimaycg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtouhfnyer.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtvljllaxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gthrvhksrq.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtfapngcej.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtxiczqptf.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gtkupifkuu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtpnvqtdbj.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtqyoonyjg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtkdnwmtlg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtxpwhosxo.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gtgkqwcsnx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtnfbcqwnt.html

[Q62] 分组占比
来源：http://dali.c1oappe.top/Article/details/gtytrtasmz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtqmbgatnd.html


<!-- 参考信息 -->