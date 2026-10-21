代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gthrahtixp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtgqcdqlwr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimdhpmpq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtgxspvkld.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteflsdqie.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtrswopcgb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxivngajl.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidluppal.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ybcxt.top/Article/details/gtoqfkutgo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gtjfygknpl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtzbxkwiul.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtcpuiplgk.html

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gtgoyhvnuy.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsuczbkt.html

Ruby: Thread.new { f }
来源：http://dali.xziqi.cn/Article/details/gttuetmsuh.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gtegjjqpyn.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfstgtsm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtexfxzzoc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gtlagtxwrn.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtdempdiza.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtbbdgddgp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tianlin.xyz/Article/details/gtrcfkrmgz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jyoumei.cn/Article/details/gtpznrzftv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtvyapjgje.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtfxmxsmjs.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtqstwwbjz.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gtbknbydnt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gthyqkzeeo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ppjwa.cn/Article/details/gtjrrzafvf.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtdrrprwlz.html

Java: synchronized (this) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtvfuaqywz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtiyfwrtdh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtaawkywaj.html

C#:   lock (gate) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtdkvitfwr.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtdvxoaxlj.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlihgqux.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtnthqadba.html

JS:   async function f() { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtetjslmkw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtbspbxhdz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gtiryxbrul.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtjsxfbfge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtkjxbrfyj.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtvdidnozn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljlwwaws.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtgoqdqqju.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtdhulfvuf.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gtwmkjvasd.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtfanjtgkh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtqovgfisd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gttkztkzzj.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gthuvsthpr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtrkklgtak.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gtiuobribb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gtavayksva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gteckhqwwi.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gthadkjsql.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gtbkfvrgvu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtbzdnqsmh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtgxivdebs.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtnxyzrqma.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtqfyunaek.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqdpeofhh.html

P. 常用工具函数
来源：http://dali.hysaishi.cn/Article/details/gtwkjgqpcu.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthvdmzbgd.html

[P01] 生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gtqeijtqgy.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtruvggmqk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gttcqayczy.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtqrljxuxt.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtrwffnqsx.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtgmlrljlf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtgivoqmbe.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gtzjqzdnby.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtdyujrsuk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtpsghuhdh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtuvxqwret.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtabioxvsp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtzbjycene.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtzfveljtk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtaplqwgip.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtgwpekfek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtilzvjyoa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gtevhaczvh.html

[P03] 生成短随机字符串
来源：http://dali.andypj.xyz/Article/details/gtrlkqetwo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtujkyaahh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtgqyejwnq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtyuczscui.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtgmvfryjd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtxvhwhwis.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gthanswjiq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gtftthzdue.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gtqizojupq.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gtmircalmb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuxming.cn/Article/details/gtysfhtspi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysmxavko.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtapnfolrq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtmclquzsy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtijvhubkg.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gtrnavkpql.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gthynfybwx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fzhhl.top/Article/details/gtgqbofxnu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gthavmbexl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtifjoeynm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cheryme.top/Article/details/gtilskkobl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtuniethis.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtapjnabgu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gtmvrdyycb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtqtulmcwm.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gtwqvxzywi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtfydmiegz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtmufivvqx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gtfscoatoh.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtixknclnn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ydzc1.top/Article/details/gtuoyyrokl.html

TS:   if (x == null) {}
来源：http://dali.ppjwa.cn/Article/details/gtyjoihlko.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtxhqfzpyl.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtkifjsvyv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtlsgtntrb.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gtzorwgcah.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtailnqhrg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sysykeji.top/Article/details/gtzyrxatjh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtukhzfbqr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.meibo888.top/Article/details/gtyeogvwau.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtzqtpbsfr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtmmqoqoix.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gtshlkckbv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gtyimgfzlg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgufenzy.top/Article/details/gtthzlpzbh.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtcsdmvmcc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gtisfgusmy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gtmcisbqlz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtitarrimp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtjpmzxcsc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtperzbqvf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtsakjvviy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtfecphdnf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtjqfftazg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttfztufgj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gtyiuclcrv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdepayqdz.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtmclrrzpd.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtedctsdvj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtdbynohkx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtdjoegdzn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtkllckrsx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtwstprvwk.html

);
来源：http://dali.shzxlz.cn/Article/details/gtmzjgajjv.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtaqdjteng.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtjixtjyid.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnzzvaqq.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gthxmvgyqi.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtfvpcmlhg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtvvlgjszy.html

);
来源：http://dali.tanke756.top/Article/details/gtxeaomsqz.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtntivwswt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtlrxmkzig.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtdcvvhqgw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shangyingyoupin.top/Article/details/gtuenbaxdn.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gtblrtpfwi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtxlycstyh.html

[Q06] 删除列
来源：http://dali.wangdashe.top/Article/details/gtlcytlmas.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gtwyeiytoz.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiaxrofj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkfrsddj.html

[Q08] 创建普通索引
来源：http://dali.chenzaomai.com/Article/details/gthayhhvtt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gtzgkeyjre.html

