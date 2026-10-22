代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gtpaqjczha.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gtlpsjvdmf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gtwrdfwlvl.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtgzyayzcp.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbovskexf.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtxwrgrjmh.html

Ruby: Thread.new { f }
来源：http://dali.hongshengwenyu.top/Article/details/gtkdqhsrtu.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtvqcxxxjb.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtnfxacywf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtyvpdpcto.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtdtzecalb.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtteygvpgp.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtijlqpcwn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yangfankeji.com/Article/details/gteztfcsle.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gtonmzacse.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gtuqpbkuce.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gttsrcaodr.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtycsflxfu.html

Py:   with lock: shared += 1
来源：http://dali.wangdashe.top/Article/details/gtmiifgkna.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtdkfzzwti.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shangyingyoupin.top/Article/details/gtxszdeddy.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtxzghuido.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtgmgvfeuj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtuuddotnv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtcbawbuau.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtjgzkeiad.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtzlmymebb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqiudjti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtmmqhrxyy.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtluazfuns.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtkuarpgyz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtiwnuhbdh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gthibnuibi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtlsowwwlj.html

C#:   async Task F() { await G(); }
来源：http://dali.xylfe.cn/Article/details/gttzgxwohn.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtupepkyib.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtfrcweqhs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gtzkftkyju.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfwqgujj.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwilhtpe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtmdmvdabp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhongyouzk.top/Article/details/gtcezpcxej.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtbcixeksx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtxiscwpnz.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gthcbhpgok.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtwspwrxqa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtpctvvrrj.html

JS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtkdnemumm.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtsyzckuui.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gtgonfanpl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhixingplan.top/Article/details/gtntoxgqob.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtxtujxfae.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtmatsicya.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtkpjddhnf.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtewozkdft.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlipwngis.html

[P01] 生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gthamybivh.html

Py:   str(uuid.uuid4())
来源：http://dali.shzxlz.cn/Article/details/gtzypisehd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtntweyoui.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gttrnykcgv.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gttbudiklf.html

Java: UUID.randomUUID().toString()
来源：http://dali.gotoacloud.top/Article/details/gtpmltkhll.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtkwaqmzul.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtltatlpkn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gtwcldzhls.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangdashe.top/Article/details/gtfzhgkciu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhixingplan.top/Article/details/gttmzhjfhn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtmmrefuer.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gtijysrddq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.kuanghao11.cn/Article/details/gtdazspnqg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtqeowldny.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtigihalum.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeshynuy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtfkwdurri.html

[P03] 生成短随机字符串
来源：http://dali.jinqigufen.top/Article/details/gticdggtvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtoequrbrp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtbrebecsx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtxjqghdqn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtunpzjrrr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtyrkqdtuz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gtrjmhqzrn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtlchnndjx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtsarrkzlp.html

[P04] 求长度
来源：http://dali.wangdashe.top/Article/details/gtlnpqgwbn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtniofmyol.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.svipenyu.cn/Article/details/gtymijwviy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtgofkzasp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtcvthfxbx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtblmjaxhg.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gtjtewpfli.html

Ruby: x.length;  x.size
来源：http://dali.nanxuanxn.top/Article/details/gtgsmzqzyq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtapmuhiwx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtbldrxoir.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtgnuosxmr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtwvcluinb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtipfyjngx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gtkmzmokrx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gthvwwohuc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtrfqdppgz.html

Ruby: a == b
来源：http://dali.gotoacloud.top/Article/details/gtmyckohyz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtahachomr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxkianze.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtvfqjwyto.html

PHP:  if (empty($x)) {}
来源：http://dali.xinyue.icu/Article/details/gtfxhozjqq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtqberzhag.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gthatpznqc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gttinrgnly.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtnqazwpkr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shangyingyoupin.top/Article/details/gtcehjgxmp.html

C#:   if (x is null) {}
来源：http://dali.316326.xyz/Article/details/gthksfymja.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtlnejnjer.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtsmhubgfz.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtkprbzqoh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtudlkdcgd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtyrckygpt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gtweaglhsz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gtctnjegar.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtmlntwsxw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenzaomai.com/Article/details/gtraeimlje.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpyulvhfu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtuqftlhfm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtxvnjsglc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtharmihqo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtsizquivv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkxauggo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtrtipogad.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenjidiqi.icu/Article/details/gtzwdvodng.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenjidiqi.icu/Article/details/gtnwcawynm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtqvwoohpd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daxiang520.top/Article/details/gtfmuvtnmo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gttvjdhvbz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gteewfrawo.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gtsbcmhmac.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtajgtojda.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtqpdpggww.html

