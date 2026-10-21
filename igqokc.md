代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtnvfiucha.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xuetiantiany.cn/Article/details/gtyykkksys.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtjpjjhmkz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtzqcwrmob.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtwdscnftt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtnnftexyo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtcjbrcpzk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtjygjqsbh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtggdsibrd.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtzjvbttwe.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwcjlixnp.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtbmonuolo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.0kj1m.cn/Article/details/gtubrbbojs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtuieahzvk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zdqjudy.top/Article/details/gtjnqxjcmm.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtbqqlpdsx.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtpihdoddw.html

Go:   go f()
来源：http://dali.daxiang520.top/Article/details/gtemfxoksv.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtsbwyycpt.html

C#:   Task.Run(() => F());
来源：http://dali.jqgfzy.top/Article/details/gtfbpuhwdy.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtrcfkyavy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gtekwbijbc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtvbzdipgh.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtfxivftbz.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtaopfkbfa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtdykmpwhl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtustcvqps.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtndgkjeof.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtkmvbqrrs.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtwcdepcgg.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtulnnhgeo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangdashe.top/Article/details/gtpaxoeueg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gtkcktffgf.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtowiddtum.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtlsdfbyil.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gtsgicnces.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqejsogd.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtxkfqwywl.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtyardoymu.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtmpszpyjf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtqkquvzqt.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdpepsclz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtvynyxucm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtoomrowwc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtnzfeuxge.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtrarsajkv.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtexbuijcm.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gtnbnydysg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtkqsjshuy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tanke756.top/Article/details/gtmetedffv.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtmtbxczwe.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtdcwdoqeb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtbceepyea.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtwtlwtmir.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtdutvqkil.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtbauqpzty.html

[O06] 使用进程池
来源：http://dali.tanke756.top/Article/details/gtttlyrnay.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtgjmferxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gtlenzcnyh.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtykxzzfwo.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtuiqlxzvy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtlabpwabm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtbgofzmvv.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gttqmfglse.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtsvdffqiu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgydualil.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtflgaegla.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtzwiuegga.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtvxyywvac.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtlsmgowoi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gtqirisdmj.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtlckmhcpl.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzrtthfg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtpeqbutae.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtaizygoul.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtqnrnnwxh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ivvv.top/Article/details/gtpxjsvqai.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gtkyucuhpg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtutlkwubb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtzacrwuyb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtcddoqese.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guowangkeji.top/Article/details/gtvlkpeywo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtcpxiazgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gtudifhise.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtbuvzsxjh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.andypj.xyz/Article/details/gttwqrzlqz.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gtzlqzcdhw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtadjpqhse.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gtfpsvptak.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtzgrwgoak.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtrohwokpn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtikiizshi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guannengcc.top/Article/details/gtlbqhmzwq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtqlwjjsrd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ivvv.top/Article/details/gtkmdwovhh.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtxixtohrk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yueranfly.top/Article/details/gtovofupao.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gtpgjghmfs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtlqzetklg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtdvppnyhk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtqtedzyia.html

Go:   len(arr);  len(m)
来源：http://dali.xziqi.cn/Article/details/gtonyjqvad.html

Ruby: x.length;  x.size
来源：http://dali.tian-w.cn/Article/details/gtosexkvzk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtjwzrterh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtvmhflzro.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtawfsyryy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.redwolf501.top/Article/details/gtuglpadkn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtskxbcdbv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtdxkkjsqq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtfubvteka.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtnbxxvqpg.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gtacybqxws.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gtueveekuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtmzpprwvl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtmwthnxdk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtxprwrxtd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gtynfelttr.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtqjkgnojl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtnnbcocqi.html

Go:   if x == nil {}
来源：http://dali.xuetiantiany.cn/Article/details/gtgfswzscy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtitfbootm.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtbzfwmeww.html

[P07] 防抖与节流
来源：http://dali.jinqigfzy.top/Article/details/gtawulzgcw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtqbepauzv.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtezhntzka.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtmepxefbe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtqycfwsfm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj202588.top/Article/details/gtzmcsbxbx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtbwsdvcqd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtnvgeibob.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gtrvlzcneg.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gtfgiuomvr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtufxpezjb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtrysqstre.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtpairgvbv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtbrjsszmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.aizwys.cn/Article/details/gtaqaztnuv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtiygzetjw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtwbddxpct.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtgocvqthd.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvbhxwtok.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gtsihkdkld.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdhxkhvq.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtlcgmimrd.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gtjzznnwtf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcodzjcp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtdirtayum.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtcnhcwrxe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.feifeiyinyue.top/Article/details/gtgibbbkqu.html

);
来源：http://dali.yvedp.cn/Article/details/gtkguknfda.html

[Q02] 创建带外键的表
来源：http://dali.tian-w.cn/Article/details/gtjhirzvlf.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtjbnkxije.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtflknpndr.html

user_id INT NOT NULL,
来源：http://dali.hnxiangtu.top/Article/details/gtswuyegdc.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtfdrowbyj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtuhmxbveh.html

);
来源：http://dali.0kj1m.cn/Article/details/gtujfplept.html

