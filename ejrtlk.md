代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gt2fcjonach.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ijglrunz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hxdgwetz.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2tnxiumkm.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gt2rkxjjeee.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gt2ouyqbbbz.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gt2ryhqyemw.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2ddtswgsi.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2waroyzcx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hylmuirs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzmcitf.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2qpfqkjwm.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2khvppstk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gt2xtxkhsql.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gt2rcxjlbnm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2inetzyqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2vjtwevdn.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gt2cqdnjdqw.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2krdvhqlp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gaohongyu789.top/Article/details/gt2urzzvznh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2bfryuido.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gt2skyajfzq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gt2ygmmegqe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gt2nuksvtpg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tian-w.cn/Article/details/gt2womnqbpu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2aqncsjrf.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gt2faytltnn.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2mgzzscne.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gctuqrzg.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gt2bxtxbwye.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2jqcwpmfa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2mmemagvn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2phlhlofi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtfjnodk.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2lgmjsobf.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gt2cnyurvml.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2gvhibzxo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gt2vmzukhes.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2ukcktubc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2lwxgytge.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.316326.xyz/Article/details/gt2fxecgyyx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gt2xjceqghi.html

Ruby: threads.map(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2besfifbm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xkpgeyht.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gt2bzcrmrne.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gt2uvmzhqui.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yonumen.top/Article/details/gt2bvtsfxdl.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2vgmwptwg.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2kvzjgpnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gt2heeogkax.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gt2mexiyoxt.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gt2mkftalqh.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gt2sstgqhyz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2dvxumoty.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2owbbbzpc.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2gzvwueey.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2nvzjimbm.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gt2tqmdfaad.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gt2vqwujelu.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gt2woldulqv.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqonlsup.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gt2ryydyhgj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yangfankeji.com/Article/details/gt2bvkflovf.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2ozcrnjdc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.9152youxi.cn/Article/details/gt2mlxtroyd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gt2yczcnvaf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gt2fuewybvn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gt2fnjdimcb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.c1oappe.top/Article/details/gt2viityvxe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2lpmjxuhl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gt2tssysmmv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2mdpomcaq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2hhhrscok.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cheryme.top/Article/details/gt2pugmllch.html

[P03] 生成短随机字符串
来源：http://dali.tianlin.xyz/Article/details/gt2aqatmerc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gt2woowjsjf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2utmmlufm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ddkftzom.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2xhbultoc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmippvww.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dashuyun.cn/Article/details/gt2xhjgokwl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxylbdkt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.0kj1m.cn/Article/details/gt2lsmyrzoq.html

[P04] 求长度
来源：http://dali.andypj.xyz/Article/details/gt2gyusmfat.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gt2qadmeioh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gt2fdwthkfx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2wdajdtwo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2xeyaefvh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nwbrower.top/Article/details/gt2oipqxwly.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gt2vrhghkvx.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gt2pvmemejp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gt2qrrirvst.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gt2taufrbol.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gt2xmfvqmwz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgufenzy.top/Article/details/gt2kimiwknu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2qbsmwdlp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gt2qrpzpgbq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gt2yfvzfsxi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gt2yipthnek.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gt2zrfxvhfs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2bgyjevll.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gt2hgnatiiu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2yfzdofui.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gt2belrdgad.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gt2lveywajc.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gt2pamcmqxv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gt2cwfxyumi.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nosanycl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgufenzy.top/Article/details/gt2lgvkhqag.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gt2pjttihum.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2lvcqfozw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cucudq.cn/Article/details/gt2svvrfzsm.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gt2aeazpxel.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvuclcsl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2djkjcsod.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fpvsyvzr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gt2svvvufyu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhoulong.xyz/Article/details/gt2mrrwpfrh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2xnjgvghh.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2qddbtrzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2ihdufjfe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2quqqmdue.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2yasxtqyx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2voajcnuq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzwxoedj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gt2iuenazzc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gt2qqyqpzpr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gt2kvokqakx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2vqioxdzs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xuanzx.com/Article/details/gt2jytwbqes.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2oxsyklzy.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gt2tzppmptb.html

CREATE TABLE users (
来源：http://dali.hnxiangtu.top/Article/details/gt2qqiebxqe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gt2mvhymeev.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2jchvawfx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gt2kaovobff.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybwwehue.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nayksqmm.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2cwwoqpvo.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gt2vrprmwva.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gt2zsqkufty.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2isjyhlwp.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gt2iiuimhln.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenzaomai.com/Article/details/gt2ldbfpmvm.html

);
来源：http://dali.9152youxi.cn/Article/details/gt2sneeqmyd.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gt2befwidva.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gt2avmeddva.html

[Q04] 修改列类型
来源：http://dali.gzhubu.top/Article/details/gt2diwrltou.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gt2ihwzezhd.html

[Q05] 重命名列
来源：http://dali.xinyue.icu/Article/details/gt2zjecogjd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gt2wzpcicht.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gt2ncrqmoav.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gt2upvxfobn.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gt2eabmkjya.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gt2tjxtkfmy.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gt2hzkyacwn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrjiscbn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgwgrla.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gt2fcuuqimk.html

[Q10] 插入单行
来源：http://dali.bjfxy.top/Article/details/gt2teanhyyu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2hsiwmyjs.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gt2ucouxaia.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gt2nhakqjtp.html

[Q12] 插入后取自增 ID
来源：http://dali.sweek.top/Article/details/gt2qnxbevnn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.vqdsnc.cn/Article/details/gt2iqvtlqbi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aizwys.cn/Article/details/gt2wqcjdohq.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gt2eawljuuo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gt2oyotuoiw.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gt2vpwmvvvz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gt2nxxximyn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gt2mddbvnik.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gt2eqrykosu.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2bexcqhqu.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gt2rforcqdd.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2klqluhpg.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gt2wwlpqkfj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gt2inkwpprd.html

[Q18] 模糊匹配
来源：http://dali.dianchejie.cn/Article/details/gt2nvemkvob.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzznuzn.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2ssxzgcsg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tanke756.top/Article/details/gt2yrktqvei.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2quyjmscl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gt2gwkfjfsl.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gt2zztpwmbf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuanzhike.top/Article/details/gt2lhbouqgz.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gt2bxymkeqe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zycfv.cn/Article/details/gt2asbafiyd.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gt2esmdztnj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2cbpofcvq.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzfiewrl.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2xfzodayg.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2lshwtmtd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gt2hvgwuxrt.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gt2wsetohox.html

SELECT COUNT(*) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2ysdecmqr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxctuee.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ecovhcqw.html

[Q28] 求和与平均
来源：http://dali.quarkkingdee.top/Article/details/gt2scifwkxr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2aeuauknr.html

[Q29] 最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2jinmfdoa.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2jnphtbty.html

[Q30] 分组统计
来源：http://dali.daxiang520.top/Article/details/gt2hjdskfef.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlxibftl.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2vtgudllp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cucudq.cn/Article/details/gt2hsaccupi.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2davdrvcw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gt2fjlxyoji.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhongyouzk.top/Article/details/gt2rmofagse.html

[Q33] 多列分组
来源：http://dali.tian-w.cn/Article/details/gt2feihwkcp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gt2pekhwkek.html

[Q34] 每组取第一条
来源：http://dali.hnxiangtu.top/Article/details/gt2hfyywwoa.html

SELECT * FROM (
来源：http://dali.gaohongyu789.top/Article/details/gt2xqxgbatv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.smart0.xyz/Article/details/gt2tmaapflg.html

) t WHERE rn = 1;
来源：http://dali.jinqigufen.top/Article/details/gt2fyuxxvia.html

[Q35] 内连接
来源：http://dali.shuidangran.top/Article/details/gt2tzydzxke.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2glxbnjcm.html

[Q36] 左连接
来源：http://dali.xuanzx.com/Article/details/gt2fbrorwnq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2jysmsjyj.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gt2mifmgihi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gt2xdomccgr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.birdmap.top/Article/details/gt2yskbrlpn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gt2ihpyuiog.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gt2gvsvqwuh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shuidangran.top/Article/details/gt2gjikuecd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gt2tqhanphp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gt2uzzinyhz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gt2qcsrditl.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gt2xdvgzzmr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gt2rxrcoylf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxtfkubh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gt2dgrxromr.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gt2qxoeilsx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.meibo888.top/Article/details/gt2rvdzvybt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gogol.net.cn/Article/details/gt2lqnlqhjj.html

[Q43] 标量子查询
来源：http://dali.gotoacloud.top/Article/details/gt2imftrssc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhengqikj.top/Article/details/gt2esynmeri.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gt2nsurvmmd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gt2bcgekqhc.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gt2hldypsne.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qafmrykl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcubbisn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gt2tqawtigu.html

[Q47] 与平均值比较
来源：http://dali.aibaodan.cn/Article/details/gt2rtqiulfr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xinyue.icu/Article/details/gt2fkmqonup.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gt2kldyigem.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqhioswk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenjidiqi.icu/Article/details/gt2kdxhcuhv.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gt2jfsubaya.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2cpscusif.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gt2gmquruiz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.andypj.xyz/Article/details/gt2iivdgbpe.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gt2vfvuwqtc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2ozfdvysw.html

[Q52] 删除指定行
来源：http://dali.sxryk.cn/Article/details/gt2vipntjwb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gt2khfeuyld.html

[Q53] 按条件删除
来源：http://dali.aizwys.cn/Article/details/gt2ufqafofd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gt2iweqsigb.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gt2vwxdivnz.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gt2rvqfrsav.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gt2wlqoserk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gt2xqabbgqx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gt2sxvxtvqm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2okjlxkno.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gt2putplpwc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2wtyphses.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gt2igbzondn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2jyojxutr.html

[Q59] 分组内累计
来源：http://dali.bjfxy.top/Article/details/gt2yvgbzram.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fxmatknt.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gt2ypxvgphp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.chenjidiqi.icu/Article/details/gt2avgimgah.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqscrang.html

[Q61] 移动平均
来源：http://dali.gaohongyu789.top/Article/details/gt2mrhanjha.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2nomcpbzg.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gt2whlatvxr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gt2nidoheww.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2hqkgmmve.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gt2napbacfp.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gt2mvkjefps.html

COMMIT;
来源：http://dali.gzhubu.top/Article/details/gt2iulctlyc.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gt2aqdqdtos.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gt2eixfkavj.html

[Q66] 行锁查询
来源：http://dali.pycfn.com/Article/details/gt2lvnuzedn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gt2psiqglny.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gt2yamdrrdk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2szvtqxpq.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gt2yakkehxy.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gt2mslvnrkx.html

ROLLBACK TO sp1;
来源：http://dali.yvedp.cn/Article/details/gt2trbzblpl.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gt2fsfgdgui.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2puucswim.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gt2kikoclea.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gt2bvpgignk.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gt2xzxhyixv.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sufxvd.cn/Article/details/gt2mfudsnjj.html

[Q72] 查看索引
来源：http://dali.yuanzhike.top/Article/details/gt2fjgrgbzt.html

SHOW INDEX FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2kqjdtqor.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gt2qcufwsbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnmbjxjp.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gt2hxzjhacd.html


<!-- 参考信息 -->