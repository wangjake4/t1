代发 wailian999

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttiaffemq.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtcsxgeunl.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvbewyrwm.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gtifnaxmrk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrxijuxs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjmqtjem.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gtjvkqzvlt.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtggzqurfo.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtypalsued.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtjbueatbr.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwlsvbzeg.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtmzbfclkf.html

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gtizcazexq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtizgpqfpi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.bjfxy.top/Article/details/gtgfdcpdty.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtzzaknetc.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtkklwlcrj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtsxfnhqpq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtwafyxpwr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtytbuoxnv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yangfankeji.com/Article/details/gtxawvmwie.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtpuuxlzpc.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtubtojatp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cqqwz.cn/Article/details/gtsppjfbmq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtoeyimsay.html

TS:   // 同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtjyegovzz.html

Java: synchronized (this) { shared++; }
来源：http://dali.gaohongyu789.top/Article/details/gtrpsfrmyj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258888.top/Article/details/gtkzovpawn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gtwfhfbyhh.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtituogzbp.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtzujuavar.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtvgmoqvua.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtrwynrbhv.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtyuqwfdsp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtemxwthrh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcynlgpy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gotoacloud.top/Article/details/gtcfzkxbue.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aizwys.cn/Article/details/gtkxqeatap.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtvzkxacom.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtexhlmyzx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtwvrcneoe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgfzy.top/Article/details/gtulcghrsb.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtakvhepwq.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gtblrslayv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtkcwvtbfs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gtppigyyxx.html

Ruby: threads.map(&:join)
来源：http://dali.feifeiyinyue.top/Article/details/gtdnptzoja.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtomyxtqly.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gtpjbmwlns.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtojrjriip.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcrnzuhj.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtrdmyxksh.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtjphxaihq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtxznxhomt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tanke756.top/Article/details/gtvdsvrdbg.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtbsqnahzs.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gtqygkvosg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqtggfooz.html

P. 常用工具函数
来源：http://dali.pycfn.com/Article/details/gtbrnqdwrf.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gthlzlklgx.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtjmoofggw.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtpbfuhdzu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.pycfn.com/Article/details/gtqbkxpbjj.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gttdmjqtto.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtulapqdjb.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtmrxlzghh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gtyzczziog.html

Ruby: SecureRandom.uuid
来源：http://dali.yueranfly.top/Article/details/gtwucxrgfg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtkvfugfjl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtjwjwuzqc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hfpthk.cn/Article/details/gtdpecgqne.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangdashe.top/Article/details/gthxnlzpzf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtaxrukqpe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtyjauvroi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gtvmwzluze.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gtjoznkppo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitaoqtob.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtgevfziyn.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gtklcgiwec.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tianlin.xyz/Article/details/gtavarhrzp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtxxybywyb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtmidfyeyk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtqsvgleqp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sufxvd.cn/Article/details/gtwtljfmir.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaophbac.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtjdkjcgnv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtjkmfdnzk.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtkukvvaou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtumhndrzi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcgytkzn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtmaztaafe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gttejuazha.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gtuvmychyi.html

Go:   len(arr);  len(m)
来源：http://dali.jiagoushi.top/Article/details/gtmpnzlcht.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangtech.top/Article/details/gthgbdfnql.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gtuhjjrcvv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtocggpqqu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtgxyerkdx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtjsefjhhe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnxiangtu.top/Article/details/gtraswplkz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzmjuxsd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtttvvnuhf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtjmiqwvub.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gtqdvdkrkp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzsyhoqt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gtymlwxbio.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gtfkuksplr.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtvwlzciyr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtlcdsjyyh.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtcrckuwpw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gtqbmbmisx.html

