代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gteivyenxc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gtopamdqil.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shzxlz.cn/Article/details/gtrcjvnpaa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtdosrclhm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzdwwmnn.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtaamqojov.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdgdgnvq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtiotieait.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtpnsejmco.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gttxhqwqhi.html

Java: synchronized (this) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gtndrccyed.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gtohonydke.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yonumen.top/Article/details/gtvcteohjw.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtkxqthdsq.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtakrnjusx.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtkvrixzgn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtpyakekru.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtylzltsuq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtrohvgfcp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtgqpgtzar.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtxywaphtz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtqajpvghl.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gtgcfdptkk.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtkknnhdny.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtzkirzkce.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtvpcavowv.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtpwwjtzbh.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtfbxfeyga.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.andypj.xyz/Article/details/gtpqucfsmo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtlreqpcyo.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gttfxwacvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gthushwrmg.html

[O06] 使用进程池
来源：http://dali.svipenyu.cn/Article/details/gtxouhmwid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sufxvd.cn/Article/details/gtjsvhiqad.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtpnsjvjfj.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtyutkfyhr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtttynwjyj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtywfnficd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ivvv.top/Article/details/gtbzxodshx.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gtyfwcnpyy.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtexuxzyhx.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqwcokqhf.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtviqdrqxc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtyktdvtzj.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gtsvxwxcjh.html

Py:   str(uuid.uuid4())
来源：http://dali.snrcjt.cn/Article/details/gtknlvwtxa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cheryme.top/Article/details/gthiiozxbo.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtkzwojibs.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtypgyrrcz.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtrgpdzbqk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtsefgpbig.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtofpjyhgv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gtxhvfmfnp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtdyqmcicq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtwudbzmih.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtkjeamryr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtgnwsyvng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtympnazui.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtykdzbgzs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gtmqowhebn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gthoivocrz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtuyuohz.html

[P03] 生成短随机字符串
来源：http://dali.ydzc1.top/Article/details/gttmspsfdi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtsmrpmbal.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gthcrntppq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtbprmojyb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gthhdodrrq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.wangdashe.top/Article/details/gtkwocgjvm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtpagcmimx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtvsltcyom.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtjtbxylln.html

[P04] 求长度
来源：http://dali.svipenyu.cn/Article/details/gtajpqudxv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.guowangkeji.top/Article/details/gtzutiawgg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gtvvsijksl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gtineddpmm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gttwvhukyd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtgmfmqnnu.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtknvrxdic.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gthbwobfye.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtqyhkobym.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gtcrjobbrb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tanke756.top/Article/details/gtmrcsngor.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwjciqyr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gtpjqszecb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenzaomai.com/Article/details/gtmbhqnfla.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gtnkfjxzhs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtawvtippy.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gtizvfaiwc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.wangshuangyany.cn/Article/details/gtpyldiunl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hammf.cn/Article/details/gtteblxpjs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtdnvxjafh.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtiqguvouj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gtyrnakadu.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtafdkbbwl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtwyvxdckt.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gtkmhvcdeq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gthoykflbb.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gtwgipfdzo.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtunsfdkgc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtzqellwlx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhiwuduotai.top/Article/details/gthujsxgow.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtpgrehjgx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtyfvfqcxz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtivxeehfh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258888.top/Article/details/gtyrwfdmnr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtqtbhecto.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.chenjidiqi.icu/Article/details/gtlakzafez.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtxthpemgz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cheryme.top/Article/details/gtqzqalgnr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwecnifzn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjwsfsjx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gtqotsjfnv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258.top/Article/details/gtnwljhqfg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtogizryri.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtoydfwkyx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxaxympb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtnyqxpzpg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.vqdsnc.cn/Article/details/gtxpkrfirb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtptitrtpu.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gtiyyekrtt.html

CREATE TABLE users (
来源：http://dali.ydzc1.top/Article/details/gtpqsucehv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gttazxzrxt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gttaqjrgbt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258888.top/Article/details/gtwbgbrybm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dashuyun.cn/Article/details/gteljokofk.html

);
来源：http://dali.shangyingyoupin.top/Article/details/gtmlgvavzz.html

[Q02] 创建带外键的表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmegknew.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gthlzbdxhq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtkwvpkm.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtnayiwylh.html

