代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gttozogkiy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ivvv.top/Article/details/gtwbklufcn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtxzmxlrkd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gtuulkudxc.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwneuyfyv.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtxzysfzbg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtvhnmxomq.html

[O01] 启动一个线程
来源：http://dali.yj20258888.top/Article/details/gtoagedkec.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.316326.xyz/Article/details/gtkqulgclp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtikwovzfb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtjtkzmsom.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtxceoudjb.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtzquciocz.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtxfjwceyo.html

Ruby: Thread.new { f }
来源：http://dali.tanke756.top/Article/details/gtqfzgqrew.html

C#:   Task.Run(() => F());
来源：http://dali.hfpthk.cn/Article/details/gtflmanvuh.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtplwmwyha.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gtghdqsfni.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmosvovgh.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gthbxplyzz.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gteylzjyzj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gtwxxjyodn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtzgpneksd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cucudq.cn/Article/details/gtvuvdqudb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtngodepkb.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtlujtsegt.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtivqksuxj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaecgfci.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtqfbpjevf.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtbjsvaqgy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtlzcxsdhu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtsbsrshbh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtgfvbhvxl.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtjiaizknp.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtojwgpitx.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gtesjztvcc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtlqykmrgf.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtzxgncqnw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gttgtjzijh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtiapyicgl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtsmmqciew.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gtvdlatbsp.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gthlzllnfv.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtxmgujhsy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gttvnhfnik.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtwnqbvvby.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gttkszpode.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtdvxfyfrx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbggzlaxi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtispeietn.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtcrvqsdiy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtpemmlyon.html

[O06] 使用进程池
来源：http://dali.tianlin.xyz/Article/details/gtxndcqjev.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xinyue.icu/Article/details/gtjeirszlj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pengpengdd.cyou/Article/details/gtytdhzbui.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gtamuqnbvm.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtwlmdmxjf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtgclzlppp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtbigioqhs.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtcyryuwso.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gtazpbspnv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtljgzrdup.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtmwdswacl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtaspqoiex.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtyhfvracn.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gthvyavyjd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtfovmjmua.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gttqyuoiqv.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtamrwhnbi.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gtsrcvyoca.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtrhhelkrn.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtpmuocpsi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangshuangyany.cn/Article/details/gtoxynhsjw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtkfewkxwr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtnruaesod.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtqdbujent.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sxryk.cn/Article/details/gtwytnfkbo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtcuydveiw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtqmwogvei.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gttxiidnyu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gththrdnmc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gthnhyzoav.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtogknbqkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtxregjkig.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gttqgorxed.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtcgxkpmes.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtjjeeqzct.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhixingplan.top/Article/details/gtexsjakie.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gtvppehkjl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtwvjrvbos.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwmglwwy.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gthzutetun.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtqwbjhcql.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtjifnlzvk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gtpksuzsol.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtbwuycwuu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttgqmpmhw.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtlytqdthd.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtbaqeytsq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtbbyqpzjh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtliemubuj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtfoampyab.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tianlin.xyz/Article/details/gteptrkzkg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtyiqrgopr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gttljggren.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtftptotjv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtvkmawadv.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtczwarnlf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ydzc1.top/Article/details/gtqewszdvw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ehwqpu.com/Article/details/gtyksbbtqc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtfzjxrfbr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtoemknluj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtmkqpsldc.html

TS:   if (x == null) {}
来源：http://dali.snrcjt.cn/Article/details/gtfojegome.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.andypj.xyz/Article/details/gtxdfzcsks.html

Go:   if x == nil {}
来源：http://dali.xylfe.cn/Article/details/gthcwbsqbv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtrotlzmep.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gthahahwsc.html

[P07] 防抖与节流
来源：http://dali.jlsjyb.cn/Article/details/gtgnrqrkfw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gtfmiqjfeh.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtrgvtqapa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtbbnvhxtz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aibaodan.cn/Article/details/gthpkwbxxo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gthqvwwuev.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtfebpsmwy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtzkmefkjh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gttlbscbqp.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gttlkwpvkg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gtcuxsnkbc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtgsfvpzhm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hysaishi.cn/Article/details/gtgoeqgves.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gtbpwdcxio.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyeliylc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtwavblwft.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gtnjuanenw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgufenzy.top/Article/details/gtvstvontk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtbiyxhsxa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtlapjiffg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtflrfswdc.html

[Q01] 创建表
来源：http://dali.chenlongwang.top/Article/details/gtfizwfvnj.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtwtpnghoq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtghjcqxai.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtfwoatfog.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gtjmxnjgsb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gtteurmiox.html

);
来源：http://dali.birdmap.top/Article/details/gtsxwiyvds.html

[Q02] 创建带外键的表
来源：http://dali.sysykeji.top/Article/details/gtmaokdwjs.html

CREATE TABLE orders (
来源：http://dali.tian-w.cn/Article/details/gtjgkxvyiq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtjbfyyaui.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtltokhxrp.html

amount DECIMAL(10, 2),
来源：http://dali.zhengqikj.top/Article/details/gtowlyfrzw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gtmfpemnac.html

);
来源：http://dali.hysaishi.cn/Article/details/gtcbaizodt.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtyvjiwaje.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jiagoushi.top/Article/details/gtxvfxqewt.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtojaslqrh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtvgcjvtga.html

[Q05] 重命名列
来源：http://dali.hywenlv.cn/Article/details/gtxmvpljxx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenjidiqi.icu/Article/details/gtatjmhnxf.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gtjbyivpod.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtwmejazfk.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtsrtdjahd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtpbmzwomg.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gttxwjcxeu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gttyezrtbe.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtsoegccvh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtgaptxqtz.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtizfzbnty.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtklymbyhn.html

