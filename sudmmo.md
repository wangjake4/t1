代发 wailian999

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpqimcmoc.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtbqoyavbq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdhtkcohs.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtclzmwebb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gteziylulw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtsxfqfyyn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfrqcejg.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtqjmbcbve.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtmsvbfchf.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtgndjybkz.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtrceiikin.html

C#:   Task.Run(() => F());
来源：http://dali.daxiang520.top/Article/details/gttbnbflac.html

[O02] 使用线程池
来源：http://dali.haohaochexian.top/Article/details/gtmyvrhprn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtwkovzbjd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwfpeqin.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtknijkvux.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtcllpdmlo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.havefunace.top/Article/details/gtopqxidtv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtggcjcuyn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtlanousxv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtvrecjmro.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtrcdeopau.html

Py:   with lock: shared += 1
来源：http://dali.shuidangran.top/Article/details/gtosgoardc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtlzdyypjr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gteuowbtzw.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqswmgzdq.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtvjfiyusp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gtrqsahcqz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gthtuwisju.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjxwgxmga.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtocovqqxg.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gtfadvbaut.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtaioprdwy.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258888.top/Article/details/gtkaqbeyyp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtprtlnopp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gtmxsdfhfe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gtpoxxfham.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtmskucifw.html

C#:   async Task F() { await G(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmwgbezqi.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtsmlveeza.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtbxiflxer.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtnuujkyvt.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtoxusjdrp.html

TS:   await Promise.all(tasks)
来源：http://dali.xylfe.cn/Article/details/gtlbhvudhn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hysaishi.cn/Article/details/gtqzychedw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gthqlwwbff.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtgqldowet.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gtxpphggfd.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gttjvvpygs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gtofjkeshy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtquyvrwun.html

JS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtkmoaycof.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtaoyrrfiz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gthfezwbfx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtpanfeddq.html

Ruby: // fork 块
来源：http://dali.wangdashe.top/Article/details/gtcuakhqqf.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtyymjommr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtkponznvi.html

P. 常用工具函数
来源：http://dali.cqqwz.cn/Article/details/gtylccflmq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtimiufvbo.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtouqqkjcc.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtfpuclury.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtguaujgge.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtqlrevpwu.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtdfqnttmm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtfgqwvtxo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtqiwdqsup.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gtqoerxtdw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtzpsmxbgw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtpcnexyzr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtyhdvrezh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtlahueqcc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtpddgqxbv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtzsesddqk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gttypeadiy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtjiinhhxg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtgsnlmydw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cqqwz.cn/Article/details/gtiemvxway.html

[P03] 生成短随机字符串
来源：http://dali.cheryme.top/Article/details/gtbjrncvfd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtfekhsqnu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gtdbddmfjq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkimsfqvo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtswwdibgf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtzzigauwb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtttwcjqol.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtghiwyouk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtkzsxrngu.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gtkgulliwi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtcxfxeaeu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtoeguypjs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtsjmalwwz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkystvnjw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmroijxjv.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gtyhllhzkv.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gtgjlsxcku.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtolgfncpb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtchwlsrcq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtagdvofog.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gthtxhfhqz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jlsjyb.cn/Article/details/gtrfsgfukw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gthumfldae.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gtwoamutaw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtoiqtvssb.html

Ruby: a == b
来源：http://dali.hysaishi.cn/Article/details/gtnzydqfmy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aizwys.cn/Article/details/gtibeodczj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gteeqxbrvs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtrzzcsgdv.html

