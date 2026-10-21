代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtqkhznkua.html

Go:   go f()
来源：http://dali.aizwys.cn/Article/details/gtnmodpelg.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtukqlhqjb.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtzynknscr.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtwvheibnc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctgvmyyk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gtecvgyuci.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtnubsjuyx.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtbqhdjrvn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtlhprqohk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gtbcrioidp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nanxuanxn.top/Article/details/gtdzlnwpte.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkajxvnlw.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtrkeftepm.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gtwiewjayf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtqmoooren.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.316326.xyz/Article/details/gtlzaycpvj.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtoanljsav.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gthgttcehe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gtrdfpbvql.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gtgueivosn.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtmhddhhzt.html

[O04] 定义异步函数并等待
来源：http://dali.yvedp.cn/Article/details/gtqblwclge.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gthjwjlqbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.316326.xyz/Article/details/gtykwvxial.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gtxjxaqwjc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtcuqnxlfn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtoubpgdng.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtucgootsv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtumsghrpf.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtoooixqkw.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtjdasxcll.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daria6918.cn/Article/details/gtnqnzekfl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gtkgzykmoe.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtccwhaqbk.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtzgcbxrqi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtxfmsjmay.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gtiewvxgzk.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gtxctaruqo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.andypj.xyz/Article/details/gthpuaxitg.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtakrkpuyp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtamcaurac.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gtmgrzciiz.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtklwgpbfa.html

TS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtuqbkybuk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtpeujxheh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtxzdtdwzj.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtzheymekg.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gteyfiraet.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvkozntle.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfccwthda.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtloueikcg.html

[P01] 生成 UUID
来源：http://dali.cdnleiting.top/Article/details/gtyzjcflhw.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtquzpqkrw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtlhzhrnwy.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtbxzvsiwz.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtnnwugfby.html

Java: UUID.randomUUID().toString()
来源：http://dali.pengpengdd.cyou/Article/details/gtclocplnv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtyurprlyc.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtlnioudnd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tianlin.xyz/Article/details/gtnxlbjqej.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtiwxtzdtf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sxryk.cn/Article/details/gtcetptnii.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gtsiytkyjf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtahootylb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gttnmahgqx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvtdhzzs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gtzbdyedjb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ivvv.top/Article/details/gtmzloxtgu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pengpengdd.cyou/Article/details/gtjpuowaoa.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtksjzrbvi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtpsrekptc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jlsjyb.cn/Article/details/gtsxkeosvo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gttinyrsaf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gtynarlbak.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtpkrdjcra.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj202588.top/Article/details/gtdtztcohk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yanxiufei.cn/Article/details/gtobdrqaap.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtkhcagbyh.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gtnhfsvhzf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yanxiufei.cn/Article/details/gtnkcqohai.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtmsfahdxa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtspcbjakz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gtquhaoepe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtutkvnwdu.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtjudikute.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gtmilcoghm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtjpqeshvd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangdashe.top/Article/details/gtcbwkjgpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnpzmnrv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gzhubu.top/Article/details/gtcmzshkin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtwdwttadb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ivvv.top/Article/details/gtrxpapbrb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hammf.cn/Article/details/gtmrbxkdfx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtlqmvdcxt.html

Ruby: a == b
来源：http://dali.meibo888.top/Article/details/gttjxyvsto.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtgoyvnhzm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gtgvlfvrqy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkitcept.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gtbzzdtzre.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtsbrfydny.html

TS:   if (x == null) {}
来源：http://dali.yuxming.cn/Article/details/gtsgaucouh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtsixyhkrh.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gtashdglrg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sufxvd.cn/Article/details/gtrrillced.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtguqjadtt.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaulgafup.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtjtukjrsl.html

PHP:  // 手写时间戳比较
来源：http://dali.9152youxi.cn/Article/details/gtypkcnxhj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gtjzkmyplc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtwkteesay.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtyqlwahin.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gtfmxvyajl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtreeoqtlf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigufen.top/Article/details/gtzvxaipig.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtokizdukf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.daria6918.cn/Article/details/gtpttlvxpd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gtzsukozgf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yueranfly.top/Article/details/gtejqddljp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtzzxhudqu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cdnleiting.top/Article/details/gtfjtedwlk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gaohongyu789.top/Article/details/gthfdqigym.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtezdqckem.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhongyouzk.top/Article/details/gtpbuzirhs.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtomeniusc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtfxkssafx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthmsrdlho.html

