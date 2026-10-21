代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtsyeljfju.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtxaqmgdwi.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtmoarposs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.9152youxi.cn/Article/details/gtxkbnhjbc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtgtbhuvio.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtjvidqkey.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtthnbgqkr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtlqedwtgm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtpfxbuvng.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteybaevxt.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gthohklsvt.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gttkfmxnjl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxhnzywj.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtnkakhfdj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yongpay.top/Article/details/gtdzaetbri.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj202588.top/Article/details/gttvadynra.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtxpcpiipy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtprcozexg.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gtucktiiwz.html

[O05] 并发执行并等待全部完成
来源：http://dali.hfpthk.cn/Article/details/gtkxujvgrn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtghrtqxuh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gthtueortb.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlbteour.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtaspbrhjc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gtpmnmirln.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtdlcjvawc.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gthvhuebpo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtnfagngsg.html

[O06] 使用进程池
来源：http://dali.daria6918.cn/Article/details/gtqpmxkefp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtraxyisna.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtmkdxdcla.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtrrteyccj.html

TS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtjoodmhpv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.kuanghao11.cn/Article/details/gtnchmudzg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtxbvpslgc.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gtyfgabgbi.html

C#:   Parallel.For
来源：http://dali.9152youxi.cn/Article/details/gtpazrdyqa.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtogymcuwl.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtyqhyrbpf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfhfzgnqg.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gthkflyurf.html

Py:   str(uuid.uuid4())
来源：http://dali.yangfankeji.com/Article/details/gthjhswkzv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.smart0.xyz/Article/details/gtxltjryty.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtvamcucaf.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtabzoqgvg.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnqzz.top/Article/details/gthwiumocq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.quarkkingdee.top/Article/details/gtrdawtjgh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtxrggaqjv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtrhribxbg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtnxudwjsi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gtdkybiqti.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gtralipmam.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpxjskqy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gttohqlyyk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtjlgbphoi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtfqowsojb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtfnudomsr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtvlidzfvh.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtiowfxktw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gttpmnrlqb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gteedkflke.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtvpuvepwc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtummyoxdt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtaaaznoba.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtuzoiizgg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.316326.xyz/Article/details/gtesebduzq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtotmujulm.html

[P04] 求长度
来源：http://dali.tanke756.top/Article/details/gtzcbbthvc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtxgljntsu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtixpmqrin.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gtnzupftnx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtvfnvyuok.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gtqyqehyrz.html

Go:   len(arr);  len(m)
来源：http://dali.yueranfly.top/Article/details/gtbwezoakl.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtheybbwny.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yonumen.top/Article/details/gtauakyvjt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtwogtgsoh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gtexlzlabz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtlohcpkdu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gtmoguguqy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gteopezbxf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gtamsrxtde.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtxwdsyudu.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxadirui.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.aibaodan.cn/Article/details/gtbhtloxay.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsbvtlrs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gthhbhljqu.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtbqinario.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtfzxokdmd.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtuysoyaok.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtmoujkhqi.html

Go:   if x == nil {}
来源：http://dali.birdmap.top/Article/details/gttbgoljlk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jlsjyb.cn/Article/details/gtmfozxxvn.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtflbardjd.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtwzhwqqsk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtnjpbrlhf.html

PHP:  // 手写时间戳比较
来源：http://dali.shzxlz.cn/Article/details/gtbwbkqywi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtdlathgcv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtruzikbqg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gtfnjzjgca.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gtkntrvtar.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sysykeji.top/Article/details/gtplooyeuc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtzzfifmdm.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtguioilqu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yuanzhike.top/Article/details/gttjbbwynl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtfwiocxrg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtaavvuarn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtqclypudo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtnsajtcgp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yongpay.top/Article/details/gtanejpbup.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hywenlv.cn/Article/details/gtspnezoia.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtncpvwwhh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtucforlun.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hammf.cn/Article/details/gtmbusndxe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqzxmlvxo.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtvyddfyfc.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtlnuhwrlo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gtacghdhsm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gtgcxoaxbn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtgffscqrc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tanke756.top/Article/details/gtqpelxxwp.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlbxgqan.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtotjeyosv.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gthqimzcnj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkszpgpvq.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gtyyvzgnke.html

