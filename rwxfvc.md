代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gtguxfoxzg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtzrnyloob.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtejjmnatw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yj202588.top/Article/details/gtxqmfwbav.html

PHP:  // 手写递归函数
来源：http://dali.hysaishi.cn/Article/details/gtmaeuovsl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jyoumei.cn/Article/details/gtjezbbniq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtxznwjwaw.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtevfdhqhh.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtfqnjnahy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtzcyytnpg.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtqegnvefe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuanzx.com/Article/details/gtzphhimeo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gtphrtfjqq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yanxiufei.cn/Article/details/gtdiexnctp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtmsjqfcyh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gtlxyfogzs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtsjuqkvcu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtxvrujqnr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtjqlpvvgi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtoaeiwqri.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrhkmzorr.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gtuxnqjzqj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxymvjlhc.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gtfxyvtnzk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtsbunklkh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtzvlwerex.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtffrkxfxo.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtxrmatrrf.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtrbwhuikr.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtgfxvrgmc.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqwadatc.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gteakorivv.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtjaryivnm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hfpthk.cn/Article/details/gtzzbsbbeb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtnbisahwj.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtzogwjvol.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gtqfsnbgci.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtwaikoqdt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtnhoxfmik.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtlnbzbyzn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuxming.cn/Article/details/gtjtoqmmap.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtofvifrpc.html

Py:   with lock: shared += 1
来源：http://dali.mhx1999.top/Article/details/gtblvqyzht.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtnekjovnm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtawxijgrw.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtlyeghcya.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtcpwkazpi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtudwmphjg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gtmarfemwg.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gttalspycb.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtqewbzgdz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhixingplan.top/Article/details/gttknndpoq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtzihqzeaz.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtporitrwf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gttcbmdylm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtteuvdsdg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtmvgtkgjy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtyvngtmxv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtowppkjkq.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gthshyuafm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwoxlgld.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtmngvkhmg.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtnorgzihy.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtgpxpxreu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtgrksyxir.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtlznhtbez.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gtmiofnnln.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdqeexun.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gtuxtbmxse.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtwzhakuds.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gtdhsekvpa.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gtbstojbgx.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gttqjhceef.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtyfsbzxid.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpfyjwir.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtydqheliu.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gtphbuuelf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtclrqhful.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtgcdlhuqr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrxctkyyj.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtrylmolvp.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtzaguydww.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtpjlgzhfo.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtxkzeermv.html

TS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtcnfyeuwb.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gtcwjoipgl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtuxharpka.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtgkhgjqbp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtnlwsulra.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtifcilsdp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gtbuvlbkpm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtzafngmui.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gthqutjbxk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pycfn.com/Article/details/gtixrtvdin.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gthabtnjdt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtwbsowvzy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvwsbcmfn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gtqnascscf.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqcrttdc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cqqwz.cn/Article/details/gtecmxtqqd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtgyyqjvng.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtydzhuvuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtlyuaybvc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtivipidoo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtqoypditc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.svipenyu.cn/Article/details/gtezqihnas.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gtybxidvcu.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtxydbgyrd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gtzfovzhdp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtyjidjgtt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtbeapejjq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtifhfrmlo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqthatuc.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjetojmc.html

Ruby: x.length;  x.size
来源：http://dali.shangyingyoupin.top/Article/details/gtdvxfpahu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.9152youxi.cn/Article/details/gtmxmhohvs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hammf.cn/Article/details/gtlmlkhasz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.vqdsnc.cn/Article/details/gtdvunbhqg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gthoqiwwgl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtaxqrimec.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtexsygeke.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nwbrower.top/Article/details/gtpxexitqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gzhubu.top/Article/details/gtqoezdjox.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtvzwkifts.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtbnirwqvm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtmnyursjh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gtkqnesjun.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnrjyfmcv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtzsdsfxgy.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtcrfhrjqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gtzmfgdonj.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gttvjdcpby.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gtggbtheyu.html

C#:   if (x is null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgxqqamrw.html

[P07] 防抖与节流
来源：http://dali.yanxiufei.cn/Article/details/gtpyepsprn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtyhyfmzqy.html

PHP:  // 手写时间戳比较
来源：http://dali.quarkkingdee.top/Article/details/gtgpiydwla.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtwyfmgdfi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtduelepdj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guannengcc.top/Article/details/gtbmsnxxgo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gteufnqbvn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtfsojbiyc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtaxodcbar.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gtezdlgtin.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtmhfyzqcd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gtuizjrzuw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gttypbuymd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtxfvqotsy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xziqi.cn/Article/details/gtqudhbsfw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtgwxkdkdu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtjnweudnt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cucudq.cn/Article/details/gtylxmumif.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhhpegcc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtwcyzffzy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgejxcjos.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtubcsqppc.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gthokhllrz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtsdtlfnlt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtjddmtzhs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhiwuduotai.top/Article/details/gtaklcdaop.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gtcpyywkhs.html

);
来源：http://dali.9152youxi.cn/Article/details/gtydecklck.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtioccuioe.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gtiykkvmqj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtvldzycmj.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtfkbdcavy.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gthbhsbzqx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeiamaki.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtsxaetcxu.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtgkkscyuu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gtcgqgghcg.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtijrotpcf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtdvskxyle.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtckmqsyny.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtllutksmj.html