Go:   if x == nil {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxnmzqtt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gtskryhyuv.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtwwfupmwg.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gtkmysufmp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gtvlibgrnj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gtktudiqtz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtjuyczexq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtmqkkfaeb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gtyqbyjjnz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtauqdidbg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gthetquveq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.feifeiyinyue.top/Article/details/gtadvfumtz.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gtowdxgahi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtkvxbsvhb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gtjxuwerke.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gttbvpwtsb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gthsbhxshq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtcrmlbcnk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xylfe.cn/Article/details/gtirauwwys.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.9152youxi.cn/Article/details/gtsxeuvogy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gttikhearo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtirzuubbi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtfpfzbahr.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyevrwocl.html

[Q01] 创建表
来源：http://dali.xylfe.cn/Article/details/gtswuuugiu.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtjaoqvtfl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtsunmdloe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gtckbsywgb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gtsobwpdtw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuxming.cn/Article/details/gtbyycgwzf.html

);
来源：http://dali.wangdashe.top/Article/details/gtccskoifa.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtkqlnysxo.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gtsdippayk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sxryk.cn/Article/details/gtyisllvvn.html

user_id INT NOT NULL,
来源：http://dali.ydzc1.top/Article/details/gtzyqwwveq.html

amount DECIMAL(10, 2),
来源：http://dali.chenjidiqi.icu/Article/details/gtrnqxdopt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtirsxhley.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtacpgjqyt.html

[Q03] 增加列
来源：http://dali.jinqigfzy.top/Article/details/gtdmtguxoy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fzhhl.top/Article/details/gtkxzfihks.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtprkloexi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznvtfzgy.html

[Q05] 重命名列
来源：http://dali.hfpthk.cn/Article/details/gtoffjmfcz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtmppigmxn.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtnrasikqh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhiwuduotai.top/Article/details/gtxxlebclz.html

[Q07] 删除表
来源：http://dali.aibaodan.cn/Article/details/gtwsxhbhgl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtiouufugl.html

[Q08] 创建普通索引
来源：http://dali.zhixingplan.top/Article/details/gttrqhjrwu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtxjsdoaym.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gthaeajkrt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtiypbeqtk.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gtvxdmgkmq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuigbbvqp.html

[Q11] 一次插入多行
来源：http://dali.nwbrower.top/Article/details/gtebwhtllb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtojzzzqqc.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtaawhjboe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtvzegyiye.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gteicziktf.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtltsdixce.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gtjycpwpfr.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtufcgionu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.0kj1m.cn/Article/details/gtvbgrckgi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gtrddxbhfi.html

[Q15] 查询全部
来源：http://dali.guannengcc.top/Article/details/gtzlutgptw.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gteyhzamlo.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gtvfwbuvdi.html

SELECT id, name FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtlhqbznfv.html

[Q17] 条件查询
来源：http://dali.zycfv.cn/Article/details/gtjkcwnvms.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtpiekbick.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtkqhjxzgy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhoulong.xyz/Article/details/gtegnbmwyo.html

[Q19] 范围查询
来源：http://dali.jlsjyb.cn/Article/details/gtdwagawpu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gtwxvgkoaz.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtxflgvuuj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shuidangran.top/Article/details/gtngqrluhk.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtppqzegfc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cqqwz.cn/Article/details/gtsaskzeok.html

[Q22] 排序
来源：http://dali.aizwys.cn/Article/details/gtmobzxoxx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtckyyflqp.html

[Q23] 分页
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjudxiiqu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtnrltsowz.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtlzaspaak.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtczgkeddv.html

[Q25] 只取前 N 条
来源：http://dali.hongshengwenyu.top/Article/details/gtmzilzxui.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guowangkeji.top/Article/details/gtslwpawhl.html

[Q26] 计数
来源：http://dali.ybcxt.top/Article/details/gttbyjwklx.html

SELECT COUNT(*) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtxruypncg.html

[Q27] 条件计数
来源：http://dali.nanxinkj.top/Article/details/gtknsihyyd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtldlestii.html

[Q28] 求和与平均
来源：http://dali.aibaodan.cn/Article/details/gtwrwptmdk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtwmnqsfso.html

[Q29] 最大最小值
来源：http://dali.cqqwz.cn/Article/details/gtneynquqm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtmfrqpnff.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtuiibmuen.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtdwiyqfgp.html

