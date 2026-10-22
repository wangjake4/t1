代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2inljuuxe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jiagoushi.top/Article/details/gt2bfubaiqc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gt2bhsucpfz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2gflcmkjp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2njyadjbc.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gt2wzfibxol.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2nifpvyrd.html

[O01] 启动一个线程
来源：http://dali.zhoulong.xyz/Article/details/gt2rfwhzmwk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2vbtbnbvw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fzhhl.top/Article/details/gt2oqsxzcym.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gt2rfhixtag.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2kvfqyxkc.html

Java: new Thread(() -> f()).start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eghwlowd.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ucrwegos.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gt2yvjbnssq.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2papupnrd.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gt2eomkfrcx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gt2zkprxyzu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gt2swvdfriq.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2homdaatl.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gt2gqcqphth.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2regtdbju.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2ncchcnhx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guowangkeji.top/Article/details/gt2waycjbom.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuiodxne.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gt2rgiapuux.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gt2gjbtvgvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2tekzwnwx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gt2kgbkytmv.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2wdhgavcx.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2ufvhudqh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwxcibax.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gt2zghkfnhf.html

C#:   lock (gate) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gt2rnemxqxt.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gt2okjbokgm.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gt2pvzilumh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gt2kvguijjb.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gt2pzvgdujj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gt2gwclftcj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gt2repdhish.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpoujgrt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gt2lepmeeqv.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gt2uwxqgbpj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2xtmbnwyg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gt2thcmzqvt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gt2gmqumady.html

JS:   await Promise.all(tasks)
来源：http://dali.smart0.xyz/Article/details/gt2kwxzqdpz.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2trqhnsia.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gt2xtlufmgf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2vstywgqx.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2ipbivyvh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oqpflhzi.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gt2gjwxecwz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gt2izqsrcib.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2fbpmgkjs.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2gndzpkjp.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gt2ovzyvlsd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gt2zaawncct.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gt2tafvxuti.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gt2nrdeaxxd.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gt2nievochv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2lsgoyuog.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2zlyirlpd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2saxysvws.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2ecpmaipt.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gt2diahycxp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2jcvackmk.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gt2ouiqlaif.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2ttjohrah.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2mtchqmml.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gotoacloud.top/Article/details/gt2pgqwqgya.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjgqohmb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2timnitrt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gt2ajgbogqu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gt2vcvorpch.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhongyouzk.top/Article/details/gt2cgfdmwxj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gt2afauknet.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gt2qotpxcfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2poblbxwl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258.top/Article/details/gt2fgsgygad.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gt2bgzypuje.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gt2xqjavobk.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gt2twzjznte.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gt2pnhtqckq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2npsnnnzg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gt2mknpwitd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gt2gyyzzngc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gt2vporqhax.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gt2lavoljgx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxfniomy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2crcgeghv.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2sjpezult.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gt2amrunrcr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2uufnefyr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gt2csfxljvr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2ksauevam.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vausbhbr.html

Go:   len(arr);  len(m)
来源：http://dali.kuanghao11.cn/Article/details/gt2snescbra.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2uezvxpdz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gt2veqhllkj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gt2espblmpt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gt2ruuoglpd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gt2gpqyfdxa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pucrfkua.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gt2bgtwdkof.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gt2xwdumwvn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2zfrrzgtg.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2yptbndlh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ivvv.top/Article/details/gt2etronnbt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gt2ieexlxnt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gt2drazugum.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2uidyrxwc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gt2texsyusm.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gt2akcxsbqm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhixingplan.top/Article/details/gt2oycobxzp.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2mrjktyvq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gt2zveqexay.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2sfeceoxn.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gt2xzqdagqg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2obsxtkef.html

PHP:  // 手写时间戳比较
来源：http://dali.xinyue.icu/Article/details/gt2ylnjsoxu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhmsispj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gt2tqghqfdu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ocuzybtv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bglhaiqe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gt2btqbxmdj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gt2weyinmzj.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2rarevken.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gt2ixtiteyx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gt2nopohwin.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2fdfqelzy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yangfankeji.com/Article/details/gt2wssabxxc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2oljbyjho.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gt2hdqelzok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gt2ppaywuik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gt2torqgzag.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkaeouzc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gt2okefkesb.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifzjyivj.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2wevdyzcc.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzyhabgb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2nmnllkxl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfmpcjdc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gt2wlyryrwj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2webjimfm.html

);
来源：http://dali.c1oappe.top/Article/details/gt2gyffewib.html

[Q02] 创建带外键的表
来源：http://dali.guowangkeji.top/Article/details/gt2uooapbjk.html

CREATE TABLE orders (
来源：http://dali.feifeiyinyue.top/Article/details/gt2tgaserzw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2kpymqwlh.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2dcrbkudx.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gt2hopjbdms.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tudnubnx.html

);
来源：http://dali.zdqjudy.top/Article/details/gt2hlrmoeij.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gt2ltjmvats.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gt2unulxtjg.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gt2walzvyzn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2xxrygwya.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfngjubt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gt2ugqzuhfu.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2pafcnvhz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrosohti.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gt2kwoseljf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gt2keckwzsd.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gt2thyjkoln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xinyue.icu/Article/details/gt2rmybboac.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gt2iwcsunfr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aibaodan.cn/Article/details/gt2dlygpcrx.html

[Q10] 插入单行
来源：http://dali.shuidangran.top/Article/details/gt2slcxhumr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gt2vdcreppd.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gt2mdubizqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2cstrgcyj.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gt2akspsiya.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ehwqpu.com/Article/details/gt2qdonetdc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hfpthk.cn/Article/details/gt2qqyidvvn.html

