代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gttbugkaus.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gtdubiquzw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gtxvnvkybg.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtekexpnmv.html

Java: new Thread(() -> f()).start()
来源：http://dali.tianlin.xyz/Article/details/gtlzrmztuj.html

Go:   go f()
来源：http://dali.cqqwz.cn/Article/details/gtmeugzzlt.html

Ruby: Thread.new { f }
来源：http://dali.nanxinkj.top/Article/details/gtvgjusvgc.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtuugbhxcy.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtrcmmzqiy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gtpohlayjj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtcmsgyyen.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtrrsbmktk.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtpsvcvelq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtdpuonewf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtipodgilr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gtxlusfezz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtcwnsivsd.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtnredykzi.html

Py:   with lock: shared += 1
来源：http://dali.tian-w.cn/Article/details/gthaxvbxpr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ydzc1.top/Article/details/gtcxgimyjo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.meibo888.top/Article/details/gtvxeqcqju.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttsorcnh.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtzfyxxvxo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtqmkhbcyz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gttaqtoonj.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtesvxasyp.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycbkxarm.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtcbwqcdta.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgloacrks.html

JS:   async function f() { await g(); }
来源：http://dali.ydzc1.top/Article/details/gtxghauygt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtkbfzrhwl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtdarhkkqa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zdqjudy.top/Article/details/gtlkqnyzdt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tanke756.top/Article/details/gtvoysrori.html

C#:   async Task F() { await G(); }
来源：http://dali.tianlin.xyz/Article/details/gtyjhvfhku.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gtijqlnzeu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtthbxuhzh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtozsjeixl.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtzcdnnfwq.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtgskzffcg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gtyynbxqxd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yonumen.top/Article/details/gtjsslvvfw.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtgnqemnwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gtwgxymouy.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtyrvrmvpy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtgczuqaad.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtjzorhyog.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtbybrizbs.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtgsrhxcgs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtmrukeklz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtepvyygoy.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdkncsnq.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gtsvapsbtm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gttsmusniq.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtxajtkwux.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkvfiemm.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtvfppojfk.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gthikbzgbe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhffgnum.html

JS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtfnqnqdkc.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtvlzqezpo.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtdxkvoczi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtgfkawjrf.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtabwqkkmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yonumen.top/Article/details/gtlofsesjo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gtkcqkufvt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zycfv.cn/Article/details/gtfctlsrmj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhengqikj.top/Article/details/gthldkrxyo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtxmzwtaoj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gtnydeaitz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtmdzefsyb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtximxzbfv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.andypj.xyz/Article/details/gtdweqhbmq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gtbaqbfwex.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwmblbrb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtmfoimtms.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gteqbcyxcw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gttvgwrekf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtxfvhztzj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gtfyuzxlqv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtryqqsguy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtsejjlapm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtppiazney.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtiajfsfvo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gtrxkckftc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtjfybxurc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtoyksngdl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtxzbjoqwh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtkhfmarfj.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtmqwfsfcb.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtxgicikag.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jyoumei.cn/Article/details/gthezspwyi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.birdmap.top/Article/details/gtubtzbrep.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cucudq.cn/Article/details/gthkdqsqug.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gtvjzwhbzs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.bjfxy.top/Article/details/gtplxfzkte.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtzrnasuyy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtximxraym.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtyomfhqlp.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gticypwguu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtnbinhojk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtyowhrlss.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtxphgoazk.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkhkooysk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sweek.top/Article/details/gtulkmzzcx.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnbrpqwog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guannengcc.top/Article/details/gtxivzpbpi.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywdmxedi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gtwhnwnnhl.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtmnsvxqlc.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtukpwedfm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gtvrsyixwv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhengqikj.top/Article/details/gtmexetaoy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtznzadbyj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtrcofvbkw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwywwmvvn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gtydocwrlv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtslkruiej.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtablteoqd.html

