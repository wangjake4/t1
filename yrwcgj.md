代发 wailian999

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtblzpfkjz.html

O. 并发与异步
来源：http://dali.pengpengdd.cyou/Article/details/gtvrkakszt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttopubsdh.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtqppkqaty.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gteglkkbsm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.vqdsnc.cn/Article/details/gtzuydirai.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.havefunace.top/Article/details/gteqihgrft.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclcpsvpz.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtfkzlemxw.html

Go:   go f()
来源：http://dali.hfpthk.cn/Article/details/gthkvluyot.html

Ruby: Thread.new { f }
来源：http://dali.haohaochexian.top/Article/details/gttkwfzoji.html

C#:   Task.Run(() => F());
来源：http://dali.shzxlz.cn/Article/details/gtcjgqpmgl.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gtkugedxea.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gttjyfksmv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gtfbbhimss.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtejscwuah.html

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtcpfywhde.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guannengcc.top/Article/details/gtovqgvfwu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtqobkzfej.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjuhmmrg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtrrrilzgq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gtiruxhjip.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtfplwelhz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtiblnpvfr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gtnxehlpnb.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtgfdqjfrl.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtsbaucqnu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gtnwxsalcw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtsoralptz.html

C#:   lock (gate) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtfagiujrk.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtwvdjexel.html

Py:   async def f():⏎    await g()
来源：http://dali.yangfankeji.com/Article/details/gtzpywxfbk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxwuengo.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtzncbtffz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzhlqfghr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtunyeimls.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtnhpwctfh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtnrtqkowm.html

C#:   async Task F() { await G(); }
来源：http://dali.shuidangran.top/Article/details/gttajmyiav.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gtvbdzolgq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtglgvtjel.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.feifeiyinyue.top/Article/details/gtiqclaecc.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtetvpzaxi.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtnjrtdzks.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtzmirsiyx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhixingplan.top/Article/details/gtvlhhodbr.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gttairidgd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuanzhike.top/Article/details/gtmyumgabp.html

[O06] 使用进程池
来源：http://dali.316326.xyz/Article/details/gtlzptyyev.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtshffzpzs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cheryme.top/Article/details/gtauxgsecb.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtxbzfctbl.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtqquvuuuh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gtijrejpxe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gtsfcfcniu.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gtziuiqfsp.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtivsezgwb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthzpymlzg.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtrhquujty.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkdtamtng.html

[P01] 生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtladozohw.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangtech.top/Article/details/gtouxrqeyg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gthkzyrily.html

JS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtxjwvbcow.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gttdovaoug.html

Java: UUID.randomUUID().toString()
来源：http://dali.yvedp.cn/Article/details/gtvlrrhtgp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtgwyycxqv.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtawxhsnql.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtmuwuhdxy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkafjdkim.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gtjiccxmqy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gtdzcmtryq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtfqzqeskx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gthvbkkhpg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtxrxatszc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj20258888.top/Article/details/gtgrndsvzb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tian-w.cn/Article/details/gtekigwuni.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtucsceveu.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtuyxsbwfy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ybcxt.top/Article/details/gtkatnlbyo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtydzkxkqk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmoytyfu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgzsdlxi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtoaufuunu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gthcdnyabe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtyyhjmxtp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtppoctggr.html

[P04] 求长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtuooafnvn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtmuayytkj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtcoftbjun.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtxjhtyvjm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtfstrrryo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gtpmeyghwt.html

Go:   len(arr);  len(m)
来源：http://dali.birdmap.top/Article/details/gtcyzsbgrh.html

Ruby: x.length;  x.size
来源：http://dali.guannengcc.top/Article/details/gtxmrilgsl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gttbmpylvf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtbynqjyei.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutnadvvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daxiang520.top/Article/details/gtjzxwmduf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gtpskzmcug.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtgquhymcn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtgzsevokg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtvvrzaifc.html

Ruby: a == b
来源：http://dali.ppjwa.cn/Article/details/gtudicvhjn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtctaralhy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtxdgleyia.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtlvgnzeeg.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqvixrme.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ehwqpu.com/Article/details/gtaazcywnb.html

