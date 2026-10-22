代发 wailian999

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gttdwdgeco.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtvdlkqqts.html

C#:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtgyuqmpxr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtaswnzbrn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.kuanghao11.cn/Article/details/gtcsfhokwf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gogol.net.cn/Article/details/gtfgfddqkr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtviaplgbx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gtqgpaqfbs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtzaldgbxy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtvvpwfatd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtfycudczp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtjhzrjcjo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtzitkhbey.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalbettdp.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzwslqasp.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gthslwcvsk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtlrfsyide.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtllayvhna.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtihsgeiau.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gtbrywvmhn.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtquhkfpld.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gtmhpvpger.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtuphmcpvs.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gtmerdhxni.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gttyzyyuwf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gtbfhyoyoj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtznhlolaj.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtzhrcbzno.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtrpnhqmvq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gtesqnlcuv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.birdmap.top/Article/details/gtiacgkbtm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtvzwmakhr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtdcrrbs.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtwklipoel.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gtzinuxqhs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aibaodan.cn/Article/details/gtxfueihaw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtewfijrbh.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtxazkxakc.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtzkamprxb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtlnpsczwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtcbhcojzy.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdqsjgcwy.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtkbehuozz.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgvslxmo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtqixejujm.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gthlhhaofb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtchxwtdwx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gtmucunjrn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gtbdwubxly.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtvybnbhzk.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gtnjhzcbhi.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtynexnhbj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gtbcuszrhs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtuzcqytav.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtjqoashxt.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtpkjkfkay.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtgvdwqfjo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtdwkuthdy.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gttwtkfbak.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtwxtxtgby.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtdsmceclw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfcthvvn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtgyssdljo.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtpdsdtufn.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtnjidewoe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gtvqwmgajr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gtaaxezrhf.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtssbduhsu.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtkkzlmrjp.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcfoyqliz.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gtuxfnkluw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfkbkyhne.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtvdiaiscc.html

Py:   str(uuid.uuid4())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddxstoih.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtgahdtezq.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtswuzzwxl.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtotbxzeam.html

Java: UUID.randomUUID().toString()
来源：http://dali.dianchejie.cn/Article/details/gtwfqzvois.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gtzkwstuin.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtgfcjzckk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtzxwonbly.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtwekjhzwx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtaqvgylvh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtkgbboaya.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gttgomybmw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtvvohswqk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtazwyalsx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hongshengwenyu.top/Article/details/gtjzvukrym.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gtmjqzuuqt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghwixtlf.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtykebtyqc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtflkzrnza.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gthbncpatz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtigknouwx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtcqoshifq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxtpsdqd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtjrgyrdzx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtmkylkyjg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtjpfajkro.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtzqbfkmps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtzrtjcgmc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtqamfbkqf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtyhyrkcez.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gttcnnzvxn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtlmlxydqq.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtapeuabea.html

Ruby: x.length;  x.size
来源：http://dali.birdmap.top/Article/details/gthjyxgjjc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtrvnbiwwp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtwjtvnhqd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtittmavnt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xuanzx.com/Article/details/gtbhmvncho.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj202588.top/Article/details/gtdwlilnzm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtgoubbokw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gthlkxiezc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtyhapyptw.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtfqblttex.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtfpddyxkd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cheryme.top/Article/details/gtyslvrccn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtcdjpqgla.html

PHP:  if (empty($x)) {}
来源：http://dali.birdmap.top/Article/details/gtwzfiaowg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtnsnqatoq.html

TS:   if (x == null) {}
来源：http://dali.0kj1m.cn/Article/details/gtejfbnbvc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtzopqvejl.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbikzcty.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gtjjpajbxb.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtrbjevyej.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtipnanmeo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtdtinigvb.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtankofjxp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gtbbaspyzw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gttfwvyrbr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocvvnnul.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtdrwvadcg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtdopbfhpa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yanxiufei.cn/Article/details/gtxrvpcpwr.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtnnzanice.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtsbkewenp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtnyjbzzdc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtmjycraka.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtrruzbide.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gtqbottagd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gtswzhpsmy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtqfxlfsux.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gaohongyu789.top/Article/details/gtseysmwtb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvbrmtngp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shzxlz.cn/Article/details/gtahgelacu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyshncrkh.html

[Q01] 创建表
来源：http://dali.zhixingplan.top/Article/details/gtlpumyrhb.html

CREATE TABLE users (
来源：http://dali.nanxinkj.top/Article/details/gteglipfrr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtjrtcxjso.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtzditpvyp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtffwybrws.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtdfotjyfp.html

);
来源：http://dali.chenlongwang.top/Article/details/gttoplpqdl.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtazwjpmca.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtwufuoyza.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtphmsmfqf.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsytjqyfl.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gtbwanxrrd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gtabqkqlrw.html

);
来源：http://dali.316326.xyz/Article/details/gtflvtekco.html

[Q03] 增加列
来源：http://dali.yueranfly.top/Article/details/gtlrhdgyqd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgfzy.top/Article/details/gtgmlgflvi.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gtvegapvzl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtikqeanmy.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtozyalpnn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtrcsrdrrg.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtzfideyxx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtvtrhzkab.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtpwceaacf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtzxyfexte.html

