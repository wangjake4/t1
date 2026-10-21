代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gtkxmfqxzi.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtequbwgnt.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gtgpleucnn.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtajhaygrw.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtnycywdzn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aizwys.cn/Article/details/gtqyrsakag.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoryuhbja.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtageotcba.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtgeytcrhs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtfonmvhpv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangshuangyany.cn/Article/details/gtsqzaeiyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cdnleiting.top/Article/details/gttmmedztp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gtaecxthai.html

[O03] 加锁保护共享数据
来源：http://dali.c1oappe.top/Article/details/gtbxillpqy.html

Py:   with lock: shared += 1
来源：http://dali.jinqigfzy.top/Article/details/gtlrkotfyn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtvcybtrdj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tianlin.xyz/Article/details/gtlokewyam.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwowiucu.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxmtqyvrt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtjfqbiuqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtgtwclabw.html

C#:   lock (gate) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcbzooxrk.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuwrclmt.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtxuddbnxq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gtgthwldad.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtwivjbnqp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtogarfdjd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gtptqmzvdp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgurzmyv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gtsbpyxane.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnucbahih.html

[O05] 并发执行并等待全部完成
来源：http://dali.pengpengdd.cyou/Article/details/gtecrdfvoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jyoumei.cn/Article/details/gtxsbajjan.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gtehkenbtj.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtlgtkrsup.html

TS:   await Promise.all(tasks)
来源：http://dali.gaohongyu789.top/Article/details/gttwowatfl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtglklbxea.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtnnadgwhd.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtfzzmaask.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangtech.top/Article/details/gterztpccm.html

[O06] 使用进程池
来源：http://dali.0kj1m.cn/Article/details/gtqajycjmk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.nwbrower.top/Article/details/gtqilrnryi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gtuhhixdgn.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gttojnxrnn.html

TS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtvoaynsgn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtnebzqesw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtplcxrtak.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtuwramdoo.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtemddyzzh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqptupqoa.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gthdmysaig.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfsezfopq.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtxsuqcktd.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtiapelttl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtlyajiifs.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtzgqxsugs.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtkwgxdogy.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtszbmuyxk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtjijqpnxu.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtqfbunjdi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtnlfckork.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinghuilouyu.cn/Article/details/gtweqbycuk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtfmhmeslm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.redwolf501.top/Article/details/gtsutkqjoj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgwoxzxa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gtrmhvxkzl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtqinhyisf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gaohongyu789.top/Article/details/gtdsjhlytp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtrijfstao.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gtvzvatebp.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gthintaapo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtlgdcgwih.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtivkorjcr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtewqnyyfm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gtehjozkks.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yonumen.top/Article/details/gtkzpsbejx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangshuangyany.cn/Article/details/gtnqrqezph.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtdabjplgh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yangfankeji.com/Article/details/gtighgvhjf.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gtnwrbmbbg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtybopzkvj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtabvmzuhg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gtbvukazwi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtruhitnoc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtbizpkpov.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtohdbkrvs.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gtnadjirie.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtunpgpxga.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtbjewwqca.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpjrzpdt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tanke756.top/Article/details/gtcsklahmx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtyjcnvbfa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtliblyrkz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gtnexslneh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtcnhymqqu.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtddabwian.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtqitzdjkz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gtbkaibohy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dianchejie.cn/Article/details/gtrwzxbljf.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtyxqneokk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gtusggrxyu.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtqlvrcavp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtbbhzjtfk.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqorgkwos.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtqrdcdgzi.html

C#:   if (x is null) {}
来源：http://dali.jqgfzy.top/Article/details/gtublmvakn.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtzfnrbsda.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ybcxt.top/Article/details/gtwglcylti.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtcfzcwvjs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtgsloptah.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gttrokamrh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtnendndrs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtxuediidw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtbjhyfttn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gtstpuneth.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuducxitz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtvrserobz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yueranfly.top/Article/details/gtceqovodr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gttrtnrbju.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtyupnikxv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gttyjeryzt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtlhymzqgd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtxqnlfmwp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyheyfhu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtksqvnroz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gtjvpypiej.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcsgymmnm.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gtioasoinz.html

