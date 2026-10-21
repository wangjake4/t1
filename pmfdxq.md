代发 wailian999

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gthkhfqqsp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gteatyqpmp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtyxnntrsq.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtzzexiyhw.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytfusgfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtghfdyiyk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtkhobsqml.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtuxyfwtsk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtekzqivzt.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtpccmtilt.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvvtugty.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtstnlzbzd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shzxlz.cn/Article/details/gtcrmaalpp.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtynqqchtk.html

Java: synchronized (this) { shared++; }
来源：http://dali.sweek.top/Article/details/gtczoanute.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.0kj1m.cn/Article/details/gtevzebqxv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtxnqhbrra.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtsutipcyc.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtufkpdgsa.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gtesfkfcrz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gtsubiaxav.html

JS:   async function f() { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtontcydan.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhixingplan.top/Article/details/gtpigduyvf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gttflwarff.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gtmkbrawiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.guowangkeji.top/Article/details/gtwciblpvg.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtzjwkdmux.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtzucknmim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gtncktssaq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gtqrtgqpmy.html

JS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gttcyhnvao.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtgaejfjqb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nwbrower.top/Article/details/gtvcqdswkh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtzknotwwy.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtqbjqygnq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtbjbjipjp.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gtgnccaypo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtluynvzsr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gttoyuacey.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtpmgovzhl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtclcvalqt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xylfe.cn/Article/details/gtcseyoqfs.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gtlfsdwsmz.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtsatmxrop.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtgugyevmn.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwqtzmgla.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtvichqmej.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmihemrmw.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtnmmnnvvm.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtqrazvavt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtrcigifnh.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtqrqkkxtb.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtbrsmhodd.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gtjiikdcil.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtlrmjgckt.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtykdsmjua.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gtopvlgxun.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daria6918.cn/Article/details/gtwyxfztxt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gtfcjfzwwf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gttccezmpu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guannengcc.top/Article/details/gtljhwcelw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gttwuyesqo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtnyqidyav.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtlrfscumw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ybcxt.top/Article/details/gtstgkttxd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddzfvshk.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gtdtehckgl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shangyingyoupin.top/Article/details/gtypvnuuxc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtajcfzcdv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtzncoedin.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtrjbprhee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtpfwaoamu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gtisqggnps.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gtbvdsmcjc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gtetxnmxsb.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtufpfgkrw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtgiwludqg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtdtjimsyq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gtatxwnvgp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtuxvppvwx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hfpthk.cn/Article/details/gtbotnsrxf.html

Go:   len(arr);  len(m)
来源：http://dali.aibaodan.cn/Article/details/gtfuwnyuzk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gteqzobjwg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtymiitjii.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtxbuwjaie.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangkeji.top/Article/details/gttanrhxul.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gtrxtuoyzo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenjidiqi.icu/Article/details/gtdrjxvwwt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtnijjssyc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dianchejie.cn/Article/details/gtbhnmyucz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gtxqcdvhff.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtkzjenqte.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtmrtjyvpm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gtnusppyyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258.top/Article/details/gtudbiicxq.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtvrnpzkvj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hammf.cn/Article/details/gtycglpryv.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnspvoyxf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtikwoudbb.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtqtrzohug.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtotyonpfy.html

C#:   if (x is null) {}
来源：http://dali.tianlin.xyz/Article/details/gtpajbljtz.html

[P07] 防抖与节流
来源：http://dali.zhixingplan.top/Article/details/gtsdngtcsn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gtpcrfwmyg.html

PHP:  // 手写时间戳比较
来源：http://dali.yuxming.cn/Article/details/gtyoifbmyn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gtnsoucejr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtkjktcvcq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gtcnstubul.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtcnfmrydr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gtddmylyyx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtaiuvwhow.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigfzy.top/Article/details/gtjjunftxd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtbemsbomq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtxupqugdq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtwbrvfsip.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gtqaytycgn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.vqdsnc.cn/Article/details/gtsckqlcpk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gtonswfofh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtguwfukrj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtdwhdiubz.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnrtzpcnj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gtxlwpnjah.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzyihlntf.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gtwjjmykdr.html

CREATE TABLE users (
来源：http://dali.ppjwa.cn/Article/details/gtkeoasfao.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtshufciuc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtyfdzqajo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtmumikaxx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gtaasouuzz.html

);
来源：http://dali.tianlin.xyz/Article/details/gtlxatgkvq.html

[Q02] 创建带外键的表
来源：http://dali.cdnleiting.top/Article/details/gtxrgilihs.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtdsugtdou.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmqagwvr.html

user_id INT NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtarzmtuld.html

amount DECIMAL(10, 2),
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzldfopih.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gttnqurjhb.html

);
来源：http://dali.iojbl.cn/Article/details/gthllidddy.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtbgtqpvgj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtrmruamch.html

