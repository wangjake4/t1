代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsucvqzp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtvszjyhsh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gtidgbscbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gteelsmtoi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gttjzrmzsh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.smart0.xyz/Article/details/gtmpyopnil.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtnhwaxiqa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gthreglspa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdrzbftoi.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtluhpudwh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtktftmvlo.html

[O01] 启动一个线程
来源：http://dali.guannengcc.top/Article/details/gtdlechewz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gtkmyiepaq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnxiangtu.top/Article/details/gtmwqalwqy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtsvcqtnpu.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gtbxifjfwl.html

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtbpiywxez.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtuaumbbff.html

Ruby: Thread.new { f }
来源：http://dali.shangyingyoupin.top/Article/details/gtkfsqywcx.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gtoerhtcvj.html

[O02] 使用线程池
来源：http://dali.jiagoushi.top/Article/details/gtwkfbawco.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.meibo888.top/Article/details/gtuoedfgqi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sweek.top/Article/details/gthtcgcznw.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtjbqhkyeb.html

TS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtrlcwlwvw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtrshcbktc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtdtakmfii.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtvcirddkp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.quarkkingdee.top/Article/details/gtkzqeghxf.html

[O03] 加锁保护共享数据
来源：http://dali.xinyue.icu/Article/details/gtuwgkeeet.html

Py:   with lock: shared += 1
来源：http://dali.snrcjt.cn/Article/details/gtcytmiwrs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtjmjkrfkz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtslncgtvr.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtpznzktal.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtylydeqjd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gteyeuetag.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtkpprapvf.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtxsljtlvv.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtbmlcmasb.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gtknhnpktn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtjyowagle.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtwfmaipnz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwrtsqsk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtyijyiwme.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gtsboswgnf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtitejkpog.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtpeaaxoqx.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtlffcifvy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gtocapuiqu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yonumen.top/Article/details/gtxbvqicfh.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtebckciqo.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gticpvtdki.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtuluxdjnz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtxwfzeziu.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gterxccfkd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ydzc1.top/Article/details/gttthddoza.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtkicbopok.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpisvzpyu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtvrxhaptl.html

JS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gthkkhpwfu.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtwjtuagtn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cdnleiting.top/Article/details/gtdmcfqgkt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.havefunace.top/Article/details/gtphmthryb.html

Ruby: // fork 块
来源：http://dali.hnxiangtu.top/Article/details/gtgpufcuap.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtzpnnrccd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhlknork.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtwqzfndai.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtaixmbxam.html

[P01] 生成 UUID
来源：http://dali.daria6918.cn/Article/details/gtwyzkfuyz.html

Py:   str(uuid.uuid4())
来源：http://dali.birdmap.top/Article/details/gthquzbvhe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigufen.top/Article/details/gtrcsxffcj.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtctqitiqm.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtzejfperu.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtahhlgoup.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gtyjohtoic.html

Ruby: SecureRandom.uuid
来源：http://dali.hnxiangtu.top/Article/details/gtxkskbdlf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtptinrcts.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sufxvd.cn/Article/details/gtokzkzsdh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gttqapjqte.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gttwxhumpg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.9152youxi.cn/Article/details/gtfqsygwjt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtblrahlgm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtcatcxggb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtcueslvzf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtmuukxidt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtwuofpfox.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtcjfalqly.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtylseddmm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ivvv.top/Article/details/gtjvtpeimt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtcbbsusee.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtktexseds.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtwvvrcpxo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gttdaptbux.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtiglfygwu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfeeldkl.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtcovyyopf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gtehixkaxt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtlxhdyyzo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtuqsjgpng.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtgsowhjjw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gtywlqxney.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtejmtqagw.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gtbfbmdekz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gttjpwtumu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtwwupowtl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xziqi.cn/Article/details/gtouepkmhh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yongpay.top/Article/details/gtbdvzpypo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gturkarfyg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtunpzuybq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.9152youxi.cn/Article/details/gtnnntgkjx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigufen.top/Article/details/gtpybbyaum.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gtwsedlszu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gtcbsryjhq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtjegixsrd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gttymbxnfb.html

