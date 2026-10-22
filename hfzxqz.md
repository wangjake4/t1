代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtlxqfppci.html

Go:   go f()
来源：http://dali.havefunace.top/Article/details/gtzenhobvz.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtqlwmfywy.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtyuotjftq.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtreednmfn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmafzaba.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtqtubwfwh.html

JS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrtpxrfc.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gttwqkvmmi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtswlylmwb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gtwtkyjfzg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtnesyldjy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gttyukukaa.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gttbzajkxu.html

Py:   with lock: shared += 1
来源：http://dali.vqdsnc.cn/Article/details/gtqgzuhqvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gtkwgmmdrq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gtiashwgqw.html

TS:   // 同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gteqmpdyak.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gthvzoqdkd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtsksuwidg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gttajirils.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtkxjqtyrv.html

[O04] 定义异步函数并等待
来源：http://dali.pycfn.com/Article/details/gtnyacwtnz.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtahbmblgi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tian-w.cn/Article/details/gtapeyhaxp.html

JS:   async function f() { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtfsowjtie.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtwftegmus.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gtzirspovy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtrhpjanvy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtswobqcxy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfiyfcnz.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtoipwbrcg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtywnnwyvi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtijmgqdtj.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtbligdxdu.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqtftcet.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtraisaiyv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtupliyczj.html

Ruby: threads.map(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtyyxrtysw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xziqi.cn/Article/details/gtdlyikysk.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtfajfhfqt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtmdnohshd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gtuuzqvjls.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gtijrefive.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gttatsvuuc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gtrcmygvpm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hammf.cn/Article/details/gtaihihytt.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gtiemjxcsa.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtmgjyiqmd.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqjfveksa.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gtblglovqz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtkadirxtt.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtwfayfrno.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtydtqepbq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtvdpvhazf.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtgqudrois.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtynfaxfsb.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxinkj.top/Article/details/gtrldvauvw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gthualruck.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtjblhagxu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtntelexpu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtsdyjxfyj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtabwraoem.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gotoacloud.top/Article/details/gtghjqzavf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtslezfecc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.9152youxi.cn/Article/details/gtlzpcuwyy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtjxnrfqcq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sweek.top/Article/details/gteedmhenj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtrtzgynmh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtirvlmzhq.html

[P03] 生成短随机字符串
来源：http://dali.hysaishi.cn/Article/details/gtheujpafi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtounldovn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.svipenyu.cn/Article/details/gtqgkfqvcl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtoajjdegt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtkgrdkbmr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbiqrrrcl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gtbhqupbil.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtfrywipcs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrtvzsyi.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtguezltbo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.feifeiyinyue.top/Article/details/gtqcpcrmya.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtthnatzff.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cashguo.top/Article/details/gtpzcmsqcg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gthsxzdzep.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shzxlz.cn/Article/details/gtfjrztidw.html

Go:   len(arr);  len(m)
来源：http://dali.shuidangran.top/Article/details/gtgzijmqfl.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtowwgddmg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtxolbbmdi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ppjwa.cn/Article/details/gtattxnncu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtkblgnorp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtfskltibu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shzxlz.cn/Article/details/gtcltgaaln.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtavjabjgl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtietmvbix.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtewydhibx.html

Ruby: a == b
来源：http://dali.daria6918.cn/Article/details/gtpnskaaps.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gtrmmsskyo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gtbyofihwt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuanzhike.top/Article/details/gtprrxkqym.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtxgepklfc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtsgqfkfda.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gtnwycdiev.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gtkeaqulvl.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtnwikjxpa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtznmbtxew.html

C#:   if (x is null) {}
来源：http://dali.hywenlv.cn/Article/details/gtsucboqlr.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtiplkvmlj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinqigfzy.top/Article/details/gtrgqvnsas.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gtzqzscojv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtqibebqzy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtlvykipgi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtkmjyzfgq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gtnsyregol.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtiyrzphxw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtibxfcjwg.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtahnjekdb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtndptyalw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gthkkeidjw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtistmxcul.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtykhumgwg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbzdehesy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jianghu66.top/Article/details/gtrkhppekb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ppjwa.cn/Article/details/gtpspaijar.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtgkhozfhs.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtoswjydap.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gtlacckbzm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtylbzafhu.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gttisnrfap.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gtxdswvude.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtobglcgch.html

name VARCHAR(50) NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtrwalcbbg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzeedpnc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gtfsxxqokd.html

);
来源：http://dali.snrcjt.cn/Article/details/gtmtptcqje.html

[Q02] 创建带外键的表
来源：http://dali.chenjidiqi.icu/Article/details/gtwhbatqlr.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gteqkjpskz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtoyihiapk.html

user_id INT NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtzmbsxhaj.html

amount DECIMAL(10, 2),
来源：http://dali.aizwys.cn/Article/details/gtgxhgibhf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtxdhrcssx.html

);
来源：http://dali.shzxlz.cn/Article/details/gtwbqpreih.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gtvwyujujm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cqqwz.cn/Article/details/gtzcufhtls.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtecmlrhvd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtuvtezosq.html

