代发 wailian999

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqgfljjfb.html

O. 并发与异步
来源：http://dali.zhoulong.xyz/Article/details/gtzcnltiyx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqrfmcab.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gthwrzagua.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtkomnikgw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtgdvfxzpx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtpwerkryq.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtzywksmcx.html

Java: new Thread(() -> f()).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtczhaheqi.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtpzxnkqnv.html

Ruby: Thread.new { f }
来源：http://dali.jiagoushi.top/Article/details/gteecmcqrh.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtbklmfyls.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtkiacgchk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtwwzmvrjs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuanzx.com/Article/details/gtudhizcvy.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtwssymfwv.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtyylnnvws.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtgconzvew.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtlczvouyi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfraadtu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtdendmfre.html

[O03] 加锁保护共享数据
来源：http://dali.chenzaomai.com/Article/details/gtgtpcbnex.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gtfscfzcqz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtbydgjnjd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtmlvvzgwt.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gtqdaehqtq.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtrehzpdla.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtijyubmvb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gtgmedrdft.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtdiwynlyp.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtviabpqtl.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gtqtnzcwty.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shzxlz.cn/Article/details/gtdupbgkri.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtlpgijhfj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiahfbhxi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtpdjutkch.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdghjkylv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangdashe.top/Article/details/gtrfxxdwlx.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtfnazpjbk.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtpaxypmoc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtzwklaoez.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtjjizozgz.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtahdhleug.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtlhzgkrsi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gttowfodpg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daria6918.cn/Article/details/gtktfkuyji.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtwwlrrulg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtyjhvazfw.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtklolhbrs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gtyfyvkhox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gtxpmyzkzx.html

JS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gtceccfase.html

TS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtaavewpmk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtzbtfpuog.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gtvfpvsvwl.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtzfiqxpmu.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtwjtednem.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmvxiddwk.html

P. 常用工具函数
来源：http://dali.316326.xyz/Article/details/gtsmqstatv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyrvrxvwo.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtpsszovnb.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtcfrikwko.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gtcgcwknyo.html

JS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtcxniwtew.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtlyscgaea.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtqjfvopxc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtorxmbyqz.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gtqlpbqopy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtgypjxhgk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtpshnfqxd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ybcxt.top/Article/details/gtdjdizari.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gthmfglcnb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gttdvxfrrn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdphjihit.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrqwyaou.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtrpihjcmn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gtajurirog.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gtqcqbtykw.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtowsefsoe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenlongwang.top/Article/details/gtishphqzw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sxryk.cn/Article/details/gtzvuaezaa.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtqehepvag.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gteudeuiic.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigfzy.top/Article/details/gteurciqcy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuetiantiany.cn/Article/details/gtgkrzcjee.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtoedxxiub.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtbfujudul.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtbglmlhrd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fzhhl.top/Article/details/gtgvorqdmp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtglxlrvmx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtbpeoyrqr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtldquyxva.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gzhubu.top/Article/details/gtkwqluuce.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtapdidzgh.html

Ruby: x.length;  x.size
来源：http://dali.cqqwz.cn/Article/details/gtjyxnfdld.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gthbyxuayk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtsvlreyeo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtitculauh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtsenxpteh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gtnwfsyigt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtgyxikedr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtyrrbrxgb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtwzgtjxam.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtyurrwmss.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtoaxaufdj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtvfhqikje.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtnbqeofxj.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtoranwkvm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtxgwujajs.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtyedhzapt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtribuqodj.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtdcoecxdz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoroifqoa.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gtnensjvjz.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gtpcpphkdy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtiniskiya.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtsbdwrikd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtwyedcrbi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gtlsietucc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gtevwuvjcc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtlyjpyjmc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gtdbdgezsr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtarulabho.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtfsxndqei.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtlibakqim.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jianghu66.top/Article/details/gtptcozdlw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtymmqmmdc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtitahawqp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yanxiufei.cn/Article/details/gtzquddixy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gttmuxzxgw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtuzbnrhhb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtbtcxnuss.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkqainvjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenlongwang.top/Article/details/gtprcboglq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtymmhvjcj.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtumsxusqg.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtztcpbvqp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtiqmevbtu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtqsoajfbt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtjjljvtxk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtjvxwubqk.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtptwqswpa.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gtzithrhvx.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtgmwnkevz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtyjsiiyew.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtsezygzqa.html

amount DECIMAL(10, 2),
来源：http://dali.jqgufenzy.top/Article/details/gtwobvvbdv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.fzhhl.top/Article/details/gtggucbccf.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtnyqzywgq.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtbxpoaxgs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gtdswlwbsd.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtptozqcts.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgfzy.top/Article/details/gtdgsbwqsc.html

[Q05] 重命名列
来源：http://dali.yuxming.cn/Article/details/gthjsimquk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaxrldhy.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtdabixpth.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yueranfly.top/Article/details/gtyhtxizqg.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtkhfstndd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtctwzkopp.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtjhqqjpzb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtribnkcyt.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gtlxtqovtk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gtromdpsma.html

