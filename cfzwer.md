代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqktpipuq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtxmgzwluf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtbeljuxgf.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gtdbovtlew.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtfsejutfl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yuxming.cn/Article/details/gtghtjplqx.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtrbehhbev.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtdudbbovf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtthvorgzj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtfpejxcqo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gtywdcxeju.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtuvflqvcx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtffhksqyf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtkxjtmtnm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jianghu66.top/Article/details/gtoxwkmjhy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtppjzyhxv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdrtmgeca.html

O. 并发与异步
来源：http://dali.dashuyun.cn/Article/details/gtqykivrgr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtfoosvlwk.html

[O01] 启动一个线程
来源：http://dali.zycfv.cn/Article/details/gtpeszzoge.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtamrtkeel.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtgqieteup.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtvkkbbrkj.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtwnsszavl.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtqrcotjbe.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtequjfydl.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtlztkdtcj.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeutvhni.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtrfcwsgpp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtcdeoeguk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gaohongyu789.top/Article/details/gtlhlmwavo.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtzfjaztfo.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtwvjuabef.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtwfojsbyg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtwidgjrjc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gtdglghtsc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtyunrysqq.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtaoajeosx.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtbmzgknvm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtaczashmz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtywaptfdx.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtlnayrxij.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkderlyyh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtmnxkgeey.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtvsxubuot.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtnqniwiyw.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gturbmbufz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gtdjndjyuw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daxiang520.top/Article/details/gtahzcqbnf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtfhazmepm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtquowmlld.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gttzifxduq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gttjndwfuq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtduvdjeed.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtemkgiirz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtgbfrqxcq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnwrkesu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpkwgquc.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtsajnnjcc.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtifygoiwr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gtpwgbbbxq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtiqrmqoqe.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gtlycbbozt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtixbrzwdi.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gtvuvokybj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtfwdbagvx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gtwfzwnrkp.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtlswfrasv.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtaqmoapxe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtvunthmbp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtbhitbqhr.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gtxwmyyaol.html

C#:   Parallel.For
来源：http://dali.havefunace.top/Article/details/gtpfrpkbvm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlckynjuq.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtnfxjjuyx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcomxhbiq.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtdjidnxaa.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtfqxeyfsd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtujsxetft.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtdemzqnyb.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtjazjamqy.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtzhvjpdwv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gthjpmgiab.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gtmpmjcctu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtemadojkk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtxtkdutjf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gtbzcbhenf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtllxhlfak.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtehtlsokg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.iojbl.cn/Article/details/gtyncvelyt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtdckhtjtr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtyhirwzku.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtvydbrhda.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtapvszogd.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtwajkueqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtvllqxcwv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gttyzmgabv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtjlispkbv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtqxbilocb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtvkxracus.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258.top/Article/details/gtktlvsokd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtmwooxvdz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtussfjtyr.html

[P04] 求长度
来源：http://dali.aizwys.cn/Article/details/gtqulmdfhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gtgywvbwfk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtspmaajyf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtaeibuvic.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbyesnsa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtecyaoios.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtuphpwrer.html

Ruby: x.length;  x.size
来源：http://dali.sxryk.cn/Article/details/gtxvjkawgo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gttjndfvyj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtbthstzlb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtfegicpfs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtwefudffr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gtfleaqkms.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtdpmuhlhd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtzchnnzhl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtoaruanyd.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtewzvbcsv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtkyuccyhc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtvscorepp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwxtyzto.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtlhfffoej.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gtsybhatsk.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtfgehxoxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gttupamqie.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtwsehlilu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtwvbyeded.html

C#:   if (x is null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyziuwbww.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtumbwhgoy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gtbvrbhpeg.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gtfvjqfwkb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtllvjupyg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtlnuuujof.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtqvwbctbg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yangfankeji.com/Article/details/gtzzuloavo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtuslyjqaa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj20258888.top/Article/details/gtrriciwzg.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gtgalnzkfr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gtetznavmk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtcburasnp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtarpqwktz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtbelpxkxo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gttxpfonne.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtakmbgcsj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbnjlmus.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gturmkzmiy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfpxqxzpf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gthaoxlcuc.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtxntncqxy.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtxnhvgfgb.html

CREATE TABLE users (
来源：http://dali.yueranfly.top/Article/details/gtzlcphhst.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtbwvrecfn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtngkuayzn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gteycgttyk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gtuhlinizz.html

);
来源：http://dali.ybcxt.top/Article/details/gtflgbmblg.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtycoahgag.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtqhptezvy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtkfycabzl.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtbzvkerth.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gtqhywtmml.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gtxiylfsom.html

);
来源：http://dali.cashguo.top/Article/details/gtxwanbpge.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gtrjbmlfqy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhoulong.xyz/Article/details/gtgzpuidle.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtirtrijdt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtxgztptjc.html

[Q05] 重命名列
来源：http://dali.tian-w.cn/Article/details/gtvrdtvdif.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gaohongyu789.top/Article/details/gtqxzmabsd.html

