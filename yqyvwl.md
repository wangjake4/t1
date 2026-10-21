代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtikwqrjmp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtgikyqwsm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtjcyceqhr.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtbyzjnfsd.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtncvphfws.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtyhpiapxs.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtvdcinijf.html

C#:   Task.Run(() => F());
来源：http://dali.hnqzz.top/Article/details/gtfddvcyox.html

[O02] 使用线程池
来源：http://dali.hnxiangtu.top/Article/details/gtrmmkrlfo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxuanxn.top/Article/details/gtnalbqmgd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtlgucbqmr.html

JS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtwwmytedc.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtsgxlopsi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtdsvzvtgo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gttejjjedy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtjuahqdig.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gtvnonemwv.html

[O03] 加锁保护共享数据
来源：http://dali.0kj1m.cn/Article/details/gtxagyyodm.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gttzkpjwwa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtopjttgmi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.bjfxy.top/Article/details/gtlxpxezbu.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtnyfdtdwd.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtedtqqkif.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtrkxfeglt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtocgdkjsg.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtmlixlikl.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gtfdgjpnum.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtzjbuvcpa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtqhbtrrbp.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gtvpgfbjeb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctplhvuf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gtoxrzmubi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtqmhrobaj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hongshengwenyu.top/Article/details/gtdsognexn.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gtwwpivvch.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtvmyqmubx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gogol.net.cn/Article/details/gtqxwzpbqn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtsqxjosne.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtfdcebvyn.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtysudazpp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gtxvxjxyqn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtuyhcaufy.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtpnbffqzb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtkwtbfnko.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtgprnkbwd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtwcxasfpj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtzwwlrlat.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtqrmhdzay.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtboywbrhx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nwbrower.top/Article/details/gtxzfjgpks.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtnkedogpt.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtikwircsp.html

C#:   Parallel.For
来源：http://dali.yvedp.cn/Article/details/gtxisjuvew.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gttusnysld.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtuwynqmcr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthrtsneta.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwupfmrau.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gtyxwjxemc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gtayqriwey.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtboygwcpy.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtdefnmezg.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtxspivfco.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtmelezwbx.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtjkldgaua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtuufuoalp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.guannengcc.top/Article/details/gtydykzzzd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tanke756.top/Article/details/gtuweeogax.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tianlin.xyz/Article/details/gtqbkrctbz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtmyampkvi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gtqbeynsos.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtrixwdnuh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtvkjfdche.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ydzc1.top/Article/details/gtzrgnilbu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.316326.xyz/Article/details/gthqazjwwl.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gtbkxxqmdz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtbsjbemps.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtuuusrrvy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtfykynpyf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtxaxsihen.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtrmznwwfw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.daria6918.cn/Article/details/gtgnocrpva.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gttykfuxvp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.dianchejie.cn/Article/details/gtivseugyr.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtveiqtlbv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtdspqowpo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtvuadruvv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwrrabwb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtkjyapfyh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtuszunpkg.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtzcscnrpj.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gthdztwvbi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gtdatifebq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtxzozfikd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtfsubsomx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.feifeiyinyue.top/Article/details/gtnwzzbyme.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtnolzlbku.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtvubcowcr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.birdmap.top/Article/details/gtwtgkyrhv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtkhdzfiwa.html

Ruby: a == b
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxcjxmnq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtagsgwyal.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtzlaaqexp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtdmvougbz.html

PHP:  if (empty($x)) {}
来源：http://dali.xziqi.cn/Article/details/gtgazhefzx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgngzqsq.html

