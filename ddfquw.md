代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pycfn.com/Article/details/gt2gqbkjucr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sxryk.cn/Article/details/gt2eeuccudd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2kgzvpykb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2dnbuefjk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vajfytkc.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gt2gvzrpcec.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2jzrsqcfv.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2ezioggkg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gt2todbpsdz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gt2xzbnvpkn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenlongwang.top/Article/details/gt2rphettqi.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2amaeuobz.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gt2slpzlfri.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2ewkecedr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aresucde.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gt2pimheloi.html

[O02] 使用线程池
来源：http://dali.yj20258888.top/Article/details/gt2iopaqpym.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gt2qcllfcwa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjlzfzfm.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2upiegwpe.html

TS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gt2vigfklqc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tapjgejz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yldqepjl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgcputdg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gt2mdcbjfec.html

[O03] 加锁保护共享数据
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpkwllwh.html

Py:   with lock: shared += 1
来源：http://dali.yonumen.top/Article/details/gt2usvepyem.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gt2hltirkcv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gt2rkyyvgdy.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2kierxacq.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2ngeoxfzm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gt2rdhmvyeg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2srcrxvqx.html

C#:   lock (gate) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2yntjksmy.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2izgvfnmx.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nfksmqbp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gt2lutctghb.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2ipoonxuh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2vwumnhvh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gt2owydfims.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gt2lilnlhvu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gt2gwahrjrp.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gt2jkyqwqjv.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2oxkxyonn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2gwguslzq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2wskkeene.html

JS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2ygqodxwd.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2pmzilcgh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2zgcnxjki.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gt2quorbkwy.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oevkmias.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2trywmzqr.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gt2riirpqrm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2txzsdvcx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gt2ebuvpijb.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2rzgluidm.html

TS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gt2pbvyuboq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2frrnirmt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gt2xtanoujp.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gt2ytrogeof.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gt2vnbutkmk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2rhtslwef.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gt2fcmzujjp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2fgptytsh.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmrqhbhx.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2siohgdpu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gt2norofxrb.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2pwgsqgrx.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2mkussqtn.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gt2uehtqnse.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yueranfly.top/Article/details/gt2rlbtyrev.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gt2bolodsan.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gt2vgmfflyv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gt2dfezsbev.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gt2iwggungl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2uqhxvnve.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gt2fwbpjyjc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gt2iynwcwyv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2pkuiallh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2banfwexb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2ogaspqyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gt2qytdppgl.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2ochizrvs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.kuanghao11.cn/Article/details/gt2kergtjtw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gt2uphohawj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2dxckinhc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2thcpvmrq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gt2nimcmjrf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sufxvd.cn/Article/details/gt2hspydscu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nanedyae.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gt2xnlowkrx.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2fvwwcgsu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gt2lcagwtdt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2lufigynw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2mzdmvczm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2kpczmfrw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gt2vqxocytj.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gt2jbyyibrf.html

Ruby: x.length;  x.size
来源：http://dali.xziqi.cn/Article/details/gt2jfaaoxtk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zycfv.cn/Article/details/gt2bkyxxmbd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gt2deukjzux.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gt2ptgfhbix.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gt2kpyxlzvu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cqqwz.cn/Article/details/gt2vghvnfyn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gt2rhpwzmmk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gt2crlmnrja.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2zastxfxe.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxoqxmer.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gt2rtlaqoxl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2ntjhtxhk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2pubzaeuh.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2lhrryrxf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gt2wainnfve.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqhdnzeo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gt2wjlwpncl.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gt2rwiedthw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gt2rnreipra.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehgwxoes.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gt2zjfsuhsi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gt2ospkccqo.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ppzrmtac.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gt2wfwohyfy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2tozulous.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2pculwgad.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gt2pgoaaepe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gt2nfldkjjw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zdqjudy.top/Article/details/gt2hmyrvbtd.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2maeypfry.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuxming.cn/Article/details/gt2ovofgatm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2rntrlcsp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gt2hhkydhgo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gt2jhfjsiuf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yvedp.cn/Article/details/gt2xpfsqqdl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhiwuduotai.top/Article/details/gt2muuihuaf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ozzommvo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ehwqpu.com/Article/details/gt2artwmywx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2kuzqymla.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gt2sywqhhmh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2swrcstbh.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sahflvhv.html

CREATE TABLE users (
来源：http://dali.daria6918.cn/Article/details/gt2tiphfutt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2dpxbvhtp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gt2zygsfunv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pycfn.com/Article/details/gt2dtswjjlt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gt2lpmdeuys.html

);
来源：http://dali.hfpthk.cn/Article/details/gt2fyanipqc.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gt2cikavmyk.html

CREATE TABLE orders (
来源：http://dali.xinyue.icu/Article/details/gt2cqwsvdup.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gt2ywgyoorc.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2sowwlkxn.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aebsquew.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2jrqpgygh.html

);
来源：http://dali.sweek.top/Article/details/gt2yupprgbv.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2voyojrup.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2kwucwqwk.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gt2wdbmkknn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2kuknkfcx.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gt2ugxafqjt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gt2wfmlmurd.html

[Q06] 删除列
来源：http://dali.chenzaomai.com/Article/details/gt2raiuvkvm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gt2zfxizagv.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gt2pnhphenn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yvedp.cn/Article/details/gt2yhspaorc.html

