代发 wailian999

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtozqeaked.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tian-w.cn/Article/details/gtyllxwciw.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtbqdekdsz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.aizwys.cn/Article/details/gttwgjyyup.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.snrcjt.cn/Article/details/gtktwyeygw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gtxdicnlkp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtedyddnsi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtipuermla.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtzyvlmchs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtmmemjfhc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtpuaahvio.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtuhcytonj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtazjmuonx.html

O. 并发与异步
来源：http://dali.yj20258888.top/Article/details/gtdtykhynp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtoagdrafi.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtdvrnwzly.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtfwwzatkq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gtrgiyppaj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtiuzngaba.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtzpnnzqhq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gtvfqtrmee.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gtgfuktlsr.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtrxpmioee.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtfgajoqcc.html

[O02] 使用线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtidwmuifw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwzhbhgi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtxvsbxzib.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtyuguyiwh.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtnjhtyoor.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gtrospixao.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gtclbvasmt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.meibo888.top/Article/details/gtnpsfkpii.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ppjwa.cn/Article/details/gtowftrcjb.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtzyozzqnt.html

Py:   with lock: shared += 1
来源：http://dali.gotoacloud.top/Article/details/gtogqefdzr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenzaomai.com/Article/details/gthunpgnjb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtdkoomehk.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtunpdpqbp.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtsnoeyoeg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gtxrgewvgj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtrxdtsyjf.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtonomzrvz.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gtrlzxyexc.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtycccghwg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtfbcecorq.html

JS:   async function f() { await g(); }
来源：http://dali.pycfn.com/Article/details/gtufreuttd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtesqvbjjd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gttzmbsjjf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gtaecwehaw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtvciiaoun.html

C#:   async Task F() { await G(); }
来源：http://dali.yonumen.top/Article/details/gtgbcomjwo.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtxroteygg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtxoaxvvyx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtjpwaibws.html

JS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gtrfldvunm.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtdzlkeasf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtgjwdfkpl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtnkxkdgno.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gthwdrndai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jyoumei.cn/Article/details/gthrvtrtjh.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetjfqzga.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guowangkeji.top/Article/details/gtxnrjqxeb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gtqkudhilp.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtydgivfkw.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtrbfyqaeg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtemnjqkyx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtbozzsrtk.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gthoxfflqh.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnkrqque.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfcesapfz.html

P. 常用工具函数
来源：http://dali.yangfankeji.com/Article/details/gtxukhccnb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgqaiqwoe.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gtjolbgxek.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtetfabpzh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtxswoznvs.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtfhykjlcv.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gttnvvothj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtnomrhebc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtayiamehv.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtteoozrlu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgfzy.top/Article/details/gtejjpeiey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtxlicmncy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gthylhncyq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtjexdtegx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtrysgvxqn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.c1oappe.top/Article/details/gtglfocuhg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gteabvnoze.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtgetakxvx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aibaodan.cn/Article/details/gtygotfxeg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtdfixxfvz.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtkbojvczd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtloyotote.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtvvxqwxnb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtlauselri.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtjdxugjkz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtrozdizqu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvykplne.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwawfouzt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtejiubhfq.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtjsvewodm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sweek.top/Article/details/gtkdamjfba.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijsdtvec.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtehjamyzv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gtmqyojely.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtoqtsikfi.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gteoynnwdu.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtqdrpttbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gthyyyfxdx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jyoumei.cn/Article/details/gtewzjzrpo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gtptpkwjow.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtsptahhdu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtdmavrwru.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jlsjyb.cn/Article/details/gtzosdgmjh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ppjwa.cn/Article/details/gtuyuemqud.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtsxhyutja.html

Ruby: a == b
来源：http://dali.nanxinkj.top/Article/details/gtbsuvqcas.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtvvxvbvyv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtgwvyotqe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtpyqhrazm.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtfhjmrvxw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gtzwmxzduo.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtersturmc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmtqrymn.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtarnfoief.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtgctczddp.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gttisniyji.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtayvjqyan.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtlfdnfmmo.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258.top/Article/details/gtevqfgfed.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtbilrproh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtbroeoynk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtmkkfszfy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gtdehovxwb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gtzgzrgdue.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtctufjwto.html

[P08] 处理浮点精度问题
来源：http://dali.mhx1999.top/Article/details/gtcsfnynyb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fzhhl.top/Article/details/gtuzsxvxgy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gtccwyyxdo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cdnleiting.top/Article/details/gtsatgqxzm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtfeqkxpdl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.9152youxi.cn/Article/details/gtbjvvbjhr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gogol.net.cn/Article/details/gtxaephfdy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtpfywuztg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gtydljzxgn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnwtwptfg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtvcqazlgt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsutapwph.html

[Q01] 创建表
来源：http://dali.wangdashe.top/Article/details/gtnmibemsy.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtvgfocjyk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtahjdliyb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtoyniuelx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gtoglkyeko.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtrdzinpkc.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gthuxpouug.html

[Q02] 创建带外键的表
来源：http://dali.zhongyouzk.top/Article/details/gtasxmhlwz.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtnwocakoh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtemkdvxfo.html

user_id INT NOT NULL,
来源：http://dali.yj20258.top/Article/details/gtyicpiube.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtyehiclkh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pycfn.com/Article/details/gtxgrsfskd.html

);
来源：http://dali.guannengcc.top/Article/details/gtnyamkgig.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtpqsbagob.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xinyue.icu/Article/details/gtxdckpwtl.html

