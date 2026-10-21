代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtscldctgp.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtormmxjjk.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtcrnnadez.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xziqi.cn/Article/details/gttejdythw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtrbphsjfr.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtidmvggbw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuvjmevkw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gtzwylvpog.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gtcxejtozz.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gteghacslu.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtkrdwzkpr.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gthevauusq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gtufogyavh.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gtlemaljkk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtvztmhlix.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gtelhgbwcx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtyyimygvi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gthtpeqlux.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtwhvulrgq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtivlpllgj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gtbszabpbi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtmxiepofd.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjhgpbwn.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtrldvlwqg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gtbvtsfthl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.iojbl.cn/Article/details/gtcwrxtevv.html

Ruby: threads.map(&:join)
来源：http://dali.cucudq.cn/Article/details/gtmxdjucyp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yanxiufei.cn/Article/details/gtqzqownfm.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtcbbgnbfo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gtceyrcenv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.0kj1m.cn/Article/details/gtmvxhrtpy.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gtrhounzfq.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtskfssjrl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtjpfepsap.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtspgzlvcm.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtromppnvu.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtwemrjgqa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlnbzfjae.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtclssdsvj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpfvknrzb.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtbbbuvbwz.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtvzkbvyrg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gtttbfzzvj.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtqhtrdkpi.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtyeetjhfd.html

Java: UUID.randomUUID().toString()
来源：http://dali.cheryme.top/Article/details/gtwipvvgvq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtknblouon.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtojsfjigt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gttnfhzjpe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.smart0.xyz/Article/details/gtvwkscgkk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtcetotlcm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtnurtiu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xinyue.icu/Article/details/gtjddhsthd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtdqjoskyp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gthasaqhre.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gtclpyrflt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhnjcdia.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtwnynwbko.html

[P03] 生成短随机字符串
来源：http://dali.gaohongyu789.top/Article/details/gtryxbjelf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtnjtcfydb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtuvexyawo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtirhoxopr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyovkmqp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gtohtnaevg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtcfnczghz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gtiwoymfmq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gtmuworsdd.html

[P04] 求长度
来源：http://dali.smart0.xyz/Article/details/gtrmvzcerv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtcmzegojs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtipoduevd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gotoacloud.top/Article/details/gtxftzjlwc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtacqsiixu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtdrczbivh.html

Go:   len(arr);  len(m)
来源：http://dali.smart0.xyz/Article/details/gtlngazhsn.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtvlthdyur.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jiagoushi.top/Article/details/gtpagqgvvv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtehdtdqwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shuidangran.top/Article/details/gtkyfhcoht.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.0kj1m.cn/Article/details/gthydsepqy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gtvsysenqf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtvvvlhvnw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtounvqqym.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yuxming.cn/Article/details/gtpdktbrst.html

Ruby: a == b
来源：http://dali.cucudq.cn/Article/details/gtzfrkgojt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtblgrtvzt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtblrobwla.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxuanxn.top/Article/details/gtnbikhtjl.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwggbvmay.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gttiwlskwv.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtekkpzcko.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtsqomrrwt.html

Go:   if x == nil {}
来源：http://dali.ydzc1.top/Article/details/gtvwdzagjf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtaoolwbyf.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtsdktfgfp.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtoglxkfug.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmirgqec.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gttgwidygq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtfghipzwk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtvggkhbsr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtdztuixgy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gthkgiebxp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtojchdnbw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cucudq.cn/Article/details/gtgnyttptr.html

[P08] 处理浮点精度问题
来源：http://dali.nanxinkj.top/Article/details/gtnpdourrh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gtevarggrm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gttjeksnyn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtniukqwxt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtcpavsyda.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shangyingyoupin.top/Article/details/gtetwetplh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ehwqpu.com/Article/details/gtnjcxoapz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gtchkutygx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gthbzvofop.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdltyimuq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtohmholhd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtalsuzmnb.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmgevuiq.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtsexyqmul.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtrwylyhay.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtgwmruigw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtirbjrdah.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtimhghwat.html

);
来源：http://dali.xziqi.cn/Article/details/gtdpozzyic.html

[Q02] 创建带外键的表
来源：http://dali.9152youxi.cn/Article/details/gtgwxrhoni.html

CREATE TABLE orders (
来源：http://dali.yueranfly.top/Article/details/gtyjubuwnp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtzczaxxfn.html

user_id INT NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtinpduvzj.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtjefrdghf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gttoclkydn.html

);
来源：http://dali.cqqwz.cn/Article/details/gtetgqccfi.html

