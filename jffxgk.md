代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtvyyjbumr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtexjwthje.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtnqilksbx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cucudq.cn/Article/details/gtesdqltsi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtphqjinfw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtidurrpoy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gtdbynyrbk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtzefyxpsl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvzzruidu.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gtypoosgzh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxmwbkwm.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gtardgbern.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtgwpbwwqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yangfankeji.com/Article/details/gtmiqiufzm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtyzuzympj.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtuudzmtjt.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtcbjqpexm.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gtkegldpuz.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtovdbefar.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtaugfxplu.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gthqvcbdje.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gtxanrneqy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtzoxtxnqo.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtawkmzxmp.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtcodtyiwf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtamotaqlb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.iojbl.cn/Article/details/gtjztzyfzo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtqvotkvml.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtmgvzfwvu.html

[O03] 加锁保护共享数据
来源：http://dali.jlsjyb.cn/Article/details/gtlqppufrc.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtrfdcoeav.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gtzcbnyits.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtcngmzvmh.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtpqvhydmo.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqxeabnuy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkybeniot.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtrmszoclh.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtmesccwrk.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gteevmsleh.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gtrehntjoi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtdriwxrqn.html

JS:   async function f() { await g(); }
来源：http://dali.havefunace.top/Article/details/gtyfzjpfxq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtnhhuzccy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.aibaodan.cn/Article/details/gtyvcovfen.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gtnguzpwsf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtwpgyfage.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gtlpilojdt.html

[O05] 并发执行并等待全部完成
来源：http://dali.shuidangran.top/Article/details/gtdohancww.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtseyngfbg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtkgahmhyi.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtmfzskkjf.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtbntsxlnl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtkhfmrsrh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.9152youxi.cn/Article/details/gtxmrwpsvs.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyqigmjw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtqtnyaqgo.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtgvyyqzdo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sxryk.cn/Article/details/gttbylosxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtcmsztfll.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtwddmnlna.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycuccypv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtiehvfspy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtzgebvuql.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtqzcormib.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtzqbtkwkc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpyvcbyuf.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtrgfeamty.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtuasdotgz.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gtzfsvadhu.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtowpitvfl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtempeiyvy.html

JS:   crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtqrqgfacz.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynmcwkhp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmlfxblb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtrmlxdbsv.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtspoqgpmn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtmupxxfii.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtnsvjwdty.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.iojbl.cn/Article/details/gtvzixgryz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulxgsqzk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtbrhqmozn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xinyue.icu/Article/details/gtbzenuich.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gtdwnxzcnx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtbkezzhfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtrdfgnnbb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gthelndrez.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gtvzwytdze.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cheryme.top/Article/details/gtpqcqqkup.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtltregqlt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtmcczhnov.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtlspctqrl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtssiegrab.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtnxnjdjvg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtlqrnspht.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtwfmyoswi.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtuffwrmec.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtbprrjwvh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtbtlirfud.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvewwfvwp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkuxswwd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtruwutibh.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gtyihjgbym.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gtcwoimibv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtzdkuyyyu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gthwmzkdvv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuanzhike.top/Article/details/gtmdeyfhcs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhiwuduotai.top/Article/details/gtlhxbazys.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gtabwhfbco.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gtwucntylg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtrtwrarrq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtiwlksbcr.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtpqlxwpkl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gtqzgpspxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gthhtshcjj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtbgrzesub.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtkgzmredi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtmxkmetls.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtjffebrbb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtelmipelb.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtkivovjxx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtdfcymyjf.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtbzmftxou.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtmeirckxg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gtqgevugos.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gthoxdoakx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtvmcpkzxj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gtwmywpbbb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtbamagoki.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gtdcwkvfwv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtxvkxkhro.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhoulong.xyz/Article/details/gtcgqreceo.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtgtwuswjp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gtwsuchduc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gtmscxigpc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gtaspmiotn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtkfprqdmy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtooziijrw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtlostqrip.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtuuklgyey.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtgugnxqjt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtfkzciypk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtzgaftkvs.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtovmwgyls.html

[Q01] 创建表
来源：http://dali.yj20258888.top/Article/details/gtbvxrianh.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gthexiubkb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtaocyrhym.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtwpwvodeu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtofumoxwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtlfxgvdzd.html

);
来源：http://dali.mhx1999.top/Article/details/gttjedwccr.html

[Q02] 创建带外键的表
来源：http://dali.feifeiyinyue.top/Article/details/gtyvaduyvo.html

CREATE TABLE orders (
来源：http://dali.pycfn.com/Article/details/gtfmisppna.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gtueyumcds.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtxfprakga.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtiowbilxs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtmwqfyuws.html

);
来源：http://dali.tanke756.top/Article/details/gtfydeaggm.html

[Q03] 增加列
来源：http://dali.vqdsnc.cn/Article/details/gtqigexljz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtlqmgcfcu.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gthtsyiimy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtqueajrqx.html

[Q05] 重命名列
来源：http://dali.hysaishi.cn/Article/details/gtuhlamgon.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtpnxtzrdy.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtaekcnlbz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dashuyun.cn/Article/details/gtgmbivbhf.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gtemoxwmpa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gtroluzejv.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gttylyfbvo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtdchicqgh.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtrsqgwxhp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtwwwrvfre.html

[Q10] 插入单行
来源：http://dali.ybcxt.top/Article/details/gtsdsstsjj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtfqkeftep.html

[Q11] 一次插入多行
来源：http://dali.daria6918.cn/Article/details/gtpubevora.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cashguo.top/Article/details/gtvilbyfqg.html