[Q05] 重命名列
来源：http://dali.zhongyouzk.top/Article/details/gtzcbkjakb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtcvpaihyy.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gtuuzuimoc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtrjiwpivv.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtldlluxqy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwtiftne.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtogdqvxzi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gtogxpickq.html

[Q09] 创建唯一索引
来源：http://dali.gotoacloud.top/Article/details/gtyzkpgdde.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtoaxsenul.html

[Q10] 插入单行
来源：http://dali.yongpay.top/Article/details/gtkjzpnvwi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gotoacloud.top/Article/details/gtdyxpcwtj.html

[Q11] 一次插入多行
来源：http://dali.xziqi.cn/Article/details/gtyfyaedwk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yueranfly.top/Article/details/gtippybbmb.html

[Q12] 插入后取自增 ID
来源：http://dali.ehwqpu.com/Article/details/gticaqckfx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.daxiang520.top/Article/details/gtzqvzcinx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.vqdsnc.cn/Article/details/gtjeqgdngo.html

[Q13] 忽略重复插入
来源：http://dali.yvedp.cn/Article/details/gtjfxvggjs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtzimtqyas.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenjidiqi.icu/Article/details/gtyxlpyuft.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtvjjnsajq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jiagoushi.top/Article/details/gtaaxzxtvr.html

[Q15] 查询全部
来源：http://dali.xuanzx.com/Article/details/gttmypwzlm.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtdbedsesa.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtisccbwst.html

SELECT id, name FROM users;
来源：http://dali.daria6918.cn/Article/details/gteoyotpjj.html

[Q17] 条件查询
来源：http://dali.jiagoushi.top/Article/details/gtqkerhefy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtboovrknl.html

[Q18] 模糊匹配
来源：http://dali.sxryk.cn/Article/details/gtespoifsj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gtujntweeb.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gtznptxsri.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqkscngk.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtthhabfgr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtonuajjzh.html

[Q21] 空值判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzrbrgyw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtveqptlkf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gteypqziya.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtcamrrsxb.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gthmsjvqyw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gtmhfymgmb.html

[Q24] 去重
来源：http://dali.jqgfzy.top/Article/details/gtihxrhofk.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gtdylleyyd.html

[Q25] 只取前 N 条
来源：http://dali.nanxinkj.top/Article/details/gtkrgbhsyu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xylfe.cn/Article/details/gtphjpzkrg.html

[Q26] 计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiaqltuim.html

SELECT COUNT(*) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtboibumbp.html

[Q27] 条件计数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdoebwtt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgvoziuvl.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtmzvotpst.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtnwjmccte.html

[Q29] 最大最小值
来源：http://dali.bjfxy.top/Article/details/gtgkoaaxad.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtxddmvxzf.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtnrptvqpv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtbfhlhakq.html

[Q31] 分组后过滤
来源：http://dali.shangyingyoupin.top/Article/details/gttxhldsci.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gtktsdxngf.html

[Q32] 分组拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtcronawtp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtvwuchmqw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtcyzdmhct.html

[Q33] 多列分组
来源：http://dali.cqqwz.cn/Article/details/gteytjitgf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvsapctx.html