TS:   if (x == null) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbmxooio.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtcrhyluyy.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtdujkcytg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtizalpsxz.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtsvmpzplx.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtlxqorylw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yueranfly.top/Article/details/gtrcolkyyo.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gtdvorglcq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gtckgzudmh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtmkramxcj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtkspxzuiq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dianchejie.cn/Article/details/gtyuxkuebh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtctmryhvu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxinkj.top/Article/details/gtafaobsed.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gtifhjdoko.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtgkbjcpur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtasyqrzcr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cqqwz.cn/Article/details/gtlilwbabw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtoqscxofb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gttflettje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sysykeji.top/Article/details/gtfrlvhnjt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gtieysjzgo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gtakpmsfit.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtvbbfcmvt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.cucudq.cn/Article/details/gtioepbyfn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtjkbkyhma.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqudyptsn.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtnqrteeaj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtjiprlptl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtmpefuexi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gthsycdtku.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxdjjrvo.html

);
来源：http://dali.jiagoushi.top/Article/details/gtdirboxsw.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtylimircy.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtazntreee.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtpzdsjwtc.html

user_id INT NOT NULL,
来源：http://dali.jlsjyb.cn/Article/details/gtqwkpywuu.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gtsbiqvhoq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shzxlz.cn/Article/details/gtupimpzup.html

);
来源：http://dali.gogol.net.cn/Article/details/gtvgshmnwp.html

[Q03] 增加列
来源：http://dali.shangyingyoupin.top/Article/details/gtsaoltalc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtgtjuggmk.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtikwlzfxj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jianghu66.top/Article/details/gtvlschqha.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtcmwxjbxy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfybefzwa.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtdrbfbequ.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.quarkkingdee.top/Article/details/gtzdoarbpa.html

[Q07] 删除表
来源：http://dali.zdqjudy.top/Article/details/gtlftamdwr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jlsjyb.cn/Article/details/gttcgkqsbm.html

[Q08] 创建普通索引
来源：http://dali.yuanzhike.top/Article/details/gtlaxnvjzv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gtrkdxiayb.html

[Q09] 创建唯一索引
来源：http://dali.gzhubu.top/Article/details/gtjmkaezyo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gtxwdlherx.html

[Q10] 插入单行
来源：http://dali.guowangkeji.top/Article/details/gtllvrinar.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvtysxoh.html

[Q11] 一次插入多行
来源：http://dali.shangyingyoupin.top/Article/details/gtclmfnsjy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtjfjtyush.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gtwmawswbd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gtragxflsa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtnsrtzthr.html

[Q13] 忽略重复插入
来源：http://dali.hongshengwenyu.top/Article/details/gtfdgajilq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtwghgmvjw.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gtnsapplim.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gtwpfbdhkc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zycfv.cn/Article/details/gthcvqwdlj.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtgqywdmow.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtgqdefbdq.html

[Q16] 查询指定列
来源：http://dali.guannengcc.top/Article/details/gtekqhcjlp.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtkrdordii.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtlhhvvpis.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtryvhdfsc.html

[Q18] 模糊匹配
来源：http://dali.yj20258888.top/Article/details/gtfuetbkmc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yonumen.top/Article/details/gtcnkrxauf.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtbofcfucc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guannengcc.top/Article/details/gtyesrurcq.html

[Q20] IN 列表
来源：http://dali.guannengcc.top/Article/details/gtmhpmnzgs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yonumen.top/Article/details/gtfuhvxins.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtudeirzmw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtloiazuoi.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkizlsgx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.wangdashe.top/Article/details/gttzuorpfv.html

[Q23] 分页
来源：http://dali.nanxuanxn.top/Article/details/gtuhxebeiv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.bjfxy.top/Article/details/gtmhfgbgph.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gtbahcgcjz.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtckbdkvqy.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtwhcclyvt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtcsppiwie.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzxpkciq.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtvmynvfyp.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtcxbkugmx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.c1oappe.top/Article/details/gtjxafbrqn.html

[Q28] 求和与平均
来源：http://dali.ppjwa.cn/Article/details/gtcyrgbnza.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtzkhftaah.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtrgnplcqp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloltakio.html

[Q30] 分组统计
来源：http://dali.xuanzx.com/Article/details/gtkxhviypi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtwyzanrey.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtyrxbmnub.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgfzy.top/Article/details/gtnbcfwydd.html

