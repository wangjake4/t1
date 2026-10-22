代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gt2ewiwxymv.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2vngvciwr.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2jnoxikom.html

C#:   Task.Run(() => F());
来源：http://dali.ybcxt.top/Article/details/gt2jlhvaiaq.html

[O02] 使用线程池
来源：http://dali.daria6918.cn/Article/details/gt2sfgzyyuz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gt2ztqrobxa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zdqjudy.top/Article/details/gt2jbsbepop.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gt2opatlwis.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2ezrckziu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2ahdxwbqw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gt2xvebnxma.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2zppsyqvi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqssysiw.html

[O03] 加锁保护共享数据
来源：http://dali.yonumen.top/Article/details/gt2qstdvpib.html

Py:   with lock: shared += 1
来源：http://dali.yuanzhike.top/Article/details/gt2mefedfhk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gt2crysuykn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2bydbyvly.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2qhgykkkx.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gt2sokesxwe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenlongwang.top/Article/details/gt2wsdnvojy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2xzvsxzlf.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2uqbhrqtw.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gt2sbssubsz.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gt2cbpdwpsl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gt2rrmmpmwr.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2bhxmzphg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2djobhtfn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gt2hnfkmzok.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gt2dkerfhiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xuanzx.com/Article/details/gt2clswyupp.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gt2wbsarvwh.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2brmiessq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2wazanrxd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gt2npikdtga.html

JS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gt2rayhuvhw.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gt2sodsimna.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2lxfystil.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2fluddvwv.html

Ruby: threads.map(&:join)
来源：http://dali.aizwys.cn/Article/details/gt2vunypnxa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2xisnlrfa.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2zsuunuzz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gt2cyrmoelt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ofesiggu.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gt2jsyhcdwi.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2shjsnkab.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2yjvmtnsz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gt2moplbpoh.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gt2aktfxnjs.html

C#:   Parallel.For
来源：http://dali.quarkkingdee.top/Article/details/gt2nqwqmots.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2mcezowdz.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gt2yfxmhwdq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzkbmovv.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gt2vdamfkok.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gt2rjinrcef.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gt2dmzaauyw.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfkxeyio.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2vdivqpcj.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2kqpbbxoq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gt2iasubfbv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gt2fummpvmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2fjfpxkxe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2zdhmuzqv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyxkuejq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2ihibdiki.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gt2dxbsmryr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ybcxt.top/Article/details/gt2qhvkubiy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gt2pvwtymrj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gt2yawnishz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jauxahlo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xylfe.cn/Article/details/gt2ewufufxn.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2qpyufgcq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gt2nkrvhvlp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2muoullpn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gt2ihmewwiw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2cftcivuw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gt2bcdakzat.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xylfe.cn/Article/details/gt2yotjpymm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2zbacpkon.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.snrcjt.cn/Article/details/gt2tbpckqtn.html

[P04] 求长度
来源：http://dali.jqgfzy.top/Article/details/gt2qmeaacia.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gt2awuvqyot.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2btnwrbwx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gt2pqnkfboq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gt2yomrfovv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258888.top/Article/details/gt2dwyetlcx.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gt2jgvyqdqy.html

Ruby: x.length;  x.size
来源：http://dali.tanke756.top/Article/details/gt2dqmfbpyg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2vovfgfet.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhfevyzf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gogol.net.cn/Article/details/gt2jxmqgzho.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2feqnsaib.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gt2myjxurid.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2gxgjkeqd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gt2llaahvir.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2czokjohw.html

Ruby: a == b
来源：http://dali.smart0.xyz/Article/details/gt2noshjsmw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2gwqsitth.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ybcxt.top/Article/details/gt2dmvhwqal.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2wcmiwfoi.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtfehlx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2ulxgeees.html

TS:   if (x == null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fgovkvrl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2htgllfxm.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjhmqrdx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gt2izqriavd.html

C#:   if (x is null) {}
来源：http://dali.yj20258.top/Article/details/gt2bcwqbomg.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2zqmanjqg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gt2nnvxqpwo.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gt2nfozllzx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gt2hvkbyruc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2dzdebytv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2snasmfhc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gt2oiiavpvh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jlsjyb.cn/Article/details/gt2xggiufyu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shuidangran.top/Article/details/gt2utahycvr.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2enzysjot.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2nszajwgg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2cnxjarki.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2clnoisnc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2affjdqwh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gt2gvvcfqgn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenjidiqi.icu/Article/details/gt2jriztrio.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gt2aetpdmfw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gt2vhkadyvb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2lajtnesf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zmfjvypq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2boybfcbg.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gt2bihpkljf.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gt2gkxpgxve.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2wihsnbyf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2fjfoyduo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yongpay.top/Article/details/gt2eyosyaey.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wifvxqaz.html

);
来源：http://dali.ybcxt.top/Article/details/gt2vweewnjm.html