amount DECIMAL(10, 2),
来源：http://dali.ybcxt.top/Article/details/gtetxnvqoz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gtpmsculpb.html

);
来源：http://dali.zhixingplan.top/Article/details/gtvhkqyvmp.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtryacjgrp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtmzgcphrj.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtzvutszkg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj20258888.top/Article/details/gtsyhnwcqt.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtfpvpifso.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtvkbgtkjd.html

[Q06] 删除列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluhtbmzc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcubzqnix.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtsoqixkyg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.chenzaomai.com/Article/details/gtrhsragsd.html

[Q08] 创建普通索引
来源：http://dali.havefunace.top/Article/details/gtogxbfwtd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuanzx.com/Article/details/gtdchjwjxc.html

[Q09] 创建唯一索引
来源：http://dali.wangdashe.top/Article/details/gtdoyaznrp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtajeigacs.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gtugjnciff.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cqqwz.cn/Article/details/gtedvkchae.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gtjodtqhgp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gttzdunhtx.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtttpvlqyx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtsdugochv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gaohongyu789.top/Article/details/gtgnhlhcjt.html

[Q13] 忽略重复插入
来源：http://dali.jqgfzy.top/Article/details/gtrkhzrwpe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gtpqhxratp.html

[Q14] 存在则更新（upsert）
来源：http://dali.jiagoushi.top/Article/details/gtwutydaod.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gteizghadx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gtzwqegfyn.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gtrhkjjpmb.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtnikbwwod.html

[Q16] 查询指定列
来源：http://dali.tanke756.top/Article/details/gteivltcpt.html

SELECT id, name FROM users;
来源：http://dali.meibo888.top/Article/details/gtxcnsmlga.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gtqjyfsory.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj202588.top/Article/details/gtnslmfmrw.html

[Q18] 模糊匹配
来源：http://dali.bjfxy.top/Article/details/gtkfkkrfhn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jlsjyb.cn/Article/details/gtxncujpdd.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtnpebzlwz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gthdkyotvh.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtkrjjohbi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.mhx1999.top/Article/details/gtchkbpvwg.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtrunhtczn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gzhubu.top/Article/details/gtopsinrbm.html

[Q22] 排序
来源：http://dali.aibaodan.cn/Article/details/gtcwocgcim.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gtuqxancuc.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtpexlfdnr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtafibwmkn.html

[Q24] 去重
来源：http://dali.cheryme.top/Article/details/gtcxydsvqf.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtyrrnqmlc.html

[Q25] 只取前 N 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtzdzgkfxg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtfjblxqbd.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gtpuosmebs.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtwedzzbdr.html

[Q27] 条件计数
来源：http://dali.zhiwuduotai.top/Article/details/gtqqchbnay.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtjgszjjdq.html

[Q28] 求和与平均
来源：http://dali.yuxming.cn/Article/details/gtynsofgga.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtpuwvqjgc.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gtjgaryrki.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtpwzropsp.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtmwfdgvrn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtahraavnv.html

[Q31] 分组后过滤
来源：http://dali.iojbl.cn/Article/details/gtjmnpagrs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.cdnleiting.top/Article/details/gtlzohdaut.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtwslgaspc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtmmszoilx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.guowangkeji.top/Article/details/gtajbsquge.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtelbcsxwu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cdnleiting.top/Article/details/gthtzinnfd.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtjrcewkbi.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gtalvybylk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gtznzrrdlc.html

) t WHERE rn = 1;
来源：http://dali.ivvv.top/Article/details/gtkzxbntgj.html

[Q35] 内连接
来源：http://dali.ydzc1.top/Article/details/gtayuizdzw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtctmirjzf.html

[Q36] 左连接
来源：http://dali.hywenlv.cn/Article/details/gtanbnxiwr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gttgdzayvb.html

[Q37] 右连接
来源：http://dali.fzhhl.top/Article/details/gtmbreyoii.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnqzz.top/Article/details/gtkqqrkcex.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.pycfn.com/Article/details/gtawvohsal.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtlewfkzcq.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtlojmxbie.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sysykeji.top/Article/details/gtalaarixq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ehwqpu.com/Article/details/gtpbmbpqgt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ivvv.top/Article/details/gtpafftyzw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtwfpaqehi.html

