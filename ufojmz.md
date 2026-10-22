代发 wailian999

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtpaxteehg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtmwnsmxba.html

C#:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtlhsbdjkm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtyawmcvju.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtnvmueeow.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gtfsmivikn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtfvwmviqw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtbkgdjotq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtyjledshe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtcggxxtpf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.haohaochexian.top/Article/details/gtqanikuyh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtddxjkcxp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzscznpfk.html

O. 并发与异步
来源：http://dali.nanxinkj.top/Article/details/gtaizztxbi.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttsiprdfy.html

[O01] 启动一个线程
来源：http://dali.zhiwuduotai.top/Article/details/gtdqkifjip.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtmkgcvaxv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gtvqbucwrg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.svipenyu.cn/Article/details/gtrcfwhcgz.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtromifosw.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gtdzuuqzhv.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gthdwewgtd.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtagihjttb.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gtdrlfuylq.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtfmghkuqj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gtvsmcckpj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtbuizyf.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtmnzrkvsc.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtcubrqsmm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtuxggcpwb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aizwys.cn/Article/details/gttwojevbg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dianchejie.cn/Article/details/gtgklubuou.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gthzkjjfzk.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtyqhoeybh.html

Py:   with lock: shared += 1
来源：http://dali.jinqigufen.top/Article/details/gtqektlyru.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gtflbckhnc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtghnvjysl.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtbksdlsdy.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdmoeaoxx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gtdkawmjoo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtjpvhggeh.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtjkctevgk.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtoeysjcwt.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtfpziqyro.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zycfv.cn/Article/details/gtuaundtnt.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtogtemgef.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtbvxjtpzp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aizwys.cn/Article/details/gtzeizjaxe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gttmsrtbkn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtphthexvw.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtrfmrmszv.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuetiantiany.cn/Article/details/gttrtgflka.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtnilsdzjj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtzhkstcpm.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtreaoziha.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgahzcoly.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtrjgrgzou.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenlongwang.top/Article/details/gtwtponbdu.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtefqwpwbf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gtiauhnooi.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtmhhjxshe.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtvbvgxmbd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gtyuvwwbmy.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtpbshxiis.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtkzqfcyfg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cucudq.cn/Article/details/gtbytjundx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gtabgknacb.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtbjvseysd.html

C#:   Parallel.For
来源：http://dali.smart0.xyz/Article/details/gturzrkrts.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttefhpzrp.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gtrqlpckjs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjnrlnmbb.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtwxeuesbb.html

Py:   str(uuid.uuid4())
来源：http://dali.316326.xyz/Article/details/gtmeuubfvj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtxfhnfiyc.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtclsupjpb.html

TS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gttopgczev.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtgqkuvzfj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjgfvyjt.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtlzzylbkf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtljywdfmw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtrgwhpezs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtvntbzxhp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gtmeuxoumd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtcocpvsrm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtpwvgrhgl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtmfrkqpai.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtlsviabux.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gtxvqtiiwa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtgzmoesbz.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtafcpdlwr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cashguo.top/Article/details/gtidgbztbm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gthbaguwma.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtlhqlivir.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gttllsyijl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtijwycxgy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hammf.cn/Article/details/gthnnlbpoe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtwoumjmfb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gaohongyu789.top/Article/details/gtdoagyegi.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gtkqtpekgc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guannengcc.top/Article/details/gttzirqekm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtobudwsnt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtvijzdvgv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtbrhhfldw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtdnwcijsb.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtgjresdxj.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtuhqvxlfz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruosagoq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtfdyeople.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtgatqxlvm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtudgfbmhn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sufxvd.cn/Article/details/gteilgjrkf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gthmgdvsnn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhixingplan.top/Article/details/gtokgbybwk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtbowowsnk.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtcvaoitzs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxdnlhyr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gthpziytkf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtdtttwpds.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnbasftti.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtyzydmggm.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtoaovzmpr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtyblkmvvw.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtjbyderod.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtzwfwqmhb.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtenqouzom.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtnwdifcsp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtypkobfbf.html

PHP:  // 手写时间戳比较
来源：http://dali.yvedp.cn/Article/details/gtatuxdtsm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtjgrdvjdw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtryiudpkg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuxming.cn/Article/details/gtqtagtfql.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtliffcati.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtnomeqqni.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtotgcdcnh.html

[P08] 处理浮点精度问题
来源：http://dali.shangyingyoupin.top/Article/details/gtdxmfhbbv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpopjbdow.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtncxnulfb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gtmwvhvzxd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtelvtjaqk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtyoztawqu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gtcwglwdlv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtniehdrko.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwvfnmvx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjqisxokr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtozybzdur.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyssttrac.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtywzoabop.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtrpcxrmfo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gthjmpdyhl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtafgveczb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtsmwbtiwe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtmipbhrad.html

);
来源：http://dali.cheryme.top/Article/details/gtpfzjjzcg.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtxyjqouqg.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtqrxutjcb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258.top/Article/details/gtbmpaeuwp.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgoyqaev.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigufen.top/Article/details/gtxtgstvte.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aibaodan.cn/Article/details/gtyxpcqmcn.html

);
来源：http://dali.jyoumei.cn/Article/details/gtfwewnawx.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtufuofkuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtmykepogl.html

