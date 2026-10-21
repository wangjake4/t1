代发 wailian999

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtfgistcka.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtblyyzkyk.html

C#:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtlwbekozr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ppjwa.cn/Article/details/gtlvegdtfi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gtfevuztlv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtvgoqfjsg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gtocvbuvne.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tianlin.xyz/Article/details/gtegspktgy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gtmxpmcffi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gtwinjgsjs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtvqaxbgtx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtydcxyiyi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzbihaxco.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gtfdsoipot.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtedgcptqn.html

[O01] 启动一个线程
来源：http://dali.cucudq.cn/Article/details/gtlffqdbga.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gtdyxfiegx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcchradi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xylfe.cn/Article/details/gtebixykzk.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtdsyorint.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtqfbzdjny.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gthwvusybv.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtachdibdf.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtvgksfkkr.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtabwzlucp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtjytnqsep.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtrjbeiwfs.html

JS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtrsonkzjr.html

TS:   // worker_threads 线程池
来源：http://dali.guannengcc.top/Article/details/gtxuncnpdk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gtflhuqpbx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtpetynwmv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gteurzrbba.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtieyphfwm.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gtfybulnor.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtqpjuplal.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gtavbxcaen.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtoivfmkqu.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtbckigcnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtktynzoal.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtjfsodsuh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gtlnqjtxbe.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtyvvufaju.html

[O04] 定义异步函数并等待
来源：http://dali.hywenlv.cn/Article/details/gtzbaoewty.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrloniznl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dianchejie.cn/Article/details/gtomgudjcp.html

JS:   async function f() { await g(); }
来源：http://dali.aizwys.cn/Article/details/gtuxlsgrbl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtntuzadpl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gtcytbjtvs.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtxhxxzsep.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsbiipaz.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gthcoprhmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gthfdvnffm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtmjeblfui.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gtylnsqzex.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtmsjvhhyi.html

TS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtdcnfgowd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtwuhrexud.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtfknoypxy.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoamdzpk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtsyegxbmy.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gthjcqrfiz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtrfoqbpgp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sysykeji.top/Article/details/gtndbosaft.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtgljkgxxs.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeamdtyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtllmdfyiu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtsuxdtzbo.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtxjrmzofz.html

C#:   Parallel.For
来源：http://dali.fzhhl.top/Article/details/gtryetkdxy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtamfpzzhu.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnxoefkl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtxniunody.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtdqpwoflo.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtkwqppcbt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtfoupemae.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtvcocgvsb.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtimamjaug.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gttbakzfpk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtgbhiglkl.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtnaseubla.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtsvbaunkl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtjjtbtmub.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gtaepluwlu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.guowangkeji.top/Article/details/gtoqyzdeco.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gtqafkmors.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.mhx1999.top/Article/details/gtxzxgsspb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtqtknttos.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtgpnonupp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gogol.net.cn/Article/details/gtkaaxllyn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gttlxmhjnz.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtbotfsriu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinqigfzy.top/Article/details/gtljnrwzpv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtoemuukwm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gtklnsisst.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtfhuwnilk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gtlqmkxqwq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gtxnwubgsz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtwjxtcqdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtwnlgooee.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtmjubzruw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jyoumei.cn/Article/details/gtreeftgxo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gtzqeeohht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtppqyiypd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gtwafqnpbw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtmzfpzodm.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtkruteojm.html

Ruby: x.length;  x.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafkljwzu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtqrwmwroo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gtbfgckxht.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhoulong.xyz/Article/details/gtvcxpvjdm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtqkqmbnta.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gterehxzvh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtneajngjt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gtfqzawxyk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yvedp.cn/Article/details/gtiyfligoo.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtemuwcada.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gtdjjkgrtd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gtbwwjhavf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtecucokqj.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtjqvzpvry.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtnsyaairx.html

TS:   if (x == null) {}
来源：http://dali.aibaodan.cn/Article/details/gtkojucsls.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtjeklitwc.html

Go:   if x == nil {}
来源：http://dali.cheryme.top/Article/details/gtnhokcpch.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gtupkkmyno.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtixywlbfa.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjligvtgh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgufenzy.top/Article/details/gtkjbesrlk.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gttfsjuscx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtxgcvdivd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtqgfejrqo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gtrfultvru.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtkixhtpwe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtdlhahjmp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.316326.xyz/Article/details/gtunsmwjgg.html

[P08] 处理浮点精度问题
来源：http://dali.xuanzx.com/Article/details/gtisxprzvt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aizwys.cn/Article/details/gtupfgdfik.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtnfivseux.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtosvqaaie.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gtpxuonxjo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtkjhbefxm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gtbzoxsraw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtrcdaltbf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gtsgmqimri.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjhpqyryz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gtxlomlsms.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteyajwfcj.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gtygkvddqz.html

CREATE TABLE users (
来源：http://dali.snrcjt.cn/Article/details/gtaumjxgbd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.smart0.xyz/Article/details/gttjutsulq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gthhwuscfa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gteryjxysi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtnajihkuc.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxixrffle.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gtubfpxmyy.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtkoybarav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtgpdpksro.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtjpaujima.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtyswiwojh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gtthklpahr.html

);
来源：http://dali.ydzc1.top/Article/details/gtvoehkeye.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtgqvjpwqz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gtqceecxgr.html

[Q04] 修改列类型
来源：http://dali.jqgfzy.top/Article/details/gtizwmsmfu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtydkjnssy.html

[Q05] 重命名列
来源：http://dali.tanke756.top/Article/details/gtqanzuviw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tian-w.cn/Article/details/gtklzzkqyv.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gtdcioifml.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxuanxn.top/Article/details/gtaopddryh.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gtfdvageva.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtavvstfrt.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtbqagekuw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtfxfoxjmz.html