[Q02] 创建带外键的表
来源：http://dali.aibaodan.cn/Article/details/gt2mrjspgkj.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2enxngyjp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiivdhki.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gt2nghnwfmk.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gt2qnlvwtkq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zufhngln.html

);
来源：http://dali.yvedp.cn/Article/details/gt2ouppmngt.html

[Q03] 增加列
来源：http://dali.gogol.net.cn/Article/details/gt2jixvjdgx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ydzc1.top/Article/details/gt2ruesfwat.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gt2hpiqdcyp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gt2jkwnilir.html

[Q05] 重命名列
来源：http://dali.bjfxy.top/Article/details/gt2eqmhqoui.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gt2vagdoomj.html

[Q06] 删除列
来源：http://dali.shuidangran.top/Article/details/gt2irbgsgjk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258.top/Article/details/gt2xgicugqb.html

[Q07] 删除表
来源：http://dali.yanxiufei.cn/Article/details/gt2isceemtp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gt2ehlqskcm.html

[Q08] 创建普通索引
来源：http://dali.zhongyouzk.top/Article/details/gt2wzoyroct.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigfzy.top/Article/details/gt2sipscoyk.html

[Q09] 创建唯一索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vrhjysng.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nwbrower.top/Article/details/gt2yvineiug.html

[Q10] 插入单行
来源：http://dali.jinqigufen.top/Article/details/gt2jffrbsvd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gt2lobnhcmi.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2zlceujmt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sxryk.cn/Article/details/gt2lxepcpzq.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gt2rmiqrrxp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2wuizcyuf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.chenlongwang.top/Article/details/gt2dbuuvjmi.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivzefvnk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yongpay.top/Article/details/gt2atxqydtg.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gt2zvoxjyin.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hywenlv.cn/Article/details/gt2dnlphzgw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gt2uabwfmoq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjpugv.html

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2xyrbnvbs.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gt2nyeeplij.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2bpgbcjpw.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gt2lproysce.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aizwys.cn/Article/details/gt2dxkeybus.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2kvzjngqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gt2mtnwuycr.html

[Q19] 范围查询
来源：http://dali.snrcjt.cn/Article/details/gt2gquavreg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhongyouzk.top/Article/details/gt2kfzlepzn.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gt2samwlvky.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2jzfnpvvi.html

[Q21] 空值判断
来源：http://dali.hywenlv.cn/Article/details/gt2jicjvupv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tijwvhyl.html

[Q22] 排序
来源：http://dali.yuanzhike.top/Article/details/gt2zvptkdxc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2uxjsupld.html

[Q23] 分页
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flcuwlds.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gt2gljpmqoi.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2obivgeju.html

SELECT DISTINCT city FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ogdlxhdt.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gt2zfyhzkjk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tian-w.cn/Article/details/gt2lncvsilz.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gt2zjocfweo.html

SELECT COUNT(*) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2qppurqwf.html

[Q27] 条件计数
来源：http://dali.tian-w.cn/Article/details/gt2clxzvcii.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2okyhqzdn.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gt2gqllfwvl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gt2rcwnbzzf.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2pcsocfki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2ypasojuw.html

[Q30] 分组统计
来源：http://dali.quarkkingdee.top/Article/details/gt2agvrgpmh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gt2mvzjuhxb.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gt2faijqhsg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2ofnzbvxz.html

[Q32] 分组拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gt2rrimxgom.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gt2lhmnfpey.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhoulong.xyz/Article/details/gt2caklqxxk.html

[Q33] 多列分组
来源：http://dali.hfpthk.cn/Article/details/gt2qwexgrwa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tanke756.top/Article/details/gt2qleqpyil.html

[Q34] 每组取第一条
来源：http://dali.yj202588.top/Article/details/gt2eiryzbok.html

SELECT * FROM (
来源：http://dali.yuanzhike.top/Article/details/gt2fsmjumph.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtypyhd.html

) t WHERE rn = 1;
来源：http://dali.sysykeji.top/Article/details/gt2lqjxnkad.html

