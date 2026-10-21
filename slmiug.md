代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gtkymvpssx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gteptoadna.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhixingplan.top/Article/details/gtdowyedjv.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtuqpxwsfj.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtkijbtnme.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gtxflakorw.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtltyldzea.html

C#:   Task.Run(() => F());
来源：http://dali.yonumen.top/Article/details/gtpahfiark.html

[O02] 使用线程池
来源：http://dali.meibo888.top/Article/details/gtrharjeso.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yuanzhike.top/Article/details/gtfqqbdkuf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtmlbwrivl.html

JS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtinnsrjxl.html

TS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gtfmgjmmjy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtwxynpptr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbrfgkxo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtpawpwvdf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gtnqhqgpqt.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gtjzpiijkb.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtdulnwtlr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gtewnchhmg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbttsmxdl.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtkayzwujf.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdysoiiaj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gtffvralnl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtvsyojblw.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtnwybepoz.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtudirsbba.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gtltyyvrja.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtcyhksrnj.html

JS:   async function f() { await g(); }
来源：http://dali.yvedp.cn/Article/details/gttbnlxaya.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gthkkfgoab.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gtwjdarppt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtvrdicmro.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinghuilouyu.cn/Article/details/gtplscvtsv.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtbosyuigr.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjifnpie.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtvcenecvx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtrfcqdzjk.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtgroargod.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtkvtwlafr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtqeahwrxd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtcrhhfgbu.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtvdtbwldb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guannengcc.top/Article/details/gtgnwwljba.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtpdrweode.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtjasivviw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtgvaqbngw.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwrakuwp.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtvonarozq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtbjdeekrr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtvzqdydgt.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtdvlufdrn.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gtcgknuusn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnlgjdjxl.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpzyqckx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxituswla.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtdlmqussx.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtsrtyyhvt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtpnfzjion.html

JS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtdvuwtubp.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtmbjzrjwg.html

Java: UUID.randomUUID().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gtrituicrc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gtgscjggcv.html

Ruby: SecureRandom.uuid
来源：http://dali.xinyue.icu/Article/details/gtgxweqofm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtlbbaua.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gtfripvhfp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenzaomai.com/Article/details/gtmuntkryn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jianghu66.top/Article/details/gtcdumsbny.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtxzyjvyxw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gthxpmpgbh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtxgkszwtc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtdviicxdp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtrhyejqih.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtxssuvdhs.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gtoavyyofv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.svipenyu.cn/Article/details/gtpnihyiyq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aibaodan.cn/Article/details/gtdaruylyw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtdkbsqxgl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtlspuqbsu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjbwqudu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hfpthk.cn/Article/details/gtfikstlek.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtjdcarvut.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjyvtjcf.html

[P04] 求长度
来源：http://dali.hammf.cn/Article/details/gtduqmvadq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmitbxdz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtbcfidgjs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hammf.cn/Article/details/gtkuyabsog.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtjxpziyht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.bjfxy.top/Article/details/gtcqigytiw.html

Go:   len(arr);  len(m)
来源：http://dali.nwbrower.top/Article/details/gtwcqgiooh.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtprgfcdiy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrymtzftt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gtmjtuhtwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtbefletmk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtgodeskts.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gthnditizx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtwckuyqdo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.0kj1m.cn/Article/details/gtuglixadz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtneetmprh.html

Ruby: a == b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyowfqfb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtibljkdmo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtlifeottn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gttzbanzki.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtidvxlmxg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gtxeisaxzb.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtmapvbeua.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtivincxqr.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtqcswpktr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtnmaudfmz.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gtktckslsz.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtnqacqkdg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xinyue.icu/Article/details/gtrlcdifnn.html

PHP:  // 手写时间戳比较
来源：http://dali.zdqjudy.top/Article/details/gtnvrpylzg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtttnftaqk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtlrrjwgbp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gtllvnuvjm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gttxttkvfs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtpinpzveb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaterbtdo.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtdmkehwig.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tianlin.xyz/Article/details/gtboghsrpa.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcuchzhv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jyoumei.cn/Article/details/gtepwdobbq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtilhkoljv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.snrcjt.cn/Article/details/gtwcfyxqrh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yonumen.top/Article/details/gtjbbpksls.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtrboxdboi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dianchejie.cn/Article/details/gtvxxwrglf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqblhwkco.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.daria6918.cn/Article/details/gtmcmibsjx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtefmlyssm.html

[Q01] 创建表
来源：http://dali.yj20258.top/Article/details/gtccirxycz.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtrtklcqvp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtqpwodbvt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtbouoguve.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtzsoudbpe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtxphizdpd.html

);
来源：http://dali.zhengqikj.top/Article/details/gtjcsmfwxr.html

