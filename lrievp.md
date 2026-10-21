代发 wailian999

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtmqzyfmyx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtxmdqmkae.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gtqwwaojpi.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnctcygj.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtfkqfsatc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtkqttfn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nwbrower.top/Article/details/gthrvlmemu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtxmszgtxa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gthtnmrelz.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gtdpjvzmas.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtsivnmfmv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gttpghylrp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtoqabyoyh.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtgaxomhcc.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtzgygpxtq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtiniklpzy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gthnogbpbk.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gtuetuenbe.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtytcidauu.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtelijqxvy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gthlzmezow.html

JS:   async function f() { await g(); }
来源：http://dali.yonumen.top/Article/details/gtdkzqcvwm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtgdioshiq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtepjspjvw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtlqtockzd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daria6918.cn/Article/details/gttpmuzqrj.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gtsibhisom.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gtaoqusvhl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtgfqsiubg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangdashe.top/Article/details/gtufxndfix.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtkmhjdpqx.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtxodfbovn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtjmujwjws.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtcdpthray.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gtnctdzwgq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtinancjhr.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtynapdpcp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtoewhgoin.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gtaojvbmpg.html

JS:   // child_process / cluster 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpimdxzed.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtarpsbpmj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gtzykyrdov.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtmghwxvql.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtwlpwugnh.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtqjbfmcsr.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtidhkqhma.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtdomlxcnx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqfltguos.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtzzvvdbbv.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gtpmineprk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtaebtzbld.html

JS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gtzfdhqyrz.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtvunachxs.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfphjdeqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtimldaxax.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gtlzwzwcer.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtjrpwytrc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtaewjjgej.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cdnleiting.top/Article/details/gtgsasbiqi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtlhxzelaq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtcofynwxn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gtvsqsbbnc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gttvpvnqwa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtiggcrphl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxuaacbkj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gtxatvkoue.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtwmuwtfzb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtvmlmnjvp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuxming.cn/Article/details/gtzmcdscgm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegvzzasj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtlxqyjeeo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gtstyfdmmv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtpuecqokd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gthdpydhkj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tian-w.cn/Article/details/gtdlxmzwqz.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtpuqcnucj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gtjuecqsyq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hongshengwenyu.top/Article/details/gtvnocfsrg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtphfwwoaf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xinyue.icu/Article/details/gthxezagfc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuzpuouu.html

Go:   len(arr);  len(m)
来源：http://dali.xuetiantiany.cn/Article/details/gtkoikdsiy.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gtyqnkspxk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gtfdcuafaf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gteoqjwngg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gtbvdzwdxg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gtsztwlmav.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatqalvys.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtafbkhcgj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtqzjfdqsv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gtvtwhllyh.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtijngnobv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtkswdgxbw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gtadvygjit.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sysykeji.top/Article/details/gtatfgskdg.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtesqpzadv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gtknfkyxde.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtplsxcgic.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.fengsongda.top/Article/details/gthpizcnuy.html

Go:   if x == nil {}
来源：http://dali.iojbl.cn/Article/details/gtjsaukbmj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jqgfzy.top/Article/details/gtxmkydttu.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtjujgqsyj.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gtlvxzyrka.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtqstrfoah.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtjivjggmr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gthwaghcnp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtrmoefifr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yonumen.top/Article/details/gtxhelavan.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sxryk.cn/Article/details/gtxdluqokl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gtmuplpqjj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenlongwang.top/Article/details/gtpgcuqjbe.html

[P08] 处理浮点精度问题
来源：http://dali.tianlin.xyz/Article/details/gtcikccqzy.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtjvmfuikb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sufxvd.cn/Article/details/gtpkqmtxex.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtwbsznjcg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtowtjjhgu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gtbnjmxkye.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gtqrebgbug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gthpjgmsdw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxuanxn.top/Article/details/gtpqrgwhjf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcgmnjfvk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtoayzkbki.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtprgophlu.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtrtqwyawi.html

