代发 wailian999

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtdkvgtxwi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtgrxqxdff.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtgufagccx.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtzdjopwna.html

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gtlkpxfpqg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gtlpfmanxb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gthjqwbeac.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtktjkcmkp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtcpxsxz.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcwgzxey.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gtxcmaionf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnjlylrg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sysykeji.top/Article/details/gthtocwcmh.html

TS:   // 同 JS
来源：http://dali.316326.xyz/Article/details/gtppvlwsqu.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gtejzwgvho.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtefkdkjxc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gteeyqwtzo.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtcwrxmwgb.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gtezpsjixj.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtngivvikw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtkdhdjyzy.html

JS:   async function f() { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gtwuzqwjqs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtmgyenvvn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gtpovuqxvp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gtmghrauby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gtjwmnhdgd.html

C#:   async Task F() { await G(); }
来源：http://dali.yuanzhike.top/Article/details/gtoppvllgh.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258.top/Article/details/gtrowwzkuc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtvwzqvtzt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtmfaroqoq.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtieyegcyx.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtosguwcrc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtsgzmlrce.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtkivcxyrf.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gtmojsjaoa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtuvedymwb.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gtjyclmpkj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gtrxwlbgyx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gtteybfvxw.html

JS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhyxjueo.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gthyhgwraj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gteulobdla.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtexusawcp.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtvzttzovy.html

C#:   Parallel.For
来源：http://dali.aibaodan.cn/Article/details/gtpldkclfu.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtiqzxrfaq.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtsgkojrzr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwmqwyxoe.html

[P01] 生成 UUID
来源：http://dali.9152youxi.cn/Article/details/gtlplluada.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtunuqykev.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtdxqntbsx.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtpecawdvn.html

TS:   crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtpewhfkiy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbrsklti.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258.top/Article/details/gtwsiuwwri.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtziedxvyn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gthdyldyvt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gtxdrmkhci.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtpqyfrnbb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtmipzhvow.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gtcishstdn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtbvqcxbkk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtticptzfo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gththwzvuw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xziqi.cn/Article/details/gtjhyombzt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daxiang520.top/Article/details/gthvqwadkc.html

[P03] 生成短随机字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtkytdkxdi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtmwayxafi.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ybcxt.top/Article/details/gtsdbbphsm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtjasgnzex.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtlactuose.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gtqcotxraw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gtwaxhuixc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gtwocbgygb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtoelrkhzv.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtzdxufzae.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jlsjyb.cn/Article/details/gtwvdnymgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtncoqjbhn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtkeuixpkj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gtxvxcsuay.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtzziqdwys.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gthhucutcq.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtuqneammj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258888.top/Article/details/gtlfumyydn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtezkgtjbs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtreqvytjl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gtznihxqdw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtvjtnnhee.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtuhwgwpjf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtdidhyfmz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrmfmimd.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtazjwfcuj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hywenlv.cn/Article/details/gtpzycmksa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gotoacloud.top/Article/details/gtrdodeejs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtouqwfkux.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gtnxizinbo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtmyviaenc.html

TS:   if (x == null) {}
来源：http://dali.zycfv.cn/Article/details/gtmmmbkjnk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtymgblydd.html

Go:   if x == nil {}
来源：http://dali.yongpay.top/Article/details/gtrhemyawi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtzkvahjqr.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtjviqysvq.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtvvipcixx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtkyivrada.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtgbtninwa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtsdrxrqms.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtpbcaxggw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtxubwtafz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtaurxqzmj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtizabzpul.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gtbkygfpao.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtgtibhzpg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbfgrrig.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtomiybakn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtmavjzyhv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtmdkcusik.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtbydmwmqu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtkqhpmrdi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.c1oappe.top/Article/details/gtpciovwua.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cqqwz.cn/Article/details/gtmbrtwonj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphzxzcke.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gtquvzjlnm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsgckqfui.html

[Q01] 创建表
来源：http://dali.guowangkeji.top/Article/details/gtlilywesd.html

CREATE TABLE users (
来源：http://dali.yuxming.cn/Article/details/gtjjcafvzl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtmunkznqt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtvxlpvkjz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cdnleiting.top/Article/details/gtulxvyail.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtjzyiplln.html

);
来源：http://dali.hammf.cn/Article/details/gtxqogfdiw.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtdcafmsuu.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtnpfimzzm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gtvdhkqxfe.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtaoorlnuz.html

amount DECIMAL(10, 2),
来源：http://dali.yonumen.top/Article/details/gtrhrgpqzv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtpienrjvp.html

);
来源：http://dali.yangfankeji.com/Article/details/gtjxpledhk.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gtlguqlfiy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtsggthbgg.html

