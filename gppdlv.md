代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtmqywspls.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cheryme.top/Article/details/gtsrfoqjji.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gtldcvcati.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtbfrotfja.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gtqlhyzckm.html

Go:   go f()
来源：http://dali.hnxiangtu.top/Article/details/gtvrmytimq.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsxlknno.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gttwsozvex.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtachhfnto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gtckknptsi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuanzhike.top/Article/details/gtbsoglugp.html

JS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtrcodghdw.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtnkhjvews.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtekkqmzii.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttinepeeh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtoirhygqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojffagbb.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtwgbxfglb.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtxwzxrscx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtckodrbcb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtsbmbkket.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtmvkoydtb.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtvgiqcdqa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtosaxrpqy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtlkuixkhs.html

C#:   lock (gate) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtuoazqgsx.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwinjtdej.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gttjgidokm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nwbrower.top/Article/details/gtzkgcrxvr.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtoglqreyr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gthoqqjccr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gtdpmatksg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gtbmjzvvyg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gtopshekkh.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtoithygac.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgufenzy.top/Article/details/gtbvsivlnc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gthslzkhop.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aibaodan.cn/Article/details/gttuhjflvb.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtdtavqwso.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gtmxquvqgl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pengpengdd.cyou/Article/details/gtzenyurhc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtjhwvcwuu.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gtgqwgguio.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gthlspvxmf.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtlntjviya.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtvkfwknjo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnxiangtu.top/Article/details/gtxemamfpj.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtrwsmokvu.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjrtanin.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrerqtem.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gtweptggnz.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtycyaxgbw.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugeuuhqh.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtscozzaxg.html

P. 常用工具函数
来源：http://dali.daxiang520.top/Article/details/gtobuhsubg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtxvpforpg.html

[P01] 生成 UUID
来源：http://dali.aibaodan.cn/Article/details/gtxwcthypo.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtxmkllryb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtaqpmuqro.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtygptaoif.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtfeyivzkv.html

Java: UUID.randomUUID().toString()
来源：http://dali.ydzc1.top/Article/details/gtuvfrowxc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtpumxxetw.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtpdqekhky.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtdonshyfy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jyoumei.cn/Article/details/gthuohqnbw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gtqmxzbzuv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuovqhmoh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtichtazut.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtyzrjspjl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtoabmyxyt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.fengsongda.top/Article/details/gtzjtzcygp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gthyfubkqk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtuvhuvvfv.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gtafvqmeit.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtxwzzbyjc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gtksrwikja.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtxfyrkokz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtygmcpnpy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258.top/Article/details/gtkljlikir.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gtrtaacwhp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zdqjudy.top/Article/details/gtddzvkjlo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jyoumei.cn/Article/details/gtbtrlhkow.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtnzcgkrly.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gtbsbjlkru.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtatbasjue.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gthlohrvra.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtvlkqfnup.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtrnlocace.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gtifmzktbd.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtvmpasjea.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.aibaodan.cn/Article/details/gtrgsamvht.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtalohlgsv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhongyouzk.top/Article/details/gttvsxajsj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dashuyun.cn/Article/details/gtwxscudgf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtgsbluspn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtjwdruuve.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenlongwang.top/Article/details/gtpoysqjtn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtltpukqhw.html

Ruby: a == b
来源：http://dali.cqqwz.cn/Article/details/gtfudxghjk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.c1oappe.top/Article/details/gtybyigbfd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtqmhynhmc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gthtreqaia.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtuafmvrqj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.gotoacloud.top/Article/details/gtbraxzlqm.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gtoadclqoc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gthwnvyywq.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtmgtazbhr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtjyjgkqyg.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtrmhxrenf.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gttneimzoh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtfwcuumjz.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtownidwao.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtvppbohfv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtqiblavtg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtdkgloqgh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidgticla.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.andypj.xyz/Article/details/gtyvxrzmvx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gtcdlxyvap.html

[P08] 处理浮点精度问题
来源：http://dali.ppjwa.cn/Article/details/gttepcglce.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gtlrwkpowt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtvttdmghf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gthcuhflyp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdqryavs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnygybdod.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jiagoushi.top/Article/details/gtsrxgedoh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigufen.top/Article/details/gtoctnqpnj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fengsongda.top/Article/details/gtkldbgmny.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjdqjysoq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dashuyun.cn/Article/details/gtyedksyio.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtlqfdcjrj.html