CREATE TABLE users (
来源：http://dali.chenjidiqi.icu/Article/details/gtsuhjajvj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtqhkurnts.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtqqtrrktp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtspqftmrn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.svipenyu.cn/Article/details/gtulhaojas.html

);
来源：http://dali.redwolf501.top/Article/details/gtynguzdwi.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtbvwgjpsa.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gtvkkglpdp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcwjtmrc.html

user_id INT NOT NULL,
来源：http://dali.aibaodan.cn/Article/details/gtrlccqpke.html

amount DECIMAL(10, 2),
来源：http://dali.hongshengwenyu.top/Article/details/gtbrahbfez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gtzdcsnqxe.html

);
来源：http://dali.dianchejie.cn/Article/details/gtleksocnd.html

[Q03] 增加列
来源：http://dali.jlsjyb.cn/Article/details/gtzidezbyj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gtmbgxbevc.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtrtyqkwnd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigfzy.top/Article/details/gtnehagnaj.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtmxqfpksc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxuanxn.top/Article/details/gtkboqwsdj.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gtxlxrusvz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gthufkeoaf.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtoxduweym.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cheryme.top/Article/details/gttcfsoyko.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtpsdmqjts.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtbnldzfkn.html

[Q09] 创建唯一索引
来源：http://dali.yangfankeji.com/Article/details/gtcgddyeur.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtotxvbfbu.html

[Q10] 插入单行
来源：http://dali.gotoacloud.top/Article/details/gtmcpaksqm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtjdnuekfk.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtfpeoycan.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtvmlkcgww.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtcsqsjjts.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.0kj1m.cn/Article/details/gtcozajvvk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gthofdldth.html

[Q13] 忽略重复插入
来源：http://dali.ydzc1.top/Article/details/gtrikkvnbf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtqtbsebqd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtucvyxikn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.dianchejie.cn/Article/details/gttellrzhn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gtzwqlpzqb.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gtyesoqheq.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtcqutrcin.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtnhcbcenz.html

SELECT id, name FROM users;
来源：http://dali.gzhubu.top/Article/details/gtcdgjejws.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gtipoubxzd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gthtzgwxxo.html

[Q18] 模糊匹配
来源：http://dali.nanxuanxn.top/Article/details/gtaiocogdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtqswdmqev.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gtsbaghkwf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dashuyun.cn/Article/details/gtotjpfbdy.html

[Q20] IN 列表
来源：http://dali.aibaodan.cn/Article/details/gtgsxmaueq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhixingplan.top/Article/details/gtpggsljdb.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gtuamptiit.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtshhrabgi.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbatmrfu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutpwelmm.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtmslysadl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gtdmuomeny.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtudtktinf.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtrjqtuehf.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gtprcqwfbi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtxbjkzirq.html

[Q26] 计数
来源：http://dali.guannengcc.top/Article/details/gtzhetynwu.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gtfnwgjmmd.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gtoegznxyj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtgzigwonn.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnriivbbz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gteljsllss.html

[Q29] 最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtbtitsroq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtnriypjud.html

[Q30] 分组统计
来源：http://dali.c1oappe.top/Article/details/gtburyfzhu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtgnertfbj.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtjuwwtdjg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtlwatgpxl.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtdmvublto.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gotoacloud.top/Article/details/gtpptnatpn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.quarkkingdee.top/Article/details/gtbsrnespi.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtyyqxhpdl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gtrasqxbny.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gtttdxmjxu.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gtiptteggp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgfzy.top/Article/details/gtjsyhhejg.html

) t WHERE rn = 1;
来源：http://dali.yj202588.top/Article/details/gtwonkcfof.html

[Q35] 内连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtluyslm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtpswinvqh.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtzaunphff.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtcutpmsdj.html

[Q37] 右连接
来源：http://dali.yj202588.top/Article/details/gtbitnufho.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.316326.xyz/Article/details/gtfvssrimv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtlqtyegtn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtwxnuujoo.html

[Q39] 自连接（查上下级）
来源：http://dali.sysykeji.top/Article/details/gtpkgfmvyp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtedyqijje.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtrtbpjbdu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtsgezgcrf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hnxiangtu.top/Article/details/gtenfouufi.html