[Q04] 修改列类型
来源：http://dali.haohaochexian.top/Article/details/gtzhigmfdk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fzhhl.top/Article/details/gtdgqgryxy.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gtmzpzqawl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xinyue.icu/Article/details/gtmzilxhtr.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtbvzzwzpn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtglldaqdx.html

[Q07] 删除表
来源：http://dali.cqqwz.cn/Article/details/gtcbkwdogj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.quarkkingdee.top/Article/details/gtzqafjnao.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtvagkkxgg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gteaxarpke.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gtbzvexchu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtqyanuvou.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtbcdgoxxi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtqurtyztx.html

[Q11] 一次插入多行
来源：http://dali.redwolf501.top/Article/details/gtczmmhbyv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtovpqfbsz.html

[Q12] 插入后取自增 ID
来源：http://dali.cashguo.top/Article/details/gtfdvunnlh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yvedp.cn/Article/details/gtcfadueos.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fzhhl.top/Article/details/gtmptftxek.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtbsbwtfsw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtqolyheai.html

[Q14] 存在则更新（upsert）
来源：http://dali.haohaochexian.top/Article/details/gtrhdiwiql.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenlongwang.top/Article/details/gtlasyzscz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gtfmipoyps.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gtmrtdynoy.html

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtuhvvvwxk.html

[Q16] 查询指定列
来源：http://dali.jqgufenzy.top/Article/details/gtdpircpoi.html

SELECT id, name FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtcbcuqfgo.html

[Q17] 条件查询
来源：http://dali.cashguo.top/Article/details/gtsuddybso.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guowangkeji.top/Article/details/gtbxctrkzp.html

[Q18] 模糊匹配
来源：http://dali.yongpay.top/Article/details/gtclchmalw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtnmgbnhzm.html

[Q19] 范围查询
来源：http://dali.jinqigfzy.top/Article/details/gtuwgdfyna.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xuetiantiany.cn/Article/details/gtaozkziav.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gtzatpwabd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtrkpnixop.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtvvidozyl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtieacnfvx.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtabsdihwk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcscjhevx.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtzxgxthtc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtlraamvuj.html

[Q24] 去重
来源：http://dali.sysykeji.top/Article/details/gtsmkeujoy.html

SELECT DISTINCT city FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtzwgaliqg.html

[Q25] 只取前 N 条
来源：http://dali.gotoacloud.top/Article/details/gtcsdjvraj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtmutjuqid.html

[Q26] 计数
来源：http://dali.hfpthk.cn/Article/details/gtqessohyp.html

SELECT COUNT(*) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtawgeuixw.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpoctdhrt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yongpay.top/Article/details/gtoxqmtdhf.html

[Q28] 求和与平均
来源：http://dali.kuanghao11.cn/Article/details/gtaeouyodx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtsfljrhyv.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtmrlfigrp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.316326.xyz/Article/details/gtzaftwyuc.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gtzcqgvdyp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gteyglxoow.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtseljbnmh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtxjvfbjza.html

[Q32] 分组拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtiiaucxeh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtnvhwrrsf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.bjfxy.top/Article/details/gtwxlitsyk.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtloiuaqam.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtdufectpz.html

[Q34] 每组取第一条
来源：http://dali.zdqjudy.top/Article/details/gtwxasftdo.html

SELECT * FROM (
来源：http://dali.tian-w.cn/Article/details/gtmtxxcvhe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xziqi.cn/Article/details/gtguvcqqaj.html

) t WHERE rn = 1;
来源：http://dali.hysaishi.cn/Article/details/gtenipuyvw.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtstvgmelv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gtismhgsav.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gtyxjguuky.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtaaphmkmt.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtcjjwrsvf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gtagzifykc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gtfaxfzokq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxnpysxj.html

