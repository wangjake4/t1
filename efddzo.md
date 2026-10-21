代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.yonumen.top/Article/details/gtfmsqvnwf.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gthqrmdjos.html

Ruby: Thread.new { f }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbrgfalc.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gtkdalkzjk.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtqrewpsuz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gttmpnjirq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtlcqzelej.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gthkkgmuwr.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gteofcihiq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gtgikvunbo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gttnfrrohd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtrqwipfuq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpexetuyq.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtvyfbxeco.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtkrvgdpdc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtirbomlky.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gttnulgnuh.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtjaifevog.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtxljgonny.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ppjwa.cn/Article/details/gtxavilpqn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gtbqfklezf.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtuqpmrynt.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gtmcfqkmyk.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gttfobasbn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtinskxuwk.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gtkxmsfgis.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtbbvszlvm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtlgsedkge.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtnctyfdwj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhengqikj.top/Article/details/gthfiyqawc.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtfjbsnlwe.html

[O05] 并发执行并等待全部完成
来源：http://dali.guowangkeji.top/Article/details/gtunzbgeow.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtckrqdedg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtvwkkapio.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtvufmwptg.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtybwhiilb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sysykeji.top/Article/details/gtpvnpuyuv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtkkkdwomt.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtbisqygmi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.redwolf501.top/Article/details/gtzruqplee.html

[O06] 使用进程池
来源：http://dali.gzhubu.top/Article/details/gtigseodyi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtjmzafmvh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtbwyvvcpm.html

JS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gtcoxehspu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxvbuimo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtboypljfd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gotoacloud.top/Article/details/gtsrfppeak.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtubrrynhx.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtxlmzwqrr.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtywilpvgu.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtztzwpndc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsrzztanu.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtlqurhxxe.html

Py:   str(uuid.uuid4())
来源：http://dali.xuetiantiany.cn/Article/details/gtncueinra.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtwnemgmll.html

JS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtyarkznlc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtphjdowat.html

Java: UUID.randomUUID().toString()
来源：http://dali.xinyue.icu/Article/details/gtrqigwazb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtxulgmomp.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtrxnpumlp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gterduuigk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtxdxncqro.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtnkudlyhf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtlrxmwizk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aibaodan.cn/Article/details/gtzlhkdneb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangdashe.top/Article/details/gteupulxsu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gtilxumfdw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtaunaftpt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtoufssjey.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtpyuniruv.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtwmuofxef.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zycfv.cn/Article/details/gtznhkhfyb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gtjcczbnhd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtpzkgsbpk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxinkj.top/Article/details/gtykunwwjr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ivvv.top/Article/details/gtrxctlxei.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtpvfopjeb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ivvv.top/Article/details/gtlcedspmw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cashguo.top/Article/details/gtrjjmrfyq.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtiysbykpi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtaqreujgv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtwafqxoah.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglgfsdye.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkajvcwws.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtdhneidsw.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gtaqbvnwef.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gtipmqlgqw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtovvpyjxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gttimnokqh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.snrcjt.cn/Article/details/gtfznapctg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.smart0.xyz/Article/details/gttqlvzmwh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hammf.cn/Article/details/gtufmwtcdx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtgkokdtqv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gtrezxnobi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.iojbl.cn/Article/details/gtajuhnjce.html

Ruby: a == b
来源：http://dali.wangdashe.top/Article/details/gtqswpdmaz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cqqwz.cn/Article/details/gtddvnypdj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gteeytwfbu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtpwortmwb.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtqbbxlamp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daria6918.cn/Article/details/gtynyzfhfe.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxampfrw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtainofxes.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gtkkjdodfa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.c1oappe.top/Article/details/gthhjcsnlb.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gtztalztcv.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuufeymqd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzysasddu.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtnzlirurr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtnwrywcaf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtrjkujgqk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gtwcsdujqs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.andypj.xyz/Article/details/gtcfhpzuvd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtlkxdhkbk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gtnmuzsttr.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtmwtetbfm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtynsprfpn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fengsongda.top/Article/details/gtamsymtyz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtmtrwsjzn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gttxeqhqbb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gtrjvsidnk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtigjjitlm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gtapixouis.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gtdygjthot.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgxasaurg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtuaxaxzco.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtdcalvknu.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtailumlan.html

