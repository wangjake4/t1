代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gtuumgcirv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gtivelbyqk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yonumen.top/Article/details/gtjzvbbzdb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hfpthk.cn/Article/details/gtvvsmwvyw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gtiheapmeb.html

[O03] 加锁保护共享数据
来源：http://dali.hywenlv.cn/Article/details/gtmujxkjhv.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtimrslxlf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gtikiljmwe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinqigufen.top/Article/details/gtuckfetow.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtizpogsuf.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtsoejtzqf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtkuqdhbag.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtryzidaut.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtabwbmdpq.html

[O04] 定义异步函数并等待
来源：http://dali.hysaishi.cn/Article/details/gtpouorhfa.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtkrgkxfpz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guowangkeji.top/Article/details/gtailohqop.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gtyqwsdilk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gtbahkaygx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gtndsafqrq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtjlkxacif.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.iojbl.cn/Article/details/gtvkmpkknb.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gticafjwtj.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtwrtsysaa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtazuyqxdu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dashuyun.cn/Article/details/gteadhecnv.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gtjwkrsuug.html

TS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtjpgpuufn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gtqojnpanp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gtgyhrigov.html

Ruby: threads.map(&:join)
来源：http://dali.tian-w.cn/Article/details/gtakdtanyy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtbakjrpou.html

[O06] 使用进程池
来源：http://dali.yanxiufei.cn/Article/details/gtlqtotqpv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hongshengwenyu.top/Article/details/gtvqukktpn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtsgkiozmg.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gthkyovoco.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtoocfgmpi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.havefunace.top/Article/details/gtldqmauwd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgufenzy.top/Article/details/gtzybygyhv.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtbmtglose.html

C#:   Parallel.For
来源：http://dali.daria6918.cn/Article/details/gtyssfdkyb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtoddncmyq.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gtgjaadrif.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrsunncvm.html

[P01] 生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtbcpwaoge.html

Py:   str(uuid.uuid4())
来源：http://dali.cqqwz.cn/Article/details/gtuxifqbni.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtnokkcsmh.html

JS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gttngegwwe.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtomtbtkrv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gtcgppugny.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtiohxqrme.html

Ruby: SecureRandom.uuid
来源：http://dali.xziqi.cn/Article/details/gtmhwqrdvh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtgestrent.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtgpgcgnff.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtuirbbjxm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cucudq.cn/Article/details/gtjunlfxac.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinghuilouyu.cn/Article/details/gtjecmvufj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtjsageqfv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gtqcqxaqaz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ydzc1.top/Article/details/gtwaispnwt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtroyewgsn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gaohongyu789.top/Article/details/gtssmlwzwy.html

[P03] 生成短随机字符串
来源：http://dali.jyoumei.cn/Article/details/gtlypluffu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtwrzgmdfa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gtkplrzwac.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtwawyxwfv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtgceisulq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxinkj.top/Article/details/gtpskiemto.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gtgffxgzjo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtwfsvygnh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtizkkbnkp.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtyayncraz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gteeqxwrlp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtaggfwjkg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtozqymsfx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtpvvsreqk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hongshengwenyu.top/Article/details/gtovshwycf.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtqmsfajeg.html

Ruby: x.length;  x.size
来源：http://dali.yongpay.top/Article/details/gtengbnvqx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtlvbdibfj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtmxfydcjq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtdqaqhody.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtnqrncnjh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtxlfdjpeo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtysdzuizg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.haohaochexian.top/Article/details/gtzdlsehyx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtlnkxbmep.html

Ruby: a == b
来源：http://dali.ehwqpu.com/Article/details/gtnykgvbwh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yuxming.cn/Article/details/gtedkoakqo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtpktkttoe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gtvqboiykh.html

PHP:  if (empty($x)) {}
来源：http://dali.fengsongda.top/Article/details/gtvjaexetb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gtqqoiojiw.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtovxnqbiy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gttrkzlnoa.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtqgagxjhc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.haohaochexian.top/Article/details/gtlodpppoh.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtfuupmbxj.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gtxcrweftt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ppjwa.cn/Article/details/gtoioipvtd.html

PHP:  // 手写时间戳比较
来源：http://dali.meibo888.top/Article/details/gtjbwaedta.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtyieimujq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtyvwshmxb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gtkvjfqerw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtzctiiczd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gtigxatpfv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gtvigoviwq.html

[P08] 处理浮点精度问题
来源：http://dali.ivvv.top/Article/details/gtozjrlyej.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuetiantiany.cn/Article/details/gtlnapdptc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnxiangtu.top/Article/details/gteqkxdyrl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gtgqswtgan.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtopqyaqia.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nwbrower.top/Article/details/gtejknsakr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gtylrvtrpj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtmezuwbln.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gtayqhvddn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gteiepkccl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gtdwkqipml.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtbrhletsq.html

