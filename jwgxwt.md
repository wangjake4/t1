代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2uzqpdxjm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gt2ttgjzcnp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gt2clyyyvsx.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stkkxspk.html

Java: new Thread(() -> f()).start()
来源：http://dali.sysykeji.top/Article/details/gt2znyyojgy.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2dzdleqqi.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2bmncluzo.html

C#:   Task.Run(() => F());
来源：http://dali.jinghuilouyu.cn/Article/details/gt2haqyvzph.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gt2orsjxccb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2mmgpockk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2kbcjoxph.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2vwsdqucz.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2ioctxcet.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cheryme.top/Article/details/gt2ysrbzbke.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gt2uaafrtts.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2fsycfpzn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gt2dzfegbhd.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gt2llhsnatt.html

Py:   with lock: shared += 1
来源：http://dali.yj20258888.top/Article/details/gt2kpqdidmm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ehwqpu.com/Article/details/gt2gyayaijp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gt2nlwbdchj.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2olsrvebz.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iahvxsif.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gt2vdawjezk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2lhjnvtte.html

C#:   lock (gate) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2offjjcoa.html

[O04] 定义异步函数并等待
来源：http://dali.jianghu66.top/Article/details/gt2kcxqumyb.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gt2npbsnysw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gt2upfcgxvg.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2nkoxhkfh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsswtivk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gt2dgjjhpyq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.havefunace.top/Article/details/gt2eobotzee.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gt2ndpcbghf.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gt2hoyuqeva.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gt2bmnysrly.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2yidyrhor.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2msyrarzp.html

JS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gt2hgvrclpg.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gt2mzlvnzah.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2wvrsbgiz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigufen.top/Article/details/gt2belhblne.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gt2cmfhzqbv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cheryme.top/Article/details/gt2qxmkzbnc.html

[O06] 使用进程池
来源：http://dali.aizwys.cn/Article/details/gt2mzdvjibg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gt2vrhkbgcw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gt2hxuiqfqc.html

JS:   // child_process / cluster 模块
来源：http://dali.tian-w.cn/Article/details/gt2eomlazqv.html

TS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gt2wqidjnsb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gt2drhxmqqs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gt2jtzkhocn.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gt2mbrjyorv.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gt2jzhbxfkl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2aombuuqv.html

P. 常用工具函数
来源：http://dali.dianchejie.cn/Article/details/gt2sukusxsb.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwpygdva.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gt2rqupbtfv.html

Py:   str(uuid.uuid4())
来源：http://dali.tanke756.top/Article/details/gt2iaagutbl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gt2yujbvcbq.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gt2jzhspqjm.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppgfutvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2quaklcqn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gt2hqmxqsrr.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2caeknntv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zycfv.cn/Article/details/gt2sksuaadm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2xgvithpx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gt2ywitlgpv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cashguo.top/Article/details/gt2oxkcqxjx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkfbppby.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2paphudtx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2pnmspnbl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgufenzy.top/Article/details/gt2zkitxrfl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gt2arcrfvnc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2llitjcas.html

[P03] 生成短随机字符串
来源：http://dali.xinyue.icu/Article/details/gt2rjlhquft.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gt2gvazmeus.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcbzaajg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2mihbgbxv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2avtpplgs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xuanzx.com/Article/details/gt2edlkbenr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gt2pktftzxp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhoulong.xyz/Article/details/gt2uanfoxdv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gt2dwzcfdkr.html

[P04] 求长度
来源：http://dali.fengsongda.top/Article/details/gt2vrvdrmdm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gt2iwyhobfh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2atfarrbn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2spspkggp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjemkxda.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2ldodtdzw.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2nurqetot.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gt2ixihueqr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gt2sxwhuikq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shuidangran.top/Article/details/gt2axkljbhp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gt2zsvllqvu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gt2sslusmdi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigfzy.top/Article/details/gt2yutrfsjw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gt2goxnoygu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gt2ygpsofaa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gykhtrpg.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2koypccft.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gt2jxvvzmfr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gt2elundwfy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2dtwdxgat.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ovekxuob.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwmplflf.html

