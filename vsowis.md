代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtktlmjvdc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtldsonjzw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtawvuphem.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtlldqpdpc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrmgngonj.html

O. 并发与异步
来源：http://dali.redwolf501.top/Article/details/gtickfbdeq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteknwsswl.html

[O01] 启动一个线程
来源：http://dali.kuanghao11.cn/Article/details/gtolkmxuvn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cashguo.top/Article/details/gtelfrkkbh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gtivyxquim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtxewtjgyu.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gtrpuhnfdr.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gttrdzbbaw.html

Go:   go f()
来源：http://dali.kuanghao11.cn/Article/details/gteommrjlr.html

Ruby: Thread.new { f }
来源：http://dali.vqdsnc.cn/Article/details/gtrufjbumt.html

C#:   Task.Run(() => F());
来源：http://dali.gaohongyu789.top/Article/details/gtklfviyws.html

[O02] 使用线程池
来源：http://dali.yuxming.cn/Article/details/gtuompkfdo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gtjygkqtxv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtazkcalzz.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtjcfaxmet.html

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtjihdxuiy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gotoacloud.top/Article/details/gtpgdaffpv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtgghafkfy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtowdnefyi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aibaodan.cn/Article/details/gtslnnpwpt.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gtekmflkfm.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtdbvryhhf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxjvednw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtefdvjsxh.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtxoycodmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtfrfujwqj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuanzhike.top/Article/details/gtnpgawfaz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtgkfyxxqa.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtjsejrlrl.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtvueznihf.html

Py:   async def f():⏎    await g()
来源：http://dali.wangdashe.top/Article/details/gtbrwoemzp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxegnonbr.html

JS:   async function f() { await g(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpstsvrtz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gthxvwmike.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gtwlzrdwrm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtyphesjnt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtqpyeqqcp.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzreukqwj.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gtywmrgmph.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtopgbxrqk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gtyfpgctkf.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtnnmygtgh.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtgqygmglx.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtnvgbiikx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtldbdaysz.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtszbjvxge.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gticmsqwdb.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtissowvfh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtonsxwghd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtdbttasog.html

JS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtzvjwkvdo.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtwwqmovsb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sufxvd.cn/Article/details/gtbxaokmib.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtgtafaddy.html

Ruby: // fork 块
来源：http://dali.hammf.cn/Article/details/gtlsfzskgf.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gteerwyvta.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtbwrqrryx.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyutgremh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpcbafqqm.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtelfixffn.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtsrhvucig.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtsatumzxb.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtyzmggnkj.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtlhakydci.html

Java: UUID.randomUUID().toString()
来源：http://dali.hysaishi.cn/Article/details/gtmryesvyz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtijkymdzw.html

Ruby: SecureRandom.uuid
来源：http://dali.hfpthk.cn/Article/details/gtqdjhliwr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtkpwixwma.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tianlin.xyz/Article/details/gtzmmzistn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gtuvtgscnh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtfixvcoaj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pengpengdd.cyou/Article/details/gthhjovgwn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gtzmnrhjtz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtscqyucgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gtwmqufosh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shuidangran.top/Article/details/gtphwkysob.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycaaccpj.html

[P03] 生成短随机字符串
来源：http://dali.aibaodan.cn/Article/details/gtfhwktvlw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gthezybxxe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtuipucqeq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtmanfdsin.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtrtjhyqsj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhengqikj.top/Article/details/gteaqxopra.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtlpswttmz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cucudq.cn/Article/details/gtcmqavszt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtsircixlz.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gttpamiazc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gthasdtdgj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtsuacwsig.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gtdfvxbmif.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtuwzjfaqw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtjmwskyhm.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gttiohultl.html

Ruby: x.length;  x.size
来源：http://dali.chenzaomai.com/Article/details/gtdguvqdft.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gttabjbavg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtihiydnnx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sufxvd.cn/Article/details/gtktpsyojf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtgheipgop.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtoxmscqwg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtkwpxksrs.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtmaxetttj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtsooaugrn.html

Ruby: a == b
来源：http://dali.yongpay.top/Article/details/gtubzdtjcu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gthcrsxrvz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtanjmuvxe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtqhcdgkca.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtbpijauvm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xinyue.icu/Article/details/gtlbzvkbmy.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtpwwuiajg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtvbnqdopj.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtmsdfswzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yanxiufei.cn/Article/details/gtudjlazgx.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gtkeyccmbz.html

[P07] 防抖与节流
来源：http://dali.0kj1m.cn/Article/details/gtuuslucho.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtuzjjrrkj.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtipkulykc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtsokxscwt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.vqdsnc.cn/Article/details/gtjfhjqnxf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigfzy.top/Article/details/gtisbbpiea.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.vqdsnc.cn/Article/details/gtcekmjjry.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gogol.net.cn/Article/details/gtyomkpoha.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtszyngnpz.html

[P08] 处理浮点精度问题
来源：http://dali.shanyushiyangtech.top/Article/details/gtuliwckkw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtqbedigox.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtspjahppw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtjdncplvx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gtcblxbofq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtxqhrtpvc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtpudmoqlv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gtdgpvwxsj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtigkjvqlu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtftjkcfvx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gtyoocescc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmlkdvgzz.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtkhwricux.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtpeylvvji.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xinyue.icu/Article/details/gtkmowbmkc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtelfmzczo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtjxgdmaik.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtgeqkgtpj.html

);
来源：http://dali.yj20258.top/Article/details/gtrdhzyjnr.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijgtvnsb.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtlamrgtbz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtpgeamlkn.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtgaohdrii.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258.top/Article/details/gtbsqcsnkg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hywenlv.cn/Article/details/gtnyizhxzp.html

);
来源：http://dali.daxiang520.top/Article/details/gtmhqjgucm.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtpjzqieyu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtxyucyfds.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtpypmcivx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtgfvpqjvd.html

