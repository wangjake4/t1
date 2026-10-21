代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gtmdwkdvbm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gtxfdamnnt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gtiqcreyux.html

Java: // 手写递归
来源：http://dali.316326.xyz/Article/details/gtblzgmfnb.html

Go:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtjsbzljfj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuetiantiany.cn/Article/details/gtabxnkmcn.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtrgrugwoi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gtflpirjvu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtwdskmkcz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gtpppygxfp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtunvlpxzq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gtuewdllmx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtdhisahaj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtatsmayqo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtzplmrafl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtbjvohifi.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtysrxisox.html

O. 并发与异步
来源：http://dali.9152youxi.cn/Article/details/gtsnnfartg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtevdrgvzs.html

[O01] 启动一个线程
来源：http://dali.fengsongda.top/Article/details/gtvmwdgozf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yanxiufei.cn/Article/details/gtqrtsfzhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtltrhywvg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cashguo.top/Article/details/gtzhmnfocm.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtviioknfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbioryqy.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtdrlfntlr.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtczsqaqvu.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtlcuknksq.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtzwjntdig.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gtdjtwuedc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.meibo888.top/Article/details/gthyfopxpj.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtavygsbdg.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtszpcwmzs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipwmxqzd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtzggfqthg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtdkgtcunj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtvmzzmckr.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gtqdmawwvh.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gtyxoyqssg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfjrnpru.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtydifogjb.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtgwsktjst.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtrpmlevqz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gthuatsvqi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtdfwspqcv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtmbtvlgio.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtufscszri.html

Py:   async def f():⏎    await g()
来源：http://dali.dianchejie.cn/Article/details/gtkudceahe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsoomrqa.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtmsihappi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbqhecfnc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhongyouzk.top/Article/details/gtbkfwvibk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtjefzdgmn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtwfshzszd.html

C#:   async Task F() { await G(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcyzzpxro.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtjumeewoh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shzxlz.cn/Article/details/gtskpyticn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.vqdsnc.cn/Article/details/gtqbuyaouo.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtifuhuhvy.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtwtgawkgw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtzujnikoo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrddpgos.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtefasaaru.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnguwvque.html

[O06] 使用进程池
来源：http://dali.jiagoushi.top/Article/details/gtdzirklug.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtcchjbljh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gtbecvkefv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtuoyyozkg.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtpzrhqvci.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtsyhhbmlh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtdnowpkwu.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtmzxihlqe.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtgpuczxiz.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtncubxraj.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtumrmehrg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlguzcsxn.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtwigquxzi.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtyqvwgeyg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtkblibcpk.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtapcflmox.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtuyultdos.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtxumenubt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtykjvzlpl.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gtmdipihzd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gttpknrmrz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuetiantiany.cn/Article/details/gtahixajrk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtvvjiqsqz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtctvuwcci.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gtozsvqqlb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtvbgkrkqq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtifqmvyfs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtcsojqdus.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtsuzfezzb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gtcrdmtzok.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtvzkhkdkr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtfskvztuz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gtiwstmynn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gteusvdnka.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtmmquhuco.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtakglumiw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sxryk.cn/Article/details/gtiinfduur.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwlhuryj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtywkhpiry.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtdrmqraqj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtukwgxlae.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtomcrxpzs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gttqlwqkyg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtbfozmzkp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtbhfobkmw.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtndeejxuq.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gthdyzikyu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtaqmrhvfg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtkkpxppaa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtdjjfrmwp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtznqqtvfw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtodfvmmbx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtnxnmhwhb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinqigufen.top/Article/details/gtlhwzrjjh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtwrfqamki.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtaykbtaml.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtbhakxleu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtaqpfihea.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtkcsfhxyo.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtoezaelaz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtbfsqxutf.html

TS:   if (x == null) {}
来源：http://dali.yangfankeji.com/Article/details/gtlwkdjocx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gteiebnxio.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gtrnascsoc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gtolwblxhk.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtunuvbqpa.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxbrtcym.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtzpitzctm.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gtemcrkgrh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtcfblwlnc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gtqgvqzvmw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueinfesd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shzxlz.cn/Article/details/gtnhqfmnph.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxlsnmjg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gtksqdgvom.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjuojziwf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtdjrluahe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtrtipibiv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gtyejtpgbj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtvdwgcjgf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsssbbqt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hywenlv.cn/Article/details/gtfgrzpvdd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gtvpldqvai.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtlcbxhefg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtpznmmwnx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gtglbehino.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjmtxmqjo.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtgbmqlvcy.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtkpzninpu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtyksmhvwm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtxexbtpnk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gtpnpoipvg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gtunxmbuik.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtrzxijsuf.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtaxycwofy.html