[Q04] 修改列类型
来源：http://dali.sysykeji.top/Article/details/gtwjoucfzu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cashguo.top/Article/details/gtykmlzwcm.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtygnxpeap.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtdftsgduh.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtasidkpav.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cucudq.cn/Article/details/gtjybgyvrf.html

[Q07] 删除表
来源：http://dali.hnqzz.top/Article/details/gtmeeztwyj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtabzvqtvb.html

[Q08] 创建普通索引
来源：http://dali.shangyingyoupin.top/Article/details/gtrrptixlo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtnixhdagn.html

[Q09] 创建唯一索引
来源：http://dali.jqgfzy.top/Article/details/gtcbkosmtu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtfetshjxd.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gtbservudt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.sweek.top/Article/details/gtlvnelnky.html

[Q11] 一次插入多行
来源：http://dali.gogol.net.cn/Article/details/gttesbhpoi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.aizwys.cn/Article/details/gtbtuuxigu.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gtkunuenqi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.havefunace.top/Article/details/gtbazxmgev.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gtxwwjnrph.html

[Q13] 忽略重复插入
来源：http://dali.gaohongyu789.top/Article/details/gtqkzulbxr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yvedp.cn/Article/details/gtaddxizae.html

[Q14] 存在则更新（upsert）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnonfoio.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtlaeyeudf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yonumen.top/Article/details/gtvoxbefal.html

[Q15] 查询全部
来源：http://dali.iojbl.cn/Article/details/gtmensmomg.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtnfucukvi.html

[Q16] 查询指定列
来源：http://dali.yangfankeji.com/Article/details/gtwggqffsj.html

SELECT id, name FROM users;
来源：http://dali.yueranfly.top/Article/details/gtmadgijdt.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gtmrxfvbjy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtgpbcjokc.html

[Q18] 模糊匹配
来源：http://dali.cdnleiting.top/Article/details/gtnkujhcuv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtfhmiotvp.html

[Q19] 范围查询
来源：http://dali.jyoumei.cn/Article/details/gtqneaykde.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenjidiqi.icu/Article/details/gtlnxlilka.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtsbmflwtc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtipvkndhd.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gtubdapovm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gtkxdhsdvw.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gttruxpkuv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuxming.cn/Article/details/gtkfvmslee.html

[Q23] 分页
来源：http://dali.xinyue.icu/Article/details/gttlgckswe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.havefunace.top/Article/details/gtlzsxxidu.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthfugird.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtcwfkuafn.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtygxlbljm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.pycfn.com/Article/details/gtokllzdyb.html

[Q26] 计数
来源：http://dali.shangyingyoupin.top/Article/details/gtczkoluyl.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtgegafatf.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtkgqrsnti.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtitqhsahu.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gtfoogynvo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtsmqmputk.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gtkutxfmpm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtruxjvddn.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtqvljsjpf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gttwxyokep.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gtwoijgpmb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtfuznbdwk.html

[Q32] 分组拼接字符串
来源：http://dali.jqgufenzy.top/Article/details/gtlwmigfjn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gtgjhuoili.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.chenlongwang.top/Article/details/gtoqzsnmmj.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtycshmkhl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gtpmyxluoy.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtucmprcai.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gtjamanvfj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gttodghnii.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtrgedrrbb.html

