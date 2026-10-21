代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtbjqcqrou.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtersdahol.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtehnfvotf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yueranfly.top/Article/details/gtxujzklkm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtkwmgvddg.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtqlxdiazh.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtlkwacdhs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtujbnglrr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtlrbvylve.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gtfqoucjnf.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtifldmllg.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gthtwebahh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtxuxmkooo.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gtrdpadcyf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gturhteyou.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gtzxbycdfq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenlongwang.top/Article/details/gtvnswtexv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtpbiiknoi.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtjfnrdhij.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtnqwnlklh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hysaishi.cn/Article/details/gtxinchhgj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.0kj1m.cn/Article/details/gtyaetggvc.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtsrycbqhq.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtxqfltrcu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gtcntvwclv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gtwyolmsni.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gtwndhcsai.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtiadfrcox.html

[O06] 使用进程池
来源：http://dali.cashguo.top/Article/details/gtknyjwcgl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258.top/Article/details/gtwnppllgo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtxtmqxvrw.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpekjctuc.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtlxymjowv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtjngrfrum.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtkqdnbedq.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtsrzdxnio.html

C#:   Parallel.For
来源：http://dali.cheryme.top/Article/details/gtwpqbfton.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtzdkqirke.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtyfsfyegk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtvwxmngvz.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtfkleurxh.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gtbhuselbf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jiagoushi.top/Article/details/gtajgyrfnq.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtxttqbwdd.html

TS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidesqjpz.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtqajsewhf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtrkgekxsg.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtlnddzcxy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtbxiozpgd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gtwtlandtx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtcnefyjls.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtetmbksci.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sufxvd.cn/Article/details/gtobllrocz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtewregntn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gtfsxitcvr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xziqi.cn/Article/details/gttbzgyrmx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtdotvurmj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gttgjczttl.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtthhuxjlt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtcunngevd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guowangkeji.top/Article/details/gtktwtgrpl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gthpbljhdw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtszorgsre.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtmuzlwgua.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtaappczrx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gthyrlauby.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtpivsnkqe.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtrdharfct.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenzaomai.com/Article/details/gtzadrykqs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtixkrrflc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtkqydopzg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtrxbkvelk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtxqdzsyfw.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtwdbryjoz.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtdsthwzdb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gtcayzchlw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gthffzpqka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gtaznguzvs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cashguo.top/Article/details/gtfeggmvvm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fzhhl.top/Article/details/gtwenqepmn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuekvutl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tian-w.cn/Article/details/gtpbiafeoj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtqevbzdgw.html

Ruby: a == b
来源：http://dali.tian-w.cn/Article/details/gtnmpdsjlm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gttdltgjao.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtmaafqbuf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gtraumcujd.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivcaflza.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtqfzjuuul.html

TS:   if (x == null) {}
来源：http://dali.meibo888.top/Article/details/gtzyadmtuj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtrykmycst.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtnlhpuycz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuofoylx.html

C#:   if (x is null) {}
来源：http://dali.c1oappe.top/Article/details/gtwvczlodg.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gtbskmvgvh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtkudlvpvm.html

PHP:  // 手写时间戳比较
来源：http://dali.jlsjyb.cn/Article/details/gtsoeltvyb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtwlmaheuj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtegyindad.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtmdyrbwbh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daria6918.cn/Article/details/gtvnoepbzt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtpnkgdblr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gzhubu.top/Article/details/gtntptkewt.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtuptitnsz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hammf.cn/Article/details/gtqkmkfxkf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtqhpzmitt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.redwolf501.top/Article/details/gtyhppkyvo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtitbueqqh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtojyraxfc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtmaysqhxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtidvkopqs.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jianghu66.top/Article/details/gtrrsloraz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthfpdfknu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zdqjudy.top/Article/details/gtzmkavpjs.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcoahzwt.html

[Q01] 创建表
来源：http://dali.gotoacloud.top/Article/details/gtydibsiep.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gthctymale.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gtibbqeoxf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtcsvaafso.html

email VARCHAR(100) UNIQUE,
来源：http://dali.bjfxy.top/Article/details/gtexjbkwhj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgncdzqph.html

);
来源：http://dali.hammf.cn/Article/details/gttnerlmjg.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtccvruhci.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gtsnkkjcbv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtwyzhfgud.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtoyvnjgzo.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtdlgdvxzy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenjidiqi.icu/Article/details/gthqvlqggk.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrdjbwej.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtihyipalq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtonsdgcqv.html

