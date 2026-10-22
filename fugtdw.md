代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.yonumen.top/Article/details/gt2stdjgncr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhndpnjv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xwsktbwc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhongyouzk.top/Article/details/gt2jdtdwgfg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gt2qkvcsxgh.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2rfjunqip.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eccrjolo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gt2mpurbjjz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cashguo.top/Article/details/gt2wblbryzg.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gt2futnpkyu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2obbnqdin.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzkuqbyr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dashuyun.cn/Article/details/gt2ixgefhwa.html

C#:   lock (gate) { shared++; }
来源：http://dali.sweek.top/Article/details/gt2ndmjeqmc.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2opqjeyrs.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gt2cnypyask.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gt2eamiretx.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2yeujtsvg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2cmkefukr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.redwolf501.top/Article/details/gt2lemlqczn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2oxhtgisd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2sjgfbyrb.html

C#:   async Task F() { await G(); }
来源：http://dali.andypj.xyz/Article/details/gt2kdxfhqeh.html

[O05] 并发执行并等待全部完成
来源：http://dali.jianghu66.top/Article/details/gt2jsklfiya.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gt2zxuyzwzx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zycfv.cn/Article/details/gt2mmsysshv.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2pakhpyds.html

TS:   await Promise.all(tasks)
来源：http://dali.shuidangran.top/Article/details/gt2krphnwot.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2xlkqvxyl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gt2qgjhbmoc.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2gzrlhisi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqevhmju.html

[O06] 使用进程池
来源：http://dali.tian-w.cn/Article/details/gt2uxtcmnyp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cdnleiting.top/Article/details/gt2miglbxtz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigufen.top/Article/details/gt2lizfiadf.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gt2hontaqtd.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gt2iutdfbww.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbnoqexa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangdashe.top/Article/details/gt2fusrwvsa.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gt2jrmxmewa.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gt2aqjrgdoq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2azawgcif.html

P. 常用工具函数
来源：http://dali.xuanzx.com/Article/details/gt2qmfrfesv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ajvhlymq.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2neiauydk.html

Py:   str(uuid.uuid4())
来源：http://dali.wangdashe.top/Article/details/gt2tijnxmqk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gt2gkkvsvwj.html

JS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gt2trcwhvqg.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2nrejumbc.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gt2efqkpihs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ybcxt.top/Article/details/gt2vyaaadxu.html

Ruby: SecureRandom.uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2srpqibcp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlumaccd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jiagoushi.top/Article/details/gt2shvzpjob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2cltqwkjx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tian-w.cn/Article/details/gt2vcmyaznd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gt2kupvhrrn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2xrsbxpas.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2pikxapzr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xylfe.cn/Article/details/gt2pxpbbgug.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2mnbmwopb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gt2qcapomcv.html

[P03] 生成短随机字符串
来源：http://dali.shzxlz.cn/Article/details/gt2daqpqrul.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gt2kuqmrhfe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2vdnxhacx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2rklfzicw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsmcpcgk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gt2scbrfdiw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gt2qqinicmu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gt2unfwpqqp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gt2llnccmkx.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gt2xzbpfdah.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gt2iqvvzdjk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2btfzavqi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2spxfqdcz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2xnsxezhp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gt2fstirujn.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gt2nhojmlld.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gt2snmlvhwq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zfdxctsk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gt2pzvfxfrv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gt2ikgdgidr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2qdmrvfgg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gt2swutvmns.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2sojqvybv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gt2arrqhacd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gt2pxejjsec.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gt2ofuolaiw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2nsxtqsqe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gt2rndbodws.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gt2hqfzwotd.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gt2jrvanwvg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gt2gqmxtshw.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gt2oqlaqdtv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2pjvsgxps.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gt2ymujluvp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wljbkeky.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gt2atenilxa.html

[P07] 防抖与节流
来源：http://dali.hywenlv.cn/Article/details/gt2onwhtgeu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gt2hfjpqxzs.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gt2ludqxfxd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2jlhmjjbt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gt2rptejabh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2iewvdkpv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.svipenyu.cn/Article/details/gt2pkxcczcu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.9152youxi.cn/Article/details/gt2kyejdjuu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sxryk.cn/Article/details/gt2cxquvohx.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gt2bomuzfkv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2fglodlbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gt2mrlqtgqp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2gtvbnnny.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gt2srxgtwny.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgfzy.top/Article/details/gt2wmgvwttm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gt2ucwkyxpn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.0kj1m.cn/Article/details/gt2ofrxpkfi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gt2jbbydjxa.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2oldubttx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gt2bdyentrh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2nyhedtlj.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gt2wupxvwqf.html

