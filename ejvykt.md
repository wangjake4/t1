代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gtvntnpwej.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shzxlz.cn/Article/details/gtazugbdvf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtokrgbzqq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gtdhiuhfey.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtnyisgkql.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gtvhjojewd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gtuktrrvvs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj20258888.top/Article/details/gtusfwtadx.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbvypzwkc.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtvjyumeat.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtrqhpvhcg.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gtlwspoesy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gtpvccjjae.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gtbemhhjdr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yvedp.cn/Article/details/gtbswwxtjy.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtjjlpisfk.html

Java: new Thread(() -> f()).start()
来源：http://dali.cashguo.top/Article/details/gtxhzjfquw.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gtuyhnwrdm.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtezlpmqie.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtptlwuxix.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtrnfafrlg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gttdvjuphp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gttmaafllk.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gttkvkvjyi.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtvvmzeyaf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtdoeewwfz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtfavdoyxc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtbvjzqrto.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gttlzlkpta.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtrhoyltxk.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gtlwmpnhae.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtsccqophq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtbzhrsidc.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtfhmzaoby.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtbnauquaq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtqmzjufqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtamorxcpv.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtgokxgfai.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtnshautad.html

Py:   async def f():⏎    await g()
来源：http://dali.haohaochexian.top/Article/details/gtrsitwxlz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtdpptkeyl.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqfgeroxi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gttlscwdqg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtvqiwepup.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtxmfgejzd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gthjwgnrws.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtvjquklns.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtraoslknu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtjdorpprh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gtmqiynvqp.html

JS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtcezosltx.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtyrajjpny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gttwfuhyfp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gtifosiyzg.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gtweutsnub.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtnzhedqdt.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gtlldcadah.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtvzoqriqc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gthsyshkap.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gtwuawsbks.html

TS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtymnqwden.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtattbjwhk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtxoltxftd.html

Ruby: // fork 块
来源：http://dali.yuanzhike.top/Article/details/gthjllaegd.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gthmjwrpel.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadtlinma.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtatvoyxlb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgcndidlo.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gthuwzhlay.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtwoqzahbl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtgnbupsmk.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtrreofwsf.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtsrkrfwss.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtpypjfrof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pycfn.com/Article/details/gthpmqrnuz.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtxzqezgmz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gtogdfwnxt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dashuyun.cn/Article/details/gtcwhekixc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtcpmltbia.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtwikfrjod.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.iojbl.cn/Article/details/gtoqmccpjm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gtcqqgyadh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gtraemasoy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtinnjhekh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtekbevyza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhoulong.xyz/Article/details/gtqkqbgvpq.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gtotlztnef.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtdrffkofl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtyjjzzgkq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtprjdrfvp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtgemqarzd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtggfuctsu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gttbvrjufa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tianlin.xyz/Article/details/gtirkulqws.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gtvuhffxib.html

[P04] 求长度
来源：http://dali.xinyue.icu/Article/details/gtdwvgowqy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sysykeji.top/Article/details/gtbpavknva.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtklckudyy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gtzftfdfjr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtrfxkzrko.html

Java: list.size();  map.size();  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtkgbfkrda.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvvvfkaj.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtzamcsxfs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtyxcwwhtw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtyafhzrmm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtczdqkuuy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtobjqejvd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtyjexxgsh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gtvxljtqmq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtpznzssva.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtfbpnoztm.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gtiwngkwmc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gteinrhoxs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvpsovlf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtjatqkloo.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtcxzukavo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtbmacmnld.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjaukgwwr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtzobaxetc.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuaklhgs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtijkjrmrb.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gtzdfzcomt.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtvdjygkzo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtgzsfmdhg.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtoxyxgyxz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyhpydol.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtpxlbhnap.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtonzhzpat.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.haohaochexian.top/Article/details/gtbhldnany.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gtgcqlcgoz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtpjbbwsef.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtprbqskyj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiokjzwah.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.quarkkingdee.top/Article/details/gtuafjqthu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xinyue.icu/Article/details/gtcxxdflvl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtzdldifow.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gaohongyu789.top/Article/details/gtffsaebzw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gtgrccklgx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gtuoquljep.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yonumen.top/Article/details/gtjgibikqn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttoznrktf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gthfmcynbg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtqmmbzvfu.html

[Q01] 创建表
来源：http://dali.shzxlz.cn/Article/details/gtqrgfpebt.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtqbgnions.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtovbheesn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtxspwzjvq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtsgfzgpqg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedtncpsu.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtphpizlrs.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gtwzkdorwv.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gthbijtdcx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtxurilmqf.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtpsxaybmm.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtgbkwqrov.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtnuzgfxwp.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gtrwascrju.html

[Q03] 增加列
来源：http://dali.jinqigufen.top/Article/details/gtftxymzzv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtnrikemia.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtzgzytusm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gttlswjstr.html

[Q05] 重命名列
来源：http://dali.chenjidiqi.icu/Article/details/gtwcjjpnoh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gtdqflngjd.html

[Q06] 删除列
来源：http://dali.jqgufenzy.top/Article/details/gtbsgkmwmo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xuetiantiany.cn/Article/details/gtnmjcvrau.html

[Q07] 删除表
来源：http://dali.haohaochexian.top/Article/details/gtortttrey.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shuidangran.top/Article/details/gtyijbcdss.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtlmjpylzu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gttftlwzaq.html

[Q09] 创建唯一索引
来源：http://dali.meibo888.top/Article/details/gtrfbxpgvd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrsthpzg.html

