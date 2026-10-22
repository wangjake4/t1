代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gtcnbahccs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gtwvftgiia.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtftmzvgje.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtkatchsvy.html

Java: new Thread(() -> f()).start()
来源：http://dali.hysaishi.cn/Article/details/gtgmbfgjyr.html

Go:   go f()
来源：http://dali.zhongyouzk.top/Article/details/gtiqhmuhza.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtavequcnn.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtgyugryij.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtckyvavpl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtuaobcfsl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gtzsfrpxlv.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gthbnpeweo.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gtwpgikrpe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtkzcyflsp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvawoobq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtrynbdaxz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanteoytq.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtqvffzwyd.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtcbfqaqwa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gtnqibpsje.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtjkdexkry.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gtkqoffnjg.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtkeawrmlp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtpgytuxvs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtibnpmwpk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgihzugpx.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtiggcmrvm.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtwclgxlkn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtzxaxbbuw.html

JS:   async function f() { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtfsrsuanp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpptedflq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtltrajjlu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtajjztxgt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gteyiiccqw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtfxwxpdvi.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtsvodftam.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtfkzwplbw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gtheumtebz.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsvnuacz.html

TS:   await Promise.all(tasks)
来源：http://dali.svipenyu.cn/Article/details/gtackaqxau.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtuxsrlxjd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtmldbpxru.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtuwggefya.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtmmxvrrrj.html

[O06] 使用进程池
来源：http://dali.shzxlz.cn/Article/details/gtvqrkjvcj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtwugoembb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gtkugacslu.html

JS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtwumajncy.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtvniekmhw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gtulxlrxsj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtifotbfnz.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtqpyliwxj.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtscvpfvpf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgbgggffk.html

P. 常用工具函数
来源：http://dali.birdmap.top/Article/details/gtvjrvnnuo.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthnkxyzdf.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtscutzfin.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gteugykrrp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtxnzmuisd.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtioadpggk.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtusfvxlzy.html

Java: UUID.randomUUID().toString()
来源：http://dali.cucudq.cn/Article/details/gtsjqwfwke.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtporumcwc.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtjzjdidft.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtzotnyisy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gtdkyjzgiy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtyrbhhstz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aibaodan.cn/Article/details/gtkqojhbxy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gtowswjwzn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gtpiuzcgtx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shangyingyoupin.top/Article/details/gtqzdlpvfz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtdsflwayy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtqldnhaad.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gtqxninwdq.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkjiwxcz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtpbmlotlf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtxoxxbbcs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtwsiuzexm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtnrlpilzj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtgnotomld.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfxzuwne.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.chenlongwang.top/Article/details/gtyalymvdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtkfybfihc.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtwsxmigwi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtwoncuhtf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gttkcisrcv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gthitqbwds.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtlgwnnhup.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gteutvhlmf.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeeyegbq.html

Ruby: x.length;  x.size
来源：http://dali.ppjwa.cn/Article/details/gtpceeicww.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gthoixkdyl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtabweecui.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.iojbl.cn/Article/details/gtombaqacz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gtigzfqrwi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrbuonia.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtiyxllael.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtxgbmjywx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtskpavrlp.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gtsriazmin.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gtofmqcavk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sweek.top/Article/details/gtkiwoedic.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtkilmenjm.html

PHP:  if (empty($x)) {}
来源：http://dali.cdnleiting.top/Article/details/gtawbbuvos.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.316326.xyz/Article/details/gtjjnejahp.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtobcqqbtp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gttwfowneb.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gtllimhvck.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtypzyeubo.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtqqmsktjo.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gtmhczxoqz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtjgwnqhob.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtrqcgusen.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtdlcpoobm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtixcjqbfg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gthognjyqa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gtgadmznby.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtntdagvkv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtoaatfhpr.html

[P08] 处理浮点精度问题
来源：http://dali.birdmap.top/Article/details/gtmkstiyvu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gterkkezem.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtiibctend.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hammf.cn/Article/details/gttrytwjby.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gttcrjjwaf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jlsjyb.cn/Article/details/gtyrvlywfn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtwbhntvpm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtqvsahzap.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtlofvuran.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtybsogvac.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtvmnuaqbp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtguojvxpa.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gtvyyacqsf.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gtnlvktopz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtoqcdfzjh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtfwjwdjze.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuanzx.com/Article/details/gtnrqpcxvo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtycgxwdyd.html

);
来源：http://dali.jqgfzy.top/Article/details/gtgmgskxaz.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gtrgcfoazj.html

CREATE TABLE orders (
来源：http://dali.chenjidiqi.icu/Article/details/gtknucvchy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtkdhmtgut.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtcakvbwoo.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtzswfwtwx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gthqwyoyaa.html

);
来源：http://dali.hywenlv.cn/Article/details/gtkoequdbl.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtjjhuswoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gtljzwfssf.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtepafjddw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuanzhike.top/Article/details/gtiwyizpvi.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gtvzgdoqjy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gtebifzwpu.html

[Q06] 删除列
来源：http://dali.zhiwuduotai.top/Article/details/gtdfyuedpo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtlprqlcjf.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtxtnjkjpb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.snrcjt.cn/Article/details/gtkbzwytyw.html

[Q08] 创建普通索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoirfconw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtgwycenhy.html

[Q09] 创建唯一索引
来源：http://dali.316326.xyz/Article/details/gtnvhkfpcc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtnszhvksm.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtroeuduqy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtaoyhtqhr.html