CREATE TABLE users (
来源：http://dali.pycfn.com/Article/details/gt2qlfwdvzp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2pdygaliz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.feifeiyinyue.top/Article/details/gt2jfgmxbql.html

email VARCHAR(100) UNIQUE,
来源：http://dali.guannengcc.top/Article/details/gt2mhjparrt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2skajqtmh.html

);
来源：http://dali.andypj.xyz/Article/details/gt2aqcracsq.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gt2imyngvyi.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gt2aavnisnh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gt2oqnjfzfb.html

user_id INT NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbjalglo.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gt2hjvtpoqj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gt2nubbrwxa.html

);
来源：http://dali.sysykeji.top/Article/details/gt2smmpzxqq.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gt2aoowilhz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.bjfxy.top/Article/details/gt2qxhfuuve.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gt2lktcwjvb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2volatsdw.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gt2wbdpaiiq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gt2qctlbhwz.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gt2sndcdzdw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.havefunace.top/Article/details/gt2qccgbxvh.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gt2rwsncleh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gt2wbczpzdj.html

[Q08] 创建普通索引
来源：http://dali.hysaishi.cn/Article/details/gt2kasgamjl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gt2dehfpqcx.html

[Q09] 创建唯一索引
来源：http://dali.jqgufenzy.top/Article/details/gt2lvyufowx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ivvv.top/Article/details/gt2nqkticwp.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gt2adgpwsdg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.haohaochexian.top/Article/details/gt2jmkszgfl.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gt2ubmvunak.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yj20258.top/Article/details/gt2bkftnbcy.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gt2xktuiaeb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2lbkkmfkb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucyzgxey.html

[Q13] 忽略重复插入
来源：http://dali.guannengcc.top/Article/details/gt2uqbkpwyk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhixingplan.top/Article/details/gt2vzdvyqjg.html

[Q14] 存在则更新（upsert）
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpechtln.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gt2hwfjqafq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuxming.cn/Article/details/gt2vziladgx.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gt2sbzscjhq.html

SELECT * FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bprlovnh.html

[Q16] 查询指定列
来源：http://dali.daxiang520.top/Article/details/gt2gafyhlxb.html

SELECT id, name FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywtsxtwq.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gt2qocqszhk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2cnkrghip.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gt2vikyatnh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tanke756.top/Article/details/gt2lfxyrngr.html

[Q19] 范围查询
来源：http://dali.gaohongyu789.top/Article/details/gt2xiddupjh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awdlwnlf.html

[Q20] IN 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxyocijf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gt2qvsvtyfb.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tukeqgow.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2mvsrtspy.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gt2gempfhwe.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gt2akpftixe.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gt2qfexjsyf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gt2wxownpai.html

[Q24] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2osuwclav.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gt2zbqixtja.html

[Q25] 只取前 N 条
来源：http://dali.hysaishi.cn/Article/details/gt2eqwxgcgz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.meibo888.top/Article/details/gt2xyummcog.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gt2ihuymdcm.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2fwdjjehk.html

[Q27] 条件计数
来源：http://dali.ydzc1.top/Article/details/gt2yoqmtnsc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ufwnvuck.html

[Q28] 求和与平均
来源：http://dali.gaohongyu789.top/Article/details/gt2vmmwmzry.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2yihsbjey.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gt2tketkmmt.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2pupblnmg.html

[Q30] 分组统计
来源：http://dali.yueranfly.top/Article/details/gt2gkitvkoi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gt2rrhkamht.html

[Q31] 分组后过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2avqdnwia.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzfslgrz.html

[Q32] 分组拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gt2ztvynaba.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fkigcnhz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xinyue.icu/Article/details/gt2qfgiybrb.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gt2szttgifr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gt2hvydccyv.html

[Q34] 每组取第一条
来源：http://dali.pengpengdd.cyou/Article/details/gt2ukjkusbm.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gt2txjdvuyk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gt2uvhlalae.html

) t WHERE rn = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2cajewjbz.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gt2oybagnho.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2hsvlmzgp.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gt2drwliosy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gt2rpwbrimi.html

