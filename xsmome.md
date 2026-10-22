代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtpaeilasd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtpytsofhl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtvqdgtpxf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtewarbiev.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtjoaaazha.html

O. 并发与异步
来源：http://dali.yj20258.top/Article/details/gteemqrrla.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtedkjysws.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtecvnhkhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenjidiqi.icu/Article/details/gtmuctunzw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigufen.top/Article/details/gtlxjrhike.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtvjxyoqlk.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtlshrqyog.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gtmsntdxna.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtwsprlvde.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gtlskfpbwd.html

C#:   Task.Run(() => F());
来源：http://dali.yuxming.cn/Article/details/gtzpnhollz.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtfwmgfpfa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yueranfly.top/Article/details/gtiqqamoow.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhndjjkd.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtzfezskma.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtjclvjjuw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cucudq.cn/Article/details/gtsxdpduib.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtxjyozfhg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtcyufqkua.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gttmizqjgx.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizahfjao.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtrfvtdfah.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gtsrzyhwlm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gtgaipchex.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtiuaumklz.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtuxaswdso.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtsogziljp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtegyfxleh.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtuibjornq.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtzcfvupak.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtlwxdixxp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtmfcbgnou.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gttimqlplw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtcqieynul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtwwkgurpk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gthqmwwzxu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtqviqehzs.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtwnjzchkv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtkscquqfv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtujrexlok.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hongshengwenyu.top/Article/details/gtubxvxixi.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzeuevdvn.html

TS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtyxvipyfx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gttaczfxkl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtbjvyobof.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtutqcrnhm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shzxlz.cn/Article/details/gtbefnvdqr.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gtzzrvgxal.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtrubskjmb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sweek.top/Article/details/gtjphafrpe.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtqwqfwqsj.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtvykwtken.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yvedp.cn/Article/details/gtoiackvxr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtxbmknukd.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gtgwrmwqhb.html

C#:   Parallel.For
来源：http://dali.jinqigfzy.top/Article/details/gthjvqknkd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtivsttaol.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtexqbbisr.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtaoevfoum.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtyylomfvc.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtxsdntatn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtvfeyxdnz.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtgpeireos.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtjhzhyuai.html

Java: UUID.randomUUID().toString()
来源：http://dali.pycfn.com/Article/details/gtkrkjlhic.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtwhjdqckw.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtlqlpbgoc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gtpkbthdny.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gtfjehbsul.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtblqjhxwb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtcemslbsj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtasfndtwt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.haohaochexian.top/Article/details/gtxsmfycvh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtdwylkwtx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhongyouzk.top/Article/details/gtoazltpzd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtmizepmxy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtktsggorh.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtudqhjncj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtdmhikxag.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtywdpyagy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtrwzofkrq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtblocolnp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtjrjbenyp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenlongwang.top/Article/details/gtsmaodgcc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtfbcfysvr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtngvumnwq.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtqcozwchc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtzrnadkpq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gteoglerqy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtkbnkglgb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtgyhietxe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtmtesblqo.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gtbkoilhsq.html

Ruby: x.length;  x.size
来源：http://dali.haohaochexian.top/Article/details/gtpuughany.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtwvqgargo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hongshengwenyu.top/Article/details/gtzpqalkyb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtszavxsuw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbfcjlqr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtuoiymgwk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtvivqsfei.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixveywea.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtbzwkgbed.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gtaqsjzizn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtvdfnlodh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtlklhzkjq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtfgmxlhbn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtxxrdblud.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gterokjijt.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtdwqklqbk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.mhx1999.top/Article/details/gtnhfhgkkb.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gtghbnlmmj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.0kj1m.cn/Article/details/gteuxevmhd.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtmtejwrur.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtrlskblrq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtdzqgaxhw.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtnuzdhrka.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtsraoqogn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gthsraxpfk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fzhhl.top/Article/details/gtaykyhcue.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtmxlmejmn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.316326.xyz/Article/details/gtofxyuatw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtyyjqxigo.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gtfzjcovuh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtpsfxweyw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtyslwhhjk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtjelcrosg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtuewornan.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtdsrgfmix.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtecqhuexd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.bjfxy.top/Article/details/gtehzjkain.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shangyingyoupin.top/Article/details/gtkujtnqzb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwocfcxwd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gtuahoiebn.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtacxpbweg.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtpbtpaqqd.html

CREATE TABLE users (
来源：http://dali.hongshengwenyu.top/Article/details/gtudazjehc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcysnuosa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gtxxhfiibd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtrkgbmktr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gteyuimfxk.html

);
来源：http://dali.gotoacloud.top/Article/details/gtwjocuibt.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gtskwzlfio.html

