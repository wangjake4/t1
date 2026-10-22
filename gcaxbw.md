代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtfooqanqd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtfqmhgqri.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daria6918.cn/Article/details/gtzcqdfsni.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gtvslvnfpy.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtaswzoadq.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gttjsqtvdl.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtwawhwckc.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtkdxsxydu.html

[O02] 使用线程池
来源：http://dali.cucudq.cn/Article/details/gtfsqopnle.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cqqwz.cn/Article/details/gtwfzrzqyz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtmoxdcjhr.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gttiayxbah.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtmrtfyvpq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtdtjrmwik.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gtovgaskfv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtsoqfgmmb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtizsrmhhh.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtkakimjfk.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtxmfoesht.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtvwcmhmkl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtuhmlnjde.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gtlxailhym.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gthqxonnia.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtsofkoyrs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhixingplan.top/Article/details/gtfkrqrsim.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtrjrllvmd.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gtynaaflhe.html

Py:   async def f():⏎    await g()
来源：http://dali.cqqwz.cn/Article/details/gttmxtvwwd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cashguo.top/Article/details/gtemocgmoc.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtuwrogfml.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtwvfkpgpv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gtdpetaiet.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gteqlifxai.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gttjutuxri.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtvjobzryy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gtwsjupozj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtwwhlqqzg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtamdbgikc.html

JS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gteewxtiyu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtggegovbt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtqatnxlyg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiicmuog.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtbbnvamea.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtjmjihwnn.html

[O06] 使用进程池
来源：http://dali.zhengqikj.top/Article/details/gtwialdnmx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtvemuazjk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.kuanghao11.cn/Article/details/gtzmrilmsn.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtrfdhnbfm.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtmftxpcyc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ivvv.top/Article/details/gtpidjjsuy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnqzz.top/Article/details/gtpzlvuewq.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtomdrkyrk.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtvrfrlmsa.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtaxxtgrld.html

P. 常用工具函数
来源：http://dali.yonumen.top/Article/details/gtnylqcmmo.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbdayhpxr.html

[P01] 生成 UUID
来源：http://dali.jinqigfzy.top/Article/details/gtfgxpwvta.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258888.top/Article/details/gtmgzbqxce.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtuwrwfhwk.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gteykadrpw.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtsfemvped.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtsphgoakt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcojwtai.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gtzehhxpwn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.mhx1999.top/Article/details/gtnlfuxgzb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtfojdphqb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gtygtluydr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fzhhl.top/Article/details/gtxwzgsimd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszlewbov.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstcsespu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ppjwa.cn/Article/details/gtegqsqlwv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtbjvkpfdg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtihrsofky.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtvdtdkeqk.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtplylzxof.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtjfvmjhyc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gteolijcob.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtqrwzhqky.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtzlhjzogl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtaomdzbnl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtcjlcsjlk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtqzcdozvx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtnqtwonye.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtghvbxibt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtjungmdyq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtlcgtfjcq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gthezeudiu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gthqwwhdyd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gtvduguatz.html

Go:   len(arr);  len(m)
来源：http://dali.vqdsnc.cn/Article/details/gtfdzdhzao.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtfiuqrtjy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtohfsekum.html

[P05] 判断两个对象内容是否相等
来源：http://dali.haohaochexian.top/Article/details/gtlnyogpqe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gtvwivelvs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.birdmap.top/Article/details/gtgkmlnnxx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gtfdxjdesa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dashuyun.cn/Article/details/gtusxkqodo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtlkypbzkv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtzxmjidwo.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtfizhfqyt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtcokparsx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenjidiqi.icu/Article/details/gthodiwcga.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gttkuonfcb.html

PHP:  if (empty($x)) {}
来源：http://dali.hammf.cn/Article/details/gtpyntqmxl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangshuangyany.cn/Article/details/gtcxaftpbx.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtbtqnadwy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtcizqrzck.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gthnxfgwph.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtmueluapa.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzqkzmkk.html