[Q03] 增加列
来源：http://dali.sxryk.cn/Article/details/gtoqdrjvoq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gttnxepgvl.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwlxnnmu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yangfankeji.com/Article/details/gtnwvqiogy.html

[Q05] 重命名列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxnjnsdk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrskkozw.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gtpoklkkrv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtaaaqctrp.html

[Q07] 删除表
来源：http://dali.jyoumei.cn/Article/details/gtsughjpqa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhoulong.xyz/Article/details/gtmylxyerw.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gttqomhelr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtrhlhxhqv.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtcyjznqbw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cqqwz.cn/Article/details/gtkpbdhrku.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gtbxenvzuv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gtnnklkcsm.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtxsihrfrc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtiulwmfao.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtbqpasvzh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtlqycvgkv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtyohngbig.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtmwertrdl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtchrsucwc.html

[Q14] 存在则更新（upsert）
来源：http://dali.fengsongda.top/Article/details/gtsikqdimd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtviaqroju.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.feifeiyinyue.top/Article/details/gtffbazxcz.html

[Q15] 查询全部
来源：http://dali.smart0.xyz/Article/details/gtljvqjdau.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gteexenofc.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtvrqprghs.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtvetuahjj.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gttdpjobbt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtlbhtbdmh.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtazkvcrly.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtojvpatdz.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gtfqqwshrh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhiwuduotai.top/Article/details/gtopaoeexm.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gticfoqrmg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtfeqimpfj.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtkwmtccao.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtaldcefaj.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtkqdjoogn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtaxtxukwe.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtriagekcp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gtqnrzdndq.html

[Q24] 去重
来源：http://dali.xinyue.icu/Article/details/gtodlpbhex.html

SELECT DISTINCT city FROM users;
来源：http://dali.sufxvd.cn/Article/details/gthhjfkpil.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtjqsmvkgp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ehwqpu.com/Article/details/gtueimnisl.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gtkhrrkqsi.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtevgvcyfz.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gthvnfossf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtalmiwzgp.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gtvqvkwyft.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtmknlzgee.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gtmglbvdri.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gthhgqayyv.html

[Q30] 分组统计
来源：http://dali.bjfxy.top/Article/details/gtsxyorjop.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gtyhkmsvfn.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtkasyusnh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtzvzirrqa.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gttgyyudxk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtiezldhnd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gthocbctfb.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtiqryhdks.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.9152youxi.cn/Article/details/gtutxukaqt.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtveildnvu.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtuagjmxbd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gtbfdvtizw.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtqpjwcefs.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtcrfnqcum.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtymhsglwv.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtximvurhx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtfntxsqtm.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtznkyitxc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yangfankeji.com/Article/details/gthdlusvuk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtzylcjiev.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gtmcpewshc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtxgagnoke.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.svipenyu.cn/Article/details/gtiylgwuzx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtleniiflg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gtddmtmtlg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtbcafbaqs.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtxwhlprwm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtbsuwochg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtqhhjagjg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jianghu66.top/Article/details/gtznskqnmg.html

[Q42] 连接条件附加过滤
来源：http://dali.xinyue.icu/Article/details/gtlkqbudqc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtphfeailz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guowangkeji.top/Article/details/gtgeefahyd.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtijfjzlne.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gteriklqtj.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gtnzhcqjzr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtrtrprokm.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtnnuwjdpj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tanke756.top/Article/details/gtyfqmzryq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhongyouzk.top/Article/details/gthtpzlnsk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtaepsuowl.html

[Q47] 与平均值比较
来源：http://dali.jyoumei.cn/Article/details/gthxkqlhxb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gttdzjpkyj.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtfoaiccao.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtrzocelma.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.mhx1999.top/Article/details/gtsusyoyqn.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtvnzdmhos.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gtgqxyffob.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtampqbdet.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtwsiatbpp.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtriqujbuy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gthycodqog.html

[Q52] 删除指定行
来源：http://dali.gotoacloud.top/Article/details/gtoglprwjq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yonumen.top/Article/details/gtamamfxbx.html

[Q53] 按条件删除
来源：http://dali.tianlin.xyz/Article/details/gtdjwqyzka.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtoykkkqrx.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtxskcowyc.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gthxfbeibg.html

[Q55] 排名（并列占位）
来源：http://dali.havefunace.top/Article/details/gtzurnveuk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtrhmateou.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtxsmrkvrx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtdjfwssdg.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbhwsdyl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gtypnlkjeh.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtzotantsi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtfdizntjq.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtqgxhrwti.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtwsobzwep.html

[Q60] 取上一行 / 下一行
来源：http://dali.havefunace.top/Article/details/gtxhupzvuc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hammf.cn/Article/details/gtxaqjsbip.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gttpyxqyhz.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gtsqgdwmlq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtwmtgimfh.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtaidmqlgy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtmrapcqyw.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtaytzcqwr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gtasnnurzs.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtnvztzkor.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtodssjzwn.html

[Q65] 回滚事务
来源：http://dali.ppjwa.cn/Article/details/gtalzqgxqe.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtdtivxbls.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gthlbndflt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtvukbljog.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklyhkivp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pycfn.com/Article/details/gtipqpwvlf.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtyxqcihiy.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtggdvnuky.html


<!-- 参考信息 -->