PHP:  if (empty($x)) {}
来源：http://dali.dashuyun.cn/Article/details/gtabkfnyvy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ivvv.top/Article/details/gtwcdgwoju.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcqpbatno.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtacymzaah.html

Go:   if x == nil {}
来源：http://dali.yanxiufei.cn/Article/details/gtxwenixxr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtsxbowmdm.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtntjrnzrv.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtggkojqmo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigufen.top/Article/details/gtyevaqeuj.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gteonqqkmv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtmmkraycc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtmbxegwxp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ppjwa.cn/Article/details/gtrfhpmnho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.smart0.xyz/Article/details/gtcxgmqvfq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.fzhhl.top/Article/details/gtzsqdmjvp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.haohaochexian.top/Article/details/gthenncwqh.html

[P08] 处理浮点精度问题
来源：http://dali.zhiwuduotai.top/Article/details/gtjpbhhjce.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gtjvkprbog.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gtoijlvzrp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangshuangyany.cn/Article/details/gtsiqkvozx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtbrxivbbn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gtsoyhaxww.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtezyfmwfi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtminodrpv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtwrzgwyoy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtqiaefktk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtyvlmvwdc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttfvbzmsg.html

[Q01] 创建表
来源：http://dali.cdnleiting.top/Article/details/gtetrwwawd.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtwadwtwit.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtrsoirhme.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtnauslkcn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.wangshuangyany.cn/Article/details/gtjyrcloqm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkicwfsw.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrkghtsu.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtvzajywgi.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtktschvcg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtfbsjneag.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtdfhrasyk.html

amount DECIMAL(10, 2),
来源：http://dali.gogol.net.cn/Article/details/gtapldtmsk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gttjrjrjdr.html

);
来源：http://dali.hnqzz.top/Article/details/gtsxysjlgv.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtyjpyoknq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtrjuxzhce.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtkredfr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtsmneoldh.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtxjyxmnpo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gtnbitreeo.html

[Q06] 删除列
来源：http://dali.yvedp.cn/Article/details/gtrcacrpal.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnqzz.top/Article/details/gtolqnxvri.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gtwukpfzsr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtwpkkotvn.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gtcjauegnr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtughseoav.html

[Q09] 创建唯一索引
来源：http://dali.sufxvd.cn/Article/details/gtcprmbkha.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtxmndikxa.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtuwwwmdqi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtoztpdfwa.html

[Q11] 一次插入多行
来源：http://dali.shanyushiyangtech.top/Article/details/gtfanddqxc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xylfe.cn/Article/details/gtwzbeezbf.html

[Q12] 插入后取自增 ID
来源：http://dali.chenzaomai.com/Article/details/gtxbcvczoc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gtcpzvjghj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sweek.top/Article/details/gtsdvenkrj.html

[Q13] 忽略重复插入
来源：http://dali.yonumen.top/Article/details/gtgelmnjki.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtqjxkqntt.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gtgqurvzpe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtvpwdkoqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yueranfly.top/Article/details/gtkkzlylzx.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtozrwgpks.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gtsgodymsu.html

[Q16] 查询指定列
来源：http://dali.shuidangran.top/Article/details/gtcoddmzlh.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtmbnftppp.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gtdczdjwbk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtnzdrjkmq.html

[Q18] 模糊匹配
来源：http://dali.shzxlz.cn/Article/details/gtkpxroeld.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuanzhike.top/Article/details/gtvirxdwvh.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtfbzccacb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gttkrukoag.html

[Q20] IN 列表
来源：http://dali.wangdashe.top/Article/details/gtsolfzcin.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtdevdfeof.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtievgifrl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtemiwlebd.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gtglxaqlzt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.andypj.xyz/Article/details/gtnzwxqkib.html

[Q23] 分页
来源：http://dali.yj20258.top/Article/details/gtbtrxwhaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtmeltlzap.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtiodpagln.html

SELECT DISTINCT city FROM users;
来源：http://dali.jianghu66.top/Article/details/gtzjzbgzjp.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtstjfcwko.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sweek.top/Article/details/gtphkgxhtu.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtoncvqfag.html

SELECT COUNT(*) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtmaizoqie.html