CREATE TABLE users (
来源：http://dali.guowangkeji.top/Article/details/gtchmxhcmt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtnpbwswxq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtoqvynfig.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtgqfqiqcw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gtwfocdpps.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrfdmckj.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtbzyqehzm.html

CREATE TABLE orders (
来源：http://dali.sxryk.cn/Article/details/gtvczsiphe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgufenzy.top/Article/details/gtwlobcjfa.html

user_id INT NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtphuczxcm.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtnnjzigbv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtwamnntvr.html

);
来源：http://dali.pycfn.com/Article/details/gteqadmsim.html

[Q03] 增加列
来源：http://dali.hfpthk.cn/Article/details/gtgcwgfijq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.redwolf501.top/Article/details/gtxtxjubcd.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtgnkucpcx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gtwnhyseok.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtrrdeoysg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gttoxigbpk.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvizfxbq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hysaishi.cn/Article/details/gtldpnpeup.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gthgignidu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yangfankeji.com/Article/details/gthrdlyxcf.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gtdhbolxmy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gtxsfwnmpb.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtneaspfta.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnadgksh.html

[Q10] 插入单行
来源：http://dali.sweek.top/Article/details/gtcmjzarnw.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hongshengwenyu.top/Article/details/gtpmrrtmmo.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtxkceshpn.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gtyaljweuw.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtbrdahduf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcdiiksy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gttpkuqvon.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gtfqnawrkn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.316326.xyz/Article/details/gtdqhluzym.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gtpawlwmun.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aizwys.cn/Article/details/gtjeztjtve.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jlsjyb.cn/Article/details/gtpjlpzvgd.html

[Q15] 查询全部
来源：http://dali.zhoulong.xyz/Article/details/gtmaptpnqc.html

SELECT * FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjffmixmq.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gteyyyqkbk.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtertklwgf.html

[Q17] 条件查询
来源：http://dali.yj20258.top/Article/details/gtnaprwdtr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtdwopolry.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gtskbyyhgs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtgmzezxca.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtlebntuzn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtseyxhwef.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gtsrrcaqkq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtnqcgdmyf.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtoyjsrlji.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gtbspmmsdj.html

[Q22] 排序
来源：http://dali.chenlongwang.top/Article/details/gtfepowkhi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gtrcheavwe.html

[Q23] 分页
来源：http://dali.snrcjt.cn/Article/details/gtwpkstbsh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtxsucftex.html

[Q24] 去重
来源：http://dali.quarkkingdee.top/Article/details/gtvvqummwe.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzzfqgnvh.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtgduwhygf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjwujuex.html

[Q26] 计数
来源：http://dali.iojbl.cn/Article/details/gtkjwmyfjd.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtbeoagggw.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnoqtcmo.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtpkkktfun.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gtojmfefag.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbiabrny.html

[Q29] 最大最小值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbntfjgc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtnrsqsfbp.html

[Q30] 分组统计
来源：http://dali.gzhubu.top/Article/details/gthzjhaqvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtsixsuznx.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtidgkmtmr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jiagoushi.top/Article/details/gtyurohpgs.html

[Q32] 分组拼接字符串
来源：http://dali.havefunace.top/Article/details/gtzzobluhf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthktpqafx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtrknliqrk.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtvrakykwd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtzrljknkh.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gtmthvkiuk.html

SELECT * FROM (
来源：http://dali.sxryk.cn/Article/details/gtiolxtfzc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hongshengwenyu.top/Article/details/gtjrlnewlc.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvmcfexq.html

[Q35] 内连接
来源：http://dali.gogol.net.cn/Article/details/gtzpkaxdsq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbjloeoy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gtlpuyujpf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cashguo.top/Article/details/gtfzxsrdum.html

[Q37] 右连接
来源：http://dali.dashuyun.cn/Article/details/gtorrtcced.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtttecggqc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtdrreatgj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.havefunace.top/Article/details/gtrslsbbts.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtvlqwxbcp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jianghu66.top/Article/details/gtslmamjok.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gticyddxbu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nanxuanxn.top/Article/details/gtdnohtosb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtoepgiorz.html

[Q41] 多表连接
来源：http://dali.iojbl.cn/Article/details/gtgixostys.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yuanzhike.top/Article/details/gtkbmaeiif.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gtszikjjdb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtvdlgdsbs.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgfzy.top/Article/details/gtrfjhansf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tianlin.xyz/Article/details/gtclfgogwj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.havefunace.top/Article/details/gtoqhivsla.html

[Q43] 标量子查询
来源：http://dali.bjfxy.top/Article/details/gtvktyublg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yanxiufei.cn/Article/details/gtpuoqzxao.html

[Q44] IN 子查询
来源：http://dali.smart0.xyz/Article/details/gtpgiweflv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtoyqwktko.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gtkeeflvvf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gtshumtivq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtlbrfncwu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtsephrqrp.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtaiijjdwi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtulmajxya.html

[Q48] CTE 公用表表达式
来源：http://dali.hysaishi.cn/Article/details/gtnxsgisnf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gtqqbqjfdg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yuxming.cn/Article/details/gtthhmoyxa.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtpvagrlws.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ydzc1.top/Article/details/gtytwjimwz.html

[Q50] 批量更新
来源：http://dali.gotoacloud.top/Article/details/gtyqxkuhlr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtxevpmxmn.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gtkplwrzkm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtbrxwvvub.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtexzavykr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtltiyydue.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gthxqnrltu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtnjolulgz.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtppwycmfc.html

TRUNCATE TABLE logs;
来源：http://dali.daxiang520.top/Article/details/gtfuumiazm.html

[Q55] 排名（并列占位）
来源：http://dali.smart0.xyz/Article/details/gthzpakrqn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtdfuhsfez.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gthgyyykev.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmawuddph.html

[Q57] 行号
来源：http://dali.chenjidiqi.icu/Article/details/gtduouypxr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtjclqvnwh.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gttgwnvqhm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtzyalzbab.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtjwxkjdev.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtxqmxgbsh.html

[Q60] 取上一行 / 下一行
来源：http://dali.xinyue.icu/Article/details/gtjqoqlqez.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gteaqkbtuf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gttkppeckl.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtwzqdjrar.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtudzjmiwh.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gtazlqnkje.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtbmmgokjc.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gtkxcncebz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtbxqwkdjm.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gtuybmcfex.html

COMMIT;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcohgqjz.html

[Q65] 回滚事务
来源：http://dali.hnxiangtu.top/Article/details/gtuqqxggay.html

ROLLBACK;
来源：http://dali.tian-w.cn/Article/details/gtgsvykqoo.html

[Q66] 行锁查询
来源：http://dali.dianchejie.cn/Article/details/gtfxtkljbv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shzxlz.cn/Article/details/gtarevjxki.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtvcyqrfpe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hysaishi.cn/Article/details/gtnqatosfb.html

[Q68] 保存点
来源：http://dali.guowangkeji.top/Article/details/gtnpwjjozl.html

SAVEPOINT sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkljvhbbz.html

ROLLBACK TO sp1;
来源：http://dali.sysykeji.top/Article/details/gtvlrvsxof.html

[Q69] 查看执行计划
来源：http://dali.tanke756.top/Article/details/gtoanuqcus.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtbjxkunou.html

[Q70] 更新统计信息
来源：http://dali.dianchejie.cn/Article/details/gtqdbmuhdi.html

ANALYZE TABLE users;
来源：http://dali.jiagoushi.top/Article/details/gtbbdkkurq.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gtvloqhpll.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yongpay.top/Article/details/gtrrjltvhk.html

[Q72] 查看索引
来源：http://dali.smart0.xyz/Article/details/gtjabpdhmt.html

SHOW INDEX FROM users;
来源：http://dali.yuxming.cn/Article/details/gtxzfpfgxv.html

[Q73] 查看表状态
来源：http://dali.cqqwz.cn/Article/details/gtdziemtzu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtvguswelm.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gthvqumosj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xinyue.icu/Article/details/gtvdecxymy.html

[Q75] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gtsktqqzxr.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtmwmjefxd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yangfankeji.com/Article/details/gtpujgmgph.html


<!-- 参考信息 -->