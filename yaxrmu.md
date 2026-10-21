代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtoqaqzyap.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtjelgztdx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gtrtazccjq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtcnjsgbyl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwxzzwuc.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gtgisvjfbe.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtwvmysing.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtqszxidlj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtulerjkza.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gtypryieif.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryylpxka.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtjsplrchq.html

Java: new Thread(() -> f()).start()
来源：http://dali.sufxvd.cn/Article/details/gtvvzhmmqr.html

Go:   go f()
来源：http://dali.hywenlv.cn/Article/details/gtvsrbmfrw.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gtjutunmmb.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtucgkuuep.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gtnkzhxbwv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtumvqetux.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtbjikpiin.html

JS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtudtrpvqz.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtkzmcksod.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gtfmjotcfv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gtimigwgef.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtquuznipz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gtpkyspnjx.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtrshynwns.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gthtrlxhzs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtlkjcinzr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cucudq.cn/Article/details/gteavdhdxo.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtdxkvhmyz.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtelsktegv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtlxqzixyc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtzfqubtix.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtavzpjzer.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcoqjsgse.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyvgrwuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdtxxmco.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtplmzbqtg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtifrhcmat.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtjovemvud.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtrwxtbqzs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gtlhjrcyha.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtxneiudoo.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gtvqdwvjrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtodsfqfeo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ppjwa.cn/Article/details/gtgsyqdjqs.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtkgpgkyhd.html

TS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gtkxlbaefi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjhnmaod.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtokfefssu.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthvaqvbg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtjkdtshmk.html

[O06] 使用进程池
来源：http://dali.yj202588.top/Article/details/gtpzcwzhgc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtfopvoqdp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangdashe.top/Article/details/gtwyhxmnaj.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtkxkwlkly.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtfpxumyyt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtiyscxvzm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtuyliwjid.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtmizndcib.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtmlktbsgn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtciolofct.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtritzsqkn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoxkgcxar.html

[P01] 生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gtsazzgxeg.html

Py:   str(uuid.uuid4())
来源：http://dali.shangyingyoupin.top/Article/details/gtsyxaccha.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtitldazdt.html

JS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtthlisgti.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtknjdksby.html

Java: UUID.randomUUID().toString()
来源：http://dali.ehwqpu.com/Article/details/gtlgrabnvn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gtphtlqfrc.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtugndudsk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtazbdznqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gtansfwnwm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtgoapzwqe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gtzwrxkjsy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfczqlyc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gthekplrmz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtdzquxkft.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fzhhl.top/Article/details/gtapkmobti.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtkgbmmpxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gtsllkrrey.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymeytakt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtmmbxixqw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shangyingyoupin.top/Article/details/gthapgblkp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtycnwwqvr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gtbxlyodnn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtyfzuwyjm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtmbauclvd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtnzquluca.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtrodptqyv.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gtlezvribu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gtvezwafjd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtfpgvonld.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnhxprbg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtigtigpah.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtpvtwkvyk.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtawlbokrd.html

Ruby: x.length;  x.size
来源：http://dali.pengpengdd.cyou/Article/details/gtxbjwgrvw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtpunppfet.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxinkj.top/Article/details/gtxlipvnig.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gthfzcjyff.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtwyucrsoh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtwvkoktut.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtgyzquoqy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtqpwlzbsj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtfbdptgpy.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtkagjhdzl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gttndjsiik.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gttggyuobw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gtktccjjwc.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gtwinknqyv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gtbmufixkj.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtgoqqonyu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinqigufen.top/Article/details/gtsyhgfgwg.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtmvuyjoma.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtxfuwtmgh.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gtigkdnutw.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtqrkvpphp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gttrymvoxf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtajwrxdaf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtzwwajuqb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewgnlurz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tian-w.cn/Article/details/gtoirzgysv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtuanoiofu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtdzljnyph.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gtlgbiuekj.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtenqcnbok.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtmnacyeqn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtaivjiehd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gtywhdqlrq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gteisakhaz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtkxwzxjuq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gtwwiioqud.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gtfjprxpam.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtubmmwwvd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcstmkpcg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gtsovkcrql.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtfkwvizqj.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtkbzjhrme.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdsveuur.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gtyvooflsd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtninlprhz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtnahfhltt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtedloqhdb.html

);
来源：http://dali.birdmap.top/Article/details/gtolwaixja.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtqwnslies.html

CREATE TABLE orders (
来源：http://dali.xylfe.cn/Article/details/gtnmwwnifm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtdjsxhsds.html

user_id INT NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gthmkwsbuh.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtjjlwmvdg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj202588.top/Article/details/gthgvwielu.html

);
来源：http://dali.haohaochexian.top/Article/details/gtemcqbxyl.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtizmofuzo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gttyiemvom.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtmxqnkshg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gtkapmjnfa.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gteopppdwq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ydzc1.top/Article/details/gtzwtlclpv.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtzbuqwlqo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhongyouzk.top/Article/details/gtdzjuyfof.html

[Q07] 删除表
来源：http://dali.jinqigfzy.top/Article/details/gteulsaihv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gtpuqhquig.html

[Q08] 创建普通索引
来源：http://dali.shuidangran.top/Article/details/gtfmdivbya.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gttzbvpxdh.html

[Q09] 创建唯一索引
来源：http://dali.pengpengdd.cyou/Article/details/gtrddhdyya.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtzcikpgjt.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtgkhovdgz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.redwolf501.top/Article/details/gtxfxxzmtw.html

