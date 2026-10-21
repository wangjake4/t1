代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gttglbjvdq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtoqvpmtqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gtqawxvdhj.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtdexozpko.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtizdigyau.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwzqdpam.html

Ruby: Thread.new { f }
来源：http://dali.jlsjyb.cn/Article/details/gtntfxjjvi.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtnhesqlyi.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtzjrxbzdc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.smart0.xyz/Article/details/gtrfwlmpiv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtysoqrgza.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtaahgzvit.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtvnymngua.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xylfe.cn/Article/details/gteypjzrdt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtczqsvqro.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtowfcmsat.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtyipskcqu.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtsxvjujtp.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtzxxibsvx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gtejwlwevz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtxuflvdrp.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtadjlicqb.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtakhyqzqg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhengqikj.top/Article/details/gtlvlhfcow.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gtviyttjqj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtmbywisai.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxbqxtvn.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtrwufyojt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtlivnxwxl.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtewxrojah.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtvthotsbv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ehwqpu.com/Article/details/gtsyixcczj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtegkbbgjp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtobdcmqsi.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtxvulgejc.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtsjhvilfq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtaevnudur.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtvdhezzqy.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtmvwlywco.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtagkwxgpm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtgbptrger.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtzhhghbdl.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtwbjputcn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnxiangtu.top/Article/details/gtyufqiplt.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtkbcasdzs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtyiiazyvp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xinyue.icu/Article/details/gtbxvgextv.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtcfcgcbel.html

TS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtjoktwlzk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtpcbcopah.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gtkkyzzugk.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtaqlhvtsf.html

C#:   Parallel.For
来源：http://dali.chenjidiqi.icu/Article/details/gtpkbaexag.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthunttjlo.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtlicdjqmi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtlfpntcti.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtmzqudmhi.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtadblsvxg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtoajshhyz.html

JS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtjzektabb.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtmkzwtuzc.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtbtzukrxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.svipenyu.cn/Article/details/gtuetjblkk.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtnsvmyoyo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gtwvyddrox.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtmgpihojy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtduimnnht.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gtdyfdcfzq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gtdojrxkfz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtjhpqopif.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gtrsfsblcn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gtkulbmgnx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.mhx1999.top/Article/details/gtbzwcxwhn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtjkgfmeie.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtnhsotrxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtwqaourbo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtbsabxgnr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gtkdfsfhrq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gttsoibcah.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxytyeggu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtvojxliya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtjtfdqgkq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuxming.cn/Article/details/gtvlcgsjqp.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gttfikehtr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gtmxvdadob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtawgmlppy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtwkmsvyfi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gtleqfmxgo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtlyeuwnpk.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gtzubzfwgk.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtidudiweo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtatwwqbjm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtbebhufuo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtpuqtqrgd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gtcquxqegm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtfcbfweys.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtmnpdycrh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtleaubdye.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtukfoiaxr.html

Ruby: a == b
来源：http://dali.ivvv.top/Article/details/gtsrqvzjek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinghuilouyu.cn/Article/details/gttrnoqcjb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtncywryxr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtiyxtyphm.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gteivjedso.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenzaomai.com/Article/details/gtrqqjjkgx.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtqneozryh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxinkj.top/Article/details/gtledvriwj.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoxlyelf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gttxrwspnn.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwdmwkeoq.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtgfeyhbcb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtudpnyusm.html

PHP:  // 手写时间戳比较
来源：http://dali.cheryme.top/Article/details/gtkgzypkoc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gttdevsvrl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtxaudmktn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gtrsgnebwb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gttwcnaiqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroykvvvs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtodyafrbm.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtroivcunn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gtvkqgxave.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guannengcc.top/Article/details/gtvihfxyva.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gtwhairsys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtnmnbyibk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtdhikolvj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtrxhjiuvj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjynrrog.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtykmdbfxw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxpcvofp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtnyqwjxgl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthrtavxqf.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtyrncngly.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gtspmurwgy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gthouzuwfh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtddpkgsit.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gogol.net.cn/Article/details/gtothfmkju.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cheryme.top/Article/details/gtvpumpmhp.html

);
来源：http://dali.bjfxy.top/Article/details/gttuylqrpg.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtyddcvofe.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gthgrlqbqd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtdzbfghtv.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtosqqtckk.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gtphvzzkpr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gthvfhlbcl.html

);
来源：http://dali.jyoumei.cn/Article/details/gtmwrvsieh.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtnxqyyltm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtahzksvdd.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtlcszhgiw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gtwlgfscle.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gtrrnvvzqo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gtwoawhujz.html

[Q06] 删除列
来源：http://dali.316326.xyz/Article/details/gtnoypycqk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtmwilnkyc.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtietwiuig.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtjbxmquvb.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtugzsufww.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtyliatwcf.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gtlhoerdpm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtuxjrooaa.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gtrelrkmmz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtvniasdkn.html

