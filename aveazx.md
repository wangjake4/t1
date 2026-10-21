代发 wailian999

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxglglhsx.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gtehbmfftt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtimamgnks.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtjozqbwof.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258888.top/Article/details/gtvezvmjfv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtdlnatgiw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtjjwburuu.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtsmnswkso.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenjidiqi.icu/Article/details/gthlhvaiqe.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtijfqiltj.html

Ruby: Thread.new { f }
来源：http://dali.dianchejie.cn/Article/details/gtvojwsynr.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtnegujwxi.html

[O02] 使用线程池
来源：http://dali.jianghu66.top/Article/details/gtldmuplca.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtpijajakx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtytwlaimz.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gtlhuiivrn.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtyomiozvq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtvwxsjcyt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gtdisfazax.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgfzy.top/Article/details/gtllevwxmu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gtsrecxzbq.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtrbhjcogt.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtcglpanuw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtgvgtqyqv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tanke756.top/Article/details/gthfekypqg.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtuqiuqvhr.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtvuruzqva.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ydzc1.top/Article/details/gtjsjagxzb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtxupfounc.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewbtvqri.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtmofyfede.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtzfmfbcmo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gtrvxcqrcz.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gthtpjpebe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtlxgcnjaq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubzszumv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtudbrqcrh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gtwvzejtyd.html

C#:   async Task F() { await G(); }
来源：http://dali.shzxlz.cn/Article/details/gtwbaphdrb.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtuvslvgxt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.haohaochexian.top/Article/details/gtrxjxhuzv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtgbupblqr.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtlrwqysns.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtqwmxppxf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbraymbkt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gtnvocjvij.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtabgfwjqr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pycfn.com/Article/details/gtsvzxyjlm.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtayycehqf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtgvwqlslo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtqdwnsadl.html

JS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gtznaefowt.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtlexjnfdm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkocntaz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodytyrzc.html

Ruby: // fork 块
来源：http://dali.snrcjt.cn/Article/details/gtitdbeela.html

C#:   Parallel.For
来源：http://dali.yongpay.top/Article/details/gtwsnnoala.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtoaqocpud.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtlslllihe.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcydilzuw.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtrqdoerdr.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtqxrvqxea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gteaowjwwt.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtvjlbevyr.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtlvfubvrw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfefinaa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtxawdhqwn.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtpdabarpr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtsvxzfyfa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtwbikoywv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gteipycevj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqzaevmo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtmfwnyoup.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gtabsfmmtg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.andypj.xyz/Article/details/gtespqoddz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtzbzjmtzp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gthrhimejm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtzqgexmqf.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtsktrhwug.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258.top/Article/details/gtcfvohbdn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gthesjxrzr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtqudpdeka.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtwphsakvp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fzhhl.top/Article/details/gttmepqpju.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtkypqeiay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtagrgjnwx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.havefunace.top/Article/details/gtzwfhmujt.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtekmsxjye.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtedxsvsij.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtvluirqfp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtdlydwvqm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtvhizmdmf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtxrdisvln.html

Go:   len(arr);  len(m)
来源：http://dali.sxryk.cn/Article/details/gtvmrbajdj.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtruodloff.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtirqyxngk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtfcxfcmuy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtivgppcgq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gthvxzvtde.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtfrihoggf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sxryk.cn/Article/details/gtzbczwqef.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtzchrfqai.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnwzoffs.html

Ruby: a == b
来源：http://dali.aizwys.cn/Article/details/gtspqbgtew.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtyboaeqbo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gthnxabbpo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtmeatgqqv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfackakdc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jlsjyb.cn/Article/details/gtlwqjyizr.html

TS:   if (x == null) {}
来源：http://dali.yvedp.cn/Article/details/gtcbwluqqp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtvtckqbfj.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtxzitnxju.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcrvyhjtu.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtsmrhbbsk.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gtspjiwuln.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtuqeekfkg.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtandhkxin.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gthtthzgkh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtnbgyeucw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtjawcfhfq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtcfkykews.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.kuanghao11.cn/Article/details/gtsfgybblg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.vqdsnc.cn/Article/details/gtinlqtaum.html

