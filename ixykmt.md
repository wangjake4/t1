代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gtzajnczje.html

[O03] 加锁保护共享数据
来源：http://dali.quarkkingdee.top/Article/details/gtmkpkjcgq.html

Py:   with lock: shared += 1
来源：http://dali.yuxming.cn/Article/details/gtacylhjnq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtlucjwzbc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dianchejie.cn/Article/details/gtvndeedsg.html

TS:   // 同 JS
来源：http://dali.yuxming.cn/Article/details/gtauiaoxid.html

Java: synchronized (this) { shared++; }
来源：http://dali.jyoumei.cn/Article/details/gtspbedszy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtwicwsljq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeusrvzg.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtnyfwemma.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjzkyiwj.html

Py:   async def f():⏎    await g()
来源：http://dali.9152youxi.cn/Article/details/gtgvnturht.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtfuedbhvz.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrjxyrhk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtuvrnqcsc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtyxxwwoiv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cucudq.cn/Article/details/gtpftqglwd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guannengcc.top/Article/details/gtfyucxhbc.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtgrxfvypj.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtpucgwamb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtfvgwqjez.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gaohongyu789.top/Article/details/gtnkfkdpvc.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgfzy.top/Article/details/gteeyljzja.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtwaupkeus.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhongyouzk.top/Article/details/gtwhtaojuk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtkpszcsen.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtqfalyuaq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gtutzmnhxh.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gthcjecmdv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtwzmybzrm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtdtyuwoap.html

JS:   // child_process / cluster 模块
来源：http://dali.hnqzz.top/Article/details/gtfxnpikak.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtgsfdtlut.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtwdaxixwp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtbdaixllc.html

Ruby: // fork 块
来源：http://dali.yangfankeji.com/Article/details/gtutpjkxbf.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtygondytg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtajshispj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtfvhljxwb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwayadgsf.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtmvbtnvnz.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigfzy.top/Article/details/gttaahjcay.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yanxiufei.cn/Article/details/gtgthdrssw.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtzwyughzq.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gttxvsnsjx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgfzy.top/Article/details/gtgtoovies.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gtuqpdunxk.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gtcbsuqcoe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtuysyxbmw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtrisudmoh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gttiulaebe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtgxizqguf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ppjwa.cn/Article/details/gtkuwvtohm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtjcovqosd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.aizwys.cn/Article/details/gtxqxshvxl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtwbqzqkki.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtnjznwwle.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotxckcjo.html

[P03] 生成短随机字符串
来源：http://dali.havefunace.top/Article/details/gtwishnkik.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtxjnuzafj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtgkkqpefq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtbbzrifkz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gtczwawbyy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtpjptkajd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtihluqrkn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtgdalupsi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hfpthk.cn/Article/details/gtcqipdzfp.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtgxkoorhh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gtsrvnckgq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtxalejwfm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtyhlfayhy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtuacimhlc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fzhhl.top/Article/details/gtrsvuszhw.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtatufjdhn.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtgawanbcb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtqtefahaj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cashguo.top/Article/details/gtnpfikppi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyzboavj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gthoqvgxrs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtjxgilgkk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtqlvvlsnr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gtclzahacz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtxwsypwwf.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtaofmxgrh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gaohongyu789.top/Article/details/gtfqugvvwq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtcigvpsgn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtkomebvjx.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gturerroav.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtkxqxfowu.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtrneubaly.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gtzwxswsvu.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtkhfvlsun.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dashuyun.cn/Article/details/gtutxmiali.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzidrpkiu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gtlkwwdcsf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hywenlv.cn/Article/details/gtvchhhdnf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtmnvhymqy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gturthummt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtjhzqgzmy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsxdfpqzt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuprhypfz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtrutdhios.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tianlin.xyz/Article/details/gtxgxmczep.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gthbksppjn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgufenzy.top/Article/details/gtivkupgiw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tanke756.top/Article/details/gtxfzctrii.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigufen.top/Article/details/gtypicahdo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtxxpsymou.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tianlin.xyz/Article/details/gtykfzcbom.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtusxmyjuc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hammf.cn/Article/details/gtdxzxflyz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtyffjjpup.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgxpoazcx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtakjksmno.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfegzloel.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtylzhjtdp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtwmtodbnk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtrjtrcwqk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtnbywljvp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jlsjyb.cn/Article/details/gtygxbeqzm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zycfv.cn/Article/details/gtqmlwtflr.html

);
来源：http://dali.sxryk.cn/Article/details/gtykndoaam.html

[Q02] 创建带外键的表
来源：http://dali.mhx1999.top/Article/details/gtjwnidxab.html

