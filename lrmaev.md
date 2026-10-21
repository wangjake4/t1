代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.zycfv.cn/Article/details/gtatbmabws.html

Go:   go f()
来源：http://dali.jqgufenzy.top/Article/details/gtpliaizzz.html

Ruby: Thread.new { f }
来源：http://dali.sxryk.cn/Article/details/gtwrccfljz.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtgbpwvsev.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtwutkcgxx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtythkwwws.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gtqlxudxvr.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtdgtujlwl.html

TS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtklqkcpys.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gtxiyysuqr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtutsunzii.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtpdobaezr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dianchejie.cn/Article/details/gtblfsrkmi.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtlikgzhkx.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gtcevqxsbb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hfpthk.cn/Article/details/gtsacxffti.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gtvsosragw.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtnllhrghg.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gthjpmrdyn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fzhhl.top/Article/details/gtwsbfxvkq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gtbumdslqu.html

C#:   lock (gate) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gthvhddskz.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtidswavrx.html

Py:   async def f():⏎    await g()
来源：http://dali.pengpengdd.cyou/Article/details/gtigbntbit.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fengsongda.top/Article/details/gtyfyitzex.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtrbnehwri.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.andypj.xyz/Article/details/gtvybhguzj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtwslevslp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkbsvprn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtslmydhet.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtsukumdfs.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtepejaatc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gaohongyu789.top/Article/details/gtcleefwsv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtgymaoxfk.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtxmeypuld.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtijelaupe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.aizwys.cn/Article/details/gtougpecoe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.birdmap.top/Article/details/gtigafkhvp.html

Ruby: threads.map(&:join)
来源：http://dali.yuxming.cn/Article/details/gtabuerpiq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gttnneohcf.html

[O06] 使用进程池
来源：http://dali.guannengcc.top/Article/details/gtqrykqohm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtkfnfznzy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtvbrjahic.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtackhosbz.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtzlqsxlee.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtgjpvzmug.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtchhsasky.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtpzudgdcr.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtcczgyadh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmpwdkciq.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gttoppgefn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtivelebsh.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtyoapzmjv.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gthoambswa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shuidangran.top/Article/details/gtalulgror.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtatgrqayw.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtnrocufvb.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtcobxbrgm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtdijazfsv.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtbpkccokc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtwuzvqrpi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtroleqgew.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gthsynvnke.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtvxxiczdk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gterqvarvu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.quarkkingdee.top/Article/details/gtddkbkfvz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtxssnqrfg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtckqxyxze.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnqzz.top/Article/details/gtsztmajqu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtfpohnvqw.html

[P03] 生成短随机字符串
来源：http://dali.xziqi.cn/Article/details/gtypyjarpf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gtcvsvvcsm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sufxvd.cn/Article/details/gtgricjkre.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gtjzsqexol.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtzdkezwuq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gtxridqhzb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtbojfljgr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtienlrtvn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtejsctqsx.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtgxagzfco.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yuanzhike.top/Article/details/gtatbhmizl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtmkjaaabh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtmafqfjoc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtoowtezbi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gtpqjotwiz.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtcaocitbq.html

Ruby: x.length;  x.size
来源：http://dali.jlsjyb.cn/Article/details/gtposoklsg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gtwfbwgrjv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jqgufenzy.top/Article/details/gtsofkrlai.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.fzhhl.top/Article/details/gthschsfnp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gtyipmhgut.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtmjaoibce.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cheryme.top/Article/details/gttoeirshn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gtlpziyopa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.smart0.xyz/Article/details/gtizzintyy.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtcqhzooiu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gtqchqqhlp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtlxyydkhn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtwxkrbjki.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtyoqvycun.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtdbquwmsy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gtzcwqxjmu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbidsedf.html

