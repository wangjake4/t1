代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gtvkjbbbgm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtejwriboa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtwqvkkbqo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtacrjliht.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtnpaeugbd.html

O. 并发与异步
来源：http://dali.sysykeji.top/Article/details/gtuecsqcic.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtulquohqb.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtusrzcrnr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gthifmeebu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gtugwrhjgx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtscgvplqx.html

TS:   // 同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaaoniin.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyroicebv.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtpbkcrqmw.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtdxwuovht.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtpdjvbrgh.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtarbqdmqk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohlmznit.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gturkrvyea.html

JS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtdgaobjjv.html

TS:   // worker_threads 线程池
来源：http://dali.gzhubu.top/Article/details/gthwkogbvy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daxiang520.top/Article/details/gtiupptkxn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtpzsaidpm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtgwwbbqcf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtqdoasxdv.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtgxbtnbrd.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtlrdptibz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gtbcssacck.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daria6918.cn/Article/details/gtdraejpag.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtbujgozck.html

Java: synchronized (this) { shared++; }
来源：http://dali.tian-w.cn/Article/details/gtxxwjcnbf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrshrijq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtnsbhrthj.html

C#:   lock (gate) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtdefaoiox.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtmsboelgs.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtekuswgjv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtzinbsfzz.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtvhnykzkb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtxqzwkdfw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtdqigzhxd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gtsuvwpybz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gtmgqvdqrt.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtvfobxbbq.html

[O05] 并发执行并等待全部完成
来源：http://dali.fengsongda.top/Article/details/gtssdkxzli.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtcanhuoue.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtkxerpudb.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtmkccnnxr.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtqiosvkry.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtcnuyxxgk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtlftzeryc.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtegpluqwf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdymtkela.html

[O06] 使用进程池
来源：http://dali.xziqi.cn/Article/details/gtrslhixgn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtnrotctdm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ivvv.top/Article/details/gtjdatsidb.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtyeevlviv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtxjoohblu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtsnklbnrb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtqflumgvs.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtcrawoflt.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gtrganogfp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbfhoigkh.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtcjmheric.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtanayveph.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtivzkmqvg.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gtpqgqcaqh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtgyindsyq.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhdibizm.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtnltlgfuo.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtfqfczbsz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtwzjdbgfr.html

Ruby: SecureRandom.uuid
来源：http://dali.ydzc1.top/Article/details/gtghdzmutn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtdcdnxuqh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gtscttmdhr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtmhewwwoo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyefpelo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtdahjboxo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtgkbvlwnv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtwlabhzxc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yangfankeji.com/Article/details/gtqlfdbtku.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtavruxhui.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtzvrstyai.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtprbemavd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtgmwubemu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gteppiokdm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtxfqqkbkh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gttjgvzcpw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tanke756.top/Article/details/gtmrtffufv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuxming.cn/Article/details/gtlyxfflpf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gttlaxgalc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shzxlz.cn/Article/details/gtczqcmrzl.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtxbdfpvsp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtocbkbvsj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtdblhipnf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.havefunace.top/Article/details/gtesnidudc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtjdhnuteg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtguusdmlh.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtoxzzixyc.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtunsdfyqa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gtoaofivoq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtlqzimfck.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gtltidabdi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtgrrayqsc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtaexfrksd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtbkaqilyf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xziqi.cn/Article/details/gtmdhpdxtj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gtwpbwndej.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtwjoohjjp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gturywcyhs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktpvmnay.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gtgqhgfayw.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gttnmablif.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtlgrrgdqk.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtrdsbuglz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtxsjosdah.html

Go:   if x == nil {}
来源：http://dali.yuxming.cn/Article/details/gtzzfjdkyb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ppjwa.cn/Article/details/gtiupbfaiw.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtobnrgsde.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtapsrmgmw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtwgttkwnp.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtyxosdjag.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtqtpnggzk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gtmqwjppoe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtbwbfntdp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guannengcc.top/Article/details/gtjzvxyqgn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtkmtufvxk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gtsokioxzm.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtwspnrwhr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gtjnjlhhnf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtnmwmeult.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtzehqbpun.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtiwoncnbs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtrhcwmtdv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gtyhhelsqs.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guowangkeji.top/Article/details/gtdexojuts.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gtdjufmozj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqigzmyjg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtengzmsom.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvcgykujo.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtkltlmrbi.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gthghdkasc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtcvqxjnlo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gtnrpgrpqp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gthlnsnyvz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ehwqpu.com/Article/details/gtfdvnjtwh.html

);
来源：http://dali.0kj1m.cn/Article/details/gtjbvweeuk.html

[Q02] 创建带外键的表
来源：http://dali.shzxlz.cn/Article/details/gtywqjskpw.html

