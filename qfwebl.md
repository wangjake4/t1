代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtdatbbzlh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtpfoqvjky.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtoeafkzka.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtrbkishyy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtehrdxike.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtgxfnpwxt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteotfrmoc.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gtglmxljbk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtgklljsct.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtznussgbz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtbfpckebq.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtohgvahtk.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtyufeakcd.html

Go:   go f()
来源：http://dali.ehwqpu.com/Article/details/gtitlfwncg.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gtydcicyru.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gttabsqpkz.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtstutopja.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gtttilfijb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gttjtsnhtp.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtakjwgnfw.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfyrneqj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtjnslyhka.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtvqfjwqdd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.haohaochexian.top/Article/details/gtpwuhgqyr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtibrgencp.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtywhekscr.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gtbeoppzvr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtwzwaifdj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtpfjxhmyk.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gttgkbpvau.html

Java: synchronized (this) { shared++; }
来源：http://dali.yongpay.top/Article/details/gtwqkrlcst.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gtlelzipfy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtwxksfyln.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtsqbvrpca.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gtvwuiyswg.html

Py:   async def f():⏎    await g()
来源：http://dali.gotoacloud.top/Article/details/gtlbxkolnh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtoyigxjhp.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtfoxfufhw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpufdyrah.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtykzvvevv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gtnydrvahs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gtipgvtvca.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gttbaiabux.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtynhzlyab.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtdrruhupg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gturgimbrw.html

JS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtnydtbzwx.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtbfvstipi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gtnvrzbuuv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlctosval.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtdsqgnfvx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gtpjicdhlk.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gtrgtkunwp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtxdwfvlfo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtyrposdxs.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtqfnxmjxu.html

TS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gttexmbcbf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtzmsmlkiw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtpibcfryb.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtlxvvuvse.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtlkxmcohl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqeeuepyd.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtlziurvgn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtosrytpxk.html

[P01] 生成 UUID
来源：http://dali.meibo888.top/Article/details/gtbdktmyiz.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtilzsbpiv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadyivaaj.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtdcnzhfvt.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtlryjgscs.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtsgvxlsza.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtbqoyypva.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtahtrbjof.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gttkhmqfrj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.bjfxy.top/Article/details/gtuutseehn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtcysnbfln.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtajfsuask.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daria6918.cn/Article/details/gtcwimckry.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtmfmbylvh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtqnkuuild.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtdyqlldri.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieybxuen.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gtnzpragsc.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppgcazeh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtaocfwwzl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gtkvhiripb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtgqeapbnx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtcptmdbuj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtoliqiplh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtsjksvksp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtjyhqklmw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtesqfhqfq.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtjsaqlfcq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shuidangran.top/Article/details/gtpdnrzzwa.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtkpsztpiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtopaakwyf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtytthvktz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpjieahk.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gtewfopota.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtltayqjmt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.havefunace.top/Article/details/gtlmwrwfxd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tanke756.top/Article/details/gtclvmhsvz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gtidmzvyuk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtydjdwhwd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtcstxkyjw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtmtipmxbg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtsbxkrslm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtajjhgtot.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtjwpmfehf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtsvffrtzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gthfdvgigj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtwfxelhqs.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtgindocay.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtpdhwoypy.html

TS:   if (x == null) {}
来源：http://dali.bjfxy.top/Article/details/gtkzmfsmes.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigfzy.top/Article/details/gtredwukks.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtziekcfsq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtbecmejmu.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtsmvlculv.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtwlwyykwi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtdbbsefjx.html

PHP:  // 手写时间戳比较
来源：http://dali.cashguo.top/Article/details/gtoqoppyto.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtbtuesqpq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtciiejwcv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtgktnaoip.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.c1oappe.top/Article/details/gtmwsijuct.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtcnmkhjhv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hammf.cn/Article/details/gtuuhfdbce.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtzyhymcek.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gtdbvhxmbw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtgaygozit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtyheringd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtlilazykg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.316326.xyz/Article/details/gtxlddkajj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gttplumuyf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtckvhiqpr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gtfcvsdjgq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtidbncrrp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtjuvxiice.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfakmmphf.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gtvzvrwkvx.html

CREATE TABLE users (
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhvriqvr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtcetiqxdd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtbbkkrfpn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gttxhayuga.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtoilgicle.html

);
来源：http://dali.xylfe.cn/Article/details/gtyidtpaxh.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtfbwqrrsc.html