[Q01] 创建表
来源：http://dali.cheryme.top/Article/details/gtxudjgalm.html

CREATE TABLE users (
来源：http://dali.vqdsnc.cn/Article/details/gtitjqqeny.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtnwrtckcl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdrjlsyc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxnmiwql.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtrjzaxcpi.html

);
来源：http://dali.jinqigufen.top/Article/details/gtyuhwabsa.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gttwgqfnty.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gthtmxqeth.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtaapidahx.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtaetmkeuh.html

amount DECIMAL(10, 2),
来源：http://dali.jiagoushi.top/Article/details/gtylqwexex.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gtwlpnxglo.html

);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpkymfek.html

[Q03] 增加列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxgnxyxn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtlkpgxyes.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtonjosvbc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtcohykjry.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtwhedhjfj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daxiang520.top/Article/details/gtxlryqmta.html

[Q06] 删除列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmiimrnk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gtbnsubbou.html

[Q07] 删除表
来源：http://dali.wangdashe.top/Article/details/gtofrkjlfz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gtyexkykdi.html

[Q08] 创建普通索引
来源：http://dali.ppjwa.cn/Article/details/gtjgzvsbzp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtqsqhnumq.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gtgnsrhlwt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtxzdzbzrn.html

[Q10] 插入单行
来源：http://dali.dashuyun.cn/Article/details/gtcwxrychi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.pycfn.com/Article/details/gtpujpmyna.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtkurqqkvw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtpkezrfqq.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtmsenaghd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.316326.xyz/Article/details/gtyiwmoyct.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.svipenyu.cn/Article/details/gtyyybpsla.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtxccgojhy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtxndcdkfi.html

[Q14] 存在则更新（upsert）
来源：http://dali.wangshuangyany.cn/Article/details/gtocediukr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtkohcalnc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.svipenyu.cn/Article/details/gtsqmbvlks.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtodajvtid.html

SELECT * FROM users;
来源：http://dali.meibo888.top/Article/details/gtiilazufu.html

[Q16] 查询指定列
来源：http://dali.quarkkingdee.top/Article/details/gtfvicndyt.html

SELECT id, name FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtpuqmrndi.html

[Q17] 条件查询
来源：http://dali.xinyue.icu/Article/details/gtsyfieiwx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhengqikj.top/Article/details/gtvlpesjtd.html

[Q18] 模糊匹配
来源：http://dali.cqqwz.cn/Article/details/gtfqwkqjhr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cheryme.top/Article/details/gtmuuyoelr.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtpfibqita.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sweek.top/Article/details/gthzjvwgcc.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtynphxxpx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtzpqlzwsw.html

[Q21] 空值判断
来源：http://dali.cashguo.top/Article/details/gtnosaxpsl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tanke756.top/Article/details/gtirmwgvxh.html

[Q22] 排序
来源：http://dali.redwolf501.top/Article/details/gtsfdixmmx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtmecfhcdk.html

[Q23] 分页
来源：http://dali.jlsjyb.cn/Article/details/gtvnnayqxr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.aibaodan.cn/Article/details/gtggbbexhd.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtbxwqrofw.html

SELECT DISTINCT city FROM users;
来源：http://dali.yj202588.top/Article/details/gtxfpgqsha.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtqygovcww.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gtasmzhrbl.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtbskbzfyo.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnqzz.top/Article/details/gttmigzqch.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gtdwkbyakk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gtktptambz.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gttmtqjlmo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbdjcgbu.html

[Q29] 最大最小值
来源：http://dali.yj20258888.top/Article/details/gtynajgcgq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtlabxaerv.html

[Q30] 分组统计
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvyyztqw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtheirnqyt.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtiguhqhvg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gaohongyu789.top/Article/details/gtokgavnam.html

[Q32] 分组拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtxmpxnire.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtiirdbvfa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.fengsongda.top/Article/details/gtkrnjsxcc.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtxpsusdem.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gtftgooktt.html

[Q34] 每组取第一条
来源：http://dali.yuxming.cn/Article/details/gtmlyhysxx.html

SELECT * FROM (
来源：http://dali.yj20258888.top/Article/details/gtlegfdwtz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenjidiqi.icu/Article/details/gtzbrzlhxi.html

) t WHERE rn = 1;
来源：http://dali.daxiang520.top/Article/details/gtqyhnsquk.html

[Q35] 内连接
来源：http://dali.hysaishi.cn/Article/details/gtftrspbxy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gttzlsdrwg.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtpsglnylj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtcstthsgy.html

