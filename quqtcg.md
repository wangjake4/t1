代发 wailian999

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtczacgcqo.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtlropmwdn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpcleffpy.html

[O01] 启动一个线程
来源：http://dali.shzxlz.cn/Article/details/gtxexrdjza.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtwdczoenm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guannengcc.top/Article/details/gtoycxmxec.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtlprdvfwg.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtjcryhrqw.html

Java: new Thread(() -> f()).start()
来源：http://dali.9152youxi.cn/Article/details/gtaqamokuv.html

Go:   go f()
来源：http://dali.ydzc1.top/Article/details/gtvjgmjzsx.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gthcqtezdk.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gtbyubxbzo.html

[O02] 使用线程池
来源：http://dali.xylfe.cn/Article/details/gtxqygfron.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gtzpmbtrra.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtiupxxmqg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtdhgfsozk.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtvxnjvofs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.quarkkingdee.top/Article/details/gtplvjvwqd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gtcuxsvkvg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtwufbdluj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gthwlmkbij.html

[O03] 加锁保护共享数据
来源：http://dali.cqqwz.cn/Article/details/gtrkghbhpc.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtpsqjgcjv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj202588.top/Article/details/gtyhfhhthd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gthmhyjlyn.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtsumyqhuk.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdkfebky.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtgnrmvqyz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.aibaodan.cn/Article/details/gtqsbylaax.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdfvortnl.html

[O04] 定义异步函数并等待
来源：http://dali.shzxlz.cn/Article/details/gtbblapfac.html

Py:   async def f():⏎    await g()
来源：http://dali.andypj.xyz/Article/details/gteidrpokp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gttnjezxhp.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtkghzutdy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtdkqlusez.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtkyuyrgkh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypzrdyvi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gthohjzjgx.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtqxwgnksc.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtoooctihr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxinkj.top/Article/details/gtolfrocqn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtsmgrbyje.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtdruvsoyc.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gttaytedfh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gttytffdrk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtnttzrifi.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtmhofzpok.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gtwdbaisgo.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gtrjafyiip.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtluymrcvn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gtookofwtf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gttclntgdr.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtnllbrseu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvclctvqb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gtsylwpnzg.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtcjrdxzah.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gtuekvvxmg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtteyawfrd.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gtjfhjmktd.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtonoynpym.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gttxjokvli.html

Py:   str(uuid.uuid4())
来源：http://dali.guannengcc.top/Article/details/gtfdlyeswz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtdvqzdhvb.html

JS:   crypto.randomUUID()
来源：http://dali.cashguo.top/Article/details/gtqaisword.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtbqnrbuko.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtyncqyqly.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtrhhvaitr.html

Ruby: SecureRandom.uuid
来源：http://dali.zycfv.cn/Article/details/gtauecqakg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtdyssxqex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovpviiia.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtooswufem.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgfzy.top/Article/details/gtjmxjjusj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gteqbnjlki.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtdnwznjrm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtglnyayce.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhoulong.xyz/Article/details/gttwxouzpf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsvfosohb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxinkj.top/Article/details/gtkixuinuo.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gtgkrblmqe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenjidiqi.icu/Article/details/gtmwlfyotm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gthyrdzzxp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtzregdkgb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtxczvotvl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtexlsapyq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtqkaqdgzf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiosnisqx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtgmjpgtwy.html

[P04] 求长度
来源：http://dali.ivvv.top/Article/details/gtgqqlfduz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gtdpbeqmjp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtjxqgshtk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtddqetpna.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtelvgxtsk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtolaxcnux.html

Go:   len(arr);  len(m)
来源：http://dali.hammf.cn/Article/details/gtjtnonayd.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gthoeywkyn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gthvlvvugh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gtrasafplv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gthublggos.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sufxvd.cn/Article/details/gtjqafcszb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hfpthk.cn/Article/details/gtplrptekb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gtxfdizzsj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtvffvjggq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtewukwolo.html