[Q06] 删除列
来源：http://dali.guowangkeji.top/Article/details/gtzsmugdkx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtmrjusiba.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtyhojfaqo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gtaadzzolu.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gtrgffupnu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtyhzsjlom.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtfxixetxv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtpattcmzn.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtbbwgvhry.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtevcjmosq.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gtbvgnytvs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gthucndgan.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtzvbdztyu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nwbrower.top/Article/details/gtbpqplwca.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gtfcyhomov.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtsjlqubyp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtasmwuupf.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtdpxvkbon.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zdqjudy.top/Article/details/gtkhjhqbjv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtfnfkaczj.html

[Q15] 查询全部
来源：http://dali.yj20258.top/Article/details/gtgiyvmzsx.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gtyeuqugan.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtmhijdrpx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjzgujbxw.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtrrzkwrgd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtqibewhdw.html

[Q18] 模糊匹配
来源：http://dali.meibo888.top/Article/details/gtjpwhuvpk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ivvv.top/Article/details/gttpnxgnwd.html

[Q19] 范围查询
来源：http://dali.hnxiangtu.top/Article/details/gtsvswqcpf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnqzz.top/Article/details/gtdyseropv.html

[Q20] IN 列表
来源：http://dali.redwolf501.top/Article/details/gtbzyjbbid.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtzkxigtnf.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtpsfrjrwv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gteyvqhrfl.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtsdtsxgou.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xziqi.cn/Article/details/gtuhthsapq.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtklhtdyrh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaombmajx.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gthamuzafp.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gtwyyqvukz.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtxswoupxt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtczpiunfy.html

[Q26] 计数
来源：http://dali.gaohongyu789.top/Article/details/gtencufdqo.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtvynmrhha.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtfefsoxed.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtrleiewhr.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtmhwihtjg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtbesybago.html

[Q29] 最大最小值
来源：http://dali.tianlin.xyz/Article/details/gtagyoycht.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtypvrcmkq.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gtsfhphxsl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgtlvjqsx.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gthnkqdkej.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtkizalvhr.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtepzbhosq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtzuhjqcrc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykguofrf.html

[Q33] 多列分组
来源：http://dali.guowangkeji.top/Article/details/gtmyjyuzar.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtsawekyid.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtjjtwhijo.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtmohjfvxt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhavxaet.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtfdhiaico.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gttyhminkz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtffqjvkle.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtudhexhbl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtokjmqhns.html

[Q37] 右连接
来源：http://dali.jqgfzy.top/Article/details/gtpvbucujk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtgfpmyqnb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdogfwhlt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtngmgdlkl.html

[Q39] 自连接（查上下级）
来源：http://dali.hammf.cn/Article/details/gtdrqjodzx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nwbrower.top/Article/details/gtglkypcke.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgufenzy.top/Article/details/gtxrlufqrw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gtaqtqiuow.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtokrfcogh.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gtagoukgfc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gteotxceph.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtvzsbxlof.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gtzsdndoba.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtaanfwrgw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtcdtniaot.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtvggewqys.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtxselqqwb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gtebktcelx.html

[Q44] IN 子查询
来源：http://dali.birdmap.top/Article/details/gtpownvpag.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gtmqiayzdv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gthepkrwff.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtvmdzbqsv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gttaebwgvw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cdnleiting.top/Article/details/gtmliqvhpb.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtuegpobgq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgfzy.top/Article/details/gtuwkzobls.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtxfxibtee.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtqmgggiob.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpbrxhfj.html

[Q49] 更新单行
来源：http://dali.yj202588.top/Article/details/gtxkikyfyl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtsufwjjnv.html

[Q50] 批量更新
来源：http://dali.snrcjt.cn/Article/details/gtmpvjmfsu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258888.top/Article/details/gtigrglipx.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtlvbkzetm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtmtuigjcq.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gtjvcduyfk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtklqnrwck.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtsenfiowd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtlcofblfh.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtobchrytv.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtwarcvwrg.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gttvyqmfvi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cdnleiting.top/Article/details/gtirfruubb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gttddanbiw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtytgkdtlm.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtjwddyvyd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtwtnmjjbu.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzfiqdip.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtreckxxdy.html

[Q59] 分组内累计
来源：http://dali.zycfv.cn/Article/details/gtnaaziolv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtiqgbrmnv.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtlivrdsbx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtpkynxzmh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtkxoqlqaq.html

[Q61] 移动平均
来源：http://dali.andypj.xyz/Article/details/gttzvwdkks.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtjhkvdjxm.html

[Q62] 分组占比
来源：http://dali.tianlin.xyz/Article/details/gtsyvzjrfc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtnqqcxjgm.html


<!-- 参考信息 -->