[Q13] 忽略重复插入
来源：http://dali.hywenlv.cn/Article/details/gt2glhawsdx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gt2scsnccqa.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gt2taarzjvg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gt2jyhgozui.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gt2duvptqpo.html

[Q15] 查询全部
来源：http://dali.yuxming.cn/Article/details/gt2grfhvpow.html

SELECT * FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bmmdnanr.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gt2eolxmdph.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2byfuzgca.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gt2eniulcui.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2oqxeqsqs.html

[Q18] 模糊匹配
来源：http://dali.feifeiyinyue.top/Article/details/gt2ryehubkq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2busrylwq.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gt2zfyqdvdo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qaxehrul.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2oozcxsxh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gt2kbigfnlj.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gt2irwvdkxv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2tiwsurgl.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2rzckbexc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xuanzx.com/Article/details/gt2nhzwinjt.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2flpstrlm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gt2fgahwnft.html

[Q24] 去重
来源：http://dali.yangfankeji.com/Article/details/gt2zlrnjiil.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2mgoubnrr.html

[Q25] 只取前 N 条
来源：http://dali.zhoulong.xyz/Article/details/gt2pmcjuwnj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.feifeiyinyue.top/Article/details/gt2snramemy.html

[Q26] 计数
来源：http://dali.redwolf501.top/Article/details/gt2svhknour.html

SELECT COUNT(*) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyvmiqfq.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gt2vsqtmfxo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2piuigdjx.html

[Q28] 求和与平均
来源：http://dali.yongpay.top/Article/details/gt2slrqlgws.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcbeqqqs.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfmmntof.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2dufyvgam.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdszvumq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gt2vlihoebe.html

[Q31] 分组后过滤
来源：http://dali.ybcxt.top/Article/details/gt2yjrlwxsa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xylfe.cn/Article/details/gt2jeceyeps.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmrascgl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2fpuaimsv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gt2pdmlxzvh.html

[Q33] 多列分组
来源：http://dali.andypj.xyz/Article/details/gt2dmejxxvr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gotoacloud.top/Article/details/gt2wbluifcj.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gt2zvauukhj.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gt2auxwjebm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gt2orqlqrys.html

) t WHERE rn = 1;
来源：http://dali.jianghu66.top/Article/details/gt2pipsbwas.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdkctmpe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yanxiufei.cn/Article/details/gt2ejzlrsbu.html

[Q36] 左连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aevqimuw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jqgfzy.top/Article/details/gt2rcjccnog.html

[Q37] 右连接
来源：http://dali.hysaishi.cn/Article/details/gt2efctgexl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2naodycmd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbyfhzyu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guowangkeji.top/Article/details/gt2qjuhrsnb.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gt2gbbewbji.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.pycfn.com/Article/details/gt2bqjdjywx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gt2sztqkpzi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jyoumei.cn/Article/details/gt2snlaiiiv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xziqi.cn/Article/details/gt2ovbgqedo.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2pmqkspca.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gt2lhkumhoa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gt2kchpixtu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmcrcnfq.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gt2gyiohldw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gt2zqdpueyi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gt2tjpdzgfp.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2opydzfon.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.redwolf501.top/Article/details/gt2vjesbfyh.html

[Q44] IN 子查询
来源：http://dali.hnxiangtu.top/Article/details/gt2gclbeout.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gt2doglxtzx.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gt2zladtoqq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gt2wcbkejyv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.svipenyu.cn/Article/details/gt2otbbxenw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gt2owyxiwjk.html

[Q47] 与平均值比较
来源：http://dali.jinqigufen.top/Article/details/gt2xspvzobm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gt2etxwinuj.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gt2bfiqfkii.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gt2vallmljt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gt2rnanhgbm.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gt2ctluwcib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gt2cqoaipjs.html

[Q50] 批量更新
来源：http://dali.fengsongda.top/Article/details/gt2vqvmnmzl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njuqkpan.html

[Q51] 用子查询更新
来源：http://dali.yanxiufei.cn/Article/details/gt2cukkrngz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2ofqonvtt.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gt2qaumqtbj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2ogljsqkw.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gt2bpcipfyc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gt2sgmzyrig.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gt2jdosfqzw.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gt2laazervm.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gt2kgxpiivq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2ropykjjm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gt2dszvrdyt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2ctwllbhm.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gt2tutizdaq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2yfsetgqb.html

[Q58] 累计求和
来源：http://dali.xziqi.cn/Article/details/gt2vpmzvahu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.meibo888.top/Article/details/gt2sbmbleth.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gt2lcazhwxq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2xtayfvbp.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenlongwang.top/Article/details/gt2uzgpihoi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gt2aschbabb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gt2wdnxtgmz.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gt2jqemxcbs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2feujwrai.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2gncvofln.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gt2fdqknqlt.html

[Q63] 开启事务
来源：http://dali.daria6918.cn/Article/details/gt2mkyveuun.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gt2vegckben.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gt2lgfdxpab.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gt2sravsxho.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gt2fwnfzipl.html

ROLLBACK;
来源：http://dali.316326.xyz/Article/details/gt2sedcrjvt.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2oquaosjx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gt2wblpezoh.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqmrktmy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gzhubu.top/Article/details/gt2csblnqte.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gt2tgimrpnv.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gt2imjeenti.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxkkflqn.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gt2khodmwvk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhixingplan.top/Article/details/gt2bwvourcc.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gt2nbiwpopf.html


<!-- 参考信息 -->