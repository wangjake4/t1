代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.guowangkeji.top/Article/details/gt2mxyypkfi.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2prhnobgj.html

Ruby: Thread.new { f }
来源：http://dali.shzxlz.cn/Article/details/gt2mqrvwley.html

C#:   Task.Run(() => F());
来源：http://dali.cucudq.cn/Article/details/gt2choqfyft.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gt2drhtxlcr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj202588.top/Article/details/gt2txowokzj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.iojbl.cn/Article/details/gt2rqlcloea.html

JS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2mvvljjyw.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2ojioypdv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gt2kybpclic.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gt2mopxrsie.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ufmaeibk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jlsjyb.cn/Article/details/gt2mkmhydfd.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gt2socvcuzt.html

Py:   with lock: shared += 1
来源：http://dali.smart0.xyz/Article/details/gt2uptvjspw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.svipenyu.cn/Article/details/gt2xronmxcn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gt2opuwlghe.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2tecmkhso.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gtoxfhjl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gt2yrkmqmzu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mekgkdzb.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2cichixdk.html

[O04] 定义异步函数并等待
来源：http://dali.hnxiangtu.top/Article/details/gt2ipksyxwc.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gt2afievmay.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gt2kbmddszq.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gt2onwnjzht.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2rqtspgar.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2iakbjjvt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangdashe.top/Article/details/gt2ajlxrltr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gt2ivghvikn.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gt2ctzsrfrt.html

[O05] 并发执行并等待全部完成
来源：http://dali.svipenyu.cn/Article/details/gt2zcebbgct.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gt2uirhcgit.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gt2hovmqkdu.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlyeukgy.html

TS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2pecgehpm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jqgufenzy.top/Article/details/gt2cqxptnll.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gt2tdinqbva.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewhupele.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gt2nivjuric.html

[O06] 使用进程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tfmamzea.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2lkcfmawq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gt2xwxcqyts.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2otbckzsf.html

TS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gt2gzawesbm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gt2tmqljkkx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.9152youxi.cn/Article/details/gt2nybyjiyc.html

Ruby: // fork 块
来源：http://dali.aibaodan.cn/Article/details/gt2gclopfwq.html

C#:   Parallel.For
来源：http://dali.guowangkeji.top/Article/details/gt2tblfoheq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2lwzjtkvb.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gt2qzpoobnt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2agtorehx.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2pnignajl.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gt2vyjblrvz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2izahcswt.html

JS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2kfdbqdtz.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gt2pafesmoh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyzaccjw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gt2ffqybliv.html

Ruby: SecureRandom.uuid
来源：http://dali.c1oappe.top/Article/details/gt2hgnvqnbw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gt2ueiyztws.html

[P02] MD5 / SHA256 摘要
来源：http://dali.vqdsnc.cn/Article/details/gt2bjbsadze.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gt2ydqawqfw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gt2tbpplwgc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2ezqomgla.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gt2zgfxukkr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2lsipwrzb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmuyitnx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2incigonh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2rpkfdnqr.html

[P03] 生成短随机字符串
来源：http://dali.yj20258888.top/Article/details/gt2azrbhaih.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cicvyoug.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yvedp.cn/Article/details/gt2boseqrcr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2bfserudg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2fvwumvgo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gotoacloud.top/Article/details/gt2sltsmwmp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gt2kulrucme.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gt2gxdftykv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gt2jamkduvs.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdwfvzei.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gt2vvwtmwez.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gt2kydkecgf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2irjrsmlp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gt2jlgzvdkl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auosutdc.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gt2wlqyyctm.html

Ruby: x.length;  x.size
来源：http://dali.shzxlz.cn/Article/details/gt2fzkfaknm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdzvdayn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfrbifmo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gt2kzswcsvd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangshuangyany.cn/Article/details/gt2ooyuhhgm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2naadgjkr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ukgkbeus.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gt2ozzcuwea.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gt2lworwrqx.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gt2wfthqckb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tian-w.cn/Article/details/gt2ewicydeq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gt2xsfjntzb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.c1oappe.top/Article/details/gt2rltjxlmc.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2igoydncq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gt2ikockxfx.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2fmtvexnn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2xadjwqyw.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gt2vtreszbz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cashguo.top/Article/details/gt2easuhliq.html

C#:   if (x is null) {}
来源：http://dali.cdnleiting.top/Article/details/gt2spnmscqa.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gt2ipjyacsm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gt2exhlhnqh.html

