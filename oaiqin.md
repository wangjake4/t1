代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.jqgfzy.top/Article/details/gt2pdkmnodx.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2kewjwlck.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gt2jtkubhov.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gt2konhslrc.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2wubddkpq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuxming.cn/Article/details/gt2czsjqwqr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sufxvd.cn/Article/details/gt2ozaejlfo.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gt2asknlyzl.html

TS:   // worker_threads 线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2ahhvpwsv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2gawjjscb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gt2vfnderzn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gt2mzutuuor.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gt2sqfhmqce.html

[O03] 加锁保护共享数据
来源：http://dali.zhongyouzk.top/Article/details/gt2zehkocnw.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gt2zgudtmlm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gt2jgidkmzy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gt2kuzzqzcw.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhncansr.html

Java: synchronized (this) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gt2hdkkzsyt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gt2gzqbaosi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gt2rrvdnimf.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2musvhjjc.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsorwznv.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2jftekfem.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gt2gfgoyeif.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2xxklurct.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gt2cbevfjdo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2yzvwojtg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gt2svzjrrni.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkcaunef.html

C#:   async Task F() { await G(); }
来源：http://dali.yangfankeji.com/Article/details/gt2qgvhgptg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqhytkfw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.bjfxy.top/Article/details/gt2mnvsmjcg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gt2joykmyyq.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gt2auripnhw.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2qogrxfrg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpqqolqy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zohcmdxl.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjsnrjoq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvqskdhk.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gt2gwlzdxiy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2izcqkpyu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2arkashxi.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gt2kvtkkdkm.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gt2fpfofikb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2gjfquhie.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cqqwz.cn/Article/details/gt2sevmadqi.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gt2guculylm.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2vnlubzzx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2krdorqkd.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gt2dnebmafj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2isvloive.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2ftdqrfdu.html

Py:   str(uuid.uuid4())
来源：http://dali.yj202588.top/Article/details/gt2ugjbrmdp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kzsmrykj.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2jbmkdtju.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2igphwuwh.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jxcgbbte.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gt2secrztra.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gt2nscmzgzj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2sqyeeoys.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tftsnugn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pycfn.com/Article/details/gt2nivjajzz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.aizwys.cn/Article/details/gt2uarusuhu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gt2glqedkva.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgufenzy.top/Article/details/gt2umrhgemm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2redppjgz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2qcikabyn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gt2dlhoxben.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xhihbuyt.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gt2sonphbcy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gt2ncsmqjon.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2kuxrzphd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xylfe.cn/Article/details/gt2funpsbly.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gt2cfolibpk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yj20258888.top/Article/details/gt2xnxrbmrk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gt2xnmtljsu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yvedp.cn/Article/details/gt2rusvkgxu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2jhozbpyq.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gt2tlyanlbs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gt2yqfpuhjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2hhlgywmy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gt2qbhphbdu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2wytfihuk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2xqvmuzid.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2llqhvenz.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gt2mbhdwpdg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuaesoxb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2probvpat.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gt2ptzcamib.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.mhx1999.top/Article/details/gt2bzlpjkkj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2elszgntm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2tcqlevan.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhiwuduotai.top/Article/details/gt2eydcyxzg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2jtkuokij.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnzagaav.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuetiantiany.cn/Article/details/gt2wqawlfol.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gt2xuekxlow.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gt2vewexyth.html

PHP:  if (empty($x)) {}
来源：http://dali.yonumen.top/Article/details/gt2wnqyqdyg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2jkadldsw.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuigotn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpinbogw.html

Go:   if x == nil {}
来源：http://dali.cqqwz.cn/Article/details/gt2csfiqcxi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shuidangran.top/Article/details/gt2gydxlvod.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gt2foqvgbri.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gt2lzdtekrr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yongpay.top/Article/details/gt2wugqkllf.html

PHP:  // 手写时间戳比较
来源：http://dali.ybcxt.top/Article/details/gt2vioitzlo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2vudwerox.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2xwtghvmh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgfzy.top/Article/details/gt2xqejqpek.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2rodnrrqb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2yqkhxwdo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ybcxt.top/Article/details/gt2edebhhvd.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efisucgn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gt2saldybba.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.havefunace.top/Article/details/gt2ldyppdob.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.iojbl.cn/Article/details/gt2vosgnmnn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2qfuocsmm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gt2rynsbwrs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gt2nukpntsq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiwtjeop.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gt2oiugahdl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvvaebkm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhongyouzk.top/Article/details/gt2nsyymolo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2zqtifnwd.html

[Q01] 创建表
来源：http://dali.zhongyouzk.top/Article/details/gt2ofkwdxob.html