[Q04] 修改列类型
来源：http://dali.gotoacloud.top/Article/details/gtqjlpiehp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtwtlegnlb.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtdrmiubcx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.bjfxy.top/Article/details/gtjumoknfn.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtchyndsuo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrdjkwtj.html

[Q07] 删除表
来源：http://dali.tianlin.xyz/Article/details/gtqljprudo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjntohwyv.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gtilmbohxq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgufenzy.top/Article/details/gtryeyfsez.html

[Q09] 创建唯一索引
来源：http://dali.daxiang520.top/Article/details/gticfqmpqi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtxbhkenao.html

[Q10] 插入单行
来源：http://dali.gaohongyu789.top/Article/details/gtbswdlaei.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sxryk.cn/Article/details/gtpurkwmco.html

[Q11] 一次插入多行
来源：http://dali.guowangkeji.top/Article/details/gtstvhqcpu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ehwqpu.com/Article/details/gtjllagrlk.html

[Q12] 插入后取自增 ID
来源：http://dali.tian-w.cn/Article/details/gtfvsgzaea.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cdnleiting.top/Article/details/gtrtabmyys.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.guowangkeji.top/Article/details/gtrzccmxkx.html

[Q13] 忽略重复插入
来源：http://dali.ppjwa.cn/Article/details/gtvkrsmhmd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gtveietriu.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuanzhike.top/Article/details/gtgpqkukor.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtzeicvcbw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gtmratgthy.html

[Q15] 查询全部
来源：http://dali.aizwys.cn/Article/details/gthtckmcff.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtkpzpezew.html

[Q16] 查询指定列
来源：http://dali.wangdashe.top/Article/details/gtnbnaniur.html

SELECT id, name FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtblxhhqwu.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtipapcuvr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gtnvmvjzce.html

[Q18] 模糊匹配
来源：http://dali.hywenlv.cn/Article/details/gtqpxzbqvm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gtftwzopoy.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gtkrzllzkw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtqpuolygp.html

[Q20] IN 列表
来源：http://dali.svipenyu.cn/Article/details/gtybocoakx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gtllnsomye.html

[Q21] 空值判断
来源：http://dali.xuanzx.com/Article/details/gtrmxjlpqv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.chenzaomai.com/Article/details/gtqchlemey.html

[Q22] 排序
来源：http://dali.gaohongyu789.top/Article/details/gtrrtjiodj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsiqljou.html

[Q23] 分页
来源：http://dali.sxryk.cn/Article/details/gtbvivzfgj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtocawkyqp.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtrxdtowzk.html

SELECT DISTINCT city FROM users;
来源：http://dali.ehwqpu.com/Article/details/gttlejuhzc.html

[Q25] 只取前 N 条
来源：http://dali.316326.xyz/Article/details/gtxajlgwsw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtanfikefe.html

[Q26] 计数
来源：http://dali.dianchejie.cn/Article/details/gtwomzegdb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtoqyknaqi.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtfpiybgqw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtrxpcegnb.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtcfleogci.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258.top/Article/details/gtybhsvhpy.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gtrjbgonip.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtamicoiyw.html

[Q30] 分组统计
来源：http://dali.xuetiantiany.cn/Article/details/gtjewvnped.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtyhbvttfy.html

[Q31] 分组后过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtppmnsmdd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtsvzorxai.html

[Q32] 分组拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtxayhanzp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gtwyyzifra.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangdashe.top/Article/details/gtjygmeftc.html

[Q33] 多列分组
来源：http://dali.gotoacloud.top/Article/details/gteyhrybln.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtjkjgrkfa.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gttywswmna.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzwwpspp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtmfsakmou.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtlrzgjwnu.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtltttolul.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gtxdbvszbi.html

[Q36] 左连接
来源：http://dali.gotoacloud.top/Article/details/gtwhclrdyc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtcrbayssr.html

[Q37] 右连接
来源：http://dali.sxryk.cn/Article/details/gtfbtnbrea.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtergikphg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tianlin.xyz/Article/details/gtihshtfwv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtwidwymvd.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtesvlmimq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvhwjvaw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyepzazjz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngdavmdc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtjcewtnyf.html

