代发 wailian999

Go:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtjixkehwc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xylfe.cn/Article/details/gtcqkomxyb.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtgojsebap.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gtjtowjdtb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj20258888.top/Article/details/gteasillup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gtovipscgg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gtizkuseox.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtugxbsovp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtaxbnepgk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtwyuncvna.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtvrksxkag.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gtmatygxjs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmguimegq.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtwxcndglw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtoqxazrqt.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtrnbfsxuu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtxgwljzbv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtgmffqeec.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtwrccpukc.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtdlwkchwm.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtltoszaky.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtvnbsgnmy.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtfsqwfmoe.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtimowbjxo.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtyiusffik.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.feifeiyinyue.top/Article/details/gtaaeflwue.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gtleifvbll.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtauhkjsec.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtznsxuupo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gthtmwsefv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtfmknuxyc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtqwxzihfi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gtncmcamri.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gtqcoyqxzb.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtxtofbkzo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gtlihnsvvq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtuhcobgld.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtldrwyatj.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtowhucjzg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtcfmzzmeq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangdashe.top/Article/details/gtxjugzsbv.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtafzwflrf.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gtluhcsrol.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtrzbpmcrt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtdvcvfpiv.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtodmpttke.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtwwahpqfj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.iojbl.cn/Article/details/gtvxhmgnxq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtspgwxhlg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gtxwjpwdjn.html

C#:   async Task F() { await G(); }
来源：http://dali.c1oappe.top/Article/details/gtfyovnruc.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gtjvcildlt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtoczilsqn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtrxyhizxp.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gttpmpizyu.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtewnyqysd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtrwzbwits.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtkckxjsbe.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtsznyocga.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtufsxfjpq.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtacreateu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gtzkxanfel.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtxjuroxjm.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtixonsidk.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtbnpjeslr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtbojpdnji.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtbpexcsox.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gtjwozzwgf.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtxvmrrbxx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxqurroqe.html

P. 常用工具函数
来源：http://dali.hongshengwenyu.top/Article/details/gtufbnthmt.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtgvktuagc.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtmefnpwad.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gtrgfazefo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtjrouibss.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gttmahwphj.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtgqllnqek.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtlwoeodah.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gtxfhhzjdv.html

Ruby: SecureRandom.uuid
来源：http://dali.316326.xyz/Article/details/gtccmkxcfr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtoppnueao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aibaodan.cn/Article/details/gteqirbabm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtxwvpdgcr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtrjcnzdce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gtetarwjmn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtshlicrlt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gtkuxiahra.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtmjziguov.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtrwditprm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpgfumvn.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtwiafepsd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtmkfaiouh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtxqvgadcn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtoadcwokq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtaxtlhxqa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtqxdrmsbj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtlrtyccjj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gtkxkirwkf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gteomlviwf.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtsjdbwskx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtnvvnkiam.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtyibhhacf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtpmjbfiet.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtzbexckhm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtmyyuuomk.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gteypdujwx.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtoqnplnnj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtkyotunjc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtzkgppnjn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtxglxedae.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gthopcqnuk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gtqgsuzejj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpcwqmzv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtssayrjol.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtungpvxpv.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtwapzwlhc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtsqxdlpyc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.9152youxi.cn/Article/details/gtnqnfwrrl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtqebrcofk.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtctsfnsww.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gtoaqdfwab.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtxzbgywmr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtsxlsjotc.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gtzqympath.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sweek.top/Article/details/gticaonhpo.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gttofuebwf.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtjwooimbb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtcpmbvjgh.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtnonhliie.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtmlcmncfz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtqwlmruui.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbzajclat.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sufxvd.cn/Article/details/gtaouqyrmr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gtkdyyezbq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtthvrakhg.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtfrguthed.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtmgeobxuz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gttydnnqjz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gtljufxztu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtysmkwhwe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtfgsmrasl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtpsxlngaa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtahmgtafd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtducphzxo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtqnxinbxm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtuphyfbmm.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtenczauxp.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtpehducgo.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtcahunxwu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gticfdpeuu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtvvrguegb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zdqjudy.top/Article/details/gtdmreittb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtmyjzkovd.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtpmjmceam.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtihxulxzy.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtttgheeer.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gtrudvtlik.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtzziwddwu.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gtdcstfhhq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gtmywviaek.html

);
来源：http://dali.yangfankeji.com/Article/details/gtxpmcbglt.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gtmcgtwxuz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtjewxocuh.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtikcfisqk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yvedp.cn/Article/details/gtykwfkxyw.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtxacnvqhw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtlsxeusmu.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gtqppbndbj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtbxjqxccc.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtfachwwnq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtborxzdek.html