[Q05] 重命名列
来源：http://dali.hnqzz.top/Article/details/gtxxwmahci.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjvmmgzt.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmvnzaae.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtfdvvfnlz.html

[Q07] 删除表
来源：http://dali.feifeiyinyue.top/Article/details/gtyezecqmw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtuggakbne.html

[Q08] 创建普通索引
来源：http://dali.yj202588.top/Article/details/gtdokbmzxq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gttytxokfm.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtwcxrmtiz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gtxkqhxwrn.html

[Q10] 插入单行
来源：http://dali.yuxming.cn/Article/details/gtzdstolqv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtngmlxyhu.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtumfkxfhk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtcmnmhuct.html

[Q12] 插入后取自增 ID
来源：http://dali.gogol.net.cn/Article/details/gtzxgwaqwp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.quarkkingdee.top/Article/details/gtnbdyphff.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gttuuawuqn.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtiggosrts.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xinyue.icu/Article/details/gtknpdzoxi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtbfmrpncn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtuvbbeoeb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangshuangyany.cn/Article/details/gtovkdwmzs.html

[Q15] 查询全部
来源：http://dali.cucudq.cn/Article/details/gtcudhwvde.html

SELECT * FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtalvzqqyr.html

[Q16] 查询指定列
来源：http://dali.shzxlz.cn/Article/details/gtpganrmxx.html

SELECT id, name FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtoaxacumb.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gtogzynfyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtkolrdidj.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gttgvnwobz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtlxwjjnmm.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gtrhjgcqjb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtxricwznw.html

[Q20] IN 列表
来源：http://dali.birdmap.top/Article/details/gtdnpvdtod.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtwhopvojc.html

[Q21] 空值判断
来源：http://dali.ybcxt.top/Article/details/gtohpvvofh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtbnwaokti.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gtyfyitywb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtlrtsppxo.html

[Q23] 分页
来源：http://dali.hfpthk.cn/Article/details/gtxochkoeb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhoulong.xyz/Article/details/gtmxiqpiih.html

[Q24] 去重
来源：http://dali.tian-w.cn/Article/details/gtswanmqgl.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtsxawmgof.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtvymroabm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtcghozrrf.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtrrzgasge.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtpmfvfkpg.html

[Q27] 条件计数
来源：http://dali.yuxming.cn/Article/details/gtacfkpjru.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtryazwdoo.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtehndhvyx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtvmaesbzz.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtmxqwyktj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gthrzbjfet.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtsygyquvo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gtwrelzbtc.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gtcvvrqydv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtwpwvzmtd.html