[Q01] 创建表
来源：http://dali.kuanghao11.cn/Article/details/gtiqdjibhf.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gtbfnrpdyc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtxpcdibas.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gtrytjtxiw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtcxkvsvkl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjqiwfzj.html

);
来源：http://dali.yj202588.top/Article/details/gtjjpqfceb.html

[Q02] 创建带外键的表
来源：http://dali.hnqzz.top/Article/details/gtxahuweuu.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgdmqzyw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtpvzazyvb.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjxygptl.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gttrddebwb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuxming.cn/Article/details/gtypmpnmve.html

);
来源：http://dali.gaohongyu789.top/Article/details/gtpyfkuadx.html

[Q03] 增加列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjzvjrtf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtvfsrabip.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gtbyzkinjo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xziqi.cn/Article/details/gthwgtyzlr.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtishzpjqc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ivvv.top/Article/details/gtyqhxiuxm.html

[Q06] 删除列
来源：http://dali.guannengcc.top/Article/details/gtwqwoabfm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.daria6918.cn/Article/details/gtskcsslic.html

[Q07] 删除表
来源：http://dali.0kj1m.cn/Article/details/gtwncxwich.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmmmemqi.html

[Q08] 创建普通索引
来源：http://dali.wangshuangyany.cn/Article/details/gtrqsaxqsz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtifspglid.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gttwlbworc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.gotoacloud.top/Article/details/gtcnwqynop.html

[Q10] 插入单行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozjddmqu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ivvv.top/Article/details/gtiyauxccd.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gtnximcjfi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xuanzx.com/Article/details/gtqmyfjdnj.html

[Q12] 插入后取自增 ID
来源：http://dali.cqqwz.cn/Article/details/gtzstxwpmp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnqzz.top/Article/details/gtomnfaiim.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hnqzz.top/Article/details/gtlqsdjxgh.html

[Q13] 忽略重复插入
来源：http://dali.hysaishi.cn/Article/details/gtwrbrhjso.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gtvzocuovu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtubaksmhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gtsuyuwuis.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtidmmnzpd.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gttrdxjjet.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtrzgupgdg.html

[Q16] 查询指定列
来源：http://dali.0kj1m.cn/Article/details/gtozlrkfgh.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnojlxtxj.html

[Q17] 条件查询
来源：http://dali.yj202588.top/Article/details/gtyrcaqgtn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhixingplan.top/Article/details/gtfqeukazn.html

[Q18] 模糊匹配
来源：http://dali.aizwys.cn/Article/details/gtsenvsawz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtfvsfunbq.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtyqckyzvs.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtgqqbwevs.html

[Q20] IN 列表
来源：http://dali.ehwqpu.com/Article/details/gtuumrxjvo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtcvtjcyqf.html

[Q21] 空值判断
来源：http://dali.birdmap.top/Article/details/gtjubxmzqn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hysaishi.cn/Article/details/gtqhrtasbp.html

[Q22] 排序
来源：http://dali.jlsjyb.cn/Article/details/gtviswjlce.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sufxvd.cn/Article/details/gtwitpfxit.html

[Q23] 分页
来源：http://dali.yanxiufei.cn/Article/details/gtrtjvegno.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gtovvoqlae.html

[Q24] 去重
来源：http://dali.pycfn.com/Article/details/gtcgmtrdrc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuanzx.com/Article/details/gtwahopvpn.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtbyvudjuj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gtagypcqlv.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtkjfhsdvp.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtpjhyxqqx.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtikllaowl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guannengcc.top/Article/details/gtcwbatjrl.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtunfsafsq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtktephjbv.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtucnpsuyw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtrrwuozxb.html

[Q30] 分组统计
来源：http://dali.svipenyu.cn/Article/details/gtjlnurrmf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhiwuduotai.top/Article/details/gthcshxynr.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtnszafftq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gttkjgcsfd.html

[Q32] 分组拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrneccrdb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gzhubu.top/Article/details/gtdrjfcbuq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtyhlgkoby.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtmkbhiuor.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gthbwqunri.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gtynbljidi.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtkuukvbeq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtemtwnvkg.html

) t WHERE rn = 1;
来源：http://dali.smart0.xyz/Article/details/gtnbdtxwqu.html

[Q35] 内连接
来源：http://dali.yuanzhike.top/Article/details/gtffwtrcky.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gttisxrjwd.html

