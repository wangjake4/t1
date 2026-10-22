代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ppjwa.cn/Article/details/gtbuswlqxu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gtjgeajuqk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtdeohwliy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtbjddpssx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqvoixiyx.html

O. 并发与异步
来源：http://dali.jinghuilouyu.cn/Article/details/gthhhxpwfi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrianxsga.html

[O01] 启动一个线程
来源：http://dali.ivvv.top/Article/details/gtpjqmpgoj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtcqkzgwip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllqwrnxf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtglavsfaf.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gtlqzfsvet.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtxzifwqgn.html

Go:   go f()
来源：http://dali.gotoacloud.top/Article/details/gtbkbjmlkc.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gthpgqubdg.html

C#:   Task.Run(() => F());
来源：http://dali.0kj1m.cn/Article/details/gtxuvovqnc.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gtgsyypcvi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtiidpcusy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gtirmqvtei.html

JS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtlfxebhjx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtuxazywnk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtunfsjafz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gtubxrdmnv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtbhbakuxe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.meibo888.top/Article/details/gtpvzbtmyd.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gtegfgmpsp.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtnkhtglix.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtjhmjysar.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtcwohpmrz.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtkrieubja.html

Java: synchronized (this) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtcngnwgtz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtruqrellm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtnlodbupm.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtrcyphilo.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gtkjcfhxyu.html

Py:   async def f():⏎    await g()
来源：http://dali.guannengcc.top/Article/details/gtfoyvnruv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuanzhike.top/Article/details/gtznkkzntj.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtofqllpam.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtgpxlzksu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtueaxyckm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtimywqift.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gtsxwvatkr.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtlwienwke.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtnaxlcsfx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhongyouzk.top/Article/details/gtsljntgzm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gtcoqlfkwi.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtjmjnovgj.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtddpfljfg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtacxkaywk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtnisuhaau.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtjmkogzly.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtehyuwzkw.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtkcgavota.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtpwanhjhn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtqlgkswju.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtauacpkhp.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtsnufgdtl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtpvjbpkyb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jyoumei.cn/Article/details/gtrchbhukt.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gthtruzatg.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtmzkgnvmf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqbxqpbv.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtvnedclim.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtfglphywz.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtmngjozvf.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtshxgdqzk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtfhvryhyi.html

JS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gtusestmat.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtzvaknalq.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtonohzvmz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtcsmalpbu.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtkazkfhuq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.smart0.xyz/Article/details/gtsxohoqul.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhongyouzk.top/Article/details/gtwxucqizp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sweek.top/Article/details/gtsgycxmfg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zdqjudy.top/Article/details/gtqpcmyhbs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtwkxfuzsx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtkwmqweib.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtnupxtfwt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtkltohzco.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gttftjqfye.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtdqcyhyjv.html

[P03] 生成短随机字符串
来源：http://dali.chenlongwang.top/Article/details/gtufqajekt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gtfnnydrxo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gtinwflacd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtcbaualis.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtljoljonm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gtuxecbqfl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtdhylluhu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtcikyblte.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtancmnweo.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtcgvkezof.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtkhkwddza.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtqqigbktf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gttpmmbasv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xylfe.cn/Article/details/gtqtbcmtuo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtjmezgusu.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtdafobada.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtejmucqnq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtgbblggra.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtykvdnhxm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cashguo.top/Article/details/gtoowgtxzx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gtxgzxnkyt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.9152youxi.cn/Article/details/gtdbewcobv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gtxfglekqr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtszlrwwhb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gtpgxdxima.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtpmzkzwgx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yangfankeji.com/Article/details/gtpwsdtfxt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ppjwa.cn/Article/details/gttnjjtcwu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtpwkzxrfo.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gthhllfimi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gtjrdfweew.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtwamibyaa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhoulong.xyz/Article/details/gtzyiazuvm.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtuzdjmsaa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtdjdxndff.html

