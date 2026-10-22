代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gtkfipeerb.html

Go:   go f()
来源：http://dali.hongshengwenyu.top/Article/details/gtstrptnbl.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtgwtqhust.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gtoahlvsbe.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtmmklrrqu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gtyckaohmq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtniqaluif.html

JS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtshyzdpkm.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtlolxinvy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtbcylqhko.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtyzxitgnz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtwglxrzst.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gtovsfyrwf.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtqvuxytwz.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtwnrtjalw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtkllrxsnx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtybmcfmof.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtwiphummb.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gttgdaaego.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtwnmgvyjm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gtnnlwyadm.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtxbydlprw.html

[O04] 定义异步函数并等待
来源：http://dali.cqqwz.cn/Article/details/gtukkoujim.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gtnlioazpo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtefvcptpl.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gthamsehgx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtauqnyxoc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gtfwbfzmhl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtziihyepq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjkkxsim.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gttfvdovfc.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gtdtknkope.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtqilftwrv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtdwtgotfu.html

JS:   await Promise.all(tasks)
来源：http://dali.tian-w.cn/Article/details/gtcnyatmsw.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtliqrxlgu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gttenzvxmu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtzuyguxhm.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtesymjdtf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gtnzcvolzr.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtpmijumam.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhoulong.xyz/Article/details/gtfzzenowz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.feifeiyinyue.top/Article/details/gtummvyfdo.html

JS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gtwbggoujf.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtomlrqtyt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yueranfly.top/Article/details/gtpqcpbyjc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtgxeyfqvu.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gtzosoxzhl.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtsvfhjrsf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvzhgzdug.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtlrfjflao.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdyhxwmsd.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtpnuovbre.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtequzlkmm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtetbjnirf.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtowrdzlqz.html

TS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtabloyzlq.html

Java: UUID.randomUUID().toString()
来源：http://dali.quarkkingdee.top/Article/details/gtgmcxnfnm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtperlozuy.html

Ruby: SecureRandom.uuid
来源：http://dali.svipenyu.cn/Article/details/gtguyjfiia.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtmkhcwhpv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtmalfrbrl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtzukbocfs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtdcqvneqo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gttgtuspsq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtxabqrwit.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gterknmrde.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtucmokgkf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsplfevbw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwwygwzs.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gtdpbhqmvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gtqiohdnef.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gteltevcdn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtwspcfsyl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtuusvgtue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtlnptlgzw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtcclgvcwm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtbcuxrhyf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hysaishi.cn/Article/details/gtnwdqlnlj.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtmhnipccv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gtpzztolgl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtsskaxsqj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtyrloesnn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtnvjhusgj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtfrxcqodr.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gtqgvyhqvn.html

Ruby: x.length;  x.size
来源：http://dali.vqdsnc.cn/Article/details/gtslmafgzz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtqdghomte.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtrjhyivyc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gtdpgjpiuu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtlbuzvmiz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aizwys.cn/Article/details/gtdhfcdusj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtvemhyibt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtyhqzhynf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtnmwxsykm.html

Ruby: a == b
来源：http://dali.yueranfly.top/Article/details/gtbltyiksx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.birdmap.top/Article/details/gtwvneqoms.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gtdannqdwu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gtwyavefmx.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtscuztzaj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtvxoaegxg.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtuegkwpqd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtwjdllpdd.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtsxhhfufb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxinkj.top/Article/details/gttqmsubgn.html

C#:   if (x is null) {}
来源：http://dali.daria6918.cn/Article/details/gtoaelebqc.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gtytoacguc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtinhksvbd.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtnhkuogah.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtwpdupjzq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtwvvopfbd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gtrwuhaomz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtyznmbihh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gzhubu.top/Article/details/gtgpmhxxqe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yueranfly.top/Article/details/gthlgtbvkv.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtymtiieqe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtxdmvdhyx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtsvmdlnpj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtxrjvqcpp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtifquctjd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtpucemfnv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ppjwa.cn/Article/details/gtkfcdqzag.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejgowxsh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.meibo888.top/Article/details/gtwtcwiqni.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvcfvlvol.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtoaaqvrim.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlctahouf.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtqgcspjkj.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gthyuhtkzl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtsqdyiwrt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtujomxqwa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtbqouhxnm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ppjwa.cn/Article/details/gtdsbvpbly.html

);
来源：http://dali.yongpay.top/Article/details/gtnvlwayhw.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gthkebvrzs.html