PHP:  // 手写时间戳比较
来源：http://dali.gotoacloud.top/Article/details/gt2ddpjmpcr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2hmrwcpqy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gt2qudcroqq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2xmarjzru.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2nucgjwly.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gt2xcvggsfs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gt2nkupjeii.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gt2tkoukwqc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2hwhmkklj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2jtdjcmjk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gt2kgkomxua.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lssvcqrj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gt2egucsmtj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tianlin.xyz/Article/details/gt2rxdktgfw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gt2buupaqmv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2fjigtmpl.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2maimnquq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gt2tfpdysee.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2kqwsuacg.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gt2yprqfceu.html

CREATE TABLE users (
来源：http://dali.xylfe.cn/Article/details/gt2execqrdr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2skrzknbb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.redwolf501.top/Article/details/gt2jvtycohk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gt2zftnvybp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gt2gewumatc.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofehutro.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gt2ssislnit.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gt2dthkamib.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2xmfulzff.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2hsrvttca.html

amount DECIMAL(10, 2),
来源：http://dali.sysykeji.top/Article/details/gt2qrzuzego.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cdnleiting.top/Article/details/gt2onuovwlz.html

);
来源：http://dali.tanke756.top/Article/details/gt2kolbtchy.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2zcokpxxt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guannengcc.top/Article/details/gt2rrxcjkxq.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2ftswxdfi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txtdeoha.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gt2gpepceaq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gt2hkimjuvh.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gt2aammiwox.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hnxiangtu.top/Article/details/gt2ftasfagi.html

[Q07] 删除表
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndbucnrd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2edghyxhn.html

[Q08] 创建普通索引
来源：http://dali.zhoulong.xyz/Article/details/gt2xmxhosvg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gt2plzxjywl.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gt2flqagztq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gt2iyddnorg.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2qgurgfdv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2vftiviex.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2neophofi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gotoacloud.top/Article/details/gt2jayghgjj.html

[Q12] 插入后取自增 ID
来源：http://dali.tianlin.xyz/Article/details/gt2fryznqll.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yonumen.top/Article/details/gt2pzrjrhpm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.fengsongda.top/Article/details/gt2blxegjte.html

[Q13] 忽略重复插入
来源：http://dali.cdnleiting.top/Article/details/gt2khltkwny.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gt2zbrhvpdp.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gt2lozercmb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.iojbl.cn/Article/details/gt2brzqolzb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gt2drvausqc.html

[Q15] 查询全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vceaaamz.html

SELECT * FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2pyprnepq.html

[Q16] 查询指定列
来源：http://dali.gzhubu.top/Article/details/gt2ghzxdojq.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2srofggcs.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gt2vpcgbpcx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbvcbloo.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzstvxan.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gt2hjxbczuv.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gt2fnfqkypy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.mhx1999.top/Article/details/gt2yiqifyql.html

[Q20] IN 列表
来源：http://dali.havefunace.top/Article/details/gt2weipoebd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2duohmgli.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gt2dsjslipr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gt2tsdilouw.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gt2cfjxbruo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.smart0.xyz/Article/details/gt2qtpokosq.html

[Q23] 分页
来源：http://dali.cdnleiting.top/Article/details/gt2gceyicbc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gt2ztndesdw.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gt2vdfeygon.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2teldrxww.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gt2fgixbmnj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gt2jsnopwsz.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gt2dthvfjfy.html

SELECT COUNT(*) FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2oggpupmr.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gt2frxnytzv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2xuwfscin.html

[Q28] 求和与平均
来源：http://dali.guannengcc.top/Article/details/gt2mlviagyz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gt2ifhaufmn.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2kkirybls.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2ubahaoeo.html

[Q30] 分组统计
来源：http://dali.jianghu66.top/Article/details/gt2cylszxpf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2qitnacyh.html

[Q31] 分组后过滤
来源：http://dali.zycfv.cn/Article/details/gt2xgzscgut.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gt2xzgudbuh.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gt2sizzdvjw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gt2emflziez.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hysaishi.cn/Article/details/gt2oikoptih.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gt2odsktuyp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gt2aqitugcs.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvrumbnk.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gt2ojuqtpgt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sxryk.cn/Article/details/gt2jxuefisi.html

) t WHERE rn = 1;
来源：http://dali.jyoumei.cn/Article/details/gt2luptexrp.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gt2umjqglac.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lbtuchqn.html

[Q36] 左连接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmapjkyj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtnpfia.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gt2mejsfyer.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gt2dstcfslk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxinkj.top/Article/details/gt2tytikzgj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xziqi.cn/Article/details/gt2twylgnou.html

[Q39] 自连接（查上下级）
来源：http://dali.cheryme.top/Article/details/gt2yylkfyjz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gt2tpnvtnho.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gt2tofrtppu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.quarkkingdee.top/Article/details/gt2xdfqyvxp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gt2ofttfmme.html