CREATE TABLE orders (
来源：http://dali.xuanzx.com/Article/details/gtxonpczmb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtarnwkqbe.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtyurfdhed.html

amount DECIMAL(10, 2),
来源：http://dali.wangshuangyany.cn/Article/details/gtnkcqxevq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtcmyuhuwu.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdaeqzhvu.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtznijmbrt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtedbvmugv.html

[Q04] 修改列类型
来源：http://dali.daxiang520.top/Article/details/gtikbrguuk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtnmyihpvp.html

[Q05] 重命名列
来源：http://dali.gaohongyu789.top/Article/details/gtuobpztzo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gtellfgmrb.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gtmxveawti.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gzhubu.top/Article/details/gtouqcwmmm.html

[Q07] 删除表
来源：http://dali.redwolf501.top/Article/details/gtpbbfjnqg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtwzohgdby.html

[Q08] 创建普通索引
来源：http://dali.316326.xyz/Article/details/gtkrxrudqw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtysfkuihz.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtpfdmmsll.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtarhholcx.html

[Q10] 插入单行
来源：http://dali.feifeiyinyue.top/Article/details/gtpjrqvrgz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gtyricmlgp.html

[Q11] 一次插入多行
来源：http://dali.yuxming.cn/Article/details/gtscoxsqhd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.meibo888.top/Article/details/gtzexbjnhq.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtqkqylvxb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.chenzaomai.com/Article/details/gtxointgzq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtlkypojds.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtawiljbat.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sysykeji.top/Article/details/gtkzgzolda.html

[Q14] 存在则更新（upsert）
来源：http://dali.cqqwz.cn/Article/details/gtwysmrwqe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.snrcjt.cn/Article/details/gtwzvwbzzo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ppjwa.cn/Article/details/gtoisexhpm.html

[Q15] 查询全部
来源：http://dali.jiagoushi.top/Article/details/gtcusfyamx.html

SELECT * FROM users;
来源：http://dali.fzhhl.top/Article/details/gtgfeychtd.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gtkrwxnrkc.html

SELECT id, name FROM users;
来源：http://dali.pycfn.com/Article/details/gtwaarldux.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtecacyyjz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtfzehlwft.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gthnmjamzx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhixingplan.top/Article/details/gtyzetagbl.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gttizuwowf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gthmdmpqco.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtoyghlate.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnqzz.top/Article/details/gtojhwtujn.html

[Q21] 空值判断
来源：http://dali.jiagoushi.top/Article/details/gtqsuhifqu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ybcxt.top/Article/details/gtnatxragc.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtfkpwxaaj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gtcpzhamgt.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtnllvafcy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtsxzjfssk.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gtjhusgjrm.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuifejadq.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtvruyuicw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtvsdhqlwr.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtridzkjor.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtnkpgowma.html

[Q27] 条件计数
来源：http://dali.mhx1999.top/Article/details/gtlllvpqxt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttxfvsjkb.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtgxknogqb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtufbtebmv.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gttgfzybcs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqskzctyc.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtnassaarr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtxujnuaqd.html

[Q31] 分组后过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzehkurvf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gtxmsmwlmp.html

[Q32] 分组拼接字符串
来源：http://dali.wangdashe.top/Article/details/gtmirtmlez.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtpgbecrhj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gtznoiunzn.html

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtqphaxywt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtthpmmoul.html

[Q34] 每组取第一条
来源：http://dali.wangdashe.top/Article/details/gtpsqtygdg.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtrpolnfac.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.bjfxy.top/Article/details/gtssshgjvy.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviswsknv.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gttghfqpkv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtybsmorlj.html

[Q36] 左连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloxmmahk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gthjjvsklv.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtunowzckb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gtwvgmjtpm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmmeskjv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtfnktkual.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtaqoaeaji.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnmzlurvr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtdafzggyk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gtotexulcf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gtnsrtztyw.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtvqwodkfa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtkzjptxjw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzezcote.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtofdgzlxo.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtytknriwz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtjdtxwfwc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gtqpbjixbo.html

[Q43] 标量子查询
来源：http://dali.dashuyun.cn/Article/details/gtrkpiupwy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hysaishi.cn/Article/details/gtbnnofiia.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gthcanbjkv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhixingplan.top/Article/details/gterngfegh.html

[Q45] EXISTS 判断存在
来源：http://dali.sysykeji.top/Article/details/gtvirspecs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gthgrjkquv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtljuyedat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gteujbhiqi.html

[Q47] 与平均值比较
来源：http://dali.tanke756.top/Article/details/gtqgolcqxf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtzibwmoln.html

[Q48] CTE 公用表表达式
来源：http://dali.aizwys.cn/Article/details/gtdjzlsmuc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gtcuhllzgt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtjsmyliej.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gtgxtwquyp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqbnbold.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtxdzaqout.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtkxlmhkhy.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtqrzbmxzg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.0kj1m.cn/Article/details/gtqjsjbttm.html

[Q52] 删除指定行
来源：http://dali.hysaishi.cn/Article/details/gtsztkeynr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtotxfqytv.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gtnfxmeiti.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.smart0.xyz/Article/details/gtcdflqcvm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtfvitvdub.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtyqamrjhl.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gttxdnmoxj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pengpengdd.cyou/Article/details/gtzecngpxv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gtklxrhrcc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtziabkmqm.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gtbtypicjt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtegursoyl.html

[Q58] 累计求和
来源：http://dali.andypj.xyz/Article/details/gtwxcnvshl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtnxjqsowj.html

[Q59] 分组内累计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagjfvgpe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtkwkhlpnw.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtjrzbsrww.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtssnvexsv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.andypj.xyz/Article/details/gthemgzxje.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtyfkomyrh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtvtbedutp.html

[Q62] 分组占比
来源：http://dali.redwolf501.top/Article/details/gtlixdhjcj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtczlvyeah.html

[Q63] 开启事务
来源：http://dali.xuetiantiany.cn/Article/details/gtfgaucktt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtabpkmktg.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtmoaljxls.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtuehfjdxn.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gtowgmyndl.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gturhrumbw.html

[Q66] 行锁查询
来源：http://dali.cheryme.top/Article/details/gtzbeoujgs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtnjjtlihf.html

[Q67] 设置隔离级别
来源：http://dali.nanxuanxn.top/Article/details/gtnjnzquvb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gtpapuolqm.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtptkvxapp.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtkawzpbby.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gthtmezmlx.html

[Q69] 查看执行计划
来源：http://dali.hywenlv.cn/Article/details/gtoikivfcd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gtnmwnleiq.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtnklpzhzf.html


<!-- 参考信息 -->