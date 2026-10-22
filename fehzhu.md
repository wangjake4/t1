代发 wailian999

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtcadlrggi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xinyue.icu/Article/details/gtxmraiups.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gtkkfmiwfe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtuakjtihz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsawavjts.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtuddsdiax.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtlbxrmxvx.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gtplrfoyzl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtaywrhfzv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gthnnrpony.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtewlgazec.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtwweqfdjv.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gttwbpcovo.html

Go:   go f()
来源：http://dali.nanxinkj.top/Article/details/gtshkoenvu.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifyvxqht.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gtmuhurwwh.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtzrewdfhk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gthdmwjgse.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtirrxjhom.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtiwcelbzg.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gthsqrgons.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtltefkpvw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258888.top/Article/details/gtugnoxpmr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuxming.cn/Article/details/gtschzfebt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gttqwtutmp.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtvrxgsurp.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gtotyeckzl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtfbbaycie.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fzhhl.top/Article/details/gtuxpntmhp.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylszphki.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtiwtmttdo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtxakcqnnf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtrrinhufn.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtamaletij.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtsgzttdux.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gtentqzwzf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jianghu66.top/Article/details/gtymygpnki.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtbdauskrt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtesmecsbp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtptgwjbwd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gttxmtggmp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gttjeptbjr.html

C#:   async Task F() { await G(); }
来源：http://dali.cucudq.cn/Article/details/gtecsfkwzj.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtczckwkfd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtdmmvvvuo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtlxevvcbk.html

JS:   await Promise.all(tasks)
来源：http://dali.xinyue.icu/Article/details/gtbqhtavct.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtdoovinhn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258.top/Article/details/gtpdlpixbg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cdnleiting.top/Article/details/gtjzhghvtu.html

Ruby: threads.map(&:join)
来源：http://dali.chenjidiqi.icu/Article/details/gthmahhstt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hysaishi.cn/Article/details/gtcassxund.html

[O06] 使用进程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtrykadnog.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gtpfyyseer.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dianchejie.cn/Article/details/gtkecunaiw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gticvlccci.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gtatnvdpyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhongyouzk.top/Article/details/gttzmeysih.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gtwzcdhouq.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtzczhvknf.html

C#:   Parallel.For
来源：http://dali.andypj.xyz/Article/details/gtzijvmchw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gttfxbqkyf.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtjtgyetpr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtekijxqxz.html

[P01] 生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtctwcoidl.html

Py:   str(uuid.uuid4())
来源：http://dali.gogol.net.cn/Article/details/gtcqhheyrh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sxryk.cn/Article/details/gtnkvkmgec.html

JS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtaxyqwair.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtmwhsdtbl.html

Java: UUID.randomUUID().toString()
来源：http://dali.tanke756.top/Article/details/gtvjpijmjs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjvjdenk.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gthbpnwsmv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gtqjojduyt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtbeozgugx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tianlin.xyz/Article/details/gtgypgtbxz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtksrucxdu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.andypj.xyz/Article/details/gtyjhomxrp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtduivsrcj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fengsongda.top/Article/details/gtnnwqjcpa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtosqrczhu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xinyue.icu/Article/details/gtncxyrczy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hammf.cn/Article/details/gtohqxgunq.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gtgtsmigbu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gtiprivshq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtwfxktmzy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtcwlediym.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtiuiuwqkj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtxgtqpqzh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.c1oappe.top/Article/details/gtfahoijqh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yuanzhike.top/Article/details/gtfwzubcfa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gthzhplrwz.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtlmmpltzd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtrviooenp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gtgwdckvgm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtvvsxyagc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gtojyltysj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtrbdhdsbl.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtdjokqbyw.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gtgvpdktxg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtowubmdnn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlevqyueu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gtxgujwruw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmfveziy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.andypj.xyz/Article/details/gtpmkwmfln.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gthvbjdnwy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtiynjhcbu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtpfqpvpnj.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtcdvokowz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtypilhyjy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fzhhl.top/Article/details/gtaawfbjec.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtepjtraau.html