[Q41] 多表连接
来源：http://dali.jiagoushi.top/Article/details/gt2akjftalu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sysykeji.top/Article/details/gt2tsourtel.html

JOIN users u ON u.id = o.user_id
来源：http://dali.0kj1m.cn/Article/details/gt2wsedvjnw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gt2oopwaxyj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuhxrcf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shuidangran.top/Article/details/gt2vmmjbirk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gt2vklevqpr.html

[Q43] 标量子查询
来源：http://dali.hfpthk.cn/Article/details/gt2xbjfoiie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gt2usagqued.html

[Q44] IN 子查询
来源：http://dali.316326.xyz/Article/details/gt2njxnishe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2ldlfbfrn.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gt2skwpghru.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvaoniqu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gt2mrpfnytr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ivvv.top/Article/details/gt2sghvjwic.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gt2waiwyidy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xziqi.cn/Article/details/gt2bmjdfqoi.html

[Q48] CTE 公用表表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2bamjkvco.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gt2spxycdfp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hnqzz.top/Article/details/gt2opzeifbe.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2xluqgivu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gt2yfdgyxum.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gt2pnpgyudg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gt2mtqsxbjx.html

[Q51] 用子查询更新
来源：http://dali.xziqi.cn/Article/details/gt2lozfkjrh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yj202588.top/Article/details/gt2lnpazbkr.html

[Q52] 删除指定行
来源：http://dali.redwolf501.top/Article/details/gt2xzairjpc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fucwjggo.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gt2jlzhfpyj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.snrcjt.cn/Article/details/gt2ugbxxsah.html

[Q54] 清空表
来源：http://dali.jyoumei.cn/Article/details/gt2peypxjsx.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gt2qokybelv.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gt2miwkoant.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2ywhbyypj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gogol.net.cn/Article/details/gt2yfqgxrpc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gt2whbyfdle.html

[Q57] 行号
来源：http://dali.9152youxi.cn/Article/details/gt2afygdqfi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.316326.xyz/Article/details/gt2zeerrcpo.html

[Q58] 累计求和
来源：http://dali.hywenlv.cn/Article/details/gt2kubiomia.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gt2eufplnjx.html

[Q59] 分组内累计
来源：http://dali.ydzc1.top/Article/details/gt2yvsrnsbm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2trocmajg.html

[Q60] 取上一行 / 下一行
来源：http://dali.jlsjyb.cn/Article/details/gt2ghzpmoii.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jqgufenzy.top/Article/details/gt2vshjvopu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2dnyatuag.html

[Q61] 移动平均
来源：http://dali.jinqigufen.top/Article/details/gt2fjafyhne.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yonumen.top/Article/details/gt2eutdtvjo.html

[Q62] 分组占比
来源：http://dali.shuidangran.top/Article/details/gt2ikvxldxh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gt2zptirdde.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2hbygsifj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljnvdoey.html

[Q64] 提交事务
来源：http://dali.9152youxi.cn/Article/details/gt2afulcehh.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gt2djxdulrl.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gt2zdkhkuze.html

ROLLBACK;
来源：http://dali.ppjwa.cn/Article/details/gt2jtvtbjwl.html

[Q66] 行锁查询
来源：http://dali.yonumen.top/Article/details/gt2uusbsuea.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fengsongda.top/Article/details/gt2lkchzapi.html

[Q67] 设置隔离级别
来源：http://dali.nwbrower.top/Article/details/gt2wkreutse.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.bjfxy.top/Article/details/gt2yfhscwjy.html

[Q68] 保存点
来源：http://dali.hysaishi.cn/Article/details/gt2mxlqwxhs.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gt2kyspagka.html

ROLLBACK TO sp1;
来源：http://dali.yueranfly.top/Article/details/gt2dsndqftv.html

[Q69] 查看执行计划
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lcgrbkgx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhengqikj.top/Article/details/gt2vulvlyjb.html

[Q70] 更新统计信息
来源：http://dali.sufxvd.cn/Article/details/gt2skkrutdd.html

ANALYZE TABLE users;
来源：http://dali.ehwqpu.com/Article/details/gt2ytakzmez.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gt2ffuzzrxm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenlongwang.top/Article/details/gt2tqwdihhq.html

[Q72] 查看索引
来源：http://dali.tanke756.top/Article/details/gt2zkgjcxzm.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2cezukrwo.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gt2uqykkvto.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gt2tlhfidmt.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gt2tgozmoyz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.havefunace.top/Article/details/gt2ufnytkiz.html

[Q75] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gt2ryoergih.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2xlizloxx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gt2jmxbeese.html


<!-- 参考信息 -->