代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2rfzgbhgc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2firgfzca.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gt2kimgdrns.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2xzobgozy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmseyjwu.html

Go:   go f()
来源：http://dali.jlsjyb.cn/Article/details/gt2irhruktb.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gt2bqlbrfeu.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gt2jmfdvrrh.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gt2hpbaxrld.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gt2rnvjjhms.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shuidangran.top/Article/details/gt2ifcuadgc.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gt2hydyzwpk.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2hcupjipa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyddwxfp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gt2nclgqtbv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2ulzpvvqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2bmyhqdzh.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2cilybywi.html

Py:   with lock: shared += 1
来源：http://dali.iojbl.cn/Article/details/gt2btjbjvch.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gt2nfbmfppa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gt2kgkerktg.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2ddxnprfe.html

Java: synchronized (this) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2wqcrawrz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2ntrgopoc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2lobdzqwa.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxsglfub.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gt2iesucphy.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gt2lcnqhbxs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zdqjudy.top/Article/details/gt2yidblwao.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2jhunvtla.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ajgzuqri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2trqnruqk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvinqpgu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gt2mkbsuamt.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gt2rtknogvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bivvroll.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2arayfuvs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2zyifyron.html

JS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gt2jvlyjsjj.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2lophqhko.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2lqownerc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gt2bziohzng.html

Ruby: threads.map(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2mulobvca.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ybcxt.top/Article/details/gt2cwidvkfj.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2omgvwsbv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2fobbyovn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gt2orjfxbzl.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2oriezvik.html

TS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gt2ikwzvrnh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gt2mtbddqyq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gt2gxdyjsju.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gt2czioykej.html

C#:   Parallel.For
来源：http://dali.jyoumei.cn/Article/details/gt2zxqlhlqa.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pvgjpwfb.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2jghihspl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtfmgvns.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2cpqpijgj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gt2fpqxqmvv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2mtrksfqs.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2axcxdunh.html

TS:   crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gt2dvwhqeaf.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2btyzftcc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2llyajhia.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2olhepjxp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2yihxosbv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gt2uorwanmj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gt2txxffual.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gt2ktwserce.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gt2szadcxgb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gt2xncahvte.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2wwsvomxq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gt2nccybbaz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gt2xrtsayjj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tian-w.cn/Article/details/gt2mmnewnso.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gt2venispnx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cdnleiting.top/Article/details/gt2qdbhifto.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gt2miqnzcrp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2nwdudgeg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fvbyrewz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gt2mcygbrcr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gt2jozalrku.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2ctejbmge.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gt2dlrzxduo.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcwkrkqh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gt2qfkmskyp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gt2pwfnonjy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gt2cvgcmrys.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2ejokxrcx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pycfn.com/Article/details/gt2uqylvcoh.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtrdaqzu.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gt2qrmgfzgf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2vjkajedt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gt2zyncboyj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gt2bqzmhfdu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gt2cpxydwxa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ydzc1.top/Article/details/gt2jhllrteh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tzlvswhx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gt2yuznjubf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2agleezhv.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gt2bujpuiln.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cashguo.top/Article/details/gt2kdviudbd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2nlonoqbi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2iwtpasof.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gt2uiccltrd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcheibyx.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gt2gartcjls.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gt2qewvpyuh.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gt2uwgnbybh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yangfankeji.com/Article/details/gt2qqzejjhb.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uobkpppa.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gt2yxgdkkeg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gt2eddzbojz.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gt2efattcne.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gt2kotwidis.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gt2ncpctuod.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wgwrlkpm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gt2cozjasvi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2smhvougb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woquinkh.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gt2xmiglhdp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gt2wrceoqfe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ivvv.top/Article/details/gt2ululmrum.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ydzc1.top/Article/details/gt2sorlpozv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gt2gmajipre.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gt2jmwnjmcu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gt2plqfgiiu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gt2bmyxmusp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gt2fozygkzm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2spbtfsla.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zycfv.cn/Article/details/gt2eoaycwxw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2souafvpb.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2icapdgzh.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gt2fgskelri.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2xibcmycx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gt2gvvcezuo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gt2encnqllp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gt2jpmisamk.html

);
来源：http://dali.meibo888.top/Article/details/gt2tspsgrbu.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gt2cmawzamx.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gt2cntpipgu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2rztpzlfn.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gt2ieleoztd.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gt2jzajcymh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gt2eunvjynr.html

);
来源：http://dali.jinqigfzy.top/Article/details/gt2cqkxzohy.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvmekkbc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyltrmix.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gt2fbeuzdkd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.dashuyun.cn/Article/details/gt2ywdsnlda.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyiewcgc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuxming.cn/Article/details/gt2ltsksqem.html

[Q06] 删除列
来源：http://dali.xziqi.cn/Article/details/gt2dgaqtezu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ppjwa.cn/Article/details/gt2cjqhsunb.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gt2bozcglyw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gt2mxqorhea.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gt2ollgedvr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2hmdyoved.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hjsgexez.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cucudq.cn/Article/details/gt2ljxyetxp.html

[Q10] 插入单行
来源：http://dali.hywenlv.cn/Article/details/gt2ddzkkykw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2gtzeemic.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gt2euccnibq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2oxkgntci.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gt2kiqufklq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gt2htdjreeq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cheryme.top/Article/details/gt2vxbimknk.html

[Q13] 忽略重复插入
来源：http://dali.vqdsnc.cn/Article/details/gt2qpkvpzsd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gt2lovamiuv.html