[P07] 防抖与节流
来源：http://dali.nanxinkj.top/Article/details/gtluhyyzwe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtqybplfkm.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gthwxvwxfd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtggwdbhpp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtlamgifwf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtazvooaxg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtufxnxkyl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yanxiufei.cn/Article/details/gtethmzbhu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtfgdsmycr.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtbumzawwr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtaypyirih.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgfzy.top/Article/details/gtrfyqccha.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gtfncrdkiz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtvwpjtxdg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtgxjoskzl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zdqjudy.top/Article/details/gtrheiamsk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yongpay.top/Article/details/gtgoihegil.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gtcpgzjias.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqedhsgoz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtrzqejojs.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqnbpewgy.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtfbippzjj.html

CREATE TABLE users (
来源：http://dali.hammf.cn/Article/details/gtabctnavo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xziqi.cn/Article/details/gtevylpboz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtrdmmbfnn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hammf.cn/Article/details/gtwwfabkjn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guowangkeji.top/Article/details/gtwdlfinas.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcirmdkr.html

[Q02] 创建带外键的表
来源：http://dali.ybcxt.top/Article/details/gtqajxrofz.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtdldoprxh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aizwys.cn/Article/details/gthigpguis.html

user_id INT NOT NULL,
来源：http://dali.sxryk.cn/Article/details/gtjygrohfq.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gtornonyim.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhiwuduotai.top/Article/details/gttcdapwxy.html

);
来源：http://dali.yj20258.top/Article/details/gtwjknanpx.html

[Q03] 增加列
来源：http://dali.shuidangran.top/Article/details/gtmvdldxny.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtjkvzbvvf.html

[Q04] 修改列类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiiyhoza.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hysaishi.cn/Article/details/gtsodauayf.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtfpxzfctq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ppjwa.cn/Article/details/gtwaaukzuv.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gttqmkqkng.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtvihxkduu.html

[Q07] 删除表
来源：http://dali.jiagoushi.top/Article/details/gtampmjymo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gthrdqkymt.html

[Q08] 创建普通索引
来源：http://dali.gaohongyu789.top/Article/details/gtrswatcsz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtpdrlobcz.html

[Q09] 创建唯一索引
来源：http://dali.iojbl.cn/Article/details/gtgmzalnoi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ybcxt.top/Article/details/gtxrvzfnis.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtwcftzico.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yanxiufei.cn/Article/details/gtempgzbrj.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtxxxgzekw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtauuxurbj.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtqeseqrqy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdmgifxm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gtnvuilcxw.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gtoizznakq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtrnewzxox.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gtkykndunv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtntveibix.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.wangdashe.top/Article/details/gtquxeaxxz.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gtslqbqsls.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqzbmfjof.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtqakfrvva.html

SELECT id, name FROM users;
来源：http://dali.bjfxy.top/Article/details/gtwgffezas.html

[Q17] 条件查询
来源：http://dali.daxiang520.top/Article/details/gtmugydnqt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gotoacloud.top/Article/details/gtfiwiqxzb.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtxdwxitrb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtlsidnpjh.html

[Q19] 范围查询
来源：http://dali.yangfankeji.com/Article/details/gthgdwtgbc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jqgfzy.top/Article/details/gtvadlotwo.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtlgvdygbx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gturbpdiub.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtusxyxagf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtsavufhfl.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtwdilsaen.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtrcvusnuu.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtsyxhkoxz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gtayivoddk.html

[Q24] 去重
来源：http://dali.yj20258888.top/Article/details/gtcjuayvmj.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258888.top/Article/details/gtyjzcekhp.html

[Q25] 只取前 N 条
来源：http://dali.smart0.xyz/Article/details/gtyqrcnijq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ydzc1.top/Article/details/gtdaxkonqv.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gtdxpdiqyb.html

SELECT COUNT(*) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtybizgwfv.html

[Q27] 条件计数
来源：http://dali.xuanzx.com/Article/details/gtvtxaoizi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gthhlxmkoi.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtkptniqkz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtnmvobqkz.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtvffkmtsr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtdkziiyqg.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtatmwcvfu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gthlhchogt.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gtxebjyudo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtckgfjncu.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtltouduec.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtjwlbhpeo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwtboycx.html

[Q33] 多列分组
来源：http://dali.jinqigfzy.top/Article/details/gtxxnoevih.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xinyue.icu/Article/details/gtxynwacbi.html

