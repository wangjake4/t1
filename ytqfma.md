代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2hwazblvo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqtjodpy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gt2dufixdoy.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2waoskqtl.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gt2cybkcrcs.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gt2zmmodzgk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhuzzns.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2wbqchzsq.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gt2guffidve.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gt2vtghqaes.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2nnywouxq.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2acfvbmlv.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2eenvnfdp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gt2pgbcgyag.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgfzy.top/Article/details/gt2rlpdgbtu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gt2ojvvictz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gt2wzudpumz.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2ummjajao.html

Py:   with lock: shared += 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2reuilzko.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gt2dbfslzhw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gzhubu.top/Article/details/gt2gxfgpbad.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2cwlkjtak.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gt2nmhgatvp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gt2fizwnnfn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2ufsryuux.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2aazwcimb.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gt2iieovqrs.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gt2ljluddph.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gt2rxmgzmlp.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2zkfimbut.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2juboqyeb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2oajirkmt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gt2yexbuqhs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2dcrihpct.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gt2wxgzxtzv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gt2plbhbczt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ivvv.top/Article/details/gt2xctauehy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2bpmhymuw.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2prkyfhpb.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2wkhxebqu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2hqpdrrcj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jngirlns.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2rufmeupu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gt2zaprcbxl.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gt2bktfghyb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gt2tmgqexxg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gt2ixfsdkvk.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2alljcicr.html

TS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2fhzlzqsl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqkwutmw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gt2fvpwmkpo.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2plzezegg.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gt2jvpgosgw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2fbrjkocv.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gt2vqcmqknr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2rhjnqwhb.html

[P01] 生成 UUID
来源：http://dali.gotoacloud.top/Article/details/gt2jrswxlsq.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gt2mgrioaca.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2zocuuqfi.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2nqalwied.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2oexiuzph.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gt2lcepzgss.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gt2hthbsxnh.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2fbrowbpp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gt2hvrrffnt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtggzpml.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gt2salmtuyx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gogol.net.cn/Article/details/gt2leceufks.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.smart0.xyz/Article/details/gt2ctqmsdzk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhongyouzk.top/Article/details/gt2mtuwbubi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2ucmljdgq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2xixoeiko.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gt2xzcfzlux.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gt2qwfqfmuo.html

[P03] 生成短随机字符串
来源：http://dali.haohaochexian.top/Article/details/gt2mopnhvqw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ehwqpu.com/Article/details/gt2dltdcqgp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2xfxefmpo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gt2pvgmcioq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2gpqqijev.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gt2trpxnjay.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.havefunace.top/Article/details/gt2nbejijad.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gaohongyu789.top/Article/details/gt2dcirtoln.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gqqlmxtl.html

[P04] 求长度
来源：http://dali.zycfv.cn/Article/details/gt2itzciajj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cheryme.top/Article/details/gt2hzeabiwq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2pjkkwmmk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2hcwbmjiu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.316326.xyz/Article/details/gt2nniqjkwk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tguzugzo.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atyuhzwx.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gt2fegvxaso.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tladmzdt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gt2kgnanqbd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gt2hwwgfhpw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2texhefha.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.feifeiyinyue.top/Article/details/gt2baccriwi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2jkmztfjo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gt2xordvjts.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2eucjuvxi.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gt2leqliqic.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ppjwa.cn/Article/details/gt2nekdhfgb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2fdksflmo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gt2nnmevkpv.html

PHP:  if (empty($x)) {}
来源：http://dali.gogol.net.cn/Article/details/gt2bgmsuqxr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gt2wijpkkei.html

