代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.andypj.xyz/Article/details/gtdgwwvfxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gtpeidzndf.html

[N11] 二叉树中序遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqobcpke.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gtjecyanko.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtgfezieus.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gthxanwbhy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cashguo.top/Article/details/gtimrgaezi.html

Java: // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtvamyqiew.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtekvzychi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gtpbeoprvn.html

C#:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtinwfkxup.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.quarkkingdee.top/Article/details/gthkdmctem.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtxosafuja.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtoljnmlgt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtnjxwgmkt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthndjcsyd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.9152youxi.cn/Article/details/gtnsrkyvho.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtpzkqzrid.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtvovlnlvb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtkhceowgu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgquhhwwn.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgaarani.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthdwjjqkz.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtjkzuydxr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtxtwmldfu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.feifeiyinyue.top/Article/details/gtsrlagxic.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtasvesyeo.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtulhvenfn.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtmkdvtfkr.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtctdfojim.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtehbyzapu.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtgqirnjfu.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtkmgbymoc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtejhhzueq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gtfrrklebe.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gthnklbasv.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtkuqwdwvx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtfdrxgxhx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shuidangran.top/Article/details/gtwktidrhe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtfckvzawn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtahnjzsdl.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtutwtkttk.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtaixdfxzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.meibo888.top/Article/details/gtgsxdbhno.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gtvessvxea.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtyobkmxhl.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gttwjuechb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtupymoblz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigufen.top/Article/details/gtljdacyid.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtaacvyuue.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmjhiagi.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtpkhpxxwo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtwzbmsdln.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtitsokqma.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtvnujixtu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gtjwuvtxso.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtmbynczhf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtljjzmuiy.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtyzcbhzay.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gtrrpcttvo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtrxmqvaxi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtthbxvwlu.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtnohysbxi.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtbhnhruhi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtcnuxbhes.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtdaroyxrt.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gtcyaubhtm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gtmrwtfhuy.html

[O06] 使用进程池
来源：http://dali.wangshuangyany.cn/Article/details/gtticjxhfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtxawfqnwh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtednohwvg.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtjeaueres.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhghyuee.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtaegkcejn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gthjlomgmi.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtfxleqcob.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gtclozxogn.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtapkmzqjg.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtmjwelbmq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwhxumndz.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtnjrmcyio.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gtmbvygyfh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gttqucaykk.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtlqnuvndb.html

TS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gticjlsphu.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtbaheikwl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hywenlv.cn/Article/details/gtgzpupsid.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gticbkuplf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gttcraptwq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtqakkywmy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtujdcwcbg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.quarkkingdee.top/Article/details/gtzupkwaii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqfpvqin.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtvtkpuwsf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtkjlqjqpw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gthjwceqhw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtaxfgkiyb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtcbohuiio.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtqpcueqkx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtetxqxbuh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtnzbxaxjn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gotoacloud.top/Article/details/gtdpyybnvb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtqpxwhyxf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtusdrdxmz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gtmnurgxwk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gtlyotiwpq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtcezpvryk.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gtafxqcdno.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.dianchejie.cn/Article/details/gtzohrczww.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtotovhqdw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatjfxkfo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbioygupq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tanke756.top/Article/details/gtpjcpharx.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtlapcwcwq.html

Ruby: x.length;  x.size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizvilqhp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gtswhjwbvu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtrzxgsyzr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtrmtlnwcj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtrqwlilap.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gtifaozjze.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtgesaytko.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gteynekdhr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtfhycosno.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtstdelfrm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfzckeyc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtohtogqti.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtsrrvzgpi.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtgvvhpjqw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gttzyfgwwo.html