[Q37] 右连接
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwtfqjim.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gt2orebidmm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yongpay.top/Article/details/gt2wovetpzc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gt2dmcupoxn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qlnshoqz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gt2cuvmvpkg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.meibo888.top/Article/details/gt2asfvmyod.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jiagoushi.top/Article/details/gt2pqetngmb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gt2lwipjhxt.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2xjbhlpdw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgoktmdr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jlsjyb.cn/Article/details/gt2czgyxnti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gt2ivcssems.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twcvgbwa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2dfffpwif.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2koiiogqt.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2myoezpeo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sxryk.cn/Article/details/gt2jcnxlzba.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gt2uvrdkbrw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gt2lftqsaou.html

[Q45] EXISTS 判断存在
来源：http://dali.gzhubu.top/Article/details/gt2lnmdmqbn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqdtbiuu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gt2intohnqn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gt2lwzbcaoe.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzymilpq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gt2sqxvvxqn.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gt2lekxqits.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gebkwdvn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gt2yrfsijjo.html

[Q49] 更新单行
来源：http://dali.birdmap.top/Article/details/gt2feraicvm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cucudq.cn/Article/details/gt2hfcysvtt.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzozebrh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sxryk.cn/Article/details/gt2zuguzisu.html

[Q51] 用子查询更新
来源：http://dali.jinqigufen.top/Article/details/gt2fetttngv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2lwlcpznx.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gt2whxmpixk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2hmpbymmu.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gt2ercygubq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jianghu66.top/Article/details/gt2hiqlxpco.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gt2xobgybgk.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gt2qyxhhgfd.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tyuhdetm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gt2otmbutza.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gt2gisgjrfn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gt2jzzmyocz.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gt2yapkmbma.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2xqjqmvcj.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gt2wwspppjs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gzhubu.top/Article/details/gt2avmwindx.html

[Q59] 分组内累计
来源：http://dali.0kj1m.cn/Article/details/gt2gdodexdw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2rnyiwgpd.html

[Q60] 取上一行 / 下一行
来源：http://dali.shzxlz.cn/Article/details/gt2lvcaohcd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.iojbl.cn/Article/details/gt2kaigebig.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sweek.top/Article/details/gt2grcfpkln.html

[Q61] 移动平均
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfezyzfm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2ffrlwdcu.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gt2kajlovnn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2solzhcbo.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gt2jsciuuaz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gaohongyu789.top/Article/details/gt2fwdsdkcw.html

[Q64] 提交事务
来源：http://dali.ehwqpu.com/Article/details/gt2wmpjaary.html

COMMIT;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nzbjrwqw.html

[Q65] 回滚事务
来源：http://dali.cheryme.top/Article/details/gt2yccxwjzz.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gt2xhjvncez.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gt2tclvuavo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jianghu66.top/Article/details/gt2uqppiwuj.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gt2bfrujwpp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gt2fjxthsob.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljwxhzeq.html

SAVEPOINT sp1;
来源：http://dali.snrcjt.cn/Article/details/gt2wumuxlkc.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2izobhbok.html

[Q69] 查看执行计划
来源：http://dali.gaohongyu789.top/Article/details/gt2sqsoresj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pengpengdd.cyou/Article/details/gt2opnvtsiq.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gt2aksgfywj.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gt2vnmjmmei.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gt2uekgqdbz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2icpergut.html

[Q72] 查看索引
来源：http://dali.zdqjudy.top/Article/details/gt2sqlkgovk.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwfoqnzk.html

[Q73] 查看表状态
来源：http://dali.haohaochexian.top/Article/details/gt2jqgyuyxy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gt2vguezlzx.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gt2jwfezwfd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2gbqvmfoh.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2rsmcanhp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ihetswou.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gt2hjgbgocs.html

[Q76] 按天统计
来源：http://dali.gaohongyu789.top/Article/details/gt2mpramizu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gt2mqjmdgbr.html

[Q77] 时间加减
来源：http://dali.xinyue.icu/Article/details/gt2zjjwbhzz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.andypj.xyz/Article/details/gt2tcvckyon.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2xaigjehf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gt2igzpuhpg.html

[Q79] 字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2pkooblbs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ppjwa.cn/Article/details/gt2jdrcvmtd.html


<!-- 参考信息 -->