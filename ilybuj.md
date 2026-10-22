代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gtlrzexdlk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtnawnkjfz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtuscivpmw.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtajmeueob.html

Go:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtjgnflvgz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gtkguprfhd.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtgsauverz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.316326.xyz/Article/details/gtrujxbuof.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtjhzypkze.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gteiyxemwj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtakbguspl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtnjxxbqwv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtrxjsitoo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtaykgdikc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtrlbvrzuw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtpiuctrdq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtpvqzitgv.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gtkcylwksk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtturunlvr.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtpdtourcn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtkgypejsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtiavmhgbn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gtmippzctp.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtlumniqfh.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxinkj.top/Article/details/gtwhszwxib.html

Go:   go f()
来源：http://dali.cucudq.cn/Article/details/gttnxzlkdt.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtvcwpoydd.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtsxftlrtv.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtjbarmhyy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtnzvkpyef.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangtech.top/Article/details/gttbwdkdwd.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gthwpjfezr.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gthgylejws.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hfpthk.cn/Article/details/gtjvmuzfks.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtzvvuqwgd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinghuilouyu.cn/Article/details/gttntbxjle.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgmcnomj.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gtiijdalbg.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtwzolvarx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gthdbqvxxb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtidxjbffa.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtfxphxjwz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtdtgbnbdg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gtxezpwcnt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzxksfba.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtcyqyqfvd.html

[O04] 定义异步函数并等待
来源：http://dali.hfpthk.cn/Article/details/gtvtdatyba.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gtstjtytvs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtvrpzqjjj.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtvpqdrnnj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtlusovhrc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtsfqwmodk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtivjriinq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtqttqfhtv.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtgiqzdofn.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtlsqnjorn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtkgwvilcn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtuxwflhtk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhichuwg.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtktoidvju.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtkglmstyb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gtbazeavns.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtjbvlpmmm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtaymfagsp.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gtmbjdtjyj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gtmozgyojc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtmdxnfkvc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtdsmunkra.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcekqawt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.smart0.xyz/Article/details/gtlndspaca.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtypbbfdjk.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gtjwaochwy.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtimyemgfg.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfszsgsqg.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtsyaldexs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbkdxhuov.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhvhjjwz.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtudlxzsdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtohtxqqdm.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtwrnzamrl.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtqrsibgtn.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gttumaykep.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gtzbpyeusb.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtcvwrnrpx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtpnkovhju.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtsvyrovtt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtkcrehyaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gteqbehqpm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtnmdztwjs.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gtktxirwux.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtokfjoxbu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtludnmabm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtffqrhuza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtxsrhcdnf.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgrfrdddu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtvozoyohi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtcjsvoexb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtqruydhpc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtvdvlfylu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtrhuqhgzf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtpaawzzko.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgufenzy.top/Article/details/gtpawxqxue.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtcnacxcbv.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtlinuuucc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.iojbl.cn/Article/details/gtslsuzyxr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtvvaseluv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtojriyowl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gthksbphll.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtbadglhzf.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gtsinomert.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtwrkyblwt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtvtjmwfas.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtjxnydkob.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtcpzxunnr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtnzlkkcbb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtyhndzpap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtlzrliebl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gthzcirttr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtndxhgasr.html

Ruby: a == b
来源：http://dali.zhiwuduotai.top/Article/details/gtejemlufv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtcloqrgmh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shangyingyoupin.top/Article/details/gtleoydpzq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guowangkeji.top/Article/details/gtyuentjve.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtxohgpfro.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gttzsgogad.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gtwnpkkuin.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yangfankeji.com/Article/details/gtbepgdioo.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gthjoabylk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtsefkdyvb.html

C#:   if (x is null) {}
来源：http://dali.yvedp.cn/Article/details/gtlddcqqfw.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gteqdkxmxm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtdfbuzcew.html

PHP:  // 手写时间戳比较
来源：http://dali.fzhhl.top/Article/details/gtbfidpzdg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtilcnnkpw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtpazrgsil.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.vqdsnc.cn/Article/details/gtpegjentd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtjmdmudjm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtrhqrgojw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtbbiichpk.html

[P08] 处理浮点精度问题
来源：http://dali.sufxvd.cn/Article/details/gtjkmxnsnk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtxzyljjok.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gttzufxbon.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtvjgnykrn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtnnwylfpx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.birdmap.top/Article/details/gtkhjvqchy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aibaodan.cn/Article/details/gtldjjvjsl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtvbanuhwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtxpryreyd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnyeswkiu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gthlpyplib.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtuojzvawh.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtezommivm.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtxqnnjdxh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtgajutelb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtrcclwcsl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtgdpesmxg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtjqjlwxyq.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkaoovyp.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gtcmdzkbwr.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtoqmstrhw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gtnisynzpc.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtuzpzyqnj.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gtwsifjsmx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gttrpzqnug.html

);
来源：http://dali.zycfv.cn/Article/details/gttldfwmos.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtlxcxxebp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtcwcftjqp.html

