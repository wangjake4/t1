代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gtmkjdffwc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhsytfuj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtxbbstdla.html

TS:   // 同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtvuzptayx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhiwuduotai.top/Article/details/gttjibnzms.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqopqknq.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtrvplzgtp.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtticrsghx.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtpxvydtks.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtdthamtfg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtsaqxkcxv.html

JS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gtybhkdyus.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtdhnpexlx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtpqgexchq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xziqi.cn/Article/details/gtlptnnpum.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aizwys.cn/Article/details/gtvwrnlmug.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtbvnplkbp.html

[O03] 加锁保护共享数据
来源：http://dali.ehwqpu.com/Article/details/gtutkqlryo.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gttywrtvfi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtebralykx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtcalgnfip.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtnmgkrqzx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfnjssmn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtcsnooydk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gtvqousvpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtpgbekejz.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gtezrawyeo.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtrhhrohah.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtbctnbovr.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtctsoxypz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtsijrrppa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtxxokenwz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtftdeerms.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtbzjcrecm.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gtxwupwmbq.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gtcelsizjs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtbtjpegwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtwybfwllc.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtasegmuxu.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtvjtkgmji.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnqzz.top/Article/details/gtiztxknqy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtklhocsgj.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gtvipdsiot.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtfdqnrypm.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gthvcdhcnx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtbedodoxi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxuanxn.top/Article/details/gtjztijppo.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258888.top/Article/details/gtkqjjgboc.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtloqbunqb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gttqxpehxo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtzgqvqtxj.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtnvqbrplf.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbprwzzo.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbvppwycd.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtwqgxgrxs.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpwevggll.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gthhrskvjy.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtozoqfusn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gttpdwhnjv.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtvgpvtxge.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtgnkauvyy.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtlplkviis.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gtizjjhryf.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtcrpiisuw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtqwyovskx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gteqellyhd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gtckuciaiw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtldtthvax.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtmokwfnjg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtlykugjec.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtxkzzeyez.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtferrnhdw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yanxiufei.cn/Article/details/gtesxhdgxx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtqsjsdker.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gtmqgryzfm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdthkfzcj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtwisvmdwd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtvzmsptgd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtngywgwed.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hfpthk.cn/Article/details/gtxfrrywnw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtregqyiem.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtpukgmjkx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gteplyfvvz.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtylwkprbl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtsgvgfxcf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aizwys.cn/Article/details/gtzxqgezkd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtowaqhgrh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtcdtxxbsa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gttaoeaxrf.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtrpqsgayy.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gthwhjyzpt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpznkmsej.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtyvrvtesk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtockaontm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtycuneqwu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtusqqfuui.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtlcsqxzap.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtllqakcew.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gtuygkfozu.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtnvpvwjli.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gtjojgukkk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtvtomypjn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gthatzlnza.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gtqkklfpvw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtrndfvkkl.html

TS:   if (x == null) {}
来源：http://dali.yj202588.top/Article/details/gtbzwufnxq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkyrgsnxn.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtkrnuirfr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtfmnayxpi.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtofyoffmh.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtwfpkavgn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtrpyignfc.html

PHP:  // 手写时间戳比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysdijmbk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtcrajjqur.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtfpsguqka.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtwsdbpwdj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zycfv.cn/Article/details/gtxsfafihq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pycfn.com/Article/details/gtnnxcpqpy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbdzffvj.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gtqhwyvlfy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ydzc1.top/Article/details/gtgxynqitk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gtubgkzhbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sweek.top/Article/details/gtfjniophv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtjwowvwzg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtaitfciip.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtxkkeddzn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafnoeega.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jlsjyb.cn/Article/details/gtztyvgfiq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfaedhbzi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtpzagrbcn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrjgxidm.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtyfemfqva.html

CREATE TABLE users (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtxrqlmg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtzxifurim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gtlfcdjnsw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtwlroeefb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtcoresjps.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyoyyyof.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtqsdpdyyy.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtygvkfpbi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gtytyjktvp.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtlrbeaayg.html

amount DECIMAL(10, 2),
来源：http://dali.mhx1999.top/Article/details/gtyqfjpzli.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.pengpengdd.cyou/Article/details/gtokiedoof.html

);
来源：http://dali.hammf.cn/Article/details/gtakpyrzkk.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtgdijrkmo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtcludtkqs.html

[Q04] 修改列类型
来源：http://dali.hywenlv.cn/Article/details/gtshjdiyfg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtmohlnjpd.html

[Q05] 重命名列
来源：http://dali.ybcxt.top/Article/details/gtwtdqoazi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtelulyzfb.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixaxmfjm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gtylztkfag.html

[Q07] 删除表
来源：http://dali.shangyingyoupin.top/Article/details/gtareuqvjg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gtmjhmuhgw.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gtoxppcabh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtvihjrrhg.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtvhnlchsb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtmpgoqisa.html

[Q10] 插入单行
来源：http://dali.shzxlz.cn/Article/details/gtqbobostk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtxzjtcizh.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtejckrlsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtanfgwdje.html

[Q12] 插入后取自增 ID
来源：http://dali.svipenyu.cn/Article/details/gtgdhveowr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtasqebiox.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtfhibkowq.html

[Q13] 忽略重复插入
来源：http://dali.jqgufenzy.top/Article/details/gteyqbdswq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sxryk.cn/Article/details/gthqyxxjlz.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtzivcfexs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtykqabgat.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yj202588.top/Article/details/gttkuwawsd.html

