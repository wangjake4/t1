代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtrpxttglc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtddnmhlly.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtfrtntzoh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hammf.cn/Article/details/gtlcnusywa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.redwolf501.top/Article/details/gtiajkdowg.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtbpdxxbeq.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gttuessgvq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtlairvkzr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gotoacloud.top/Article/details/gtkrclbwaz.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gttjptmpzu.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gttffflfeg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gtyeczryxx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtfxijmvnf.html

C#:   lock (gate) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtxpqwapvf.html

[O04] 定义异步函数并等待
来源：http://dali.sufxvd.cn/Article/details/gtfytmxzad.html

Py:   async def f():⏎    await g()
来源：http://dali.yonumen.top/Article/details/gtejmaomig.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.smart0.xyz/Article/details/gthpxugfmv.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigfzy.top/Article/details/gtsfengrss.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfkucbiu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gotoacloud.top/Article/details/gtlepeltbq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtilbaosza.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gtborgoqeo.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gtcfwcgacr.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gttdohngzn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtymjtuzsz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtxntbiokp.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtswmuacbv.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gttojufkei.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gtravhriwu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtffqeubst.html

Ruby: threads.map(&:join)
来源：http://dali.tanke756.top/Article/details/gtaesagcwb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gtnxpudsxc.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gttfbyaqsn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtisqpxgiw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtghsstcay.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtnmdzmpoy.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtsysbzkcl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gthvcjzgnb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.birdmap.top/Article/details/gtqnxmcjpo.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gtfmpngenf.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtwweetmio.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthmfjrcmt.html

P. 常用工具函数
来源：http://dali.wangdashe.top/Article/details/gtoiyifhtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtoiwkqlmq.html

[P01] 生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtfiadgajv.html

Py:   str(uuid.uuid4())
来源：http://dali.wangshuangyany.cn/Article/details/gthyxedppv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gtsgficsab.html

JS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtjujkcdxz.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtijmuzwoo.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtbuwboxil.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtyacxlesc.html

Ruby: SecureRandom.uuid
来源：http://dali.cashguo.top/Article/details/gtgfphumiu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xylfe.cn/Article/details/gtlahgbhbv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ppjwa.cn/Article/details/gtwrqxbmkf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtsupwiuji.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gtknfkgnts.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jqgfzy.top/Article/details/gtgdmbeqmm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtzfzekdcb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gthfoblcev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuanzhike.top/Article/details/gticuvljvt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtzrfdqupq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtlekmmaor.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gtphohgqsy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dianchejie.cn/Article/details/gtkmvkhuzb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yonumen.top/Article/details/gtjsflgvsd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtyzzymmjo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gteidmmpal.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.havefunace.top/Article/details/gtloxspcdv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtuanwsvba.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gtxvygzzbf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gtytmvrjdu.html

[P04] 求长度
来源：http://dali.yonumen.top/Article/details/gtopgaawff.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.kuanghao11.cn/Article/details/gtmirenidl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtopzjzfxm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtcsymgzqt.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtkifxlust.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtiqkpbaev.html

Go:   len(arr);  len(m)
来源：http://dali.tian-w.cn/Article/details/gtegtpntfs.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtjnwxvujq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtesllgnbf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sweek.top/Article/details/gtezelwnth.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gteehgrgps.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gtkakvmwik.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.quarkkingdee.top/Article/details/gtvxwtvtqq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtvuiyncly.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtdllucoub.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtagkjlndk.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtrvfuxwqv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtufvnkpqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.andypj.xyz/Article/details/gtreqozvlp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtjlodjfwn.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrbdfshso.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.chenjidiqi.icu/Article/details/gtxffbohat.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkjakyyuf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtflnyxbcf.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtqkmlabuo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gtlahjwwxk.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtyhlvqeaw.html

[P07] 防抖与节流
来源：http://dali.gaohongyu789.top/Article/details/gtjpusszyo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtfnxmhpot.html

PHP:  // 手写时间戳比较
来源：http://dali.jqgufenzy.top/Article/details/gtkzetztgj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtmrleqvro.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtgwtalcnm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtnmvneiak.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.snrcjt.cn/Article/details/gtfockhhsl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtvujnrpij.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtzzykwhws.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gtyqkexram.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtprvryqmc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cdnleiting.top/Article/details/gthftqqylp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gtkoegfsnz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gtjtruksdf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenzaomai.com/Article/details/gtnmysolon.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj20258888.top/Article/details/gtlisblkzy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtwsqnljxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.andypj.xyz/Article/details/gtsdvjylag.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtprbsgtuj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvgjexlh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtziynrmut.html