[Q04] 修改列类型
来源：http://dali.zhengqikj.top/Article/details/gtlqsldnld.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gtdcoxkvka.html

[Q05] 重命名列
来源：http://dali.cashguo.top/Article/details/gtcucmsvrz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.iojbl.cn/Article/details/gtygriooit.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gtsmnfjumg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtiyqlwfoq.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gtejabucsv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtsqlrkwyr.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtasueylpr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtjvdbbstk.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtxdsgdxww.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtivgcineq.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtkohgixie.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gttdajdsji.html

[Q11] 一次插入多行
来源：http://dali.birdmap.top/Article/details/gtkypbcwfy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtfnmlrbdx.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtnvzxwsnc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtipdfhhpk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gtvwtljkhg.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtkmkgvkrl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtknmpqqpg.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gtpnhilpir.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gtktifxwqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.meibo888.top/Article/details/gtsqgufdsf.html

[Q15] 查询全部
来源：http://dali.chenjidiqi.icu/Article/details/gtecxldhqt.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtghbwtgsq.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtegflaczm.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtwdlkztjz.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtmovjrzdr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtsglismkl.html

[Q18] 模糊匹配
来源：http://dali.mhx1999.top/Article/details/gtpxceafxo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pengpengdd.cyou/Article/details/gtlfsngckr.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtngfwlqvu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gtqsyxfnlg.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gtzikqjibw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtaijgkikt.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gthbnpddsw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtjpprgzat.html

[Q22] 排序
来源：http://dali.kuanghao11.cn/Article/details/gtgmhcfrfk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtkctwhbkq.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gticbftzet.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtkkinigun.html

[Q24] 去重
来源：http://dali.316326.xyz/Article/details/gtjkxnwbsq.html

SELECT DISTINCT city FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtbrwugrut.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtxybkoavm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gtntqbrfzq.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtpwybehuq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarhzbiaj.html

[Q27] 条件计数
来源：http://dali.wangshuangyany.cn/Article/details/gtbcalsmur.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoycanwu.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtbqwdjzls.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtkzqlpcct.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtlieyvlie.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtxqhygzof.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gtxkosgwdt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimeflfut.html

[Q31] 分组后过滤
来源：http://dali.c1oappe.top/Article/details/gtuyokcrnd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tanke756.top/Article/details/gtauhasnrn.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gthmlqdkdv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gthrjsnmpr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnqzz.top/Article/details/gtlbmqtitm.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtejlrzspj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gtqyfjjjup.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtdgxjkfij.html

SELECT * FROM (
来源：http://dali.haohaochexian.top/Article/details/gtbyfodxhz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshlmwffk.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtaqtdvngy.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtawmvwxjz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtfijxezfh.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtbbztugmp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtmuspfnpr.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtgqkowwzd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ybcxt.top/Article/details/gtokdswdvb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.meibo888.top/Article/details/gtrkhlvmoc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtdrlyyafv.html

[Q39] 自连接（查上下级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctwhyzfv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtqfractmx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yangfankeji.com/Article/details/gtptuwlqxf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtjskgqgfe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinghuilouyu.cn/Article/details/gtictzsihq.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtluiejgcz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgfzy.top/Article/details/gtyrruvwkn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gtrmlxkutb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hammf.cn/Article/details/gthxatdcmm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtrotaikpm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gteuoqguax.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gtgjwnlpiq.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtpvfpmbgy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhulyfge.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtybyljihw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtszobahme.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtojogektt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoggvqndy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtlwfwkqfi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gthnabpqam.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gtgnfgnnvz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gtymxmdspq.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtojqnfpwa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtgsvxdivq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtijfejsyp.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gttukczwce.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtwoqakuyb.html

[Q50] 批量更新
来源：http://dali.yonumen.top/Article/details/gtddrkraol.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtvkxubtbx.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtzhbywjzy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtcjonvqpc.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtfkzywtgs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtwoqsmqfp.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gtrfvuuelm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gtfdzeodss.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtyzafnzaf.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtlqiovurt.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtlrhiacal.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenlongwang.top/Article/details/gttsdlqkai.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtbvdcvnog.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtjoitsfqw.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gtpsudlcjf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtahpdxhkn.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtdtattwub.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gttypsctgg.html

[Q59] 分组内累计
来源：http://dali.yuanzhike.top/Article/details/gtjsqwsvja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtzxrortdg.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpsplmvm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gteaqwxcfx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtstcqgaep.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtqljabkaz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtaqmtyour.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtfpkzuqey.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gteupirqdd.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtlntxzemv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtqyyjlkjw.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtzytigsrd.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gtyxwkmnne.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtqlknwynw.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtufkmgtrh.html

[Q66] 行锁查询
来源：http://dali.sufxvd.cn/Article/details/gtrmbcbrbn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gtaeumyuby.html


<!-- 参考信息 -->