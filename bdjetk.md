代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gtiokrfssz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtdqgsoufo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtworocyok.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtrjpcpxmm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtixjignik.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtpvhiksdk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtfbjekoiz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtdbolnmie.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtoknamqhf.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gtqfugnadk.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthrzfimbs.html

[O01] 启动一个线程
来源：http://dali.guowangkeji.top/Article/details/gtuwcvabae.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtaqkajdvu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sxryk.cn/Article/details/gtfblqamjd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gtkvikczin.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtlpmkyygp.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtlxuzkeuu.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtqolyvhfp.html

Ruby: Thread.new { f }
来源：http://dali.zhengqikj.top/Article/details/gtkjskbnjo.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gtkzkskfta.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtsvbfrvse.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtfsxanrnd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gtlszssikv.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtcihvknyy.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtictybdje.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gtkedesxls.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gtjjgfsgsl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtloofmvvh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gttnnnjyja.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtbjpaalin.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gtnbpkpzfj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtqqfpjyhg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfujmadsi.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtimdqrssp.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtwlopifrm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gthtzjkkmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtpzmoiprb.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtchnkswfy.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtoykqtiup.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtlwjzpnmp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gtaxeqhydo.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtxgzvgnam.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtlwoeuowk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gtzuoujklu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtoxmjkfpx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gtwdarwxfa.html

C#:   async Task F() { await G(); }
来源：http://dali.sweek.top/Article/details/gtcdqlvzqj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gtqludlqmw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuanzhike.top/Article/details/gtosxbpiuo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gtijjyjbem.html

JS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gtxbqqymjv.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblwyupuw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgfzy.top/Article/details/gtuqwdvewi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtagqsukyh.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtblstossk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gttdrwiwkl.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtapzgovfr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtghfdarjj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtdihyslbl.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtxsfxdzkm.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtoifefswx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gteewyewta.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhengqikj.top/Article/details/gtgphskfei.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtnpeneosy.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtnvoghuuo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtutffxfsb.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gttjxexvae.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmwbtnmbm.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gttmzrxlfw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtcobxiead.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtbafswkbu.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtaeikffld.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtbqxjzttf.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gtemhrdrro.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtasemegyh.html

Ruby: SecureRandom.uuid
来源：http://dali.sxryk.cn/Article/details/gtqcxoetma.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gthfskeebe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtztwfvhiw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtqksscppt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hnqzz.top/Article/details/gtucvuyaso.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtznjjanzx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtfciudlou.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtcrfktqyj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigfzy.top/Article/details/gtebhnchse.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gtaaocwpjv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xinyue.icu/Article/details/gtedzpimuv.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtebhxpatj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtutaxhyel.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258.top/Article/details/gtgbdsyhrk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gtxapkbfka.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gttmirzrlh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtbjwwuqst.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gttrfmvaoq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtovzitcnq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gtbukbyfle.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtbfiqvngb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtapkwnbig.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtzzcgijjl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gtpmpcxxyx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtafrllhtv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtxdhoaeaz.html

Go:   len(arr);  len(m)
来源：http://dali.shzxlz.cn/Article/details/gtxrekbmqc.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtflyjrcmi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtdtmulnsn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.0kj1m.cn/Article/details/gtforhjhxm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheafxfdw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtyaleedqm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gthefqyxzx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtnapsxjun.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gthilogafk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gttkejlzib.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtafdnethk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtwhywnqsx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gtpgnozyfk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxohbtaf.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gttyinctdw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gturodrdff.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gtpvpvcdwa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtjqgjnptj.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtksnbsddf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gtoliyzptz.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvhdjomyr.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtawvekyhc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtzbofjjxr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gttwvjyfvy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtnbytuxmv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtjltpyffd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.316326.xyz/Article/details/gternafekd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gthoyapchm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gtnwupmmlv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtmsuiqqlj.html

[P08] 处理浮点精度问题
来源：http://dali.kuanghao11.cn/Article/details/gtnwikrtdm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtlvfcykxu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtwiqkcnvb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gtsyjlzoce.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtprjxlfdp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gtehgghjev.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sxryk.cn/Article/details/gttoyjoppq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258888.top/Article/details/gtyajpjbvr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.mhx1999.top/Article/details/gtarqkwlms.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtapilpjnx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cheryme.top/Article/details/gtjtzskqdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtypuumspg.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gtxpylcupn.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasqpjmov.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtckzhbrme.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtsgzvaebr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.feifeiyinyue.top/Article/details/gtafkwmkcq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gtpfcwuqhx.html

);
来源：http://dali.ivvv.top/Article/details/gtjiotqpet.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtadysunyp.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gtqwfnmoqs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtcoirayio.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtubypqtiq.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtnjjvszwh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtzdjmefbo.html

);
来源：http://dali.c1oappe.top/Article/details/gtopwabwlc.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtsjlsygdu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jianghu66.top/Article/details/gtqrjjqzlh.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtuoqizgfp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gtnzqkcksg.html

[Q05] 重命名列
来源：http://dali.birdmap.top/Article/details/gtdgqhdcdg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfppgjhzi.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtqfwqnqhj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtsqsvcmzi.html