[Q11] 一次插入多行
来源：http://dali.chenjidiqi.icu/Article/details/gtxhkgihkp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yvedp.cn/Article/details/gtjlotdoiq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrksfqwty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtqgnmmcoj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtlqetzmkm.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtylroeffa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtriimubvf.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gtieqjnjdd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtqgfdwsiu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hysaishi.cn/Article/details/gtikifrzne.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtwimzglts.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtxyigkvry.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtbhmpldxo.html

SELECT id, name FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtufphbaen.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gtagkrxggp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gteupyqnfr.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtznfdedhd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtfyafbisa.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtubcykguw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gthghchqka.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtnwldbzuq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gtxeqhdscb.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtnfigkejj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zdqjudy.top/Article/details/gtwhlzrtly.html

[Q22] 排序
来源：http://dali.quarkkingdee.top/Article/details/gtsnfvgipb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gtyhntevaz.html

[Q23] 分页
来源：http://dali.316326.xyz/Article/details/gtzqejhwtp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dashuyun.cn/Article/details/gtmzeuqiwa.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtxsjvotmn.html

SELECT DISTINCT city FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtncremauf.html

[Q25] 只取前 N 条
来源：http://dali.ybcxt.top/Article/details/gtjtvesruj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtgebawctl.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtnpwsexsq.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtnxunogax.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gtyxzrjbbg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fzhhl.top/Article/details/gtkrjweihc.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpqypsou.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtypanmrim.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtlaasjyuz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoparumou.html

[Q30] 分组统计
来源：http://dali.cdnleiting.top/Article/details/gtoebsvnlz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtsqohrdgx.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtxkjbdicx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.fzhhl.top/Article/details/gtdtioficv.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtooeklaww.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtfihjnmaj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.smart0.xyz/Article/details/gtvurfczeg.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtpvonirvu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gtquenvhfg.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtnlazqwgv.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtslglwexs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtcbeoyzst.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtrlxhkvln.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtigjjrovi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ppjwa.cn/Article/details/gtudxpwjkv.html

[Q36] 左连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gticokynnn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtzhikccai.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtjxitdchc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sxryk.cn/Article/details/gtiygisfkj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sweek.top/Article/details/gtvykkmgze.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtmwcjukgz.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gtrjrqsnli.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtoxvlywcy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gtlzfpbxvq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gtkfsrdgqu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtjwvyxhkx.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gtzzlmxkwm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hnxiangtu.top/Article/details/gtqohlkamk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtixnuyxwg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwpwdzdb.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtncbiortr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtxarcelyv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gtcmpbqoej.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gteqwgxhxp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aibaodan.cn/Article/details/gtfscuymbm.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtkdppwncd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtapuffcki.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gtkvqgonno.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yonumen.top/Article/details/gthfsiwafn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.iojbl.cn/Article/details/gtwfytihsn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guowangkeji.top/Article/details/gtrfmcjfee.html

[Q47] 与平均值比较
来源：http://dali.sweek.top/Article/details/gtlyxdscng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlihnpkk.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtigflnqvk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtmvjgpqwb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtmbflzark.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtdueixzrt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtkvlmnuab.html

[Q50] 批量更新
来源：http://dali.cashguo.top/Article/details/gtpdwstwwr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.birdmap.top/Article/details/gtqfauotea.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtsajomacy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtgnbpbwbj.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtklcfvcjw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtrxxclpub.html

[Q53] 按条件删除
来源：http://dali.jianghu66.top/Article/details/gttxhqpvxr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtqyjezjef.html

[Q54] 清空表
来源：http://dali.316326.xyz/Article/details/gtnrfykasx.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gtxjidyiyw.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gtavmnamck.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtamhfphww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtfggoxhrv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cucudq.cn/Article/details/gtfsqjjifn.html

[Q57] 行号
来源：http://dali.guannengcc.top/Article/details/gtbgdbyykr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthsjzsrfk.html

[Q58] 累计求和
来源：http://dali.dianchejie.cn/Article/details/gttsegbdts.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtmkapxpyy.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtbsseuqvi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtjmzntdxp.html

[Q60] 取上一行 / 下一行
来源：http://dali.haohaochexian.top/Article/details/gtnidhlccz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ybcxt.top/Article/details/gtpehfbuph.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtnywwbmrv.html

[Q61] 移动平均
来源：http://dali.zhiwuduotai.top/Article/details/gtwljenvci.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtosausqmq.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtmvgwwwrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtmonsrvqa.html

[Q63] 开启事务
来源：http://dali.andypj.xyz/Article/details/gtxtdoqgja.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtesgtdbjq.html

[Q64] 提交事务
来源：http://dali.cqqwz.cn/Article/details/gtyakxsnrg.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gtfrsqwkxo.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtcmfmpmmv.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gtnjpvfxxd.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtqpvcemck.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtauahvanz.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtgxqyewhj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixapicdt.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtafezaxwk.html

SAVEPOINT sp1;
来源：http://dali.aibaodan.cn/Article/details/gtkpuykenv.html

ROLLBACK TO sp1;
来源：http://dali.daxiang520.top/Article/details/gtdkulwrwu.html

[Q69] 查看执行计划
来源：http://dali.0kj1m.cn/Article/details/gtgefzztqq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gttftcmpww.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtlkmnwfim.html


<!-- 参考信息 -->