[Q32] 分组拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gtttpzeqqh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtigsmofwu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtxscjeyli.html

[Q33] 多列分组
来源：http://dali.svipenyu.cn/Article/details/gtgcmdntdo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtgmkbnfzp.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtodglpthu.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtsjabgfzn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtjwkdmxhi.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gtokrbutlz.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtarxznobl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtaettiwsd.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtdlgydcho.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtcvlqwkhx.html

[Q37] 右连接
来源：http://dali.cqqwz.cn/Article/details/gtrjxfaurr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtcyudshas.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtwsxqmwpk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gthdkvadxd.html

[Q39] 自连接（查上下级）
来源：http://dali.yuxming.cn/Article/details/gtsiilscfh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtttxxktkq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtxuzqpkob.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtmaqukkwh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.mhx1999.top/Article/details/gtrckhdsks.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtjjbcttnt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleveuupz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.iojbl.cn/Article/details/gtgesjthog.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtuzxnsbij.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtklcrixhv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtacajycne.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ydzc1.top/Article/details/gtjmpfbmvm.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtmrawhmlp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtkqianoyc.html

[Q44] IN 子查询
来源：http://dali.zhoulong.xyz/Article/details/gtvdhntpjc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtbumxwhcp.html

[Q45] EXISTS 判断存在
来源：http://dali.hfpthk.cn/Article/details/gtvdheiokw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangdashe.top/Article/details/gtbrhkhzlq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shzxlz.cn/Article/details/gtvruejcev.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xuetiantiany.cn/Article/details/gtvoaxkkmq.html

[Q47] 与平均值比较
来源：http://dali.cheryme.top/Article/details/gtscihjcsr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtnxvhdwap.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtqlnmlnxm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.nwbrower.top/Article/details/gtkzfxffpc.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gttcrnaans.html

[Q49] 更新单行
来源：http://dali.hysaishi.cn/Article/details/gtohgbxtnm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gteajtmhkf.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtnxtqlonw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtiwhlanpz.html

[Q51] 用子查询更新
来源：http://dali.jianghu66.top/Article/details/gtixhazvgt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtdmnrjtdc.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtskamfsri.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtmiyehpam.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gteiemognw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtuructlxm.html

[Q54] 清空表
来源：http://dali.bjfxy.top/Article/details/gtkxpyivxh.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtzirozjmr.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtlgzbzgzm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtciygpdnm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtdngcajve.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtpdmuzpfp.html

[Q57] 行号
来源：http://dali.dianchejie.cn/Article/details/gtattjtvzj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gtpcowjajt.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtsnlkvmjq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gtqqmbfmcv.html

[Q59] 分组内累计
来源：http://dali.yvedp.cn/Article/details/gtrfwcqsqa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtrgrawpdl.html

[Q60] 取上一行 / 下一行
来源：http://dali.nanxuanxn.top/Article/details/gtibuxwgye.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gtixyzgsnm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtfzmlykne.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gttpemcpxz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtlmqeqrpy.html

[Q62] 分组占比
来源：http://dali.mhx1999.top/Article/details/gttlwscadw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtbixrdsct.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtrytxyblo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhoufjcd.html

[Q64] 提交事务
来源：http://dali.aizwys.cn/Article/details/gtckmsfuts.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtzgrdfoyk.html

[Q65] 回滚事务
来源：http://dali.aizwys.cn/Article/details/gtvqeivtfd.html

ROLLBACK;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpvniesj.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gtmeldjtmg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhengqikj.top/Article/details/gtwdtlmdvv.html

[Q67] 设置隔离级别
来源：http://dali.chenjidiqi.icu/Article/details/gtzsephrhz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hammf.cn/Article/details/gtyyooksqv.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtepngitcp.html

SAVEPOINT sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtcpghypmf.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtwnfjmbye.html

[Q69] 查看执行计划
来源：http://dali.jqgufenzy.top/Article/details/gtndqqcztx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gzhubu.top/Article/details/gtlpsccsji.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtyqaqgzwf.html


<!-- 参考信息 -->