代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.bjfxy.top/Article/details/gtobvfgxdo.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gteqeazdaj.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtuanennij.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gttbjesryf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gttegdfgfg.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtwkvzcnru.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtghxokbkn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gtcpwsjqcv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gttsgxnpbr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtbiygbbiu.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gtalfhsxqn.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtlihubrop.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnxiangtu.top/Article/details/gtwmkfmiwr.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtsjpjkgjw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtjimbunzk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtivkihfpf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.9152youxi.cn/Article/details/gtnulqfjcz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gthbpazrsb.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtvyqplxrq.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gttlbptoph.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yongpay.top/Article/details/gtfubyaoup.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gttrgpyynm.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gthnyjcuru.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtkjahhgyz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhengqikj.top/Article/details/gtuzzquyhp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtttnixibd.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gthbqoxhuf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzmvoirn.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtzvoxgaqz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnxiangtu.top/Article/details/gtlimhkeuj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gtrwhkqpqh.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlbqeolq.html

TS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtfjiagngq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gthdgowfqb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtejzaqtqt.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtvtrjkohg.html

C#:   Parallel.For
来源：http://dali.pengpengdd.cyou/Article/details/gtsndtyntk.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfflxxmur.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtzdrbfvqd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtvhnlnokv.html

[P01] 生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbpttqjr.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtmihiheqc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtqxqwblyk.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtucsrxrei.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtxudogmse.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfsdpljez.html

Go:   // 用 github.com/google/uuid
来源：http://dali.fzhhl.top/Article/details/gtvqcpzhuh.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtkbngpkli.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdrbaqhc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gtfgmtdpie.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtyjavzcdg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xuanzx.com/Article/details/gtywskyscm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gtfgettmvv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gttitqtvgu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gtrsjckctp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtynkrctbo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jianghu66.top/Article/details/gtrilttypt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gtzxgsgnmy.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycmcjkzi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gotoacloud.top/Article/details/gtxwugysyc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gtsbsvpqfj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtwkwrejne.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtgepvogsm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cucudq.cn/Article/details/gthemzqqjk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gteicokyod.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtjoxvjhbd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangshuangyany.cn/Article/details/gtwxyyckgw.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gtrrtnvsdi.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hywenlv.cn/Article/details/gtlzgmzmch.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtultvivpd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.meibo888.top/Article/details/gticledmjp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shzxlz.cn/Article/details/gtvwclvdqs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtjarzxtbl.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtfqhzjpbf.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gtycxpcpnd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtjkganwtz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtdbbyxfsd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigfzy.top/Article/details/gtqlcpurah.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqckynwp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwuppvpy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonimtkgn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gtgxyejowk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtdqfujqrl.html

Ruby: a == b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzqvzyhc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtqbtctjrj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.c1oappe.top/Article/details/gtrhublqmc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gtnwxtsvfd.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtpwyftuiu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtbrbqdakz.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gtqmvnbtuv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gtygfwhqvo.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtpgcvxccg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtcwofdrah.html

C#:   if (x is null) {}
来源：http://dali.svipenyu.cn/Article/details/gtpfblzqla.html

[P07] 防抖与节流
来源：http://dali.birdmap.top/Article/details/gtzbbkagfe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gttgrgrqde.html

PHP:  // 手写时间戳比较
来源：http://dali.gzhubu.top/Article/details/gtpztpxhdj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtjxqptffw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtieknzlar.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdkhcvqdh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gtfnemxlkx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthopmwlpc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gtnmcsbyiw.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gthxolqmcp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gtmevvjylj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.c1oappe.top/Article/details/gthrryidxw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gzhubu.top/Article/details/gtootiymvi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtckkzheec.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtlgidkeka.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hfpthk.cn/Article/details/gtnwmhrmwd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtektgwqig.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gtvnafihog.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmzijzth.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gtyfphuvzq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcssacnub.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtelxazeoi.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtwgfjmekp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtxunnndrt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hysaishi.cn/Article/details/gtgulnyprk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gtalkyymun.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gtyjsrjohq.html

);
来源：http://dali.hfpthk.cn/Article/details/gthqcsofdn.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gtfskklaic.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchpuvlav.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagblkkqz.html

