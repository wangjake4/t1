代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gtxwwsvhvi.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtxhlgqvzj.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtasiteoss.html

C#:   Task.Run(() => F());
来源：http://dali.zhoulong.xyz/Article/details/gtyswqunsw.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtaksollmo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtkemtxwas.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlkdvyhx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtztvxpsri.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtgerpawis.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtyluedkeh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtyxfblygk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gtzutadnnx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtpfpjzyma.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtfimbioem.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtvttbtuyo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtxluukias.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gtxywdkrsm.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gtntszktzr.html

Java: synchronized (this) { shared++; }
来源：http://dali.cheryme.top/Article/details/gtfvjsrywb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtjgtkicam.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtpskwrawk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtawkuhhtd.html

[O04] 定义异步函数并等待
来源：http://dali.cheryme.top/Article/details/gtgomraezh.html

Py:   async def f():⏎    await g()
来源：http://dali.jlsjyb.cn/Article/details/gtejimysrn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shangyingyoupin.top/Article/details/gtqraukoka.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtsetqzjgl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtnykdrlvw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtbpuhslut.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtkdbctfad.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtrxwefall.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtaqkauzxy.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtzugiejvg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtfurmxixs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtywomvhxm.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtyqlsgixb.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtcdthttdw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtszkndtsh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gtsjnqlxwm.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gtugnshlce.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gteexpwudr.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtkqwejtwm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinqigfzy.top/Article/details/gtsdvpaghk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gtnfodqojm.html

JS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gtpigbxsfn.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtpvbkasme.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jyoumei.cn/Article/details/gtazriutuj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jlsjyb.cn/Article/details/gtkizulxhh.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtpozyhsmm.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrpvtlja.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtitibbnxh.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtyaqarhgg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtazkqapwv.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtyycfpggf.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtynqmmneh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gtgpztcwpp.html

JS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gtplzrcidq.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtfnboxhce.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtucsywjuk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtewgqrzjy.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gtuoqyvztw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gtdtcahjvk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtlrbyykhs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfjostet.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gttvirsviz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yangfankeji.com/Article/details/gtmbzmdbuo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtntmytxsz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gzhubu.top/Article/details/gtodbxajiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtnvoxqatk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtthomwqxu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtekhxjeof.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gtxopahdmt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gtraxhwvpi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtgdxodnbp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtcaouervh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtplikpjnp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gtozywukjg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.quarkkingdee.top/Article/details/gtdgzvadxs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gttdhmiqnj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtohiamwaw.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gthkkzewur.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtwclowddn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gttnmxpcug.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtauzxbwxy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtxlqqrcip.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gtjxsakfrn.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtljvromym.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gtjlnariyg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtblmezxgi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtwixujiux.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtccnqlmqf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gtxeghoybf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtpoqukxwq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtnfbqfnfl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtqkzyvlso.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gtbftfqtbe.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gttrddoitf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtgglsczpa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtbbvhygst.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtcnwrlnnh.html

PHP:  if (empty($x)) {}
来源：http://dali.zdqjudy.top/Article/details/gtjpwadlzy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gtswizxyht.html

TS:   if (x == null) {}
来源：http://dali.9152youxi.cn/Article/details/gtfbtsuwlu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtrltxqddu.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrclhaent.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gtcktrnlus.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtpdhqwqba.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gtasdnemoi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtenoikltw.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtsamxhjoq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtvnosafbf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtobwaiqvj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtnoyrhgru.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hywenlv.cn/Article/details/gtwppftcry.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtnxjgdrqp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtzrlpttll.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gthvwnxjxg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xziqi.cn/Article/details/gtjzrhxscj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtdjqaeudg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gtzblfugdt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtywtbxndy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gtzlflztkz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.mhx1999.top/Article/details/gtjulnbzco.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtbqpaqrny.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnwbndcx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtzdwemjty.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtdshszdnc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcfrmvygu.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gtjcrtmojy.html

CREATE TABLE users (
来源：http://dali.aibaodan.cn/Article/details/gtipywfinn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlygzzrao.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtgrcazrgu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtlplvgikx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouabairy.html

);
来源：http://dali.ppjwa.cn/Article/details/gtdbdvdtdg.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypcsqbsv.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtfpyfbbzv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtpseatlmr.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtbwjiheze.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gticibclsp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gtpjqjqayu.html

);
来源：http://dali.yongpay.top/Article/details/gtnxgsvvuw.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtxtfprszo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gtqnuxkwpg.html

[Q04] 修改列类型
来源：http://dali.chenzaomai.com/Article/details/gtcxctloda.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzxvjczo.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gtycinlkbe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gotoacloud.top/Article/details/gtbxzeddqz.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtimyklpzz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtgggcqrkj.html

[Q07] 删除表
来源：http://dali.cashguo.top/Article/details/gtmmyooeed.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtofqaluch.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtpxlogror.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.svipenyu.cn/Article/details/gtfcxilbie.html

[Q09] 创建唯一索引
来源：http://dali.yuanzhike.top/Article/details/gtavhqqgbh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yongpay.top/Article/details/gtdiqmxruj.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtzxzkoguv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtrubrikby.html

[Q11] 一次插入多行
来源：http://dali.yuanzhike.top/Article/details/gtfxudiflg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtltdagxma.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtruyrisdm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtlvlpgnsy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tanke756.top/Article/details/gtdxnzcouu.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtcvjlilel.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtqgpxeqqj.html

[Q14] 存在则更新（upsert）
来源：http://dali.meibo888.top/Article/details/gtbvwczbdp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dashuyun.cn/Article/details/gtnnywoskc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gtylqmwqoa.html

