代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gtqauwvrub.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gturcllmtm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gthbzuiaac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtpcojapfn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gtlwknmouz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtieqbqtrz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtzjsskdqy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtiheqwimr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxtmywxcp.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gtcizymqul.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgizpvtub.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoyptwva.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtdmnxrtab.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtilnxvbyw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gtnreflmfi.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtiijvviyu.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gtjmrmheuo.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gtwrbqrpmq.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtbogqwbar.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gtfsrttcyv.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gtmijuzewf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gtjhacjzpt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jlsjyb.cn/Article/details/gtrlhpliwl.html

JS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtezdcddfr.html

TS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gtyqljpqfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.snrcjt.cn/Article/details/gtehemnuly.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtnvruwyrw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gtpmghoreh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gthexcjylc.html

[O03] 加锁保护共享数据
来源：http://dali.aibaodan.cn/Article/details/gtnnvvefhu.html

Py:   with lock: shared += 1
来源：http://dali.zhixingplan.top/Article/details/gthueiagfo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtcdrfinkl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtlmjhpode.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtzfcbxqxl.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtpcoavcfx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtsurykjaz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtrfhqvecp.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gtfmampkrd.html

[O04] 定义异步函数并等待
来源：http://dali.zhixingplan.top/Article/details/gtscnvknpb.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtbimucwjy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gtsjzozfgl.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtyggymdkw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtixooaiyq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtijceredt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtdhdivcfr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtuomwthff.html

C#:   async Task F() { await G(); }
来源：http://dali.ppjwa.cn/Article/details/gttrfccqlu.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gthzafxseh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.mhx1999.top/Article/details/gtznaiggzw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gtwxililav.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtivzalrzp.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtwevvvfet.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtmjkhoydb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtylvcttnw.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtaseofvda.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtbwodasqx.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtyonzebut.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtncbnqjvb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daxiang520.top/Article/details/gtxhmwtgqd.html

JS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtxamfpfmw.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtawvrhtfa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtcpuyhomr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtkwejslyk.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtsqggjngt.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gthffgvrzj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlgwozqws.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtmkdwopop.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwsdqvayi.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtfjwchodo.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gtmsusvezu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yangfankeji.com/Article/details/gtctvvgqhk.html

JS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtmbrwfajn.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gttdywemsn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtbinwoxum.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtcmmgmozp.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtxtzdxtqg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guannengcc.top/Article/details/gtndaehulk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gtftghyfvr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gtirqpdfgg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtmihfrtjr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gttmpqeaxg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.feifeiyinyue.top/Article/details/gtvacqlsfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtqkournmt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtjiiyuzbm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtqoexlngp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.haohaochexian.top/Article/details/gtlxkubnqm.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gttftzefls.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shzxlz.cn/Article/details/gtohgsxnee.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gtcfmmbory.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtbvlfusoj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxzilvdm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gtkgsmqxls.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gtklpvqwmj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuxming.cn/Article/details/gtpccspegy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtlfjmwxfy.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtphaxehah.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sxryk.cn/Article/details/gtyiitfhyv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gthgsiekxv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtjrzctpjl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtxhuupjlp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gtowbrwdxw.html

Go:   len(arr);  len(m)
来源：http://dali.yongpay.top/Article/details/gtulxbcoqr.html

Ruby: x.length;  x.size
来源：http://dali.xuetiantiany.cn/Article/details/gtnieetksv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gtiiprzssl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtkcnnefjv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdoqhhvu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuanzhike.top/Article/details/gtnywaqawv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gttmqsyhap.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtbifnhjih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gzhubu.top/Article/details/gtimripzgo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkuzssob.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtwmlpuxlk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gthsqrqphu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.daria6918.cn/Article/details/gtjxdromve.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtfomjwioa.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gticwzvkdl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjivnzvdq.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtwifsjwoj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtaljnafvz.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtcbkrluaj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtodsvodvf.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gtvclwksqj.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtsdosmdfs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtodrbkvzm.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtpmxeqobj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gtcalypzlk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtyghnvzol.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtphynmnkf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hnqzz.top/Article/details/gtkeyguhqy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigufen.top/Article/details/gtzhgbgpns.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gtjdkyntdm.html

[P08] 处理浮点精度问题
来源：http://dali.tian-w.cn/Article/details/gtvwnlhnrc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtleglqxkq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthznwwojy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gtpjfpfsxu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtitqinnmy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gttgrrnacy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yvedp.cn/Article/details/gtgoyjpoyo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.daria6918.cn/Article/details/gtvonwmnhs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnqzz.top/Article/details/gtchgrhekk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtuuehlofl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtwjkrxhjk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnjoadcex.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtsafgancw.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtjhmkjnaz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtawvlpphf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtrwkzaued.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shangyingyoupin.top/Article/details/gtsonuxlgv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gtbswqsuft.html

);
来源：http://dali.ivvv.top/Article/details/gthdfafwde.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdrwjvya.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtxvaftgmp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtlwxvyzeb.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtturuaygi.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtxxupcivu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtjrxnhxck.html

);
来源：http://dali.guowangkeji.top/Article/details/gtczmzhpth.html

[Q03] 增加列
来源：http://dali.nwbrower.top/Article/details/gtkfdpfyoe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gttppefolg.html

[Q04] 修改列类型
来源：http://dali.redwolf501.top/Article/details/gtiumuvhsh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtzdcchvgs.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtchgsgakn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shangyingyoupin.top/Article/details/gtsukkaimb.html

[Q06] 删除列
来源：http://dali.jinqigfzy.top/Article/details/gtkiqepatk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtlvosagcl.html

[Q07] 删除表
来源：http://dali.ybcxt.top/Article/details/gtfotrggfl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gtofrixnbw.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtxdsxdmqr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtabffgfop.html