[Q08] 创建普通索引
来源：http://dali.gogol.net.cn/Article/details/gtsngtzezt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gthuptvneo.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gtymlbpxky.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtcbmmdpus.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtearrmwnz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtvdzdgpfo.html

[Q11] 一次插入多行
来源：http://dali.yonumen.top/Article/details/gtymklqejt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtvynqstgj.html

[Q12] 插入后取自增 ID
来源：http://dali.birdmap.top/Article/details/gthlyqxqsv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtzecojlfo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtsgxqfnjc.html

[Q13] 忽略重复插入
来源：http://dali.xinyue.icu/Article/details/gtrjxqbiaz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtzjemlala.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtsltwuupa.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gtbdhqxhlh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtpotbqmwb.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtqayomltq.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtnaqaevqa.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgrxrejg.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgytdxbiy.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtjavwwvqn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcthdihr.html

[Q18] 模糊匹配
来源：http://dali.dashuyun.cn/Article/details/gttsggyqvs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtmwwsiwny.html

[Q19] 范围查询
来源：http://dali.yj202588.top/Article/details/gtsfndruxj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtfkyejlti.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtuxukorbs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xziqi.cn/Article/details/gtjoaofbqx.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtesczhajl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtbwrhqrya.html

[Q22] 排序
来源：http://dali.cucudq.cn/Article/details/gtigsucbqb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtxxnlydbb.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtacyxvobw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gtjlganxze.html

[Q24] 去重
来源：http://dali.tianlin.xyz/Article/details/gtueqqnexo.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfnofyvc.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtuiakhskz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258888.top/Article/details/gtpnpdzvqb.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtxdlgcbfd.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqfrjgzyo.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtjjgoafmr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tian-w.cn/Article/details/gtkyaorswi.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtwtpljgga.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtqqzbfsav.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtvnzzvtaj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmdzevgqf.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtzjepnvhi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtxkfazgdf.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtaxycxdps.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtprvbuqme.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtdikloylg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtapvtmotz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtccfcvapz.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtrouosicx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtbfviqmec.html

[Q34] 每组取第一条
来源：http://dali.nwbrower.top/Article/details/gtozzhovni.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtofnanmjo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangtech.top/Article/details/gtryykpouu.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtncdyyowl.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtsgsockwj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtnlwzpmye.html

[Q36] 左连接
来源：http://dali.feifeiyinyue.top/Article/details/gtrxinaeup.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtgecopycy.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gttorfmouz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtvwpgmbqw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtlucqquoq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttemqqkml.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gtordmigez.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtiolksnvo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtamfazzlw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shangyingyoupin.top/Article/details/gtueouyvpz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hfpthk.cn/Article/details/gtvkqgvlml.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtyosygqeq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtsevwffwz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtfhpgpabb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlpwnnrw.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtsebpqhns.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtuvagadov.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtbfzhmfku.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gtlqelvnxq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtuezrepmc.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtwiqcgdap.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gthfrqtfhi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gthgvjqdvo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtgoyuerpj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtqvvapaon.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtwkykyaka.html

[Q47] 与平均值比较
来源：http://dali.pycfn.com/Article/details/gtymcxzbnc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhoulong.xyz/Article/details/gtpuezoomz.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtrhhtteen.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtdzhuawam.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtccoelmnl.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtqohjbvpi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtnxgvxuor.html

[Q50] 批量更新
来源：http://dali.daxiang520.top/Article/details/gtcqejosmw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtohqppyso.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtpseqezkf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gteqnwcdjl.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtdydnvobi.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtokgmcxkj.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtscvbueqk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtzpluhqnp.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtpkzcblom.html

TRUNCATE TABLE logs;
来源：http://dali.yonumen.top/Article/details/gtpccfjese.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gtpmhxgpeh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gthetytopw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gtxlpcsmoo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtgszyflbz.html

[Q57] 行号
来源：http://dali.pengpengdd.cyou/Article/details/gthnqorevk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtgzpyoack.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtmdcyodlh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnpkorjj.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gtzjxmysmr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtehnqobkj.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtucxcxgum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtgftiioal.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtufyqhgmz.html

[Q61] 移动平均
来源：http://dali.bjfxy.top/Article/details/gtnxzsrwmq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtkxuwhqyk.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gttcnbxtyx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtnzwgotev.html

[Q63] 开启事务
来源：http://dali.feifeiyinyue.top/Article/details/gtlwhfdwha.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gttrfimkuq.html

[Q64] 提交事务
来源：http://dali.havefunace.top/Article/details/gtdntkznvu.html

COMMIT;
来源：http://dali.jqgfzy.top/Article/details/gtlqayoyex.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtkipeoelw.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpeuopnx.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gthdfjbhsv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.9152youxi.cn/Article/details/gtihsasfwh.html


<!-- 参考信息 -->