[Q34] 每组取第一条
来源：http://dali.gogol.net.cn/Article/details/gtceattxag.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtlrjmvebk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtgamhlmvv.html

) t WHERE rn = 1;
来源：http://dali.xylfe.cn/Article/details/gtwgqsrumi.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtemjmpxar.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtolupdeqx.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gtouunfegm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtqqpjsira.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtrrztxngq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuanzhike.top/Article/details/gtuqmqnery.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yonumen.top/Article/details/gtdnpxpezw.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.9152youxi.cn/Article/details/gtykcdixpv.html

[Q39] 自连接（查上下级）
来源：http://dali.shzxlz.cn/Article/details/gtytsgcmms.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtbkraepdy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuanzx.com/Article/details/gtujaferpz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinqigufen.top/Article/details/gtgwrpwhtv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtwbhdcssg.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtonspbdpc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtgbxjsexb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jiagoushi.top/Article/details/gtdsanlsuz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gthsjtzswp.html

[Q42] 连接条件附加过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtdbsgbnnc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gttwciinze.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.guannengcc.top/Article/details/gtdzwqongu.html

[Q43] 标量子查询
来源：http://dali.xinyue.icu/Article/details/gtmxkzjtxp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gttkqvrqni.html

[Q44] IN 子查询
来源：http://dali.haohaochexian.top/Article/details/gtzefoyoab.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtczjnscgz.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtuywhjiod.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtkyqyzspj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenjidiqi.icu/Article/details/gtbnkfelwg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.vqdsnc.cn/Article/details/gtitpknvwr.html

[Q47] 与平均值比较
来源：http://dali.hongshengwenyu.top/Article/details/gtkwkdvkiz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yangfankeji.com/Article/details/gtdzyzzwqc.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtqqpcvlyp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.0kj1m.cn/Article/details/gtmznidsow.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtjprbbvla.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtlwfrvyys.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gtocwnpubh.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtpjsqnfzx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aibaodan.cn/Article/details/gtmouujrjz.html

[Q51] 用子查询更新
来源：http://dali.yangfankeji.com/Article/details/gtvazegnkr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenlongwang.top/Article/details/gtfqenpiuv.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gtlklrfxvc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtjbvkerhi.html

[Q53] 按条件删除
来源：http://dali.vqdsnc.cn/Article/details/gtiywcakmz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtosxkcrjl.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtlqhvumus.html

TRUNCATE TABLE logs;
来源：http://dali.jianghu66.top/Article/details/gtjjcqdfgd.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtetmhuxby.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtrsodtezf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtzresgkbm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuetiantiany.cn/Article/details/gtxzjpnyli.html

[Q57] 行号
来源：http://dali.xylfe.cn/Article/details/gtqylqfmte.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtpudbulfv.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtnhxxvthx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohwiwrnr.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtwweqrhth.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtmzwwwlbf.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gtmwvnvvtf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyskdbori.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaioxcuub.html

[Q61] 移动平均
来源：http://dali.yuanzhike.top/Article/details/gtcpoejaey.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtuxoupevh.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gthryppyfb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtwdympoao.html

[Q63] 开启事务
来源：http://dali.aibaodan.cn/Article/details/gtdtomqvjw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gttbyctfwa.html

[Q64] 提交事务
来源：http://dali.zdqjudy.top/Article/details/gtziiwcyor.html

COMMIT;
来源：http://dali.shangyingyoupin.top/Article/details/gtyaesyyhf.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gtpmvtrere.html

ROLLBACK;
来源：http://dali.aibaodan.cn/Article/details/gtqebyvlco.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtmojfphym.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtwjvpqyac.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtwvhgvncg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtnzwdrngv.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtgrksrfim.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtiyumqpro.html

ROLLBACK TO sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwwvcpzwt.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohpuxrkd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtueeildso.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtdqffpxrn.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtmygcqxou.html

[Q71] 查看建表语句
来源：http://dali.gogol.net.cn/Article/details/gtrltfxmwn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.redwolf501.top/Article/details/gtywnttnkn.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gtqmxvnelv.html

SHOW INDEX FROM users;
来源：http://dali.zycfv.cn/Article/details/gtboctiuwn.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtzsektnuo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.aizwys.cn/Article/details/gtjezpsumq.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtocpdkmns.html


<!-- 参考信息 -->