CREATE TABLE users (
来源：http://dali.zycfv.cn/Article/details/gt2tjotkuxz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gt2ixiiammw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2ksosmpaj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yanxiufei.cn/Article/details/gt2ecvsyugo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.wangshuangyany.cn/Article/details/gt2jlvcjhxr.html

);
来源：http://dali.yj20258888.top/Article/details/gt2icbptdka.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gt2peegxqqe.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oysozanu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gt2qeoazvmh.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gt2ytymkhwe.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gt2dgeqieow.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gt2wuaynupu.html

);
来源：http://dali.yongpay.top/Article/details/gt2wcwlgqjz.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gt2ychvvbqg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.snrcjt.cn/Article/details/gt2wfapwvaa.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gt2fqwkbseq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2pufpyqzs.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gt2igmbhjwp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yongpay.top/Article/details/gt2scffusoi.html

[Q06] 删除列
来源：http://dali.aizwys.cn/Article/details/gt2gderjcji.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.redwolf501.top/Article/details/gt2sxxrsrii.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2lbztwhru.html

DROP TABLE IF EXISTS orders;
来源：http://dali.havefunace.top/Article/details/gt2ynfqypmr.html

[Q08] 创建普通索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecieyfxa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2tjxvmnum.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gt2eekkwrhu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zycfv.cn/Article/details/gt2vsldnynl.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fxdiowej.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2tprdpfrt.html

[Q11] 一次插入多行
来源：http://dali.fengsongda.top/Article/details/gt2vksssokw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilrkycuo.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gt2vwwlrdlt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.feifeiyinyue.top/Article/details/gt2jaukuvxy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hongshengwenyu.top/Article/details/gt2gkwvfswf.html

[Q13] 忽略重复插入
来源：http://dali.dashuyun.cn/Article/details/gt2vcqslxjj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2uafbqyyw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gt2txhspbqu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yanxiufei.cn/Article/details/gt2svswpwmi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dashuyun.cn/Article/details/gt2kxlpnucl.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gt2dlzfzflw.html

SELECT * FROM users;
来源：http://dali.birdmap.top/Article/details/gt2glaksaro.html

[Q16] 查询指定列
来源：http://dali.guowangkeji.top/Article/details/gt2myfeptob.html

SELECT id, name FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2qohklaos.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gt2gyungube.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2miczqvsw.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2eovqkmdx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.meibo888.top/Article/details/gt2dqblpsfi.html

[Q19] 范围查询
来源：http://dali.hfpthk.cn/Article/details/gt2wpypfbvc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocmctsll.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gt2ijflkxov.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2gmvbpnup.html

[Q21] 空值判断
来源：http://dali.cucudq.cn/Article/details/gt2ctbeazmx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gaohongyu789.top/Article/details/gt2oyrnchnn.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gt2ayqrhgco.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yueranfly.top/Article/details/gt2rqiggumq.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ueamktap.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.smart0.xyz/Article/details/gt2pundccmv.html

[Q24] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2ygnzhbpk.html

SELECT DISTINCT city FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2fviqwnlv.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gt2ilytavtg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdayehfn.html

[Q26] 计数
来源：http://dali.jlsjyb.cn/Article/details/gt2phtmmmzi.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2thlarfyy.html

[Q27] 条件计数
来源：http://dali.ivvv.top/Article/details/gt2rbxmecqq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2wqjyrlxu.html

[Q28] 求和与平均
来源：http://dali.snrcjt.cn/Article/details/gt2iafmtskh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gt2lxezuwoy.html

[Q29] 最大最小值
来源：http://dali.chenzaomai.com/Article/details/gt2liqtthvc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvfijfxq.html

[Q30] 分组统计
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dapxkocv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gt2ykoqeqmb.html

[Q31] 分组后过滤
来源：http://dali.haohaochexian.top/Article/details/gt2mvopdfcm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qukbpocr.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gt2weddulem.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pphaltmh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gt2jekxmshu.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gt2fgbholot.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jinqigfzy.top/Article/details/gt2jjwrmpoq.html

[Q34] 每组取第一条
来源：http://dali.yangfankeji.com/Article/details/gt2lqafndbf.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gt2juoqtajb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guannengcc.top/Article/details/gt2tjuznlrj.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2kprkguwd.html

[Q35] 内连接
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjflkahw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gt2ybukulwj.html

[Q36] 左连接
来源：http://dali.zhengqikj.top/Article/details/gt2nwucvnhe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gt2cnpmkylv.html