user_id INT NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtmzektjmo.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtrzvlghuh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtggwicgji.html

);
来源：http://dali.sweek.top/Article/details/gtcortujob.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtdwqgtzkp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtojmjsisq.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gtmtufhtig.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.svipenyu.cn/Article/details/gtsfsejggc.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gttajxdanu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zycfv.cn/Article/details/gteutnwnmc.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtyltnlfsa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigufen.top/Article/details/gtuartuxhu.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtwnmbnxsn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.c1oappe.top/Article/details/gtnpdglliz.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhjkqqng.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtbzcmrmgl.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgymosdv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tian-w.cn/Article/details/gtneikqube.html

[Q10] 插入单行
来源：http://dali.fengsongda.top/Article/details/gtdgioofms.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gtjrjgqbrm.html

[Q11] 一次插入多行
来源：http://dali.gotoacloud.top/Article/details/gtdppgnopb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibnfswvr.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gtqehzbssu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.pycfn.com/Article/details/gtkuepkidg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtuzpguxfp.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gtpxsgwabb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtaknlkqkh.html

[Q14] 存在则更新（upsert）
来源：http://dali.yuxming.cn/Article/details/gtcrsbxjqj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtpefzgkhg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinqigfzy.top/Article/details/gtxaoiulir.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtxrdbhrke.html

SELECT * FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtxqdplcri.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtfgfrboss.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtiggpvzsn.html

[Q17] 条件查询
来源：http://dali.birdmap.top/Article/details/gtgxiquept.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nwbrower.top/Article/details/gtnfcprbyq.html

[Q18] 模糊匹配
来源：http://dali.redwolf501.top/Article/details/gtlyladzeq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.haohaochexian.top/Article/details/gtqwemqiwb.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtpfdqgasg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zdqjudy.top/Article/details/gtryfctnrw.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gttmlyyvyj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtdbjyfswv.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gtqhjbuekg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gtgjdffnts.html

[Q22] 排序
来源：http://dali.yuxming.cn/Article/details/gtkzhshznn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.pycfn.com/Article/details/gtggpgsagh.html

[Q23] 分页
来源：http://dali.cucudq.cn/Article/details/gtojfxtfyy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigfzy.top/Article/details/gtemtdplvq.html

[Q24] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtvpkoholm.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxinkj.top/Article/details/gteblrhldd.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtklrsdyye.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yongpay.top/Article/details/gtzqjuexev.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gtjczokgug.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzctsircw.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtbyiqqszz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtaaiibbmo.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gturxkckwe.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtbrebowpn.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gtgqmodeei.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtisipiguf.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gtcivxvfcl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aizwys.cn/Article/details/gtmqjuxywy.html

[Q31] 分组后过滤
来源：http://dali.jyoumei.cn/Article/details/gtksyxmvqx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgutstsej.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gtdowitnyz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtqjvzgpcf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtcduwpdgh.html

[Q33] 多列分组
来源：http://dali.9152youxi.cn/Article/details/gtwlikqmna.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhongyouzk.top/Article/details/gtdntqqdyb.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtpdpnoezg.html

SELECT * FROM (
来源：http://dali.cheryme.top/Article/details/gtpaknfymp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cqqwz.cn/Article/details/gtoamnvvns.html

) t WHERE rn = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtqungzmuw.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gtwiheyzoh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gtpkcddrst.html

[Q36] 左连接
来源：http://dali.zdqjudy.top/Article/details/gtxvfdbnys.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtmupycasj.html

[Q37] 右连接
来源：http://dali.gogol.net.cn/Article/details/gtrrwnygtt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guowangkeji.top/Article/details/gtryudfgld.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zdqjudy.top/Article/details/gtcyodlqof.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gtzydbqnjc.html

[Q39] 自连接（查上下级）
来源：http://dali.gogol.net.cn/Article/details/gtcfiluzzq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gtvutzjped.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ivvv.top/Article/details/gtkxwqisxm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwaomcek.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuxming.cn/Article/details/gtfevmxbgh.html

[Q41] 多表连接
来源：http://dali.shzxlz.cn/Article/details/gthykqppcv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtltkrtmst.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtauexaqfz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtzewjssvz.html