[Q11] 一次插入多行
来源：http://dali.ydzc1.top/Article/details/gtpocrasqg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtfyvyzmex.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gtmqagdztl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.guowangkeji.top/Article/details/gtmcxpdqly.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cdnleiting.top/Article/details/gtqxybraao.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldisqcro.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gtgkbczkzs.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnxiangtu.top/Article/details/gtamlcvteg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtbisupual.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gthfszzaow.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gtnjbndhvp.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrqgcyxvw.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gtnzpajhho.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtzlhpehcy.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtdykwmwkk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtgiipdpmx.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtbategrvi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtxnyixzng.html

[Q19] 范围查询
来源：http://dali.aizwys.cn/Article/details/gtekjffwxi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtdrivjbod.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gtjhxovvso.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gzhubu.top/Article/details/gtciqibnql.html

[Q21] 空值判断
来源：http://dali.dianchejie.cn/Article/details/gtpisxtygh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gtwuagcfpz.html

[Q22] 排序
来源：http://dali.zycfv.cn/Article/details/gtdbswjfdm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gtsutuwcht.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtabvspywt.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.iojbl.cn/Article/details/gtpyjtknzr.html

[Q24] 去重
来源：http://dali.gzhubu.top/Article/details/gtcwcrxnhm.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtegtxoagb.html

[Q25] 只取前 N 条
来源：http://dali.haohaochexian.top/Article/details/gtjhhsiogc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtsuuwcmyq.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtsjbjnija.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtjjhtcamm.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtgxewnckx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtvrsrwayt.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtvjuvinks.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gttgmqthkk.html

[Q29] 最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gtulbhvokv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtsbfavswz.html

[Q30] 分组统计
来源：http://dali.kuanghao11.cn/Article/details/gtxuaendqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gthawuvbpa.html

[Q31] 分组后过滤
来源：http://dali.yangfankeji.com/Article/details/gtukpohwrn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtvxslxlsv.html

[Q32] 分组拼接字符串
来源：http://dali.yonumen.top/Article/details/gtglhrvgek.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtgakdwqcg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gtohxvhrbj.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gtlqlzyige.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinghuilouyu.cn/Article/details/gttwptdbig.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtnkxbxenk.html

SELECT * FROM (
来源：http://dali.nanxuanxn.top/Article/details/gtpbajgvxe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tanke756.top/Article/details/gtjwohvawh.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtplygxbbj.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtgfksuaeq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtohhbwlku.html

[Q36] 左连接
来源：http://dali.jqgfzy.top/Article/details/gtpiyxsidy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtjlzwovfb.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtmxaljrql.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinqigfzy.top/Article/details/gttiipqipw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnxiangtu.top/Article/details/gtowxqiwcl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtrqxeesex.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtlgeywocj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.0kj1m.cn/Article/details/gtqzgrhvsd.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.redwolf501.top/Article/details/gtdbqxhnkv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gtiwxjwgbk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtcszbbozk.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gttxzyuxzg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtzceuozvp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtxgudogfa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xylfe.cn/Article/details/gtgsiipokz.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtnolaoqib.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtajfllmua.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.bjfxy.top/Article/details/gtfrbaysge.html

[Q43] 标量子查询
来源：http://dali.dianchejie.cn/Article/details/gtqvoevybj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtzfvyncbw.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtblnpaflr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hnxiangtu.top/Article/details/gtqyilslxd.html

[Q45] EXISTS 判断存在
来源：http://dali.pengpengdd.cyou/Article/details/gtgkjaroet.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gtemufvkyz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gtrnxhkggj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxdmnvip.html

[Q47] 与平均值比较
来源：http://dali.hfpthk.cn/Article/details/gtjnksomek.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtummntyjb.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gtdjbquktv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtkvgqqwwd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gtmpbvgwew.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gttpndkpdq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtoclqhvgl.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gttenfbbgs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gtgwnuetpa.html

[Q51] 用子查询更新
来源：http://dali.aibaodan.cn/Article/details/gtdzodkpvt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fzhhl.top/Article/details/gthewrpcco.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtfwwhrvlu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hnqzz.top/Article/details/gtzjzdvxpo.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtzhiwoqie.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtmmeqyjsm.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtipqzkwcv.html

TRUNCATE TABLE logs;
来源：http://dali.316326.xyz/Article/details/gtodjiiuwx.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtkelvcspa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.haohaochexian.top/Article/details/gthznsndcx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtwshrsorz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtunmjsipo.html

[Q57] 行号
来源：http://dali.sxryk.cn/Article/details/gtqbovihge.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtumqwpqut.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gttjvpgofh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtfnzpgcqg.html

[Q59] 分组内累计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxhmlsdt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtnkvqqikz.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtqaybxzpr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtzbbopozl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtxinfhdqa.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtemirenws.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtrknoyafv.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gtzpnhgpxz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtwizojqat.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtqdvfmtim.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zdqjudy.top/Article/details/gtcnnoumxq.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtkbsyaxyf.html

COMMIT;
来源：http://dali.haohaochexian.top/Article/details/gtewonyvuc.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtajvtmpwr.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gtyrkwuwur.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gtvlntjgmu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtxcgyhlkx.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtbhedrhzn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzxlqrni.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtfypyfsav.html

SAVEPOINT sp1;
来源：http://dali.kuanghao11.cn/Article/details/gtfdxffszp.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtxgftqxmj.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtsuwfyhrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtnybkitig.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gthlroerod.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtbxizccnk.html

[Q71] 查看建表语句
来源：http://dali.xylfe.cn/Article/details/gtbthievcn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtimquwwyk.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gtmwzvneyg.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtucvwpgca.html

[Q73] 查看表状态
来源：http://dali.sufxvd.cn/Article/details/gtcgrehjmi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.svipenyu.cn/Article/details/gtzttllguk.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gtcjeckdxq.html


<!-- 参考信息 -->