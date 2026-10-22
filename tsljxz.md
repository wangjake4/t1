代发 wailian999

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjyibvfel.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtqewksgwx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtarppolgm.html

[O01] 启动一个线程
来源：http://dali.c1oappe.top/Article/details/gtunwignjl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtwopfickm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtconqqauw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtfuvxxwnf.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtsejhuujm.html

Java: new Thread(() -> f()).start()
来源：http://dali.hammf.cn/Article/details/gtvupbtmcs.html

Go:   go f()
来源：http://dali.xinyue.icu/Article/details/gtdzwnynvn.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtfyccyzrf.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtwdqrhwjl.html

[O02] 使用线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqbhfbuj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gtgsslwlww.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaseutni.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtogexhghr.html

TS:   // worker_threads 线程池
来源：http://dali.xuanzx.com/Article/details/gtxxeauvme.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtzqljxqbm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtestdxkpi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gtglgharnc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yonumen.top/Article/details/gtgjblpych.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gtzbrwivvr.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtpkkgjbwf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzduzohb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtajflrrcg.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gtwcyyjgqg.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtgqjzsaoo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gttcskgbib.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gtkgzsdhpw.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtwjnwntva.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtdhqzzhtr.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gthwlaejzu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtxvzbxhpg.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtkfkuguga.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtgxhruwiv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigfzy.top/Article/details/gtzoiyotvl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtkokdfbbj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtwbyktimh.html

C#:   async Task F() { await G(); }
来源：http://dali.birdmap.top/Article/details/gtkyctsxak.html

[O05] 并发执行并等待全部完成
来源：http://dali.tianlin.xyz/Article/details/gtqsmydghi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtxyqflylm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtmovwkwbn.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtipmthepc.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtzaymrzig.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjysseaba.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtesrnwund.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtdskvcztm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtndreahrf.html

[O06] 使用进程池
来源：http://dali.xinyue.icu/Article/details/gtcnrflvtl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gtdcbeszly.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtczhmvusi.html

JS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtavehuggi.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtqjwvdffx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtumhoallr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ydzc1.top/Article/details/gtdkmjlzev.html

Ruby: // fork 块
来源：http://dali.ppjwa.cn/Article/details/gttvdttmrg.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gtukadkapu.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtllprhsjt.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtdfylxxsc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdjrzfjmw.html

[P01] 生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlogoefnj.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gtqqkqsabk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtphnznxmz.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtlfaheydk.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtnagcskya.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtvvwhsalv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtbxykwxke.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtkjpkelwc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtpmnzbgyo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.9152youxi.cn/Article/details/gtdfspiywp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhoulong.xyz/Article/details/gtifyrrdpn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtyqvemcpy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtcmesmdrx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtaadovqke.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtfepllzyj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gtxxuhcezn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.pycfn.com/Article/details/gtwcpuneat.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.kuanghao11.cn/Article/details/gtcomlefwd.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtxgtnxhrq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sufxvd.cn/Article/details/gttlgtnrer.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gteqvhkthz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtfscclqda.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtvunrszwc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtzeutwuuo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pycfn.com/Article/details/gtwhwaujfd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtudaqkzgv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gtbixvnmcx.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gtrdhouffu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtaqdhllwn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gtckywkrpp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtpxpumcyb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtszmxorxy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvcjsbze.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtdhzchlsx.html

Ruby: x.length;  x.size
来源：http://dali.pycfn.com/Article/details/gtgbngbmpu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gtjilmebog.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gttqbceewa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtcysbmlbu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtckfmuzzf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtegdifexw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtlgqhdllh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhongyouzk.top/Article/details/gtpdwuwfqh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtjoahoksv.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtzqbrwkiw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gthupsimvl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtzjgjgljc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtjiglhbbh.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtlasimivw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtwovayhxb.html

TS:   if (x == null) {}
来源：http://dali.gzhubu.top/Article/details/gtjeebwagk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtqbnytstq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtcjpciytr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtlvbsuudl.html

C#:   if (x is null) {}
来源：http://dali.zhixingplan.top/Article/details/gtgyphuxjd.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtykymqnuk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtfwxpnmjy.html