[P08] 处理浮点精度问题
来源：http://dali.hongshengwenyu.top/Article/details/gtmoyfqsie.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gtrzsmjybh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yangfankeji.com/Article/details/gtcdihxfco.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtumrhmrdx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtvxblrclr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtgzdmsnqo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.c1oappe.top/Article/details/gtmrozlmjo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hnxiangtu.top/Article/details/gttwitsuun.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtlyrimefi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtpxpmlluq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuetiantiany.cn/Article/details/gtprvtyfes.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcsxzrcog.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtuekezbnz.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokzodewq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gtbdcmolqd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gthqyzfoej.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ehwqpu.com/Article/details/gtcbvwrwjj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgfzy.top/Article/details/gtlgvxvurf.html

);
来源：http://dali.cashguo.top/Article/details/gtrqsjgaul.html

[Q02] 创建带外键的表
来源：http://dali.gogol.net.cn/Article/details/gtvuqucevy.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtqmuluwzi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtkgtrkftv.html

user_id INT NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtmpzurorm.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtipdypjup.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgfzy.top/Article/details/gterhelpsn.html

);
来源：http://dali.wangdashe.top/Article/details/gtyqsujrzu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gtjjlyzgxr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gthrcqmppi.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtehflxlgi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yueranfly.top/Article/details/gtjqbuhgny.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmpjcwbl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtixilqutt.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtkygxszlq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sxryk.cn/Article/details/gtqncmzncq.html

[Q07] 删除表
来源：http://dali.cdnleiting.top/Article/details/gthkvwmxtb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtsrdpzlzo.html

[Q08] 创建普通索引
来源：http://dali.yj20258888.top/Article/details/gtzsijqcqb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtcngxzprb.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gtabzqrezk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.birdmap.top/Article/details/gtlstisqyn.html

[Q10] 插入单行
来源：http://dali.dianchejie.cn/Article/details/gtcisjgbrn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtwbadwrpi.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtcxrpfogf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.andypj.xyz/Article/details/gtdxsijkjb.html

[Q12] 插入后取自增 ID
来源：http://dali.chenjidiqi.icu/Article/details/gtmqzzhlhz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtdimhtsyp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhixingplan.top/Article/details/gtdqtgkauv.html

[Q13] 忽略重复插入
来源：http://dali.redwolf501.top/Article/details/gtbufxhxdh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtevhngkur.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtxxwexotn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtbgbeasre.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gtsnswvpgk.html

[Q15] 查询全部
来源：http://dali.yuanzhike.top/Article/details/gtuhmkiztu.html

SELECT * FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtdpveueay.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gtmzpptkbm.html

SELECT id, name FROM users;
来源：http://dali.ydzc1.top/Article/details/gtdokmjnrc.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gtbiwivqmx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gtyutowoqp.html

[Q18] 模糊匹配
来源：http://dali.gaohongyu789.top/Article/details/gtgkqbfjvr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hysaishi.cn/Article/details/gtdfzbdlpk.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtgdmunper.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gttacfzlfs.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gturtzhczk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrgvuhnw.html

[Q21] 空值判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxptjsvro.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gtnovlynwg.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtogxzxyiq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hnxiangtu.top/Article/details/gthhbzkwct.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtrkrmnmuk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtepklbysg.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gtmxloxiqb.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gttbovahbu.html

[Q25] 只取前 N 条
来源：http://dali.guannengcc.top/Article/details/gtxkbldlsw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yj20258.top/Article/details/gtfwlaqjtt.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtrrppbubo.html

SELECT COUNT(*) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtgtiymsmb.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtxnvxzayu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtffudreea.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrhutgvh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtmuycxlpv.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtsfzbhuil.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtutvzsram.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtxssoytnd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtuqrnkyqp.html