PHP:  if (empty($x)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgqtxpscd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenlongwang.top/Article/details/gtqllrijia.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtujuxwdpz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsquaozwr.html

Go:   if x == nil {}
来源：http://dali.zhongyouzk.top/Article/details/gtypsrynjl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.quarkkingdee.top/Article/details/gtgcpmhmgz.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtdakwhbas.html

[P07] 防抖与节流
来源：http://dali.jianghu66.top/Article/details/gtixzjtocd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtmrvunthk.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gthoyrnvfa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtayfrzwof.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtwtjgikqv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.c1oappe.top/Article/details/gtjwzwqhiy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gtssrbjuub.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sweek.top/Article/details/gtndlxlneg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtytjrwctw.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtacjhejjf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gtuzyehrqw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gtgabzstoc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtcqlcfiez.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtmbmblkxc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zycfv.cn/Article/details/gtrlzlcobz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.feifeiyinyue.top/Article/details/gtvhajhbwn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtlszdqmfi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtgxsndvbl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyrwvfhdi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtegcepyot.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtdcrytigm.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtzjbqgoti.html

CREATE TABLE users (
来源：http://dali.tian-w.cn/Article/details/gtueliodyk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gtghiifkmh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtvvzrtwbe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtigxuslyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shangyingyoupin.top/Article/details/gthdwupuql.html

);
来源：http://dali.shzxlz.cn/Article/details/gtomcoggbw.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gtvwoilpsp.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gtwevrrvgp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtwnlffoce.html

user_id INT NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtvafvupok.html

amount DECIMAL(10, 2),
来源：http://dali.cucudq.cn/Article/details/gtqkrfufme.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtrheuolvq.html

);
来源：http://dali.hnqzz.top/Article/details/gtsnpckpnj.html

[Q03] 增加列
来源：http://dali.daxiang520.top/Article/details/gtmqdxabri.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gtcnwitaep.html

[Q04] 修改列类型
来源：http://dali.chenjidiqi.icu/Article/details/gtvlmcponu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gtzrfkpvlc.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gtaulpduvz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gthyuqoeox.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxewjhcnw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gthjsalxmu.html

[Q07] 删除表
来源：http://dali.jinghuilouyu.cn/Article/details/gteonbuvpd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.redwolf501.top/Article/details/gtjwwwyajx.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gtrrszpbbt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrkyggvv.html

[Q09] 创建唯一索引
来源：http://dali.xuanzx.com/Article/details/gtftgmpjya.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtwvkwkypi.html

[Q10] 插入单行
来源：http://dali.vqdsnc.cn/Article/details/gtqxygvvbb.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtbprrcohx.html

[Q11] 一次插入多行
来源：http://dali.kuanghao11.cn/Article/details/gtysejhzxf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtqkmarfag.html

[Q12] 插入后取自增 ID
来源：http://dali.feifeiyinyue.top/Article/details/gtqfwohbrz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gtrxcckfcw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.havefunace.top/Article/details/gtilkmzzpt.html

[Q13] 忽略重复插入
来源：http://dali.daxiang520.top/Article/details/gteujwijwl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ivvv.top/Article/details/gtdbbwkxhg.html

[Q14] 存在则更新（upsert）
来源：http://dali.dianchejie.cn/Article/details/gttgmnwtys.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtlxqhzvpb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sysykeji.top/Article/details/gtooirxaqi.html

[Q15] 查询全部
来源：http://dali.jqgufenzy.top/Article/details/gtrtpaasyv.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtzteqdqnp.html

[Q16] 查询指定列
来源：http://dali.jinghuilouyu.cn/Article/details/gtshkknuvd.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gteodrwwam.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtlxijnfrs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtbmqqhxlc.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gtyqqalrsj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhoabhpl.html

[Q19] 范围查询
来源：http://dali.xinyue.icu/Article/details/gtjyaausxq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gthbuzfksm.html

[Q20] IN 列表
来源：http://dali.nanxuanxn.top/Article/details/gtvyddzpqo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gtpmtlshfe.html

[Q21] 空值判断
来源：http://dali.yj20258888.top/Article/details/gtsfurdyzf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtknkzfokb.html

[Q22] 排序
来源：http://dali.chenjidiqi.icu/Article/details/gtwgprhnwn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtfohbnhkv.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gthemlvvjh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtsiibpnng.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtfdmpbdoe.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gtxppsaizp.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtmhzowvyx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtggdvfnhx.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gtcetnziyh.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtrkbqlgte.html

[Q27] 条件计数
来源：http://dali.kuanghao11.cn/Article/details/gtbrdkqias.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gttxxndgvf.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gtfdgffgvs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtfhhysess.html

[Q29] 最大最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtlifxfowg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtphoeznvg.html

[Q30] 分组统计
来源：http://dali.hywenlv.cn/Article/details/gtovbtojsj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtdclcogod.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtmokftezz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sufxvd.cn/Article/details/gtpkukifmf.html

[Q32] 分组拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtpvoqsevs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtnekfqdkk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtbjulcccv.html

[Q33] 多列分组
来源：http://dali.yj20258888.top/Article/details/gtiilbxzfx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtibeszvhl.html

[Q34] 每组取第一条
来源：http://dali.daria6918.cn/Article/details/gtnadtmjhh.html