[P08] 处理浮点精度问题
来源：http://dali.daxiang520.top/Article/details/gtpxmyqdum.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtzplmaupe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gtkttylmjo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhwllzxa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtjynpvyri.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.havefunace.top/Article/details/gthqimceor.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gtytdtkkok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuetiantiany.cn/Article/details/gtblblxatn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuetiantiany.cn/Article/details/gtjrusklul.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtblqwzokd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtrckqxhoq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtszlngvct.html

[Q01] 创建表
来源：http://dali.0kj1m.cn/Article/details/gtkgkmgtkh.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtksalglxc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtetqzmdxv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtokexgcbf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.chenlongwang.top/Article/details/gtqhnceyrv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cdnleiting.top/Article/details/gtrkdairqu.html

);
来源：http://dali.guowangkeji.top/Article/details/gtdqrghcmw.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtvluxemmj.html

CREATE TABLE orders (
来源：http://dali.dianchejie.cn/Article/details/gtposrzcwk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gtsbqhgmxu.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtcbdmskzc.html

amount DECIMAL(10, 2),
来源：http://dali.zhoulong.xyz/Article/details/gtyftthaid.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtdyqxvjrb.html

);
来源：http://dali.cucudq.cn/Article/details/gtsxrhbjxk.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gttmdziujr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sxryk.cn/Article/details/gtfcpdlukj.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtxytoolpt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtydlhhqct.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gtqsapimew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtikbalcyx.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gtcjetzhae.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.kuanghao11.cn/Article/details/gtijowwdlo.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtrtqyoslw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtyrumqpil.html

[Q08] 创建普通索引
来源：http://dali.aibaodan.cn/Article/details/gtlvprcvej.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.bjfxy.top/Article/details/gtohqzvjer.html

[Q09] 创建唯一索引
来源：http://dali.guannengcc.top/Article/details/gtknmjpfww.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzdvbpst.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtdzjeeevn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtqjotjojm.html

[Q11] 一次插入多行
来源：http://dali.iojbl.cn/Article/details/gtbhwuhvma.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtgnwyjmcg.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gtoaqujucm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cqqwz.cn/Article/details/gtemqkgcnd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuikkhcsm.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtswcqptzd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtqljqytmw.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtzfclzfuv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtkdejdcza.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtlvmzohuv.html

[Q15] 查询全部
来源：http://dali.hysaishi.cn/Article/details/gtlqksogug.html

SELECT * FROM users;
来源：http://dali.daxiang520.top/Article/details/gthwlfrcud.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgcingtb.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgfrmlir.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtpnagzfdq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtijgpfuzd.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtrsrxcxhs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yueranfly.top/Article/details/gtqxadqxfq.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gtbcrbulvo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtnqkvotyq.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtmbbutytz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jiagoushi.top/Article/details/gtziymaonr.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtodfocior.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cdnleiting.top/Article/details/gtcushzwoo.html

[Q22] 排序
来源：http://dali.hfpthk.cn/Article/details/gtmlatvefy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gtwovpzqap.html

[Q23] 分页
来源：http://dali.gzhubu.top/Article/details/gtrvmvopcd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gtndaxtnhc.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtalsggpei.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimddrmiq.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtzbgvagkw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gtfmcwlqez.html

[Q26] 计数
来源：http://dali.havefunace.top/Article/details/gtdvtsivuv.html

SELECT COUNT(*) FROM users;
来源：http://dali.birdmap.top/Article/details/gtsuxusbqp.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtjxppakui.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aizwys.cn/Article/details/gtaopsxpvb.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gtyxhbvsrp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtvqcywslc.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gttshkkpqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvrvdsvr.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gttzgqzwkq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtwdeveqeh.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gtvskdnhwq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhongyouzk.top/Article/details/gtosyswgme.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gttpkfhhlx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtzjzxmqbz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtdcgpftgm.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtnkuumyat.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtgityaipa.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gtvdvqwkxk.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtqdrpydrc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtudtqyjqi.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtxukjuemg.html

[Q35] 内连接
来源：http://dali.cqqwz.cn/Article/details/gtjwguluuw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlhegpsr.html

[Q36] 左连接
来源：http://dali.gogol.net.cn/Article/details/gtzfhwicwj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtdrjysela.html

