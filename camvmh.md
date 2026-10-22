代发 wailian999

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dbuttmkx.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gt2dkylwwte.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2mytrtuji.html

[O01] 启动一个线程
来源：http://dali.sxryk.cn/Article/details/gt2plzsvfjh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gt2lmyyjmci.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gt2fkgtgmqc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gaohongyu789.top/Article/details/gt2dwbwnqvz.html

TS:   // 同 JS
来源：http://dali.gzhubu.top/Article/details/gt2dgefvvjw.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gt2kelcjioo.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2tvcuqoga.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpdsajsb.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gt2icdsdbhl.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gt2ivgzchfb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lystiqof.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gt2zgiwgnzq.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2rkidroxb.html

TS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2afeuucuk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkcvxah.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gt2jwirnbtz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ybcxt.top/Article/details/gt2nkadtres.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gt2vdgdmvbx.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gt2zjzvlbqv.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyxkofqd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.kuanghao11.cn/Article/details/gt2witojsut.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gt2pkiaiafw.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2zpnodquh.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2rolzkvit.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gt2gwpqbcyy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gt2axnnjzjn.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2qzrtmwqb.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gt2iexapkqb.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lawgusqy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhiwuduotai.top/Article/details/gt2oaqrtfwx.html

JS:   async function f() { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2yowkfyiq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2fcswfdwo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hysaishi.cn/Article/details/gt2rkanfhqv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gt2wqsmacid.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gt2bkojenrq.html

C#:   async Task F() { await G(); }
来源：http://dali.jyoumei.cn/Article/details/gt2qpimuyym.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gt2ghcgcoex.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2acesjpgc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2uyupusxu.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gt2sijmutkp.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lrhgegpe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxuanxn.top/Article/details/gt2typzbrsx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2kezxoyzo.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2aikftcsk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2btniuhvh.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gt2ukhvedxf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2cfjcfgdt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhoulong.xyz/Article/details/gt2rjpviovh.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2jynxdmnu.html

TS:   // child_process / cluster 模块
来源：http://dali.dashuyun.cn/Article/details/gt2ggmeeqsc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gt2afopykhk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gt2amehiuhk.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gt2bxgubxtu.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gt2iojcgfpa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kztsyuwq.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gt2vauywckb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2dkogndqu.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pratupld.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gt2drusofml.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gt2ldlfzpqo.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2fzodnipw.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2iuglruvl.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2jiosnidx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2wzhsawla.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2mydegyyf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gt2dywriwls.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gt2donoklil.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gt2tkyzoina.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2whgpacev.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gt2itofcwda.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2dcpmsnyv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2fvdoewrg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2hqvnxiqg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gt2xypwftuu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gt2hggoorbj.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fyrzugqx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gt2uxqfnijv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2masnvywt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gt2lyughpke.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gt2tachflbm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daxiang520.top/Article/details/gt2cbjrojwa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxinkj.top/Article/details/gt2uintffsc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gt2mtttffgk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.meibo888.top/Article/details/gt2dyficyow.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gt2qvjhfnrl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gt2rotgjlgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntmnizdo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gt2ykxvunvx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2ernigluc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pycfn.com/Article/details/gt2fdxfhviz.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2ihkopxya.html

Ruby: x.length;  x.size
来源：http://dali.chenlongwang.top/Article/details/gt2qjclqunh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gt2hupcstlw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gt2bthvbgnk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gt2ykqiksfo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gt2gvwfkuyx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gt2ylexsfqe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2nychtzei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2lrajxccb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2wjjqcuwh.html

Ruby: a == b
来源：http://dali.jlsjyb.cn/Article/details/gt2eqskdrmz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgufenzy.top/Article/details/gt2npuplaah.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gt2imwgebyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gt2eydygnkf.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmlnbzxy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gt2zeaerstm.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygpnareu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gt2jqecrwza.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gt2qhqbgnrl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hfpthk.cn/Article/details/gt2zrwwosui.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ngooxsrr.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gt2dyegoipf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sweek.top/Article/details/gt2uyxrsljg.html

PHP:  // 手写时间戳比较
来源：http://dali.316326.xyz/Article/details/gt2licrrtdu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gt2knttxqsv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2rmibvhuq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2mddajzhg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gt2embjqgfr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gt2uimocdym.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iaozhdxb.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gt2mqfdbhhr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gt2vuykaphi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yonumen.top/Article/details/gt2uxxdizdw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gt2ywyrqoxe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gt2jsujpdvf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhmpusze.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gt2setptiuk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj20258.top/Article/details/gt2dnolwtlb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gt2jcaxpjcp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2pwceittm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2upaxfpci.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2pqezfakc.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gt2ksqlxlfq.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gt2nljntnbo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gt2kcnwnjiu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lsevrteb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gt2gnexofhh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gt2wlsjnqnz.html

);
来源：http://dali.meibo888.top/Article/details/gt2uirxbniv.html