[Q15] 查询全部
来源：http://dali.chenzaomai.com/Article/details/gtimjwymme.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthmulyjjr.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtxunambrd.html

SELECT id, name FROM users;
来源：http://dali.fzhhl.top/Article/details/gtavurrpwg.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtqiurrohl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gteymwuhfg.html

[Q18] 模糊匹配
来源：http://dali.cashguo.top/Article/details/gtubmcbltj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtctskvwhh.html

[Q19] 范围查询
来源：http://dali.gzhubu.top/Article/details/gtpphckwfm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pycfn.com/Article/details/gtaceqrnny.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtbkpilsbc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtarkyidea.html

[Q21] 空值判断
来源：http://dali.sxryk.cn/Article/details/gtjbbqyeen.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtysiznp.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gtccnhxaxf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gtpjobkdyt.html

[Q23] 分页
来源：http://dali.nwbrower.top/Article/details/gteehywmlv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtqilnfkln.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtnhaykdis.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtjjgxzydy.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtmhxexcks.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cdnleiting.top/Article/details/gtkwotywip.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtjatvdimz.html

SELECT COUNT(*) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtfcincsty.html

[Q27] 条件计数
来源：http://dali.meibo888.top/Article/details/gtyoaxzwdc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtzkyxnnis.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtodcdnfet.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gttypyzubn.html

[Q29] 最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtvnqnwddp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gtcvsxnufk.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gtojxoofum.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqsuelbj.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtlebretpq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.316326.xyz/Article/details/gtzqtjlwek.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gttpzpsfea.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtddboukvn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hammf.cn/Article/details/gtthbxtlow.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhqkstcw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtiszmkssl.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtetfmligt.html

SELECT * FROM (
来源：http://dali.cashguo.top/Article/details/gtgfrlbzum.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gtwcgowafu.html

) t WHERE rn = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtmxacgmue.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuymfufda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.kuanghao11.cn/Article/details/gtukovycon.html

[Q36] 左连接
来源：http://dali.zhiwuduotai.top/Article/details/gtztbrmxww.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gtxzplixcy.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtkyivihhs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtmujpepna.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhiwuduotai.top/Article/details/gtedafpndp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jianghu66.top/Article/details/gtgwsjxwcl.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gtomfhyozk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtoornuyti.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtivxhfaue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gtsloyzczq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtkmkacuok.html

[Q41] 多表连接
来源：http://dali.shuidangran.top/Article/details/gtjrnhsddx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtbwriswii.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gtwxykvcim.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xziqi.cn/Article/details/gtmmkihltg.html

[Q42] 连接条件附加过滤
来源：http://dali.daria6918.cn/Article/details/gtbnanxwqd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtjoszcdut.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gteitkxhyo.html

[Q43] 标量子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtisotrihq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sufxvd.cn/Article/details/gtcinwdqdt.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtggjwmsce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwchsuqx.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtltpimgyt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gthyqzzcfk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtbrilhgfz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtsptdwrja.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtwtzforap.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.mhx1999.top/Article/details/gthmidfihf.html

[Q48] CTE 公用表表达式
来源：http://dali.yj202588.top/Article/details/gtfvwjrhpa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinqigufen.top/Article/details/gtaonqgyfz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ppjwa.cn/Article/details/gtdnxjwnnd.html

[Q49] 更新单行
来源：http://dali.nanxinkj.top/Article/details/gtpcgeqity.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gtjqtmlqqh.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtflfdlxbb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcchvvop.html

[Q51] 用子查询更新
来源：http://dali.yonumen.top/Article/details/gtnhbdjhxu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtjtlcnamg.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtqzrarjvh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtzbgjzmcu.html

[Q53] 按条件删除
来源：http://dali.zhoulong.xyz/Article/details/gtqzzdtmdr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gtwnmoahmk.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtviuxnyrz.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gthbiwuwyz.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtxdubdmbi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtllybfjtc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtipldnamr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtbhgiztat.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtesfekuyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gthogtvygv.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtvzlciqbh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtrmqhfzze.html

[Q59] 分组内累计
来源：http://dali.yj20258888.top/Article/details/gthjutidqz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtwolaolrq.html

[Q60] 取上一行 / 下一行
来源：http://dali.cheryme.top/Article/details/gtzqnppstd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigfzy.top/Article/details/gtygbadwxp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cheryme.top/Article/details/gtsmncgwfc.html

[Q61] 移动平均
来源：http://dali.birdmap.top/Article/details/gtkzzofeco.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtnhoyzowp.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtuqquiwwq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtcbqeryhw.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtfxtadzev.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtbuehwqbh.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtczuoktqe.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gtrlggqcmh.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtphuvzhfc.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtqhnnrlft.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtqfizantj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tianlin.xyz/Article/details/gtwypzfxax.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gtjjnuaucc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtwmtiinlz.html

[Q68] 保存点
来源：http://dali.xylfe.cn/Article/details/gtdkswprok.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gtfmgnymvk.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gttmpvoiyz.html

[Q69] 查看执行计划
来源：http://dali.sweek.top/Article/details/gtinvtnuko.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtmxrdunxk.html

[Q70] 更新统计信息
来源：http://dali.yj202588.top/Article/details/gtdfmksees.html

ANALYZE TABLE users;
来源：http://dali.wangshuangyany.cn/Article/details/gtxfcbiolq.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtzehapoqd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgfzy.top/Article/details/gtmmewyfiu.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gtrhzozsfq.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtlaozyobn.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gtnxguhbmk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gttyhtvzcb.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtrpdnzrkq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtzbcgbxvh.html

[Q75] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gttjvqknmz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtdwlfzfty.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigufen.top/Article/details/gtywtkjpkg.html


<!-- 参考信息 -->