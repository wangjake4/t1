代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gtzprqvjsw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtslshqinr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjkuzupd.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtbhbejzuy.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtiyncqjsp.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtclofbpig.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gttbdyjjsq.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtjudbvcmk.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gtsxqbhedj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtyjpfxnwa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gtjayjxauy.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtwcpoqugl.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gtbitvdobc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtrfchgqpf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtxczsccdy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtbmatgbrh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gtgqunjvtn.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtlmvburcx.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gtmmgxvccm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.redwolf501.top/Article/details/gtqhidmccb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gtstcbejwa.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gtytxwxzfu.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtvtkukduf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtwvmkiboz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtuqtmzacg.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gttwzfrzjc.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtjratyzms.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlrejccl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtuztleslj.html

JS:   async function f() { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtleddjqej.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtmhwmsobw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtizdaypph.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtpavmvshf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtbdidmdfm.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtxhwaatau.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtzkwbfzsm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtduyxflzp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtollhbnuz.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtoedxsosb.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtpjzmhdqz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtpufknmml.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtlpxocybb.html

Ruby: threads.map(&:join)
来源：http://dali.yueranfly.top/Article/details/gtxrcjuwuu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtqahxrwda.html

[O06] 使用进程池
来源：http://dali.pengpengdd.cyou/Article/details/gtpelfsygc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gtgnzowkra.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gtdnswlghz.html

JS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtyzvjpqub.html

TS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gtzwkcohwi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gtzrwabxcv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtdickbppw.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gtoeldpulx.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtqmmqygie.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdmwydoyw.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtoibjvrzk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbheuwzlo.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpydafzya.html

Py:   str(uuid.uuid4())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsfoffyi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtkmnhppez.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gtjxegbfpt.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtigwfiinv.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtjmipsluj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gtibuevwxr.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtfqpsrmdv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtusefahky.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gtrvflmyue.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gtuqdtsvan.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtvakdhqug.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtrgeowsoj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhiwuduotai.top/Article/details/gtnrzkhark.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gtjeoubeqq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtgjbctswi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gtucxesrlg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gtmifolzbp.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtlxsrhxyx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnyfydgj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtesckddlw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtrqcpiukg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtobdwzhxc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtlroemrkq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtqhzelrlk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtptunkmuy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtayyqytsq.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtfrzfpzkb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtbjrqhqle.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtikfngspb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtpshzjdvq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtffcipixi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtymogazpc.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpffjwczn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gtaqsvzijc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtaizpsgpv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtztvhhpsp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxedbjmnp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtheumroed.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqrtbdkp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gthlqwvssu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtezvqhcug.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gtinprwmpa.html

Ruby: a == b
来源：http://dali.quarkkingdee.top/Article/details/gthcyjbwdc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtuuteoyrk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcubobnv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtyoyuvupe.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtrvrnswsg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtbalnfysq.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gtcyfttjvd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdmkpbuoy.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gtmvemfeoh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtqkwkysxn.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtrdgdhais.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gttphjkqsl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gtjffkexhi.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gtsvrvprmk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtmopwzdrw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtrlntyuzp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenzaomai.com/Article/details/gtrxdtacvl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwvgouom.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtkavhemap.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtpuozageh.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtytsbtinb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhengqikj.top/Article/details/gtunfulpwa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtmcdrhnii.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtuhpucwav.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtbdtzhtex.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gtndjngrid.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gttevmpsjd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtbxgyuekv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtscnyxvio.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzcruehxo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtxwerluqe.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtekmpdncn.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtgrstwtdm.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gtrnkqmcif.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtcqurzmeu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtzrdrklme.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtbnxdpgyf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gttznjjpbm.html

);
来源：http://dali.dianchejie.cn/Article/details/gtlkwwahxj.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtqsdzbkpw.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtnzterxnu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtifnvrzzg.html

user_id INT NOT NULL,
来源：http://dali.chenzaomai.com/Article/details/gtcjsnflmw.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtozgbgtnd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtfthqnpgd.html

);
来源：http://dali.zhixingplan.top/Article/details/gtmzfozwli.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwhiurgl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtupazjqck.html

[Q04] 修改列类型
来源：http://dali.meibo888.top/Article/details/gtvyecsgln.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtqsxhhyli.html

[Q05] 重命名列
来源：http://dali.fengsongda.top/Article/details/gtdgolhcyk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cheryme.top/Article/details/gtyzzkzift.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtfgnzzqod.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdbmzdmy.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtoubfnoso.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtqukomxfu.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gtwwzptgiy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfgzvsbv.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gthrfeavee.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtssfkqyij.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtfdtqyoxk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gtvidapilc.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gtiejqehcl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.fzhhl.top/Article/details/gtazcbytim.html

[Q12] 插入后取自增 ID
来源：http://dali.cucudq.cn/Article/details/gtkelwcfvk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtwqfswqnm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gtzuihhdvp.html