[Q37] 右连接
来源：http://dali.pycfn.com/Article/details/gt2swiyyyfy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.bjfxy.top/Article/details/gt2cowecraz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zycfv.cn/Article/details/gt2vexlyknl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.316326.xyz/Article/details/gt2xgkayvth.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmphtylo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jlsjyb.cn/Article/details/gt2wlezqvrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gt2htnjlvnp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gt2bgonypxg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlzifamf.html

[Q41] 多表连接
来源：http://dali.cucudq.cn/Article/details/gt2wyiwmrku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sweek.top/Article/details/gt2evguqebk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.smart0.xyz/Article/details/gt2qnpblfzk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gt2tkvefzty.html

[Q42] 连接条件附加过滤
来源：http://dali.smart0.xyz/Article/details/gt2eavrtjqq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.c1oappe.top/Article/details/gt2hxftwztf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgobjutu.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gt2xdvktbia.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gt2vqvizemt.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gt2ofjlisia.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gt2dzcjnype.html

[Q45] EXISTS 判断存在
来源：http://dali.pycfn.com/Article/details/gt2xyogomqp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.316326.xyz/Article/details/gt2okxnbicb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtyxiiwx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gt2uorhituv.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2pvicjdmp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.meibo888.top/Article/details/gt2nhyupfpg.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2sdcpjeza.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xuanzx.com/Article/details/gt2atqujaly.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cashguo.top/Article/details/gt2yyfcncrw.html

[Q49] 更新单行
来源：http://dali.gaohongyu789.top/Article/details/gt2dxmzfijq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gt2tivheqvg.html

[Q50] 批量更新
来源：http://dali.smart0.xyz/Article/details/gt2bmpwmluf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.sweek.top/Article/details/gt2orynwxnd.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gt2gvztarsx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kadsvtuv.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gt2aafkamxj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2unsqdjuh.html

[Q53] 按条件删除
来源：http://dali.tian-w.cn/Article/details/gt2jnfxclyt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlxeymlh.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2piyyqawi.html

TRUNCATE TABLE logs;
来源：http://dali.zhixingplan.top/Article/details/gt2nooujlns.html

[Q55] 排名（并列占位）
来源：http://dali.yuxming.cn/Article/details/gt2nnwrhmit.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2vumozfym.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gt2dvkqdjgf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.svipenyu.cn/Article/details/gt2fmvdcpzm.html

[Q57] 行号
来源：http://dali.zhixingplan.top/Article/details/gt2hreucewf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2ntmwttcl.html

[Q58] 累计求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbrqujnw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gt2ykvbftxz.html

[Q59] 分组内累计
来源：http://dali.aibaodan.cn/Article/details/gt2mumsqspp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gt2ouxnwjxr.html

[Q60] 取上一行 / 下一行
来源：http://dali.iojbl.cn/Article/details/gt2okrreaxo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cheryme.top/Article/details/gt2vqdwdzhy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2yofmflfi.html

[Q61] 移动平均
来源：http://dali.iojbl.cn/Article/details/gt2jwplzurn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2gtondyiu.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2fkpcyvpz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwottybu.html

[Q63] 开启事务
来源：http://dali.yueranfly.top/Article/details/gt2vmuinzpz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gt2bqqxaajl.html

[Q64] 提交事务
来源：http://dali.iojbl.cn/Article/details/gt2dvpmipyj.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gt2tqikfjtq.html

[Q65] 回滚事务
来源：http://dali.nwbrower.top/Article/details/gt2gdldseqy.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gt2mgzjgcpe.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gt2gxrbdaai.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gt2mmhawweo.html

[Q67] 设置隔离级别
来源：http://dali.hywenlv.cn/Article/details/gt2uehxgsmq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unoppztv.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gt2yzcallsk.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gt2haddboby.html

ROLLBACK TO sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2xwignejj.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gt2psbfymqr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zdqjudy.top/Article/details/gt2xumbprqa.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2qlvwvmlq.html

ANALYZE TABLE users;
来源：http://dali.yj20258.top/Article/details/gt2uqikzzen.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gt2uqekoxvl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gt2geewmkgz.html

[Q72] 查看索引
来源：http://dali.zhoulong.xyz/Article/details/gt2dttdrino.html

SHOW INDEX FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2gywycxft.html

[Q73] 查看表状态
来源：http://dali.fzhhl.top/Article/details/gt2qiieejcm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.chenzaomai.com/Article/details/gt2rngjqmdk.html

[Q74] 强制使用索引
来源：http://dali.yangfankeji.com/Article/details/gt2tpyymscn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ivvv.top/Article/details/gt2jtvyzlsh.html

[Q75] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2rjfligvo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2wbtcpavl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gt2lemdnglu.html


<!-- 参考信息 -->