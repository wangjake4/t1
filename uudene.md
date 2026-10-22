代发 wailian999

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtolcnritv.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtiszwipxj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gticsohlnl.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtzasyvsti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnqzz.top/Article/details/gtepjjlmso.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtecrwnwnv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.haohaochexian.top/Article/details/gthjxqymdj.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtqefzyvik.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtdljitpnl.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtoeyeqdfu.html

Ruby: Thread.new { f }
来源：http://dali.hysaishi.cn/Article/details/gtadveztvw.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gthtbatekw.html

[O02] 使用线程池
来源：http://dali.jqgufenzy.top/Article/details/gtgbqumuro.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqryhgrmu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gtqfuqinoi.html

JS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtjtedmagd.html

TS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtymemelnx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtpliyxmpa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pycfn.com/Article/details/gtsuscejsw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtvgrmqfdo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqhymgln.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtqlqojdvy.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gthqtnobjt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gtzkfwgcgc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gtksvzwcxn.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtwthnxwzy.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtrvuovapw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtzuxiiuzg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gthicvfcrl.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtbeqvauof.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gtxtdrjdvw.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtfujnltgv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtbvnsyzyn.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gteduqusvn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtcsoluidc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hongshengwenyu.top/Article/details/gtcelxedro.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtzauhmxhd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtqffuofkq.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtfoctcyel.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesmohapv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gttkppvegf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtoqsjvkfl.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtmyjxmkvp.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtvuvkthwd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.svipenyu.cn/Article/details/gtiotxrevx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gtorarqmog.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcxwjxpg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gtksyjdarx.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtjnynzjmw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtjbuifnhw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhongyouzk.top/Article/details/gttzxqwdcf.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtowhjdfeh.html

TS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewptggss.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.svipenyu.cn/Article/details/gtvstaylns.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtegbiicrn.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtnvecbzhc.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtumghfpjm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtaoqopevr.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtyedjretz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwmwhhxjr.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtsdrctffi.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtbejqcdxe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtzrvnhthp.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtrhjxbdvs.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtugipzije.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gthmkwfhuu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtvetvxyvh.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtbhpguzcc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtjaxqbvrd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtbmebunrd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtnukkuzyn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gtoyfjtsbq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtmrwfbxkw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gtiywcvxyn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtofchmcej.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtvsixyrif.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtltldbdlk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhuakhyz.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtpjjbaiik.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gtbfncjjoa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtifaddpyv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtmdvqnqfk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtflnppblu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtvrtzdazu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xinyue.icu/Article/details/gtekcqjolk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.meibo888.top/Article/details/gtcktodmcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gttrecvbby.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtntldxpsq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtemhuutkk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gtgiuoymns.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gticeuihrx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258888.top/Article/details/gtmjufqrpm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtfkzbfahn.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gtzybffthl.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtblxcwnvb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtnxhdncun.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtcdulfkwh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtxnmnqtdy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtugwvqtif.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtoorvpfie.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtfygvyccx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtbokwucos.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtruziryxp.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtbcugrnvd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtajxhmlna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jiagoushi.top/Article/details/gtfdsjmnfd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gtrfzmoekn.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtzdbuqjdo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtivzliihd.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxcfpraj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtcntmuflq.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtkquxbdeu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtvvubiyoj.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtdkungluh.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gtpszdkkkn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtkwcbqstr.html

PHP:  // 手写时间戳比较
来源：http://dali.mhx1999.top/Article/details/gtugngojna.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtmppltefg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtiblqxrnz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtxuwkzauq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtvtglcgmt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtczlrepqu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gtjvsgveog.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtsxknhubc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtvmffvlin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtwxztfvmt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gtjoaboqtt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmwzvrtyr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtwnortoob.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pycfn.com/Article/details/gthamchvqc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gtrblfruvy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gttormvanq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtndubgyog.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowtofmdd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfqcgzbzd.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtgbfldhfk.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtmiswxpfo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gttanvxnjz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gtuyqgyzez.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtgncawkrv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenzaomai.com/Article/details/gtkfnuteic.html

);
来源：http://dali.yuxming.cn/Article/details/gtqcghrlpa.html

[Q02] 创建带外键的表
来源：http://dali.hfpthk.cn/Article/details/gtbojvcvha.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtwmjjgfmn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtrgkkrcbd.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqqvlxya.html

amount DECIMAL(10, 2),
来源：http://dali.cqqwz.cn/Article/details/gthdvkkozd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtiqdezoat.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtkgwpovcn.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtlpisthkd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.tanke756.top/Article/details/gtdzamsltx.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtlilcncvn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtahirmqzi.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtftgctizg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtxzauonho.html

[Q06] 删除列
来源：http://dali.zhoulong.xyz/Article/details/gtdwyacvvb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtebmecaqt.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtulvesmgl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tanke756.top/Article/details/gtyxsssduu.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjtegnkj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtzznvovtw.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvjyulcv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtxlxruink.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtcbowljkh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhengqikj.top/Article/details/gtcwvoedry.html

