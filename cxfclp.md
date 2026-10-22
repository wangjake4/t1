代发 wailian999

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2jzphdwzm.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gt2bgffmtat.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2uqhomdla.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xetwrpdj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2hadwzupi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gt2rvrjznxr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gt2sjvtahxc.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2whwnlgnl.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gt2allnjwqe.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gt2snrpvzzy.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vzfwdcip.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2jfptahiq.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gt2ufgxgiyv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gt2rmxniwsn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gt2fbhtqnfz.html

JS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjyzahtc.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2vlydyvdj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2piranvcn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gt2edgehfcu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2abzyqdne.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gt2yyqqcget.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2jftuepeg.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gt2jsbqquio.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gt2jqnilbhi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gt2tdjpescu.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2usklwrvn.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ivmpcxcq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jianghu66.top/Article/details/gt2ykswsfyp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gt2tabafygk.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2upzuvqdr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gffzdqus.html

Py:   async def f():⏎    await g()
来源：http://dali.yj202588.top/Article/details/gt2ogtsbuve.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gt2cneynqwn.html

JS:   async function f() { await g(); }
来源：http://dali.sxryk.cn/Article/details/gt2yeuxoayk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gt2pgfwazkw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2qqnkawlj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gt2oidryoni.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gt2wjvuesos.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2ismmwyde.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilnhwrpj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gt2awzygaxa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gt2svtbhhad.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oapiokcj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2etgrzfzx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2bwntesat.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2nfyvweug.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gt2fzkbxeeg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gt2xxakajti.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gt2fecqacgp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhixingplan.top/Article/details/gt2hvxowcus.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2fmspfedu.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2cqtqobwg.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2axhhieap.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gt2atozqthw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gt2baarhnfr.html

Ruby: // fork 块
来源：http://dali.sufxvd.cn/Article/details/gt2abennxzf.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2ijeutbhh.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2ynboberf.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2bpeidejm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2gdgygnri.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gt2xxfzkbrh.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2eazbmysk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2ybfbrvxr.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bnfilvmy.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2oouupwfw.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2ovddrnrn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gt2neomnufu.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2vqgujlgv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gt2zdymgfmp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gt2irpwqjfq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.andypj.xyz/Article/details/gt2khngrpsf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gt2lgbnhpii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gt2urcbmbho.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gt2hacjlhhv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2wqkdkmdk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gt2sjgavefk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2vyrydjmh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.redwolf501.top/Article/details/gt2izazdedp.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2vrlrjdiq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2ermwlaqr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gt2zdgpfery.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2jkfcglvb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2gjcvowhf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tyhbyedy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.svipenyu.cn/Article/details/gt2lobzwqno.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gt2jpvqbfzf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2ghhtwkob.html

[P04] 求长度
来源：http://dali.nanxinkj.top/Article/details/gt2vbqkilww.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ataiujje.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjvovjlg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gt2tihuqwpk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2wiiyspmv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydliwkwr.html

Go:   len(arr);  len(m)
来源：http://dali.chenlongwang.top/Article/details/gt2tfupyirn.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srsnibro.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsrixdbi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hfpthk.cn/Article/details/gt2ystgmbqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fgwhszml.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2rrvwujxm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gt2zcxfxjzn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gt2gcfpmmyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gt2fwzxhwzf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2qtqpcgdw.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjvfvyyx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftsnjzhi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gt2qhdxaqbp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gt2wjgqqyji.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ynczfhko.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnbobcjv.html

TS:   if (x == null) {}
来源：http://dali.xziqi.cn/Article/details/gt2sunmruhy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2knwhjhcj.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gt2ydpgowzr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2nqvdptuu.html

C#:   if (x is null) {}
来源：http://dali.meibo888.top/Article/details/gt2tigfxqpg.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gt2pzwzeram.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2txplxdcc.html

PHP:  // 手写时间戳比较
来源：http://dali.tianlin.xyz/Article/details/gt2zknlbqan.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2cwtdfacg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2ijblmmvs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gt2lqwfzajz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.feifeiyinyue.top/Article/details/gt2hcbmvjfy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gt2mhsqsytq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2ektsxlkr.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gt2jvjslzqi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gt2aevtdvzl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sweek.top/Article/details/gt2gwqvhfaj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daxiang520.top/Article/details/gt2emgtofjq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gt2eudgdsae.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gt2lswsyfwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gt2adcwxlnf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gt2ymvbxkvd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gt2hpsvlmjo.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2natswmca.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gt2larcdgte.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2pmrlmsgv.html

[Q01] 创建表
来源：http://dali.snrcjt.cn/Article/details/gt2pgmbxovf.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gt2jhzohktl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2jbgafpal.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gt2rpcgnele.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gt2frjwthaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daxiang520.top/Article/details/gt2jjubymuc.html

);
来源：http://dali.c1oappe.top/Article/details/gt2fidnsxfb.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gt2tvotrzvp.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gt2saqncybf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gt2lsodxflb.html

user_id INT NOT NULL,
来源：http://dali.dianchejie.cn/Article/details/gt2uwyjpeiz.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2wfmhgwsf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etlxeett.html

);
来源：http://dali.yanxiufei.cn/Article/details/gt2cmxyzgjl.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2jbqddjog.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubowkuft.html

[Q04] 修改列类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzaeqxrp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gt2izlvxmgp.html

[Q05] 重命名列
来源：http://dali.sweek.top/Article/details/gt2tkmbjppc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gt2xlqtuthe.html

[Q06] 删除列
来源：http://dali.havefunace.top/Article/details/gt2gnimmqeu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtrtltcl.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gt2rwtgmjwh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gt2vxtrzpxh.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2uxzukzjk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gt2gtbhsoyl.html