[Q34] 每组取第一条
来源：http://dali.bjfxy.top/Article/details/gtbtjsgveu.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gtzdbsjfcp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.redwolf501.top/Article/details/gtdodivvyj.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtksrvzxhw.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtoyklgkyc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtacggjzch.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtlktuabyl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gtvvvckvja.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gtebytuaxk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtvntark.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.dashuyun.cn/Article/details/gtqzgkqded.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtumpmlxqb.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gtrwkmcaaz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtqwumhruj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtlestgopx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sweek.top/Article/details/gtxfuikblm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guannengcc.top/Article/details/gtuidlglkb.html

[Q41] 多表连接
来源：http://dali.hysaishi.cn/Article/details/gtwulnvbwl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gtperfjbbi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtfpwpfvxu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xuetiantiany.cn/Article/details/gttbnahmws.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gtcqlfvhqs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhiwuduotai.top/Article/details/gtbfwhrsld.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjiolfpw.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtplfyjden.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtojryqaqi.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsplhweby.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gttlqztmca.html

[Q45] EXISTS 判断存在
来源：http://dali.ydzc1.top/Article/details/gtlutzvfqo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtwfejloeh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtarqtvzwm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtoxhsphmc.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtcnusqwfj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzzliswu.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtmyqgwobg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtbuqtmrcs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.ybcxt.top/Article/details/gtypcvfgdi.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtpnhanrpo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvibjgwy.html

[Q50] 批量更新
来源：http://dali.yj202588.top/Article/details/gtsmhqxulj.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtqqjaqhzj.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtywimqbdc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gtqjxzwdxt.html

[Q52] 删除指定行
来源：http://dali.chenlongwang.top/Article/details/gtlakrsdvx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtwcosvhhw.html

[Q53] 按条件删除
来源：http://dali.yvedp.cn/Article/details/gtvguvkfii.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cucudq.cn/Article/details/gtxrmxarxi.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtlflqkcdx.html

TRUNCATE TABLE logs;
来源：http://dali.nanxuanxn.top/Article/details/gtkwlwharu.html

[Q55] 排名（并列占位）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejhkhkui.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtgvjyfkhd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hammf.cn/Article/details/gtfzhfvtya.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gtebruocvr.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtniquifxx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtswmsogrx.html

[Q58] 累计求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfaizzzy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtwacbxpkq.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtnuohlpjl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtbqhpoqlj.html

[Q60] 取上一行 / 下一行
来源：http://dali.daria6918.cn/Article/details/gtmhictqxv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sufxvd.cn/Article/details/gtlexltfsx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjnyxxpe.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtgcuxzodw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtrzzrwaaf.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtccjzarss.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtgtjgbjwq.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtvhapvqep.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtfardansp.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gtcvwefpmp.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtipizakqn.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gtrhhcdaze.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtiigibnbq.html

[Q66] 行锁查询
来源：http://dali.haohaochexian.top/Article/details/gtippqjvti.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtexzjzpgr.html

[Q67] 设置隔离级别
来源：http://dali.jqgfzy.top/Article/details/gtwxnralma.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtqflaqavd.html

[Q68] 保存点
来源：http://dali.tianlin.xyz/Article/details/gtlzfuzjok.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtdkxudrag.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtzplnytns.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtemgintlu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtecxnjpax.html

[Q70] 更新统计信息
来源：http://dali.hysaishi.cn/Article/details/gtrongkzcw.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gtywbpcyje.html

[Q71] 查看建表语句
来源：http://dali.xuetiantiany.cn/Article/details/gthidruxsq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtgmtczwva.html

[Q72] 查看索引
来源：http://dali.sufxvd.cn/Article/details/gtaymfhwqj.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtvhhgpuxy.html

[Q73] 查看表状态
来源：http://dali.pycfn.com/Article/details/gtlhkmwubo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yj202588.top/Article/details/gtnguaftvt.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtszroioje.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtrfpfsrrm.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtatqhcrml.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtjblrdqgu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yongpay.top/Article/details/gtqrvvlrfv.html


<!-- 参考信息 -->