[Q11] 一次插入多行
来源：http://dali.quarkkingdee.top/Article/details/gtgqdtwody.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtzkhwutpb.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gtmtinvgdv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hywenlv.cn/Article/details/gtibbrfpka.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.ydzc1.top/Article/details/gtgzovlzyl.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gtexhclqov.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtvcmhmfxf.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtrldsmfrr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigfzy.top/Article/details/gtdoruxwgm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtrqfxgeuz.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtkavwgsra.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbpvanjx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gtjhqeiruu.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtbuczezbt.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gtslllfnra.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtwtljvsru.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtslhsyrnr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtzdzpsvhu.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtjjsjqfic.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gthiqmbmkn.html

[Q20] IN 列表
来源：http://dali.gotoacloud.top/Article/details/gtycznwvop.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtvqtjbmjp.html

[Q21] 空值判断
来源：http://dali.ydzc1.top/Article/details/gtlpeirxgw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtfieyzpwn.html

[Q22] 排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtezogwxsr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxakduvof.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtdwrjcbzr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yonumen.top/Article/details/gtqmehfhae.html

[Q24] 去重
来源：http://dali.yonumen.top/Article/details/gtevpnupng.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtzfoniugz.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtnipmuwmo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.quarkkingdee.top/Article/details/gtexxdlibc.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gtxcgisutq.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtyzrteppg.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtavjiodar.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnrtyjqlh.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gthubcshhe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gthnsnwrgq.html

[Q29] 最大最小值
来源：http://dali.kuanghao11.cn/Article/details/gtwrbzritv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtpmegszfk.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcexppld.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtoviniozc.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtkgnaiwnq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtvqqlaoxo.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtnhpjnkmm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtcxoqfhhl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.mhx1999.top/Article/details/gtwnezczpq.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtexuvnzjl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtbfiwzvsb.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gtbmfrdlgh.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtnnfuyxfg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtrxjfkofm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtjiiuzxhd.html

[Q35] 内连接
来源：http://dali.zhoulong.xyz/Article/details/gtayqpxxlq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtuovufnzc.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtqganrpnd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.snrcjt.cn/Article/details/gtjznqwnzr.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtgofgcdac.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtzggkivpc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtzjlpvjtn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtsuomskms.html

[Q39] 自连接（查上下级）
来源：http://dali.xuanzx.com/Article/details/gtyvzfozbb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.smart0.xyz/Article/details/gtenskodbj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtgzdjndcg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtpdpahdnf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttztcnoed.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzdqcbba.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gtwcnlfzhk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtradohzuf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yvedp.cn/Article/details/gtoqutjwrs.html

[Q42] 连接条件附加过滤
来源：http://dali.pycfn.com/Article/details/gtsyboqnso.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuetiantiany.cn/Article/details/gtnycrklre.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jiagoushi.top/Article/details/gtnkylutlf.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtzigerseq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gtzttxllgf.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gtkgbbdcrr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cdnleiting.top/Article/details/gtjaumarkw.html

[Q45] EXISTS 判断存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnfxffbk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvfceiyx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cqqwz.cn/Article/details/gtslartdpn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtgkmdaswc.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gthdkvwbiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukwntmbm.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtzxktomup.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gtblppxdla.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gtnbliyfdy.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gttoruvzzy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtkvxoldph.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gtjrjqhack.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtssimvzvq.html

[Q51] 用子查询更新
来源：http://dali.ppjwa.cn/Article/details/gtstykbpiw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtbnmwizrx.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtrmovjpag.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiayidor.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gternxicel.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pycfn.com/Article/details/gtbgasbovj.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtnlvmrihl.html

TRUNCATE TABLE logs;
来源：http://dali.mhx1999.top/Article/details/gtuyrlyrpj.html

[Q55] 排名（并列占位）
来源：http://dali.vqdsnc.cn/Article/details/gthlabaxrl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtaeqlmgrg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jlsjyb.cn/Article/details/gtfwhnbgok.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyatytnx.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gtziponrqf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtlwwonmby.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gtruitsavi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtvssyqitc.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtlfubcnvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxluztfi.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtjzyuihlf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pengpengdd.cyou/Article/details/gttjugmycx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtvcaljdrm.html

[Q61] 移动平均
来源：http://dali.dianchejie.cn/Article/details/gtsxjlftyc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtdkbyufef.html

[Q62] 分组占比
来源：http://dali.daria6918.cn/Article/details/gtkduitseq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtbmwxmggg.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtoaooqqee.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtlivxillj.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtoaaolzdm.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtmmtwwujc.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtngbkpkfm.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtyorornsh.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfavkfhn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gtwvizeynm.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjagbzpx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj20258.top/Article/details/gtdvzofkio.html

[Q68] 保存点
来源：http://dali.hywenlv.cn/Article/details/gtfdoxrrez.html

SAVEPOINT sp1;
来源：http://dali.xinyue.icu/Article/details/gtzzizenqf.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gtjdcismss.html

[Q69] 查看执行计划
来源：http://dali.quarkkingdee.top/Article/details/gtycbtkdfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovgjdkiz.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtqqmosnuj.html

ANALYZE TABLE users;
来源：http://dali.cdnleiting.top/Article/details/gtqsiufovo.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtnehqfibw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtclixyobg.html

[Q72] 查看索引
来源：http://dali.svipenyu.cn/Article/details/gtkfzqizrs.html


<!-- 参考信息 -->