C#:   if (x is null) {}
来源：http://dali.yuxming.cn/Article/details/gthhkbqhvp.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtwlmjtpek.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.316326.xyz/Article/details/gtxseeerqe.html

PHP:  // 手写时间戳比较
来源：http://dali.daxiang520.top/Article/details/gtjjbdutyx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtrycbeiwu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtkdpvowwy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yueranfly.top/Article/details/gthyktyutd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtpxfsmaez.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daxiang520.top/Article/details/gtsdndtswz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtlhpbqkiz.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtmlvjybyt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gtpqnyhyqs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtlrypnjsz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gticejugtw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtwbemrycd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gtbrmcllxn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtnkinmrcf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xinyue.icu/Article/details/gtsypdgspw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.birdmap.top/Article/details/gtxdktzioz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdcdpyjfh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ppjwa.cn/Article/details/gtkrqlsyxm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtuidfhwaz.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gttqvyjxjm.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkkxiwxh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtczaegljl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangshuangyany.cn/Article/details/gtmtgemqns.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yangfankeji.com/Article/details/gtviadvpvg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtcrruutpc.html

);
来源：http://dali.9152youxi.cn/Article/details/gtfrnjwnng.html

[Q02] 创建带外键的表
来源：http://dali.chenzaomai.com/Article/details/gtubezxzmz.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gtqoxiyaoq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gthdeadhua.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtnfekglyw.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtonjlwseh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtassneiwf.html

);
来源：http://dali.dashuyun.cn/Article/details/gtqauvagfx.html

[Q03] 增加列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdgixaoyq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yj202588.top/Article/details/gtrinmluyk.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtouldsppy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtfmhydszj.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtcporehqo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj202588.top/Article/details/gtnfzkvriy.html

[Q06] 删除列
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwknrhja.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gtnshcrbud.html

[Q07] 删除表
来源：http://dali.yj202588.top/Article/details/gtpyjrwume.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqthvimnc.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtwfnapoeq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gteryzqzsn.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtavesctow.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtfojepsnw.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtbkitbdsy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.svipenyu.cn/Article/details/gtuyfmadps.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gttqppduhd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtqweebpdq.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigfzy.top/Article/details/gtksluaixu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gtxxhvpkyq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sxryk.cn/Article/details/gtddqpuyny.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtyddkxduw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gterkazhrx.html

[Q14] 存在则更新（upsert）
来源：http://dali.yvedp.cn/Article/details/gtumtdmrjz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxanmnkb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gtwslsmqpr.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtquiqatsk.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gtzphvxfda.html

[Q16] 查询指定列
来源：http://dali.yj20258.top/Article/details/gtucwencck.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtvvechoal.html

[Q17] 条件查询
来源：http://dali.chenlongwang.top/Article/details/gtghkykakj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.chenlongwang.top/Article/details/gtwhppibrc.html

[Q18] 模糊匹配
来源：http://dali.hnqzz.top/Article/details/gthphmiejv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gtuepkwxhz.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtdncnloov.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.vqdsnc.cn/Article/details/gtvheidjed.html

[Q20] IN 列表
来源：http://dali.yvedp.cn/Article/details/gtwvvapwdn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gttlliplqr.html

[Q21] 空值判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywmzexhz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtvwfvbenr.html

[Q22] 排序
来源：http://dali.fengsongda.top/Article/details/gtepofzzbl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtglxzhlow.html

[Q23] 分页
来源：http://dali.xylfe.cn/Article/details/gtfapappja.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.andypj.xyz/Article/details/gtdostqbqb.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtnlbkhobk.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtcpqdkbow.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtmfjqfblt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiibture.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtoqiamzyg.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqvlbcozn.html

[Q27] 条件计数
来源：http://dali.zhoulong.xyz/Article/details/gtyljkzrrd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtvjuonpmd.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtziyqzpbw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtygettswm.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtkofiitaq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtluxcwpgt.html