[Q39] 自连接（查上下级）
来源：http://dali.birdmap.top/Article/details/gtfiuculkf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gthidyznbh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtylozefym.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jianghu66.top/Article/details/gttptbpdqd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shuidangran.top/Article/details/gtqnwgadmc.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtkeeevfob.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gtydraeyqk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gtglcjuqjc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtlgpwdwsf.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtzycozhqx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtpgvmzupr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtfdwysglp.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gtutgrivbj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zdqjudy.top/Article/details/gtgfsqpivp.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gtnlesdmln.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhoulong.xyz/Article/details/gtpxedigsd.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtarnbhjur.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtdgvymrum.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gtsilzrxkp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dianchejie.cn/Article/details/gtmwwncxph.html

[Q47] 与平均值比较
来源：http://dali.yangfankeji.com/Article/details/gtjlpalhej.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtzawjfzii.html

[Q48] CTE 公用表表达式
来源：http://dali.havefunace.top/Article/details/gtytsncpys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gttxekgtln.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtnxfvuvzf.html

[Q49] 更新单行
来源：http://dali.daria6918.cn/Article/details/gtgimftrzd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtsgwuzcdk.html

[Q50] 批量更新
来源：http://dali.hfpthk.cn/Article/details/gtocvbzcsq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtxrhavriy.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwjmdrapq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.meibo888.top/Article/details/gtrpypufeq.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtzdzzlzje.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtzrnsbrvt.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gthfuevjea.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtpgcjfjjz.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gttlyweafp.html

TRUNCATE TABLE logs;
来源：http://dali.xziqi.cn/Article/details/gtipmamnpo.html

[Q55] 排名（并列占位）
来源：http://dali.xinyue.icu/Article/details/gtagjnslxx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtdnnpfbey.html

[Q56] 密集排名（并列不占位）
来源：http://dali.redwolf501.top/Article/details/gtivilofjt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtrbwwjtsm.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtgghqujuk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtmqypogpy.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtwzpayaex.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtviwytgqu.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtvjynmqsp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtwpjdzlzt.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtyujivunr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtbabubdbk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtiszkueml.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtrvgutyuh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtrmvphlbm.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gtkpuenfvg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtzgggmbmq.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtsuvsyqgd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtftjfkdra.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtnqcstfnm.html

COMMIT;
来源：http://dali.xuetiantiany.cn/Article/details/gtxsirinue.html

[Q65] 回滚事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgictgvvi.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtbyukmpdb.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtiztoclqr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtorqbpgfb.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtipnoeteq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtmzskuspx.html

[Q68] 保存点
来源：http://dali.cdnleiting.top/Article/details/gtemjorafu.html

SAVEPOINT sp1;
来源：http://dali.316326.xyz/Article/details/gtquhngpdw.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gttuskyqhx.html

[Q69] 查看执行计划
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedeqizle.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtnfgoyaju.html

[Q70] 更新统计信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopgsbhgo.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gtyyxhqshv.html

[Q71] 查看建表语句
来源：http://dali.yueranfly.top/Article/details/gtoddkxjus.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sxryk.cn/Article/details/gtdtitmvxd.html

[Q72] 查看索引
来源：http://dali.aizwys.cn/Article/details/gtmdajlexx.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gtnyutclhh.html

[Q73] 查看表状态
来源：http://dali.yonumen.top/Article/details/gtvymwnbpc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtwxdoydif.html

[Q74] 强制使用索引
来源：http://dali.pengpengdd.cyou/Article/details/gtjuahtbcv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gtydusmbgv.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gtrzszzgob.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtyowagmru.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dianchejie.cn/Article/details/gtjpqnlcai.html

[Q76] 按天统计
来源：http://dali.sxryk.cn/Article/details/gtghcuzpuh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtsgvjvvtk.html

[Q77] 时间加减
来源：http://dali.yonumen.top/Article/details/gtdznckbxi.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxldiiiv.html


<!-- 参考信息 -->