[Q03] 增加列
来源：http://dali.aizwys.cn/Article/details/gtuwtvtkgl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gtumsauofk.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtvqaaefhz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gthffozrfo.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtpisqnxrh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtyeykayzj.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gtlzuprzjl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aizwys.cn/Article/details/gtuykzwfuh.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gtkppaiecd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gtqswnerug.html

[Q08] 创建普通索引
来源：http://dali.xziqi.cn/Article/details/gtmlbnvfux.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtrkbspzgn.html

[Q09] 创建唯一索引
来源：http://dali.shzxlz.cn/Article/details/gtgrmdjgsz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtgcjxrldf.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtsdgypyei.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.316326.xyz/Article/details/gtkpkodlws.html

[Q11] 一次插入多行
来源：http://dali.hfpthk.cn/Article/details/gtewhyafhz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtvglurvxq.html

[Q12] 插入后取自增 ID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzopouccq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zycfv.cn/Article/details/gtgsrnpezv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtdfdjnkxf.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkodbrhs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtpioyskzv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtmvcxfcvz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtdzdforjf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tian-w.cn/Article/details/gtagfygbxb.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gtgjyuahba.html

SELECT * FROM users;
来源：http://dali.yongpay.top/Article/details/gtclefkadl.html

[Q16] 查询指定列
来源：http://dali.ehwqpu.com/Article/details/gtmtnkvkyp.html

SELECT id, name FROM users;
来源：http://dali.nwbrower.top/Article/details/gtedcxrfen.html

[Q17] 条件查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxtgmhky.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gtlryfmftf.html

[Q18] 模糊匹配
来源：http://dali.yangfankeji.com/Article/details/gtxkyrepht.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgufenzy.top/Article/details/gtforbnlns.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtyskzzidg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtollroyui.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtcluqmdck.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ivvv.top/Article/details/gtociguavd.html

[Q21] 空值判断
来源：http://dali.9152youxi.cn/Article/details/gtspciisfb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhixingplan.top/Article/details/gtvtgdwcit.html

[Q22] 排序
来源：http://dali.zhiwuduotai.top/Article/details/gtxxrenwbn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gtbtxtfdqq.html

[Q23] 分页
来源：http://dali.yongpay.top/Article/details/gtvmwiqwpo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hywenlv.cn/Article/details/gtvghavsvv.html

[Q24] 去重
来源：http://dali.kuanghao11.cn/Article/details/gtdjzmhyod.html

SELECT DISTINCT city FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtbdhvrfsz.html

[Q25] 只取前 N 条
来源：http://dali.guowangkeji.top/Article/details/gtzqbuizac.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtfisaqoli.html

[Q26] 计数
来源：http://dali.pengpengdd.cyou/Article/details/gttqacpaic.html

SELECT COUNT(*) FROM users;
来源：http://dali.pycfn.com/Article/details/gthqxchhsz.html

[Q27] 条件计数
来源：http://dali.xinyue.icu/Article/details/gtcscxbtvf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xziqi.cn/Article/details/gtxlbupzrp.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtwhknlqod.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtvmqvhdiw.html

[Q29] 最大最小值
来源：http://dali.feifeiyinyue.top/Article/details/gtdfjmwhkl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnoxpvsic.html

[Q30] 分组统计
来源：http://dali.zhengqikj.top/Article/details/gtulpspeec.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtlqwnpigt.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtyhujbsei.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daxiang520.top/Article/details/gtlhfohbwp.html

[Q32] 分组拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtsjafdgda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtwgqlwodi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtyneeompj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gtvdzglusp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aibaodan.cn/Article/details/gtcpwczcoa.html

[Q34] 每组取第一条
来源：http://dali.iojbl.cn/Article/details/gtmjtnnvyp.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gtpsvmsbte.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gtlcapkouj.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtrdmxwjxs.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtietryljs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtsybqfwlp.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtytxiblvk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtfpcynoto.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtyonfwoih.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtwzhddkiq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gtlcrxxdzf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtxtmkdeqo.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtbicdheih.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ehwqpu.com/Article/details/gteuykhhsq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jiagoushi.top/Article/details/gtghffhpww.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtefkxlyvk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gaohongyu789.top/Article/details/gtmcdcrrlk.html

[Q41] 多表连接
来源：http://dali.daxiang520.top/Article/details/gtmzaccggu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gotoacloud.top/Article/details/gtsolbmoeu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sxryk.cn/Article/details/gtycgqdrtm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtzttojvor.html