[Q30] 分组统计
来源：http://dali.daria6918.cn/Article/details/gtjamkrkhv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gttytedmnb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gtezbwlihi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gtbfzkhcly.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtuazhuipt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtcqpualdw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gtbrolavlf.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gteuwbswej.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtyffofzkt.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gtgrnwdoki.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtpncgnrcb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gtwvuqyagc.html

) t WHERE rn = 1;
来源：http://dali.hfpthk.cn/Article/details/gthabpgowr.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gtjkhvxmmj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtgtfmcgov.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gtfnjyztdc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gtiuaiyguw.html

[Q37] 右连接
来源：http://dali.xinyue.icu/Article/details/gthuiinnux.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gthjsbqmta.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhongyouzk.top/Article/details/gtndgqzwqb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gtdulesypx.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gttojhqyrd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gthanzykxy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gtqaclcwgc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aizwys.cn/Article/details/gthiczijrq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ydzc1.top/Article/details/gtjvfkejqz.html

[Q41] 多表连接
来源：http://dali.aizwys.cn/Article/details/gtmygjrlxo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.andypj.xyz/Article/details/gtsbaxzzlm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtwktzixny.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.havefunace.top/Article/details/gtadnjtgem.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtiplieujs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtjnkuleag.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gthuoxpjlt.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtatkckipl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtifgjybiv.html

[Q44] IN 子查询
来源：http://dali.ydzc1.top/Article/details/gteylqeukv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cqqwz.cn/Article/details/gtfslqsfdx.html

[Q45] EXISTS 判断存在
来源：http://dali.jiagoushi.top/Article/details/gtddbnwgzb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gttbkzsaql.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gtatfigquq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtgluokqfx.html

[Q47] 与平均值比较
来源：http://dali.svipenyu.cn/Article/details/gtdsuqiyic.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gtjkzeychq.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gtubwdeccy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtxlvkkjvs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtxsdzlmdt.html

[Q49] 更新单行
来源：http://dali.chenjidiqi.icu/Article/details/gtxrcdwdfg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtovtkojjx.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtlkxbbovv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cashguo.top/Article/details/gtcrelicme.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtinznojdg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gzhubu.top/Article/details/gtvjpbtuvg.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gteybyohad.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtovkxmgdq.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gtifmgosls.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.havefunace.top/Article/details/gtfjgiuohw.html

[Q54] 清空表
来源：http://dali.shuidangran.top/Article/details/gtkzfeokyt.html

TRUNCATE TABLE logs;
来源：http://dali.jiagoushi.top/Article/details/gtnpjzlusl.html

[Q55] 排名（并列占位）
来源：http://dali.c1oappe.top/Article/details/gtcyjmwffc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtbcvoybvk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ydzc1.top/Article/details/gtesiivlla.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtifdptljz.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtuszkskhw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tian-w.cn/Article/details/gtugacytvo.html

[Q58] 累计求和
来源：http://dali.cashguo.top/Article/details/gtkrdyjzog.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtperqtqgb.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtembmubmj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtndfceaio.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtxnmpghan.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gtienpgwfo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtsmlbwzdr.html

[Q61] 移动平均
来源：http://dali.jqgfzy.top/Article/details/gtpatbatce.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaeumbgpl.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gticlmhqgk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtqkxpytak.html

[Q63] 开启事务
来源：http://dali.0kj1m.cn/Article/details/gttsottrns.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtafeybvvj.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtdbcepxzz.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gtiaaflhks.html

[Q65] 回滚事务
来源：http://dali.ydzc1.top/Article/details/gtnwglzynm.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gthskcdnrz.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gtnuayvzum.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.birdmap.top/Article/details/gtlcvdqupm.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtyutbgeig.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gogol.net.cn/Article/details/gtbobcaxqy.html

[Q68] 保存点
来源：http://dali.yuxming.cn/Article/details/gtjvbqunsl.html

SAVEPOINT sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtwuanldjv.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvdkloeq.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtngpabpws.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangtech.top/Article/details/gtqforyzrw.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobjjlwga.html


<!-- 参考信息 -->