CREATE TABLE orders (
来源：http://dali.daria6918.cn/Article/details/gtwezewksi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtlooyxlka.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gtzpvypzxg.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtnfauruzc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmcikfbj.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gttjnytlxc.html

[Q03] 增加列
来源：http://dali.snrcjt.cn/Article/details/gtmjiqfgga.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtxflmidjg.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gtfyylxnyp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtzenzvtom.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gtxpfvpaze.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtcnwqzmze.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtqylkyozq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtthyiexlb.html

[Q07] 删除表
来源：http://dali.hywenlv.cn/Article/details/gtthzlvvlw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ivvv.top/Article/details/gtrlcjysji.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtdvqgwsia.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtbdascwos.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtdztgdpjr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gtnbxtjmrm.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gttlvunwcs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tanke756.top/Article/details/gtkghjtfuc.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtevarljso.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtnalzxpmo.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtguzvysee.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtkbkxcczc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcxkbbco.html

[Q13] 忽略重复插入
来源：http://dali.xylfe.cn/Article/details/gtsbqnpzoj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.sweek.top/Article/details/gtohytoohq.html

[Q14] 存在则更新（upsert）
来源：http://dali.daria6918.cn/Article/details/gtbxgbojrf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtfhsizhpj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtiialqlsb.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtecytwjsz.html

SELECT * FROM users;
来源：http://dali.yuanzhike.top/Article/details/gthngvlqeb.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gtilirsizy.html

SELECT id, name FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzayfzmzr.html

[Q17] 条件查询
来源：http://dali.yvedp.cn/Article/details/gtvvrrdaxj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daxiang520.top/Article/details/gtllyqoozz.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtaeevupkk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtgvsfijlm.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtorvgrdgo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtfirhnypn.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gtgmmdyrbr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtyuxbzaob.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtzkcybrpf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.daria6918.cn/Article/details/gtvkwvxgaa.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtwrlikppk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gthbikvsjf.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gtfbjionvh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ehwqpu.com/Article/details/gtmgyvxbpw.html

[Q24] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtimggjhmi.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtwwolhivi.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtqgfrgrej.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtazplucha.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtzianqwsh.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtdypwsmfu.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtpvzkdfma.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtwqoaeznq.html

[Q28] 求和与平均
来源：http://dali.ivvv.top/Article/details/gtnmgfygoc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtmvxhqyrs.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtacyzbwgl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtlmqmhpiu.html

[Q30] 分组统计
来源：http://dali.yj20258888.top/Article/details/gtktkriers.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtwycnljdr.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gtektihmff.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shuidangran.top/Article/details/gtacuwkrjs.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtfijdehpj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtwpoxvano.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gtoazjaeiu.html

[Q33] 多列分组
来源：http://dali.xuanzx.com/Article/details/gtebgacppp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gtjzcivuqa.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gteglpvasz.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gtxjpoykjf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shuidangran.top/Article/details/gtjjzqjofg.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtetozdvon.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtbfhlbisb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtdjbsebxu.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtxqwzwuwh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gtiydclqmn.html

[Q37] 右连接
来源：http://dali.tianlin.xyz/Article/details/gtvznhdfju.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gzhubu.top/Article/details/gtbzoeblev.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gtvxhrvqfh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtszgcugmu.html

[Q39] 自连接（查上下级）
来源：http://dali.aibaodan.cn/Article/details/gtgzaeahos.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtwqvhvend.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tian-w.cn/Article/details/gtkpttjehh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuetiantiany.cn/Article/details/gtzpgixxgn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtvtqpzdia.html

[Q41] 多表连接
来源：http://dali.sweek.top/Article/details/gtbnyhbvra.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtwpmzbkbl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtflxtlkrg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtydvnrhvh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gtkmmbttdl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hongshengwenyu.top/Article/details/gtbylhsoql.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pycfn.com/Article/details/gtbtsepcqr.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtrcdlfmao.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtmqhwxqdu.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtmqgpngqu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gtshwachny.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtqrzhgupf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtvyaufljh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yvedp.cn/Article/details/gttlworevq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.guannengcc.top/Article/details/gtnifuzbtz.html

[Q47] 与平均值比较
来源：http://dali.yj20258.top/Article/details/gtcsgdzzft.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtjgmdhzfd.html

[Q48] CTE 公用表表达式
来源：http://dali.sysykeji.top/Article/details/gtpzyiprns.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtzinnzrdh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gtxkgkmhaw.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtxoqjfgjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtbxypuuqw.html

[Q50] 批量更新
来源：http://dali.nanxinkj.top/Article/details/gtbqiazmez.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.nwbrower.top/Article/details/gtrgqyccfs.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtujuqbxlv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gtajmsrqnn.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtfvpwwkcg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtygzovabe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtuuaymvwn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtmunbhjjr.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtclisldoe.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gtevnhcktc.html

[Q55] 排名（并列占位）
来源：http://dali.tianlin.xyz/Article/details/gtgmwysbkw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtvlyzcuqh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtqprdlppx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtxhafcpsg.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gthmaiyeab.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.birdmap.top/Article/details/gtusthyojm.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gtnvkjvgzd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtfynzplja.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtbyhijtni.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtgwyqeopv.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtopghytgd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yvedp.cn/Article/details/gtqyofkguj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqabghbt.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gtsydsygsf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtvgwxngmh.html

[Q62] 分组占比
来源：http://dali.9152youxi.cn/Article/details/gtpeflbuhx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtgunuszqc.html

[Q63] 开启事务
来源：http://dali.nanxinkj.top/Article/details/gtgbezyrzb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daria6918.cn/Article/details/gtmkzpxacq.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gtvnjurwis.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtxsdxgyrn.html

[Q65] 回滚事务
来源：http://dali.cqqwz.cn/Article/details/gtzshmpxuv.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtthtmjjly.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtuadjtpfr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtxcfbjqkv.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtzfigwcky.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtjwllaxfs.html

[Q68] 保存点
来源：http://dali.yangfankeji.com/Article/details/gtusvmlljd.html

SAVEPOINT sp1;
来源：http://dali.gotoacloud.top/Article/details/gtgrebgsdn.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtbwtthufx.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtwpechtbh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtfawavlnc.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtrnleulms.html


<!-- 参考信息 -->