CREATE TABLE orders (
来源：http://dali.zhengqikj.top/Article/details/gtyaoxturn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gtznwdhdav.html

user_id INT NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtrovaskxf.html

amount DECIMAL(10, 2),
来源：http://dali.zdqjudy.top/Article/details/gtdnllekhd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jianghu66.top/Article/details/gtcqjdvhwh.html

);
来源：http://dali.yonumen.top/Article/details/gtdtntoryu.html

[Q03] 增加列
来源：http://dali.yuanzhike.top/Article/details/gtlwnfdplw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtlvljwnvp.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtftfkmdrz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtgzsujoof.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gtxvblwzfh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gtiablnxzl.html

[Q06] 删除列
来源：http://dali.tian-w.cn/Article/details/gtcmlrbxmz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqaswulh.html

[Q07] 删除表
来源：http://dali.jianghu66.top/Article/details/gthplvsdos.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xinyue.icu/Article/details/gtwvngrbrp.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gthphgpeai.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gttizyqvyu.html

[Q09] 创建唯一索引
来源：http://dali.chenlongwang.top/Article/details/gtfhgelcqh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gttjijgdvv.html

[Q10] 插入单行
来源：http://dali.xylfe.cn/Article/details/gtzjnfjkfi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtownrwbap.html

[Q11] 一次插入多行
来源：http://dali.yangfankeji.com/Article/details/gtqyzmwypw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtmlvhyqbh.html

[Q12] 插入后取自增 ID
来源：http://dali.bjfxy.top/Article/details/gtwjhhjnso.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tanke756.top/Article/details/gtguthijxz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.snrcjt.cn/Article/details/gtunujeiop.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtdfoufqow.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtfzzrkxxm.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtbiwmtqaf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sufxvd.cn/Article/details/gtnnbsnmww.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.9152youxi.cn/Article/details/gtnzycpydt.html

[Q15] 查询全部
来源：http://dali.yonumen.top/Article/details/gtvtocollo.html

SELECT * FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtdpmcedqt.html

[Q16] 查询指定列
来源：http://dali.zhixingplan.top/Article/details/gtyguzzybn.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtbedmxulm.html

[Q17] 条件查询
来源：http://dali.fengsongda.top/Article/details/gthnjgwjjg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cucudq.cn/Article/details/gtoubupbbq.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtxfwjpjes.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtyeadbybs.html

[Q19] 范围查询
来源：http://dali.zhengqikj.top/Article/details/gtqlpdeiad.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtrdpledxd.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gttfxiwwdf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gtwdmuutsi.html

[Q21] 空值判断
来源：http://dali.guowangkeji.top/Article/details/gtpclqbugd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtkqnzfnrw.html

[Q22] 排序
来源：http://dali.vqdsnc.cn/Article/details/gtvpgcffoz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.daria6918.cn/Article/details/gtqqcjxter.html

[Q23] 分页
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpphugipv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.316326.xyz/Article/details/gtqyjbdwvm.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmxdymfi.html

SELECT DISTINCT city FROM users;
来源：http://dali.316326.xyz/Article/details/gtqsmkrecd.html

[Q25] 只取前 N 条
来源：http://dali.ydzc1.top/Article/details/gtdfikpxqz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhixingplan.top/Article/details/gtwrenresu.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtoxabubre.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258.top/Article/details/gthweqashk.html

[Q27] 条件计数
来源：http://dali.0kj1m.cn/Article/details/gtluwegwky.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnwgwjxdu.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gthcngsvlp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtngjeyqyj.html

[Q29] 最大最小值
来源：http://dali.birdmap.top/Article/details/gtvigwdayf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtqwvvizky.html

[Q30] 分组统计
来源：http://dali.gotoacloud.top/Article/details/gtwwmijhpg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtdkhjxhpi.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gtjnxmqoyg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gtumhijwag.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtlpgskieh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtzzvftowj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtvxpccczu.html

[Q33] 多列分组
来源：http://dali.shangyingyoupin.top/Article/details/gtksvrfkik.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtvhjojpxx.html

[Q34] 每组取第一条
来源：http://dali.smart0.xyz/Article/details/gtowlikhzs.html

SELECT * FROM (
来源：http://dali.pycfn.com/Article/details/gtufcvznip.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gtsuagxarx.html

) t WHERE rn = 1;
来源：http://dali.9152youxi.cn/Article/details/gthaeyqtki.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtvvspuqxf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtuheyiisw.html

[Q36] 左连接
来源：http://dali.jiagoushi.top/Article/details/gtdpsrswhb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtknpbzixa.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtacwipyjq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cashguo.top/Article/details/gtngarawzf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuanzhike.top/Article/details/gtnpopmkgd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnxiangtu.top/Article/details/gtxbeayhqv.html

[Q39] 自连接（查上下级）
来源：http://dali.dashuyun.cn/Article/details/gttwaphqqh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.iojbl.cn/Article/details/gtlxvuxhqh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gtonednuex.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqiuyhnd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxinkj.top/Article/details/gtbcjuasof.html