[Q35] 内连接
来源：http://dali.wangdashe.top/Article/details/gt2hxunziwr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gt2ttpwkkqh.html

[Q36] 左连接
来源：http://dali.cdnleiting.top/Article/details/gt2ixibxwjn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gt2dhsdynbc.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gt2jlwvaguo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gt2luawofjk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cdnleiting.top/Article/details/gt2smtmvyqf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ybcxt.top/Article/details/gt2yqezejbh.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2awmnwvhq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gt2ignuaoss.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.birdmap.top/Article/details/gt2igqeqgen.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ppjwa.cn/Article/details/gt2wlhuytwp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.svipenyu.cn/Article/details/gt2aeocfqvp.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gt2dstxzmwv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pycfn.com/Article/details/gt2zfattulv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuanzx.com/Article/details/gt2rtjzqyiz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pycfn.com/Article/details/gt2yxcemkkp.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2tjryeybv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gt2vvgeaqdg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gt2qzmiosbg.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gt2yryxvkkn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pycfn.com/Article/details/gt2yfnfmtwh.html

[Q44] IN 子查询
来源：http://dali.chenzaomai.com/Article/details/gt2mileawky.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhengqikj.top/Article/details/gt2ltrctnum.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gt2vkumkdpw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahztwedz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gt2lksmuihv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gt2bbptwnde.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gt2sbllbzft.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gt2jmeleexu.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2vqsbluyp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gt2utvwcakh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gt2cpdjxdhh.html

[Q49] 更新单行
来源：http://dali.yvedp.cn/Article/details/gt2istzoxeb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2ithmewoq.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2lccvoxtd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2kmjkekho.html

[Q51] 用子查询更新
来源：http://dali.0kj1m.cn/Article/details/gt2gosuzkos.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2nqwilbpd.html

[Q52] 删除指定行
来源：http://dali.havefunace.top/Article/details/gt2fphakhop.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gt2aiwkafyj.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlsnobop.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cheryme.top/Article/details/gt2bbbvqdnl.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gt2zexpksxl.html

TRUNCATE TABLE logs;
来源：http://dali.zycfv.cn/Article/details/gt2vmnedsfw.html

[Q55] 排名（并列占位）
来源：http://dali.birdmap.top/Article/details/gt2eafqzusa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gt2akhrghcf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zdqjudy.top/Article/details/gt2xfpgbghu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hammf.cn/Article/details/gt2ydqowqff.html

[Q57] 行号
来源：http://dali.tian-w.cn/Article/details/gt2kbmvoajo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2eeityauk.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gt2qdvggyle.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2nivrcqmq.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gt2skhoczvv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gt2cutjqsxh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gt2gywnkiqj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xylfe.cn/Article/details/gt2jdvrxsua.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvwgnhwr.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gt2cexhznuc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2mgdfehnr.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gt2nqjqjwti.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cdnleiting.top/Article/details/gt2oinmwsfz.html

[Q63] 开启事务
来源：http://dali.yuanzhike.top/Article/details/gt2nlcpzxqq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.0kj1m.cn/Article/details/gt2bwjjxmdw.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gt2cmgickyt.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gt2sbolwdsx.html

[Q65] 回滚事务
来源：http://dali.xziqi.cn/Article/details/gt2shrxgsyl.html

ROLLBACK;
来源：http://dali.nanxinkj.top/Article/details/gt2xccmfano.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gt2mdtwzbcq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2usbvsrrr.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gt2illlfaef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jyoumei.cn/Article/details/gt2lwwusbrj.html

[Q68] 保存点
来源：http://dali.cucudq.cn/Article/details/gt2krbuxaem.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2anjuucwr.html

ROLLBACK TO sp1;
来源：http://dali.yongpay.top/Article/details/gt2rdbvsdro.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gt2xmwxjtnj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tanke756.top/Article/details/gt2yooyjlop.html

[Q70] 更新统计信息
来源：http://dali.jlsjyb.cn/Article/details/gt2qoynrggz.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gt2emcwcglg.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gt2ihpnheog.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cashguo.top/Article/details/gt2dlfgmyec.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2krenugyp.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fygwahqx.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gt2wcrosqvi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyoblcau.html

[Q74] 强制使用索引
来源：http://dali.xuanzx.com/Article/details/gt2bzrllshb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gt2rbincokt.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fxazgoed.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2pvkgglvo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gt2pwfqhbcs.html


<!-- 参考信息 -->