[Q10] 插入单行
来源：http://dali.iojbl.cn/Article/details/gtxlphqqkt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtloclxshi.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtgmkpwito.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yonumen.top/Article/details/gtvlblrxym.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gtssuxlrkc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gthrjewlwy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gzhubu.top/Article/details/gtpgbijqmw.html

[Q13] 忽略重复插入
来源：http://dali.havefunace.top/Article/details/gtwgjpuetr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtdtsbhetz.html

[Q14] 存在则更新（upsert）
来源：http://dali.ppjwa.cn/Article/details/gtrkqtuchn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yvedp.cn/Article/details/gthxqwfsnh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gtczbbeeuh.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtuioxvbgk.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtfyicorev.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsrfomek.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrejcketr.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtkekykckj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtfytdxdwd.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gtztaqddvu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtnqshiznk.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gttgnugcxr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sufxvd.cn/Article/details/gtqptjgshv.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtpuhruxgw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtgfjfxcaf.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtlyblhlic.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtfcdqybnz.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtodivivma.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gttdoyncho.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtzbkeeerr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gtiecezzur.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gtslhqljhw.html

SELECT DISTINCT city FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmqdusslq.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtlxesjsun.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtfrdspvlf.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gthvoixwut.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzfgtdktd.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtbkrwdkut.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtcdecgmpt.html

[Q28] 求和与平均
来源：http://dali.c1oappe.top/Article/details/gtugfotndp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtxnsxjxnc.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gteoxgbfvk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvvybwnnm.html

[Q30] 分组统计
来源：http://dali.zhongyouzk.top/Article/details/gtzsallnft.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtzzhsmiju.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gteesxsofy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtxyifcjvg.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gtnabmippg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumdbytcc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhiwuduotai.top/Article/details/gtkbyptfwv.html

[Q33] 多列分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfrlklth.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtjzsbtzct.html

[Q34] 每组取第一条
来源：http://dali.yongpay.top/Article/details/gtjgqjcrfp.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gthtdgkcic.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fengsongda.top/Article/details/gtdcmmpfgk.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtbeeumafs.html

[Q35] 内连接
来源：http://dali.hammf.cn/Article/details/gtmumyiknw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtemupfywc.html

[Q36] 左连接
来源：http://dali.xziqi.cn/Article/details/gtfwhfzaof.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xinyue.icu/Article/details/gtzjtnvkeo.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwncscqc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gtpveerupk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtprikhmta.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmktfxqq.html

[Q39] 自连接（查上下级）
来源：http://dali.tian-w.cn/Article/details/gtiulzycyj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnwdwidh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nwbrower.top/Article/details/gtbohcxerg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwbopald.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtsxiwwfrs.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtynxajtzd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gthkpwfkzr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtpvlmiojg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtppqrharb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gtsncfwwiv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jiagoushi.top/Article/details/gtpngamzui.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gtwrjnaglp.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtlxkwokms.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.mhx1999.top/Article/details/gtpdhfurri.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gtueompqmv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznoajqqu.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtxhtzebzg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtpxhcwcax.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtsltycfbp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdjeqkjd.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtxxrqkhgf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cashguo.top/Article/details/gtbwetdiko.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtpltrpndx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtzbofdcok.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtzgbycvnx.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gttiyyskan.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtkumaqxib.html

[Q50] 批量更新
来源：http://dali.9152youxi.cn/Article/details/gtvxhcegsi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtnewsxlpr.html

[Q51] 用子查询更新
来源：http://dali.jqgufenzy.top/Article/details/gttnfxtbda.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gtroxrxtle.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtpfhbtlvu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtvayxserh.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtfwlghtam.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtpoavienl.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtorhduouh.html

TRUNCATE TABLE logs;
来源：http://dali.jlsjyb.cn/Article/details/gtoknxcyyq.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtsfvlfaje.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtzysgxfat.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtsidrjdia.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtgnklhcyn.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtxsgsdtyw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtjxlwzhlf.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtrzqavcig.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtbohwguhq.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtkakcebiy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gteckbmefu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtzkhkrafz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtnzkcgntl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtucnijxmj.html

[Q61] 移动平均
来源：http://dali.wangdashe.top/Article/details/gtyhlfvcwh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtkskfhoyv.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gthxihieed.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gttgbjqwsr.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtoxyfnbvn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtrqyanuii.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtnsdkfipc.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtateqftsu.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gttcsotukc.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gtnzdrpzpf.html

[Q66] 行锁查询
来源：http://dali.zhiwuduotai.top/Article/details/gttpyznrpy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtaupoexmr.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gthbczwdwj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gtfceatpif.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtnndhvmax.html

SAVEPOINT sp1;
来源：http://dali.nanxinkj.top/Article/details/gtdcvgxucr.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtorqlxhnh.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkcjgrit.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gtyswzuxzi.html

[Q70] 更新统计信息
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamquhxvb.html

ANALYZE TABLE users;
来源：http://dali.bjfxy.top/Article/details/gtqdzrylqh.html

[Q71] 查看建表语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnegpfel.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtzaockqud.html

[Q72] 查看索引
来源：http://dali.fzhhl.top/Article/details/gtdkncuzii.html


<!-- 参考信息 -->