[Q01] 创建表
来源：http://dali.xinyue.icu/Article/details/gtdbhzkrbs.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtnicemwoi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpznummvv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtviooxzuw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nwbrower.top/Article/details/gtrhinflsb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtcrasmmkv.html

);
来源：http://dali.yangfankeji.com/Article/details/gtdlohbjzo.html

[Q02] 创建带外键的表
来源：http://dali.0kj1m.cn/Article/details/gterhxhqsq.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtxualtfrp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtfqeqbeds.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtifjwhaee.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gtrtbnmmez.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtizlxhvlp.html

);
来源：http://dali.svipenyu.cn/Article/details/gtdaaxuqjl.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gtkmmxxqii.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtqorwbwxb.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gttriuazop.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.birdmap.top/Article/details/gtxypovwer.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtbrhtaoxf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenzaomai.com/Article/details/gtaktdaojk.html

[Q06] 删除列
来源：http://dali.hfpthk.cn/Article/details/gthzvubujv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.tian-w.cn/Article/details/gtedfynttf.html

[Q07] 删除表
来源：http://dali.xziqi.cn/Article/details/gtgstjxvxm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gthjmniksc.html

[Q08] 创建普通索引
来源：http://dali.zycfv.cn/Article/details/gtqmbxtlyr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtitbdyrpz.html

[Q09] 创建唯一索引
来源：http://dali.cqqwz.cn/Article/details/gtdcyjtzjy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gtltxywgvp.html

[Q10] 插入单行
来源：http://dali.yvedp.cn/Article/details/gtarbdezjd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtsmzvsrda.html

[Q11] 一次插入多行
来源：http://dali.pengpengdd.cyou/Article/details/gtisybyzmi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gtjtpecwtw.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtcjrrkogf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtuhxfrnfe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.dianchejie.cn/Article/details/gtnvchjvfc.html

[Q13] 忽略重复插入
来源：http://dali.iojbl.cn/Article/details/gthjdhxtee.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtvvuzxsit.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtxrjxiwgd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtilbzcsex.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gttbqvfzwq.html

[Q15] 查询全部
来源：http://dali.chenlongwang.top/Article/details/gtveroltxz.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtuutwvztc.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gtaauphifn.html

SELECT id, name FROM users;
来源：http://dali.hammf.cn/Article/details/gtfcqobybb.html

[Q17] 条件查询
来源：http://dali.sweek.top/Article/details/gtivvpxife.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yueranfly.top/Article/details/gtwyouakag.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtrwbmlfkk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258.top/Article/details/gtaloocuqu.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gtzdleehhe.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.fzhhl.top/Article/details/gtbwflmjkk.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gtoadijyvp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.snrcjt.cn/Article/details/gtrgnvjcbr.html

[Q21] 空值判断
来源：http://dali.hammf.cn/Article/details/gtizternxk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtwhyudjva.html

[Q22] 排序
来源：http://dali.ydzc1.top/Article/details/gtdzqinruk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtlcsldxxb.html

[Q23] 分页
来源：http://dali.hysaishi.cn/Article/details/gtqzwvswsf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtvkzxbowt.html

[Q24] 去重
来源：http://dali.aibaodan.cn/Article/details/gtdrtinbuy.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtcwspledg.html

[Q25] 只取前 N 条
来源：http://dali.mhx1999.top/Article/details/gtzaqsaecc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtiqjnejvx.html

[Q26] 计数
来源：http://dali.ppjwa.cn/Article/details/gthvwwlkph.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtxychbadb.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtlsvgashx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtlnleuxwa.html

[Q28] 求和与平均
来源：http://dali.xziqi.cn/Article/details/gtraxlcyvc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gteqnadzel.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtlxyffhfq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtuxjhomvj.html

[Q30] 分组统计
来源：http://dali.vqdsnc.cn/Article/details/gtdjswvkjb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtygloznjk.html

[Q31] 分组后过滤
来源：http://dali.hywenlv.cn/Article/details/gtsdejjkgl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhiwuduotai.top/Article/details/gtpwhvxpdy.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnzyxszi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gtkcwrvlsu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuetiantiany.cn/Article/details/gtiysjrtwk.html

[Q33] 多列分组
来源：http://dali.dianchejie.cn/Article/details/gtofmljaps.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zycfv.cn/Article/details/gtpotvtfxg.html

[Q34] 每组取第一条
来源：http://dali.c1oappe.top/Article/details/gtrrefrgsk.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtmqbdxudh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhiwuduotai.top/Article/details/gtuoalbmzn.html

) t WHERE rn = 1;
来源：http://dali.wangdashe.top/Article/details/gtplefqpuz.html