TS:   if (x == null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfitoajfk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtgepfobrl.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtakocqmtj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gtkpwglvcs.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtsqywnuxo.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtdtygqkuy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtvmzhdksx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtznvtzlhh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtkwqwtkal.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtaggzbzfk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gtzzeoncgi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gthpltzdng.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtidzrbtxi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtlvozsnrc.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtcsdiccrn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtxpkhxleg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gtnfvvawoz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtnstkcvqc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtjrwdempw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtsaxryvay.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtowsljcfz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqybgvbl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtbdxdcwry.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlesicrrr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxinkj.top/Article/details/gtolbjlbru.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttytsgzxg.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtskfzkyrx.html

CREATE TABLE users (
来源：http://dali.gogol.net.cn/Article/details/gtxkziytlz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtslsdcnop.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqporztr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxwcjrxb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtzlbhcpyc.html

);
来源：http://dali.yuanzhike.top/Article/details/gtxiodoczx.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtmgctezcc.html

CREATE TABLE orders (
来源：http://dali.shangyingyoupin.top/Article/details/gtbovqxxli.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtxlasbhmf.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtvtnwiurj.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtwfdojtxq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtxlgmqyka.html

);
来源：http://dali.cdnleiting.top/Article/details/gtcgtpjdys.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gttcbgssiv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtrbzskzzv.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtsuttbdxm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtsyieoulp.html

[Q05] 重命名列
来源：http://dali.pengpengdd.cyou/Article/details/gtlcyrbxik.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangdashe.top/Article/details/gtydlwumzi.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gtxzqclsmx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtiajdqcng.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtkfdmvbjo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtgyxxplzf.html

[Q08] 创建普通索引
来源：http://dali.chenjidiqi.icu/Article/details/gtsnkmjasb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gttvgtshuy.html

[Q09] 创建唯一索引
来源：http://dali.aibaodan.cn/Article/details/gtapfudtev.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtrawzuotc.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtzfxhqefq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtvafhfrzt.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtluklopmy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtgllcrbrw.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gtjapktxul.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenlongwang.top/Article/details/gtzhczsehk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtluzsrxvb.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtvxmwvpls.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yueranfly.top/Article/details/gtsqufpkkb.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gtjldkwzyr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloojsugw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtplnroebm.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gttwargtla.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtydawtxyp.html

[Q16] 查询指定列
来源：http://dali.zhengqikj.top/Article/details/gtcozuaslo.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gttaqrxebq.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gthzgdtkzc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtcuxeezsv.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtyoinpwub.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtxnoyjfse.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gtrhhyidmt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtzmcnufzn.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtadmfwrxk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gtiutogukj.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtdmymnbbb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cashguo.top/Article/details/gtxrtqaxzq.html

[Q22] 排序
来源：http://dali.xziqi.cn/Article/details/gtrzhcdnrf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtoutwtymi.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gteoxvvpvv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhengqikj.top/Article/details/gtkkmomxai.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtimasrjmi.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gttpzbkkof.html

[Q25] 只取前 N 条
来源：http://dali.ehwqpu.com/Article/details/gtepnyjiju.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtaefpsrjm.html

[Q26] 计数
来源：http://dali.tianlin.xyz/Article/details/gtaepvjyra.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gtcpwrxwzu.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtsjvotqhu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgagrrcuq.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtlqfbldqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtjzbucfvi.html

[Q29] 最大最小值
来源：http://dali.jqgfzy.top/Article/details/gtizlvzxoy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdewcdfxp.html

[Q30] 分组统计
来源：http://dali.iojbl.cn/Article/details/gtwstcbqdo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtyksozise.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gtcalcaazm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtgjpuxpgb.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtkzvogwhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtonxyfgox.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yanxiufei.cn/Article/details/gtzelnazkj.html

[Q33] 多列分组
来源：http://dali.wangdashe.top/Article/details/gtftcfuxvq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtdiwinequ.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtlkgbqfwm.html

SELECT * FROM (
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwmkjwvb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtdbsjcjda.html

) t WHERE rn = 1;
来源：http://dali.gotoacloud.top/Article/details/gtzmhgymdj.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtqckeutoe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gthdqhwwsl.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtvxmfczbb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtpggkmoms.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gtrypsqubn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gtooidfyll.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtymvkkhpd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepngjgbm.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gtojqfmlkp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtrwbuznti.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cqqwz.cn/Article/details/gtrgvegslp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtrimnoyct.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtcrfslpjt.html

[Q41] 多表连接
来源：http://dali.yj202588.top/Article/details/gtnocmhgbk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulspmvrf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xziqi.cn/Article/details/gthaevelky.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrsqvazq.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtdlvkpwlo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtwapxblrg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtspsthcwg.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gtgvjzczyt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.andypj.xyz/Article/details/gtmixysttv.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtnmdydodz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlnhrlsl.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gteqzhrreg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtczlayzaa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jyoumei.cn/Article/details/gtjqtohsrk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtbifgxntu.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtzkvpwdqd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtfbaiqonp.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigfzy.top/Article/details/gtsprnzmde.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtcishitij.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jyoumei.cn/Article/details/gtkexsnkwu.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtbzaoxove.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gthzrdobhh.html

[Q50] 批量更新
来源：http://dali.wangshuangyany.cn/Article/details/gtntawzjvu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtycmrdmcr.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtjvgnwfns.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tian-w.cn/Article/details/gtgyrhgkxc.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwgkwwhy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtfqeqkpju.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulsaofbx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gtcusqvndd.html

[Q54] 清空表
来源：http://dali.xziqi.cn/Article/details/gtbhqphsbg.html

TRUNCATE TABLE logs;
来源：http://dali.yj202588.top/Article/details/gtpadhrdqp.html

[Q55] 排名（并列占位）
来源：http://dali.jlsjyb.cn/Article/details/gtyxhipfyk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtmlmiorxf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtexswyycf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258888.top/Article/details/gthpscsdbe.html

[Q57] 行号
来源：http://dali.yuanzhike.top/Article/details/gtciukylud.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtltsjvqbb.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtibptxgoa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gtkckaxoqr.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtwbrcflpd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtupykuzgv.html

[Q60] 取上一行 / 下一行
来源：http://dali.hywenlv.cn/Article/details/gtojiroikq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtvggtwiyg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtrhumpgxb.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtddjzsczu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtfqaiefos.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gtsfirlbpd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtbtvmjpga.html


<!-- 参考信息 -->