TS:   if (x == null) {}
来源：http://dali.sysykeji.top/Article/details/gt2juhvweng.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2puiabbbs.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gt2jtxdbbfu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hysaishi.cn/Article/details/gt2tuvwkwjl.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gt2vcqxceeb.html

[P07] 防抖与节流
来源：http://dali.yvedp.cn/Article/details/gt2soklinai.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmapezxq.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbgltfzs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gt2txouavpu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gt2uapyszhh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gt2kmapwgoa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gt2wxytmmtz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gt2bxldxdiv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gt2rvyaabyq.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gt2wagisuce.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gt2vffhtujy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gt2mbpakvko.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258.top/Article/details/gt2svuecyqm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2mrnepsnd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gt2gmodpand.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhengqikj.top/Article/details/gt2rowhghyk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gt2edzuqjni.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shzxlz.cn/Article/details/gt2lhkjwzsi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2hdknnhra.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gt2kvdnezec.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqvbywsy.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2lgkhrpdd.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2evdhasal.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gt2pzehzgrm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wzxtmyfo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hysaishi.cn/Article/details/gt2swcazxcs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gt2vgzndith.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irsucrtn.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixjexorn.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gt2amonuyti.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gt2algdtjuy.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gt2dqizeuoh.html

amount DECIMAL(10, 2),
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfojwxdi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gotoacloud.top/Article/details/gt2acdmlcul.html

);
来源：http://dali.redwolf501.top/Article/details/gt2ndohvhyu.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gt2tomgvbse.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2zisswtjx.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gt2fkvtlsnc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258.top/Article/details/gt2hxpsxdhx.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmhyraos.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gt2jpavlhxb.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2onghpiih.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gt2dqeaiuze.html

[Q07] 删除表
来源：http://dali.hfpthk.cn/Article/details/gt2aqifbvjc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gt2ozvhlmvz.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfhslzoc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gt2mpzlaovu.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gt2rdimrler.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2bvxtgrjb.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gt2mdswrevi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2buuzmtth.html

[Q11] 一次插入多行
来源：http://dali.yongpay.top/Article/details/gt2ozpjzshl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jiagoushi.top/Article/details/gt2fvqsjbqd.html

[Q12] 插入后取自增 ID
来源：http://dali.jlsjyb.cn/Article/details/gt2wziykyoq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2bcigblbc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gt2wnbzmlsg.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gt2qfadzaqh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuetiantiany.cn/Article/details/gt2xuirhcga.html

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gt2hddvjnyb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhengqikj.top/Article/details/gt2lnfoejfe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gt2qdyfbcuu.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gt2owoxxxac.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2bhzhfkww.html

[Q16] 查询指定列
来源：http://dali.yueranfly.top/Article/details/gt2andauiyd.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2zwpilvdh.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gt2wsjbzlvz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2flrqvlvj.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gt2otcpqwyd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gt2njqyswnv.html

[Q19] 范围查询
来源：http://dali.zhiwuduotai.top/Article/details/gt2liqhsckn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.smart0.xyz/Article/details/gt2ubhvxstd.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gt2wdeumsul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gt2clzkavzw.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcwqphl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gt2pewhbagr.html

[Q22] 排序
来源：http://dali.ivvv.top/Article/details/gt2obqnzaea.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxinkj.top/Article/details/gt2gfiostzl.html

[Q23] 分页
来源：http://dali.haohaochexian.top/Article/details/gt2onlfxcbm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxfkksao.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gt2pirprbah.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2aizxposs.html

[Q25] 只取前 N 条
来源：http://dali.jqgfzy.top/Article/details/gt2rgxhbpoi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gt2ifyuhuii.html