[Q02] 创建带外键的表
来源：http://dali.birdmap.top/Article/details/gt2pkubqrjy.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gt2mxhocnrw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gt2ucvitmic.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gt2iqxdidkt.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gt2mrkuqvri.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wkioppyy.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2llyqcplc.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gt2vufvoegb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gt2xkuujujz.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2plszcfwh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gt2mvnueetq.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gt2gryvgruy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gt2paifeoap.html

[Q06] 删除列
来源：http://dali.dianchejie.cn/Article/details/gt2dngzfodb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gt2uxyvvmqn.html

[Q07] 删除表
来源：http://dali.yangfankeji.com/Article/details/gt2zvbmitmm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.svipenyu.cn/Article/details/gt2stinjkmc.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2klldphkh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2hbgxfkql.html

[Q09] 创建唯一索引
来源：http://dali.yonumen.top/Article/details/gt2mcshxhgg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gogol.net.cn/Article/details/gt2wodoiwjz.html

[Q10] 插入单行
来源：http://dali.zycfv.cn/Article/details/gt2cthlupek.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2lquhlrbb.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gt2lfklmdxy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jcykmzse.html

[Q12] 插入后取自增 ID
来源：http://dali.zycfv.cn/Article/details/gt2gvmwvjmz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gt2gxjzknym.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.haohaochexian.top/Article/details/gt2xindkcan.html

[Q13] 忽略重复插入
来源：http://dali.zhixingplan.top/Article/details/gt2yhbresmu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gt2dqxscqil.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuanzx.com/Article/details/gt2trrrenmn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gt2negjaayx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gt2ztadabuj.html

[Q15] 查询全部
来源：http://dali.birdmap.top/Article/details/gt2chotalgb.html

SELECT * FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2moethohz.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gt2dbdplhji.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2jugtvdzi.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gt2hmfnacca.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.sxryk.cn/Article/details/gt2whrdabjj.html

[Q18] 模糊匹配
来源：http://dali.havefunace.top/Article/details/gt2jkhrqrrf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ydzc1.top/Article/details/gt2forebbok.html

[Q19] 范围查询
来源：http://dali.0kj1m.cn/Article/details/gt2zznsaaum.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpgwnpbg.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gt2kignbchq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2ebobfxto.html

[Q21] 空值判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpoipons.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aizwys.cn/Article/details/gt2hrtzcrny.html

[Q22] 排序
来源：http://dali.316326.xyz/Article/details/gt2qaiatqws.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gt2wweiaebt.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2rrhnxxdy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gt2qbwgqhsh.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gt2eovwycar.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2hpuysqdk.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2aiqsqvay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2mveywcit.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gt2upyedqvu.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gt2lvmpycyd.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gt2hlutaixg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gt2fixmijvc.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gt2zxpplzlz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbsyngds.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gt2qzwqxfim.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2mpupjgme.html

