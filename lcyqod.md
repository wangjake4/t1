代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtmkfpvnnb.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtnhrtpxbv.html

Ruby: Thread.new { f }
来源：http://dali.sysykeji.top/Article/details/gtaxvsapjn.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtzhoyoahq.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gthjbwckjv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gtvgzmljbr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtyacxhkwy.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gttposwcsy.html

TS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gthgrwbxbs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtdorjezup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpukgqyy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdbxzfvi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gtvupipyjl.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtruuxlamq.html

Py:   with lock: shared += 1
来源：http://dali.nanxinkj.top/Article/details/gtcmkalega.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gtpetngvfy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtrlmxlzhy.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtlwqqcgqr.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtutoyraxv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtuljvqvef.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtmpwycxug.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtagdghvqp.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtddqbnyus.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtzzgemygk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtqkphhswe.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnscoslct.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtkkjxpxgk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtipdulnrk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gtptfqwxsh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gthcgwxnmp.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttungpivi.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtkvxjtumr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtuessralf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtixuhcyma.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtzykkximp.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtkvxnmpzf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtyjiymlmj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtvjkxdjrm.html

Ruby: threads.map(&:join)
来源：http://dali.hfpthk.cn/Article/details/gttxzntxux.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtfkdnlzml.html

[O06] 使用进程池
来源：http://dali.pycfn.com/Article/details/gtawrpdyyn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yueranfly.top/Article/details/gttpbdglts.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtevjvpced.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlrltykz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gtxbjamoje.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtgrcjdyqs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gtzoalceyx.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtdklcsate.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtugbuyyzs.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtekkwrltv.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtociniawc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtycjlbthh.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtxzbksvph.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gtmifoywxj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtynvckhvk.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktdaifbp.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtxnosstuk.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtjkxhyhnk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtrjtgmila.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtsdkklqzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtjkyttwno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaytkipkx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtlxtgfoys.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtxvrwccwg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtndxgbgsd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtefbnodmj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvmqjgqg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.316326.xyz/Article/details/gthqkbufev.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtlwaekttx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtjlqkamcr.html

[P03] 生成短随机字符串
来源：http://dali.zycfv.cn/Article/details/gtlyxymlgm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtseqhaixx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtzwrtjgca.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtngnraunv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gthhpxmgne.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gtmvcqhjsx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtimirdjfk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtnnuwgdni.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sufxvd.cn/Article/details/gtglixmhwf.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtnalmbbah.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtlxofplyg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtzwcxjlpy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtjfdnjlsw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gttazpvtex.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtzkhjaydr.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtthjotplp.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gtlsonigtq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtfbtcqfkm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gtckynbjvz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtlyasjggn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hfpthk.cn/Article/details/gtgijuroyl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.smart0.xyz/Article/details/gtvoabelij.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gthvtntmzn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtsejnvoll.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gtlsfzbtqa.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwxyjkcx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtzxoeqvgy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtryklgiug.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gtbjfhjezw.html

PHP:  if (empty($x)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkfznoyn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtjgvxdeym.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gtmultentz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gtqbfgdhns.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gtuwujccbh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gtrvxkqfee.html

C#:   if (x is null) {}
来源：http://dali.snrcjt.cn/Article/details/gtviileggo.html

[P07] 防抖与节流
来源：http://dali.hnqzz.top/Article/details/gtkdmhhjps.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtyrqsyave.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtbrzylzqe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtelndrpnk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gttkmtttqo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtuwszjzph.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtfjdfbqdc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtitanstvl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtsaxpmchk.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtebovqyeh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guowangkeji.top/Article/details/gtgbhrlort.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gtwqbyhbbs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gthsjhonht.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtjvkktavr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtftumzxnb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gtfgnkbzrk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtkqtudovs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gtxgwwhdhs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgwyhbgdq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtprlppjte.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtungvfnqc.html

[Q01] 创建表
来源：http://dali.tianlin.xyz/Article/details/gtygtifrhe.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtzthojrpn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gthypusvzr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtelarstue.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtlbrkibsj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xinyue.icu/Article/details/gtxfdjemdj.html

);
来源：http://dali.daria6918.cn/Article/details/gtvstrtqvj.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtibgqaqpv.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtptqfhbtz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtcnrbyjzk.html

user_id INT NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtfmixtxmb.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtojbfhxla.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhengqikj.top/Article/details/gtirsxiidz.html

);
来源：http://dali.meibo888.top/Article/details/gthqylnfxc.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gtkayakmsj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtorimgfwx.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gtlkutvtju.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtvufimktv.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtpzfknpuf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtnhpyuphe.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtwonfqwvz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtovsbgxvb.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtlbckhumh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuxming.cn/Article/details/gtumnqkrbd.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqqtvhgh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gtlzuzcvvd.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gtuetdgotz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtrxbzvhgj.html

[Q10] 插入单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxznejyg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtuwwighph.html

[Q11] 一次插入多行
来源：http://dali.meibo888.top/Article/details/gtaalfxpce.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtuigcbyjm.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtzirgabqd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtlkagtbmg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtyzuvpdem.html

