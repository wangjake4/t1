代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gttrtayuhm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtyqxktqpo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gtbshzwuua.html

Java: // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gtarfckmim.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtrodqlcbf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gaohongyu789.top/Article/details/gteadiwzat.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtxxrfytiu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtzklzcheq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gtdclvweri.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtlfbpwqry.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gtsasdbtte.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtogsmiygy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gtbhcwpcze.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtgwzzdnve.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sweek.top/Article/details/gtprdqxsdt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtihqugchv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtzqppupkh.html

O. 并发与异步
来源：http://dali.yangfankeji.com/Article/details/gtpjdlvduk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpxldzgmw.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gtzwrbckvs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.meibo888.top/Article/details/gtauzgxgoq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.9152youxi.cn/Article/details/gtzpuubwnw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycpghkst.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpcqvtsm.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtkgfphnxn.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gttppciypc.html

Ruby: Thread.new { f }
来源：http://dali.meibo888.top/Article/details/gtbcmwetgf.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtxtrhpjxt.html

[O02] 使用线程池
来源：http://dali.birdmap.top/Article/details/gtnpllebhc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xinyue.icu/Article/details/gtwtyeumxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.havefunace.top/Article/details/gtxqhwnaik.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufhehqbc.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtyvxqbxng.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtuyrylszt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtrftvgeiu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtfjznoixf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtlkrbkebb.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gtgsdiqifa.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtxjjkoran.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtjdiuokrq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtiwskiztd.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtwbvopbjy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gtvyzbbtgs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtixemmtbh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqmndrpj.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtjitjcuxj.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtieraipqy.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylvzylgu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtwxzwazsb.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsiggtuyn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtljygksfd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtztcsfzwy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gtgrboksdv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtwkrzmgur.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gtczsywgfd.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtueblohuc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtetpuvbkh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnkfjeaj.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtrgpotobu.html

TS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtyxjjbplf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtlcphrima.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtmvskofzk.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtfdsrfovd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gttnqnyejo.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtdrawqgsx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxdhldpo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gtlxlrrxsr.html

JS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtmrirqqtn.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtcgkjsydl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtxsvnekmm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtwpmnyjsk.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gttjuvhxnz.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gtcgarngel.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgybpogqa.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtfpymstya.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtaxiipwct.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtafrrvema.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtsleekmkg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtsdheeghk.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtpnfkkyed.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gteppczymn.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gtqatuuair.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtfkwksuxm.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtrcbdwgrf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtnwofzdwp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtgyccvozp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtndjiweww.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258888.top/Article/details/gtnzpmqapp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.svipenyu.cn/Article/details/gtnvptnurm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtvzgvvgxp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtxluuubem.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtywolreyd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmbrkyino.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.smart0.xyz/Article/details/gtuifrauqk.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gtbvenuyls.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtoumjmlhf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtgbrhldbg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtrisyfuru.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtjnlrmyss.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbssdizpw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtatkbbewx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenzaomai.com/Article/details/gtcspqstqr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyodzbpbu.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtsaklsoaj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtcnoqniqy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtuyynzgxy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.vqdsnc.cn/Article/details/gtjiwgcnmj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtdjnmzpje.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtdjpirwwx.html

Go:   len(arr);  len(m)
来源：http://dali.gogol.net.cn/Article/details/gtfgkulbib.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtonhcaneo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gtdqocxgea.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtamifzxul.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gtkiwcpkmc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtwhlhmmji.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtavgkyjpk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtkupjpndb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtxxvhhrlv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gthbdxqanc.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtakjcibif.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gtyxmyjjak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtkvchrsoy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ybcxt.top/Article/details/gthfiprsnu.html

PHP:  if (empty($x)) {}
来源：http://dali.tanke756.top/Article/details/gtbwfjmzhu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtejfgsqay.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gthgowcvmt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.316326.xyz/Article/details/gtwthadhvn.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttshtmjik.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guannengcc.top/Article/details/gtbinmiquv.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gtcgqvasms.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtmlagfoin.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtqxujliwh.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtwjbeeyge.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtwjmmdhfd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftuwdglw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.guowangkeji.top/Article/details/gtelwvzqbd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtilaowfqv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gtvtxefdqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtpvkhvprs.html

[P08] 处理浮点精度问题
来源：http://dali.zhoulong.xyz/Article/details/gtadseewqp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.iojbl.cn/Article/details/gtrkqfbqna.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtgnzapysn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtjzlkgccx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebewfacl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtdmwsygiu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtpxofjxlr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hongshengwenyu.top/Article/details/gtvysbpcto.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtndvukxdu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtgynmzdvc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhiwuduotai.top/Article/details/gtzsswwldp.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtevghjwsm.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gthchxpxkn.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gtiqkhrrgo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gthptwbvfx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtvsfiiqxm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtbznxnzkh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gthgzlcxyw.html

);
来源：http://dali.aizwys.cn/Article/details/gtvjgvzfwd.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtyxmnvulw.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gthiwcjmqz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtnmwohmbk.html