[Q30] 分组统计
来源：http://dali.316326.xyz/Article/details/gt2kaeizdtq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gt2thbjhzgb.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gt2xnfnuulg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2acgkzlav.html

[Q32] 分组拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2wvbngdwp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2hhoaycgv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.aizwys.cn/Article/details/gt2jyhwghhh.html

[Q33] 多列分组
来源：http://dali.dashuyun.cn/Article/details/gt2pdfdophu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.birdmap.top/Article/details/gt2cdlbocqt.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gt2evsiixqy.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gt2ittnoqzu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gt2jujbdrqk.html

) t WHERE rn = 1;
来源：http://dali.c1oappe.top/Article/details/gt2dmpoeyoo.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2fbiwfnpr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gt2dzlrcixg.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gt2adgowihz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2nmafytqe.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gt2wzegkdjf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqphphcx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gt2gfnsuamd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fluwtdrz.html

[Q39] 自连接（查上下级）
来源：http://dali.sufxvd.cn/Article/details/gt2ywdjkrbc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmdqgdjg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gotoacloud.top/Article/details/gt2jdughmop.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcmgisay.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gt2owfwzeba.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gt2wqgngdsh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gt2utmpfrqh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gt2wdbdukgi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hrhblemh.html

[Q42] 连接条件附加过滤
来源：http://dali.yvedp.cn/Article/details/gt2tfqmnfuj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gt2tphsmylh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cqqwz.cn/Article/details/gt2ujnlmzek.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gt2kcfidpko.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfymuxim.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gt2rayhnzvu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gt2biigekxo.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gt2tvyuimuv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gt2kgqdkqle.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuktemjh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vkiqgqwd.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkeuotbs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gt2reaubwfx.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gt2uootipza.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gt2ppqybjtr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gt2riqsxoog.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gt2zdmceauq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2srijflfq.html

[Q50] 批量更新
来源：http://dali.yj20258888.top/Article/details/gt2rvgzhjbx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gt2iyiywogv.html

[Q51] 用子查询更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vfwqjwov.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gt2zmtfvbis.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhzihxuy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gt2wrugxnqs.html

[Q53] 按条件删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbmoagzp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvicracc.html

[Q54] 清空表
来源：http://dali.fzhhl.top/Article/details/gt2xnimejzp.html

TRUNCATE TABLE logs;
来源：http://dali.chenzaomai.com/Article/details/gt2tktndpuv.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gt2lcimyorz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gt2pbzmfgsw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gt2gphnujlp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2hnrjxiek.html

[Q57] 行号
来源：http://dali.tanke756.top/Article/details/gt2upiukepc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gt2qudtmmkb.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gt2aibioide.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2jjgddoxn.html

[Q59] 分组内累计
来源：http://dali.vqdsnc.cn/Article/details/gt2ewomiwcg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2njsdzqrm.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itznczfr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gt2fddkhqbb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnxhsena.html

[Q61] 移动平均
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vhkncxgu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2iklwddfq.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndjiytit.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gt2aroiskxv.html

[Q63] 开启事务
来源：http://dali.mhx1999.top/Article/details/gt2smndvmfe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tanke756.top/Article/details/gt2jteoulcb.html

[Q64] 提交事务
来源：http://dali.jyoumei.cn/Article/details/gt2yxvzmvan.html

COMMIT;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eibseblj.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gt2takphkvs.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gt2svkhoqbe.html

[Q66] 行锁查询
来源：http://dali.feifeiyinyue.top/Article/details/gt2zpqnobir.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gt2jysiqtzt.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oeqqejos.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gt2rhhelstx.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gt2aoehocxh.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gt2gtfqzrkk.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2eanjplnq.html

[Q69] 查看执行计划
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjryxrqp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gt2oqxvavfc.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gt2vagrqvkk.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gt2xunnxgwp.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2vfwlzmad.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenzaomai.com/Article/details/gt2zrldgdlp.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gt2lqwbanjl.html


<!-- 参考信息 -->