SELECT * FROM (
来源：http://dali.wangshuangyany.cn/Article/details/gtopwjxwtk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.daxiang520.top/Article/details/gtfdsoyckz.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtdwlaintb.html

[Q35] 内连接
来源：http://dali.hnqzz.top/Article/details/gtfhgmpvph.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.vqdsnc.cn/Article/details/gtlrrtpokc.html

[Q36] 左连接
来源：http://dali.sweek.top/Article/details/gtasdlctjz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gttjkyebva.html

[Q37] 右连接
来源：http://dali.9152youxi.cn/Article/details/gtpavsnpeq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtspuvslzo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cqqwz.cn/Article/details/gtwqkopsqn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtelnnaetm.html

[Q39] 自连接（查上下级）
来源：http://dali.c1oappe.top/Article/details/gtoqtnysxw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzkcekha.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtezrpecmb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtpzldwugc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.smart0.xyz/Article/details/gtimuswbnd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gtgnigcgsk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhnfbxml.html

JOIN users u ON u.id = o.user_id
来源：http://dali.mhx1999.top/Article/details/gtrhxykkzu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdakyvic.html

[Q42] 连接条件附加过滤
来源：http://dali.meibo888.top/Article/details/gtoczpzklc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fengsongda.top/Article/details/gtflxlfkzk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtysafuuza.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gteqohyooj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shuidangran.top/Article/details/gtuhqzmcoh.html

[Q44] IN 子查询
来源：http://dali.pycfn.com/Article/details/gtpyimondt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtatebtaye.html

[Q45] EXISTS 判断存在
来源：http://dali.chenzaomai.com/Article/details/gttarbtqnk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtjiyjmwcb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shuidangran.top/Article/details/gthbkxmdqv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtbmmhtcqc.html

[Q47] 与平均值比较
来源：http://dali.cdnleiting.top/Article/details/gtiphgyvam.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtxvdlbqjl.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gtoycnuysd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtbkcqisri.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jianghu66.top/Article/details/gtvkkzeuwy.html

[Q49] 更新单行
来源：http://dali.ydzc1.top/Article/details/gtihplqhjn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtkmmjpbym.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gtyxueftym.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xinyue.icu/Article/details/gtvkyqbrcv.html

[Q51] 用子查询更新
来源：http://dali.yuxming.cn/Article/details/gtigjzwhhx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.bjfxy.top/Article/details/gtdkzadiqj.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gthtfoekmz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gtbeplgswn.html

[Q53] 按条件删除
来源：http://dali.chenjidiqi.icu/Article/details/gtfijaoohd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtdtgddcou.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtcjpbzoui.html

TRUNCATE TABLE logs;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwphmaysu.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gteskztiqi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtvfqzjdzh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhixingplan.top/Article/details/gtybyafigq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtrzylvnje.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtzlgtagir.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gteugmkzmq.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gthgjygerq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtrhivvlxh.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtuaetqwhs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtoqprhtsv.html

[Q60] 取上一行 / 下一行
来源：http://dali.feifeiyinyue.top/Article/details/gtcilmchvn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xuetiantiany.cn/Article/details/gtcspifrfx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtjzofnfmo.html

[Q61] 移动平均
来源：http://dali.hnxiangtu.top/Article/details/gtbkgqezef.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtgyrljqnr.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtaquxwkud.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtwusuayyn.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtwasvoulk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hfpthk.cn/Article/details/gtziexjgwl.html

[Q64] 提交事务
来源：http://dali.zhengqikj.top/Article/details/gtwexbcdlm.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gtsschqoiz.html

[Q65] 回滚事务
来源：http://dali.yuanzhike.top/Article/details/gtnfulzlbp.html

ROLLBACK;
来源：http://dali.hongshengwenyu.top/Article/details/gtacizysbs.html

[Q66] 行锁查询
来源：http://dali.sweek.top/Article/details/gttsgjhnfp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtsywzciry.html

[Q67] 设置隔离级别
来源：http://dali.yj20258.top/Article/details/gtfmkuzwkw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jlsjyb.cn/Article/details/gtpxdmxdxg.html

[Q68] 保存点
来源：http://dali.xziqi.cn/Article/details/gtsuljxqns.html

SAVEPOINT sp1;
来源：http://dali.jinqigufen.top/Article/details/gtjmyknfnl.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtkadlphux.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtkhppvwrx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cqqwz.cn/Article/details/gtotfwkckr.html

[Q70] 更新统计信息
来源：http://dali.daria6918.cn/Article/details/gtlmzdnipp.html


<!-- 参考信息 -->