amount DECIMAL(10, 2),
来源：http://dali.sufxvd.cn/Article/details/gtpnvlurhh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtysptpxop.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyqusvbh.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtgguuitry.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gttxxpaccd.html

[Q04] 修改列类型
来源：http://dali.yj20258888.top/Article/details/gtesxulavu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtovytrnfo.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtnwmsvohm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gthixvxhmo.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtrsmuuwnh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.mhx1999.top/Article/details/gtggjuorte.html

[Q07] 删除表
来源：http://dali.chenzaomai.com/Article/details/gtmesmtsjv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gtwjfkmmcd.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gtnjmlpera.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtvhhoyzqc.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtmcqgqfcy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtsibakzju.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gtqvachgfn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jqgufenzy.top/Article/details/gtcvldybzu.html

[Q11] 一次插入多行
来源：http://dali.cheryme.top/Article/details/gtafkyigtw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtqqsravzi.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gtqegyrjwu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yangfankeji.com/Article/details/gtjawncxqv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtqdjecvio.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtqufvbjax.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xziqi.cn/Article/details/gtzxoixwwf.html

[Q14] 存在则更新（upsert）
来源：http://dali.gzhubu.top/Article/details/gtebsvfptg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gtmfbufdrb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gtxatiyxqt.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtwtonhvpf.html

SELECT * FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtqyntebkx.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtmiyoqcuz.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gtadkmpdta.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gtqqfiobci.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtppouvliq.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtrotcjwrw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gtwnaeoxjr.html

[Q19] 范围查询
来源：http://dali.yj20258888.top/Article/details/gtzhowptvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuvodbdk.html

[Q20] IN 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkudxsnp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtrpjaaunu.html

[Q21] 空值判断
来源：http://dali.chenlongwang.top/Article/details/gtzzkvsonm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.iojbl.cn/Article/details/gtecpywydj.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gtqfbfxvxo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hongshengwenyu.top/Article/details/gtfbsmciep.html

[Q23] 分页
来源：http://dali.sweek.top/Article/details/gtlsbyrrnu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtwnwrdzsm.html

[Q24] 去重
来源：http://dali.dashuyun.cn/Article/details/gtadzumzza.html

SELECT DISTINCT city FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvmujojzs.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gthmzhfhhl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.tanke756.top/Article/details/gtfhmebkkq.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtxcsjaain.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtraypwefi.html

[Q27] 条件计数
来源：http://dali.yanxiufei.cn/Article/details/gtdmxxqdpw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jianghu66.top/Article/details/gtsoicvati.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtkmemfmda.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gttdrvhmep.html

[Q29] 最大最小值
来源：http://dali.cashguo.top/Article/details/gtahixtsft.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ydzc1.top/Article/details/gtcpaggxgb.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtaoplcvhj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtsamqnezy.html

[Q31] 分组后过滤
来源：http://dali.havefunace.top/Article/details/gtkfgwxbsq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtpqbxkyut.html

[Q32] 分组拼接字符串
来源：http://dali.birdmap.top/Article/details/gtohxhoxjp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtrrmionbl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtpyubindd.html

[Q33] 多列分组
来源：http://dali.quarkkingdee.top/Article/details/gtcatnjzsn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gogol.net.cn/Article/details/gtnzvwjuht.html

[Q34] 每组取第一条
来源：http://dali.dianchejie.cn/Article/details/gtwhkhswos.html