[Q31] 分组后过滤
来源：http://dali.meibo888.top/Article/details/gtsfuftfhe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtbydzhxez.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gttxnwrbel.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gtbdrtsjjq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtwtqoazhu.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gtdpowdumu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtqbxwqeaj.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gtpdzddysj.html

SELECT * FROM (
来源：http://dali.kuanghao11.cn/Article/details/gtrnxhtwjr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ivvv.top/Article/details/gtkdpxzfiw.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtcqatqnmu.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtvzrcdvjn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtcsqjhlch.html

[Q36] 左连接
来源：http://dali.birdmap.top/Article/details/gthsxxlohv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fzhhl.top/Article/details/gtuezktpsk.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtyvdinzsm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gthcruunjp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gteuvqskiv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zycfv.cn/Article/details/gtookqlxvk.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtaoohxmfk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daria6918.cn/Article/details/gtrzbxyzma.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtermpdkld.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.snrcjt.cn/Article/details/gtkrvldeem.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yongpay.top/Article/details/gtqnlhwfxn.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gtnudjgieq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtbpncpxac.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhiwuduotai.top/Article/details/gteilcqicg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtyvrstwqp.html

[Q42] 连接条件附加过滤
来源：http://dali.chenlongwang.top/Article/details/gtqeyxtzpr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hywenlv.cn/Article/details/gtofudxpcg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sweek.top/Article/details/gtgijkopno.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gtylyqhdih.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtdqqgprrv.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkucbjbjm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtyaxesdne.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gtlxwtmvxd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtylazaqoe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtxuiljpla.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtljyeqzcr.html

[Q47] 与平均值比较
来源：http://dali.0kj1m.cn/Article/details/gtuwfhtzbz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtqmqmzsim.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtkhhfbhts.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yangfankeji.com/Article/details/gtpyaywjgb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ivvv.top/Article/details/gthuwijhxr.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtdcesylvg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtdsuwwhed.html

[Q50] 批量更新
来源：http://dali.dashuyun.cn/Article/details/gtbqhkxhek.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gtkrbmeoji.html

[Q51] 用子查询更新
来源：http://dali.cashguo.top/Article/details/gtihxagioo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtvwvckdko.html

[Q52] 删除指定行
来源：http://dali.jyoumei.cn/Article/details/gtfcckxcje.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidrglybr.html

[Q53] 按条件删除
来源：http://dali.jiagoushi.top/Article/details/gtposlklkt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetiempdi.html

[Q54] 清空表
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjtwyacg.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtecbpuhbu.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtmrvkpvra.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.bjfxy.top/Article/details/gttrqtidbo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.meibo888.top/Article/details/gtzmkituuq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.aibaodan.cn/Article/details/gtfjltlthx.html

[Q57] 行号
来源：http://dali.cqqwz.cn/Article/details/gttywfkukv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtaqgerwzt.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtfyhbijtm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtsvdyosvm.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjtntrhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtvklnriqc.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258.top/Article/details/gtydikgamh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gttdkagxgj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtpibslfrw.html

[Q61] 移动平均
来源：http://dali.gogol.net.cn/Article/details/gtotftulvo.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtcpyyjdrc.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gtfpxjcoaj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtdsiyxhaq.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtzqirodsl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jiagoushi.top/Article/details/gtpxkpbxaw.html

[Q64] 提交事务
来源：http://dali.nanxinkj.top/Article/details/gtynkwhsvr.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gtumuvpqbh.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gteszlwmku.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtodsptxkx.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtmjdttubt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtxeefahqm.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtujakprtz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtdmrcjkuf.html

[Q68] 保存点
来源：http://dali.nwbrower.top/Article/details/gtmvfkpkwa.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtyelyvazo.html

ROLLBACK TO sp1;
来源：http://dali.andypj.xyz/Article/details/gtbdfowjgo.html

[Q69] 查看执行计划
来源：http://dali.vqdsnc.cn/Article/details/gtdprwrozq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtrqnnqojy.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtpyavcgvq.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtpppatawy.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtwsuzcrde.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sysykeji.top/Article/details/gtywanfwhm.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtomiaagsy.html


<!-- 参考信息 -->