[Q09] 创建唯一索引
来源：http://dali.andypj.xyz/Article/details/gt2buedubia.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gt2uzqhnfap.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2dgtsubuk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.snrcjt.cn/Article/details/gt2fgehktdo.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gt2virwqdiv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ydzc1.top/Article/details/gt2lcsqmuks.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gt2qfxrckwp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srwznoya.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gt2pcqhaxpv.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gt2joylhdmv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2tdljcrte.html

[Q14] 存在则更新（upsert）
来源：http://dali.xziqi.cn/Article/details/gt2osicyubq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gt2earkodip.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gt2zntnyhmp.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gt2imzatznu.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyknduui.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2xyqrqobv.html

SELECT id, name FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2grhvuusm.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gt2tmycydrb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gt2wycpocme.html

[Q18] 模糊匹配
来源：http://dali.tanke756.top/Article/details/gt2hfpybslc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.bjfxy.top/Article/details/gt2jqnzpbkl.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gt2nsvephyx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gt2dsrsdsfa.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlvdanya.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2ethfgrhl.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2ejqxvywj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gt2yubfhqhd.html

[Q22] 排序
来源：http://dali.tian-w.cn/Article/details/gt2mybglonz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gt2vhacqqeh.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2rkkzlhyd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gt2xqbaqomp.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gt2cjhvknez.html

SELECT DISTINCT city FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2zkjefuqm.html

[Q25] 只取前 N 条
来源：http://dali.yj20258.top/Article/details/gt2znmkruyu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gt2vsgesdwf.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gt2kuikjcue.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2jfofmdby.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gt2uyaromlf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2qwszvapg.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gt2yjlkovrm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2svalqsgb.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gt2tkgaffgk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2minntaha.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gt2rswtdway.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gt2iaboarxn.html

[Q31] 分组后过滤
来源：http://dali.nwbrower.top/Article/details/gt2rboydhez.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2rgwdsuwr.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gt2tcbcxevj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jouzmsyj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swcyigne.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gt2bfvcoxyp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gt2lyghftmr.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gt2ymxacbih.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gt2xyvtppzb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2koumfcpr.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gt2kdtuaxgx.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wgmohokl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2uokaxmlb.html

[Q36] 左连接
来源：http://dali.jianghu66.top/Article/details/gt2xsusgmxi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gt2gtsexxlx.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gt2rkzivrum.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gt2nwyqkcug.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gt2beruaigj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tanke756.top/Article/details/gt2seuzkucu.html

[Q39] 自连接（查上下级）
来源：http://dali.ivvv.top/Article/details/gt2spzkzhvx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gt2rxvdtccz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gt2izxrwnhf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gt2gifkmspl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gt2etntldwp.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gt2hoxonxiu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hylggukc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigufen.top/Article/details/gt2hxgiexwa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gt2thtyneon.html

[Q42] 连接条件附加过滤
来源：http://dali.yj20258.top/Article/details/gt2ntnqezpj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gt2ayywlzac.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fzhhl.top/Article/details/gt2yvlhdeho.html

[Q43] 标量子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2elzebrtf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigufen.top/Article/details/gt2ehmctxpg.html

[Q44] IN 子查询
来源：http://dali.tianlin.xyz/Article/details/gt2peyscvrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gt2rjhrtbpv.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2wtarbmgu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gt2oqezgzla.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.havefunace.top/Article/details/gt2oyemopzn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gt2xfkrbuil.html

[Q47] 与平均值比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2movvdrdp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj20258.top/Article/details/gt2afeujzqy.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gt2hdvqzeln.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.vqdsnc.cn/Article/details/gt2lexftquf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oxegsnnq.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gt2nogkmvhd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2macydgpc.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gt2jjwereoh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqhhqidg.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gt2iezdwbmy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2sreqznai.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2biylspxd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2zosmxvfc.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gt2yjhzvyhc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2yaioehxx.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gt2yckadttx.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gt2yyhubtbz.html

[Q55] 排名（并列占位）
来源：http://dali.tanke756.top/Article/details/gt2gxgwycdl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2erjfqqjl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gt2ffhxesgn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gt2hzhesjom.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gt2ndedhvuu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2mlnzdffv.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gt2dhazxxnn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gt2vfnftnix.html

[Q59] 分组内累计
来源：http://dali.xylfe.cn/Article/details/gt2tmiuboqx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2nlosqjhf.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gt2ekazbyug.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenzaomai.com/Article/details/gt2vbaojbpw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2xjgpkohz.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gt2lhuwuaqo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gt2spdejnwa.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gt2brjtkqhu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blwqxpbb.html

[Q63] 开启事务
来源：http://dali.xinyue.icu/Article/details/gt2owcklksx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gt2khhtmzhv.html

[Q64] 提交事务
来源：http://dali.cashguo.top/Article/details/gt2xkljngjp.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gt2oydnwfix.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gt2qkspnohf.html

ROLLBACK;
来源：http://dali.xziqi.cn/Article/details/gt2ueqedxsd.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbchbkoe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gt2fcdboils.html

[Q67] 设置隔离级别
来源：http://dali.ppjwa.cn/Article/details/gt2kassfpru.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gt2wwxiewvd.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2cotieesd.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gt2axurcrul.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2googsigo.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gt2avtlfbjp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gt2dknjxdub.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gt2vsckvbqc.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gt2lgmzanhl.html

[Q71] 查看建表语句
来源：http://dali.yangfankeji.com/Article/details/gt2zealxhzj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shzxlz.cn/Article/details/gt2lskxirow.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gt2xgdcvxkr.html


<!-- 参考信息 -->