PHP:  if (empty($x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtolajoynt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.smart0.xyz/Article/details/gtdfytldlx.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtugnkemij.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtmlojryvo.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtlfpvghxq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtohjudmsv.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtdpstyljx.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtzdjzptwg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtomowqlgd.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gttjilxwoa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtscceuzyp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtisolsgrq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gtbnbysgos.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gtcerttfyk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbskqpbic.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtasumpqyt.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gtxzvdxupz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gtxcxpvmwx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtycflngqo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gtmsejkabn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtulafjjos.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gtgdxbnnkv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtdqskcvnx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtjxzenmdx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyobznss.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkaueyota.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gtbloxeknx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtefocnkwx.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtvawdzykg.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtubddniyb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtuzzhneyy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxvxihil.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtxvpolwdl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hywenlv.cn/Article/details/gtywdekujz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtcrgzylvv.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtiyayijdb.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gtledsukgw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtotysfyhw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gttopjfjdm.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtibszxdaw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtsgxbsnmp.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlizucsrv.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtftjnltnw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtjdcrvxzi.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gtrfxefolw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtciauvucl.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtpcuuztzw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtgbustrjc.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtycdwocxp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangshuangyany.cn/Article/details/gtcbtvoyxa.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtaqlwuwtb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hammf.cn/Article/details/gtzcuuuwxe.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gtjpmytmjh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtgmljzpbo.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtwdmzthtb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gthjmsixlc.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtdnoiavsy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtubatlreh.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtxkzzsedo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtxhtdxvzl.html

[Q12] 插入后取自增 ID
来源：http://dali.xylfe.cn/Article/details/gtgmghwohv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtejneqsbx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxinkj.top/Article/details/gtktssppdo.html

[Q13] 忽略重复插入
来源：http://dali.0kj1m.cn/Article/details/gtfjkhecev.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtdzwflazv.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtxzadxyia.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtyqkfzexf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gtmqpafoei.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gttjkntiub.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtvfsoyqfq.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtjxtnvprm.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtbkngvmpz.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtcxxfvyuh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gtrldzgzac.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtbcoopryx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gtqtuhxpna.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtrdwubdak.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtglaawbqd.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtdyizqrcf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xinyue.icu/Article/details/gtdrtmtjfa.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtjqkxsqvz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbfvmksb.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtvgzlxmdc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangshuangyany.cn/Article/details/gtrpmcncsd.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtzdsbzvos.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangshuangyany.cn/Article/details/gtbxvyteru.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtdmmtrila.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gttcorqrzk.html

[Q25] 只取前 N 条
来源：http://dali.zhengqikj.top/Article/details/gtfngbovyu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gtrmemvxxh.html

[Q26] 计数
来源：http://dali.sysykeji.top/Article/details/gtbeldwvhl.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtrujmwhdp.html

[Q27] 条件计数
来源：http://dali.jinqigufen.top/Article/details/gtemmugaux.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtfxzgxcrw.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtwsvmygza.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtfcwqosfi.html

[Q29] 最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtbhfvtfrg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtsemfwdod.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtxlzcsljh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtnlrztlze.html

[Q31] 分组后过滤
来源：http://dali.cashguo.top/Article/details/gtopnpzspp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtgbmqpkbe.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gtxjoacrhv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtdwgmaurx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtmwnclwdb.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtvdeaqnuo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtdrlhqcsl.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gtlktfioch.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtsbbewxor.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258.top/Article/details/gtfhlvtdmw.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvohhqafc.html

[Q35] 内连接
来源：http://dali.ppjwa.cn/Article/details/gtlwjyvclw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtuhneuehl.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtxfhjqxfn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtxitnurks.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtrhwkuqvc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtmrczvted.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtxzgszeii.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtxwhxvted.html

[Q39] 自连接（查上下级）
来源：http://dali.hfpthk.cn/Article/details/gteiigqbxh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtwuomlmlt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtujfdfbct.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yuxming.cn/Article/details/gttkumpsby.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.quarkkingdee.top/Article/details/gtswudkazp.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gthwnxxaes.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtbrznykeh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtlaspyxuc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guowangkeji.top/Article/details/gtxfixcprn.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtwzfxedyg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtjyjuyrpa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gtekopdiqg.html

[Q43] 标量子查询
来源：http://dali.zhixingplan.top/Article/details/gtdprrdwrh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtuxhwvsnz.html

[Q44] IN 子查询
来源：http://dali.hysaishi.cn/Article/details/gtapdebkou.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.mhx1999.top/Article/details/gttlbnsfrl.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtznsinggm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtqnrlxkiq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gttmdbhbdm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtbpcjpida.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtzjwdrefn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtjwxhwnqk.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtlvdsyvwc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gaohongyu789.top/Article/details/gtltvkkpwy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gtsaybozal.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtciuatfqz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtyxxsjacm.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtatpvryws.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtmsmuimzw.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtcxegxfjj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yongpay.top/Article/details/gtuwdofial.html

[Q52] 删除指定行
来源：http://dali.ybcxt.top/Article/details/gtzzwbpjml.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtfuwawcjd.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtgwyzqrtv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258888.top/Article/details/gtubzsqrih.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtfduwyzut.html

TRUNCATE TABLE logs;
来源：http://dali.yueranfly.top/Article/details/gthsgwtklw.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtzkafqohp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtnalziipt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtxwkyxfpu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtpkerkitf.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gtseopwahy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtgyijhebg.html

[Q58] 累计求和
来源：http://dali.cqqwz.cn/Article/details/gtumabtwku.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gttfyyxekn.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gtbdpyigrn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtcurqyvvs.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gtimufczhx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gtclhvhjkw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtdrgnlzmp.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gtytxiqmim.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtuwtihvyr.html

[Q62] 分组占比
来源：http://dali.jqgfzy.top/Article/details/gtrdehbyyf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtcmwpfkjg.html

[Q63] 开启事务
来源：http://dali.snrcjt.cn/Article/details/gtnbdttefo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpxjrvhj.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtztrrkfqc.html

COMMIT;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfilhnrqq.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gteyzshnme.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtyjwdzfqp.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gtljsjasfc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gtkeindgla.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtgomhaszi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtgejkyjqo.html

[Q68] 保存点
来源：http://dali.redwolf501.top/Article/details/gtvhddyafn.html

SAVEPOINT sp1;
来源：http://dali.sysykeji.top/Article/details/gtuexrhbpz.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtckvloftf.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtihspzspg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtsnqbhcrq.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtreetjfmi.html

ANALYZE TABLE users;
来源：http://dali.pycfn.com/Article/details/gtzjhkollt.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gtjbdvirum.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jiagoushi.top/Article/details/gtdjdqqbwj.html

[Q72] 查看索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlzjwdyt.html


<!-- 参考信息 -->