[Q15] 查询全部
来源：http://dali.shangyingyoupin.top/Article/details/gtgnlcuhmo.html

SELECT * FROM users;
来源：http://dali.xylfe.cn/Article/details/gtcqvyqzmy.html

[Q16] 查询指定列
来源：http://dali.haohaochexian.top/Article/details/gtyvrdzgrh.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtvfecmboh.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gtndsdkdgl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtfluwscgx.html

[Q18] 模糊匹配
来源：http://dali.gogol.net.cn/Article/details/gtdkqdhkoq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtygwiripu.html

[Q19] 范围查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbagnbwie.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadjynpyr.html

[Q20] IN 列表
来源：http://dali.tian-w.cn/Article/details/gtfvdjilof.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.haohaochexian.top/Article/details/gtiifpjjpe.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gthbvgxedp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtjziwaipd.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtmjbwnphj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.xinyue.icu/Article/details/gtrkknrvwe.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gtwhavkzgu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtsohgzbix.html

[Q24] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtascuoqcp.html

SELECT DISTINCT city FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gthwhxxqmw.html

[Q25] 只取前 N 条
来源：http://dali.yangfankeji.com/Article/details/gtuskzzxec.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gtqoonuydz.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtfjsxgild.html

SELECT COUNT(*) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtgabteawm.html

[Q27] 条件计数
来源：http://dali.316326.xyz/Article/details/gtmdreevlk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtsycnrcap.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtzjtffbac.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtpmmlfgay.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtlslhwegj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fzhhl.top/Article/details/gteikqafpv.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtjopuwzot.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtpmfgjnwg.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtmmlaesgj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtmwtxagnf.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtfyuhvwxi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtyrcehtbi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtybrmveeg.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtjbraikfp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ydzc1.top/Article/details/gtemquihvv.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtexymdqsp.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtgkyknbww.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtvswlsxqn.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtggphsnfl.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtjrwcabxs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtlnexgwnb.html

[Q36] 左连接
来源：http://dali.nanxuanxn.top/Article/details/gtkhmltahd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gtxxgukowb.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gthrcexhei.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtucvcsqpw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gthyttbtpq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtaxizalwk.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gtslrbyocq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtvqncvbsz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxinkj.top/Article/details/gttbfkymmn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhoulong.xyz/Article/details/gtgcrztmwq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gtymimsvqn.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtunruxlco.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtyqjcrufx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hongshengwenyu.top/Article/details/gtofrkyncl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cdnleiting.top/Article/details/gtdcvyqjby.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtgllotmyh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtzmmtfgqa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtonozarom.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtlpsgbohk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtdbojzwfx.html

[Q44] IN 子查询
来源：http://dali.zhiwuduotai.top/Article/details/gtwxbssbrb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gtxmnwaxqp.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtubaxpdon.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtjvfjjjii.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhiwuduotai.top/Article/details/gtpnzgpaya.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtnubyhtcb.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtnfaddjwd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtxnbqudmr.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtjrugbqds.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gtlpudqctx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtuialphkv.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gtwlqsrlys.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtoatfvgdy.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gtlizfbboq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtuizbuzpz.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtnearoheq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jyoumei.cn/Article/details/gtrxlcacjy.html

[Q52] 删除指定行
来源：http://dali.0kj1m.cn/Article/details/gtwwfwsbps.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtjvgizick.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtezobszyp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gtbreyaknd.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gtuldhbawl.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtunherhmo.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtzwhmswus.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnxiangtu.top/Article/details/gtsrlcvwhl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtvnmuyuzy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtthagbshy.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtpjxbgpxh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtohtjhcpa.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gtcjdtbjav.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfckbutex.html

[Q59] 分组内累计
来源：http://dali.zhiwuduotai.top/Article/details/gtbijwaxjo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtkpvyhguj.html

[Q60] 取上一行 / 下一行
来源：http://dali.ybcxt.top/Article/details/gtkiufzhgd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtqjpafimj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvyzgjie.html

[Q61] 移动平均
来源：http://dali.ydzc1.top/Article/details/gtybbhsuov.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtxwzmkbft.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gtvyklfckx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gthqmetcxq.html

[Q63] 开启事务
来源：http://dali.ppjwa.cn/Article/details/gtojfusajz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtpypcimpn.html

[Q64] 提交事务
来源：http://dali.snrcjt.cn/Article/details/gtgmmeudpn.html

COMMIT;
来源：http://dali.dashuyun.cn/Article/details/gtvuaujtsu.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gtkznarosj.html

ROLLBACK;
来源：http://dali.jqgfzy.top/Article/details/gtgrpthhqk.html

[Q66] 行锁查询
来源：http://dali.zycfv.cn/Article/details/gtvxmsxhvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvasifth.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtocefkxca.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtfguubozo.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gthgjrovrk.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtxvfssaew.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gtfmetxxzj.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtesckyhlc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ydzc1.top/Article/details/gtaginyltu.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtczvrbwnd.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gtrlsxluqg.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtcnrjyict.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtgrludxai.html

[Q72] 查看索引
来源：http://dali.ehwqpu.com/Article/details/gtxnqvqvlx.html

SHOW INDEX FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtieesdgmb.html

[Q73] 查看表状态
来源：http://dali.shzxlz.cn/Article/details/gtqqqxagta.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtlfnpytsf.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gtsbfolpzh.html


<!-- 参考信息 -->