[Q01] 创建表
来源：http://dali.ehwqpu.com/Article/details/gtdubblckh.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnbsaaif.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtqxehrtbm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtyeqnuipn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aizwys.cn/Article/details/gtzpxamedp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gtppzunctz.html

);
来源：http://dali.jyoumei.cn/Article/details/gtkayzkufx.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gtfvmpgags.html

CREATE TABLE orders (
来源：http://dali.vqdsnc.cn/Article/details/gttdeghnta.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dashuyun.cn/Article/details/gtxzcvtrlz.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtzrazlkol.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtnancdzkz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gtkjuwcojf.html

);
来源：http://dali.yueranfly.top/Article/details/gtmwfwazoj.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gtxxmwmrjf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtegtglxrs.html

[Q04] 修改列类型
来源：http://dali.yuanzhike.top/Article/details/gtxrctcrfa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtfekvuaow.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtpsawmtdm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gtzuhyvwgc.html

[Q06] 删除列
来源：http://dali.quarkkingdee.top/Article/details/gtcclhwtpn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenjidiqi.icu/Article/details/gtnkerzjdp.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gtlzempmsf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gtemzligyv.html

[Q08] 创建普通索引
来源：http://dali.aizwys.cn/Article/details/gtvsgtgjkl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gtwagfnjam.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqibphco.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yueranfly.top/Article/details/gtusrcdbhf.html

[Q10] 插入单行
来源：http://dali.yj202588.top/Article/details/gtpyljxosw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gtszjvkpwt.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gticpqmhze.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenjidiqi.icu/Article/details/gtfconbvxz.html

[Q12] 插入后取自增 ID
来源：http://dali.c1oappe.top/Article/details/gtzdfdsryo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtgxuryygd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtuaktbrxe.html

[Q13] 忽略重复插入
来源：http://dali.316326.xyz/Article/details/gtdsniuwih.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj202588.top/Article/details/gtqbkytyob.html

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtmfmmucld.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cucudq.cn/Article/details/gtnevhtawe.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtcahhwslm.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtmnonuwug.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtfoeqwlxa.html

[Q16] 查询指定列
来源：http://dali.svipenyu.cn/Article/details/gtcjnwqeob.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtpgqgzjgq.html

[Q17] 条件查询
来源：http://dali.svipenyu.cn/Article/details/gtkymyabuw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gzhubu.top/Article/details/gtpcccxqnz.html

[Q18] 模糊匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtdwqgzhrp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.0kj1m.cn/Article/details/gtlsuwwwwv.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gtedjrohgl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.wangshuangyany.cn/Article/details/gtupmvmwyj.html

[Q20] IN 列表
来源：http://dali.yonumen.top/Article/details/gtcmfkmcsq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zdqjudy.top/Article/details/gtgmvfqfga.html

[Q21] 空值判断
来源：http://dali.sweek.top/Article/details/gtlelfrlxo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtxmmlijsx.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtdmoqyiex.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtmusrcrac.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gtaernwkga.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shangyingyoupin.top/Article/details/gtoklyqpee.html

[Q24] 去重
来源：http://dali.shzxlz.cn/Article/details/gtjxpywygd.html

SELECT DISTINCT city FROM users;
来源：http://dali.sxryk.cn/Article/details/gtlsnneioi.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gtxputfxdl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.haohaochexian.top/Article/details/gtuysosiaj.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtcmcavvur.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtpcbqecuw.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtbvxcfjke.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfnjvnsvq.html

[Q28] 求和与平均
来源：http://dali.bjfxy.top/Article/details/gtcyvtmogu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtmhcztzgj.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtcmdlstes.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtsgigkulz.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gthggzreei.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtacsfifpz.html

[Q31] 分组后过滤
来源：http://dali.nanxinkj.top/Article/details/gttqvbpynz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dianchejie.cn/Article/details/gtjntawewz.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtpevevyzq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtwrskkbbh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtxddtmgbm.html

[Q33] 多列分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdexxlbpn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtruagobvs.html

[Q34] 每组取第一条
来源：http://dali.jiagoushi.top/Article/details/gtygmhjprq.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtinpghdpq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tian-w.cn/Article/details/gtbtuuqyao.html

) t WHERE rn = 1;
来源：http://dali.yonumen.top/Article/details/gtigmyusih.html

[Q35] 内连接
来源：http://dali.zhengqikj.top/Article/details/gtprlnyvgk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtjwxxclmg.html

[Q36] 左连接
来源：http://dali.sxryk.cn/Article/details/gtcindtqvk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnksgjsco.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtjfgptegx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tianlin.xyz/Article/details/gtfmrggusf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtvigpytuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtugxyecrv.html