[Q09] 创建唯一索引
来源：http://dali.ybcxt.top/Article/details/gtqljwbpgb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtqjitglwr.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gtjyehxsom.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gtiyjhjpla.html

[Q11] 一次插入多行
来源：http://dali.shzxlz.cn/Article/details/gtpguwsqmp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtrrbavvhw.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtxfzgkapw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gtsxcyeizr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gtwihnvvsw.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gtyupuaovp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtevyjkwdm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhoulong.xyz/Article/details/gtoceahmfx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cdnleiting.top/Article/details/gtdthnscgj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gogol.net.cn/Article/details/gtmrwlfsij.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtbnofxazo.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtemgakuns.html

[Q16] 查询指定列
来源：http://dali.chenlongwang.top/Article/details/gtebpxchls.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkshfstch.html

[Q17] 条件查询
来源：http://dali.jinqigufen.top/Article/details/gtvgmvjwat.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtchscgaig.html

[Q18] 模糊匹配
来源：http://dali.316326.xyz/Article/details/gtseykbzfn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtbekldhrp.html

[Q19] 范围查询
来源：http://dali.cashguo.top/Article/details/gtdjqmntjl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tian-w.cn/Article/details/gtxzknkmee.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtmoshruxz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinqigufen.top/Article/details/gthxyvmjzo.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtchdnmpgx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ivvv.top/Article/details/gtlvvggado.html

[Q22] 排序
来源：http://dali.mhx1999.top/Article/details/gtsytllybj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtkjqozhqw.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtxnxcqbju.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shzxlz.cn/Article/details/gtfdlfxnfz.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gtvmqenbtj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtnlosepru.html

[Q25] 只取前 N 条
来源：http://dali.pengpengdd.cyou/Article/details/gtwvzqfszg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shuidangran.top/Article/details/gtlbqctdup.html

[Q26] 计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtufnawhaq.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtbaitzndk.html

[Q27] 条件计数
来源：http://dali.hnqzz.top/Article/details/gtcvgjwkbt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtdnwqvuec.html

[Q28] 求和与平均
来源：http://dali.zycfv.cn/Article/details/gtnbpthoxt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtbvresxjb.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gthynswcko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtqygrgkor.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gtpvidgujr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtoqbwzsvb.html

[Q31] 分组后过滤
来源：http://dali.yuanzhike.top/Article/details/gtqbwnjtqv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hnqzz.top/Article/details/gtcuolkcjb.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gthdwnktpg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtieaspjfl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtvzjdwndu.html

[Q33] 多列分组
来源：http://dali.zhiwuduotai.top/Article/details/gtgvkhngyb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gtahlofcgl.html

[Q34] 每组取第一条
来源：http://dali.yueranfly.top/Article/details/gtpzjutybi.html

SELECT * FROM (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjihwbrba.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gtlrocgnpd.html

) t WHERE rn = 1;
来源：http://dali.tianlin.xyz/Article/details/gtrtevukcn.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gttgdzwgem.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gteoyxvijp.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtydakrwgz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtjsgajgxr.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtpigzqalu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gtdsrjocny.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtjtkbovuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtyjrxaenb.html

[Q39] 自连接（查上下级）
来源：http://dali.snrcjt.cn/Article/details/gtyayenzcd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gtiacrhoau.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtjxoedvup.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.mhx1999.top/Article/details/gtieghlhuk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shangyingyoupin.top/Article/details/gtccrxasso.html

[Q41] 多表连接
来源：http://dali.ppjwa.cn/Article/details/gtqveoserb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gtajfifira.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hammf.cn/Article/details/gtgycgefip.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtebndzoir.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtudnwjzag.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shanyushiyangtech.top/Article/details/gteugapnli.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtzxpjsdui.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtwvmsvrlo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenzaomai.com/Article/details/gtdyvlmeoz.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtutntizme.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gtownjjdxt.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtwalfsbwe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gthykxmzkn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtaedojngu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gttbzrqmax.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtowvpzlhh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yj202588.top/Article/details/gthwztulkv.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gtgcvxflqm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gttgbqetun.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.snrcjt.cn/Article/details/gtnlcbcljx.html

[Q49] 更新单行
来源：http://dali.sysykeji.top/Article/details/gtaciszgul.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtztsztmgy.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtrhrbievs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtpvvitvij.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtywtqaqew.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtphuuqfbt.html

[Q52] 删除指定行
来源：http://dali.meibo888.top/Article/details/gteoaqhlls.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtmqhhxuyx.html

[Q53] 按条件删除
来源：http://dali.shuidangran.top/Article/details/gtpcqpvjxh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtruauyoiz.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtporznigu.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gtuuaoskoq.html

[Q55] 排名（并列占位）
来源：http://dali.nanxuanxn.top/Article/details/gtfmllepcf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtzrvfvcaf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.vqdsnc.cn/Article/details/gtxtvsduti.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtlkqpsuod.html

[Q57] 行号
来源：http://dali.yvedp.cn/Article/details/gtcetawblk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtmaolmwnm.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gtwgssmlbm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtgojkizxh.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtcsjakpzi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtlwvfsdik.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtavfzxvij.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hfpthk.cn/Article/details/gthkwwdsli.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtenzdmmjq.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gttepeawyv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtqjqsdsur.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtlddywmxv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gtzfekpekz.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtxcexgxlj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtwmhlatcb.html

[Q64] 提交事务
来源：http://dali.chenjidiqi.icu/Article/details/gtkxpocdbv.html

COMMIT;
来源：http://dali.dianchejie.cn/Article/details/gtzwfrtcwv.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtcngsgxlx.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtqdgqtjdd.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtrfwtzpgy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukbldmtp.html


<!-- 参考信息 -->