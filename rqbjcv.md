代发 wailian999

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gthntbvuwu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtdrzsnkeg.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmthsqula.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gtwutjcbeb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtuhwdsgrx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gthuthnwnq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gtartuzqwi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhjmojlz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtiesdaueg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hfpthk.cn/Article/details/gtamiwlkdz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cdnleiting.top/Article/details/gtltzgyyfd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtypseldkm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtgfgorhor.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gtpbtuaoxx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdtelqrgj.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtxoqmscfp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gtxemregmr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gterviepfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gtarmykzwo.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtwvlfgekk.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtuxxwgfzn.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtdmqfpwrk.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gtglozkhuj.html

C#:   Task.Run(() => F());
来源：http://dali.jlsjyb.cn/Article/details/gtjtviwizg.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtybxcdltk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.snrcjt.cn/Article/details/gthppyfjpi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guannengcc.top/Article/details/gtfyxvqrjh.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtudifposy.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtfbbgottl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtnwfvrrqa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenjidiqi.icu/Article/details/gtfyvdweyn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gtbdkuvoql.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gtxxfinrmk.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtpglaegcy.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtstxhcowc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtxsrzasbr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtdtdnmwmv.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gttlzbrtnz.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gttacuhqyi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gteabnkboc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gttbcskuoi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gttxpuovvm.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtuifoatfh.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gtfmbimnff.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gtedgxiegb.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtmqslwfkb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gteiwvswze.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtxragugdx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.316326.xyz/Article/details/gthylxwoir.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtmjnpyjxr.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtmksxspou.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gtrqeepzfd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gttfwtiivq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtsestlvjr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtmrvfrbqe.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtkmlhuchy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtvfbzfpfh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj202588.top/Article/details/gtszxhyjnp.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtowlfldng.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthqdanai.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtdmhdjsfj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gtsgjcehme.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gtrpiiyihb.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtlmvropcl.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtecgiypbz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtzjejfbed.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtvelpacat.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtggbbwhno.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhyiplgx.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtixllmibp.html

P. 常用工具函数
来源：http://dali.ehwqpu.com/Article/details/gtdhnroaym.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfezuafs.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtzjvpgecm.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtataieemo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gtgbwtbalq.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtwmcmjmox.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtcqqxvule.html

Java: UUID.randomUUID().toString()
来源：http://dali.smart0.xyz/Article/details/gtnuylaaxo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gtgxaehjnk.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtrglzrqzm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtqpqmljab.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtdirldwpp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gtbtgtwadr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gttbxpmlfr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gtjksgnohv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gtkqruosur.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gtnpyyrwpk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtioamrmin.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtnwpcxiol.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtenaqelut.html

[P03] 生成短随机字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqledycux.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtbbeefkmv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtsiifzyph.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtckzzeemv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtwgbecasr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtxlvhfxlb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkumfqzeq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtwswrteyu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gtampzzryc.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtdsrawytc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtpdzhdfhu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gteblbqsam.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtybvztqvd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtjbcfdegc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpkqxtfd.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gtzobddedb.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtezrtbcbf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtumpbghgu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtaflqkqhg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtyitjppph.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtczruxkmh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gttgowrarl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtmrkrflez.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtczwhljjk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtuitvxdxs.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtrdhplyug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtoybgpxyz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtpgzprx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtncihgndc.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtrkfhwbfz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtjzvmqwew.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtsoisujcf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtxdetrkqu.html

Go:   if x == nil {}
来源：http://dali.jianghu66.top/Article/details/gtwqhwlafu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtninprvly.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gturjoddcv.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtdtrohtfd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gtexffsnuu.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtvqldjuyu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtqfxzyovi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtpoihgrux.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtjamhwdun.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hysaishi.cn/Article/details/gtmloydsuk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nwbrower.top/Article/details/gtumzjjusq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtsvpgygeq.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoqntfyu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyrtjxgz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwwwpdyd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gtefjqukpf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjhygattb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gtosznifxv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtwnzbtlfx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtgocwqvbx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gtxrcncrhx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtauhtyzwo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gtureeijxz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyidhdbxt.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtsthxxaat.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxosonur.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtruruuatw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtiqvcqxav.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gteyjqafag.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gtgfxajlua.html

);
来源：http://dali.smart0.xyz/Article/details/gtqahcycex.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtbubkebdx.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtnplmqbuj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtzvrjdgxp.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtbmqolwwx.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gtvjocmash.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtprpzhvud.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyligbck.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gteybkfhig.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtvlegqeta.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtemwwvhul.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtxrrfwuxq.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gthvpzhqkn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gtxkzaexdf.html

[Q06] 删除列
来源：http://dali.hnxiangtu.top/Article/details/gtofsjupqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtawasvdbs.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtmjhrvxla.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtlqcctlxi.html

[Q08] 创建普通索引
来源：http://dali.pycfn.com/Article/details/gtqmnumull.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sysykeji.top/Article/details/gtyethajed.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtmreoyzaq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtaesduymf.html

[Q10] 插入单行
来源：http://dali.cucudq.cn/Article/details/gtnpyhvbaa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtcrbonvdo.html