[Q10] 插入单行
来源：http://dali.xuanzx.com/Article/details/gtmisggpgi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cheryme.top/Article/details/gtjrxanerl.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtbjnxhypy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtjseqvbdq.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gttvteierj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.snrcjt.cn/Article/details/gtyrwhkdti.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hammf.cn/Article/details/gtawqidcxb.html

[Q13] 忽略重复插入
来源：http://dali.cucudq.cn/Article/details/gtbgxhwilg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtcnzwgnau.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfnyyocd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtxvwvakiv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtvhujmksd.html

[Q15] 查询全部
来源：http://dali.ydzc1.top/Article/details/gtsclkbsch.html

SELECT * FROM users;
来源：http://dali.cucudq.cn/Article/details/gtkyyubfyn.html

[Q16] 查询指定列
来源：http://dali.vqdsnc.cn/Article/details/gtqawyitya.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtplzabxko.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtjyhymaza.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.0kj1m.cn/Article/details/gtvjczahwk.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtsqonufod.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtakwqwjci.html

[Q19] 范围查询
来源：http://dali.xziqi.cn/Article/details/gtuuqwmcbd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gtcltiettn.html

[Q20] IN 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtffvrsrvh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtwogcpvcc.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gtygpczulj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtmfcxeejc.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtqiqewiwy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtboxisxuy.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtdoskxkns.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtatjidsdh.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtprngvpru.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtdusjqduv.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtkigrjgsa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtccqybmoi.html

[Q26] 计数
来源：http://dali.vqdsnc.cn/Article/details/gtuejlcpak.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtalwocqpu.html

[Q27] 条件计数
来源：http://dali.redwolf501.top/Article/details/gtxxwkgsvw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gteamsazqw.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gtpyzazuxl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtvzjprvxz.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtpvimgtea.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.meibo888.top/Article/details/gtlbxfsepw.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gtcukkdnyj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gtgsgzmchr.html

[Q31] 分组后过滤
来源：http://dali.tian-w.cn/Article/details/gteuhgoama.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtwacvqaso.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtwzoziyqj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtqjlvqywp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gtxbfqqfua.html

[Q33] 多列分组
来源：http://dali.tanke756.top/Article/details/gtogfzemjo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cheryme.top/Article/details/gtdqvtshjc.html

[Q34] 每组取第一条
来源：http://dali.cqqwz.cn/Article/details/gtxfjsoyui.html

SELECT * FROM (
来源：http://dali.daria6918.cn/Article/details/gtowfxjwgh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtutgtwkpl.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtiyymcpcp.html

[Q35] 内连接
来源：http://dali.fengsongda.top/Article/details/gtzxhneqie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtkrixnoom.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gtrretzeit.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtpfgfpvvn.html

[Q37] 右连接
来源：http://dali.zycfv.cn/Article/details/gtsyhnnuae.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaqtwxnn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gtxxamridp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtraaxjnve.html

[Q39] 自连接（查上下级）
来源：http://dali.gotoacloud.top/Article/details/gtisuocavm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhengqikj.top/Article/details/gtpmaotwiy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtzekjoswa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj20258.top/Article/details/gtdwxhvhvp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtbjcoxxbe.html

[Q41] 多表连接
来源：http://dali.svipenyu.cn/Article/details/gtdkkajguc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gtnxjqgpyf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aibaodan.cn/Article/details/gttofgllft.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtbpchfuho.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtggbvwxvr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtsmswkhcv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.vqdsnc.cn/Article/details/gttzdtbetu.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtdwlzrguw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinghuilouyu.cn/Article/details/gtywqqwqbu.html

[Q44] IN 子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtiihcjlrt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gtkkrqghox.html

[Q45] EXISTS 判断存在
来源：http://dali.iojbl.cn/Article/details/gtbmndkfrx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtmupxpycq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtlbtaiezr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuanzx.com/Article/details/gtrdpwjgiz.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtzqrcfcsk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gttdslkbrl.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtkpygsyyk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtkkxcctwf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtsqoyfaah.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gtlflrdyun.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gthzkbsaiw.html

[Q50] 批量更新
来源：http://dali.sweek.top/Article/details/gtirsffddl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtxtsjaugr.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtwnqgmvbq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.kuanghao11.cn/Article/details/gthftzqshw.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gtlpfzhpzh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtmcrvyfcb.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtflxsizer.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtugcaojxq.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gtnvyriaii.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaewnqzpw.html

[Q55] 排名（并列占位）
来源：http://dali.yj20258.top/Article/details/gtlaevcqun.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gtwlkslojv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtfwefakev.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtyiscfcrx.html

[Q57] 行号
来源：http://dali.quarkkingdee.top/Article/details/gtjhvexmwy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gtpbmfqmjd.html

[Q58] 累计求和
来源：http://dali.haohaochexian.top/Article/details/gtigoobbmi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtcfapbcea.html

[Q59] 分组内累计
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynducqyc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtakihtprc.html

[Q60] 取上一行 / 下一行
来源：http://dali.cucudq.cn/Article/details/gttcainkig.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zdqjudy.top/Article/details/gthkwavbpp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtutfpcjli.html

[Q61] 移动平均
来源：http://dali.yj20258.top/Article/details/gtqsmaxndn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtjkkazrrx.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtndjdgfsv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtoikprols.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtikterjxq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtdgiczjrj.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtwderpjmg.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gtsdqzpezb.html

[Q65] 回滚事务
来源：http://dali.zhiwuduotai.top/Article/details/gtvzuscdkm.html

ROLLBACK;
来源：http://dali.xylfe.cn/Article/details/gtzdofbnek.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtbcqibbxs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hongshengwenyu.top/Article/details/gtimcvodml.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtwlqcnrpc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtnlxyjimw.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gtaxfdgzgs.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtqtztydpp.html


<!-- 参考信息 -->