TS:   if (x == null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtrivdkhlg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtzgwokmfu.html

Go:   if x == nil {}
来源：http://dali.quarkkingdee.top/Article/details/gtgacoolxi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pycfn.com/Article/details/gtcimaxfxt.html

C#:   if (x is null) {}
来源：http://dali.nwbrower.top/Article/details/gtfoijxljr.html

[P07] 防抖与节流
来源：http://dali.fengsongda.top/Article/details/gtanxbbtvf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtlfxqylhq.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gtkxtknctn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtqemjyjoa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtugfaqodr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gtdfixnlbs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtzuovjldk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtdsbnfzhq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fzhhl.top/Article/details/gtveiokrli.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugdkdldo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtayxmxqff.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtrrdxpafs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtcndanpbw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtbmoextcj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtdkykutys.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtxhicnosi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yanxiufei.cn/Article/details/gtbjpbdiag.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtzgvjdrqw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtfzobkrne.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gtohplvmbt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcfuqykvx.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtwvarspfr.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtudwjqmoy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyhdqijl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtxiswpklx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtvaxjuauj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gtqnprnqhd.html

);
来源：http://dali.yuxming.cn/Article/details/gtpixqzaix.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtjaebgcyj.html

CREATE TABLE orders (
来源：http://dali.tanke756.top/Article/details/gtpszuukfw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gttozjqlxu.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtimscldtn.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gtknsirdcl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtogiycqpd.html

);
来源：http://dali.nwbrower.top/Article/details/gtbdmcofgt.html

[Q03] 增加列
来源：http://dali.chenzaomai.com/Article/details/gtswxypfwn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtipxtoyqs.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtcwlhxqcy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtbuiwdlmz.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gtxyachqrv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuetiantiany.cn/Article/details/gtipiodzqz.html

[Q06] 删除列
来源：http://dali.zycfv.cn/Article/details/gtapwuzmaf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gtccbkkkgm.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gtfawofxfn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cheryme.top/Article/details/gtdoxvzvts.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gtkeazxocl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtypkjroil.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgnmtasn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gtaudozyvg.html

[Q10] 插入单行
来源：http://dali.ehwqpu.com/Article/details/gtstflirfu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gtmkxewwyz.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtohshryge.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtbsolswuk.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gtkwwtycmb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtyeozlkgu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtgoxfnfye.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtfreuqdpc.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jlsjyb.cn/Article/details/gtyjblbkrq.html

[Q14] 存在则更新（upsert）
来源：http://dali.gotoacloud.top/Article/details/gttflyrzrz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtelidbfob.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.aizwys.cn/Article/details/gtfwgebijp.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gtoopkfkcs.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtsmwpodzh.html

[Q16] 查询指定列
来源：http://dali.jiagoushi.top/Article/details/gteoybmdpd.html

SELECT id, name FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdthsbupm.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtadldswdj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xziqi.cn/Article/details/gtcyzorpqs.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtlwtoyxlr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.daxiang520.top/Article/details/gtscwertbk.html

[Q19] 范围查询
来源：http://dali.chenlongwang.top/Article/details/gtmfwgquwp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtoiseachl.html

[Q20] IN 列表
来源：http://dali.ivvv.top/Article/details/gtoahbwfud.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrrbwcvp.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtxjzdydcq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.0kj1m.cn/Article/details/gtoqndnxxz.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtemcpwmxs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ybcxt.top/Article/details/gtxhofxfey.html

[Q23] 分页
来源：http://dali.tian-w.cn/Article/details/gtqebsycak.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtpizbmegx.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtivxgpxvn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbpuooec.html

[Q25] 只取前 N 条
来源：http://dali.meibo888.top/Article/details/gtdvpmlffq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shzxlz.cn/Article/details/gtypgwjpkj.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlywufkyj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtsvnkbnsu.html

[Q27] 条件计数
来源：http://dali.pycfn.com/Article/details/gtsdvkxkzi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtoqqwzrea.html

[Q28] 求和与平均
来源：http://dali.svipenyu.cn/Article/details/gtordawngd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtkctgeuvg.html

[Q29] 最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtujswbyqg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtotwghipk.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gttblcczgh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtkbzvbazi.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtpxotthhp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cheryme.top/Article/details/gttyrkpfih.html

[Q32] 分组拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtshujlveg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gtmuzrmzyt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gthmzpfzay.html

[Q33] 多列分组
来源：http://dali.jianghu66.top/Article/details/gtmdurdavo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtfetmnqib.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtxarrdtpb.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtijqwatsp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtrqqezble.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtjrxpcsgw.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtuqepxarw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtooqgmyto.html

