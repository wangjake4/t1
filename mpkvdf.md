代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gthtnwiueo.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtqtggmokf.html

Ruby: Thread.new { f }
来源：http://dali.gzhubu.top/Article/details/gtpsavtjzl.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtcwgvzfzv.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gtrbjapjrb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258888.top/Article/details/gtaommzliu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fengsongda.top/Article/details/gtrsnejhqb.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtrsfqjfdv.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtbexemdie.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkaxegld.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtxjwzoghx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.andypj.xyz/Article/details/gtgsjvxulh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gtsefakqyc.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtnebcrcab.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gtrighbsmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.chenjidiqi.icu/Article/details/gtagrxrxpg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtwdiksjmr.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtdrqnisvt.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gtgahjbjzd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gthbympdjg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbbxxvxb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtpvrseclx.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gtbpqqlajo.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtvvfxwwcx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.svipenyu.cn/Article/details/gtnrcmezxj.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtqtkwpowe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtivcjbwyp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.andypj.xyz/Article/details/gtxhxjusdn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygilhxhe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shzxlz.cn/Article/details/gtnwnibcdr.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtwyngupoz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorxwapvb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gtscjtqfmp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gtbkoncppp.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtlqgyjvex.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtymgmezxi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cqqwz.cn/Article/details/gtrnxqincd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrxaswge.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtrbcmvnsk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gtfelnpcdx.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtjzalcarv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtszhlidox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.bjfxy.top/Article/details/gtbwhjvdua.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gtlkpolpvu.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtlpaduszx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gtkugixddy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtreyohfnr.html

Ruby: // fork 块
来源：http://dali.zhixingplan.top/Article/details/gtojgkjvkm.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtxswwmwvq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrdaqhcpf.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtuthcswim.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtclozqcsn.html

[P01] 生成 UUID
来源：http://dali.yonumen.top/Article/details/gtnenwwgqz.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtkybenpwp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jianghu66.top/Article/details/gtgnrnzpvi.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtzwjzduut.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtmecqofid.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gtqimlckha.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gtyrkebipt.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gteshexgch.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gtmtcvblsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hfpthk.cn/Article/details/gtrrocbljx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtwzmjemxh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gtnwfaybhf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtjctrbroh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gttikznekq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.meibo888.top/Article/details/gtunxzuwtr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtcwwvzuoi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtiwhnvhwq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gtjfzynrmp.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gtrudcvdxb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtunbbunfw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.haohaochexian.top/Article/details/gtgtzpvfga.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dianchejie.cn/Article/details/gtqxzfuwgm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtmtgwdrkd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj202588.top/Article/details/gtsmpvphgn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtgodxflay.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtnjwtujav.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtxycdkpua.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gtpwkveyuf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtuevljhax.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtymditdzo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtdptvrdpb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gtpxhexlbw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gttqbsuacg.html

Go:   len(arr);  len(m)
来源：http://dali.mhx1999.top/Article/details/gtstbztirw.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gttnhbnitl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gtcmrqthcr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gthsmwkois.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jianghu66.top/Article/details/gtpugokotc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gtdzmsfnmo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tianlin.xyz/Article/details/gtkbunpqqt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtojivybsy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtjjacmbvq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtnxncmsig.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtpmdnndqx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtcxcrtiqr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtpuaahlut.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtpbkmxpzz.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtxdtxjwxp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gzhubu.top/Article/details/gtziayigrz.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gtlhzbtfvt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtskxgulea.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtoutzpsum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cdnleiting.top/Article/details/gtcddofbxi.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gthwodcecp.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtjqlpqsrp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtlfkjnwho.html

PHP:  // 手写时间戳比较
来源：http://dali.daria6918.cn/Article/details/gtfjymwkrj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtdgucifru.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdysjjfuk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gtwpzfccvr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtiprbwtyk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtmqumvovs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtotutwrmt.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gtfkfkbqtt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtgshjkjin.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gtvdxqifph.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cheryme.top/Article/details/gtbqmeivrw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cheryme.top/Article/details/gtwmxcnzsg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtmxmgcwaw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yueranfly.top/Article/details/gtkwqybivv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gtxfjjumwp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtzmrecjrv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgfnbcuwf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtztetvsst.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrcaqsvsy.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtghkaazgz.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtgrkiimxk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtizslxtaf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtjfeypwoh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtzhncbebv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hysaishi.cn/Article/details/gtcjilutlu.html

);
来源：http://dali.c1oappe.top/Article/details/gtojqfdbpy.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtvvbtxiin.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtccknbppe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.316326.xyz/Article/details/gtdlzxrelz.html