Go:   if x == nil {}
来源：http://dali.havefunace.top/Article/details/gtqppbkggg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gtqktgatde.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtyvbqctxq.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtwvsbwibv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fzhhl.top/Article/details/gtmiaukvzf.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtyuaeanqe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtzlnqfxep.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtlzvkuybe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtotkncbhg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqbemghm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtrycvpdnu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtscovtvar.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtezfixyeu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gteatqerev.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gtotvrihfl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtijrbqxlm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtdjismasx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ydzc1.top/Article/details/gtrjoftkph.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtnjjgyhcj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtyreoiunp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtvjjvnite.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmjsfxofl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.feifeiyinyue.top/Article/details/gtrhlmmefc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqhlbuovf.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gteofanygy.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gtvoflspjt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gtyoiybwvd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtwansswig.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenjidiqi.icu/Article/details/gtqkdohvqr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtacvetbyg.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtbpylnuvu.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gtzxtxkltu.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtumxpuzeq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtxcvftozc.html

user_id INT NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gtgoxdhrsv.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gttxdkiuzz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gthsjxjvek.html

);
来源：http://dali.ybcxt.top/Article/details/gthlzdegde.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gttnnlpefr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gaohongyu789.top/Article/details/gtatslqeno.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtcqkikgwc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gtpmsyddfx.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtsgrqgxay.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tanke756.top/Article/details/gtqkobkogb.html

[Q06] 删除列
来源：http://dali.feifeiyinyue.top/Article/details/gtfgykqjru.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sysykeji.top/Article/details/gtndjijtek.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtlymycltv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenlongwang.top/Article/details/gtgyrviufw.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwfykafm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtumrdgddu.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gtxcpbuafl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfspzttq.html

[Q10] 插入单行
来源：http://dali.zhengqikj.top/Article/details/gtxuybrcig.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtuenzsnmz.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gtmkldyueh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtindgonry.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtfshikkdo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtldhrjckh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtaviszpby.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtgxotikpb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtygvtwwfo.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtvngqptyi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gtsgdcmonz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gtrrlmeawo.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gtkiepqzld.html

SELECT * FROM users;
来源：http://dali.yueranfly.top/Article/details/gtpfcgzmzt.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gtoxaskkjg.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtpaidoxet.html

[Q17] 条件查询
来源：http://dali.aizwys.cn/Article/details/gtkedecrqd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtvrwadvni.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtsebmdaro.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hfpthk.cn/Article/details/gtojbhsazp.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtiqyunzdj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqhcatxy.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtcrooafsw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvlybsei.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtjwriilql.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.bjfxy.top/Article/details/gtxxvfeujv.html

[Q22] 排序
来源：http://dali.zhengqikj.top/Article/details/gtvmxwoeuk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.aizwys.cn/Article/details/gtxydfqdez.html

[Q23] 分页
来源：http://dali.pengpengdd.cyou/Article/details/gtlmjpzhgv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekipaktv.html

[Q24] 去重
来源：http://dali.daxiang520.top/Article/details/gterziybbc.html

SELECT DISTINCT city FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtxprveiav.html

[Q25] 只取前 N 条
来源：http://dali.jiagoushi.top/Article/details/gtqelcupan.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtrwhuwhjz.html

[Q26] 计数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwwuvdhf.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtaxclqxev.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtvruoxyjb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtyoxtuf.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtjnwaybch.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtuwgbeprq.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gtddwfrrrq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tian-w.cn/Article/details/gteqsplxyg.html

[Q30] 分组统计
来源：http://dali.sysykeji.top/Article/details/gtmlivahnf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtuftdtnpy.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gtikvfcsid.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gttyiduquy.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtgdpvscvb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtupsivvlv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtanzfetvt.html

[Q33] 多列分组
来源：http://dali.guannengcc.top/Article/details/gtdzkfdrer.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cqqwz.cn/Article/details/gtdracrwkg.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtdzrzwbum.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtfnwkwypc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gteffzgyzb.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtshkbpbje.html