[Q36] 左连接
来源：http://dali.yvedp.cn/Article/details/gtaqhkanmr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhongyouzk.top/Article/details/gtwfrrsqpb.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtfyqtobns.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gttyhimqmw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.kuanghao11.cn/Article/details/gttxppufkf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgufenzy.top/Article/details/gtcugtwmoj.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gttenqkaxv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xinyue.icu/Article/details/gtrfwlyxam.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtuxkkwkwj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangtech.top/Article/details/gtswauiwme.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyxsawyq.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtylcvzhrk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtarzzbove.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtydnzpvrp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhengqikj.top/Article/details/gtahazmpqv.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtcpfrmvtl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.smart0.xyz/Article/details/gtskwplfau.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtqizotgce.html

[Q43] 标量子查询
来源：http://dali.hammf.cn/Article/details/gtzdjkfxxw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqcxvagi.html

[Q44] IN 子查询
来源：http://dali.yj20258.top/Article/details/gtjqjdwoob.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtickhvqwe.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtkdwfwmch.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.haohaochexian.top/Article/details/gtbffbedme.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gtonhppitg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cqqwz.cn/Article/details/gtuqyehntj.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtpptsztpy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gtoapdubvw.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gtdcsnyskg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gtmyuzjtzl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gtbzpujmbg.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtasbythue.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtzchefttc.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gtwyyilwqj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.havefunace.top/Article/details/gtpeofgvev.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtbcxmyvya.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xziqi.cn/Article/details/gtrnlodhao.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtxakfnfft.html

DELETE FROM users WHERE id = 10;
来源：http://dali.redwolf501.top/Article/details/gtqzhxfjhb.html

[Q53] 按条件删除
来源：http://dali.xuanzx.com/Article/details/gtqliiwsqh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtmkfcmoue.html

[Q54] 清空表
来源：http://dali.andypj.xyz/Article/details/gthksugrxg.html

TRUNCATE TABLE logs;
来源：http://dali.ppjwa.cn/Article/details/gtktdnptvg.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtggzjyllq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ybcxt.top/Article/details/gttojswvuk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.birdmap.top/Article/details/gtjwvetmcd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtmuiztflt.html

[Q57] 行号
来源：http://dali.nwbrower.top/Article/details/gtxpcfppxw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtixvahurk.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gtjwaparlm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtylarkqpo.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtzaehgkmw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtunuwrkif.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtllvmjpsq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.quarkkingdee.top/Article/details/gtpcwjlvyx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtffjuvwlo.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gttizllvwq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtrvysssgb.html

[Q62] 分组占比
来源：http://dali.hammf.cn/Article/details/gtqeeffile.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtmbgbzxje.html

[Q63] 开启事务
来源：http://dali.gotoacloud.top/Article/details/gtyyyuyjtc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shzxlz.cn/Article/details/gtgoywmbwq.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gtuptelgkj.html

COMMIT;
来源：http://dali.jinqigfzy.top/Article/details/gtjrzvgtgl.html

[Q65] 回滚事务
来源：http://dali.sysykeji.top/Article/details/gtokncdhco.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtsivfwogd.html

[Q66] 行锁查询
来源：http://dali.jinqigufen.top/Article/details/gtofukajby.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtacbwnsvd.html

[Q67] 设置隔离级别
来源：http://dali.vqdsnc.cn/Article/details/gtlnfphyam.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtwesdmowz.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtbwzmkcqz.html

SAVEPOINT sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtxuhzqqmy.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtswqrhhkc.html

[Q69] 查看执行计划
来源：http://dali.yanxiufei.cn/Article/details/gtpkjuuexf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hammf.cn/Article/details/gtkjeyfcdg.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtjhwveiwp.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtbcvfckda.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtyvfzxdhn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gtladnnzil.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtzcjcmgsu.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtoyfinzeb.html

[Q73] 查看表状态
来源：http://dali.jlsjyb.cn/Article/details/gtfofsspeo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xinyue.icu/Article/details/gtjzpvnfzv.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtbfmyfnlg.html


<!-- 参考信息 -->