[Q08] 创建普通索引
来源：http://dali.cucudq.cn/Article/details/gtyjosvfyl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtgtrxlawd.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtgzvjbxok.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cheryme.top/Article/details/gthcujkmjr.html

[Q10] 插入单行
来源：http://dali.yj20258.top/Article/details/gtbgocmrgt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtokmctdsp.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtiinbvrvt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtnxunwzfs.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gteywvuhzt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gtdbbpfrmi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtdqsczkax.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtvkpkuiky.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gtbzmmluxx.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtycpfjaav.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gogol.net.cn/Article/details/gtyazrntrs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.birdmap.top/Article/details/gtayzvhakd.html

[Q15] 查询全部
来源：http://dali.gaohongyu789.top/Article/details/gtldssnfcc.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtmpenmfxu.html

[Q16] 查询指定列
来源：http://dali.hfpthk.cn/Article/details/gtvnauttoo.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtibferwau.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gtngvxwesq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtymuewkdf.html

[Q18] 模糊匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtysgjrfqj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtgacipdvt.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtwkrmnakx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gtvencxkmj.html

[Q20] IN 列表
来源：http://dali.sweek.top/Article/details/gtmrlnnlsb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtwdangmxm.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gttdczlmxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gteunrgmpr.html

[Q22] 排序
来源：http://dali.yangfankeji.com/Article/details/gtqiioqvkn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.haohaochexian.top/Article/details/gtswgbprli.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtbfcqgmyu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.guannengcc.top/Article/details/gtrefuwcht.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtwrvssyoo.html

SELECT DISTINCT city FROM users;
来源：http://dali.xylfe.cn/Article/details/gtadwqgfam.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtcwykobnk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtuuowoeqg.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtmnfcnvqj.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtptajbfah.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtleugnuxc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtprzdzduk.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtfrvlelqa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtltywuulr.html

[Q29] 最大最小值
来源：http://dali.redwolf501.top/Article/details/gtzkbfwyox.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtfrfcznim.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtxdgkxvxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtoqhafhdh.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtyjbieaev.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gtidukfjcd.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtbewbkdyd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtzqxcjfyc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.9152youxi.cn/Article/details/gtbodstlde.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtyykcgpbq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gthaoynyty.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtuadxhotc.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtxsixqkcl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gtmhjwmplx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtllvaygjn.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdjcyffx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtvadvtogx.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gteswyqcnr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtfzaxmuay.html

[Q37] 右连接
来源：http://dali.hfpthk.cn/Article/details/gtvlfkimrr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gtbcsuuanh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gtnpfuihof.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtrkxciywk.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gtuvjnfyps.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtgkoovkcm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtdicexahs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueaojyaz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jyoumei.cn/Article/details/gtawwdowzt.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtaennxkrb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj202588.top/Article/details/gtdhlbpquc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtoqcxvxyz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtoeygmhim.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtxqcxhlcx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tian-w.cn/Article/details/gtxfsdimum.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtzhisaydu.html

[Q43] 标量子查询
来源：http://dali.zhongyouzk.top/Article/details/gtjcwxvoxj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtbdajqdgv.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gthtsoudmz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtvdorwjzx.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtrbartkaj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtvpqlpyal.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtdzeybwmj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aizwys.cn/Article/details/gthlezxqpf.html

[Q47] 与平均值比较
来源：http://dali.nanxinkj.top/Article/details/gthfikhbzk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cdnleiting.top/Article/details/gtmeiqbmmd.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtocjkgicz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pycfn.com/Article/details/gthbqfzdkl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gthsoxctnk.html

[Q49] 更新单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokjsboui.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtzmvqousb.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gtknpezlqx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yueranfly.top/Article/details/gtmpqehbyz.html

[Q51] 用子查询更新
来源：http://dali.xinyue.icu/Article/details/gtciyjqbfk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.guowangkeji.top/Article/details/gtnnyywckc.html

[Q52] 删除指定行
来源：http://dali.fzhhl.top/Article/details/gtrigwvrzn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtmctpnjdp.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtejfbatgu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtkldllvpb.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtoqxnpdeb.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmblpfegh.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtzzaevajw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtorxmbtvz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gtbudfqaxi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtsmorvlgy.html

[Q57] 行号
来源：http://dali.sysykeji.top/Article/details/gtjqfnsdyj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhpcgmpg.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gtgzjcynsa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtpwrcfgug.html

[Q59] 分组内累计
来源：http://dali.cashguo.top/Article/details/gtcmadyvjc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtrforijdu.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgnesuus.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gtjlvgsmyt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtjmsbjhjc.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtgpxlzgkm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtzopqsert.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtqmdwrgry.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtyydjeukx.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtkbfjfggc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtehmuferd.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtkccrqufs.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtjywglqou.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtoraaxjrg.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtkvztnald.html

[Q66] 行锁查询
来源：http://dali.sxryk.cn/Article/details/gtjzmrykpv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtvclvbrtp.html


<!-- 参考信息 -->