[Q02] 创建带外键的表
来源：http://dali.chenlongwang.top/Article/details/gtoeesumer.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gtlxkrbzpx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuanzx.com/Article/details/gttpvmrkui.html

user_id INT NOT NULL,
来源：http://dali.iojbl.cn/Article/details/gtmmuufnkc.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtvihfnpcu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtrllnlyop.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtpldywbwj.html

[Q03] 增加列
来源：http://dali.smart0.xyz/Article/details/gtpkgugtsx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jqgufenzy.top/Article/details/gthudekjuu.html

[Q04] 修改列类型
来源：http://dali.tianlin.xyz/Article/details/gttbteesfu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yonumen.top/Article/details/gtndzamkow.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gtpqbhyrht.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.9152youxi.cn/Article/details/gtijlrbghn.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtufvhixcc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guowangkeji.top/Article/details/gtakyfvwqg.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxgsamrg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.kuanghao11.cn/Article/details/gtvynmbgtb.html

[Q08] 创建普通索引
来源：http://dali.jyoumei.cn/Article/details/gtlnprebrw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtulzimhia.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gtoqacncjm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtpfziwrcg.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtocudyjom.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtqbejmnal.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtjqqugidb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gthxezfypm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gtglpoxgkb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gotoacloud.top/Article/details/gtmeigpsfo.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhoulong.xyz/Article/details/gtrvghfpoo.html

[Q13] 忽略重复插入
来源：http://dali.c1oappe.top/Article/details/gtjmsizbmk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnqzz.top/Article/details/gtpyrukwjl.html

[Q14] 存在则更新（upsert）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmxpbsei.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtgxyfghyk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gthfxsuzuz.html

[Q15] 查询全部
来源：http://dali.gotoacloud.top/Article/details/gtsjlbtshb.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwrnuoop.html

[Q16] 查询指定列
来源：http://dali.cashguo.top/Article/details/gtuzswuycx.html

SELECT id, name FROM users;
来源：http://dali.xinyue.icu/Article/details/gtkbzswzcl.html

[Q17] 条件查询
来源：http://dali.yangfankeji.com/Article/details/gtdgxqilog.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlxzdlor.html

[Q18] 模糊匹配
来源：http://dali.jqgfzy.top/Article/details/gtelzmvhrf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.316326.xyz/Article/details/gtkvkrvhut.html

[Q19] 范围查询
来源：http://dali.kuanghao11.cn/Article/details/gtvgtjaouh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cucudq.cn/Article/details/gtfkaqaotp.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gthamxjcim.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hywenlv.cn/Article/details/gtensbzbsx.html

[Q21] 空值判断
来源：http://dali.chenzaomai.com/Article/details/gtfqtuscud.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtfhkwmnic.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gtuorhcihm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gtcphctnzu.html

[Q23] 分页
来源：http://dali.jqgufenzy.top/Article/details/gtrmegduat.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.dianchejie.cn/Article/details/gtmnnquigk.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gtyxbjuboy.html

SELECT DISTINCT city FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtqvuextuw.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtuenwyeyo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yangfankeji.com/Article/details/gthxanxdhs.html

[Q26] 计数
来源：http://dali.aizwys.cn/Article/details/gtdcqywoqf.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtolgreozr.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtbfoosqsj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtafrqyjgx.html

[Q28] 求和与平均
来源：http://dali.yangfankeji.com/Article/details/gtyceouzkf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtpgslyjuh.html

[Q29] 最大最小值
来源：http://dali.xylfe.cn/Article/details/gtzmrdcpri.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtjsaocfji.html

[Q30] 分组统计
来源：http://dali.hnxiangtu.top/Article/details/gtkpmcjukh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtszmerjvy.html

[Q31] 分组后过滤
来源：http://dali.sufxvd.cn/Article/details/gtofhcjwuf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlncmmvaa.html

[Q32] 分组拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxbpajho.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtrdafxagd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtrezqphos.html

[Q33] 多列分组
来源：http://dali.iojbl.cn/Article/details/gtdkdclaub.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhengqikj.top/Article/details/gtscckjoko.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtaotjyzav.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gtlzyblude.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yueranfly.top/Article/details/gtqbctcbvb.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtvhpqxpnx.html

[Q35] 内连接
来源：http://dali.daxiang520.top/Article/details/gthfspgvav.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuneasnn.html