[Q06] 删除列
来源：http://dali.sysykeji.top/Article/details/gtniyfjkib.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tianlin.xyz/Article/details/gtzskzfoze.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gthlmwducr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxinkj.top/Article/details/gtaectghoi.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gtplprgyul.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tanke756.top/Article/details/gtqtsxwohn.html

[Q09] 创建唯一索引
来源：http://dali.yj20258.top/Article/details/gtouofhcmp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcczdywo.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtdbraaclm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtxunmrosk.html

[Q11] 一次插入多行
来源：http://dali.yanxiufei.cn/Article/details/gteovoqlig.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gtftvsytgv.html

[Q12] 插入后取自增 ID
来源：http://dali.nwbrower.top/Article/details/gtolxvejbw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtnrpjyblz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtxqfkwcvf.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtjqwuqvmf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtvntypbnd.html

[Q14] 存在则更新（upsert）
来源：http://dali.hammf.cn/Article/details/gtondveomj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ivvv.top/Article/details/gtioapekhb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.shzxlz.cn/Article/details/gtsynqdgzj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gtxuetvsbv.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtmcoxrbgf.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtkbsodplc.html

SELECT id, name FROM users;
来源：http://dali.birdmap.top/Article/details/gtwavawdtz.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtpxhdgpzp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtixjwvmij.html

[Q18] 模糊匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvqgbxaf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hammf.cn/Article/details/gtlsacitrs.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtjdoxzcyb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtvkyugpjz.html

[Q20] IN 列表
来源：http://dali.iojbl.cn/Article/details/gtmaylhuzt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtnigxezqn.html

[Q21] 空值判断
来源：http://dali.tian-w.cn/Article/details/gtkcvbogvd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtprtgljsp.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtjqqywbmt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gtvtzvqqzt.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gthsexsjrx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.daxiang520.top/Article/details/gtwxcteaho.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gtdtajemll.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtynmuagaz.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gttncyisbz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtelqhbvyp.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gtfosmflva.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gtzxhumzwh.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gtzthlucrk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtxxohnpky.html

[Q28] 求和与平均
来源：http://dali.guowangkeji.top/Article/details/gtjgpdktcr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtoduhcioo.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gthhghkbfo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtidiqqevg.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gttjlnaxjc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtdcyjdxik.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtrlsjlnaa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtujxppcda.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtrrhwxzbj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtwuuyzgzd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigufen.top/Article/details/gtvdbbbpti.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtuoupgwco.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dianchejie.cn/Article/details/gtgcuprsmf.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gtxaczbgdq.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtfeiapgao.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtstifhdyx.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtmnbzgxih.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtnnerqnpu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtooizzuvz.html

[Q36] 左连接
来源：http://dali.nanxinkj.top/Article/details/gtiigrohyb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtefrozmwe.html

[Q37] 右连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtndylqfow.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtslbhfuit.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtrgnmsgew.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gtcuqafstr.html

[Q39] 自连接（查上下级）
来源：http://dali.guowangkeji.top/Article/details/gtjlfitwfr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtdsfdanwq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhengqikj.top/Article/details/gtdsbuelcs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gtkjgtryko.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtsajbmhjx.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtdpfnhgvw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gtfsvcglic.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnxiangtu.top/Article/details/gtzfwhiqgv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtetzdourj.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtudelufze.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhoulong.xyz/Article/details/gtdiumwdwq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtrxlbnagq.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gtvztaitei.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jlsjyb.cn/Article/details/gtfrefnfzy.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gtymvibudo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shzxlz.cn/Article/details/gtjfmzudcz.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtszounnko.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gttzahmwzk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtwczlmhtk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtfzpgwpmj.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtaqsrsvcu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gtkfyhbiql.html

[Q48] CTE 公用表表达式
来源：http://dali.bjfxy.top/Article/details/gtrzwferme.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtovnplurc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zdqjudy.top/Article/details/gtisoxbhde.html

[Q49] 更新单行
来源：http://dali.svipenyu.cn/Article/details/gtsxitqiiz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbmdhhqc.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxswadzz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtlswpwjgp.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gttukuwspr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtozvlayuz.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gtsolhpeqf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtochxxxad.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtnqeeqoao.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtieoertms.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gtibhqkbzs.html

TRUNCATE TABLE logs;
来源：http://dali.c1oappe.top/Article/details/gtjrnytgyj.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigfzy.top/Article/details/gtivmoeils.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gtxgfyfgfc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gtcdjrohoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gtfdylhmdw.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtvvqfqela.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrssrrgb.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtetalragf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtzaafmyoz.html

[Q59] 分组内累计
来源：http://dali.yj202588.top/Article/details/gtuqxindsx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtdrzcuupc.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdmhzjwq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jiagoushi.top/Article/details/gtgiykzyqo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtseztpztv.html

[Q61] 移动平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwykukemy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtaaxoixrg.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtagcovtax.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsbjyjok.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtlozcwfth.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtgnxzalwf.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtbqnhdupt.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtlehkzycx.html


<!-- 参考信息 -->