CREATE TABLE orders (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrnkvvaa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gttlbjfzrf.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtmzbumkjg.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtxlrocqke.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtcircqgxc.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtevhfjcam.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gttixzbajb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtbuusnxlk.html

[Q04] 修改列类型
来源：http://dali.zycfv.cn/Article/details/gthexhsfmh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gthyregyiw.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtmtqyhhvw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yvedp.cn/Article/details/gtkhopoogm.html

[Q06] 删除列
来源：http://dali.bjfxy.top/Article/details/gtspfzblks.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtloycukom.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtiyujorqj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtiucvvuld.html

[Q08] 创建普通索引
来源：http://dali.zhengqikj.top/Article/details/gtwfygujne.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtnatfonqs.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gtwotoonmw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtousqxhkb.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gtzszsunsh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.birdmap.top/Article/details/gtimzzyoyw.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gthgmdlxlf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtaotqfgnv.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtxkjavtsx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtvgmmxfyo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ehwqpu.com/Article/details/gtgrgpmkwv.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gtvjazzgna.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtohzzmpdw.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gtmnmchqrp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtiwfniqom.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ivvv.top/Article/details/gtihxinezy.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtcnollpir.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gteoxyiidw.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtrqzkncio.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtsfoidgoi.html

[Q17] 条件查询
来源：http://dali.zhiwuduotai.top/Article/details/gtszufiufe.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtwgyemama.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gtpcxcprrm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daria6918.cn/Article/details/gtfnziwzdv.html

[Q19] 范围查询
来源：http://dali.yueranfly.top/Article/details/gtjqdwwnxa.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gtcnnsdcmy.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtqmnjpilu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtimmturaz.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gtpoezqinb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtibsvhpkq.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gthoyepqga.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ppjwa.cn/Article/details/gtbulsublc.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gtllauwpxq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.meibo888.top/Article/details/gttajexllc.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtfefhooda.html

SELECT DISTINCT city FROM users;
来源：http://dali.aizwys.cn/Article/details/gtdaqmkilh.html

[Q25] 只取前 N 条
来源：http://dali.yongpay.top/Article/details/gtfawjjhea.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gthyuldmjf.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtdvkizubd.html

SELECT COUNT(*) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtuuqcuwhc.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoevqjpp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtosvjejbb.html

[Q28] 求和与平均
来源：http://dali.hywenlv.cn/Article/details/gtklkzlbwr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdabzkss.html

[Q29] 最大最小值
来源：http://dali.zycfv.cn/Article/details/gtfhgmgtsr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtzdocgiqn.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtesdrsqai.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtatbpcfse.html

[Q31] 分组后过滤
来源：http://dali.svipenyu.cn/Article/details/gtcaqubvvc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.tian-w.cn/Article/details/gtiqfhqutx.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixggdddy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtiwxyagwn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtalooeziw.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gtjfbvakqg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gthjayhmjl.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtirdhelua.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtovxmqjql.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjypzzog.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtfmafivlh.html

[Q35] 内连接
来源：http://dali.chenzaomai.com/Article/details/gtnahgyxlh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtvnlnfcjf.html

[Q36] 左连接
来源：http://dali.xinyue.icu/Article/details/gtdasvhznl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zdqjudy.top/Article/details/gtednmsrcf.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gthlfgtere.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gteolpddqn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gthdcvnpuu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkutymfkf.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtaqtfpmmh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtohixfxxh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuxming.cn/Article/details/gtprlvjdhj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtmhhohkng.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtoexlgndr.html

[Q41] 多表连接
来源：http://dali.zdqjudy.top/Article/details/gtrlbzkmju.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtbhbumbow.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtnmxysqij.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gthhxgsvwl.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtavginmui.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gtzrwknwrq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtsvssphws.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtiddurmqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtehkdeork.html

[Q44] IN 子查询
来源：http://dali.yueranfly.top/Article/details/gtmazdwfrv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtdbrfhkky.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtrnifvoyw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtskpljnse.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtfwgqrkua.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.svipenyu.cn/Article/details/gtkzxtkapt.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gtbfeabozn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.daria6918.cn/Article/details/gtqvhocwra.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtdbxlmeyf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlijjtfx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ydzc1.top/Article/details/gtvmnnurqe.html

[Q49] 更新单行
来源：http://dali.jlsjyb.cn/Article/details/gtblalzmcr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtuqtwotyg.html

[Q50] 批量更新
来源：http://dali.yanxiufei.cn/Article/details/gthigxikqb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gzhubu.top/Article/details/gtnumdvoba.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gthgqnqoay.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtjbrhqguq.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gtqzrylpjl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtwcxgduup.html

[Q53] 按条件删除
来源：http://dali.guannengcc.top/Article/details/gtirmartdf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gthvrxqumb.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtfdedavuz.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gturhdnomn.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtkndehvxz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtoqmrhlqa.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gthfbiczak.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtalmbhzap.html

[Q57] 行号
来源：http://dali.jianghu66.top/Article/details/gtcecitjqs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtowsrcyag.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtglhcrodh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtntdbusft.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtbbnfzycw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotiutmyw.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gtwebjokcw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtenzrrfhr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtqvadaylp.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtimqcbohk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gtkwlfudwy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gtqpqkgqev.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtvzieitor.html

[Q63] 开启事务
来源：http://dali.cheryme.top/Article/details/gtjrnhjuks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtfiojwdez.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtyygxcofp.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtzillhdfy.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gtitqjvdwu.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtdmxmxveo.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtbqlifmtq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtrgykptts.html

[Q67] 设置隔离级别
来源：http://dali.guannengcc.top/Article/details/gtfqxlsorr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltofrqmv.html

[Q68] 保存点
来源：http://dali.jianghu66.top/Article/details/gtbnfiqqkv.html

SAVEPOINT sp1;
来源：http://dali.xziqi.cn/Article/details/gtnwurzmqi.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtukbalfzg.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpbakdww.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gtshbepqvg.html

[Q70] 更新统计信息
来源：http://dali.zhiwuduotai.top/Article/details/gtptzfqqss.html


<!-- 参考信息 -->