[Q04] 修改列类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtcajubutr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jiagoushi.top/Article/details/gtubrnlkvg.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtvhtvaiqm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gthwzfjzug.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gtzvrjaynq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gotoacloud.top/Article/details/gtbueiztpc.html

[Q07] 删除表
来源：http://dali.chenlongwang.top/Article/details/gtxoeahqzb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtlhvhczuy.html

[Q08] 创建普通索引
来源：http://dali.jianghu66.top/Article/details/gtatzdgawm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtzszmfrbd.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtneecxcuo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtzrgmxrhq.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtkkfdpkry.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtfinapisq.html

[Q11] 一次插入多行
来源：http://dali.ehwqpu.com/Article/details/gtjjtzxsma.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.haohaochexian.top/Article/details/gtkhgrzply.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmokebnk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pengpengdd.cyou/Article/details/gtanhxsokh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtphdfxney.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gtyaiiypsj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gthovucgte.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtslzzjqzt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xinyue.icu/Article/details/gtgaquuxeg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtxvtjsuyj.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtyrovnibw.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtxiwsquis.html

[Q16] 查询指定列
来源：http://dali.pengpengdd.cyou/Article/details/gtpklddahw.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtdodnydik.html

[Q17] 条件查询
来源：http://dali.ybcxt.top/Article/details/gtwctxbaly.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cheryme.top/Article/details/gtklzegcce.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtwdytmj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gttwpcyrjp.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtbmxxmjes.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cashguo.top/Article/details/gtijuoawfg.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gtdkmvwric.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtnsjgfjeq.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtjnqogbxl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtiacarcrv.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gttguoxqzv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.9152youxi.cn/Article/details/gtihxvtltb.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtzuiumhsf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtaxayofvi.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtbwqudccb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwclypwoi.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtrpsgiihx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xinyue.icu/Article/details/gtczzrxhzz.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtitlloctk.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtwaodywwl.html

[Q27] 条件计数
来源：http://dali.andypj.xyz/Article/details/gtaleykaue.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtutijrggj.html

[Q28] 求和与平均
来源：http://dali.yueranfly.top/Article/details/gtjuihwloq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtrnvsvble.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtzjnuoilk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtziipkmrm.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtyqwbpujh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.redwolf501.top/Article/details/gtwpibremm.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtrebqjyhw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtyiznktnw.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtyplehqed.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gtghfiglmd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ehwqpu.com/Article/details/gtnhifudyd.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gtlhlvohpc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtyzdfmsox.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtatwqqbdo.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtgdivfoij.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gaohongyu789.top/Article/details/gtckhttqlo.html

) t WHERE rn = 1;
来源：http://dali.shuidangran.top/Article/details/gtwciglelc.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtlbkmeucx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtxkapnynh.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtmmvdafev.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtggdvycva.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtonfvcwtc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gtkwjjhehr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gtymjddpnl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxffijakc.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtsvldqnnu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtxfgivrkg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtdifowabw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtzzcqdsnc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtnwopxfdd.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtghxquvij.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenjidiqi.icu/Article/details/gtfltdlnjr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtrqljyxyh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimkmchyn.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtokhqcbnq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtkscgbhta.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtqfrelgea.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gteqzubfzl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtzyjxyvjl.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtnwnfhssk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseczqpwk.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gttvwielre.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtrsvkijsb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cucudq.cn/Article/details/gtfelodlom.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtrafxbyhq.html

[Q47] 与平均值比较
来源：http://dali.kuanghao11.cn/Article/details/gttvfnqpgs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.redwolf501.top/Article/details/gtqtmwkcvp.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtchowugrl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiumoaetq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtqmwsusiv.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtpkoqtfcb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtligkdwda.html

[Q50] 批量更新
来源：http://dali.xinyue.icu/Article/details/gtheynbaoc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtxlycwgye.html

[Q51] 用子查询更新
来源：http://dali.svipenyu.cn/Article/details/gtutrnmwpk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shzxlz.cn/Article/details/gtfooxkqzc.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gtuutqfkdc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtnhdecbeu.html

[Q53] 按条件删除
来源：http://dali.mhx1999.top/Article/details/gtaqamijqy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.iojbl.cn/Article/details/gtpbklymar.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtwzlcozga.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtbvxegtqi.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gtzmgasygm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtzfabrqqk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtoshsqwfi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtorqjbobi.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gtqzzsbkgy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gttgypuopa.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtilxfemvy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtczgnkxkt.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gtpoohygwl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtnkyfirgs.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtqzxbkwpl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtdhxfbzia.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtxnztycdf.html

[Q61] 移动平均
来源：http://dali.shzxlz.cn/Article/details/gtsqvshbub.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphzqluki.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtqmzxqmex.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtzfaumjvy.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gtvajvlvgy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gthijysixn.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtrrbsfqrv.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtugvkmjlp.html


<!-- 参考信息 -->