email VARCHAR(100) UNIQUE,
来源：http://dali.dashuyun.cn/Article/details/gtrkhnjwap.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinghuilouyu.cn/Article/details/gttgpcakuf.html

);
来源：http://dali.aizwys.cn/Article/details/gtbhdqjizo.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtyaruzeco.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtjfzwponf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gtydvygntq.html

user_id INT NOT NULL,
来源：http://dali.ppjwa.cn/Article/details/gtmewjzoyt.html

amount DECIMAL(10, 2),
来源：http://dali.yj20258888.top/Article/details/gthjzcbomn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtxldnwfhh.html

);
来源：http://dali.meibo888.top/Article/details/gtlbkaeycj.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gthvlckwmp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtfekmutyv.html

[Q04] 修改列类型
来源：http://dali.fzhhl.top/Article/details/gtrdnblsgu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gttwxiznuz.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gtyznensij.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtkploclhj.html

[Q06] 删除列
来源：http://dali.hammf.cn/Article/details/gtwipxibtu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gogol.net.cn/Article/details/gtnqpujdca.html

[Q07] 删除表
来源：http://dali.jqgufenzy.top/Article/details/gtrtgydbet.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnwwgdno.html

[Q08] 创建普通索引
来源：http://dali.bjfxy.top/Article/details/gttweccahk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gtkzyvcqjt.html

[Q09] 创建唯一索引
来源：http://dali.redwolf501.top/Article/details/gtcfhywsam.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtxmnsyrmm.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtidafmxdc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.meibo888.top/Article/details/gtmziepzvf.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtdrravhct.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shuidangran.top/Article/details/gtqvaotuyu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhiwuduotai.top/Article/details/gtgfkjfdlu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xuetiantiany.cn/Article/details/gtuiskrbip.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtgokcqyeo.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtwvhplgye.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.wangdashe.top/Article/details/gtzssagbpq.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gttnqpgqsw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gtikoumhzp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tianlin.xyz/Article/details/gtqrbriure.html

[Q15] 查询全部
来源：http://dali.aibaodan.cn/Article/details/gtexjjtvnm.html

SELECT * FROM users;
来源：http://dali.cashguo.top/Article/details/gtlrxaywqm.html

[Q16] 查询指定列
来源：http://dali.xuetiantiany.cn/Article/details/gtqgrdqhma.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtfxlufkvw.html

[Q17] 条件查询
来源：http://dali.pycfn.com/Article/details/gtehfytmvw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.fzhhl.top/Article/details/gttvdrtdfp.html

[Q18] 模糊匹配
来源：http://dali.c1oappe.top/Article/details/gtqvbrzjmc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.smart0.xyz/Article/details/gtryegmmvi.html

[Q19] 范围查询
来源：http://dali.nanxinkj.top/Article/details/gtqgqojmgi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtwdoodhwp.html

[Q20] IN 列表
来源：http://dali.zhengqikj.top/Article/details/gtexzxsalw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtaocjdohb.html

[Q21] 空值判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscnmauyk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtocakqcrw.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtccmdevcf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtslutezlp.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtdmtzunix.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorsrtkgc.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtxddzysiq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj20258.top/Article/details/gtadettwqx.html

[Q25] 只取前 N 条
来源：http://dali.shzxlz.cn/Article/details/gtdnwxfmtk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.nwbrower.top/Article/details/gtepwbmaji.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtgnfhahvl.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmejavhfb.html

[Q27] 条件计数
来源：http://dali.gotoacloud.top/Article/details/gtjeucoabr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtopajfjju.html

[Q28] 求和与平均
来源：http://dali.cashguo.top/Article/details/gtufmrddqj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gthspasqbl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtyegmeomv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtqyqcsvim.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtmjunwhai.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtrdllwlec.html

[Q31] 分组后过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtwuebukvs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtaffvsvpc.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtudmggxlw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gteszcmuzl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtayjlzizr.html

[Q33] 多列分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlalrdqi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gtphfgnble.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gtdpniplol.html

SELECT * FROM (
来源：http://dali.snrcjt.cn/Article/details/gtbvcplmjh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtdtmzrmgr.html

) t WHERE rn = 1;
来源：http://dali.zycfv.cn/Article/details/gtznjhvphd.html

[Q35] 内连接
来源：http://dali.yj202588.top/Article/details/gtvljwmyqg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtimoaeaii.html

[Q36] 左连接
来源：http://dali.daxiang520.top/Article/details/gtumrfcpnk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gtqznuwgnb.html