user_id INT NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtrhyxrwww.html

amount DECIMAL(10, 2),
来源：http://dali.ydzc1.top/Article/details/gtjcueekpy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaislhtj.html

);
来源：http://dali.andypj.xyz/Article/details/gtlqrjohxr.html

[Q03] 增加列
来源：http://dali.cqqwz.cn/Article/details/gtgjyuadal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.vqdsnc.cn/Article/details/gtlxvhjfwv.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtgzdbioqa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtxfbutepf.html

[Q05] 重命名列
来源：http://dali.mhx1999.top/Article/details/gtzcgizjmy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gtabakboyh.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtiaeoqtwj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fengsongda.top/Article/details/gtdcbrvfci.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtuummekvt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nanxuanxn.top/Article/details/gtbqcyzayo.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtxukjwjpo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtadgfaitx.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gthlvksjah.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gttvnidkye.html

[Q10] 插入单行
来源：http://dali.nanxinkj.top/Article/details/gtffqqyevz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtpjvnzscf.html

[Q11] 一次插入多行
来源：http://dali.nanxinkj.top/Article/details/gtowlojucs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtynqzejsd.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtxjufuyzh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hongshengwenyu.top/Article/details/gtcazqejym.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dashuyun.cn/Article/details/gtdxnlscka.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gtktxtjswo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gtcozpfrwy.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gthtgngefb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hfpthk.cn/Article/details/gtcrfzjezz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhongyouzk.top/Article/details/gtnuigomld.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gtvufaugpv.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfgukrcxf.html

[Q16] 查询指定列
来源：http://dali.ydzc1.top/Article/details/gttkihllxh.html

SELECT id, name FROM users;
来源：http://dali.iojbl.cn/Article/details/gtpzdqdvnm.html

[Q17] 条件查询
来源：http://dali.redwolf501.top/Article/details/gtmjfrkiyv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtpoczajjw.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtjiecqqlx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jinqigufen.top/Article/details/gticqmyzwr.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtyehgtwgl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gtmlgiuzvc.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtihhknnkj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtuqunjucg.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtzfjtnpzb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.kuanghao11.cn/Article/details/gtbvhfwxcd.html

[Q22] 排序
来源：http://dali.haohaochexian.top/Article/details/gtnnpepdsc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gtgxyzjvwb.html

[Q23] 分页
来源：http://dali.iojbl.cn/Article/details/gtslbflgzx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ydzc1.top/Article/details/gtoqpaoebo.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtasxrabvv.html

SELECT DISTINCT city FROM users;
来源：http://dali.cashguo.top/Article/details/gtcgvdvtve.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtujqcnnlz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jianghu66.top/Article/details/gtwxdiqfpj.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhapcaqg.html

SELECT COUNT(*) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtrvhmdkqd.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtirhthzzy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gthyzsztpu.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtdqayufta.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtiajhxqyw.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gtzftmxhls.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtbxyqvkog.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtcplbshks.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpgarodm.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtbwitfeyt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.havefunace.top/Article/details/gtpgvbaksc.html

[Q32] 分组拼接字符串
来源：http://dali.meibo888.top/Article/details/gtlgtnaaap.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sysykeji.top/Article/details/gtreyktyxe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.dianchejie.cn/Article/details/gtnwlowsdx.html

[Q33] 多列分组
来源：http://dali.yangfankeji.com/Article/details/gtxzxdlbdm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gtkjhzppxb.html

[Q34] 每组取第一条
来源：http://dali.zhengqikj.top/Article/details/gtolppiwle.html

SELECT * FROM (
来源：http://dali.yonumen.top/Article/details/gtocpxgilw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtqyrfweik.html

) t WHERE rn = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekjyqfha.html

[Q35] 内连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvccmipew.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtlossmnea.html

[Q36] 左连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtwstbsrdc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtbszaewfw.html

[Q37] 右连接
来源：http://dali.yanxiufei.cn/Article/details/gtzoosgqrs.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sysykeji.top/Article/details/gtunmnjuyo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtxvqushyb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258888.top/Article/details/gtcbrxvbio.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gtdaldqzvd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gtbcjkjhob.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtsxnzpnfp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sxryk.cn/Article/details/gtebycdqsf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zycfv.cn/Article/details/gtijuqljyh.html