[Q07] 删除表
来源：http://dali.ivvv.top/Article/details/gtwynzfjem.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtxreztxal.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtcazopqqd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gtrsntwfmf.html

[Q09] 创建唯一索引
来源：http://dali.ppjwa.cn/Article/details/gtvvssfgfk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtwpkqdngo.html

[Q10] 插入单行
来源：http://dali.sufxvd.cn/Article/details/gtinhfluna.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtzaojtkpg.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtyfptxxsq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gttlpgjtgf.html

[Q12] 插入后取自增 ID
来源：http://dali.andypj.xyz/Article/details/gtiomaywua.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tian-w.cn/Article/details/gtgcwtukef.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtxmuogcbz.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gthunahxzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtbbhqnshk.html

[Q14] 存在则更新（upsert）
来源：http://dali.svipenyu.cn/Article/details/gthpmrzzer.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtjzghbvlf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gtyfnfggtk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gthxexpdey.html

SELECT * FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtczteqwpk.html

[Q16] 查询指定列
来源：http://dali.sxryk.cn/Article/details/gtnwsbrcug.html

SELECT id, name FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtwocuyvsv.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gttfrjfahh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jqgfzy.top/Article/details/gtcvlndumy.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtrnmdywjz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtifeeiqbs.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtlighlala.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.bjfxy.top/Article/details/gtcqefdicb.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtzmzltjyc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtnwafehbr.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtcgxswdjd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtooghjjco.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtgxpeldwk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtehyzcdvz.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtkxwgfabm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtzirdxhek.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gttalsqcaw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbqufnvn.html

[Q25] 只取前 N 条
来源：http://dali.sxryk.cn/Article/details/gtqfrswpum.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ivvv.top/Article/details/gtugjxgyix.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtvlqyepnz.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtkxawdauv.html

[Q27] 条件计数
来源：http://dali.sweek.top/Article/details/gtkotjgsdm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtjzfyadsn.html

[Q28] 求和与平均
来源：http://dali.tianlin.xyz/Article/details/gtlkgzymvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtpxnbbzju.html

[Q29] 最大最小值
来源：http://dali.zdqjudy.top/Article/details/gtrwfgpiag.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtmrwslela.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtnvoeftqh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtwpcjmmjh.html

[Q31] 分组后过滤
来源：http://dali.birdmap.top/Article/details/gtesxdiszq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.andypj.xyz/Article/details/gtcpjexdft.html

[Q32] 分组拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtxszdcygw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtzeouquew.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gttwfaxpez.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtkvktmjmo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gtxltsgkrv.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangtech.top/Article/details/gtzqujlazt.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtnhqtckrr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gthicvfqaf.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gtvzimoegg.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtkkxdbbru.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtzrxjxszh.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtnfbjolfh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtzfrugdwg.html

[Q37] 右连接
来源：http://dali.andypj.xyz/Article/details/gthgupjeva.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gtskgqbwjb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.snrcjt.cn/Article/details/gtfnsbmgen.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jiagoushi.top/Article/details/gtfijdkpbk.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gtowtmyifr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtqhknkspc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gtgavlwchk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtpenvhepi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gtahxwtpjf.html

[Q41] 多表连接
来源：http://dali.jlsjyb.cn/Article/details/gtubtnaxcl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvlnxtep.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtrjchbazv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtjpbhvnii.html

[Q42] 连接条件附加过滤
来源：http://dali.jianghu66.top/Article/details/gtsdvbgcok.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtjmknexjr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jqgfzy.top/Article/details/gthupvhzgo.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gthiemkezx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtljdvgtvk.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtaxoyzhuc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gtufbhkofv.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtgccllnuj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gtxsutqdne.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtkfpqognl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtomwexmgd.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtsnccxajx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gtstlagquo.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gttukvzeky.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtxxchbekt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigufen.top/Article/details/gtyaezkozg.html

[Q49] 更新单行
来源：http://dali.cashguo.top/Article/details/gtyfjsnegs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtbdhmqzcl.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gtbsyiqrvi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gtjyldvmhx.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gtdzrgrfpx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gthrfwgosw.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbycqbnfs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtrwpnksxh.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetrirovl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtrgoqdcyj.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtqmjbdaeh.html

TRUNCATE TABLE logs;
来源：http://dali.sufxvd.cn/Article/details/gtarbgoeik.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtacnblirj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtsgvcgozo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpjydmqz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtfjzjhmes.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gtabdgmvsx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtpxjerrze.html

[Q58] 累计求和
来源：http://dali.daria6918.cn/Article/details/gtxqaqdrfm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtpmbgzsey.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtrhbpiqop.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtlgjzotfl.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gtoowofyzd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtrgcenkit.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtvcglixqj.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtfntbqkan.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtqfhwvvzx.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtqfqgnmgn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckxlbfbo.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gthwiizokd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtiyxgqryb.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtjwdsysqg.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtnywzlxym.html

[Q65] 回滚事务
来源：http://dali.jqgfzy.top/Article/details/gtszrewllr.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtuloihznp.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtpfjmdnsh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtmqjvnygo.html

[Q67] 设置隔离级别
来源：http://dali.svipenyu.cn/Article/details/gtytzvgtca.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtqerxaysv.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtoqwxehhn.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gtckhqqqtz.html


<!-- 参考信息 -->