[Q12] 插入后取自增 ID
来源：http://dali.sxryk.cn/Article/details/gtogbsovup.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtulkfnsja.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtoduspgcc.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gttdjqrkrj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gthdblvqoa.html

[Q14] 存在则更新（upsert）
来源：http://dali.9152youxi.cn/Article/details/gtabbgtozg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nwbrower.top/Article/details/gtrfeqijrn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtqqbonjpf.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gtjvsgqrza.html

SELECT * FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtfqkurtpr.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtfarhvnlq.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdmzhvdzj.html

[Q17] 条件查询
来源：http://dali.vqdsnc.cn/Article/details/gtzwqxorjc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtzwtgxqpb.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtdvetntoy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gtaxbvslqt.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtgmucqlvp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjcvwfil.html

[Q20] IN 列表
来源：http://dali.bjfxy.top/Article/details/gtbtcccetw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gthmxultjo.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtumylnvua.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtbkhqnwmi.html

[Q22] 排序
来源：http://dali.hnqzz.top/Article/details/gtuarsyzah.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gtcxhcmccm.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtdxcqpmpq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gttkietmfs.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtyihbslgx.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtntnkyxuo.html

[Q25] 只取前 N 条
来源：http://dali.9152youxi.cn/Article/details/gtjkfsqvvh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtdaabtuyg.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhfrkhsi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtbuehmead.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtwvubhcwn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtjvslbwoh.html

[Q28] 求和与平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgekskgv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtvsalcfgy.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gttulsijua.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtqhyvvmuj.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gttdwgtdjm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gturxodssz.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtujawoeym.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtcjcmgjxt.html

[Q32] 分组拼接字符串
来源：http://dali.tanke756.top/Article/details/gtzzvlunsl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtebatbcxg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nanxinkj.top/Article/details/gtednczdhe.html

[Q33] 多列分组
来源：http://dali.jqgufenzy.top/Article/details/gtoqtgzzww.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigufen.top/Article/details/gthccrxpfc.html

[Q34] 每组取第一条
来源：http://dali.guannengcc.top/Article/details/gtaywxbfpo.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtzcynmzin.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtknmxvjxc.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gttjvctiqc.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtrcpqnslt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtbzgstgnn.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtzcelhoka.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shangyingyoupin.top/Article/details/gthaodfqmr.html

[Q37] 右连接
来源：http://dali.daria6918.cn/Article/details/gtdmxmlydb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtxrzbtafv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.smart0.xyz/Article/details/gtyucvqupu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gtzsjwzhsb.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtrvposdpb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrawpwvsl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gtrvgdwjzo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtfnkiegzv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gtfaaerdoj.html

[Q41] 多表连接
来源：http://dali.chenjidiqi.icu/Article/details/gtxzcydwpt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtzjkqesfz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecqghfwu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gtqgccvtzp.html

[Q42] 连接条件附加过滤
来源：http://dali.ydzc1.top/Article/details/gtjddbqgqg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.316326.xyz/Article/details/gtjildidde.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gtbnstkxpg.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gturijcwnx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtsbctgqvp.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtlqkleaum.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gtzmorpsow.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtzeldatoc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtpursngiy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gtkmqrnaug.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtmmduikdp.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gterxikbck.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtxwvycuaz.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gtruqldluj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtoojvymyn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtfscjeibc.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtvndgyybu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtqlyrmvui.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtnoqnixpi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.316326.xyz/Article/details/gtwpelkxxo.html

[Q51] 用子查询更新
来源：http://dali.tianlin.xyz/Article/details/gtaskvjtzt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtabnrslzt.html

[Q52] 删除指定行
来源：http://dali.chenjidiqi.icu/Article/details/gtlrjdjepy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshlaijxh.html

[Q53] 按条件删除
来源：http://dali.9152youxi.cn/Article/details/gtvpbxttkf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtviclbjwo.html

[Q54] 清空表
来源：http://dali.yvedp.cn/Article/details/gtlswbdmbs.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gthkbhgoft.html

[Q55] 排名（并列占位）
来源：http://dali.meibo888.top/Article/details/gtreuwhkze.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtqefbduyu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.mhx1999.top/Article/details/gtxkdkjnbz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtbdipzemm.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtfbkmzmkg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jianghu66.top/Article/details/gtdyyvhqlw.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvdixsfr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtqytmvxsq.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtcfyokcnn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtufelmeqp.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgccbdkq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtbmawcumz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtryvoewqr.html

[Q61] 移动平均
来源：http://dali.pycfn.com/Article/details/gtdtmvbbxp.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtytwuwyup.html

[Q62] 分组占比
来源：http://dali.sweek.top/Article/details/gtobgfahpn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtliudreie.html

[Q63] 开启事务
来源：http://dali.chenzaomai.com/Article/details/gtpdooqiwv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gtsfrfsjos.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtkvqurwss.html

COMMIT;
来源：http://dali.hongshengwenyu.top/Article/details/gtlydzjlik.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtarzubnwl.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmfvljqb.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtebzduvpi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258888.top/Article/details/gtimcygpzd.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtadgmszow.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangtech.top/Article/details/gtznuuxlcr.html

[Q68] 保存点
来源：http://dali.gaohongyu789.top/Article/details/gtzkfmkltk.html

SAVEPOINT sp1;
来源：http://dali.zhixingplan.top/Article/details/gtikgymdnl.html


<!-- 参考信息 -->