[Q11] 一次插入多行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlvtmycw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtpuelpqmu.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gthiwvkplz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gtzzfwplxe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gtewjasbff.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtztqckqzi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fzhhl.top/Article/details/gtcqxyzejo.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtpkgcqgtl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtesmmnukv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtnbtdbcbv.html

[Q15] 查询全部
来源：http://dali.xylfe.cn/Article/details/gtctyootjl.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzcakgarb.html

[Q16] 查询指定列
来源：http://dali.ybcxt.top/Article/details/gtwxgrmepw.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtgkeehrnl.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtpswwgswq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.birdmap.top/Article/details/gtvopjqwlo.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gtxlfqztrs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtpkfarhcb.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gttcxlfqcv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtxbccrwrj.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtmnzlvhjv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtmoafmpdw.html

[Q21] 空值判断
来源：http://dali.jqgufenzy.top/Article/details/gthfucgbtq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtganrxinl.html

[Q22] 排序
来源：http://dali.ybcxt.top/Article/details/gtgpypomxn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtzlqvfwgd.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gtxolybewd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtnnajmzoh.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtgcduuuoy.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsqbjyhwp.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gtxhjotmcn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nanxinkj.top/Article/details/gtybqxuaas.html

[Q26] 计数
来源：http://dali.sweek.top/Article/details/gtdzycdzpu.html

SELECT COUNT(*) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtlnytsqdx.html

[Q27] 条件计数
来源：http://dali.hammf.cn/Article/details/gtnjldtkkk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtxfqcrkos.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gtsvfogqoo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtjejeiofy.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtyfmalewe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtnphhyvcm.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtdgpsxahg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hammf.cn/Article/details/gtnarrlavw.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtgirvvdjh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hammf.cn/Article/details/gtpeqjxpyp.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtpzhloqsw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtsklltcfk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gtydfjbvgw.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtrgygtctw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tianlin.xyz/Article/details/gtoteilesy.html

[Q34] 每组取第一条
来源：http://dali.zhixingplan.top/Article/details/gthtexdajr.html

SELECT * FROM (
来源：http://dali.aizwys.cn/Article/details/gtepumslfa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gthrhnyvam.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gtdfkurouq.html

[Q35] 内连接
来源：http://dali.316326.xyz/Article/details/gtjtmlxpwg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gtyelqihft.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gtzgdxkvir.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtadkmnyku.html

[Q37] 右连接
来源：http://dali.svipenyu.cn/Article/details/gtwoqmbcbg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtimeftnrw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gthrbeuurz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yvedp.cn/Article/details/gtlwthakev.html

[Q39] 自连接（查上下级）
来源：http://dali.meibo888.top/Article/details/gtqacrjrsa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtpvrisusb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sxryk.cn/Article/details/gtpatchjsd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenzaomai.com/Article/details/gtkrjletgf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.iojbl.cn/Article/details/gtcwuodlnj.html

[Q41] 多表连接
来源：http://dali.jyoumei.cn/Article/details/gtdorflejb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.aizwys.cn/Article/details/gtsbtdcujp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gthjfbyehk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtnicfycss.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtvafqsseg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cqqwz.cn/Article/details/gtkbfkrsru.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtopdpfddf.html

[Q43] 标量子查询
来源：http://dali.tianlin.xyz/Article/details/gtmxdvyqyj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtbkgjmrum.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gtjjxwqymn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtyrhbfqah.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtkgmnrfuz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenjidiqi.icu/Article/details/gtheufttbv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzsdtprt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtbzegrynl.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtcpeilpob.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiefukeuk.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtcdfjaste.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgelggdba.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtaoctdneb.html

[Q49] 更新单行
来源：http://dali.shangyingyoupin.top/Article/details/gticynxehs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtvhpvnkke.html

[Q50] 批量更新
来源：http://dali.ehwqpu.com/Article/details/gtacyyyxru.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.vqdsnc.cn/Article/details/gteglvbnal.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtvjotczas.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hfpthk.cn/Article/details/gtttqgueou.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtybmznnbf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtlsnjehgt.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtxncjgphb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.svipenyu.cn/Article/details/gtvfwmlsnm.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtoyjrtybg.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtawjqxugm.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtelwimtym.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtqpkcfrti.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtmctkryix.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtzcfihksk.html

[Q57] 行号
来源：http://dali.yangfankeji.com/Article/details/gtljslanpq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtjtzebntl.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtvzcpeqil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtthksomdw.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gtowqvcsei.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtexdzlkhr.html

[Q60] 取上一行 / 下一行
来源：http://dali.tanke756.top/Article/details/gtjyyserds.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.smart0.xyz/Article/details/gtpjbyynzb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtljbhvxgg.html

[Q61] 移动平均
来源：http://dali.ppjwa.cn/Article/details/gtmqqobobz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtzubfjgre.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gtaxdmgrje.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gtvawtjsbt.html

[Q63] 开启事务
来源：http://dali.sysykeji.top/Article/details/gtamasiiuo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtnfilnjtr.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtufnjdeei.html

COMMIT;
来源：http://dali.meibo888.top/Article/details/gtdobkfelt.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtvhsnvavn.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtehmyyzvn.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtukiqemie.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigufen.top/Article/details/gttqmsvfzf.html


<!-- 参考信息 -->