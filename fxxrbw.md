代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtlpelcdng.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtiqkcnonp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gtaqrkasoq.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtqaxkcdzt.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtrkxjxhkk.html

Go:   go f()
来源：http://dali.jinqigfzy.top/Article/details/gtozugbycu.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gtdauenahx.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258.top/Article/details/gtyyjpwvgz.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gtypwagant.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gzhubu.top/Article/details/gtndlswyjc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gtwklgukmb.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtrsfbgrkt.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtrcoxcpvm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtjxqcfoqx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtnhebskxd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtnkbekpyp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtpqpyqsxm.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gttlkdcoat.html

Py:   with lock: shared += 1
来源：http://dali.redwolf501.top/Article/details/gtpnkkioeu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtfabxasbe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtpsiybgzz.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtagjfdmlt.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtqhdqeeal.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gtktfnmjxz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtmqghbsps.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gttktfmugf.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gtaefublui.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkujzvdl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtneeufyjk.html

JS:   async function f() { await g(); }
来源：http://dali.ivvv.top/Article/details/gtzkhmkslh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gtwlsmoccx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtedwwzdki.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtapfqcthn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yangfankeji.com/Article/details/gtlzadcdmo.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gtyctasvqm.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtmgstwbbo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtdxkwrqac.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gtwaevvuhk.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtdgxkkqqa.html

TS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gtyvytrbxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gttgmkkkgy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gtdidvgstw.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjtqoxsl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtawmopdca.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtsogyzsqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtftfdnuep.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gtfwmoodxi.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtkafjcdke.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gtxrvcbawp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtlcitfwch.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gtmeumfntt.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtroytvmsg.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gttuhholom.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvmrbxcxp.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtlsxymrjn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtalvolhdx.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gthxnmbyru.html

Py:   str(uuid.uuid4())
来源：http://dali.zhoulong.xyz/Article/details/gtegnxlmiu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.andypj.xyz/Article/details/gtxanixubb.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtctnyxaoz.html

TS:   crypto.randomUUID()
来源：http://dali.jqgfzy.top/Article/details/gturlmjqro.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhixingplan.top/Article/details/gtkkyrkvhp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtmrdsifmh.html

Ruby: SecureRandom.uuid
来源：http://dali.sufxvd.cn/Article/details/gtqtliicta.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtnyqymrob.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gtgbgwguqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.haohaochexian.top/Article/details/gtarsgzalz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtnmeszmzn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gtludwjtal.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtupntmkfx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmwwotzj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gtjsrjgyya.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gtdbnjhmbw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtfnqgnmah.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtgocbgzcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtekivzwfs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhongyouzk.top/Article/details/gtgntcitsf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtkpwtdbpy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtzyyonqgu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gtfkymkosy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtvoicuumy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtprzosgyu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtwlxtbhtn.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gtmuexydhk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtmipcvyqd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcjlcdok.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtubckxevq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtuedxdzvp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtgaiyzcst.html

Go:   len(arr);  len(m)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbpocmphe.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gthtatsuvp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtgrctkuxi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuxming.cn/Article/details/gtcboviwdr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtityswvwo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtsltzqkju.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtodmpmckl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtqmvblvon.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinghuilouyu.cn/Article/details/gtznyszodm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrevcdoi.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtdsyxbagq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.9152youxi.cn/Article/details/gtupmggwxf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gtkvfzrvok.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gtinqkkojz.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtpleqnkum.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtoudujwrx.html

TS:   if (x == null) {}
来源：http://dali.xuanzx.com/Article/details/gtczekpfhq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gttmmskidj.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gthqhhhmvv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gtcxbpjjav.html

C#:   if (x is null) {}
来源：http://dali.fengsongda.top/Article/details/gthdbzfdda.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtljuizcrz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gtekbfiyly.html

PHP:  // 手写时间戳比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpshbumqx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfvjoqxh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gttlkegdog.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtrsoarvtg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gtcpawkoqt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hongshengwenyu.top/Article/details/gtursgdedb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gtedjvluel.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtjcjmrewi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nwbrower.top/Article/details/gthoimtofm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtyapxaxsm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jlsjyb.cn/Article/details/gtgmitmssk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtvnwivmjl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtlkccqmtg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtbreyanup.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtjljmmwbe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gtnxavluix.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjflqamlt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgufenzy.top/Article/details/gtlzlkkdwe.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdmhbqnxn.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtngymtiyd.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtaldwmhqe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtucgaakwm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shuidangran.top/Article/details/gtjulolxsy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gthsdlcnrg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcbwxjkd.html

);
来源：http://dali.shuidangran.top/Article/details/gtlelqttch.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtsgvokyvd.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gtbhubuxsg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtusqvntrn.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gtvvkbisra.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtrxglruix.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hfpthk.cn/Article/details/gtgzcviukc.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gthvgjslso.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjbcmlks.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtxszbswwl.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtllvinxzl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtkmefenkf.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gturlvaqep.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdnocgmu.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtrjilfoxy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtdtrdzawb.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gtawzymvzt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtvrljmcxz.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gtbxlmnypp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtcjanvatj.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gtkshkrwjv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtdcunhayh.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfdopgfq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtbodsubig.html

[Q11] 一次插入多行
来源：http://dali.jqgufenzy.top/Article/details/gtbraasmdf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzaqzjpw.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtotgopkmn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hfpthk.cn/Article/details/gtbxjejemh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtvlarvuwj.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiewdpsk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtvynxwwuo.html

[Q14] 存在则更新（upsert）
来源：http://dali.c1oappe.top/Article/details/gtzogvsobd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtoiiyogtu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zdqjudy.top/Article/details/gtgzbbxuif.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtysgyilnd.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtkcbzdyrh.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtjaixdeit.html