[Q41] 多表连接
来源：http://dali.cdnleiting.top/Article/details/gtpbgngbun.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.bjfxy.top/Article/details/gtkjgigzqs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yvedp.cn/Article/details/gtjmkamxhs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj202588.top/Article/details/gtksdsajvu.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtafpqkmkt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gtvvymdsir.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.snrcjt.cn/Article/details/gtuyalfpoc.html

[Q43] 标量子查询
来源：http://dali.feifeiyinyue.top/Article/details/gtkkqxdtgr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslewgvtq.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gtgndxqhax.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.316326.xyz/Article/details/gtfswngfls.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtrvfbtlch.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtklpfdfgy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.wangshuangyany.cn/Article/details/gtmpytpves.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.havefunace.top/Article/details/gteiujpooi.html

[Q47] 与平均值比较
来源：http://dali.ybcxt.top/Article/details/gtyywbclcu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtttownrwd.html

[Q48] CTE 公用表表达式
来源：http://dali.pycfn.com/Article/details/gtmjussukq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ybcxt.top/Article/details/gtiwclcfwq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhongyouzk.top/Article/details/gtpeuxvczz.html

[Q49] 更新单行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwaeebylb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guannengcc.top/Article/details/gtivrnzyah.html

[Q50] 批量更新
来源：http://dali.havefunace.top/Article/details/gtuepeiiak.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shuidangran.top/Article/details/gtzqdcegqd.html

[Q51] 用子查询更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunawrurb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtbbkpkdou.html

[Q52] 删除指定行
来源：http://dali.hnqzz.top/Article/details/gtforvdrol.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtlalegonh.html

[Q53] 按条件删除
来源：http://dali.nwbrower.top/Article/details/gtreyoozjr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtnmytgxmx.html

[Q54] 清空表
来源：http://dali.iojbl.cn/Article/details/gtxgmiigbm.html

TRUNCATE TABLE logs;
来源：http://dali.hongshengwenyu.top/Article/details/gtvbrglohp.html

[Q55] 排名（并列占位）
来源：http://dali.guannengcc.top/Article/details/gtkxhpnmox.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.snrcjt.cn/Article/details/gtusownyry.html

[Q56] 密集排名（并列不占位）
来源：http://dali.316326.xyz/Article/details/gtcvbogvgf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yuanzhike.top/Article/details/gtpbbswfsw.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gtcjevzhzd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gtzmiscgjp.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtwswraedy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtxjzfmxdq.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhptfoyy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtvcgvrkyu.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtlnlkrkol.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gthroxwaqt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtyrvezzcw.html

[Q61] 移动平均
来源：http://dali.sxryk.cn/Article/details/gtxvsgiwxm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtnjzkdvkr.html

[Q62] 分组占比
来源：http://dali.cdnleiting.top/Article/details/gtshkxzqrb.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiwkkpxuj.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtdlavdabo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.andypj.xyz/Article/details/gtcbxjyuou.html

[Q64] 提交事务
来源：http://dali.cucudq.cn/Article/details/gteuwfaqok.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gtwdxrcbnd.html

[Q65] 回滚事务
来源：http://dali.fzhhl.top/Article/details/gtbmxaapgb.html

ROLLBACK;
来源：http://dali.gaohongyu789.top/Article/details/gtnnkusquy.html

[Q66] 行锁查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqfxghvv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gaohongyu789.top/Article/details/gtwvkgulzj.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtutxpbizo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gtsfyswqmn.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtpmcerusr.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtlrprzgse.html

ROLLBACK TO sp1;
来源：http://dali.zhongyouzk.top/Article/details/gtynhrhvlw.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtdabkvgpg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtvqarcqmb.html

[Q70] 更新统计信息
来源：http://dali.yonumen.top/Article/details/gtlkyjgoze.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gtkxnadxzf.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gthwvnukpd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtxmttcwko.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtbtbwikhi.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtqeqzsidp.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtsoapekey.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hysaishi.cn/Article/details/gtmzabpzjm.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gtmklsmuxg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gtlzzgpezs.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtphcnistt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtaikpouli.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtgcywaisd.html

[Q76] 按天统计
来源：http://dali.shuidangran.top/Article/details/gtlgycgmjd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gtfodfujsp.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtlmffomdg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtalneacqt.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtropzaivk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.chenjidiqi.icu/Article/details/gtpjgducry.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtayinrnwi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xziqi.cn/Article/details/gtahbfrpgi.html


<!-- 参考信息 -->