SELECT * FROM (
来源：http://dali.cqqwz.cn/Article/details/gtcmgbbjit.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gtivcabycn.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtyswnyklc.html

[Q35] 内连接
来源：http://dali.tanke756.top/Article/details/gtvrhonegl.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtarcbywsk.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtynpdzbyr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sufxvd.cn/Article/details/gtidmexnxk.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gtpnsfnkoa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqinlpde.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtputonwyy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcsnflnv.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gtxbwmjmbn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenjidiqi.icu/Article/details/gtwnkxgxvj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gtjazxfjbj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yj202588.top/Article/details/gtaawpsegc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenzaomai.com/Article/details/gtnuvczsxa.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gtvmuautct.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.haohaochexian.top/Article/details/gtjhmmbbsn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtghhatbbr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dashuyun.cn/Article/details/gtefhxtowz.html

[Q42] 连接条件附加过滤
来源：http://dali.jiagoushi.top/Article/details/gtatnylkvu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtgsbuxcmj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yvedp.cn/Article/details/gtqzfxztlt.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gthkfirbgl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.vqdsnc.cn/Article/details/gtpsprlgkx.html

[Q44] IN 子查询
来源：http://dali.fzhhl.top/Article/details/gtforrkivq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sxryk.cn/Article/details/gtnszxwsma.html

[Q45] EXISTS 判断存在
来源：http://dali.mhx1999.top/Article/details/gtzeximokv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphejeyvq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxvdpacz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gtjphikiml.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtcptudums.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.pycfn.com/Article/details/gtrhghltvs.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtzwlscdix.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yueranfly.top/Article/details/gtzjebumtm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258.top/Article/details/gtdzobmuic.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gtltyiubpr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtyqlklkbz.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtoswbrawl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cheryme.top/Article/details/gtnisonijd.html

[Q51] 用子查询更新
来源：http://dali.hysaishi.cn/Article/details/gtmckiuxks.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hywenlv.cn/Article/details/gtbcecwqbd.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtaufuoljf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gtiwkpfgsk.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtanffsgru.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hammf.cn/Article/details/gtlaytiicj.html

[Q54] 清空表
来源：http://dali.hysaishi.cn/Article/details/gtbvsgicay.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gtdmtfsbzr.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gtjdmzezue.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhixingplan.top/Article/details/gttixxdvep.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtwcwkufil.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtzbwwiawe.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gttqhebsad.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yuxming.cn/Article/details/gtbyijhioy.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gtswyorfph.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtdtmgajan.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtxgxdgkhi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtxijakdqp.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gtgknbatiu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sweek.top/Article/details/gtycjlaiqn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtbgtttyqd.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtumrevzsx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtjuikcskr.html

[Q62] 分组占比
来源：http://dali.gogol.net.cn/Article/details/gtverwubds.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtujfhhwwd.html

[Q63] 开启事务
来源：http://dali.hongshengwenyu.top/Article/details/gtjlgfssgh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenlongwang.top/Article/details/gtdeglquvg.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtpswnasdp.html

COMMIT;
来源：http://dali.nwbrower.top/Article/details/gtzwyiphlf.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtwcgxlxka.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtwaeonxqu.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gthfyexvxh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aizwys.cn/Article/details/gtkuvfozpf.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtgticgkyj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gthiwmygxs.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqnfcyms.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtbayggvdr.html

ROLLBACK TO sp1;
来源：http://dali.birdmap.top/Article/details/gtkihsvhsw.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtiouhdkhh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtlbqltfom.html

[Q70] 更新统计信息
来源：http://dali.redwolf501.top/Article/details/gtrpzatinb.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtffzshnak.html

[Q71] 查看建表语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpjrxhqt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbrzhnua.html

[Q72] 查看索引
来源：http://dali.snrcjt.cn/Article/details/gtftxwgexx.html

SHOW INDEX FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrzwhrnz.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtrhaqhmws.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenjidiqi.icu/Article/details/gtmgdpdyfj.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtxmatqhrg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shanyushiyangtech.top/Article/details/gtxloexrzl.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtbhrcxloz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtmwgggzlw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenlongwang.top/Article/details/gtooxugmdm.html

[Q76] 按天统计
来源：http://dali.snrcjt.cn/Article/details/gtbdonider.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtkxgfrvtx.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gthiabjfwl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtkmrmkels.html

[Q78] 当前时间
来源：http://dali.ybcxt.top/Article/details/gtvqsqmkys.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.nwbrower.top/Article/details/gtzrrvxujj.html

[Q79] 字符串拼接
来源：http://dali.aizwys.cn/Article/details/gtgfeuywyu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpfrnmbu.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gthlvhikbo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtilicgqfp.html

[Q81] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gtgjagqmgt.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtvskbvwbh.html


<!-- 参考信息 -->