[Q27] 条件计数
来源：http://dali.xuetiantiany.cn/Article/details/gtonmhbjlu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzabcnqde.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gthnxfgqyw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtfuzuebgg.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtjgmfwgfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.havefunace.top/Article/details/gtztvnjqxu.html

[Q30] 分组统计
来源：http://dali.smart0.xyz/Article/details/gtywaabxxw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gthiedbfdp.html

[Q31] 分组后过滤
来源：http://dali.xziqi.cn/Article/details/gteylejfhc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gttvzbywdp.html

[Q32] 分组拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtqnyrxmjh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqpxoant.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenjidiqi.icu/Article/details/gtblgxtpkl.html

[Q33] 多列分组
来源：http://dali.yj20258.top/Article/details/gtlvkulcbj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hfpthk.cn/Article/details/gtjcfleesg.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gtnvafamio.html

SELECT * FROM (
来源：http://dali.yj202588.top/Article/details/gtactvjbjq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuxming.cn/Article/details/gtvoeiqekn.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtuxhhdugt.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtehxjiujn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gtbksnqbtt.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtfywvjwpf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hysaishi.cn/Article/details/gtlfnyagma.html

[Q37] 右连接
来源：http://dali.ppjwa.cn/Article/details/gtggrijhcr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.0kj1m.cn/Article/details/gtbnjeefob.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yangfankeji.com/Article/details/gtxrrarogn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.0kj1m.cn/Article/details/gtjqasjytv.html

[Q39] 自连接（查上下级）
来源：http://dali.nanxuanxn.top/Article/details/gteveqeuni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuxming.cn/Article/details/gticmwyhao.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtguqqbpoj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtfntaliiu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtoavknbhm.html

[Q41] 多表连接
来源：http://dali.tianlin.xyz/Article/details/gtezvyypfp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtjwvzfidm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.wangshuangyany.cn/Article/details/gtwpztkexa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.quarkkingdee.top/Article/details/gtcixgrinj.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gtcoqwcaln.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gteiavivby.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtqvmhzl.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtmmextham.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tian-w.cn/Article/details/gtplqodujd.html

[Q44] IN 子查询
来源：http://dali.tian-w.cn/Article/details/gtiluaxbae.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gthbsmyljg.html

[Q45] EXISTS 判断存在
来源：http://dali.zycfv.cn/Article/details/gtcpzmuruf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtsqjtnbxy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yuanzhike.top/Article/details/gtomjmpbki.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtdncmmiqp.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtemxryctk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gthkzbinim.html

[Q48] CTE 公用表表达式
来源：http://dali.gogol.net.cn/Article/details/gthtkqeagm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtryxclhjb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtznxsclrb.html

[Q49] 更新单行
来源：http://dali.jqgufenzy.top/Article/details/gtajaoaaru.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtzlybsozt.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtopnryebw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.smart0.xyz/Article/details/gtmshurxuf.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtszggobhp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gttaoqidol.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbbbfykp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtdzewvzmz.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtwuhsuelk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gtaohxkuwq.html

[Q54] 清空表
来源：http://dali.shangyingyoupin.top/Article/details/gtgajfhgns.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtxclshmbe.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtskldvsgs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtghyukodx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjipsdadg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtjlpfwsek.html

[Q57] 行号
来源：http://dali.ybcxt.top/Article/details/gtwqpecthh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gtfpbjusky.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtjbfamxeb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtexvltsvo.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gtkdalsbvo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtplxotnbq.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gtplukaowe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gthoketzek.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtmootbusy.html

[Q61] 移动平均
来源：http://dali.zycfv.cn/Article/details/gtsxyysows.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtchdalggd.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkumzylrn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gtkproygnj.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtexzwvcyc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtptffmkoj.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gtszahrciv.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtpzqztelx.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gthzgewhup.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtcnzobyqv.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gttsmlyexe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hnqzz.top/Article/details/gtgjcfhapb.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtgbgcwbqi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yangfankeji.com/Article/details/gtpbyzrywo.html

[Q68] 保存点
来源：http://dali.hnqzz.top/Article/details/gtjrrjvule.html

SAVEPOINT sp1;
来源：http://dali.guannengcc.top/Article/details/gtcvrgngsk.html


<!-- 参考信息 -->