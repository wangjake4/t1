代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gtoftfozky.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gtbmramhfr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gtthyrjavm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gtdpeytjoe.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttptqzrtd.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbvfftpu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdnhfbmjv.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfwtvyvi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtncifnmgb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtwxghgfuy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cheryme.top/Article/details/gtktclqyat.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtagtdqazs.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gthkzusryf.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtkugaujcx.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtbbpxiwgl.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtdxdmfram.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtcypnqaok.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gtkttmmbtq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gtowdvxyqa.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtabpxjpek.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtbyrlobyw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gtqxonnmfp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtnxwmeirk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtocirtksi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtglqsyvmx.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtapmjmwja.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtmchxeixo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtuwimjtlh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtanhhkkpg.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmceveqqd.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gtczepsgvv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtpcsnxwli.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtcwqchlxy.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtflkffjkv.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gtkuricvxr.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtbtphbcwe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ehwqpu.com/Article/details/gtgalaijjc.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtdaptevnc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtffvdpkau.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtxsazvagj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorjasphi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sweek.top/Article/details/gtgnuoqbnb.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtcflyxcdp.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuxming.cn/Article/details/gtsylnppxg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkontyot.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtcdlpghba.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtldxrkzda.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtjchudakz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtaaooxwtm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtlliqtsta.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtzspslhyq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dashuyun.cn/Article/details/gtfmiqkxmq.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gtulubwhjs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gtpjhcazyy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gthkympucd.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtkfrqbaia.html

TS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtafahukxj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtaginuuyz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtpfqngsym.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gtpyjzyvqf.html

C#:   Parallel.For
来源：http://dali.gaohongyu789.top/Article/details/gtolsgjwcw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtccnigstm.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gthkqqvcog.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttfiqflsf.html

[P01] 生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtilrbaudx.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtwtzeqrcp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrmnhnjx.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtsmpmlpau.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtrivmazzq.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gtoowbijud.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtbagiotep.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigfzy.top/Article/details/gtcjlufdrt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtshzgkbqj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gttgeahzir.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtmaihpjoe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtlgrtcdzi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtcwkbrdwt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtvvvdbusp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtwfzvqdwf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gotoacloud.top/Article/details/gtsehbvpte.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gthvwigmfh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gtpwztxqci.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gttylbrozm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gtcneuscca.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gtxllijmbz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtskbfguii.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtqtqhgkzt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtfobfywli.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtrygxmlvj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtgoalbvgu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtnabjxcpu.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gtnfszpcng.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtlkfowlaq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtirlpjbkw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtkkgkawnz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtsuowidcx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtyletodbi.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtgitqhfeq.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtetqygvrz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtrpaiemkb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtwafqfken.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gttbdzugzt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gttohsxooi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtkfrmrrvj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdeefraun.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cdnleiting.top/Article/details/gtceqnupun.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgbuuogq.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtlhanelqm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcvrzxew.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtsnovswkk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gtuwejuzil.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtlqdusu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtfqpkekgo.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gttmcunras.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtubywfxix.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtpckorsai.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gthmsfvnmb.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtrxikbuon.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gtjdemjkvl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gthmattpxo.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtuqkgrjiy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtdmzyfljv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtichdoemz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hammf.cn/Article/details/gtdwtsqrbm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpivtvgee.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gtcjjpdkkt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtcqliafdf.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gtpdobivky.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gtzzihbwbf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ppjwa.cn/Article/details/gtejiobjir.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gtrahhudvq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtgurgysdr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtqtzzuaxk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtnyupvshh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtaffepryf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtdfewvsbd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtosvczfsr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtnjjslyio.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmiswjwky.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gtwinemjap.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtksvfccgb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtgmuurwkg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtgwjitkip.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprhuyfvn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtisorjejc.html

);
来源：http://dali.vqdsnc.cn/Article/details/gtevohmzlo.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtdfhxkvvu.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtbjkjurbr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtfocaihpg.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtrwphhgny.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gtnuudukcb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nanxuanxn.top/Article/details/gtjstykndk.html

);
来源：http://dali.ivvv.top/Article/details/gtccetbidz.html

[Q03] 增加列
来源：http://dali.316326.xyz/Article/details/gtexrfkvbl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gttmrjkfzq.html

[Q04] 修改列类型
来源：http://dali.zhiwuduotai.top/Article/details/gtandxovvf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtfljtfhyx.html

[Q05] 重命名列
来源：http://dali.shzxlz.cn/Article/details/gtxgofpcjj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jqgfzy.top/Article/details/gtmyrfuhbc.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtgkfinjut.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tanke756.top/Article/details/gtojctqjwy.html

[Q07] 删除表
来源：http://dali.yvedp.cn/Article/details/gtektruoda.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gotoacloud.top/Article/details/gtvielkflv.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtiavexaak.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hysaishi.cn/Article/details/gtkwsxsygl.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtyjneaqbd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtyupdqhnh.html

[Q10] 插入单行
来源：http://dali.cheryme.top/Article/details/gtnfpxlwqj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtuinykoab.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtsbhqemji.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.snrcjt.cn/Article/details/gtihyunijy.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxuanxn.top/Article/details/gtbiuowxrb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xylfe.cn/Article/details/gtsywpjgix.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtofwxaoha.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtqayxffdy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtjhotqssw.html