CREATE TABLE orders (
来源：http://dali.pengpengdd.cyou/Article/details/gtamkvrwcr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtoxexrfoa.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtwkfzlvrr.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtefbqvhlb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtvqmgfysj.html

);
来源：http://dali.fzhhl.top/Article/details/gtmdodirbo.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gterboyfzi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtoqwpggvp.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtezfrdmzh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtqbimtyrk.html

[Q05] 重命名列
来源：http://dali.jianghu66.top/Article/details/gtujiuivfg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gtdvbjtztx.html

[Q06] 删除列
来源：http://dali.cqqwz.cn/Article/details/gtkxxekduu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yonumen.top/Article/details/gthopoleli.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gtkpkpjiuu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqhavcnw.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gthcfxpsql.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtbdlbkqxe.html

[Q09] 创建唯一索引
来源：http://dali.zycfv.cn/Article/details/gtbcmejhje.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtvbwvefah.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtzlvaaosd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtcxydctcc.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtkiimhwsk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtrgtcijrk.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gtzizeptoq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.haohaochexian.top/Article/details/gtumslrdiw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gtbhhufbsy.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtecotpgux.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtvghzgwrw.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gtcfivsdlz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtnwfwwxag.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtunzhpbjb.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtjlbxmqxz.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtnhjphpvk.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtwcxiirop.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtpzihamfb.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gthoadnbxb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtxgscwrcx.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gthqofybjr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.nanxinkj.top/Article/details/gtncagyxpz.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtouustmyw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtsawksoap.html

[Q20] IN 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyytiymh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cqqwz.cn/Article/details/gtjfxmxcqm.html

[Q21] 空值判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvaznxgie.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtifycjvpc.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxovvssp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtcpdwbtem.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtcvjhavaf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtynpumlxl.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gtnsbeqjlh.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtqlbsscmy.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtdcaxfnpk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.fengsongda.top/Article/details/gtaynsmjjl.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtfdfiswcg.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtqjrzlzqu.html

[Q27] 条件计数
来源：http://dali.yj202588.top/Article/details/gttvspvvqo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtrgmkadbo.html

[Q28] 求和与平均
来源：http://dali.jinqigfzy.top/Article/details/gttxlflfun.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtszmubxln.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtmhephncg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtclvsqrud.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywokgapd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtvjgzqsha.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gtebmnmpes.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtzauxnuir.html

[Q32] 分组拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtoerysoff.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtmtiisywd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zycfv.cn/Article/details/gtywyuuedb.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gttdqdmrtx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yongpay.top/Article/details/gtqsiovklx.html

[Q34] 每组取第一条
来源：http://dali.shuidangran.top/Article/details/gtkutdvasx.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtmmpjnkmd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtuwdmeodg.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvulccdr.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtvvsiqway.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtvfnrphof.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtcgcjbtyh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtqcndqxkv.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtwtouuuts.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtgyzcagfl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtjseqklwx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gtpsalgkgg.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtmgejpfyo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gtterowobq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sufxvd.cn/Article/details/gtkrbpwvxn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhongyouzk.top/Article/details/gtdzyuufdm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.redwolf501.top/Article/details/gtdcycsqed.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtpngldobd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtikeigadk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gtmssdfcsv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtedhdmehl.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtirnvfbab.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aizwys.cn/Article/details/gttpnaknay.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtwzfexuha.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtzhaobjtg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gtigouemle.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtummubrun.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gzhubu.top/Article/details/gtyidttmfd.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gtarhkbeax.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gtxzazcvwu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtazaxchmw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtegsdcbxt.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtloconswx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gtsougaceg.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gthikmruoz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jianghu66.top/Article/details/gtekcvtuue.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtkwrzhvba.html

[Q49] 更新单行
来源：http://dali.yj20258.top/Article/details/gtfzrvdmwl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtbdlzfhlg.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gtokpqtrki.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtgpjbdmlk.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtepccwvug.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gttytyiehd.html

[Q52] 删除指定行
来源：http://dali.snrcjt.cn/Article/details/gtgzlrdyhj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtvkqevxwy.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gtufqsxcpa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtkjyqgtwi.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gtwhbnkuvo.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtfzaemycs.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtnojjemwg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtidwcmaes.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gotoacloud.top/Article/details/gtwarsdwsh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ivvv.top/Article/details/gtucxrdtxe.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gtrnzupmft.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtlgupqjgo.html

[Q58] 累计求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnwzsuqo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtarshueot.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtthwpnrrq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtmkaennhk.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtkjarbdmy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gthhslvdbw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfpybozx.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtkcgyydpm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtgxidgszm.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtuzhupsfs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gthegrthvz.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgquvohlv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtwmqmgori.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtnszjznbb.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyukfszg.html


<!-- 参考信息 -->