[Q04] 修改列类型
来源：http://dali.hnxiangtu.top/Article/details/gtodlpqpqy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gttndjnqrv.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtegwryipb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aibaodan.cn/Article/details/gtzucuzfyd.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gtdvrabwkb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gtpoyrxtlv.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtikitsaie.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ehwqpu.com/Article/details/gtyczvdqux.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtjwgjkpmp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpgstmib.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtthgftsmt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtbnlntbgb.html

[Q10] 插入单行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnfsgtis.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtqvhtjnkq.html

[Q11] 一次插入多行
来源：http://dali.cdnleiting.top/Article/details/gtkyqsqies.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtowjnvsnx.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtoztofrhs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtxzbrwilq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnxiangtu.top/Article/details/gtyjnwgcff.html

[Q13] 忽略重复插入
来源：http://dali.birdmap.top/Article/details/gtxuviwiec.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtyjgudtxw.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnnlbmzn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtddumozfd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtijvzoauj.html

[Q15] 查询全部
来源：http://dali.pengpengdd.cyou/Article/details/gtnudmlzxv.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtylpfktnq.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtbcxzzhno.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtzepneogr.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtqorokeko.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gtagwdrusb.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtanpbswye.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtnuddzkup.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtqdbkzvxa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtctokytdt.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqvceupw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtfeocwmxc.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtunlautvi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtxjvkkisv.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtcddpgfkd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gtcjymzoum.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtuoqcwzwo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtnrmcdlsd.html

[Q24] 去重
来源：http://dali.guowangkeji.top/Article/details/gtjfwrfvzx.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtftyhgoau.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtwivbmuxm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gtgxtqjipo.html

[Q26] 计数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzybmcoz.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtoqnbgwts.html

[Q27] 条件计数
来源：http://dali.zycfv.cn/Article/details/gtyotfxhdi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtzjqkxuxg.html

[Q28] 求和与平均
来源：http://dali.jlsjyb.cn/Article/details/gtxdkhtzyx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkppwvrlg.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gtepwnrwqd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtxdgjgifk.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtskrjubki.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtytbnwovi.html

[Q31] 分组后过滤
来源：http://dali.shzxlz.cn/Article/details/gtezriwtpx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtknoqyljc.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykuixqcs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtsgitqpyc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hnxiangtu.top/Article/details/gtzhjjouxq.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtpkvvdoqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtcmhrzeel.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtscbblzgx.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gteiigsumz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gtkeiywlfa.html

) t WHERE rn = 1;
来源：http://dali.snrcjt.cn/Article/details/gtfsdhluhd.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtxljzcghu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtfjolpxzw.html

[Q36] 左连接
来源：http://dali.jlsjyb.cn/Article/details/gtjhfkbpzr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtumqguaqc.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtqoyyfrlb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtompeqhgu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtyxqsgsrf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hfpthk.cn/Article/details/gttqpdhbnx.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtqvfpyjjh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtwbpmwzos.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtejtzzjrl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.c1oappe.top/Article/details/gtnbiunqon.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtzcndbrhk.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtnsgwdbns.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258888.top/Article/details/gtfbecilvo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gtuvjkidvm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gttekekzcy.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtzfmycxdy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hysaishi.cn/Article/details/gtkguufbcs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.andypj.xyz/Article/details/gtwxranaxk.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtlmrqnwql.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtrfbhciky.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtxeebbwim.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.dashuyun.cn/Article/details/gtfwxzsoyu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtpskgkcie.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtdyejulcz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dianchejie.cn/Article/details/gtyrlctptx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtvhuyvepw.html

[Q47] 与平均值比较
来源：http://dali.sysykeji.top/Article/details/gthctsjvjj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gtxwqmfswa.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtibnsmfqw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtclqtoxew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtiurptipd.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtyizwpbox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtbuxdmgxg.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gtdnkszfmg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtzamxumeu.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtmkljbyip.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsydoeos.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtkuyqdvpl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.mhx1999.top/Article/details/gtreaikrbo.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtljmgeyfi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtnmrdpgpe.html

[Q54] 清空表
来源：http://dali.dianchejie.cn/Article/details/gtxpcjmvfx.html

TRUNCATE TABLE logs;
来源：http://dali.dashuyun.cn/Article/details/gtlsukbysr.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtdzncrnxr.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtuaxjublt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtstskpgpy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtoeeynxqj.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtrgpwzcqe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtxeufnyxi.html

[Q58] 累计求和
来源：http://dali.yuanzhike.top/Article/details/gtmwhkyise.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtchhzvlgi.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtdpllgffd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtdzzmnbwq.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gthaljvfdf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtfxuxztho.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gttiujqqiy.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtsynulosn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtrvjapivw.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtpgknvoif.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtunzbumga.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtvwwvlspc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtlozecwjy.html

[Q64] 提交事务
来源：http://dali.pycfn.com/Article/details/gthhzfvmky.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtapijqdrg.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtilosihjy.html

ROLLBACK;
来源：http://dali.ybcxt.top/Article/details/gttlvkqncz.html

[Q66] 行锁查询
来源：http://dali.andypj.xyz/Article/details/gtoewjxqwf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtvijaupjq.html


<!-- 参考信息 -->