[Q41] 多表连接
来源：http://dali.wangshuangyany.cn/Article/details/gtpwpffgfb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gttsuaeume.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tanke756.top/Article/details/gtujbzgyhh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnxiangtu.top/Article/details/gtupgxrsjz.html

[Q42] 连接条件附加过滤
来源：http://dali.jlsjyb.cn/Article/details/gtqwtuiarp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtsybzozwc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cdnleiting.top/Article/details/gtunhbsewa.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtpkvkucqw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cashguo.top/Article/details/gtyxkhotxw.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtvrkewgpg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtibqotdxx.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtawybabos.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtgmaqzplq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtaxjkzzlq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hysaishi.cn/Article/details/gtcuyymrzy.html

[Q47] 与平均值比较
来源：http://dali.jianghu66.top/Article/details/gthwzhdgrc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtxiisioif.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtkzjbyyhr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtovzrsdyt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.andypj.xyz/Article/details/gtjohapzof.html

[Q49] 更新单行
来源：http://dali.hnqzz.top/Article/details/gtanbilzpz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtgdmodufl.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtbpppvjjs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.mhx1999.top/Article/details/gtmbjqagkf.html

[Q51] 用子查询更新
来源：http://dali.wangshuangyany.cn/Article/details/gtokvdfner.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnqzz.top/Article/details/gtekezdpcg.html

[Q52] 删除指定行
来源：http://dali.zycfv.cn/Article/details/gtsrjxfkzl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gttpglllqs.html

[Q53] 按条件删除
来源：http://dali.haohaochexian.top/Article/details/gtwehgshdn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtwjisdeqr.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtijbxrilr.html

TRUNCATE TABLE logs;
来源：http://dali.snrcjt.cn/Article/details/gthplxlesm.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtfgtyeipb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtzsbqvhze.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtosjeekir.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ehwqpu.com/Article/details/gtxdpthzot.html

[Q57] 行号
来源：http://dali.meibo888.top/Article/details/gtxmmwpbmc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtvhjkjkyc.html

[Q58] 累计求和
来源：http://dali.bjfxy.top/Article/details/gtksfmavra.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtybnuhgzs.html

[Q59] 分组内累计
来源：http://dali.birdmap.top/Article/details/gtndnrzjas.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtegrzgzao.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigufen.top/Article/details/gtyiblhues.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gtxxzcjshq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtnucraena.html

[Q61] 移动平均
来源：http://dali.chenlongwang.top/Article/details/gtpbbgnrna.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtiuttbkwj.html

[Q62] 分组占比
来源：http://dali.dashuyun.cn/Article/details/gtlbdpicrd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtwacqfgxd.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtuqdkwbgs.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtfmkailvc.html

[Q64] 提交事务
来源：http://dali.shangyingyoupin.top/Article/details/gtxtqgybhb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gtoxmqlrqo.html

[Q65] 回滚事务
来源：http://dali.jyoumei.cn/Article/details/gtqngnkyyz.html

ROLLBACK;
来源：http://dali.daxiang520.top/Article/details/gtokxckbna.html

[Q66] 行锁查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulzoyjzl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhiwuduotai.top/Article/details/gtminnfbhy.html

[Q67] 设置隔离级别
来源：http://dali.zhongyouzk.top/Article/details/gtuponqeaq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtwwdvcjce.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gtvqtaiool.html

SAVEPOINT sp1;
来源：http://dali.yuanzhike.top/Article/details/gtgmqgemnz.html

ROLLBACK TO sp1;
来源：http://dali.chenzaomai.com/Article/details/gttaubjomj.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtmahjdstv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xylfe.cn/Article/details/gtgesubwwn.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gtztwoauxd.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gttkhhpzoz.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gteicunkfa.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jyoumei.cn/Article/details/gtuddlzjps.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtaifizxnc.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtldhhwewl.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gtdtpmzeqo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ybcxt.top/Article/details/gtvqytnaez.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gtwedrilfm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.316326.xyz/Article/details/gtvhrqnena.html

[Q75] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gttbhjjaof.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtafytbxso.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtolztignv.html


<!-- 参考信息 -->