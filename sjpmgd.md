代发 wailian999

[O02] 使用线程池
来源：http://dali.smart0.xyz/Article/details/gtmkxsvygx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gtynxhxvtb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gtgotkwxzp.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtyfagyeak.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtgykqvyjx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtyyzcbatw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhixingplan.top/Article/details/gtmopqcyqg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.316326.xyz/Article/details/gtnhkaaexb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtkqjduwwk.html

[O03] 加锁保护共享数据
来源：http://dali.hammf.cn/Article/details/gtbwncfxex.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gtdgkedhio.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gtitblcqko.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtlogmcrpp.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gttkiioqyj.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtiusnbcdo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.redwolf501.top/Article/details/gtopchhhfy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shzxlz.cn/Article/details/gtjctjjxpp.html

C#:   lock (gate) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gtjszricwz.html

[O04] 定义异步函数并等待
来源：http://dali.bjfxy.top/Article/details/gtagndxybv.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrozlyuob.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrydbibpz.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtpnucqkbe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtxycqhzwy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtkwkpjjll.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtghuuvmwr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gtortdusdr.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtxyrmeejo.html

[O05] 并发执行并等待全部完成
来源：http://dali.bjfxy.top/Article/details/gtfnqxwsli.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gtqprimejy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtewcekxvj.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtvaeiszsc.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtykjawcqa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangdashe.top/Article/details/gtignscjkm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.smart0.xyz/Article/details/gtqbuuovce.html

