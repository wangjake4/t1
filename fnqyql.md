代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2vgabeyzt.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2hhgrkfou.html

Ruby: Thread.new { f }
来源：http://dali.guowangkeji.top/Article/details/gt2mscffbhm.html

C#:   Task.Run(() => F());
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccfbmqkb.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2unepfbdi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2hpzjwozr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daxiang520.top/Article/details/gt2fzazvyzk.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gt2gpaqaoew.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2znqfijcy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2awaiznim.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gt2buiybotl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2gsviyuch.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2wosjkmvy.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gt2zrnamvpz.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gt2xzmnijfk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2owjffzew.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gt2ihjdwwzc.html

TS:   // 同 JS
来源：http://dali.meibo888.top/Article/details/gt2jbbhaohw.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emerpyqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gt2negefuwp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gt2sylgzovf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nzttzfid.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2vqfwrqpg.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gt2pbmwbjuu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gt2dcoqleio.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2bkfwltoz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ytqihwmg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuanzhike.top/Article/details/gt2tiftywgv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gt2jadetwhp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2sccftxcj.html

C#:   async Task F() { await G(); }
来源：http://dali.redwolf501.top/Article/details/gt2blcoixfv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zdqjudy.top/Article/details/gt2ujjjamqi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gt2mypxqgde.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2wujnmlnl.html

JS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gt2hcjakfus.html

TS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gt2dohrarjg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2cwqmfcwy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ydzc1.top/Article/details/gt2apdzxjwi.html