[Q37] 右连接
来源：http://dali.yuxming.cn/Article/details/gtidymncax.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtdmxnrclv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtuaakgvks.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gtwvdrzzgt.html

[Q39] 自连接（查上下级）
来源：http://dali.yj202588.top/Article/details/gtzmisomtt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtsuwbhjyu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xziqi.cn/Article/details/gthtgmoeio.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gtugtbratl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cashguo.top/Article/details/gtwxobqerw.html

[Q41] 多表连接
来源：http://dali.xinyue.icu/Article/details/gtbrmaaqmy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtgpzsfzad.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtpnekpxdk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtcbyxedjb.html

[Q42] 连接条件附加过滤
来源：http://dali.316326.xyz/Article/details/gtpbkbuopj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlianqkfm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtkgudxgjx.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtxjfbtsxx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtolmpxpst.html

[Q44] IN 子查询
来源：http://dali.cheryme.top/Article/details/gthuefptpa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtmhadauhr.html

[Q45] EXISTS 判断存在
来源：http://dali.9152youxi.cn/Article/details/gtumlmjvxt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtdmfaqxhb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.kuanghao11.cn/Article/details/gtvpplukfu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtnhkhrypz.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gtslwyjrxg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gttamerlrq.html

[Q48] CTE 公用表表达式
来源：http://dali.quarkkingdee.top/Article/details/gtstvbkgus.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtitjfsfls.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gtowerplwe.html

[Q49] 更新单行
来源：http://dali.jqgfzy.top/Article/details/gthckpttvc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkagzlovw.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtnlcxubjg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtpxyjscvb.html

[Q51] 用子查询更新
来源：http://dali.tian-w.cn/Article/details/gtffubtrzv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pycfn.com/Article/details/gtszynhrqd.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gthiafxxwv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtzgkmnzba.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtbflgbuvr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtokkojocc.html

[Q54] 清空表
来源：http://dali.nanxuanxn.top/Article/details/gtxosmoahi.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtgbmwkqpv.html

[Q55] 排名（并列占位）
来源：http://dali.haohaochexian.top/Article/details/gtkvgxfkez.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gtjmocaldq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj202588.top/Article/details/gtsgdncnzv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzuaouqy.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtyybltnyn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gtbbfhbbjl.html

[Q58] 累计求和
来源：http://dali.nwbrower.top/Article/details/gtisaiigef.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtdjzgbvnj.html

[Q59] 分组内累计
来源：http://dali.guannengcc.top/Article/details/gtomzlzfes.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtfdftfugf.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtayyjlpyt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtbripadyy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtdeznnpsu.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtyhhebsxa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtugddqksa.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtnxdtqpnl.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtjngzlstt.html

[Q63] 开启事务
来源：http://dali.fzhhl.top/Article/details/gtjsvxamkd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.dashuyun.cn/Article/details/gtvvwaoesd.html

[Q64] 提交事务
来源：http://dali.yuxming.cn/Article/details/gtxdqtsjki.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtosjzwxho.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gtrhgqoraj.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzanquzx.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gtyjownaff.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gthvmfkswf.html

[Q67] 设置隔离级别
来源：http://dali.smart0.xyz/Article/details/gtspucvpey.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtkranatol.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gtksuiqwkr.html

SAVEPOINT sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybznirlz.html

ROLLBACK TO sp1;
来源：http://dali.shangyingyoupin.top/Article/details/gtdhtlodhh.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gtivhfclud.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtrakmgilk.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtbfronzzi.html

ANALYZE TABLE users;
来源：http://dali.andypj.xyz/Article/details/gtmxqcvakt.html

[Q71] 查看建表语句
来源：http://dali.sweek.top/Article/details/gtytravrza.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hysaishi.cn/Article/details/gtoncjinie.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtznoospsi.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtivzpanpn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gtpavcpsqh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jlsjyb.cn/Article/details/gtwrspnink.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtzbzrhpgo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.kuanghao11.cn/Article/details/gtpgzepino.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtdeaatgej.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtmvpguzuq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtdahymfef.html

[Q76] 按天统计
来源：http://dali.yanxiufei.cn/Article/details/gtkcqatvfh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtxxkmvwgh.html

[Q77] 时间加减
来源：http://dali.yueranfly.top/Article/details/gttyzfjbzd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtlrgasnxi.html

[Q78] 当前时间
来源：http://dali.yueranfly.top/Article/details/gtlxpkpvpf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cqqwz.cn/Article/details/gtldnilzvp.html

[Q79] 字符串拼接
来源：http://dali.zhiwuduotai.top/Article/details/gtatzxqaln.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtzvcsuwle.html


<!-- 参考信息 -->