[Q08] 创建普通索引
来源：http://dali.snrcjt.cn/Article/details/gt2bqxwhuez.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2njbrupoz.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gt2jiusjhns.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2kddhstqv.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2mibzjrkw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yj20258.top/Article/details/gt2rttnliyn.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2xwrsbkww.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gt2tdcudffd.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gt2kuxmoyba.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gt2hofzbisl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yongpay.top/Article/details/gt2lubbpfkz.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gt2xtkhrijr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2nwfeiejf.html

[Q14] 存在则更新（upsert）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlxeocnh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.quarkkingdee.top/Article/details/gt2lxltlkih.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gaohongyu789.top/Article/details/gt2grxrfxbu.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gt2bvvdhndh.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2xnagztri.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2agjmlnrs.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2nvtsvbej.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gt2ntskvzif.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2vubmairs.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gt2hiikxwgv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aibaodan.cn/Article/details/gt2ywomxjel.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gt2pvqzxqao.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gt2uoxfeart.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gt2zgtrtrgu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gt2oxkkvntu.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gt2sfaobdtv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsvdijqj.html

[Q22] 排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpfnlmyq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ydzc1.top/Article/details/gt2fbmrvpoi.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gt2xrxzthlf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gt2obghswuv.html

[Q24] 去重
来源：http://dali.jianghu66.top/Article/details/gt2bmllhmpa.html

SELECT DISTINCT city FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2kocmqmnz.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2pmneymlk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gt2voqpbbgk.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gt2unjujnwv.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2wndlokkq.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gt2gdqvsxgr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2stptulfa.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvmtrcgi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2npjdemkx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqpicze.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2bncdipke.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gt2ytcxraml.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gt2olheqmey.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gt2mseegqdu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gt2obushwoa.html

[Q32] 分组拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2mujylnlp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2xnevafuq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cucudq.cn/Article/details/gt2uzefivku.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gt2nxvhpdfv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gt2rzpigkgx.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gt2fjmbilem.html

SELECT * FROM (
来源：http://dali.svipenyu.cn/Article/details/gt2mufkewob.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gt2qbyqsexg.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2wrmgettt.html

[Q35] 内连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfnzuedt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gt2tlmzkfye.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gt2safnxofw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2tmnrjuuw.html

[Q37] 右连接
来源：http://dali.yj20258888.top/Article/details/gt2oojbtksv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gt2qdphhpjd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ydzc1.top/Article/details/gt2bbujccbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gt2agpvsekh.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gt2ebqibiwg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gt2tahufngp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gt2xykmbbkb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gt2qdexbmjo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jinqigfzy.top/Article/details/gt2xyacjnbr.html

[Q41] 多表连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlypylhu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xziqi.cn/Article/details/gt2iankeeqc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gt2ivlvztnb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmifsblo.html

[Q42] 连接条件附加过滤
来源：http://dali.tanke756.top/Article/details/gt2zwjeomfo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.havefunace.top/Article/details/gt2bzdihqyx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shuidangran.top/Article/details/gt2jsoeyijb.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2jtbivvjn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gt2cxsfokdw.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gt2kloxxlxk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gt2dxepesal.html

[Q45] EXISTS 判断存在
来源：http://dali.ehwqpu.com/Article/details/gt2pqypclik.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pxptnzun.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cywvnuqa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbwhgede.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gt2ldipksyd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gt2sowvvzua.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gt2opziyirk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jiagoushi.top/Article/details/gt2ihvufgme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gt2xqfwgsfy.html

[Q49] 更新单行
来源：http://dali.guannengcc.top/Article/details/gt2ntghgjxk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ievuwcqe.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2xbmpzbpc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj202588.top/Article/details/gt2acjghimp.html

[Q51] 用子查询更新
来源：http://dali.cqqwz.cn/Article/details/gt2gtocadcc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gt2qkomdohw.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gt2sringipv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhongyouzk.top/Article/details/gt2jnybziwk.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gt2xxchexra.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gt2pifmcvys.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2ibwiypgt.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2cxqmnnfu.html

[Q55] 排名（并列占位）
来源：http://dali.redwolf501.top/Article/details/gt2cpamzsxs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gt2ywmzyzjl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yangfankeji.com/Article/details/gt2ysxwwjqb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2pgtelxij.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gt2kvnlibdy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2qhgygial.html

[Q58] 累计求和
来源：http://dali.gotoacloud.top/Article/details/gt2wyyjubji.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umjykops.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gt2xonawrzt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2icimpvux.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gt2reorkuzk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gt2sdwldwjt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gt2mxufqrda.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gt2wxfwxbwm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2paktxzuy.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2uoippglh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2dnlxaqrn.html

[Q63] 开启事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpwizuhd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.quarkkingdee.top/Article/details/gt2avbrqskm.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2oqmfdych.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfvtvgfs.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gt2qbdsbdbw.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ingtpquw.html

[Q66] 行锁查询
来源：http://dali.yanxiufei.cn/Article/details/gt2dalhojhx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gt2oztupglo.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gt2ioikltii.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daxiang520.top/Article/details/gt2tfppoaoz.html

[Q68] 保存点
来源：http://dali.bjfxy.top/Article/details/gt2gwqrkpph.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuuxmoar.html

ROLLBACK TO sp1;
来源：http://dali.iojbl.cn/Article/details/gt2srspnbnn.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gt2qwldgfbp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gt2ytxltwno.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gt2kcehdebn.html


<!-- 参考信息 -->