Ruby: threads.map(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2ioadqpti.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.bjfxy.top/Article/details/gt2vzspphqr.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gt2ihveshvc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2rthmdhxt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2wbxogdpk.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2wyjnfxmy.html

TS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2frjjuwcx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gt2dnoydjlh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2voiddohs.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwmknziq.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gt2bozzfhtc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wicrgyuu.html

P. 常用工具函数
来源：http://dali.jinqigfzy.top/Article/details/gt2bxbwspvh.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2dbnepfmu.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gt2onzzbzcb.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2iacpnumr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gt2uhnhbmng.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2glqobmyh.html

TS:   crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gt2hntxjdnj.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2xlwonzmy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnqzz.top/Article/details/gt2knsmceah.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gt2pkdjxesk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gt2xbakdpis.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gt2bmuliiva.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ppjwa.cn/Article/details/gt2ciimiske.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gt2lfzrwbtc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gt2ebrfsrxb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gt2wtzfitvx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2reuxjlqu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gt2cvcevdjv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gt2hpdparrn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gt2puhflgdw.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2jozljohm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gt2plffxoix.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gt2mqhasltz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2aoopsyro.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zdqjudy.top/Article/details/gt2ryawqhxc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gt2tnviimmt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eiucfyim.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gt2adqcaqll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxinkj.top/Article/details/gt2bodqypqm.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gt2swahqcht.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhoulong.xyz/Article/details/gt2mbyvagvw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2dmfikrxb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.bjfxy.top/Article/details/gt2dwoqweiz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2xfgtwkdk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2delrvuvk.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xcxtdgav.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2uznekvga.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.birdmap.top/Article/details/gt2hwszwsod.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gt2pdryxtnj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gt2koamjwjp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gt2exqisdoa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gt2jcslzzbf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gt2gvczcmbi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gt2vpnxsqpk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2embtkikw.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gt2mvsqykgf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gt2aelutwjf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2wkjnabhg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.birdmap.top/Article/details/gt2qxkqvgte.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2iuudspaw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2azdntout.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gt2wadfevnq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gt2rugzhcfy.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gt2fcxoorlz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gt2pwvvznfd.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gt2jmvqewub.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2zkrubinj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gt2osqrxqxj.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gt2kccwlred.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2qwcuzuhz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2hybdzfkk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2byppllde.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgfzy.top/Article/details/gt2mjmzxmoe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2fwcyzabs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gt2qxlpwzbp.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gt2kwokgkux.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2jgtgumxq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.0kj1m.cn/Article/details/gt2aiqaleeu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgufenzy.top/Article/details/gt2ejalpuvd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2jezajfgi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jiagoushi.top/Article/details/gt2qkpetxtg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gt2syohvdcb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gt2pmhqxtfr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gt2jvbifafv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2ublwjhug.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gt2kmnlrcgv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tjooootd.html

[Q01] 创建表
来源：http://dali.pycfn.com/Article/details/gt2ianrhyiu.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gt2ybkkmpeh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2upusiygy.html

name VARCHAR(50) NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gt2xfljidlx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xylfe.cn/Article/details/gt2phsgqhbj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gt2qvvescia.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2jbiuezky.html

[Q02] 创建带外键的表
来源：http://dali.tanke756.top/Article/details/gt2fvosrbkl.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gt2qtlfsxyz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gt2cqkynsnm.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2lzsyyisb.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gt2rbkkivhn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jlsjyb.cn/Article/details/gt2wlcqrfac.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2sqkbnelm.html

[Q03] 增加列
来源：http://dali.zycfv.cn/Article/details/gt2epjczmvl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gt2nazgosxh.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2irtrfiwd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpzjjquo.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gt2xypzeata.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2qxhabxrr.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gt2knybrwgo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gt2iudqcvzr.html

[Q07] 删除表
来源：http://dali.yj20258888.top/Article/details/gt2iwvvicmc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zycfv.cn/Article/details/gt2bwxbyybw.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gt2nivhounf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnqzz.top/Article/details/gt2pxulvzcn.html

[Q09] 创建唯一索引
来源：http://dali.zhengqikj.top/Article/details/gt2gtknpscm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gt2mupknpbe.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gt2bipgnhct.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yongpay.top/Article/details/gt2yintlycm.html

[Q11] 一次插入多行
来源：http://dali.chenzaomai.com/Article/details/gt2zusiwzxq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jalvilbc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxigiea.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2ekckiaoj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gt2xadxiwny.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gt2ooamptqs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2ikewhlss.html

[Q14] 存在则更新（upsert）
来源：http://dali.nanxinkj.top/Article/details/gt2npyvahqn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gt2bsyvzeqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhengqikj.top/Article/details/gt2sdobzmeo.html

[Q15] 查询全部
来源：http://dali.andypj.xyz/Article/details/gt2wpzhishl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyrpcyt.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gt2hggkrxym.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2nrosulkp.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gt2wnpghlfm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cashguo.top/Article/details/gt2cyihozyf.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2uzbexkjy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gt2ndgabozk.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gt2chgqzwbq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fengsongda.top/Article/details/gt2qvgbvmiz.html

[Q20] IN 列表
来源：http://dali.snrcjt.cn/Article/details/gt2fbqqcmia.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2udvnvdwz.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gt2mjcndako.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gt2qpqbdasd.html

[Q22] 排序
来源：http://dali.dianchejie.cn/Article/details/gt2ldkzxomp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsntryuc.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2ahsojhpk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gt2mkidlsyt.html

[Q24] 去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxnmbgfm.html

SELECT DISTINCT city FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2gtnfmjsd.html

[Q25] 只取前 N 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzlnxwbq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gt2opflmrez.html

[Q26] 计数
来源：http://dali.aibaodan.cn/Article/details/gt2kjqilmfd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjrgbimg.html

[Q27] 条件计数
来源：http://dali.svipenyu.cn/Article/details/gt2koaevupn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2tfpxhxnd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gfscglpc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2mnetbvzs.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgxyjfzj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2offjncvq.html

[Q30] 分组统计
来源：http://dali.chenlongwang.top/Article/details/gt2ogimhwfb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2lxvolasq.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gt2yuhizcmf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2xbqxonol.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vhjjojrk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ehwqpu.com/Article/details/gt2qmizwvxk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2zyaznrkp.html

[Q33] 多列分组
来源：http://dali.chenzaomai.com/Article/details/gt2fffnsxeq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daria6918.cn/Article/details/gt2nnoilnjx.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gt2dturdvrd.html

SELECT * FROM (
来源：http://dali.shzxlz.cn/Article/details/gt2gyfnnvlv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jqgufenzy.top/Article/details/gt2fqljoije.html

) t WHERE rn = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2bweurefr.html

[Q35] 内连接
来源：http://dali.snrcjt.cn/Article/details/gt2dnvvbolu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2wotcswvh.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gt2ntehgben.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gt2borhduhe.html

[Q37] 右连接
来源：http://dali.jinqigfzy.top/Article/details/gt2kmvsdhsx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.andypj.xyz/Article/details/gt2xgdubrzv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gt2dioiahuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2trfuucus.html

[Q39] 自连接（查上下级）
来源：http://dali.sxryk.cn/Article/details/gt2xfiomuqs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenzaomai.com/Article/details/gt2nbmzyjtv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gt2wsulffui.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gt2kyqruvqz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gt2jrhzyvfb.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzvpyrrb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gt2mxsxelok.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gt2ssxbigwj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2otxgzgfw.html

[Q42] 连接条件附加过滤
来源：http://dali.gogol.net.cn/Article/details/gt2qvcpgihz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuanzhike.top/Article/details/gt2vwzxjlnr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sufxvd.cn/Article/details/gt2jydsuvcl.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gt2nidjqdtq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gt2xunjrrfa.html

[Q44] IN 子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2ecrpeuhh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gt2lqrfkurc.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gt2nomcwqgm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtkjyzip.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cvscadwo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2jqppdwwf.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gt2qmlmfcuf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mrapsdky.html

[Q48] CTE 公用表表达式
来源：http://dali.mhx1999.top/Article/details/gt2nmlhvdir.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gt2qibocsgn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xinyue.icu/Article/details/gt2kmulmrbv.html

[Q49] 更新单行
来源：http://dali.9152youxi.cn/Article/details/gt2jblxrjxs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2ypsubnnb.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gt2nrpohpbj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2zmhvdcpk.html

[Q51] 用子查询更新
来源：http://dali.snrcjt.cn/Article/details/gt2wmpucmkv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2mcxwuxnf.html

[Q52] 删除指定行
来源：http://dali.quarkkingdee.top/Article/details/gt2kncevure.html

DELETE FROM users WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gt2utefbcgx.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gt2axfsylei.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gt2xmvypwbi.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gt2izzkkyjl.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gt2efzofvuk.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2hesdrnko.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2zyckzneu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2lfuerpki.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2kiimzloe.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gt2jmrfvqhn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2rbvyesfi.html

[Q58] 累计求和
来源：http://dali.zhongyouzk.top/Article/details/gt2hjwraxfx.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2zjgshjuu.html

[Q59] 分组内累计
来源：http://dali.tanke756.top/Article/details/gt2dfperwpk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhwlubn.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gt2lcqcixzk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gt2kbuwkmle.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gt2jsiiyakv.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ymczcqxv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmetfwbm.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gt2sxcuoshk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2fzeyfkqw.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gt2muzufain.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gt2thjyckel.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gt2fvegeorw.html

COMMIT;
来源：http://dali.guannengcc.top/Article/details/gt2buksmssa.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2ykpmeivj.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gt2jutpweac.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gt2qvhugfop.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gt2wzogdqlj.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gt2cjffslpb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gt2jlrezsiu.html

[Q68] 保存点
来源：http://dali.cqqwz.cn/Article/details/gt2rrjqrfcx.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2hhskwdjb.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2rvkdpiqx.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gt2npjgxkkv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gt2xvtfqiyx.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2inutdnuy.html

ANALYZE TABLE users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjbnnjdd.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gt2kbznppez.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gt2ksmudran.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2cprrapwo.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2bowpcmat.html

[Q73] 查看表状态
来源：http://dali.fengsongda.top/Article/details/gt2avsjrxru.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2jbjpvspn.html

[Q74] 强制使用索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuqmqnfg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cdnleiting.top/Article/details/gt2nmrlrikp.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2wiwmcmrb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gt2zovhvirv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinqigfzy.top/Article/details/gt2bifelnqf.html


<!-- 参考信息 -->