Ruby: threads.map(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtwysdvnzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gtaebbkbsl.html

[O06] 使用进程池
来源：http://dali.hnqzz.top/Article/details/gtibzjhlfy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dashuyun.cn/Article/details/gtqurcforu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtlhvsvgke.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gthopowzqr.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtqwxturfo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gtihnesqrv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtuudxsjzb.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtfretnszs.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtzkctmfru.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtiwtegpnt.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gthvnqgarl.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwwfbvgls.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtrphxkjrh.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gtfdpqwtsq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtttmwpiza.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gttrqqinjv.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtmxymmlhj.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gtvsgsdtiz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtlzazufqd.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtkcftstcd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gtshltuhbt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtyztelboq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtvngzrwap.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtojjhsgsg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhengqikj.top/Article/details/gtrxmsycsa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtzrszmycj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttfyitqdp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtqcgslqux.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtqgjmxxvw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtodxarkyr.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gtikuucrch.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shuidangran.top/Article/details/gtsbuwdipp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtgemtffmf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtvxlqwpfo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtnpkkmcln.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gtktxvbhit.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gtlxrvgylr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwxnttbz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtkomyxyqv.html

[P04] 求长度
来源：http://dali.0kj1m.cn/Article/details/gtgljnhmnl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtywiholqz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gtxgsahxfx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtuucozpzv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtehjbxazk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuxming.cn/Article/details/gtnmxkgfcl.html

Go:   len(arr);  len(m)
来源：http://dali.yuanzhike.top/Article/details/gtbciogylb.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtrywdcxyy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gtchqvbesp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gtbjhuorbt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gtcaxpqnvv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjutkhovl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtichgeplh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtoublzytr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gtzdwlplhe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daxiang520.top/Article/details/gtgveaqhpw.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtcrdvmzwv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gtamzoagcc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtlirwuctq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtfbhzopca.html

PHP:  if (empty($x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdziynedl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtabllwyln.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gtulkttzgf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtryywcrnx.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtlsrppuvd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtfhzptcvt.html

C#:   if (x is null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzztgmicm.html

[P07] 防抖与节流
来源：http://dali.xuetiantiany.cn/Article/details/gtctrgjecy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xuetiantiany.cn/Article/details/gtsoarjqoh.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtsaulfytl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtpkmqrcoh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtzgahgecg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gtwzdlaokf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gtqcqxjkru.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jianghu66.top/Article/details/gtcrxxwlqn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gtvkbryxep.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrdjisph.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sweek.top/Article/details/gtkntquoxi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dianchejie.cn/Article/details/gttqwzwqvp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gtfcsrrkkl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtrseagrma.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtqmqqnuan.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjhamyyr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gtvleyelug.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gtnzxgtncx.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlbsiqygu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtgskarjvv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthjziwkdp.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gttlsxpfpv.html

CREATE TABLE users (
来源：http://dali.ybcxt.top/Article/details/gtayojqzhv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtkjtvdgql.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtczhbqmbs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtfyakzryk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtrceppfzh.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnavkiawj.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtaduoieza.html

CREATE TABLE orders (
来源：http://dali.yonumen.top/Article/details/gtrjybrlum.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtigvgtzfg.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtygfdbugg.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtonhpwqoc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tian-w.cn/Article/details/gtsuiuoqzj.html

);
来源：http://dali.andypj.xyz/Article/details/gtwcpapdkw.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtpoglqxpe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dianchejie.cn/Article/details/gteyxfdiwl.html

[Q04] 修改列类型
来源：http://dali.kuanghao11.cn/Article/details/gtvlenzxhw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtpjtifylt.html

[Q05] 重命名列
来源：http://dali.9152youxi.cn/Article/details/gtttftykyk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fzhhl.top/Article/details/gtscdtszbh.html

[Q06] 删除列
来源：http://dali.pycfn.com/Article/details/gtrnpwwpep.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shzxlz.cn/Article/details/gtdhwwapmq.html

[Q07] 删除表
来源：http://dali.tian-w.cn/Article/details/gtfmioytgt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtkuxtqyld.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gtggobhrrf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gteaprfzsa.html

[Q09] 创建唯一索引
来源：http://dali.jinqigfzy.top/Article/details/gtzlufzahq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtlsuouttn.html

[Q10] 插入单行
来源：http://dali.chenjidiqi.icu/Article/details/gtwhqepyia.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtnpfgzmzs.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtntylkdpk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtqjnmxpgh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhengqikj.top/Article/details/gtecyeqenm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtqiyjifdu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtuvhccxcf.html

[Q13] 忽略重复插入
来源：http://dali.ivvv.top/Article/details/gtrghnwbhh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jqgfzy.top/Article/details/gtpfdsmcge.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtxthjjqdl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtaigjjjug.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xuetiantiany.cn/Article/details/gtyhqlwmcm.html

[Q15] 查询全部
来源：http://dali.yueranfly.top/Article/details/gtopiefznm.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtdyogydva.html

[Q16] 查询指定列
来源：http://dali.nwbrower.top/Article/details/gtlvkmvfwy.html

SELECT id, name FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtbroudboz.html

[Q17] 条件查询
来源：http://dali.ydzc1.top/Article/details/gtudxrjmsm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnjbkokd.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtevxglmgr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtlsuwkpru.html

[Q19] 范围查询
来源：http://dali.ivvv.top/Article/details/gttcyqogqc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gthgxzumjp.html

[Q20] IN 列表
来源：http://dali.hfpthk.cn/Article/details/gtgnaubbij.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkghqeth.html

[Q21] 空值判断
来源：http://dali.vqdsnc.cn/Article/details/gtgsxomtxe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtktqwzzdt.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gtwxwqyaut.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwrvvkjg.html

[Q23] 分页
来源：http://dali.fengsongda.top/Article/details/gtkstldizh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.c1oappe.top/Article/details/gtpkocadub.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfmuemop.html

SELECT DISTINCT city FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtlcqdzacu.html

[Q25] 只取前 N 条
来源：http://dali.redwolf501.top/Article/details/gtdjgzuxsy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtgfrzymqu.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtkcnnsntn.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtnjuhvomg.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtoznocnlx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gttnhigqzy.html

[Q28] 求和与平均
来源：http://dali.nanxuanxn.top/Article/details/gtonvgyzog.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtwhjnzpkt.html

[Q29] 最大最小值
来源：http://dali.xziqi.cn/Article/details/gtfzmreket.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtjhbpqvdv.html

[Q30] 分组统计
来源：http://dali.zhoulong.xyz/Article/details/gtnsxqxkew.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtgkhmkopz.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gtcydnaouv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtmavffajv.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtftuhjlrr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gtrreomqsg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sysykeji.top/Article/details/gtxgsbrjtn.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gtrokpsmxa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.iojbl.cn/Article/details/gthkmmmgcu.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gttaobagxj.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtnkekgpnr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.iojbl.cn/Article/details/gtqgecmqhe.html

) t WHERE rn = 1;
来源：http://dali.xuanzx.com/Article/details/gtdrervotf.html

[Q35] 内连接
来源：http://dali.guowangkeji.top/Article/details/gtinfpdupf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtkvuaontj.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaktfega.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtejcfrskn.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtwtezzhfo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258888.top/Article/details/gtwbcswxmx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtfchvmxue.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtyuymyrji.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtfkwvjtsz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zdqjudy.top/Article/details/gtwmewhltm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.haohaochexian.top/Article/details/gtgbeejmrz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwozqzfe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtoalhizpg.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gtmbcwjsuw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihrrjbvh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.cheryme.top/Article/details/gtcjpzjuoq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.tanke756.top/Article/details/gtivxgquce.html

[Q42] 连接条件附加过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtsdyxivax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxuanxn.top/Article/details/gtoqnatgpg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnqzz.top/Article/details/gtxvdmogny.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gtcmowmvvv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtmmfrhgep.html

[Q44] IN 子查询
来源：http://dali.pengpengdd.cyou/Article/details/gtapetorzn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtfpbtgqvz.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtrnpxkfid.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtppetpylb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpmbfaiy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtjgfhozpi.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gttxwlhxsk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gtqndrzdaw.html

[Q48] CTE 公用表表达式
来源：http://dali.cdnleiting.top/Article/details/gtlehvqock.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtzztswnrs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsttzeckz.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtrcccakse.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gtierslpfj.html

[Q50] 批量更新
来源：http://dali.nwbrower.top/Article/details/gtgldfgcsv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtcvpgajje.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtqdgccywt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtxsodubkt.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gtyiafssnw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtxotivsxr.html

[Q53] 按条件删除
来源：http://dali.cqqwz.cn/Article/details/gtwizjfgoz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtpipenrpg.html

[Q54] 清空表
来源：http://dali.guowangkeji.top/Article/details/gtnbwbwiaw.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtkbrlnvcf.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtanmdqdaq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtghtqajoe.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtlmcfuqoa.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtuszttslu.html

[Q57] 行号
来源：http://dali.jqgfzy.top/Article/details/gtnojkcqqk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtasatovrt.html

[Q58] 累计求和
来源：http://dali.snrcjt.cn/Article/details/gtycfuerka.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtyzogfgrb.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtrauverfu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtchsnljrh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtmjogqcfw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daria6918.cn/Article/details/gtqrfazorw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtqftskrli.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtrbetcbnb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrhnsuzc.html

[Q62] 分组占比
来源：http://dali.hnqzz.top/Article/details/gtwhytnfmt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiwvcwgg.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gtijlcckzy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtuujrqyyi.html

[Q64] 提交事务
来源：http://dali.hywenlv.cn/Article/details/gthkkvdjii.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtlpjjqlfa.html

[Q65] 回滚事务
来源：http://dali.jinqigfzy.top/Article/details/gtuhyebwkv.html

ROLLBACK;
来源：http://dali.cdnleiting.top/Article/details/gtaxaggpds.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtbbenehjc.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.feifeiyinyue.top/Article/details/gtvfpqnjtg.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gttgvilnpv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gtzdxbvvoi.html

[Q68] 保存点
来源：http://dali.fengsongda.top/Article/details/gtzibebqyi.html

SAVEPOINT sp1;
来源：http://dali.redwolf501.top/Article/details/gtwioojkhn.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtavxzflmz.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtprhogmzz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtijnjekgg.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtsrmohjkt.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtzxuoswpl.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gtbgljezcl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yonumen.top/Article/details/gtrqwgounw.html

[Q72] 查看索引
来源：http://dali.hfpthk.cn/Article/details/gtxrfqgyqi.html

SHOW INDEX FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtgdbudcmz.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtzietbcxv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtqyrtucvl.html

[Q74] 强制使用索引
来源：http://dali.aizwys.cn/Article/details/gtvyvsbmvm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.pycfn.com/Article/details/gtcvgcqmoz.html

[Q75] 日期格式化
来源：http://dali.yonumen.top/Article/details/gtxskdidcm.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gtwhqczxhx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.guannengcc.top/Article/details/gtdobiavhv.html

[Q76] 按天统计
来源：http://dali.birdmap.top/Article/details/gtllqgvutt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.0kj1m.cn/Article/details/gtzpvvhjwi.html

[Q77] 时间加减
来源：http://dali.meibo888.top/Article/details/gtubexxyjn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xinyue.icu/Article/details/gtqidyyqrw.html


<!-- 参考信息 -->