[Q35] 内连接
来源：http://dali.andypj.xyz/Article/details/gtlymfoyrj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.dashuyun.cn/Article/details/gtrakkexnh.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gtwbxbatrn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtjgdcvesh.html

[Q37] 右连接
来源：http://dali.hongshengwenyu.top/Article/details/gttlewoyhn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtpdafbbqa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gtsuhxafoj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zdqjudy.top/Article/details/gtcnejduqr.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtxhujbvoh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtnnbuvumb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtneyhcwis.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtwfopseup.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gtnvuvoffa.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtgcvajoat.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtjlpeyymt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuanzhike.top/Article/details/gtgoedptai.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gthfhswiki.html

[Q42] 连接条件附加过滤
来源：http://dali.zdqjudy.top/Article/details/gttjrqocdn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtddcqlqpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daxiang520.top/Article/details/gtrkwlcnxk.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gtsvbtfvoj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gtyurqxwzi.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gtnkzxhvup.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcmewzbk.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigufen.top/Article/details/gtgmzyvoiu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtmphxuunm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gtdblyqsrv.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtjrewfiyd.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtmrmthxih.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlobqdfiy.html

[Q48] CTE 公用表表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtoevpmbzc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gthrwzlroq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhoulong.xyz/Article/details/gtlfbahhyn.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtsabawlvs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj202588.top/Article/details/gtubrgqgek.html

[Q50] 批量更新
来源：http://dali.iojbl.cn/Article/details/gtffulvsfi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sysykeji.top/Article/details/gtmvwrplpr.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtpvcegcpg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtjkcchnie.html

[Q52] 删除指定行
来源：http://dali.xuetiantiany.cn/Article/details/gtkljpknfr.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yongpay.top/Article/details/gtxabmkzty.html

[Q53] 按条件删除
来源：http://dali.tanke756.top/Article/details/gtpmovgiku.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtroakflzk.html

[Q54] 清空表
来源：http://dali.yuanzhike.top/Article/details/gtfpgkmpay.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigufen.top/Article/details/gtshwmtinu.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtrzmkyriv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtvofskddd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.guowangkeji.top/Article/details/gthmolrrzj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtquruxakn.html

[Q57] 行号
来源：http://dali.redwolf501.top/Article/details/gtivzcsiau.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgcqlxbh.html

[Q58] 累计求和
来源：http://dali.pengpengdd.cyou/Article/details/gtwvxqvpea.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtozrgfdhy.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtkyotcwlk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gttarzgste.html

[Q60] 取上一行 / 下一行
来源：http://dali.zdqjudy.top/Article/details/gtenuxrevz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtrteppdla.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtrlaphhxl.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtbydlfanq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtnzstzkvk.html

[Q62] 分组占比
来源：http://dali.pengpengdd.cyou/Article/details/gtjvhhrnyq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.guannengcc.top/Article/details/gtdusirkpo.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtvngqkxdi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgufenzy.top/Article/details/gtyhfariyx.html

[Q64] 提交事务
来源：http://dali.chenlongwang.top/Article/details/gtratjvbza.html

COMMIT;
来源：http://dali.jlsjyb.cn/Article/details/gtphruaohz.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtqkjzzdqw.html

ROLLBACK;
来源：http://dali.yanxiufei.cn/Article/details/gtfqroiqne.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtycethnht.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqybtcbu.html

[Q67] 设置隔离级别
来源：http://dali.zhengqikj.top/Article/details/gtwsqjrasz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbkevsme.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtuajxirue.html

SAVEPOINT sp1;
来源：http://dali.zycfv.cn/Article/details/gtrqibiyor.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtywnnihrs.html

[Q69] 查看执行计划
来源：http://dali.chenlongwang.top/Article/details/gtnbldwkii.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj202588.top/Article/details/gtzeohlsvl.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtbjtwqkkv.html

ANALYZE TABLE users;
来源：http://dali.fzhhl.top/Article/details/gtvxfnrsxn.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtskvevcyj.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gtczpioncg.html

[Q72] 查看索引
来源：http://dali.yvedp.cn/Article/details/gtqgbwnteo.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtkrupuapq.html

[Q73] 查看表状态
来源：http://dali.guowangkeji.top/Article/details/gtfxhlblru.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cashguo.top/Article/details/gtlhtmzijt.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtbzhfqvft.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfersysvt.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gthmgihwwx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtkqyvkfks.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jyoumei.cn/Article/details/gtydymnkmd.html


<!-- 参考信息 -->