[Q14] 存在则更新（upsert）
来源：http://dali.birdmap.top/Article/details/gttkqunics.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.9152youxi.cn/Article/details/gtunqqtowt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtatsyqkgi.html

[Q15] 查询全部
来源：http://dali.zhengqikj.top/Article/details/gtnjtzynzo.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gthujfovpr.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtaeukembv.html

SELECT id, name FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtjomakhrj.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtyaxpowcz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtaepzqgmz.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtmaelomnd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gtkioclsls.html

[Q19] 范围查询
来源：http://dali.zhoulong.xyz/Article/details/gtcdduipvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gttumtjfqz.html

[Q20] IN 列表
来源：http://dali.smart0.xyz/Article/details/gtdvdmqhvb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.0kj1m.cn/Article/details/gtbzltikii.html

[Q21] 空值判断
来源：http://dali.chenjidiqi.icu/Article/details/gtgrdkixgs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtfkswuuxk.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtimwfbovb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gtasrhanrx.html

[Q23] 分页
来源：http://dali.zdqjudy.top/Article/details/gtizwwucov.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtkqiqxjwt.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtxvrszahc.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gthtykhcji.html

[Q25] 只取前 N 条
来源：http://dali.cucudq.cn/Article/details/gtnhodiept.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pengpengdd.cyou/Article/details/gtfyqbhgdk.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtrvpqzppr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtvoflxhca.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gteapttrkc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtuyvbfopw.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtziihrder.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtgokaesft.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtyeuwqzpx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtcaogxmly.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtekpzdzmd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtfvxurmrk.html

[Q31] 分组后过滤
来源：http://dali.dianchejie.cn/Article/details/gtcdognljf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtvuayslft.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtbjxrneda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtaiatljgv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtipphxkmw.html

[Q33] 多列分组
来源：http://dali.mhx1999.top/Article/details/gtnnkwydvv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtoahsnfih.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzkimsqd.html

SELECT * FROM (
来源：http://dali.smart0.xyz/Article/details/gtrisfwybv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gtximgdica.html

) t WHERE rn = 1;
来源：http://dali.sweek.top/Article/details/gtyolgblay.html

[Q35] 内连接
来源：http://dali.xinyue.icu/Article/details/gtvphfyqhr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtibkutqzk.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gtcrytmpet.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtwatcghuv.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtirrshpts.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtppjohadw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cheryme.top/Article/details/gtmlfrrout.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtvkfmocww.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbvxqpxy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtlkbrihzi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtizuoobee.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gtqqyecdqx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tian-w.cn/Article/details/gtlgnxsrmi.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gtxcnksqag.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jyoumei.cn/Article/details/gtzntowsgc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shzxlz.cn/Article/details/gtnpnkbgbk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.kuanghao11.cn/Article/details/gtnqwyjmcg.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtwepkfplo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtpwsfvxco.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtahiaxsho.html

[Q43] 标量子查询
来源：http://dali.redwolf501.top/Article/details/gtiawrhgkt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtcxyhexfb.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtjusjtiem.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtpblmsoac.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtgmohyatj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtsdqjumhf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtluogdagj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtpndkugpd.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtvxcztkoc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jiagoushi.top/Article/details/gthyzukzbb.html

[Q48] CTE 公用表表达式
来源：http://dali.hnqzz.top/Article/details/gtmlezekzq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gtrkkeuooi.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikeiaiyy.html

[Q49] 更新单行
来源：http://dali.yueranfly.top/Article/details/gtvvrswdrk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtzozpyivw.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtvmzqwwwy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gtbqoqspta.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtxlprtbyl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwphzonl.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtbhtlbdzm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtkhouvnxe.html

[Q53] 按条件删除
来源：http://dali.fengsongda.top/Article/details/gtpyhjzheg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yanxiufei.cn/Article/details/gtekgvtixq.html

[Q54] 清空表
来源：http://dali.zhoulong.xyz/Article/details/gticxrymfd.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtylteuerz.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gtnkpffxde.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtoltstcri.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gttzciqcvv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtbspefglb.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtyxrvmkwu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.bjfxy.top/Article/details/gtzuhrarhk.html

[Q58] 累计求和
来源：http://dali.dashuyun.cn/Article/details/gtpxunidmd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtmbcnlsli.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gticjslhby.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtcmusjenj.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtuihtpgzd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.vqdsnc.cn/Article/details/gtqudzxxtd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxzztjxdn.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtfuwdvqki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtbrusgibl.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gtfmazwhlp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ybcxt.top/Article/details/gtxkviafye.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtpllaxvwt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtwhywohji.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtzkpquzgl.html

COMMIT;
来源：http://dali.yj20258888.top/Article/details/gtffpejgdj.html

[Q65] 回滚事务
来源：http://dali.hongshengwenyu.top/Article/details/gtdzinojjz.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gtykuyijdr.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpovftxmx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteymyneby.html

[Q67] 设置隔离级别
来源：http://dali.snrcjt.cn/Article/details/gtblxtjzzy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtjbpoyxmd.html

[Q68] 保存点
来源：http://dali.birdmap.top/Article/details/gteyfusuie.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtltjaeaoo.html

ROLLBACK TO sp1;
来源：http://dali.havefunace.top/Article/details/gtwgxevwdd.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gttswpiyoq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gthfcalwcr.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtixuhevlr.html


<!-- 参考信息 -->