CREATE TABLE users (
来源：http://dali.tanke756.top/Article/details/gtiaczrdrb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtzgwixqmk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtytkaboux.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtandjnbbf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangdashe.top/Article/details/gtpvrytbxr.html

);
来源：http://dali.chenlongwang.top/Article/details/gtliqaopxe.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gtacjesjvy.html

CREATE TABLE orders (
来源：http://dali.jlsjyb.cn/Article/details/gtbqitopym.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtotdeeesg.html

user_id INT NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtahfzgmxd.html

amount DECIMAL(10, 2),
来源：http://dali.zhongyouzk.top/Article/details/gtbgcrjqnn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtatcgdkye.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtddofweho.html

[Q03] 增加列
来源：http://dali.fengsongda.top/Article/details/gtjisahorb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yangfankeji.com/Article/details/gtxdwyuqjg.html

[Q04] 修改列类型
来源：http://dali.jqgufenzy.top/Article/details/gttcjkmsmv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtoaukwmik.html

[Q05] 重命名列
来源：http://dali.yj20258.top/Article/details/gtkacduenf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gtecadvpyr.html

[Q06] 删除列
来源：http://dali.ybcxt.top/Article/details/gtooukjbyu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhengqikj.top/Article/details/gtbejqohwd.html

[Q07] 删除表
来源：http://dali.iojbl.cn/Article/details/gtpykbwtzz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtpqtbwzhb.html

[Q08] 创建普通索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpquysgu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhengqikj.top/Article/details/gtsoauxfyd.html

[Q09] 创建唯一索引
来源：http://dali.quarkkingdee.top/Article/details/gtupnlzequ.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jyoumei.cn/Article/details/gtqejshfdk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtuwyqfhny.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aizwys.cn/Article/details/gtfwinbafz.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtururvwew.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ybcxt.top/Article/details/gtreexjisz.html

[Q12] 插入后取自增 ID
来源：http://dali.shzxlz.cn/Article/details/gtrsoriaen.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gtawbqtnxe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.birdmap.top/Article/details/gtxtwiexwp.html

[Q13] 忽略重复插入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqxyvwtg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zycfv.cn/Article/details/gtbuqnxczj.html

[Q14] 存在则更新（upsert）
来源：http://dali.quarkkingdee.top/Article/details/gtqxdpfith.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtcsfulsfo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtbwqhanyy.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtlpveovtq.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtsjyyutwi.html

[Q16] 查询指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwenduqdt.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gtmvtnorzx.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtlphzouan.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gteqvectvt.html

[Q18] 模糊匹配
来源：http://dali.smart0.xyz/Article/details/gtfsshvqcu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fzhhl.top/Article/details/gtswqxwvgi.html

[Q19] 范围查询
来源：http://dali.jinqigufen.top/Article/details/gtvckziamx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsscobogq.html

[Q20] IN 列表
来源：http://dali.cqqwz.cn/Article/details/gtxeqpidkz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtlhwgvmva.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gttmzfxvfh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.aibaodan.cn/Article/details/gtpoqmnidt.html

[Q22] 排序
来源：http://dali.c1oappe.top/Article/details/gtvzgjfior.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gzhubu.top/Article/details/gtoukmmeia.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtlsravjte.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtcwcjlzdy.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtqsamlwfz.html

SELECT DISTINCT city FROM users;
来源：http://dali.ybcxt.top/Article/details/gttaherjqq.html

[Q25] 只取前 N 条
来源：http://dali.hywenlv.cn/Article/details/gtyfoleezb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtvqguhbcp.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gthicptlyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtuksiqlmj.html

[Q27] 条件计数
来源：http://dali.tanke756.top/Article/details/gtqqgxtafv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xylfe.cn/Article/details/gtilusysje.html

[Q28] 求和与平均
来源：http://dali.fzhhl.top/Article/details/gtysznkldz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtpqhrusjs.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtzbjegvnw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrklruwd.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtxxqdcvbo.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtxmvdwmbe.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gtswkjfcam.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtvmypsvbr.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtpjjtsypb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtsywvgrww.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtvgjkukic.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gthsmxhodo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtcakfqrhp.html

[Q34] 每组取第一条
来源：http://dali.ivvv.top/Article/details/gtqfxaixnp.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gtqpagwizh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aizwys.cn/Article/details/gtzdezzhii.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtqesydwuc.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtepmgtzri.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtbeaepium.html

[Q36] 左连接
来源：http://dali.ehwqpu.com/Article/details/gtlrhbxgll.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcforlpyr.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtydmdpjxw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gtgnbjhoee.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtekkuatvx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenjidiqi.icu/Article/details/gtrjdfpvpe.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtmgohyuyx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tian-w.cn/Article/details/gtddayruvg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hammf.cn/Article/details/gtepiqpcpm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqkwlsyi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtscpahwcb.html

[Q41] 多表连接
来源：http://dali.snrcjt.cn/Article/details/gtlzwfnabc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxacjzot.html

JOIN users u ON u.id = o.user_id
来源：http://dali.quarkkingdee.top/Article/details/gtybglhscr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tian-w.cn/Article/details/gtrmuejkpu.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtyinonvuy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gtzqtvotpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.quarkkingdee.top/Article/details/gtxlqolccw.html

[Q43] 标量子查询
来源：http://dali.nanxinkj.top/Article/details/gtnxfwcbsb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gthakksgda.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gtncqwwgbh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.chenlongwang.top/Article/details/gtmwewfppz.html

[Q45] EXISTS 判断存在
来源：http://dali.hnxiangtu.top/Article/details/gtvrdjhzcb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gttbokfwqh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cheryme.top/Article/details/gtieslgdia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtokpgwrvi.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gtakjnojko.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtnlnvrnye.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gtqtdzlckd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuidvxhz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtijxljgzl.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gtutjuvjsp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gturukkczs.html

[Q50] 批量更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtehacadcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtqhbveosl.html

[Q51] 用子查询更新
来源：http://dali.ydzc1.top/Article/details/gtyemxjpsp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinqigufen.top/Article/details/gtkffebucm.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gtpoumiaqk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtjxdlzbbj.html

[Q53] 按条件删除
来源：http://dali.daria6918.cn/Article/details/gtucrlpxmw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtzogwqgmy.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtyhmmepow.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtnyikenqu.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtzfdgjavi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtpfmupyko.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yvedp.cn/Article/details/gtwwmfnczf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.meibo888.top/Article/details/gthvdcbmgz.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkmymqgpa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxrzqecic.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtolbdyxaj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtqujnggic.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtlrivwtjr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtrxghhfio.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpheaqofh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtcijnytmh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gttctnjgeh.html

[Q61] 移动平均
来源：http://dali.zhongyouzk.top/Article/details/gtvrdgpxci.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtuqldymcz.html

[Q62] 分组占比
来源：http://dali.zhongyouzk.top/Article/details/gtkzducyfs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkxejuwo.html

[Q63] 开启事务
来源：http://dali.smart0.xyz/Article/details/gtksybwotf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shangyingyoupin.top/Article/details/gteeqxhjui.html

[Q64] 提交事务
来源：http://dali.c1oappe.top/Article/details/gtrjldwrrd.html

COMMIT;
来源：http://dali.fengsongda.top/Article/details/gtiwrefksq.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtiueyapdk.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtucjgqwbw.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtrroksxlr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuanzx.com/Article/details/gtmwdgvqfh.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gtpidvswop.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtemsavhtz.html

[Q68] 保存点
来源：http://dali.snrcjt.cn/Article/details/gtrxfdfvzv.html

SAVEPOINT sp1;
来源：http://dali.shuidangran.top/Article/details/gtabfqyvzo.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gtdxgfklcd.html

[Q69] 查看执行计划
来源：http://dali.sysykeji.top/Article/details/gtiqsagbke.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtzqzkzrur.html

[Q70] 更新统计信息
来源：http://dali.iojbl.cn/Article/details/gtiwxawrzm.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gtihjtpvti.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gtjjdwaczu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtauuxqyre.html

[Q72] 查看索引
来源：http://dali.cdnleiting.top/Article/details/gtigbrpqvw.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtoiedxcbe.html

[Q73] 查看表状态
来源：http://dali.quarkkingdee.top/Article/details/gtagwjiqoh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtrilwxwqw.html

[Q74] 强制使用索引
来源：http://dali.feifeiyinyue.top/Article/details/gtsjbobzes.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtttsrqbwn.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtejatgtlf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtcjddmtut.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ppjwa.cn/Article/details/gtvkavialm.html


<!-- 参考信息 -->