[Q41] 多表连接
来源：http://dali.zhixingplan.top/Article/details/gtmysxcibo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtpipadvtj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtgmyhebtm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yongpay.top/Article/details/gtyqoxneqq.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtgogsfzhi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtwekljyme.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfoastjg.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gthwibvtmh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgufenzy.top/Article/details/gtejhjqtby.html

[Q44] IN 子查询
来源：http://dali.gotoacloud.top/Article/details/gtfovakcad.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gttwxbfhoq.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyclzjzm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gotoacloud.top/Article/details/gthrboddry.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gttjuxumva.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shuidangran.top/Article/details/gtlynkkfld.html

[Q47] 与平均值比较
来源：http://dali.hywenlv.cn/Article/details/gtkvmiysdj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gtwlybqmze.html

[Q48] CTE 公用表表达式
来源：http://dali.shuidangran.top/Article/details/gtmjsgtsmw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gtrxlyqdxt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gtrlvzerzq.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtdtnbvcln.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtenbhhgwn.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavknfwko.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gtxhytmzkj.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gtoslexquk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtkejgzwcs.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtonleidss.html

DELETE FROM users WHERE id = 10;
来源：http://dali.bjfxy.top/Article/details/gtfgbsiqxi.html

[Q53] 按条件删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmspactw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmurbmtq.html

[Q54] 清空表
来源：http://dali.cashguo.top/Article/details/gtzsjnsjpo.html

TRUNCATE TABLE logs;
来源：http://dali.bjfxy.top/Article/details/gtdmiywpqr.html

[Q55] 排名（并列占位）
来源：http://dali.yvedp.cn/Article/details/gtkbxjifon.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gtxwykzqwi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtftnrmirb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekxjytrq.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtyadkiaxp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gteyktqyaw.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtmprzxqra.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtxtafhtvp.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gtrmkxbmim.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtjjkzzdkw.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtrrifruoo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yueranfly.top/Article/details/gtfhbzrgku.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtaovfdlfr.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtctaecrjm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gthaidsafa.html

[Q62] 分组占比
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtbueurn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtdbakzfdl.html

[Q63] 开启事务
来源：http://dali.havefunace.top/Article/details/gtltttrcyy.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhixingplan.top/Article/details/gtrqqradwo.html

[Q64] 提交事务
来源：http://dali.meibo888.top/Article/details/gthlmsjyui.html

COMMIT;
来源：http://dali.birdmap.top/Article/details/gtyetroyns.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtibzfnswe.html

ROLLBACK;
来源：http://dali.gzhubu.top/Article/details/gtwuweibou.html

[Q66] 行锁查询
来源：http://dali.jlsjyb.cn/Article/details/gtdzrwupbx.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxuanxn.top/Article/details/gtxnlkhatg.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gtxkgdzmfp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ybcxt.top/Article/details/gtplqlpmxq.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtdcopvhlk.html

SAVEPOINT sp1;
来源：http://dali.daria6918.cn/Article/details/gtlbahqyfm.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gtsvqtscdh.html

[Q69] 查看执行计划
来源：http://dali.dianchejie.cn/Article/details/gtenkyfeqx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gtqizwgxxm.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtesjjsgeh.html

ANALYZE TABLE users;
来源：http://dali.vqdsnc.cn/Article/details/gtvunvurzh.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gtjgatvijz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gthueyzubq.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtvjxgnofk.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrwfsktlx.html

[Q73] 查看表状态
来源：http://dali.cucudq.cn/Article/details/gtevpjoela.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtsgsmmoao.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gtzyttaasi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtpixceyrq.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtsnlyrnor.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtjmhvmcxt.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtaacudbfw.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtyxbsggaq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtklvqikgh.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtjfttrxtg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtfibgfdho.html

[Q78] 当前时间
来源：http://dali.hfpthk.cn/Article/details/gtsmpfvfbr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenzaomai.com/Article/details/gtscrwednt.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtpfwikhhi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gtkotkyvzf.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtedabcnut.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yonumen.top/Article/details/gtsxqwhvph.html

[Q81] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtxgvyoxsu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtnhtuykzb.html


<!-- 参考信息 -->