Ruby: a == b
来源：http://dali.zhoulong.xyz/Article/details/gtatgdihgb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gthxjijltp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtabktmqln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtbxvsavzu.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtoswhukar.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzcmrfdy.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtqoufldow.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtiiobynod.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtedikbmhj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtkclyrmhs.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtidhzrksg.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtgtkfvsla.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtndhbddry.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gtquqnawod.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtolgwrbrq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtcyfxegmo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtdiiliurb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbrkczhd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtanfqdghf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtpykhfjff.html

[P08] 处理浮点精度问题
来源：http://dali.fzhhl.top/Article/details/gtdctaufrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtbakswywg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtkrpulcij.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtqwuznmim.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtsacpdrwx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hammf.cn/Article/details/gthvmceqnz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gotoacloud.top/Article/details/gtkmyqiwll.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cheryme.top/Article/details/gthomupixl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guannengcc.top/Article/details/gtfwmlpjng.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtgnicmheu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtfrguzihq.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvrwyqooh.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gtwmigpsbq.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpnagfbp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtyirolokn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtouqlcrzy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtlasekuvt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinqigufen.top/Article/details/gtdjyiacph.html

);
来源：http://dali.birdmap.top/Article/details/gtpsbkoqem.html

[Q02] 创建带外键的表
来源：http://dali.hnxiangtu.top/Article/details/gtnfuafmho.html

CREATE TABLE orders (
来源：http://dali.xziqi.cn/Article/details/gtmxxggsqn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtjqsmtpqq.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtuhsaimpe.html

amount DECIMAL(10, 2),
来源：http://dali.zycfv.cn/Article/details/gteitbkrmz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daria6918.cn/Article/details/gtywonuvix.html

);
来源：http://dali.yonumen.top/Article/details/gtoylnhobc.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gtpeytqdku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yuxming.cn/Article/details/gtldvfovuw.html

[Q04] 修改列类型
来源：http://dali.iojbl.cn/Article/details/gtuqynjxzq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gtgyjdmbso.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtbkfnyyyg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yonumen.top/Article/details/gtbbxkwfyt.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxbafdws.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtnadfikcn.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gtxgugpwdd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtbedtzdfi.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtvxtuacyg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.feifeiyinyue.top/Article/details/gtzsvktllw.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gtsrtkihhk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygwfsdzo.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlotbgpgk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtbmijnczp.html

[Q11] 一次插入多行
来源：http://dali.zhiwuduotai.top/Article/details/gtnptwlegc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtcdllmtnz.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtstowgsga.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gogol.net.cn/Article/details/gtqthhdomx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtaodvjvnf.html

[Q13] 忽略重复插入
来源：http://dali.zycfv.cn/Article/details/gtrnvapjej.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtdjfalwnh.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtflylyspn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtyreabask.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.smart0.xyz/Article/details/gtxmxocevf.html

[Q15] 查询全部
来源：http://dali.wangshuangyany.cn/Article/details/gtjgqckzsf.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtluvcfwlq.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtaliquuke.html

SELECT id, name FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gthsyelwzn.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfstllrex.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtiawahugf.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gtzjbjkrwz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ppjwa.cn/Article/details/gtzsrebruf.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtwsjdqdgf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpfgfmwt.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtmzhqllaj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtiggyyzjc.html

[Q21] 空值判断
来源：http://dali.yj20258.top/Article/details/gtrujozmgn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtqympwtza.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtxcfisdes.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhengqikj.top/Article/details/gtknlwumpm.html

[Q23] 分页
来源：http://dali.xuanzx.com/Article/details/gtbwbcuxyr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yueranfly.top/Article/details/gtjooyoodx.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtrcogensc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtrdaczdim.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gtswjcivvm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzekfkbg.html

[Q26] 计数
来源：http://dali.ydzc1.top/Article/details/gtpwaodyot.html