[Q26] 计数
来源：http://dali.bjfxy.top/Article/details/gt2iixjaebr.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2zartkrpe.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gt2pskvjxyp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2fdyveqfw.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2ilvjygmo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2nskglqrc.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gt2wbglrxjc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2yfftjkyj.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gt2veymvgld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2divaezju.html

[Q31] 分组后过滤
来源：http://dali.yongpay.top/Article/details/gt2mgnauuzm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gt2sgwgaafv.html

[Q32] 分组拼接字符串
来源：http://dali.nwbrower.top/Article/details/gt2qrliqcxu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gt2bneucokf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ybcxt.top/Article/details/gt2cigoxila.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gt2eqxyodkz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gt2thhtolqm.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gt2dtgqxohd.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2kgaangyo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfsmrkyp.html

) t WHERE rn = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2pvaqfbic.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gt2bflrzngr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gt2zdssttrm.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gt2khlnormo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigufen.top/Article/details/gt2srvrkyim.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gt2yvcskwfq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gt2bdnnyaoo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gt2vybtzjbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cashguo.top/Article/details/gt2nhnjfutw.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2qphblwvz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gt2lzvkegqx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gt2hakowiib.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pifzglxl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gt2lefdwlxx.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gt2hvgzquur.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gt2rzvteylf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gt2bgnimgyt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2ugcuujym.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gt2xckphrzm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gt2vztltjsk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinqigufen.top/Article/details/gt2gpuosfzq.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gt2snlhmttl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gt2mkunougf.html

[Q44] IN 子查询
来源：http://dali.bjfxy.top/Article/details/gt2ntsjbfzw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxuanxn.top/Article/details/gt2lmdkruru.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gt2xlnhpafl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gt2rjvretnx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zdqjudy.top/Article/details/gt2escwevzy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2pfhfngfy.html

[Q47] 与平均值比较
来源：http://dali.bjfxy.top/Article/details/gt2uozxqoei.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyhdfeqa.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2uzparrch.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekncwday.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gt2cqlguani.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2posotnne.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gt2lhgvkmss.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wqvmqufp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2yuuxtnxj.html

[Q51] 用子查询更新
来源：http://dali.sxryk.cn/Article/details/gt2wzminyaf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gt2mrhyoeyt.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2usvavhpt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2wyznlyml.html

[Q53] 按条件删除
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwzwgdda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gt2goyurgsd.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gt2zsookzfp.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gt2rzfxovjn.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gt2tcphzdso.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gt2jjuimrwl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gt2wqxuaqqd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gt2pvzjgaqa.html

[Q57] 行号
来源：http://dali.ehwqpu.com/Article/details/gt2adwywrbu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guannengcc.top/Article/details/gt2uqgzyvqd.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gt2egingurf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gt2uzoutvii.html

[Q59] 分组内累计
来源：http://dali.yuxming.cn/Article/details/gt2iodnxznv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2vzkzvrtc.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gt2cjblqxop.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gt2oagtvdnm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gt2fzkdlouo.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gt2lfvgbxfg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dawbzmbj.html

[Q62] 分组占比
来源：http://dali.sufxvd.cn/Article/details/gt2cvrqdgnh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gt2jqurijei.html

[Q63] 开启事务
来源：http://dali.yangfankeji.com/Article/details/gt2qmjdnzwb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvwlouqc.html

[Q64] 提交事务
来源：http://dali.zycfv.cn/Article/details/gt2irtjvfth.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gt2kcwudzgg.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gt2oxylbowa.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2jfadjkki.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gt2vknzyuqs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gt2zgurhgns.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gt2oiojtmkr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gt2ilktjesf.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2penjsaiy.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gt2wcdzysin.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2wtqffyru.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gt2eypsfpjf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gt2lqfbxdzm.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gt2pkdldkdd.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gt2tfnrpapd.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gt2mfccnmgq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxinkj.top/Article/details/gt2yecwpaco.html

[Q72] 查看索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzxqjryc.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2gusojmgq.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gt2qfaxjdib.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbihghjz.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gt2ocyschob.html


<!-- 参考信息 -->