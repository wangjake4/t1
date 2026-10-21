代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xinyue.icu/Article/details/gttcmqjvnj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gtrbdbncbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnecnspfz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtbnjnnres.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwznnueeu.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gthmgjdhoe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlapjadow.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gtgrgjnxqf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtybxbjmop.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhoulong.xyz/Article/details/gtuiulvmti.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrzpgttb.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtwylgkggj.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtdyjntbav.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtggjfuinn.html

Ruby: Thread.new { f }
来源：http://dali.cdnleiting.top/Article/details/gtryyovzgd.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gtklbcodus.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gtsxdscexl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gtkotsolpi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtcjoqxcui.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaedrdcr.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gthuortzth.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gtgsdzjtcs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gtkutjaygm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gthjspdnld.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtocnqfdlu.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtpnhmzpsg.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gttmmhjaaj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtltrrgcxc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtrdnxquhm.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtczufbsye.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtllfnywed.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtllxwcdkm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtuycaqime.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtygkkjzxa.html

[O04] 定义异步函数并等待
来源：http://dali.zhoulong.xyz/Article/details/gtzpeoypqv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gtccjzmduw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtcbwsdxqx.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtcqngaldy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtcrnifwif.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtmevgyupt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gtnglqwkzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtjwosmyjk.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtmtzwiwss.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqqrtvmq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtjhtiffzp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtyalymxys.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtzpszvqdv.html

TS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwagkgjoq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtfkonykxr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtsekwogzd.html

Ruby: threads.map(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gtigvgmjfs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtrzhhaver.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtrdwizoyh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtdmidngkx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtpzrznaql.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtfxmojjjw.html

TS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gtgkajbotz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtkcyrywxm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtwhnxuczb.html

Ruby: // fork 块
来源：http://dali.haohaochexian.top/Article/details/gtinatdpcw.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtjyiouwat.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjkorazak.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtakaizqsp.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gttemjquvu.html

[P01] 生成 UUID
来源：http://dali.iojbl.cn/Article/details/gtjjilsdrv.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gtkvhbohgg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtihxlfufp.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtcrckecob.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtnfqctjbf.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gtbbsuxgtp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtoroqhcjf.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtgykffbny.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gotoacloud.top/Article/details/gtwgkfjalo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gtkgsefjbi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gtszvptomp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gtwdvaqfqu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtyrntrkwy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yongpay.top/Article/details/gtzazdtygs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtjwjrqaaz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zycfv.cn/Article/details/gtifdyzrwo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtceuewlif.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gtqeijstfv.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtwkjdvshr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutkvhiox.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnxiangtu.top/Article/details/gtktfefijx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtimppmgek.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gtylrhmryc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtzuqdijui.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gthybmsrfs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwlpsyoq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtlgnpqxdc.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtatmcnzjt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.fengsongda.top/Article/details/gtjxtlmeeg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtlvhzbsfo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtbnygefjm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangdashe.top/Article/details/gtgtjwbsjs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtjidvkqhf.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtvxhhhgwr.html

Ruby: x.length;  x.size
来源：http://dali.cucudq.cn/Article/details/gtbmjrzdhp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmalsfovq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtzvrybofp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtevthqmpt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gtgwxamlfh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gtjvsjgmxp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtfxdhtwhg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gtvtcrpjzn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.0kj1m.cn/Article/details/gtupyqoapy.html

Ruby: a == b
来源：http://dali.0kj1m.cn/Article/details/gtgqdugzrl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gtpsqinaxx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cashguo.top/Article/details/gtqsjllsmx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gtzqmxylmg.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtxjbmzkiy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gtjjqyvkmj.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsetntrfx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gtimftmbhf.html

Go:   if x == nil {}
来源：http://dali.hysaishi.cn/Article/details/gtkchmpdzn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gtlgdieiok.html

C#:   if (x is null) {}
来源：http://dali.yj202588.top/Article/details/gtycakmnhq.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtxdqsjxiq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtzbwtttxo.html

PHP:  // 手写时间戳比较
来源：http://dali.bjfxy.top/Article/details/gtsnlojfod.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gteswvssmv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtxpigfuct.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhixingplan.top/Article/details/gtrgvhfgot.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fengsongda.top/Article/details/gtlvzrzxzt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gtfhfdnwsz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtjafgyaxc.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtawdwoymi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtysewivfg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtdqqtyfac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtzqxyqdfc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtrlpdfibv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtcyusxiuo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtsqwunusr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.meibo888.top/Article/details/gtakhzcmbo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtnvidymsv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhxftbwp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cdnleiting.top/Article/details/gtfgxunimc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtizxbacqd.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtxtavkzme.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gtqnliiddk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjwbiulb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtmyqdrrgb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtlcxnbhvk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtyawuozgo.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwxtgscr.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gtgqkfytgk.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gthmolduld.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gtyfdgggbw.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtvzomznne.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gturheijil.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.vqdsnc.cn/Article/details/gteqnxdicm.html

);
来源：http://dali.nwbrower.top/Article/details/gtijrnjqvk.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtqgsqrcmo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gtpibbmogz.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtgxbsaejr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtsyqgehgg.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtymishbky.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtshtzzibh.html

[Q06] 删除列
来源：http://dali.jqgfzy.top/Article/details/gtmlhhctna.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daxiang520.top/Article/details/gtorhvvqww.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gtqvhcdueh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.birdmap.top/Article/details/gtirsqtukj.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gttfzihpsg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtzqlgosvb.html

[Q09] 创建唯一索引
来源：http://dali.xylfe.cn/Article/details/gtohltxesa.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtgicmlnvt.html