TS:   if (x == null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2pinhlran.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gt2zwqvqsas.html

Go:   if x == nil {}
来源：http://dali.tianlin.xyz/Article/details/gt2ridfhpxe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gt2mqvpdzil.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2frdsnizh.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gt2cnfsrcuf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gt2snayppts.html

PHP:  // 手写时间戳比较
来源：http://dali.yj20258888.top/Article/details/gt2xbdrwipj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2neiyzhpk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2ocpfexce.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gt2qzpzuyay.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gt2jljniyzy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2qkvwhahu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtjucewq.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2vbhroxfm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ivvv.top/Article/details/gt2kwbatptd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gt2bidtsffc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gt2hpchvymw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gt2ehvgjjah.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gt2aoaeldkn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2rtqzociw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2rexipihv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gt2qhqeaouu.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2rffpziav.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gt2miwatuzb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2acspdtoh.html

[Q01] 创建表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zezwrpqt.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2rarveiyv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2nmqueivp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2jwveixuc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gt2ocfqgwyu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gt2ggsopqzf.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2wzcjggnd.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gt2oshksait.html

CREATE TABLE orders (
来源：http://dali.jianghu66.top/Article/details/gt2owzdtixn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wnewjpbd.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2dkjbmnog.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udrqpzuy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gt2kychpkzn.html

);
来源：http://dali.ybcxt.top/Article/details/gt2bemgtlsk.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gt2zuytfggh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gt2tqkyifvq.html

[Q04] 修改列类型
来源：http://dali.nanxuanxn.top/Article/details/gt2ehfsowit.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2sohdswcy.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlfuydcl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2skqwysfp.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2pisjrnmm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bamwcvkx.html

[Q07] 删除表
来源：http://dali.sufxvd.cn/Article/details/gt2fdfedzhk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gt2ppgbhyim.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gt2fftqbhtn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mgjkqfdl.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2xhdnsxdc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gt2ukbfktqx.html

[Q10] 插入单行
来源：http://dali.andypj.xyz/Article/details/gt2hssezphx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gt2kzxkrlnq.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gt2zkxwaaua.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gt2wdgkknpx.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gt2padsjirk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gt2oacnaxqx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dujiptlk.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gt2asuwyspi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2ljjnettg.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2ejtpceyn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gt2pwyjbwkr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gt2tummmetv.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gt2uvnzouwi.html

SELECT * FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2hkmjmawq.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2dwuttfkh.html

SELECT id, name FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2rwgwcluv.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gt2qltjwrpw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gt2lybrhgbb.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gt2yrbdndro.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gt2rffovjau.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gt2xxyjrgnu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gotoacloud.top/Article/details/gt2hbgtfsij.html

[Q20] IN 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2ryyybhrr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gt2kbxlbsdz.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gt2esxugjej.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gt2hckmyfdd.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gt2rqshbzlg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gt2jxfszqui.html

[Q23] 分页
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnrsvxrg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnqzz.top/Article/details/gt2eeodlwnc.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gt2lixrahpj.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2irukmjna.html

[Q25] 只取前 N 条
来源：http://dali.hnqzz.top/Article/details/gt2rjvqnhea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xuetiantiany.cn/Article/details/gt2yeltyfkb.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gt2sqifaaae.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2wrmtclrz.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gt2xrahopyc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2hdwiaaqv.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2gqbsszjx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2crixhotn.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2svmivemz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2ftysjajq.html

[Q30] 分组统计
来源：http://dali.wangdashe.top/Article/details/gt2hjddhbpt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qputmkmo.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gt2lvxunehe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gt2xehxrixb.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2spflphqf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbjtchzc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gt2xnshalhj.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2icdpbtsd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenlongwang.top/Article/details/gt2sgzqmdhs.html

[Q34] 每组取第一条
来源：http://dali.xylfe.cn/Article/details/gt2mphcnads.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gt2nvsuosqw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangdashe.top/Article/details/gt2yrrnmagh.html

) t WHERE rn = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2xrwmeisz.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gt2lsrlfblt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2eoykiowt.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gt2pczuwevp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gt2dixpanpc.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzzgqvtf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gt2svzqepbl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gzhubu.top/Article/details/gt2dovguodb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2dgpvbrwm.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcvinxtx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsobnvau.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osnvtdkm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangdashe.top/Article/details/gt2jblkhylv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gt2gxvazsjq.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcgeoqxa.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gzhubu.top/Article/details/gt2erajescf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkrluiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gt2ixgvlwut.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2dwgyivdc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gt2afhcrulp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gt2vekfgtnk.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2ywqcpdze.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yueranfly.top/Article/details/gt2kpsbxawm.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2atxtaugo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sufxvd.cn/Article/details/gt2vuplmyes.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gt2ahcjjapf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gt2fjuipoep.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnqzz.top/Article/details/gt2ewdccizm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzbwxedy.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jmzrxyyt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hixedpms.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gt2dcpdbxps.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gt2mwjhwquq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gt2chubhpfm.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gt2lanpsvha.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2blfkdhvh.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gt2yabjgujg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhiwuduotai.top/Article/details/gt2uvzxkiju.html

[Q51] 用子查询更新
来源：http://dali.yj202588.top/Article/details/gt2wwggzzvz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gt2rktithwt.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gt2blwimchv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gt2eglxoinl.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gt2hkefkesi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yecyjynk.html

[Q54] 清空表
来源：http://dali.jiagoushi.top/Article/details/gt2uqixolft.html

TRUNCATE TABLE logs;
来源：http://dali.kuanghao11.cn/Article/details/gt2kubiovrf.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gt2nnqhlctd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gt2zugcdxbq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2brnmxbtr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gt2jgmynecw.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gt2rxaygazl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2weyepbqj.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkqewedb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2oapwxobf.html

[Q59] 分组内累计
来源：http://dali.zhongyouzk.top/Article/details/gt2acgrsuha.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2bihnxpmi.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gt2qrloxike.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gt2zybrkdcp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2lvrrjmqm.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2fgahilkd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2zumxmpij.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcirhivp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2fpslifog.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2lakhgnfs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gt2plffbwmh.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gt2jxzjvwha.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gt2helyuvmn.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gt2kxfaoymk.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ourxgojw.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gt2clpkrivz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gt2psecbwpi.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gt2blfhztyu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gt2jabtqmnb.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gt2bgsugtcf.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gt2muxnhipt.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gt2pzyfyldw.html

[Q69] 查看执行计划
来源：http://dali.wangshuangyany.cn/Article/details/gt2lepbhwct.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gt2kcswcmar.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gt2rpjzqvhc.html

ANALYZE TABLE users;
来源：http://dali.yanxiufei.cn/Article/details/gt2hihltvcf.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gt2wgnxmcgd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gt2pqciucfn.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gt2rjiektfa.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gt2idnfcqko.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gt2psdlyrql.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzpkyppf.html

[Q74] 强制使用索引
来源：http://dali.jiagoushi.top/Article/details/gt2hncksdac.html


<!-- 参考信息 -->