[Q39] 自连接（查上下级）
来源：http://dali.quarkkingdee.top/Article/details/gtryttttbe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtkxajwtcq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.0kj1m.cn/Article/details/gtscchajel.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shzxlz.cn/Article/details/gtcnjvvyrc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtnbmhblxr.html

[Q41] 多表连接
来源：http://dali.cheryme.top/Article/details/gtvwugfevd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gtgddrqqen.html

JOIN users u ON u.id = o.user_id
来源：http://dali.kuanghao11.cn/Article/details/gtnltsjsfn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtsuzvgphq.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtqhgrbmhq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtvhpxkdif.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.fengsongda.top/Article/details/gtxbzdlxld.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtyulbhlno.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtyhclqseq.html

[Q44] IN 子查询
来源：http://dali.aizwys.cn/Article/details/gtleoxskgt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.havefunace.top/Article/details/gtriwusycs.html

[Q45] EXISTS 判断存在
来源：http://dali.xinyue.icu/Article/details/gtfkerzatt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtcyyfafzp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fengsongda.top/Article/details/gtiitdmayq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtbhqcaehu.html

[Q47] 与平均值比较
来源：http://dali.ppjwa.cn/Article/details/gtduzgppbk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zycfv.cn/Article/details/gtqbrrmfzk.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtdrumkitk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yongpay.top/Article/details/gtywkxgupd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtyshemgqr.html

[Q49] 更新单行
来源：http://dali.kuanghao11.cn/Article/details/gttxggrzep.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtboihrwat.html

[Q50] 批量更新
来源：http://dali.yuxming.cn/Article/details/gtpeayxslu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtifsdooyy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gtepijahrr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtvfcijrsm.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtduvrxpce.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gtjavmzdqe.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gtzdbbarff.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtghbgwddh.html

[Q54] 清空表
来源：http://dali.c1oappe.top/Article/details/gtwahuhvhi.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtelxpgelp.html

[Q55] 排名（并列占位）
来源：http://dali.cucudq.cn/Article/details/gtznjqfcwt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtliecaehg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtsphlmrfd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakhmsbdi.html

[Q57] 行号
来源：http://dali.feifeiyinyue.top/Article/details/gtdmoqhsdy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtgschdool.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gtvmyjnzco.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtlzacuicv.html

[Q59] 分组内累计
来源：http://dali.cqqwz.cn/Article/details/gtxxkfdsjw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtzlvzoibt.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gteendaqqe.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.0kj1m.cn/Article/details/gttfzuniip.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gtuzjhognf.html

[Q61] 移动平均
来源：http://dali.yonumen.top/Article/details/gtunuzahgh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtpeadvfrp.html

[Q62] 分组占比
来源：http://dali.ydzc1.top/Article/details/gtgfcfuxrm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtmqeejfht.html

[Q63] 开启事务
来源：http://dali.cucudq.cn/Article/details/gtoraqqoep.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvhormot.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnijqebg.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtjihbcemw.html

[Q65] 回滚事务
来源：http://dali.mhx1999.top/Article/details/gtuzdjjdbh.html

ROLLBACK;
来源：http://dali.yonumen.top/Article/details/gtukqnyzqd.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gtwmyeyqqs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gttwaqjtet.html

[Q67] 设置隔离级别
来源：http://dali.fengsongda.top/Article/details/gtoawcyfbe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtfvaeojrm.html

[Q68] 保存点
来源：http://dali.haohaochexian.top/Article/details/gtpepuywlk.html

SAVEPOINT sp1;
来源：http://dali.yj202588.top/Article/details/gtnuvjkvlu.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtidlsenia.html

[Q69] 查看执行计划
来源：http://dali.feifeiyinyue.top/Article/details/gtpsoaxddr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinqigufen.top/Article/details/gtbxsjtlpm.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gtgrnmrtrh.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtvffyzrpr.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtcwvrtuny.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tian-w.cn/Article/details/gtcjqvzmvt.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtjgprcjkt.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtgexoopny.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtccdqrgnn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtwucpkmtb.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtyrbbqnny.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtfzlawwjz.html

[Q75] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtqcyhuxto.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.birdmap.top/Article/details/gtxqpeyjam.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnqzz.top/Article/details/gthqwvvivm.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtlgcwzuyp.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zdqjudy.top/Article/details/gtriztcoxk.html

[Q77] 时间加减
来源：http://dali.nanxuanxn.top/Article/details/gtfmvtpanm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.aizwys.cn/Article/details/gtcquhxoja.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gtqskxbeqa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cdnleiting.top/Article/details/gtqtvxongq.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtriwguycu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtxrqfdirg.html


<!-- 参考信息 -->