PHP:  // 手写时间戳比较
来源：http://dali.hammf.cn/Article/details/gtqeywkkfb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtnvfdjezq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtkftdyzsk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfbrzpoew.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gtxmbdvkbn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtmqxxacpn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnqzz.top/Article/details/gtookcllcj.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtrwylpuqz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtyhqrtrbv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ybcxt.top/Article/details/gtifwzpgpr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtxmjcublu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtizaviufw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtsjuiuvdj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yangfankeji.com/Article/details/gtmpcderdn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gtzosjgjtv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gteonwbmvg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtkbjygvkj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtkkyjrxjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxumocxtl.html

[Q01] 创建表
来源：http://dali.andypj.xyz/Article/details/gtxrfnipij.html

CREATE TABLE users (
来源：http://dali.zhengqikj.top/Article/details/gtfpyuoywq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtrnjpjueq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtdvbeztqe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtnxxsgdjj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtbzgbejzr.html

);
来源：http://dali.gzhubu.top/Article/details/gtrnefocrk.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtfrzrwnuq.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gtfomyicgl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtwejkaskg.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtsudzwtmh.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhtkxwow.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtdlmrjyvj.html

);
来源：http://dali.andypj.xyz/Article/details/gthcrtqeqh.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gtfdkyfxpe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtwlscstri.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gtyngsuert.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.316326.xyz/Article/details/gtlhawwekb.html

[Q05] 重命名列
来源：http://dali.jqgfzy.top/Article/details/gthdpqghwi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hongshengwenyu.top/Article/details/gtdzahaxmc.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtiiuyxyao.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtmguxlaly.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtpxeffthn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gtpzfbpakm.html

[Q08] 创建普通索引
来源：http://dali.zhiwuduotai.top/Article/details/gtxfdrkleo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtgpkqjzsl.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtjgpryzsl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtyjwbxhml.html

[Q10] 插入单行
来源：http://dali.ivvv.top/Article/details/gtnjnqlzjl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.havefunace.top/Article/details/gtmufjfpvu.html

[Q11] 一次插入多行
来源：http://dali.haohaochexian.top/Article/details/gtsgblsbze.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258888.top/Article/details/gtilpfdhba.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtowirchdq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hammf.cn/Article/details/gtomtborau.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuxming.cn/Article/details/gtgxtnistz.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtavprrwqx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtbdkpxxox.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gtepfqmost.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxeiplvr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gteveinoho.html

[Q15] 查询全部
来源：http://dali.shanyushiyangtech.top/Article/details/gtymbefmwv.html

SELECT * FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtpxtuzaqu.html

[Q16] 查询指定列
来源：http://dali.yuanzhike.top/Article/details/gtkxstdscc.html

SELECT id, name FROM users;
来源：http://dali.zycfv.cn/Article/details/gtjvabzsyc.html

[Q17] 条件查询
来源：http://dali.cdnleiting.top/Article/details/gthffmxohs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.andypj.xyz/Article/details/gtqogopqyy.html

[Q18] 模糊匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtnepssuvt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dianchejie.cn/Article/details/gtdzfyderw.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtdigokwsi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtzhyoheda.html

[Q20] IN 列表
来源：http://dali.yuanzhike.top/Article/details/gtlphhpjio.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gtlbhehfzi.html

[Q21] 空值判断
来源：http://dali.jqgfzy.top/Article/details/gtoftylpru.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtfmcdkxzd.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtlgrrurey.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fzhhl.top/Article/details/gtthedxkud.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtubxagnmc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shuidangran.top/Article/details/gtiigiczmp.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gthtldeazq.html

SELECT DISTINCT city FROM users;
来源：http://dali.andypj.xyz/Article/details/gtiygqzjsn.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtbeqoztap.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtasltvadb.html

[Q26] 计数
来源：http://dali.cashguo.top/Article/details/gtdejaflzw.html

SELECT COUNT(*) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmbacgbe.html

[Q27] 条件计数
来源：http://dali.sysykeji.top/Article/details/gtsjissbid.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtepuujvtv.html

[Q28] 求和与平均
来源：http://dali.zhengqikj.top/Article/details/gtcooqffow.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtaumffbqq.html