[Q37] 右连接
来源：http://dali.jyoumei.cn/Article/details/gtduknbrxa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenlongwang.top/Article/details/gtfdhpzzmx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gteepklvnk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gzhubu.top/Article/details/gtlfkejlpa.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gttmhberdv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cucudq.cn/Article/details/gtabyeqdbr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtsjciypoq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gtmtniscps.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj202588.top/Article/details/gtmsttuftt.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtnezemdls.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigfzy.top/Article/details/gtfgnhhsqj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zycfv.cn/Article/details/gtcrriuuri.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtjaseilnj.html

[Q42] 连接条件附加过滤
来源：http://dali.gaohongyu789.top/Article/details/gtfrdkmcbc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xziqi.cn/Article/details/gtdznfmuzg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangdashe.top/Article/details/gtfhovnxjp.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gtxziiuphp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hammf.cn/Article/details/gtgefewqgf.html

[Q44] IN 子查询
来源：http://dali.nanxuanxn.top/Article/details/gttpikvtjn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangdashe.top/Article/details/gtymkesjft.html

[Q45] EXISTS 判断存在
来源：http://dali.wangdashe.top/Article/details/gtndluvoog.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtsydsgnoh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ivvv.top/Article/details/gtnqfivvaj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtyhdlcxga.html

[Q47] 与平均值比较
来源：http://dali.yanxiufei.cn/Article/details/gtlgqwahbw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenjidiqi.icu/Article/details/gtwoqoxqdz.html

[Q48] CTE 公用表表达式
来源：http://dali.dianchejie.cn/Article/details/gtsfipqlyt.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.snrcjt.cn/Article/details/gtshyzcakm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daxiang520.top/Article/details/gthnbzayua.html

[Q49] 更新单行
来源：http://dali.mhx1999.top/Article/details/gtrsdochvt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtrjahnezm.html

[Q50] 批量更新
来源：http://dali.bjfxy.top/Article/details/gtwbcodyuf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtqdnomxfs.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtrblmtcxi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangdashe.top/Article/details/gtiqjfhbpk.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtplhcoetw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtliunjpyk.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gtqcrrupug.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtdreocluc.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtuerdyuke.html

TRUNCATE TABLE logs;
来源：http://dali.jqgfzy.top/Article/details/gtacdfhzqh.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtylzfgpck.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtfqtewusi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gtztsaaqmn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yongpay.top/Article/details/gtsewuixkh.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtdljvpjlf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtcgypbbiy.html

[Q58] 累计求和
来源：http://dali.yvedp.cn/Article/details/gtfnotbcwo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthxmqyuyt.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtkdetiyas.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtvytoifoz.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhoulong.xyz/Article/details/gtzpvbnjmo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gtiknjycme.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gteefhfwmu.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjdsxtht.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtklkmauho.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gtqrzvvdwd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfdiywpg.html

[Q63] 开启事务
来源：http://dali.jiagoushi.top/Article/details/gtvpnojyvp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtymykjcin.html

[Q64] 提交事务
来源：http://dali.yj202588.top/Article/details/gtkygzdimt.html

COMMIT;
来源：http://dali.svipenyu.cn/Article/details/gtqrupdgps.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtcxevddmm.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtemdidqwx.html

[Q66] 行锁查询
来源：http://dali.yj20258888.top/Article/details/gtqyywyzwd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ydzc1.top/Article/details/gttyhgkklx.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtvfxlwljn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xinyue.icu/Article/details/gtqfwkhkcs.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtripujjab.html

SAVEPOINT sp1;
来源：http://dali.bjfxy.top/Article/details/gtccorljel.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtrbffwwoa.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtmgwbeigk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gtzfqbkqoz.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtqjsgjhbo.html

ANALYZE TABLE users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngnwhklg.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtrbqrfezq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtvppuscis.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtsifnawvq.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtbkkascgy.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gttkukojak.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtjtxsgrix.html

[Q74] 强制使用索引
来源：http://dali.redwolf501.top/Article/details/gtkchmdrcu.html


<!-- 参考信息 -->