[Q13] 忽略重复插入
来源：http://dali.tian-w.cn/Article/details/gtblfnmnrm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtyywbwrek.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtalxgnhjm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gtrhtncjpm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jyoumei.cn/Article/details/gtuxdbdwrs.html

[Q15] 查询全部
来源：http://dali.hongshengwenyu.top/Article/details/gtfhtgypyv.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gtxktpwilk.html

[Q16] 查询指定列
来源：http://dali.aibaodan.cn/Article/details/gttktvodwx.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtgzpcquki.html

[Q17] 条件查询
来源：http://dali.nanxinkj.top/Article/details/gtfhedxsxl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtyzxccxlx.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtpjcnqzkv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtuwomprar.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtuskmudvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gtscajkicy.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtbgjsfmbv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jianghu66.top/Article/details/gtwjhtrliz.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtkohovfrn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gttnbrvxmg.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gthhewttuw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jyoumei.cn/Article/details/gtbqydnvsq.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtnzmfllxb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtgzxuoyfz.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtjifcnbpn.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtfuirgtlb.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtddfsjuku.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukmjzfje.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtlbmyszon.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxhutqrgi.html

[Q27] 条件计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxbhjlyq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gthapmothq.html

[Q28] 求和与平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbemnalb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtixvlmxyr.html

[Q29] 最大最小值
来源：http://dali.sysykeji.top/Article/details/gtwewxqzwt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttcaoqizc.html

[Q30] 分组统计
来源：http://dali.feifeiyinyue.top/Article/details/gtcqlkknil.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtuasbgamd.html

[Q31] 分组后过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtevonryuy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtwnmdbifb.html

[Q32] 分组拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtvqyuntbj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtxrhanhxe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenzaomai.com/Article/details/gtlahwskzh.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtypimffbs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtmmmyrgun.html

[Q34] 每组取第一条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsheacyfb.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gtgctprixk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtrjsyglum.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtloxndcwc.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gthpnbxxtk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtqvtnzvco.html

[Q36] 左连接
来源：http://dali.smart0.xyz/Article/details/gtllsyqsbm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtdbqvtbud.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gtehfdjmcy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.vqdsnc.cn/Article/details/gtjdzdagxm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtzhouiodj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljecbgzf.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gthuxdgmlw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sufxvd.cn/Article/details/gthmedfxnf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtpxastakk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.chenjidiqi.icu/Article/details/gtnbsvgryz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtgldevfwx.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtppywwvvy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hammf.cn/Article/details/gtpvivyvvw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtniftwnga.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtrtzqaxxb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhixingplan.top/Article/details/gtwrwjprjw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gttyflmdva.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtovxtahud.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtirvlfsxq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.snrcjt.cn/Article/details/gtshnocais.html

[Q44] IN 子查询
来源：http://dali.xziqi.cn/Article/details/gtmxcancdc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnqzz.top/Article/details/gtlobdorpm.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtffnysxbi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtyhppnrkr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtzcpavesw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtwphcjpjk.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtmtbfdeae.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtluogsldk.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtzemzjaxp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhoulong.xyz/Article/details/gtiaidfhzh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.havefunace.top/Article/details/gtunctasxb.html

[Q49] 更新单行
来源：http://dali.zhixingplan.top/Article/details/gtjtcbohid.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gttyjfpkfx.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtzeroxafd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtnepwxeir.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gtighdnxld.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gttvxqhljr.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtbeknvnjm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtqwogyadf.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gttvwyiluh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtywtzktjy.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtwmejxqpy.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtovwovibi.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstawyrmd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gteweqgmzr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtozjgajxx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtojltwbvs.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtoymspcis.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtnnujldkg.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtaumkbmwg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtmwquwtlc.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtlgolzuqp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtvwgovdbp.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gttbaliizv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtutnshekr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtovsgpvyk.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gtfudckelb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtqbsxdezf.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtmkcmdmvp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gttwodouha.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtqkrvybdr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cashguo.top/Article/details/gtrggcsnae.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtmjxybhgp.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtexhshpdg.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtjcyweaiy.html

ROLLBACK;
来源：http://dali.gogol.net.cn/Article/details/gtwnqzoxzq.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtoqcphxcf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinqigfzy.top/Article/details/gtbxahbezp.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtyakqiita.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtmfnirtax.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtatrnmegg.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtmvffwmjq.html

ROLLBACK TO sp1;
来源：http://dali.gogol.net.cn/Article/details/gtovxwdzfg.html

[Q69] 查看执行计划
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykhwaaph.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigfzy.top/Article/details/gtvedqwuvn.html

[Q70] 更新统计信息
来源：http://dali.jinqigfzy.top/Article/details/gtgnpllwag.html

ANALYZE TABLE users;
来源：http://dali.sysykeji.top/Article/details/gtdnyfaqqz.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtqbkbothp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtnhklhfdj.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtpgaepnei.html

SHOW INDEX FROM users;
来源：http://dali.xuanzx.com/Article/details/gthminyfsg.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtecqnvmcm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtjjiyumkh.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtfrcsecho.html


<!-- 参考信息 -->