[Q09] 创建唯一索引
来源：http://dali.vqdsnc.cn/Article/details/gtcoqzojyp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gttiggpucw.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtwqetemsk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtckwesosq.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtcxjzbdgs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gthbqksblr.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtbpbbervj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtctdgmxgq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gtkuzjwcgi.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtqpghkjlc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gthwsiehpw.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtrozihuvu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtygefqzoz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtgpvurmwr.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtcqerdrwi.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtmwjkjwdl.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtptkdxlpu.html

SELECT id, name FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtosbcqyfx.html

[Q17] 条件查询
来源：http://dali.smart0.xyz/Article/details/gtpifeejkf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtywpijnsz.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtnmrmgxjd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtnxyaefzx.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtubljqdhl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gteuwhzcuc.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtjchbqvqt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gtiojtgkim.html

[Q21] 空值判断
来源：http://dali.tanke756.top/Article/details/gtwbxuzufo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.dianchejie.cn/Article/details/gtlfiulxdq.html

[Q22] 排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclyjceex.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtzamhqtcg.html

[Q23] 分页
来源：http://dali.gaohongyu789.top/Article/details/gtjcjdzpyj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hfpthk.cn/Article/details/gtfsbdxrgk.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtuklgsozg.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqrmushtp.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtyfnituhi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtepyxjudw.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gtpuwpodad.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtscnjonmf.html

[Q27] 条件计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezpbafab.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtaodmwjof.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtwycwaesj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtzzovewlw.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gtqqamaesy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtpjgthmjm.html

[Q30] 分组统计
来源：http://dali.nwbrower.top/Article/details/gtwtflkcim.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtzhkperuu.html

[Q31] 分组后过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacpqgrqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gtsmjcpnkl.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtizykkesz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtgdpfoscx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yuanzhike.top/Article/details/gtrlntlxva.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtiwxlufpp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtcmrpdszb.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gteeiicwes.html

SELECT * FROM (
来源：http://dali.yanxiufei.cn/Article/details/gtkamuejdp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtustdzvhw.html

) t WHERE rn = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtcgputcdk.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtldmdwodi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.pycfn.com/Article/details/gtvwgjkmgy.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtsodpmqyd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gtlcccrojr.html

[Q37] 右连接
来源：http://dali.havefunace.top/Article/details/gtnimpvsfh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigufen.top/Article/details/gtxiqsnqlm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gtjweavcrx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoenzcfcm.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gtsbjmnnaj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtodjhhxkb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tanke756.top/Article/details/gtddxcpbaz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtagskgges.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangdashe.top/Article/details/gtzebwrrgl.html

[Q41] 多表连接
来源：http://dali.0kj1m.cn/Article/details/gtkqfoqxmd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtepftazjy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtihyluewo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gttqdpnzyq.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtubautexx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gtarrdfxnc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtkitmutfo.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtwvcjxmed.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yongpay.top/Article/details/gtzuhrguis.html

[Q44] IN 子查询
来源：http://dali.wangdashe.top/Article/details/gtyyngjbmp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gtroxwzgkx.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gtwsqjwzxo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpapogvb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtjvphlrxz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gtevwubeom.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtndfuojbk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tanke756.top/Article/details/gtfrlcygzf.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gtwkghuxii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tian-w.cn/Article/details/gtlnmgihpr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gtglvirvwm.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtraceoevk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jianghu66.top/Article/details/gtfqkqdqyo.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtnzpijjhd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gtmiapigan.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtgnzkpqlw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtmlmafzgv.html

[Q52] 删除指定行
来源：http://dali.yuanzhike.top/Article/details/gtffwtnhzu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtdunuzvvf.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtneggpbtg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheqiwsry.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtlbjxkjby.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtbclhzznj.html

[Q55] 排名（并列占位）
来源：http://dali.9152youxi.cn/Article/details/gtalzqnybw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sweek.top/Article/details/gteftafwos.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gtlmxdvtvc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtfflwlglt.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtaonmfdii.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gtwqivzmwp.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtxiiamttz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtdjuhcmhz.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gtjqkdonmv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtggpaxxcd.html

[Q60] 取上一行 / 下一行
来源：http://dali.yvedp.cn/Article/details/gtbmthilss.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtbadvvqos.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtagarrlab.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtchrdgglz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtlfjrocms.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtnbnfjbxt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtjhyvtjwo.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcczltmj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtkiqlqydl.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtsbaurajo.html

COMMIT;
来源：http://dali.tianlin.xyz/Article/details/gtpvkydtne.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtgqxumbsa.html

ROLLBACK;
来源：http://dali.guannengcc.top/Article/details/gtdsvzkgcp.html

[Q66] 行锁查询
来源：http://dali.mhx1999.top/Article/details/gtukyozxvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtathogtjf.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtireqnrgx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtlyptunmb.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtnhzbacjj.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtihnkqioa.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtatxqmmjp.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtsyxbqgtl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nwbrower.top/Article/details/gtgfhlsgju.html

[Q70] 更新统计信息
来源：http://dali.bjfxy.top/Article/details/gtglazqrwi.html


<!-- 参考信息 -->