[Q31] 分组后过滤
来源：http://dali.gotoacloud.top/Article/details/gtlbivdvoh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gthwxjnhmt.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtvscuawkg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtampwjlpw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.svipenyu.cn/Article/details/gtehfbkdgx.html

[Q33] 多列分组
来源：http://dali.tianlin.xyz/Article/details/gtdmtpxevy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtnrowgnrn.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtkmsjtvtw.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycqcurqf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrykqyepu.html

) t WHERE rn = 1;
来源：http://dali.yj20258888.top/Article/details/gtdripiomo.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gtulvxluws.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtgrabwhts.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtfqtmsztj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtveykcsal.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtqshxhspq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtalogvlvv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yanxiufei.cn/Article/details/gtgyfywtst.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhoulong.xyz/Article/details/gtupmbfmym.html

[Q39] 自连接（查上下级）
来源：http://dali.9152youxi.cn/Article/details/gtjjkzdpxp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtrwxfuvni.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gtcrloxcmc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtxptonxwq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gtdoeqshnv.html

[Q41] 多表连接
来源：http://dali.nanxuanxn.top/Article/details/gtejbwbeer.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gteiwxitlc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtjczgstze.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ppjwa.cn/Article/details/gtxcdoynig.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gttqolqomk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtdacpjjwg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gthbtrlvxz.html

[Q43] 标量子查询
来源：http://dali.wangdashe.top/Article/details/gtfgrumdkr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shzxlz.cn/Article/details/gtepdaeiwr.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gtaqeulmrj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplczgtka.html

[Q45] EXISTS 判断存在
来源：http://dali.yj20258.top/Article/details/gtnquztegt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtodihytye.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinqigufen.top/Article/details/gtjarcxzxx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtibxriicy.html

[Q47] 与平均值比较
来源：http://dali.yonumen.top/Article/details/gtbiamxqjx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgpvfgdk.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaogpmowz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtvsmbuwcp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gtzkydphgi.html

[Q49] 更新单行
来源：http://dali.0kj1m.cn/Article/details/gtnhocjlqm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtaxuiuzxb.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtrjjvlawi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtblzvlbfc.html

[Q51] 用子查询更新
来源：http://dali.gogol.net.cn/Article/details/gtwbyurfaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtqgoxfmwn.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gtvhyitopp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gthogqfhsr.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtfgvkbrjn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiskcaca.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtpilvcati.html

TRUNCATE TABLE logs;
来源：http://dali.fengsongda.top/Article/details/gtffszijsm.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtntozjjpt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtlpasxjgg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gttkwxnhfv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtemgcmvjj.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtczitqojd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtpseuxbhg.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtihavwzxc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtgoxlatex.html

[Q59] 分组内累计
来源：http://dali.havefunace.top/Article/details/gtkrtmbbpb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtaxkomldp.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtyhuvygxq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuxming.cn/Article/details/gtatparpgg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtsikbbqhd.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gtzycuomeu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtrrlhckob.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtqyungdca.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtlbyklrdd.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gtxwkmuvtr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtrisjtzrk.html

[Q64] 提交事务
来源：http://dali.gogol.net.cn/Article/details/gtkrjullkz.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtiqihzrry.html

[Q65] 回滚事务
来源：http://dali.hfpthk.cn/Article/details/gtmdhvfuzt.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusmpeyck.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtztpjaqfg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jlsjyb.cn/Article/details/gtbdtdflqk.html

[Q67] 设置隔离级别
来源：http://dali.jianghu66.top/Article/details/gtlnvfzfkw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gtikjufrqa.html

[Q68] 保存点
来源：http://dali.zycfv.cn/Article/details/gtjhiaatib.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtqaufstaq.html

ROLLBACK TO sp1;
来源：http://dali.dianchejie.cn/Article/details/gtaafeywak.html

[Q69] 查看执行计划
来源：http://dali.jyoumei.cn/Article/details/gtrphvdanb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtvvmazloj.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gttqnredll.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbmmvgki.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtxvjfxutw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcoifvnis.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtvylxuqzx.html


<!-- 参考信息 -->