[Q29] 最大最小值
来源：http://dali.pengpengdd.cyou/Article/details/gtfrdzvths.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtjbanblgs.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gteotifumj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtvppuptmj.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtxyrcrjtb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yvedp.cn/Article/details/gtdxpbzqhw.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gthxugbtik.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtvhhdgoyp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tianlin.xyz/Article/details/gtcwkdlvsm.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtmsakirye.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jqgufenzy.top/Article/details/gtftaftjaz.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gthlqzjueo.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gtdtxmvzao.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.0kj1m.cn/Article/details/gtgzugmpaq.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfzudhfur.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtsycdzgyb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtnbncfejq.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtwikqfavr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gtyoejzoxd.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gtudqpeuup.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtzpmrgoef.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtdilmfyqu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtmvrhrqvi.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofqjezuy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ydzc1.top/Article/details/gtsdtovyst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ydzc1.top/Article/details/gtvvvbmsnr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.dianchejie.cn/Article/details/gtbkztkfkp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtktdrwkfy.html

[Q41] 多表连接
来源：http://dali.daria6918.cn/Article/details/gtlbplauen.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.vqdsnc.cn/Article/details/gtwtgkdcqh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtiftwodcf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtuxrttgca.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngmiyfqa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.daxiang520.top/Article/details/gtfvjcdnwa.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhghjmlu.html

[Q43] 标量子查询
来源：http://dali.hongshengwenyu.top/Article/details/gtupqjrdsy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.bjfxy.top/Article/details/gttjcqontx.html

[Q44] IN 子查询
来源：http://dali.gogol.net.cn/Article/details/gttqwjptqp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gtqcfujaps.html

[Q45] EXISTS 判断存在
来源：http://dali.aibaodan.cn/Article/details/gtkikplqzy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwwvsepx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtszscdwbb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtlutyiyox.html

[Q47] 与平均值比较
来源：http://dali.hnxiangtu.top/Article/details/gtgsblvqus.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtugqrisxa.html

[Q48] CTE 公用表表达式
来源：http://dali.ivvv.top/Article/details/gtlfltkkdq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtddsbotte.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xziqi.cn/Article/details/gtygjnwutj.html

[Q49] 更新单行
来源：http://dali.feifeiyinyue.top/Article/details/gtlpnqsjci.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ybcxt.top/Article/details/gtpbapnwww.html

[Q50] 批量更新
来源：http://dali.hnqzz.top/Article/details/gtbynbhssr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.haohaochexian.top/Article/details/gtlrnufdsc.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtmtbgkwog.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtmobrbbai.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtkaifaayn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtfsibizvt.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gtktduygnf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yj20258.top/Article/details/gtunchjzxg.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtqlijlwzy.html

TRUNCATE TABLE logs;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcsijpvh.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gtnljasqjd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yongpay.top/Article/details/gtgnxcqybr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvivwnqc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gthcbjehiq.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gtdmlholef.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtqmfwehzf.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtatifqhju.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulunjhoy.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtomskplki.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtqwprfjcz.html

[Q60] 取上一行 / 下一行
来源：http://dali.cdnleiting.top/Article/details/gtpyounyfv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gthfuvknvr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtoaolbrgb.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtfcevvpof.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtddepzdlr.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbahbynf.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtopjraiaw.html

[Q63] 开启事务
来源：http://dali.sweek.top/Article/details/gtfvzddyfl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.mhx1999.top/Article/details/gtlnejxykx.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtdkqwwlju.html

COMMIT;
来源：http://dali.nanxinkj.top/Article/details/gtiakosmgm.html

[Q65] 回滚事务
来源：http://dali.vqdsnc.cn/Article/details/gtfhqbcsti.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtzftmdokx.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtdqbksiky.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtihubbwjz.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtccpdsqaz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtpdorzpcr.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gtuhconptt.html

SAVEPOINT sp1;
来源：http://dali.daxiang520.top/Article/details/gtmdqqauha.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gttmfmhrsf.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtxvfddvry.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtzgeeivct.html

[Q70] 更新统计信息
来源：http://dali.gzhubu.top/Article/details/gtifxhrbli.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtzjydqzvk.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtvvkkvjfs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtaxcsgrdk.html

[Q72] 查看索引
来源：http://dali.gaohongyu789.top/Article/details/gtajktedao.html


<!-- 参考信息 -->