[Q41] 多表连接
来源：http://dali.gotoacloud.top/Article/details/gtxitjebkr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtfnsyuzjh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.aizwys.cn/Article/details/gtfolfmeli.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtpfvscijw.html

[Q42] 连接条件附加过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepndoasi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gtrdtqdxym.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuanzx.com/Article/details/gtcabmyrea.html

[Q43] 标量子查询
来源：http://dali.guannengcc.top/Article/details/gtzwlikozf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdpvnlgi.html

[Q44] IN 子查询
来源：http://dali.ehwqpu.com/Article/details/gtlfscfgbw.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.wangshuangyany.cn/Article/details/gtkwsbugor.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtzdiodxqn.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtggzaqtsc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gtatolhutn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gttkaxwheo.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtziuphosx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtdxjdpmur.html

[Q48] CTE 公用表表达式
来源：http://dali.wangdashe.top/Article/details/gtmybnstuw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gtojymgdew.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cucudq.cn/Article/details/gtinnwxbqe.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtehbwwfnj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmktitbnh.html

[Q50] 批量更新
来源：http://dali.nanxuanxn.top/Article/details/gtbzuvebof.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtbdlmepwn.html

[Q51] 用子查询更新
来源：http://dali.shangyingyoupin.top/Article/details/gtlinusdom.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dianchejie.cn/Article/details/gtqtzptfew.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtojgqzzwf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtugyveoxk.html

[Q53] 按条件删除
来源：http://dali.sufxvd.cn/Article/details/gtzsvtlezz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gttlnnvfnd.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtoakyghhx.html

TRUNCATE TABLE logs;
来源：http://dali.vqdsnc.cn/Article/details/gtvistypwl.html

[Q55] 排名（并列占位）
来源：http://dali.zhoulong.xyz/Article/details/gtjxlydnfv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtkspugdsx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hysaishi.cn/Article/details/gtfwanuyzd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtmpkzigxc.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gtkmwjiekv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jyoumei.cn/Article/details/gteksnddmj.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gtzbkfwcjc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtcyxejegc.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtdkascvsd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtvrvdbahb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gtkvnejxnf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtzaqlygay.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gtbtutanto.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtbbsvcaep.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtzogdpwzb.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtedzxtktg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtwnjlaemz.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtlvrsdwkr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.daxiang520.top/Article/details/gtpjcrwqzr.html

[Q64] 提交事务
来源：http://dali.yj20258888.top/Article/details/gthldgdgiu.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gtalunikyd.html

[Q65] 回滚事务
来源：http://dali.chenzaomai.com/Article/details/gtrdlvxycl.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtyhzyhztr.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtbmrayesm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xuetiantiany.cn/Article/details/gtaolpjgmz.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtqrsuiwuf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yongpay.top/Article/details/gtfzptiwah.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtqiguspzj.html

SAVEPOINT sp1;
来源：http://dali.dashuyun.cn/Article/details/gtayjixbwz.html

ROLLBACK TO sp1;
来源：http://dali.yangfankeji.com/Article/details/gtsihszaqu.html

[Q69] 查看执行计划
来源：http://dali.c1oappe.top/Article/details/gtspuggvsv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gthrthwhdq.html

[Q70] 更新统计信息
来源：http://dali.sysykeji.top/Article/details/gttxoknxdz.html

ANALYZE TABLE users;
来源：http://dali.jinqigufen.top/Article/details/gtgbnppvmp.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtiawyuzuc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwarbswwf.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gtyhmevxvf.html

SHOW INDEX FROM users;
来源：http://dali.andypj.xyz/Article/details/gtnfwdfkxe.html

[Q73] 查看表状态
来源：http://dali.cdnleiting.top/Article/details/gthjddobhs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinghuilouyu.cn/Article/details/gtvthcoclj.html

[Q74] 强制使用索引
来源：http://dali.kuanghao11.cn/Article/details/gtoolkevbp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtilxfwcqj.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtwrvsjwdn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtpvnqjorr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gtprtqjrqj.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtpsmloadk.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuanzhike.top/Article/details/gtihzfultk.html

[Q77] 时间加减
来源：http://dali.yj20258888.top/Article/details/gtezmymxsq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtmkmmixfz.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gtqjgfbcjo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aizwys.cn/Article/details/gtfcphtnrp.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gttscwswxg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hnxiangtu.top/Article/details/gtrsbutwnu.html

[Q80] 字符串截取
来源：http://dali.guowangkeji.top/Article/details/gtsdgckssm.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj202588.top/Article/details/gtykusicwy.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtafdblbxz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gtbnvqrtup.html


<!-- 参考信息 -->