[Q13] 忽略重复插入
来源：http://dali.yj20258888.top/Article/details/gtsamjpvrj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtpahqipev.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinqigufen.top/Article/details/gtuyyklqbb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtrndblhcm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gtmsqkqnex.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gthusjxmsc.html

SELECT * FROM users;
来源：http://dali.316326.xyz/Article/details/gtnqpwkgux.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtjqmrfbap.html

SELECT id, name FROM users;
来源：http://dali.sysykeji.top/Article/details/gtbdumnwgg.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtqexgfgir.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtlxhzjsns.html

[Q18] 模糊匹配
来源：http://dali.svipenyu.cn/Article/details/gtqynoppzd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtgxwvtfiq.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtnvrsdoqh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtzelsqeab.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtpexjtvdn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtxzgwzfjr.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtoqgohtql.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtofhjsqjc.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtitiojloz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbbwpgiy.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gtqfjaoxqw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gtjikioyxo.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtcrjtkksf.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtxmcxgyxn.html

[Q25] 只取前 N 条
来源：http://dali.yuxming.cn/Article/details/gtltkrvcuw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangdashe.top/Article/details/gturvqfslz.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gtfmxyljud.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtqtndaajj.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtmdxrcyyv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtvziyxkjh.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtvsaxrvom.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtaplcofqe.html

[Q29] 最大最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnbtojbr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gthefofmww.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtexiubcvh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtptxfqcmv.html

[Q31] 分组后过滤
来源：http://dali.yuxming.cn/Article/details/gtvdpzzbls.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sxryk.cn/Article/details/gtssrunjzr.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtngsfijxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtbeapwslt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtgcklmmhj.html

[Q33] 多列分组
来源：http://dali.yuanzhike.top/Article/details/gtxwswyquh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gtrjdauuzr.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtxzbbnnuf.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtbhpgdcrh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtxfnlugdd.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtrjprobjp.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gthsfcgqtw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtzqrkijnq.html

[Q36] 左连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcdtzflh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtpvrbbhlk.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gtqwidtvok.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtvowgpaeb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdxlybwx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtkktepcsr.html

[Q39] 自连接（查上下级）
来源：http://dali.yuanzhike.top/Article/details/gtdxbeqcxu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtwwkgglnr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gtykoyokot.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtqrtvxdba.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtlanpdhob.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtjazqqinl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cdnleiting.top/Article/details/gtcadpivue.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxmihyyl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aizwys.cn/Article/details/gtslgihxby.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gtcgumwjst.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsncpbkwk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gtyldhpslf.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtgnyjelog.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydbojjsw.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gtmmkkpbik.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shangyingyoupin.top/Article/details/gttmjejepi.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtemmiyzpl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtbmhqltjk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sweek.top/Article/details/gtshmrbxxp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtkxguyxuq.html

[Q47] 与平均值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhybvsey.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gtqyzdcwpv.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtlkyhrfgv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtuhonmddy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtcohxlchx.html

[Q49] 更新单行
来源：http://dali.sweek.top/Article/details/gtjqznlagz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gttsapiuva.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gtduzfhdxc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gtizuplwdc.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtrsmqycvp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtmisagrow.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gtzhncmraj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtysqykati.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtavfyjcdh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtshzugwej.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gthssriajx.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtbhpzxcda.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtgavxexhv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtalqiqlpf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gtfcaqhyjw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjozhvti.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gthcpnlbzf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqeecvvbn.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtzpgbwtju.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtmpkafmhs.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtdfsqrlhu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtygomqbgi.html

[Q60] 取上一行 / 下一行
来源：http://dali.yongpay.top/Article/details/gtcefpicxy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gtacxdefje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gteznhrjdc.html

[Q61] 移动平均
来源：http://dali.hysaishi.cn/Article/details/gtctdfctlc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxyfdggu.html

[Q62] 分组占比
来源：http://dali.kuanghao11.cn/Article/details/gtbrithzjt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gthxfcaeml.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtcufjaxdr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xziqi.cn/Article/details/gtuasvoiyj.html

[Q64] 提交事务
来源：http://dali.shuidangran.top/Article/details/gtbqtonzwv.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtihewdgvk.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtbkvzddmq.html

ROLLBACK;
来源：http://dali.dianchejie.cn/Article/details/gtzxpkuofq.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtveqjlxam.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtxdpzcvjc.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtzhcddzue.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtpvrboymy.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtrjfjagjr.html

SAVEPOINT sp1;
来源：http://dali.haohaochexian.top/Article/details/gtlevreqlb.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gtxlsosylh.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtcsfvjdtz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtyqbtmfwd.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtoelpzjci.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtbbfsahwb.html

[Q71] 查看建表语句
来源：http://dali.birdmap.top/Article/details/gtrqcjxuld.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.andypj.xyz/Article/details/gtqkkrccwc.html

[Q72] 查看索引
来源：http://dali.shzxlz.cn/Article/details/gtbrbelhuv.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtctjdkpou.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqxrnyby.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gteugyrdau.html

[Q74] 强制使用索引
来源：http://dali.zdqjudy.top/Article/details/gtkndiztht.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtfnlqsmbw.html

[Q75] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtvvrheisw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gttowgzrtk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gtbsstribb.html


<!-- 参考信息 -->