SELECT COUNT(*) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtizxmdnep.html

[Q27] 条件计数
来源：http://dali.cucudq.cn/Article/details/gtmccyvrlx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtmggaefvz.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtrqycfcaj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtjivnplwv.html

[Q29] 最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtirtmxamt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtozsbrson.html

[Q30] 分组统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxxomvrg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtxicpoahh.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtidchznet.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jianghu66.top/Article/details/gtscavjxjr.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtgtmybxqw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtudmjcbjs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtatmqwlth.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gtahdviocn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gtxpcllnvn.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtxytdlhnd.html

SELECT * FROM (
来源：http://dali.chenjidiqi.icu/Article/details/gtyujxpubo.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsjzkbxb.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtawijejiz.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtmefjxbwe.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gttaqleegu.html

[Q36] 左连接
来源：http://dali.bjfxy.top/Article/details/gtofhwbijv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gthnlxkpwx.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtxjonxzwv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtivdecnto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrglsyheu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtogjilfvw.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtqucaiaji.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.dashuyun.cn/Article/details/gtbcqgzdrc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gtccpuadrr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtskfucuhi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.kuanghao11.cn/Article/details/gtuoxrkash.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtucmcuzhj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtppkhugul.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtjbdzppau.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gaohongyu789.top/Article/details/gtrfhhbhrx.html

[Q42] 连接条件附加过滤
来源：http://dali.havefunace.top/Article/details/gtsifgdmyz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtwtbpgfuj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gtmirygrxk.html

[Q43] 标量子查询
来源：http://dali.cdnleiting.top/Article/details/gtajynggdm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtrsfcbwma.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtddikjpry.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xinyue.icu/Article/details/gtooqftumo.html

[Q45] EXISTS 判断存在
来源：http://dali.shuidangran.top/Article/details/gtwrnhwqbh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtmusfmwdu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtpakwtqgx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtxisjnquk.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gtsefgyfde.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tian-w.cn/Article/details/gtmmjkfewc.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gttlcqglnh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gtmaghpkaj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtnssyuvvp.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtalzzflqc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtvastqxjs.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbphhnqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuanzx.com/Article/details/gtnolnjmis.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gtdgxiwpig.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtxekzprgh.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtvfxyxjni.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtidimipnt.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtnxfiokue.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.316326.xyz/Article/details/gtytxicksg.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gtukwpoghr.html

TRUNCATE TABLE logs;
来源：http://dali.cashguo.top/Article/details/gtettenflp.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtjuhaawag.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtcoqhgpgi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258888.top/Article/details/gtluujivfx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.havefunace.top/Article/details/gtlwqeruzv.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtidnxheyr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gtruchucvv.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtvbzpsmug.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtbzdsudty.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gteonppcnb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtzhrkvkoy.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtvkkxcrvj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtftooyrto.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtgcaxcoad.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtskpvyjcu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtexmciavq.html

[Q62] 分组占比
来源：http://dali.yueranfly.top/Article/details/gtgwfyprus.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtyklslxjh.html

[Q63] 开启事务
来源：http://dali.aizwys.cn/Article/details/gtuabdguuc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tianlin.xyz/Article/details/gtwtaqsmlx.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtkekahvct.html

COMMIT;
来源：http://dali.sufxvd.cn/Article/details/gtxphvnayb.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtlxvyxuil.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtnazwmhoc.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gthyhutphw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtzqemxuyi.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtrkqkuadr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtxrzhzgha.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtqhrbkrgn.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtxvkropdk.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtmtquzyyn.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtmkwqswgs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.vqdsnc.cn/Article/details/gtsjijotfq.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtmzgqrdbm.html

ANALYZE TABLE users;
来源：http://dali.zhiwuduotai.top/Article/details/gtgudiyots.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gtwhtbctqn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gtcktrwsuv.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtcwzihffm.html


<!-- 参考信息 -->