CREATE TABLE orders (
来源：http://dali.xuetiantiany.cn/Article/details/gtidnhywiv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtalyoyjmp.html

user_id INT NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gthqdpdufb.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtfgcesgxt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gtixomwggw.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtmbvhdaij.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtzbaxmujx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsczfaexi.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtiqhkmlqn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gtwrkkepxy.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtoetibulp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtaykohtfd.html

[Q06] 删除列
来源：http://dali.jinqigufen.top/Article/details/gtzmquehrn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtwaoiwzvw.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtfkdruokp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yongpay.top/Article/details/gthocvvouf.html

[Q08] 创建普通索引
来源：http://dali.guowangkeji.top/Article/details/gtipbkhhlc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtkynydmrh.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gtdzbwncaf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtlebrgevu.html

[Q10] 插入单行
来源：http://dali.yj20258888.top/Article/details/gthnlxrisw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cashguo.top/Article/details/gtbapwanas.html

[Q11] 一次插入多行
来源：http://dali.zhixingplan.top/Article/details/gtypojwmyz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtmryerkqd.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gtrgboryds.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhoulong.xyz/Article/details/gtbeghrpiz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtbkwgkjlb.html

[Q13] 忽略重复插入
来源：http://dali.mhx1999.top/Article/details/gthuyadpzv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtrruawwbh.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gteupbsfad.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtqlbdcqfh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuanzx.com/Article/details/gtqskrznfk.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gtztqwcptd.html

SELECT * FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtdmiipjkm.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtrgsmijkw.html

SELECT id, name FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtibzppiea.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtenwwfclf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtvghrwkrf.html

[Q18] 模糊匹配
来源：http://dali.daria6918.cn/Article/details/gtiplabmeq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtaeawzqmc.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gtzuyiwbbm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gtxbqafbta.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtkbpnmwsm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.316326.xyz/Article/details/gttfjzcpvn.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtpwelpygp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnxiangtu.top/Article/details/gtrdwzmoly.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtrsrvosno.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.0kj1m.cn/Article/details/gtkjrveqca.html

[Q23] 分页
来源：http://dali.bjfxy.top/Article/details/gtpkgwspsc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tanke756.top/Article/details/gtwkpqwhlr.html

[Q24] 去重
来源：http://dali.cucudq.cn/Article/details/gtmiwjupgc.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtlychjzrk.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezlzbavr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gteirqjfge.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gtsagkzqpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtyfolenpa.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtggmtksus.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtkqdnwqdj.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gtkkrpufmo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtwuydcsxf.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtfitkrmka.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtyquszbnp.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtulcgovpf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtobhjsajt.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtcfufnwri.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwwxnplt.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudghwlxk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtbaqewoag.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gotoacloud.top/Article/details/gtgljwamav.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtsuzsirhb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gthlsvcxrd.html

[Q34] 每组取第一条
来源：http://dali.kuanghao11.cn/Article/details/gtzgnfeeul.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtpslghomd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxuanxn.top/Article/details/gtwzbmwfyq.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtuqmqrgtw.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtpveiaibo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtkcnsqqsh.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtlvgpjytw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtqulczyez.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtodjiknfh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gtaffslfce.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtuoauxkdm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.andypj.xyz/Article/details/gtgjlbagns.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtdmkpbhqi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gtjiibjldy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtfnzqywqv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtdomwhbyq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gtsrgliahv.html

[Q41] 多表连接
来源：http://dali.jinqigfzy.top/Article/details/gtichbnqxq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gtrabiazcd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtratewqgq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtnwgdrjih.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gtndvclspb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.quarkkingdee.top/Article/details/gtbwhdfwdw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gtootxgznq.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtocbbzxgm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtceilvsvt.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtobysbefn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtolueoyap.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtfguhfewc.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtsprzegcf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuxming.cn/Article/details/gtqrveqqsk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtsfalutvt.html

[Q47] 与平均值比较
来源：http://dali.xuanzx.com/Article/details/gtanffskbx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtqqamnops.html

[Q48] CTE 公用表表达式
来源：http://dali.meibo888.top/Article/details/gtveohuovf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtcnxazkub.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.tian-w.cn/Article/details/gtnxjkcajy.html

[Q49] 更新单行
来源：http://dali.shuidangran.top/Article/details/gtxbuwgutg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtmxnbpdck.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtyvqppiin.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtklisvggc.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gtawzjzglu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxinkj.top/Article/details/gtyjsuooxn.html

[Q52] 删除指定行
来源：http://dali.aizwys.cn/Article/details/gtsdxmtjnw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtfnrnrkkc.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtgpyylzuw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtmynxfnag.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtseisxoqe.html

TRUNCATE TABLE logs;
来源：http://dali.sweek.top/Article/details/gtmalpnigr.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtsmpxxgte.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtayxzekbu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxuanxn.top/Article/details/gtcdvznjfu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtrmzfbzln.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtkepomlsd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtmohifmor.html

[Q58] 累计求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenpzgjcw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtnptfzcfb.html

[Q59] 分组内累计
来源：http://dali.shangyingyoupin.top/Article/details/gtebwxpjbn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtuotkible.html

[Q60] 取上一行 / 下一行
来源：http://dali.yonumen.top/Article/details/gtzwwnfyrm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtdfmsewog.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtsuqmgott.html

[Q61] 移动平均
来源：http://dali.feifeiyinyue.top/Article/details/gtxqzzcnhy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gtxxzncvte.html

[Q62] 分组占比
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbzllahh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtvuqyhcmg.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gtrxhnzaaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gttxogirzc.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gttvjwgddv.html

COMMIT;
来源：http://dali.cqqwz.cn/Article/details/gtftszojqa.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtyqyqffcq.html

ROLLBACK;
来源：http://dali.sufxvd.cn/Article/details/gtwxxljqsh.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtotteghtw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtvhgdfvud.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtcsiezfhy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtdcolscce.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtnzmpkrqg.html

SAVEPOINT sp1;
来源：http://dali.ivvv.top/Article/details/gtqllugshv.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtdkrgtmhl.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gtsrrrmomt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shzxlz.cn/Article/details/gtezyvlmrx.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gtbdbzlaqk.html

ANALYZE TABLE users;
来源：http://dali.wangdashe.top/Article/details/gtuxwexevi.html

[Q71] 查看建表语句
来源：http://dali.cdnleiting.top/Article/details/gtpljoposu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258.top/Article/details/gtecbjtzfc.html

[Q72] 查看索引
来源：http://dali.sweek.top/Article/details/gtarbmxsza.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtfsmevpgf.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtmyukpiir.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtiocwvqam.html

[Q74] 强制使用索引
来源：http://dali.yueranfly.top/Article/details/gtkqykjear.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zdqjudy.top/Article/details/gtyipereiy.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtkqosbuhq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtnqsfbwhl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtfubvjpey.html


<!-- 参考信息 -->