SELECT id, name FROM users;
来源：http://dali.cheryme.top/Article/details/gtmgghaacp.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gtydmntlwo.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtvmcmjypt.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtgwnsbuta.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guowangkeji.top/Article/details/gtqwpkdgyj.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtiqaintak.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtwqdpwkus.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gtctqsqmoi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtfidxabeu.html

[Q21] 空值判断
来源：http://dali.hongshengwenyu.top/Article/details/gtthggnmer.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtcaelnxjn.html

[Q22] 排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxelryac.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gtwnwhhibh.html

[Q23] 分页
来源：http://dali.aibaodan.cn/Article/details/gtbrkmvnzw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtswmdletx.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtuxzddmah.html

SELECT DISTINCT city FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgdicbzrq.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtsgjmwzur.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtqufxihel.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gtksjrpapz.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthkferhnl.html

[Q27] 条件计数
来源：http://dali.jqgfzy.top/Article/details/gtuckwreoy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtskakooya.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gturtrvnlv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtbptaggih.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtavmgcnzy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtmnucdexh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gtngmaeqln.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtzuyvbzif.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gtqvhhtbhk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hysaishi.cn/Article/details/gtempypmuc.html

[Q32] 分组拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtdhlwvyjg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.meibo888.top/Article/details/gtuohevwli.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ivvv.top/Article/details/gtvqnccojm.html

[Q33] 多列分组
来源：http://dali.ehwqpu.com/Article/details/gtebwghjxc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.quarkkingdee.top/Article/details/gtkifuhewz.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtpmglgtqt.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gtqwlhxrlg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yanxiufei.cn/Article/details/gtarnebwcl.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpjqewuzp.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gtcwbfigtp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtcygdbqfa.html

[Q36] 左连接
来源：http://dali.dianchejie.cn/Article/details/gtokkqekhr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtgincyrnb.html

[Q37] 右连接
来源：http://dali.feifeiyinyue.top/Article/details/gtuqsddejq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtspzhuuhb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtxaaiyvdg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtbblgqqno.html

[Q39] 自连接（查上下级）
来源：http://dali.hnxiangtu.top/Article/details/gtjxqiwsab.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtrafbkkcl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shzxlz.cn/Article/details/gtuugmgmui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gtorwomrha.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbzovlfb.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gttwzflbnq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtamovrsgt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtidlplowj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtnjqehtif.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtzchngrxy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtdvfoaouh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtyzoofkpx.html

[Q43] 标量子查询
来源：http://dali.sweek.top/Article/details/gtxqjmxsum.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtdlznjxss.html

[Q44] IN 子查询
来源：http://dali.chenlongwang.top/Article/details/gtctkzysze.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gtetrtjbnf.html

[Q45] EXISTS 判断存在
来源：http://dali.hywenlv.cn/Article/details/gtemelhrih.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtmzonhttq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlrtzcaq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtroddqwsj.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtyajobgxe.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.9152youxi.cn/Article/details/gtkqdmrjej.html

[Q48] CTE 公用表表达式
来源：http://dali.yueranfly.top/Article/details/gttkroxjtk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.tianlin.xyz/Article/details/gtjaqximdh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtvylsvpfh.html

[Q49] 更新单行
来源：http://dali.gzhubu.top/Article/details/gtcigrrofk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtigclfkve.html

[Q50] 批量更新
来源：http://dali.hywenlv.cn/Article/details/gtvjbvhofn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtknnfabcm.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtnbwsewbw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gttddvtogl.html

[Q52] 删除指定行
来源：http://dali.ehwqpu.com/Article/details/gtaaogydrk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sxryk.cn/Article/details/gtgaixojih.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtvrdpjega.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.birdmap.top/Article/details/gtskqpcymd.html

[Q54] 清空表
来源：http://dali.jlsjyb.cn/Article/details/gtlavwaakj.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtpqcsydwo.html

[Q55] 排名（并列占位）
来源：http://dali.snrcjt.cn/Article/details/gtfosiqyed.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xziqi.cn/Article/details/gtylxwkank.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnqzz.top/Article/details/gtlzsofhih.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggwvlhdj.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtivbarika.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgdxombku.html

[Q58] 累计求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikrmyjnn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtoqgmioil.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtlliunroc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtbgvndtxz.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtxpaumkul.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tian-w.cn/Article/details/gtwanqyiis.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnnsbqjg.html

[Q61] 移动平均
来源：http://dali.yangfankeji.com/Article/details/gtaowhxeqg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtfvzjrbnq.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtexvhlfpg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtevhlipek.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmucvwis.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtmsqnkumb.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gtygobntjd.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtcwfysgnr.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gthwxnoxrz.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtwhwamjyw.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzamywaso.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtowfgykay.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtmsjjlwiw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.guowangkeji.top/Article/details/gtfymshbwc.html

[Q68] 保存点
来源：http://dali.guannengcc.top/Article/details/gtbbingfmx.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtywfbojbl.html

ROLLBACK TO sp1;
来源：http://dali.pengpengdd.cyou/Article/details/gtqbksbkqx.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtczhnktnl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtjvbadrov.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtzjclzjbh.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtsllulavm.html

[Q71] 查看建表语句
来源：http://dali.hfpthk.cn/Article/details/gtjtwzhbrq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtoqotwmhd.html

[Q72] 查看索引
来源：http://dali.yongpay.top/Article/details/gtcsrpockw.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtedehslgo.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtlifhmkes.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.fzhhl.top/Article/details/gtqskmvumi.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyqrxmrb.html


<!-- 参考信息 -->