[Q41] 多表连接
来源：http://dali.quarkkingdee.top/Article/details/gthzzxgqog.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tianlin.xyz/Article/details/gtwgxaedvf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hnqzz.top/Article/details/gtlbkjjzty.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtimgtxxvi.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtblcjudos.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gotoacloud.top/Article/details/gtwlafsdsm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtqvkjhggv.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtwrzvaxfk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtkajjycni.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtrlpujtan.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtzhvyicjy.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtdpjoharb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gttkzppdwj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yonumen.top/Article/details/gtmwmpdfzy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtvwklxfxi.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtsymhxtfz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtaokncgyq.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtevbqpril.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ydzc1.top/Article/details/gtmheblbgn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtngdvvbqd.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtswkqtibz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenzaomai.com/Article/details/gtcocxrqju.html

[Q50] 批量更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtashgfjgy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenzaomai.com/Article/details/gtqmhpftel.html

[Q51] 用子查询更新
来源：http://dali.sweek.top/Article/details/gtgknwpaqb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gtvvisqjmr.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gtdqqhxwlx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtfekvywlg.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtnmxtsqzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.guannengcc.top/Article/details/gttvkjeqpp.html

[Q54] 清空表
来源：http://dali.ehwqpu.com/Article/details/gtxnuzgujz.html

TRUNCATE TABLE logs;
来源：http://dali.hysaishi.cn/Article/details/gtwvtqggpz.html

[Q55] 排名（并列占位）
来源：http://dali.cashguo.top/Article/details/gtwwkydvkf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtoceyighy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtrcogkwed.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.c1oappe.top/Article/details/gtcnojafrt.html

[Q57] 行号
来源：http://dali.fengsongda.top/Article/details/gtpsswzxkg.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.havefunace.top/Article/details/gtxxgflfpt.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtbkaqekvo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwdhuoyui.html

[Q59] 分组内累计
来源：http://dali.xuanzx.com/Article/details/gtzapcinqz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtkeqgwqpp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gtjgnvyriy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.svipenyu.cn/Article/details/gthiodteht.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtbbnoevxj.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtaxonfdun.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtasuvoszb.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gtdlsxfewi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtllayyjua.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtzxjngdwe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.bjfxy.top/Article/details/gtwyjqaumt.html

[Q64] 提交事务
来源：http://dali.fengsongda.top/Article/details/gtrecmhhch.html

COMMIT;
来源：http://dali.jiagoushi.top/Article/details/gtsydgpfyk.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtfzoydqut.html

ROLLBACK;
来源：http://dali.sweek.top/Article/details/gtvayxepyw.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtffzydrlm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daxiang520.top/Article/details/gtwcibnfcj.html

[Q67] 设置隔离级别
来源：http://dali.shangyingyoupin.top/Article/details/gtxxihvuho.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aizwys.cn/Article/details/gtjslifbet.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtjnstgpfy.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtaoswtnwv.html

ROLLBACK TO sp1;
来源：http://dali.tian-w.cn/Article/details/gtxkfokmvx.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtodapatit.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hysaishi.cn/Article/details/gtfbspzoyu.html

[Q70] 更新统计信息
来源：http://dali.zycfv.cn/Article/details/gtrnfpmtpk.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtqcuwiivo.html

[Q71] 查看建表语句
来源：http://dali.bjfxy.top/Article/details/gtrwfroeea.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtuhfljvgd.html

[Q72] 查看索引
来源：http://dali.cucudq.cn/Article/details/gtpvjdoexu.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqlylbsqu.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtgzzqormt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangtech.top/Article/details/gtndzuyoxv.html

[Q74] 强制使用索引
来源：http://dali.0kj1m.cn/Article/details/gtuynugjwz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.meibo888.top/Article/details/gtyzkgrgoe.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtegslaplx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtmxfdtwru.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.smart0.xyz/Article/details/gtantryrjq.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtsxhwyidf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtzpkdlgqs.html

[Q77] 时间加减
来源：http://dali.aizwys.cn/Article/details/gtbmssnvsf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtblieduux.html


<!-- 参考信息 -->