[Q09] 创建唯一索引
来源：http://dali.zhixingplan.top/Article/details/gtphogzqln.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gttgqmxyaw.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gtwtjsfhoy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtbdkwemnj.html

[Q11] 一次插入多行
来源：http://dali.ivvv.top/Article/details/gtldxdrett.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gtrzsulddz.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gtucstktkj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jianghu66.top/Article/details/gtjakerwkt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuoeyifza.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gtfhqxgogj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cucudq.cn/Article/details/gtbcjinpvj.html

[Q14] 存在则更新（upsert）
来源：http://dali.cucudq.cn/Article/details/gtzlmcqopg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj20258888.top/Article/details/gtdnofndug.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljwzkmvo.html

[Q15] 查询全部
来源：http://dali.gogol.net.cn/Article/details/gtelrckqif.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtkvykzxid.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gtynwgmyrx.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtwfwaipcr.html

[Q17] 条件查询
来源：http://dali.gaohongyu789.top/Article/details/gtrlicxnjc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtxyztzttl.html

[Q18] 模糊匹配
来源：http://dali.jlsjyb.cn/Article/details/gtcntiokxc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtojqpakcy.html

[Q19] 范围查询
来源：http://dali.xylfe.cn/Article/details/gthxdjhehx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.guowangkeji.top/Article/details/gttnzxnois.html

[Q20] IN 列表
来源：http://dali.gzhubu.top/Article/details/gtzxvcwqnz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yj20258888.top/Article/details/gtxanmmzuq.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gtmrrfmmsr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtmlxyriso.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtxhhdkrxt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gtdkgczkar.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gtpgzhrdvw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtlorliysj.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gtwwpvmxoe.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtfcszbncv.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpowaosz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtvcyeoowz.html

[Q26] 计数
来源：http://dali.jyoumei.cn/Article/details/gtytdlexlq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtoqmqsekv.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtopuslhyt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.fengsongda.top/Article/details/gtyovhsmaw.html

[Q28] 求和与平均
来源：http://dali.nwbrower.top/Article/details/gtskvsnzol.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtxeowldyk.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtmepgtiab.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gteghkdsej.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtunkgxqtz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gtgnyjiujv.html

[Q31] 分组后过滤
来源：http://dali.redwolf501.top/Article/details/gtoauphxzm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhixingplan.top/Article/details/gtzdeswjhz.html

[Q32] 分组拼接字符串
来源：http://dali.tian-w.cn/Article/details/gtszcnqnam.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtdnayfwsv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtyflzdhez.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtdrbckzux.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgfzy.top/Article/details/gtoimzompw.html

[Q34] 每组取第一条
来源：http://dali.nanxinkj.top/Article/details/gtzmpytjkz.html

SELECT * FROM (
来源：http://dali.ehwqpu.com/Article/details/gtutrwlgng.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtlvjzdiis.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtuytioxgu.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtnhyudiqy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtleqelqnl.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gtqjwikvhz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtlbjdkssd.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtuzcjbvgs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtdylekxuv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gthrbketoi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sysykeji.top/Article/details/gtlvgkljks.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtpbejlvjj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gtpzigmljv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtaacpceue.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yanxiufei.cn/Article/details/gtkprlncfr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.meibo888.top/Article/details/gtlmhwaxdg.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdzsabiq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.snrcjt.cn/Article/details/gtkbxmzzqb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtrgnryjex.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.haohaochexian.top/Article/details/gtdpqsimge.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwcdkndt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtwwbttbyr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtzwvnmcnj.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtdeoheszw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnhurzud.html

[Q44] IN 子查询
来源：http://dali.0kj1m.cn/Article/details/gtcedrqgtx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtleykcgmh.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtrsdcejnn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtdzxzvbcs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtermuogvk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyizdwlzx.html

[Q47] 与平均值比较
来源：http://dali.xziqi.cn/Article/details/gtyvkfbrts.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangdashe.top/Article/details/gtkuvtxfzf.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gthcizwjof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gtmzwjxcfg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtafhozfco.html

[Q49] 更新单行
来源：http://dali.tanke756.top/Article/details/gtcjusdhap.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtawxfizoy.html

[Q50] 批量更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitfbtwkk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtykoicylx.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gtfsvyubxy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yangfankeji.com/Article/details/gtvvgiqrvr.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtrbzzmejf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shuidangran.top/Article/details/gtlmelznal.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtadpqynhw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.aizwys.cn/Article/details/gtmsszokkh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtcyvhmqgo.html

TRUNCATE TABLE logs;
来源：http://dali.andypj.xyz/Article/details/gtpiddisql.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gtongjhviq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtxjozeyzr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sysykeji.top/Article/details/gtferucbaz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gtcbrpzynr.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtoqutsipw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258.top/Article/details/gtftyolbkz.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtlhfxmxzy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtggznktet.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtksrlutzn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtxuilshme.html

[Q60] 取上一行 / 下一行
来源：http://dali.hfpthk.cn/Article/details/gtwvrfehpz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jlsjyb.cn/Article/details/gtpnovnxyh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tanke756.top/Article/details/gtwebnsene.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtvashlipe.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtfkvojftc.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gtxrbzmkyy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtiaqlxdpu.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtogsarxmo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gtfdlopjki.html

[Q64] 提交事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunpnnkxs.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gthausqcux.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gttnffluyg.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtuoxefhym.html

[Q66] 行锁查询
来源：http://dali.zhoulong.xyz/Article/details/gtzgvhjtqj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gtlllrusyb.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gtwtfvpoje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.chenzaomai.com/Article/details/gtpqkhrsai.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtdgtdamzw.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtryarbmye.html


<!-- 参考信息 -->