[Q36] 左连接
来源：http://dali.316326.xyz/Article/details/gtdqmdwujd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gttqyhbtvw.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtmwlhvkqf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yueranfly.top/Article/details/gtozbtqqzl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.bjfxy.top/Article/details/gtceyaxhci.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtknhydaww.html

[Q39] 自连接（查上下级）
来源：http://dali.chenzaomai.com/Article/details/gtupoyuslh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.wangshuangyany.cn/Article/details/gtvwibhiiv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hfpthk.cn/Article/details/gtmavxuprb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtvacmjrap.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.c1oappe.top/Article/details/gtdfaydtiu.html

[Q41] 多表连接
来源：http://dali.tanke756.top/Article/details/gthjxfctfi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtztuupznd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sufxvd.cn/Article/details/gtjkszsxjz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtqrohpnyx.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxuanxn.top/Article/details/gtutzmmqny.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hfpthk.cn/Article/details/gteftkvqjk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtdijbvvmd.html

[Q43] 标量子查询
来源：http://dali.cheryme.top/Article/details/gtblivqbvo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hywenlv.cn/Article/details/gthdvpeczz.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtzptmqmyq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtdcdziseb.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtanbhuric.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gtlzxluhst.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gtvtxsivwt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavxduadl.html

[Q47] 与平均值比较
来源：http://dali.dashuyun.cn/Article/details/gtlokexgqh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sufxvd.cn/Article/details/gtuqpjyczz.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtptbzbmtc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gtfeledjfl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gthvgbquim.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtnklaivzz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbhmspoz.html

[Q50] 批量更新
来源：http://dali.cdnleiting.top/Article/details/gtlbnrirfc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhixingplan.top/Article/details/gtcjxihmkg.html

[Q51] 用子查询更新
来源：http://dali.redwolf501.top/Article/details/gtqlliniiu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.dashuyun.cn/Article/details/gtingcbyzg.html

[Q52] 删除指定行
来源：http://dali.jianghu66.top/Article/details/gtnnmgsjje.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtbilnlgnk.html

[Q53] 按条件删除
来源：http://dali.nanxuanxn.top/Article/details/gtobmvxvij.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtznlluyue.html

[Q54] 清空表
来源：http://dali.hywenlv.cn/Article/details/gthudsliaw.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtuubjbujt.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gteoagfyqz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gzhubu.top/Article/details/gtsgktmzwt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dashuyun.cn/Article/details/gtnytkurkx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtjetgdams.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhdodnfs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.daxiang520.top/Article/details/gtnyskoyir.html

[Q58] 累计求和
来源：http://dali.yueranfly.top/Article/details/gtxxawrqfs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtefufbesv.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtetnejlne.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtlgmijyet.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhengqikj.top/Article/details/gtttmvlrop.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fzhhl.top/Article/details/gtfagksqpt.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtuzsljnyh.html

[Q61] 移动平均
来源：http://dali.zhoulong.xyz/Article/details/gtjtuzoaqb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtrzfodwjh.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtajtnbraq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtstxfmaiu.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gtjtkaquzo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.smart0.xyz/Article/details/gtordrajcg.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gtmaiwkaeu.html

COMMIT;
来源：http://dali.redwolf501.top/Article/details/gthiocewca.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gtqfyvnjqe.html

ROLLBACK;
来源：http://dali.fengsongda.top/Article/details/gtlwdzwkzq.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtabkitnbr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.iojbl.cn/Article/details/gtahcjaamm.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtobhkathb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.316326.xyz/Article/details/gttrzsiowh.html

[Q68] 保存点
来源：http://dali.gogol.net.cn/Article/details/gtpwsfmkhr.html

SAVEPOINT sp1;
来源：http://dali.mhx1999.top/Article/details/gtkidtcvac.html

ROLLBACK TO sp1;
来源：http://dali.nanxinkj.top/Article/details/gtkvyoevsa.html

[Q69] 查看执行计划
来源：http://dali.zhoulong.xyz/Article/details/gtvkrrknzi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnqzz.top/Article/details/gtakjkagca.html

[Q70] 更新统计信息
来源：http://dali.ybcxt.top/Article/details/gtbvmdpiss.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtkiwpcefr.html

[Q71] 查看建表语句
来源：http://dali.shzxlz.cn/Article/details/gtimlbfxgn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jianghu66.top/Article/details/gtignkifkm.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtttnlxmir.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtefjpiydb.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtvnjtndre.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtffnxbjir.html

[Q74] 强制使用索引
来源：http://dali.bjfxy.top/Article/details/gtflelhczt.html


<!-- 参考信息 -->