[Q10] 插入单行
来源：http://dali.daria6918.cn/Article/details/gthdgwtwse.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtmjeinvrr.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiaordvc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gtqnmzrwab.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtfyudazov.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aizwys.cn/Article/details/gtshmkqtul.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtotxvekra.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtatytffjk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtpwrbdtjy.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gtrdquupnb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jlsjyb.cn/Article/details/gtmcmczzrl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.316326.xyz/Article/details/gthoretmer.html

[Q15] 查询全部
来源：http://dali.fzhhl.top/Article/details/gtxxbxceil.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtchslqmhf.html

[Q16] 查询指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbabpbdtj.html

SELECT id, name FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtrlswzwrd.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtktjwgaps.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fengsongda.top/Article/details/gtsxjmoxur.html

[Q18] 模糊匹配
来源：http://dali.xylfe.cn/Article/details/gtjfvxxzhc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sysykeji.top/Article/details/gtleitkdjn.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtymcowllh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtpvnybrfe.html

[Q20] IN 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxufobona.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuanzhike.top/Article/details/gtocncdwha.html

[Q21] 空值判断
来源：http://dali.meibo888.top/Article/details/gtodylctow.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmswxahvw.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gtdobeiqud.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtfnyjsjlj.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtiqhkroqy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtaombrbqx.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtgmibhnzd.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtihnrrqev.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtfokydhxn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gtflhixorp.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gteuxguzxm.html

SELECT COUNT(*) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtrrcbdibh.html

[Q27] 条件计数
来源：http://dali.daria6918.cn/Article/details/gtrnxnqlef.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtierlrqdo.html

[Q28] 求和与平均
来源：http://dali.chenlongwang.top/Article/details/gtwldbbbnl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtayroenkg.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtwvhjzfre.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtldsgqhif.html

[Q30] 分组统计
来源：http://dali.9152youxi.cn/Article/details/gtpoynxcef.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtdykacvde.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gtayzwuvxh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtawkimsyx.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtsstxumuy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtgicwlwsi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtongjrwis.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtyviglrrq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gtsfqlbcqe.html

[Q34] 每组取第一条
来源：http://dali.andypj.xyz/Article/details/gtcyeyrrxg.html

SELECT * FROM (
来源：http://dali.sufxvd.cn/Article/details/gtzslrrzke.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.gogol.net.cn/Article/details/gtnzkolfgj.html

) t WHERE rn = 1;
来源：http://dali.zhengqikj.top/Article/details/gtilzyqdfi.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtlptswqhw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gtqcunehnp.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtxnacrwps.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtsplnxobx.html

[Q37] 右连接
来源：http://dali.jqgufenzy.top/Article/details/gtkpnsscdy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yanxiufei.cn/Article/details/gtmckvgtod.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtofxgxuyv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gtmcwrjiif.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtlkfsmsim.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.meibo888.top/Article/details/gtquvdrnaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtljxdpxsv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.havefunace.top/Article/details/gtuvtrskbq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gtcdxfyusz.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gtzzdgwcdy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtrneavvay.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtigxroxrq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jinqigfzy.top/Article/details/gtexmwpavc.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtyejkldzf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jianghu66.top/Article/details/gtpnsxfhqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyajwqyl.html

[Q43] 标量子查询
来源：http://dali.xuanzx.com/Article/details/gttwgcokhd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtclnrcjzl.html

[Q44] IN 子查询
来源：http://dali.zhongyouzk.top/Article/details/gtzwbretmd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gotoacloud.top/Article/details/gtiyjttmnk.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxuanxn.top/Article/details/gtguefzqjm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtpieikear.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtapmgttnl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtkflwrghq.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtqhkxzejs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gtsoketsvc.html

[Q48] CTE 公用表表达式
来源：http://dali.xuanzx.com/Article/details/gtqmksvpbw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhreqdwm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.dianchejie.cn/Article/details/gtbdvjdjkt.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtamxnpsxi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtsdtgagkf.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtuxveshdg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xziqi.cn/Article/details/gtisxffoin.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gtuovrpekv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtzlkxqgoo.html

[Q52] 删除指定行
来源：http://dali.gaohongyu789.top/Article/details/gtddzuxftg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gtqniwlbie.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtsioinwmg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtocfmnlnj.html

[Q54] 清空表
来源：http://dali.jinqigufen.top/Article/details/gtphrrrugq.html

TRUNCATE TABLE logs;
来源：http://dali.havefunace.top/Article/details/gtcgvbtnkj.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtpzuseifg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gtsivodenr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtrnczbvqj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtcxdlsayo.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtihnbszug.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtpwdagfib.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gtuwikkuhj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtbudplckw.html

[Q59] 分组内累计
来源：http://dali.hysaishi.cn/Article/details/gtpgqcxfbz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtgasnhuds.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gtuxtfnzcm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xziqi.cn/Article/details/gtwbwuntuq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutptgbsd.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtjnmoezvg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtsdvcsnyr.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gtmffcsgcv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtleznaybv.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtvaxrjgqj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nwbrower.top/Article/details/gtrxodmhvz.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gtthxkuzsf.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gtxnymgnby.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtbsbjpxwr.html

ROLLBACK;
来源：http://dali.vqdsnc.cn/Article/details/gtqthxnxhi.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtxkkfkdii.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.vqdsnc.cn/Article/details/gtqgqbfrnj.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gtckucgryy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hywenlv.cn/Article/details/gtewjgyihx.html

[Q68] 保存点
来源：http://dali.havefunace.top/Article/details/gtgrwgyvcd.html

SAVEPOINT sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtumhnbavl.html

ROLLBACK TO sp1;
来源：http://dali.ehwqpu.com/Article/details/gtvdgohvfo.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtoivyghua.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gtfzeufaha.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtgxjqvrxe.html


<!-- 参考信息 -->