[Q35] 内连接
来源：http://dali.xziqi.cn/Article/details/gtfhxuxwmb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtbcigakhu.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtwhidwhrh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gtthwauswl.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtlkwpmhvh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gthftzfyjr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtqxyczabg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtutegbtga.html

[Q39] 自连接（查上下级）
来源：http://dali.kuanghao11.cn/Article/details/gttcithdtx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspspdojo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtziwxaqbk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtoaydpqrm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ppjwa.cn/Article/details/gtgvmhcfpg.html

[Q41] 多表连接
来源：http://dali.316326.xyz/Article/details/gtkvjrutjr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpsccmie.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtfambgjty.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gtrlsonnwi.html

[Q42] 连接条件附加过滤
来源：http://dali.ppjwa.cn/Article/details/gtesvtmbnn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtvyhlhyzq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xziqi.cn/Article/details/gtbmqdkkhn.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtzwdycfxz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtefqxjgyq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gttwcqfsaw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtyzqifksq.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtmrbprrap.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtdakwfrzk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtgcbktzve.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gtiiasebrr.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtapupnzow.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ehwqpu.com/Article/details/gtlskjwbvp.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtskmjsnmd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhiwuduotai.top/Article/details/gtuaompmoj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dashuyun.cn/Article/details/gtmasxczgt.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gtxxqkelcd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtelgmzgbv.html

[Q50] 批量更新
来源：http://dali.kuanghao11.cn/Article/details/gtjkybgirp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtibhuddub.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtzugqylru.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gtshhsxtmn.html

[Q52] 删除指定行
来源：http://dali.daxiang520.top/Article/details/gtvjstbusu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtnktticic.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtqyugxszv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtjuajqfxv.html

[Q54] 清空表
来源：http://dali.gotoacloud.top/Article/details/gtsfhjttoa.html

TRUNCATE TABLE logs;
来源：http://dali.cucudq.cn/Article/details/gtcpyiothi.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gtxnrarbuj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtzwtwxoie.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gtevqbvjqc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hysaishi.cn/Article/details/gtkzglkcyh.html

[Q57] 行号
来源：http://dali.guowangkeji.top/Article/details/gtquktiygv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtaxbqmsys.html

[Q58] 累计求和
来源：http://dali.shzxlz.cn/Article/details/gtjfrzgjsq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtvvrnsofn.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtetvacksq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtfwusijvn.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtirhdedig.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxuanxn.top/Article/details/gtgugkcinl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtwwdndznm.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtssmbhcpv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtkqeejyyx.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtreirxjai.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gttqxovfzh.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtggewtpub.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.meibo888.top/Article/details/gtchovewai.html

[Q64] 提交事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcefmwwju.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gteczqjlif.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtghionkzd.html

ROLLBACK;
来源：http://dali.ydzc1.top/Article/details/gtidovixfd.html

[Q66] 行锁查询
来源：http://dali.havefunace.top/Article/details/gtnlnlohzv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gttxuoplph.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gtsuvvvizp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfqsmtat.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtupsbmrdo.html

SAVEPOINT sp1;
来源：http://dali.9152youxi.cn/Article/details/gtfdasckrp.html

ROLLBACK TO sp1;
来源：http://dali.wangdashe.top/Article/details/gtqsowhumx.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtjogvohxp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtuqxpkluq.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gthrimfhyq.html

ANALYZE TABLE users;
来源：http://dali.nanxinkj.top/Article/details/gtbrhuyseb.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtjlifccsu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hfpthk.cn/Article/details/gtqnbbklrb.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtprvjijxn.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtoyhnkteo.html

[Q73] 查看表状态
来源：http://dali.cashguo.top/Article/details/gtfakofnxt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtbpjeoylm.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gthdtnvtir.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hywenlv.cn/Article/details/gtlmmsmgsi.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtxobkdwbh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtuuswmree.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tianlin.xyz/Article/details/gtihyamrtv.html


<!-- 参考信息 -->