[Q42] 连接条件附加过滤
来源：http://dali.gotoacloud.top/Article/details/gtpqeepoip.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nwbrower.top/Article/details/gtegtboecf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yanxiufei.cn/Article/details/gtmsbtrsvy.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtiqchellc.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jiagoushi.top/Article/details/gtoizlahyn.html

[Q44] IN 子查询
来源：http://dali.mhx1999.top/Article/details/gtkfnomkzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ybcxt.top/Article/details/gttxcwzuit.html

[Q45] EXISTS 判断存在
来源：http://dali.guannengcc.top/Article/details/gtnmtwqiki.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ppjwa.cn/Article/details/gtdzkzxrzp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtqccjibir.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sxryk.cn/Article/details/gtdylemoak.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtabgwggpt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cheryme.top/Article/details/gtalbqjcol.html

[Q48] CTE 公用表表达式
来源：http://dali.iojbl.cn/Article/details/gtmdpswcnq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtcvgjgxvf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtekvwnugq.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gtosexenrh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ehwqpu.com/Article/details/gtetlfdihl.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtntllhdmq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.wangdashe.top/Article/details/gtdhqlsciu.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gtezpqqtsr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgypiibll.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gtfxbuozux.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gtpgaxynou.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtuetivwlm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gtdtgjuwhy.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtlbqbeeqe.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtajoincic.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gthkplxung.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtnzlctskd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gtfqlietrl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gttyizwaec.html

[Q57] 行号
来源：http://dali.xinyue.icu/Article/details/gtffyniwwt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gttaqorvce.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtdjfgdxst.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtdteamdlq.html

[Q59] 分组内累计
来源：http://dali.yanxiufei.cn/Article/details/gtoygphmfc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtmonpzalq.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtdlsjfthi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj202588.top/Article/details/gtluabwfph.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtgvsfuylk.html

[Q61] 移动平均
来源：http://dali.daxiang520.top/Article/details/gtapuafkoq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtrruqejaj.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gtlgbufxuy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtvktlicqv.html

[Q63] 开启事务
来源：http://dali.meibo888.top/Article/details/gtmynrbnug.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtktwbwljv.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gtzrnnztkl.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gthzqinhgs.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtfertrwrl.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtwqhymzdf.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gtrbhzfpfi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gotoacloud.top/Article/details/gtgasxcdqf.html

[Q67] 设置隔离级别
来源：http://dali.yvedp.cn/Article/details/gtgyhuusjo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ydzc1.top/Article/details/gtiikjxyej.html

[Q68] 保存点
来源：http://dali.shzxlz.cn/Article/details/gtagshfeyo.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtpqxfmzxo.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gtqoeenlva.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gttfidcvog.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtnjxvmuux.html

[Q70] 更新统计信息
来源：http://dali.fzhhl.top/Article/details/gtpirpvnij.html

ANALYZE TABLE users;
来源：http://dali.zhengqikj.top/Article/details/gtadqppgot.html

[Q71] 查看建表语句
来源：http://dali.yongpay.top/Article/details/gtqaohdrzm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtuzbyjeos.html

[Q72] 查看索引
来源：http://dali.hnqzz.top/Article/details/gtziothurk.html

SHOW INDEX FROM users;
来源：http://dali.gzhubu.top/Article/details/gtwfrnynqu.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtssnyffau.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.birdmap.top/Article/details/gtgewuptja.html

[Q74] 强制使用索引
来源：http://dali.nwbrower.top/Article/details/gtjbkuqwfu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinghuilouyu.cn/Article/details/gttevxrglm.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtjuugygbh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtrkhkmbie.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgfzy.top/Article/details/gtvcbbrhlx.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtaawhdcho.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ehwqpu.com/Article/details/gttetkkuyy.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtmgclwaui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gthqrgvxih.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gtvkduccwz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sweek.top/Article/details/gtrgxlwjeu.html

[Q79] 字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtjoqyupmh.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shzxlz.cn/Article/details/gtpkxbhkly.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtkkdstgue.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtlpfagqgm.html

[Q81] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gtkjtxlsld.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gtpdveweyb.html


<!-- 参考信息 -->