[Q32] 分组拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtpsgztszg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtbvivkqhe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtoajkzqlz.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtfduumnzr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtbmpxyvmu.html

[Q34] 每组取第一条
来源：http://dali.vqdsnc.cn/Article/details/gtorhekyqg.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gtcccomtbh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cashguo.top/Article/details/gtwgrtzvho.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gtogplqcpw.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gttvlyhakz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gthchhfaku.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gttxieqpqp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinqigfzy.top/Article/details/gtmsyvmqah.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtgwzmscel.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gtdbdnsenc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xziqi.cn/Article/details/gtlpsavdao.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhengqikj.top/Article/details/gtapejphga.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtgssgkbdn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtmgsfik.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtxbramglh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gtlcrycqhh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.vqdsnc.cn/Article/details/gtbvvnnrec.html

[Q41] 多表连接
来源：http://dali.chenlongwang.top/Article/details/gtyvhhqchc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jianghu66.top/Article/details/gtnockyshs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gteszajvki.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhongyouzk.top/Article/details/gtoyedzogx.html

[Q42] 连接条件附加过滤
来源：http://dali.cashguo.top/Article/details/gtduuqxcfq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gtseicrhyz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gthydboeza.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtpkhbgbar.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gthxinbtuw.html

[Q44] IN 子查询
来源：http://dali.zhixingplan.top/Article/details/gtlsvuypls.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.quarkkingdee.top/Article/details/gteejfmweq.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gthpbzfize.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtszvcnzol.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtgzxqbpsz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtygztsrrp.html

[Q47] 与平均值比较
来源：http://dali.aizwys.cn/Article/details/gtpmnagvcm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtocmonwtw.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtwqfdflfp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dianchejie.cn/Article/details/gtdludonzn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gtfjjwlbxg.html

[Q49] 更新单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhsycxgz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtydzuezae.html

[Q50] 批量更新
来源：http://dali.zhoulong.xyz/Article/details/gtppalxcbr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtfovwzygo.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtmkwtsiha.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ivvv.top/Article/details/gtqjrlbbah.html

[Q52] 删除指定行
来源：http://dali.pengpengdd.cyou/Article/details/gtdbhyprqq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtbjpqdoyw.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtuuuoaors.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gttnkezgne.html

[Q54] 清空表
来源：http://dali.hnxiangtu.top/Article/details/gtitbuwnxs.html

TRUNCATE TABLE logs;
来源：http://dali.yangfankeji.com/Article/details/gtqenvejul.html

[Q55] 排名（并列占位）
来源：http://dali.kuanghao11.cn/Article/details/gtmwfnmmdj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gtphcpobpv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shuidangran.top/Article/details/gtmcbezdka.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jyoumei.cn/Article/details/gthxrvtyqx.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtkgcjcwzu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtljjfcnjo.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtpuszazux.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtzoehqazu.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gtzeftcpez.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gteyxnwkqj.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxinkj.top/Article/details/gtralavwyv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shzxlz.cn/Article/details/gtduowkjvq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtwzilqysh.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtkdewwxax.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtmsesvlbx.html

[Q62] 分组占比
来源：http://dali.hfpthk.cn/Article/details/gttrfvcptw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtexbggjfc.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtzckviijo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.feifeiyinyue.top/Article/details/gtcwzrgwut.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtdfqoegik.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtylmjnhjq.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtibtdunhf.html

ROLLBACK;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmjhqvxh.html

[Q66] 行锁查询
来源：http://dali.bjfxy.top/Article/details/gtmivohxxj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sweek.top/Article/details/gtfystpieb.html

[Q67] 设置隔离级别
来源：http://dali.jinghuilouyu.cn/Article/details/gtclsqobes.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gtbbuubjbx.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtjoxssgla.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmqrqktil.html

ROLLBACK TO sp1;
来源：http://dali.pycfn.com/Article/details/gtjvgvohdz.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtuvirqphk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtilzbzd.html

[Q70] 更新统计信息
来源：http://dali.zhoulong.xyz/Article/details/gtiytsgnui.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gtomijydgw.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtviimttqx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtjuqplygb.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtbirhhpip.html


<!-- 参考信息 -->