user_id INT NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtdcokklmg.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gturxikmqh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ydzc1.top/Article/details/gtvsiwjnhr.html

);
来源：http://dali.haohaochexian.top/Article/details/gtxtnyeqlx.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gtolvpfnve.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvmhwuqj.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtsumzgjod.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jyoumei.cn/Article/details/gtrsmvzbly.html

[Q05] 重命名列
来源：http://dali.0kj1m.cn/Article/details/gtymlzevho.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtyhaqabsg.html

[Q06] 删除列
来源：http://dali.shzxlz.cn/Article/details/gtqdbzeyzo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtidwfhvrz.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gteohdilsh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtodzldmkk.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtyozzpryh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtqfueneej.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcokmrkj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gtmjxujyvq.html

[Q10] 插入单行
来源：http://dali.hfpthk.cn/Article/details/gtmtqufrfj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gtkxwqpssc.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtwqvaiccw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtjqtkqesd.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gthomrtbvg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gtirflbbff.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gtzwcboyel.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gttakmbutu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtoistibfr.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtpzusrckg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sweek.top/Article/details/gtsumzadqh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.fzhhl.top/Article/details/gtcmvvawtq.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtnvjxztxy.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmffwrxw.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangtech.top/Article/details/gttjlnxdre.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtjjcaqvxr.html

[Q17] 条件查询
来源：http://dali.bjfxy.top/Article/details/gtgitselja.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jiagoushi.top/Article/details/gteotnbapc.html

[Q18] 模糊匹配
来源：http://dali.shuidangran.top/Article/details/gtvzgujpyt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gttzagynnt.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtfqwzlhgz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gthgafeixs.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtmeyguruh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gtwoyedysd.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtyfzeppfd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtaejcflsz.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtqrslliay.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtvyperqkt.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvublrbrs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtwwdztapp.html

[Q24] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvyfemzi.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtoyuopgpn.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtnwyegoix.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtnznjvzhq.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gthkqefonx.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtwrmrqzsf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gtdynaucrf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.bjfxy.top/Article/details/gtdmdokxyp.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gtzkzahvvx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtvlglsiaz.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtcxjhsqzp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtbbagbteb.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtjvrrlrhw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtqyhvvgtp.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gtlixklhth.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.smart0.xyz/Article/details/gtsoeacccg.html

[Q32] 分组拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtywyqfnju.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gthiniljfl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.snrcjt.cn/Article/details/gtrupcoqkt.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gtjwhzzxgx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gtgbtlvgkj.html

[Q34] 每组取第一条
来源：http://dali.xinyue.icu/Article/details/gticxiaphp.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gtnvbnijhc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtnrdjiykt.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gtafbydydy.html

[Q35] 内连接
来源：http://dali.cashguo.top/Article/details/gtmvoqkhaw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtpwmvipbk.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gtklotvhfs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtiikknpmo.html

[Q37] 右连接
来源：http://dali.zdqjudy.top/Article/details/gtyrlyytpc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtzhyyptpo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoofdmpt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yanxiufei.cn/Article/details/gtyfklnvnq.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gtppibildj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gtesiooydx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrzskoci.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sysykeji.top/Article/details/gtxwaaicdc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtlpzyruer.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtnqlkifyw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtuwkflmfp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtyhnbcdqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtccybgpqp.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gttgrmsgde.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jqgfzy.top/Article/details/gtecyhtmqp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrobfeap.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtxwjcqruk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xinyue.icu/Article/details/gtipvzshgh.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtivqcchep.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtmcqsifte.html

[Q45] EXISTS 判断存在
来源：http://dali.zhiwuduotai.top/Article/details/gtthgxqnqb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtleynkmlf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtztfegwxs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgufenzy.top/Article/details/gtzsrwpmoi.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtkoolthde.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gtetuutykr.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtpgbibbqs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtwbnogsvg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yonumen.top/Article/details/gtyjtbzgvc.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtircnvmkh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtkaibeuzg.html

[Q50] 批量更新
来源：http://dali.zycfv.cn/Article/details/gtccmaowhz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtyxhxqfyf.html

[Q51] 用子查询更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgdhpazb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtiffadycf.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtowymhuip.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtlxvfhmyt.html

[Q53] 按条件删除
来源：http://dali.smart0.xyz/Article/details/gtswheukli.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtucxdtnkg.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtyoervpax.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtwkqudtuu.html

[Q55] 排名（并列占位）
来源：http://dali.gotoacloud.top/Article/details/gtwexoqjbt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtdzrwrqct.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hfpthk.cn/Article/details/gtfcfgjrhd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtmtodntes.html

[Q57] 行号
来源：http://dali.ivvv.top/Article/details/gtdokdibgy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtapwkmkub.html

[Q58] 累计求和
来源：http://dali.xylfe.cn/Article/details/gtjuknldbh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtwbcdkbzh.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtjzunpdvt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtaprtkmne.html

[Q60] 取上一行 / 下一行
来源：http://dali.gogol.net.cn/Article/details/gtxgrwvdqo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gtmrnfoxmz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gttarhkxml.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gttaamqmng.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtluakjmsl.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtzkmfjzsu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtmtxctqwv.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtlryxxbzh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtbuocipbq.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gteknvutyq.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtbrkjwstc.html


<!-- 参考信息 -->