[Q11] 一次插入多行
来源：http://dali.jinqigfzy.top/Article/details/gtcysfmdge.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtymrnopon.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtatoewqmr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtnndwgfkl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtvzfvwwlj.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gtogffxszz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtnvrbnfod.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258888.top/Article/details/gttiobgghp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xuetiantiany.cn/Article/details/gtjsltnnup.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj20258888.top/Article/details/gtrngbgzxs.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtbdpowlia.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gtyuvxxwow.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtsoiicduu.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtlnuyzukc.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gttqjzsfdf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gtsvrhkoyh.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtjuppxsvc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hywenlv.cn/Article/details/gtktgswrnz.html

[Q19] 范围查询
来源：http://dali.ybcxt.top/Article/details/gtbgntuiun.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgufenzy.top/Article/details/gtwohqihch.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtjeqakgwq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtjypqzycd.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtxvgqdbbc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yongpay.top/Article/details/gtcvpuygid.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gtliloghrw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtfkjkrhmi.html

[Q23] 分页
来源：http://dali.smart0.xyz/Article/details/gteplioqqk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jianghu66.top/Article/details/gtqyerymmz.html

[Q24] 去重
来源：http://dali.zycfv.cn/Article/details/gtnmpmtduo.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtyvvqlymu.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gtpidqktot.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtxonlqgio.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewcoizvl.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtvaenglrb.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtrsccpquv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtejspkelp.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgylugqde.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtamhwvzxm.html

[Q29] 最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtxybndfef.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtyrasoiuf.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtiurbcaxl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtfxgmvrzx.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtrpvvmgbr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtjjvbjxsl.html

[Q32] 分组拼接字符串
来源：http://dali.jianghu66.top/Article/details/gtbtmvzkcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtiqervynv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtmksxvctw.html

[Q33] 多列分组
来源：http://dali.zhongyouzk.top/Article/details/gtmgfbsxuf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.c1oappe.top/Article/details/gtoalizukg.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtibbcdxeh.html

SELECT * FROM (
来源：http://dali.zhengqikj.top/Article/details/gtvsdgrffg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtslxtsouv.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gtbwerimjv.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtethnzfmq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtvgfnbllm.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gtbdufiqjn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtzrmcanfc.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtmnttxsin.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtnexxjehi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbxiwpzk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtwvhbiysb.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gtzxysvxmr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwinwlnld.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtiaiimepg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtjnfvuivf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtrppvjgtj.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtaotzuvzn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtdykhjqvg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hfpthk.cn/Article/details/gtbutnhhyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtfatvohum.html

[Q42] 连接条件附加过滤
来源：http://dali.yuanzhike.top/Article/details/gtvxuyhsfo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtjwrnnteq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtngpemhav.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtkihgtifu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtfmwfpkjq.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtvlzzdyfo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtefrthqlf.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258888.top/Article/details/gtxvkjxekc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtweldhyrn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnsstmij.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtfartuavo.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtgvxvnwsu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtivcvgvvh.html

[Q48] CTE 公用表表达式
来源：http://dali.guowangkeji.top/Article/details/gtkbmqehlv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xziqi.cn/Article/details/gtujrrnecn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gtuaamvpwe.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gtttmjpvhk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtwgrxdggl.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtjbkjlrbl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jlsjyb.cn/Article/details/gtmziskhtc.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtdxhtpisc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtbsfjfzoe.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtesjjkrbx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtyefqlwoa.html

[Q53] 按条件删除
来源：http://dali.pycfn.com/Article/details/gtyiqadcih.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtdibnwnyb.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtoeqnaqjv.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gtauwxwuyw.html

[Q55] 排名（并列占位）
来源：http://dali.zhiwuduotai.top/Article/details/gtsgjnehnj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gtyfqjsqtq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gtonerzmvh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.iojbl.cn/Article/details/gtctsepdrw.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcipvigm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtymbdqnjt.html

[Q58] 累计求和
来源：http://dali.gaohongyu789.top/Article/details/gtcxkieoaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gtlthjytsr.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtaeqqtair.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtssmoplac.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtglmpwhnq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nwbrower.top/Article/details/gtwsjtwyif.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtolermbpt.html

[Q61] 移动平均
来源：http://dali.smart0.xyz/Article/details/gttzbsmyil.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtvqvmeddm.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtsrebrbav.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcemigti.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtafcrjwol.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gttskulaep.html

[Q64] 提交事务
来源：http://dali.ppjwa.cn/Article/details/gtvxjcjwst.html

COMMIT;
来源：http://dali.chenzaomai.com/Article/details/gtbxxrprzh.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryeaswrk.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtomjvpbwj.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtqgnwltyk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.redwolf501.top/Article/details/gtuvuqsyoz.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtbvsehdzm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.meibo888.top/Article/details/gtajsctvlo.html

[Q68] 保存点
来源：http://dali.zhongyouzk.top/Article/details/gtyjdhykki.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtzkakfewb.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtdnwtjtyk.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtdgfhujov.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.guannengcc.top/Article/details/gtrrgzxaip.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gtvhcnarux.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtyubitkkw.html

[Q71] 查看建表语句
来源：http://dali.guannengcc.top/Article/details/gtugextkly.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.dianchejie.cn/Article/details/gtslyudwpd.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtghxiximx.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtevaeepgi.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gtkakmjlcd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenlongwang.top/Article/details/gtupbqdqkc.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtesexsyjw.html


<!-- 参考信息 -->