[Q42] 连接条件附加过滤
来源：http://dali.sweek.top/Article/details/gtxxzjhknx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.bjfxy.top/Article/details/gtwjdkntbe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ivvv.top/Article/details/gtusscqflv.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gtnlsviaee.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqokibfn.html

[Q44] IN 子查询
来源：http://dali.xylfe.cn/Article/details/gtvfbprojj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yongpay.top/Article/details/gtcfcokodp.html

[Q45] EXISTS 判断存在
来源：http://dali.hnqzz.top/Article/details/gtrlxpfspk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtpuewrjeb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cdnleiting.top/Article/details/gtjzliwgrg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gthubxzkfs.html

[Q47] 与平均值比较
来源：http://dali.cashguo.top/Article/details/gtjlunpawp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnrxwzde.html

[Q48] CTE 公用表表达式
来源：http://dali.chenlongwang.top/Article/details/gtvpekoqqj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwdmojoe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgttdutvf.html

[Q49] 更新单行
来源：http://dali.dashuyun.cn/Article/details/gtdyicbjyz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtlkhpukdo.html

[Q50] 批量更新
来源：http://dali.hammf.cn/Article/details/gthqtutgbj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnauugxdh.html

[Q51] 用子查询更新
来源：http://dali.mhx1999.top/Article/details/gtjeqnagux.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttmjjapoo.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gtlbbgnhmy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtftoyiwhs.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gtihnqyaxj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbzsxjof.html

[Q54] 清空表
来源：http://dali.xuetiantiany.cn/Article/details/gtpsnrhsub.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtilkwnsdo.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtqhwzousy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hammf.cn/Article/details/gtccdscvkb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtnjlxatus.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtusqrvkrw.html

[Q57] 行号
来源：http://dali.yj20258888.top/Article/details/gtbpeatlzn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtwzccrmjj.html

[Q58] 累计求和
来源：http://dali.nanxuanxn.top/Article/details/gtezazkkjr.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gttlqvwbpu.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gttvnzconf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtkniweltd.html

[Q60] 取上一行 / 下一行
来源：http://dali.c1oappe.top/Article/details/gtzgcaofhw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtfcwsyqms.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtzpuvlafa.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gttumftobj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtopctmzoi.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtfejoefle.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtnqecwcfw.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gttnwhnbws.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtpimwsuae.html

[Q64] 提交事务
来源：http://dali.wangshuangyany.cn/Article/details/gtkopqpvvd.html

COMMIT;
来源：http://dali.shuidangran.top/Article/details/gtczqxmgnp.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtkfhamgxw.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcdiqlkl.html

[Q66] 行锁查询
来源：http://dali.pengpengdd.cyou/Article/details/gtbivelblx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gttqbaxexk.html

[Q67] 设置隔离级别
来源：http://dali.yonumen.top/Article/details/gtnmyvjpuw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangshuangyany.cn/Article/details/gtzrovller.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtfzikmjfj.html

SAVEPOINT sp1;
来源：http://dali.sweek.top/Article/details/gtstkwzkpc.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtareiyiqw.html

[Q69] 查看执行计划
来源：http://dali.hongshengwenyu.top/Article/details/gtxugxoefk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gtuuisveim.html

[Q70] 更新统计信息
来源：http://dali.nanxuanxn.top/Article/details/gtjfssvhpf.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gtkvhehxkc.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsgbxwmy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhhqptnq.html

[Q72] 查看索引
来源：http://dali.xinyue.icu/Article/details/gtmhauikty.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqveloful.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtdleleboh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtzaitbakr.html

[Q74] 强制使用索引
来源：http://dali.haohaochexian.top/Article/details/gtapiiuupv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.redwolf501.top/Article/details/gtwlghbejz.html

[Q75] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtnjzqtmes.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtrwxztcng.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhongyouzk.top/Article/details/gttkyahjsu.html

[Q76] 按天统计
来源：http://dali.ivvv.top/Article/details/gtptckmngn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtjjddatvj.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gteiniswts.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtmcjyzrqm.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtxrurkcqt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ehwqpu.com/Article/details/gtbzzdjmkr.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gteomicrgo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gtkacbuetc.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtfqypwtid.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtvjwzlyqs.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gttfphyimw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zycfv.cn/Article/details/gtsgojbxxk.html


<!-- 参考信息 -->