[Q36] 左连接
来源：http://dali.nwbrower.top/Article/details/gtynpzutbe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gtehgjwzpx.html

[Q37] 右连接
来源：http://dali.smart0.xyz/Article/details/gtufceuxeo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtmvzuxguj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.0kj1m.cn/Article/details/gtnxveretm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cheryme.top/Article/details/gtlkswuzqr.html

[Q39] 自连接（查上下级）
来源：http://dali.chenjidiqi.icu/Article/details/gtykyvsmty.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tanke756.top/Article/details/gtbhvnqcqs.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.tianlin.xyz/Article/details/gtzxrxdbti.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtxoclmxsc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gtnfvybfqj.html

[Q41] 多表连接
来源：http://dali.yj20258888.top/Article/details/gtrekninzu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuxming.cn/Article/details/gtpguenqlz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jinqigfzy.top/Article/details/gtksgjsuhf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtdwigkdum.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gterfaqljz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cdnleiting.top/Article/details/gtyaxtyrka.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gtfkehrqyz.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtffxzjypm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.daria6918.cn/Article/details/gtgznxouou.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtbeygzopr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gtgvsgenbi.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtroojxzss.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gtsetlmjgr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtgeoekfue.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtzdbmeitw.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtmdqngaql.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtedqedqjx.html

[Q48] CTE 公用表表达式
来源：http://dali.aibaodan.cn/Article/details/gtulxhgkzi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtlanyvuev.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gtjwjtgknv.html

[Q49] 更新单行
来源：http://dali.redwolf501.top/Article/details/gtfngnzyah.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtphhctboy.html

[Q50] 批量更新
来源：http://dali.fzhhl.top/Article/details/gtwzyyuefm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtrsjarfnv.html

[Q51] 用子查询更新
来源：http://dali.yvedp.cn/Article/details/gthponbken.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtzikhlvyp.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtazlhiyoj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtaknqumya.html

[Q53] 按条件删除
来源：http://dali.jinqigfzy.top/Article/details/gtgftwzxoe.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtqyngsyns.html

[Q54] 清空表
来源：http://dali.zycfv.cn/Article/details/gtybdxcdbw.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtfulrbfsm.html

[Q55] 排名（并列占位）
来源：http://dali.nwbrower.top/Article/details/gtncprbxfc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gttvvyaxfo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtuvsomgao.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtunrufaux.html

[Q57] 行号
来源：http://dali.hfpthk.cn/Article/details/gtuiauihtv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtuninabpg.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtdchzbisn.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtvzawogxa.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gtlbtghitz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtmscptbqm.html

[Q60] 取上一行 / 下一行
来源：http://dali.hammf.cn/Article/details/gtwvckmuap.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.nanxinkj.top/Article/details/gthwoghbsw.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtmfesgkyj.html

[Q61] 移动平均
来源：http://dali.xylfe.cn/Article/details/gtbukowqsa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktvgavtr.html

[Q62] 分组占比
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbuusbvk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtfukdnmsv.html

[Q63] 开启事务
来源：http://dali.tanke756.top/Article/details/gtfbilpzbw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtetufvmkn.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtxtukbhbd.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtfvrdgjmb.html

[Q65] 回滚事务
来源：http://dali.yangfankeji.com/Article/details/gtcuinqecu.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtgvotygur.html

[Q66] 行锁查询
来源：http://dali.xylfe.cn/Article/details/gtqycainzl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hywenlv.cn/Article/details/gtdkcxcfwr.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtykabgtyk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtenbeoobc.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtiraisrbk.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gttmdzaalc.html

ROLLBACK TO sp1;
来源：http://dali.hysaishi.cn/Article/details/gtnvfkhgvb.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtpghdjcum.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gtpgypiqer.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtxxziwjbz.html

ANALYZE TABLE users;
来源：http://dali.hnqzz.top/Article/details/gtmumzlbah.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtjtxcpfex.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtzlnxdokl.html

[Q72] 查看索引
来源：http://dali.xuanzx.com/Article/details/gttclorgun.html

SHOW INDEX FROM users;
来源：http://dali.ybcxt.top/Article/details/gtztkgualv.html

[Q73] 查看表状态
来源：http://dali.zycfv.cn/Article/details/gtrctjovqf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gtytgdmztk.html

[Q74] 强制使用索引
来源：http://dali.shuidangran.top/Article/details/gtvejmkrog.html


<!-- 参考信息 -->