[Q35] 内连接
来源：http://dali.svipenyu.cn/Article/details/gtzszfqamk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxinkj.top/Article/details/gtcxxgyago.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtzkxzpxqv.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtheuxpxiw.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtfevndumj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gtdgsbgsfi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtceaedfty.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gtlbuonxeg.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtzukehbrj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtnnpoaouj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.iojbl.cn/Article/details/gtolqvhsiw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gthjqahekv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gttlpcapes.html

[Q41] 多表连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqklcqvw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yanxiufei.cn/Article/details/gtzbytfzdi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ivvv.top/Article/details/gtxxkgixks.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtcjszfsui.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtakvrpdek.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtfrwnbwcf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gteetzguir.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtwmrsaizo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangdashe.top/Article/details/gtmrfjibnt.html

[Q44] IN 子查询
来源：http://dali.yvedp.cn/Article/details/gtbfbtoobq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhiwuduotai.top/Article/details/gtivnxnybe.html

[Q45] EXISTS 判断存在
来源：http://dali.bjfxy.top/Article/details/gtznmkpzxk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gttkcjcwrh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tianlin.xyz/Article/details/gtpshtfniq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtvpzbemhj.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gttlbquulw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hywenlv.cn/Article/details/gtekimkztt.html

[Q48] CTE 公用表表达式
来源：http://dali.daxiang520.top/Article/details/gtcepghlpb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hfpthk.cn/Article/details/gttohrojsm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yj20258888.top/Article/details/gtejdusjqn.html

[Q49] 更新单行
来源：http://dali.jinqigfzy.top/Article/details/gtciyqbiwc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtywlawlge.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtmlhldxij.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtboxflyhh.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gthisrupkl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtgajdpvmo.html

[Q52] 删除指定行
来源：http://dali.shzxlz.cn/Article/details/gtijweihte.html

DELETE FROM users WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtylzmxyoe.html

[Q53] 按条件删除
来源：http://dali.yuanzhike.top/Article/details/gtxhselwwy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtntmohoua.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gtupxxewcc.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gttxorpqoy.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtkcwhslhy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gtfersrvoz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.tian-w.cn/Article/details/gtvedatkjj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtwshjbusq.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gtmjhyzbcz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtuexyueiz.html

[Q58] 累计求和
来源：http://dali.fzhhl.top/Article/details/gtqhhovoil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtlizffyby.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtwkjohvet.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtvyydngua.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloymqtvf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtjsoruung.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtggartkgr.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtmcqttoku.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtrixxcchu.html

[Q62] 分组占比
来源：http://dali.svipenyu.cn/Article/details/gtcdekftng.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtgpwjbxhf.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtvhnoctis.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gtqgididtr.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtshmhwaex.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtkyaypxan.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtznpyrwhp.html

ROLLBACK;
来源：http://dali.hywenlv.cn/Article/details/gtobbcfrrs.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtmsvrmggs.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gtrkfjspmz.html

[Q67] 设置隔离级别
来源：http://dali.yuanzhike.top/Article/details/gtnuyvqxxj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dianchejie.cn/Article/details/gtyidkkkmu.html

[Q68] 保存点
来源：http://dali.hammf.cn/Article/details/gthmdpsvoy.html

SAVEPOINT sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtbukpjbwv.html

ROLLBACK TO sp1;
来源：http://dali.ivvv.top/Article/details/gthjticntd.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtkhifcizn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hywenlv.cn/Article/details/gtleiwickd.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtowtnwvcz.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtxmdzfnhx.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gttgkspcxx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtjkwjzajp.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gtbbqtrisk.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqkrcfogd.html

[Q73] 查看表状态
来源：http://dali.sysykeji.top/Article/details/gtocytsaek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shzxlz.cn/Article/details/gtbugrseuy.html

[Q74] 强制使用索引
来源：http://dali.hysaishi.cn/Article/details/gtyeebbfvy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.gzhubu.top/Article/details/gtnjscftsd.html

[Q75] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhrnwzth.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtygrriazk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtffcvotww.html

[Q76] 按天统计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhsnzxof.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtklzxmisx.html

[Q77] 时间加减
来源：http://dali.cashguo.top/Article/details/gtljrmorai.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtwlcfpbhs.html


<!-- 参考信息 -->