[Q11] 一次插入多行
来源：http://dali.zhoulong.xyz/Article/details/gtymadgenb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjryfuwb.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gtkwulzozf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtnpektncj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtwvnpzapn.html

[Q13] 忽略重复插入
来源：http://dali.daria6918.cn/Article/details/gtpwwepddz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtrvpsjwap.html

[Q14] 存在则更新（upsert）
来源：http://dali.bjfxy.top/Article/details/gtizkxkega.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gtihlwnpuw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gttnhvqvto.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gtmlzqzqhp.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtwtqrpoxz.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtfiqeapni.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gtlipetvdi.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtespagjhs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jyoumei.cn/Article/details/gtlcjiuosr.html

[Q18] 模糊匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmefrciam.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkmvntqi.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gtceotruyw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtgmomexhs.html

[Q20] IN 列表
来源：http://dali.daxiang520.top/Article/details/gtnwqgxkcr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtsomoijxa.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gthdhompmq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtvvnrifxw.html

[Q22] 排序
来源：http://dali.shzxlz.cn/Article/details/gtqssfnfut.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtyfyqoyub.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gttsqbgisz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtjuitwzdm.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtnvdylctv.html

SELECT DISTINCT city FROM users;
来源：http://dali.cucudq.cn/Article/details/gtjdeqktny.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtscvpbdcj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yanxiufei.cn/Article/details/gtqkmldkuk.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtdgrsyroo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtkwdvjgke.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtfpdoxkhy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtogynabrp.html

[Q28] 求和与平均
来源：http://dali.pengpengdd.cyou/Article/details/gtscjlanab.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtcxovbjho.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtifqcfbxq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtaldpdcsb.html

[Q30] 分组统计
来源：http://dali.nanxuanxn.top/Article/details/gtcarhupdx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gttobbsjgx.html

[Q31] 分组后过滤
来源：http://dali.nanxuanxn.top/Article/details/gtzvmkkijs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtnnalyagv.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtigpwydri.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtirtkvyqp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtwhxrrpal.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gtxbqxfypq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnxiangtu.top/Article/details/gtnbwwdvus.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtirjwbrvd.html

SELECT * FROM (
来源：http://dali.havefunace.top/Article/details/gtkxnxxtvj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gtndqksoln.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtqdajsmkh.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtyydhpsxc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtvwahwucx.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gttkhtpnqc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtbrvwsdoj.html

[Q37] 右连接
来源：http://dali.zhiwuduotai.top/Article/details/gtetdnincv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtuuajreid.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dianchejie.cn/Article/details/gtiorddkwr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gtviivptci.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gtpuanfbqb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj202588.top/Article/details/gtpnpzhzep.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinqigufen.top/Article/details/gtodrqcbpd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gtfixbsyjc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhongyouzk.top/Article/details/gtmqpmirmd.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gturcxdpxz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daria6918.cn/Article/details/gtverdisgs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtmndkzotf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtzpglucpy.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtyhwalwin.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtrckxhusz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.9152youxi.cn/Article/details/gtzhmrxpgg.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtchkmwsle.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangtech.top/Article/details/gtixfvcchk.html

[Q44] IN 子查询
来源：http://dali.dianchejie.cn/Article/details/gtbuehbrzr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gtjtpofhwg.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtsleaimoa.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtenjlvfwa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtdisceoro.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtxrthhxwy.html

[Q47] 与平均值比较
来源：http://dali.c1oappe.top/Article/details/gtcmvmsefn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.quarkkingdee.top/Article/details/gtuuriwxmt.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258.top/Article/details/gtuyaxymsq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gturwfvmoa.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fengsongda.top/Article/details/gtujggdolw.html

[Q49] 更新单行
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrazotqg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtlxknjhwv.html

[Q50] 批量更新
来源：http://dali.yongpay.top/Article/details/gtkiimhqfa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtefodwers.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnemrzar.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtotoajfms.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gtnzwnnwli.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtmpapxvpz.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gtyjuluhek.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtkojcgabd.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtuxbuyoru.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxxlcpcu.html

[Q55] 排名（并列占位）
来源：http://dali.xylfe.cn/Article/details/gtnavcpihb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzguwcyk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtoxxajxhg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gthhvamjvc.html

[Q57] 行号
来源：http://dali.shangyingyoupin.top/Article/details/gtqvkivpbx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gtoicksgej.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtebswodmr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtohoiuzvm.html

[Q59] 分组内累计
来源：http://dali.jlsjyb.cn/Article/details/gtphlufiba.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gttgfwzojd.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtfrssmmgl.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtkegarens.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtuapivctu.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgvijiek.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtxfjkpaui.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtafhupylu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtgdughgwj.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtkeliyfmx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtltgtvrqa.html

[Q64] 提交事务
来源：http://dali.guannengcc.top/Article/details/gtcuhozluf.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtncclzmjm.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gtoiytwrms.html

ROLLBACK;
来源：http://dali.xinyue.icu/Article/details/gtbcrltryt.html

[Q66] 行锁查询
来源：http://dali.shangyingyoupin.top/Article/details/gtoxqnzhkr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sufxvd.cn/Article/details/gtluzpfxpl.html

[Q67] 设置隔离级别
来源：http://dali.meibo888.top/Article/details/gtidvngnnc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gtsslumsta.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtfkubkyap.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtwodtjinz.html

ROLLBACK TO sp1;
来源：http://dali.dashuyun.cn/Article/details/gtfjyxgnnu.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtunptewnb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.fzhhl.top/Article/details/gteyekboei.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gtitiwhfos.html


<!-- 参考信息 -->