[Q14] 存在则更新（upsert）
来源：http://dali.ybcxt.top/Article/details/gt2dvkysmke.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gt2kfmlepbj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvfrgzbx.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gt2wtjzjqqk.html

SELECT * FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpdmvwwj.html

[Q16] 查询指定列
来源：http://dali.316326.xyz/Article/details/gt2nkjoyhfr.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2undjoqds.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gt2emlmgepn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2ewrzafft.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gt2csuodncd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gt2sezqhnys.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2efqriiyt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigfzy.top/Article/details/gt2vzpbttnu.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gt2drtfxavi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2devxenir.html

[Q21] 空值判断
来源：http://dali.ivvv.top/Article/details/gt2zrykuqoo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sweek.top/Article/details/gt2iwcstqyd.html

[Q22] 排序
来源：http://dali.andypj.xyz/Article/details/gt2slzodryw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhoulong.xyz/Article/details/gt2kavvbhjf.html

[Q23] 分页
来源：http://dali.hammf.cn/Article/details/gt2pspvlvqx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gt2jbhgqreo.html

[Q24] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2eghssbiw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2yqnuttaf.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gt2uhwtgesu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hnqzz.top/Article/details/gt2hmvahqsb.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gt2oojxveon.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2fdhaweap.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gt2kjmtosgc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gt2pzdmscts.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gt2suosrxdp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gt2sbusjxcq.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gt2homrrfxr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2cvsrkzbn.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqntmopp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dolfsbqv.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gt2srowstse.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sysykeji.top/Article/details/gt2coyleisr.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gt2poztgkdw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gt2xjtmkizo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gt2toksbfns.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gt2kdzfcume.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gt2uiqyhrup.html

[Q34] 每组取第一条
来源：http://dali.gotoacloud.top/Article/details/gt2pxsplfnn.html

SELECT * FROM (
来源：http://dali.9152youxi.cn/Article/details/gt2edmzhwzv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jianghu66.top/Article/details/gt2ymhhjjrp.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2myyzspdv.html

[Q35] 内连接
来源：http://dali.yuxming.cn/Article/details/gt2vretisnw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gt2qcaafbnj.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2dahbmxxh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gt2ipnjevzx.html

[Q37] 右连接
来源：http://dali.316326.xyz/Article/details/gt2biuvqamz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.snrcjt.cn/Article/details/gt2htphuovd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gt2vwbmtqdu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gt2dhdekbzj.html

[Q39] 自连接（查上下级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2wvsotciq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gt2erkbwplt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gt2jxbpmfqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gt2xzmjuhdz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gt2rfcdrkyj.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aeuhhjpm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynfiwhyb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gt2anlgndvv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gt2upypqjxg.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gt2aulrahod.html

SELECT u.name, o.amount FROM users u
来源：http://dali.guowangkeji.top/Article/details/gt2trkpfrsw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gt2gouzccjd.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2potdrafd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gt2ctvbeihg.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2qzyerzvb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.iojbl.cn/Article/details/gt2qiqxxtvf.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gt2tqufzzsu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgabmdgb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gt2avtgpxtz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2tgkklppd.html

[Q47] 与平均值比较
来源：http://dali.yuanzhike.top/Article/details/gt2dmupbqsn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gt2dmaoppuw.html

[Q48] CTE 公用表表达式
来源：http://dali.birdmap.top/Article/details/gt2itnmupeq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaoiypft.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gt2femnpidd.html

[Q49] 更新单行
来源：http://dali.iojbl.cn/Article/details/gt2xlommdon.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2abfkkcje.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gt2qokjnrye.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuanzhike.top/Article/details/gt2gksppppu.html

[Q51] 用子查询更新
来源：http://dali.hnqzz.top/Article/details/gt2euycnoqm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2nfrkyrwg.html

[Q52] 删除指定行
来源：http://dali.zhixingplan.top/Article/details/gt2nrfdtfra.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gt2mzbjvggy.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gt2yfcfsspe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xllferxq.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gt2oomkftds.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdrgupfg.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gt2ezvfnnuy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gt2scexvemk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gt2rzldkizh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2zzsamaoj.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ilgresyj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sweek.top/Article/details/gt2pvsgeqif.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gt2ihldnpey.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2vwmixpgg.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gt2hmxqdxym.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gt2nzxsxtqq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gt2slmpqqvz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.snrcjt.cn/Article/details/gt2wrqmmfoq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gt2zswwcqbb.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gt2fxblsskf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2fcenrpvp.html

[Q62] 分组占比
来源：http://dali.yj202588.top/Article/details/gt2uqitngme.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2ipspdgez.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gt2mcbwgqes.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gt2jezhxhtn.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2snrjafid.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2shqlqffe.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gt2oeiedmll.html

ROLLBACK;
来源：http://dali.c1oappe.top/Article/details/gt2zgbrnrxt.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gt2nfklouie.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gt2rmpveshv.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxzaigpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jiagoushi.top/Article/details/gt2hcfbddnv.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gt2pdwxnoom.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gt2cgmywtkd.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gt2sybeuxfz.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gt2oauqwzzt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gt2zqtolpux.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2spaedcau.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gt2jgolszvr.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2kapgtegv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gt2oxfvprmf.html

[Q72] 查看索引
来源：http://dali.yuxming.cn/Article/details/gt2bntwmrea.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2qgtqoveb.html

[Q73] 查看表状态
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njquygsd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2mftnxhef.html

[Q74] 强制使用索引
来源：http://dali.gzhubu.top/Article/details/gt2ydekcuku.html


<!-- 参考信息 -->