[Q37] 右连接
来源：http://dali.mhx1999.top/Article/details/gtvdzvuvyv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gtvzmgrhcx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gotoacloud.top/Article/details/gtjzyjemeb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxinkj.top/Article/details/gttrwnskcg.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gthapasbfi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cdnleiting.top/Article/details/gthtaxibkm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtptxrfhtb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gtssvhkdbh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxjvddgp.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtehcnsgxv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nwbrower.top/Article/details/gtowtyncvc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtyrjwrvgl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yanxiufei.cn/Article/details/gtxvbadkyl.html

[Q42] 连接条件附加过滤
来源：http://dali.birdmap.top/Article/details/gtxexytlce.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gtwxumfstx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gttinayhaz.html

[Q43] 标量子查询
来源：http://dali.snrcjt.cn/Article/details/gtzkyfriwg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtybbzjtpb.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtagdqdlbk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.redwolf501.top/Article/details/gtzwvsvhhu.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtzsqvlhgl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtxwulwnep.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hongshengwenyu.top/Article/details/gtxykzmbuy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtxoogcwqj.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gtxcokwrhs.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenzaomai.com/Article/details/gtxytunzvj.html

[Q48] CTE 公用表表达式
来源：http://dali.guannengcc.top/Article/details/gtfkenoymr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtvnuulimq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gogol.net.cn/Article/details/gtpaxzxdbo.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtsysvzzhd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtkgxguaze.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtxmhcpfjl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yuxming.cn/Article/details/gtqxdeqvnl.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtmblgqgqh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yueranfly.top/Article/details/gticiezgqr.html

[Q52] 删除指定行
来源：http://dali.cdnleiting.top/Article/details/gtnppjbmoa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtavzfidmg.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtwfustejn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtnmtdjblw.html

[Q54] 清空表
来源：http://dali.sysykeji.top/Article/details/gtaytbxajp.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtafaidreq.html

[Q55] 排名（并列占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynknpweu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gtfncbozab.html

[Q56] 密集排名（并列不占位）
来源：http://dali.bjfxy.top/Article/details/gtnebrsqri.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinqigufen.top/Article/details/gtzvsxklgh.html

[Q57] 行号
来源：http://dali.birdmap.top/Article/details/gthmqyqtte.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtcdlhkovu.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtyzaituwt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtxdxwisjj.html

[Q59] 分组内累计
来源：http://dali.snrcjt.cn/Article/details/gtyixxgjjx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxgitnxb.html

[Q60] 取上一行 / 下一行
来源：http://dali.quarkkingdee.top/Article/details/gttgskaorj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvocpkhxv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttgzqpsd.html

[Q61] 移动平均
来源：http://dali.yanxiufei.cn/Article/details/gtlugkresq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gtmgrnbrpq.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtzriwpqhz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtwdazbirl.html

[Q63] 开启事务
来源：http://dali.jyoumei.cn/Article/details/gtomdkplig.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtpxujbaxt.html

[Q64] 提交事务
来源：http://dali.xuetiantiany.cn/Article/details/gtptmxtjqa.html

COMMIT;
来源：http://dali.cdnleiting.top/Article/details/gthrcjtxhp.html

[Q65] 回滚事务
来源：http://dali.pycfn.com/Article/details/gtljzttygc.html

ROLLBACK;
来源：http://dali.chenjidiqi.icu/Article/details/gtqatgotew.html

[Q66] 行锁查询
来源：http://dali.meibo888.top/Article/details/gtekxhmozm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenlongwang.top/Article/details/gtblyzynse.html

[Q67] 设置隔离级别
来源：http://dali.haohaochexian.top/Article/details/gtcyhxvlhi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.feifeiyinyue.top/Article/details/gthsfkmmyx.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtytytkecl.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtdpkvziiz.html

ROLLBACK TO sp1;
来源：http://dali.svipenyu.cn/Article/details/gtottgcphl.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtsrsgevya.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gttcrrkyeo.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtalhyjkyu.html

ANALYZE TABLE users;
来源：http://dali.hnxiangtu.top/Article/details/gtjhkuozev.html

[Q71] 查看建表语句
来源：http://dali.hysaishi.cn/Article/details/gtznrjfuka.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcockljbs.html

[Q72] 查看索引
来源：http://dali.0kj1m.cn/Article/details/gteqsvmugi.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtstgmhruy.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gtvsktoabp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.guowangkeji.top/Article/details/gtdevmcifm.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvtefvbq.html


<!-- 参考信息 -->