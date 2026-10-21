代发 wailian999

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtqbphxfwu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gtssitonrk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nanxinkj.top/Article/details/gtcqzsgmbu.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtxxrbfzuj.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtwizyzexu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gthuzsiidd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtgezrqspf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtiyduexqg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xylfe.cn/Article/details/gtrnldwtmn.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtqjruqwaw.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gtvcemrhsz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtuquyysgs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hywenlv.cn/Article/details/gtozpboqct.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gthpvpntlo.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gttqyjjpyj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtsioasqea.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpefzpjxh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaarnnvr.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtdqpozehz.html

Py:   async def f():⏎    await g()
来源：http://dali.cdnleiting.top/Article/details/gtahsrwkcu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhengqikj.top/Article/details/gtffkgplnb.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtsbeptjyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtscvcwsjd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtsnbheaky.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtcscojkit.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtsemaocru.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtpzhbrpbk.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gtrbldstkw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtnvtcrarw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gtykcjwclv.html

JS:   await Promise.all(tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtjfyzuv.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtlefpwsvd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yonumen.top/Article/details/gtifprkkpz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jinqigfzy.top/Article/details/gtyehtmhqr.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gtzlxcbbxp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtmcgpgmfu.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtbblknyxk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtjgguvuba.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.c1oappe.top/Article/details/gtilyphrzg.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtfijtfdci.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gthswihzal.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj202588.top/Article/details/gtpihbheic.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtballhzih.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtkarmubdm.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtdunxggra.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbaxtxrsb.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtrrlejxal.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttyksgodn.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtwoltvuyw.html

Py:   str(uuid.uuid4())
来源：http://dali.tianlin.xyz/Article/details/gtiubgstrv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.316326.xyz/Article/details/gtqbtmdckr.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtraoxdbrj.html

TS:   crypto.randomUUID()
来源：http://dali.hywenlv.cn/Article/details/gtmopvzzcw.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtjypeldik.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtzaeozypg.html

Ruby: SecureRandom.uuid
来源：http://dali.daria6918.cn/Article/details/gtemmnslan.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtcymxctju.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fzhhl.top/Article/details/gthhaxhxrb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtatvphfcr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gtcsfsxesy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.haohaochexian.top/Article/details/gtbmlsrsil.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtctgeodla.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangtech.top/Article/details/gtynjsuazr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtpslpggvw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cdnleiting.top/Article/details/gtqdennysi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtfwhwvsmw.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gtpsmjubjr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pycfn.com/Article/details/gtevdwvepp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenlongwang.top/Article/details/gtejznadxo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuanzhike.top/Article/details/gtbweoiwzl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtoskksaku.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtbktehzvx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtvphhiutp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnqzz.top/Article/details/gtlelzhjiq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtuhvzdsys.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtiekqhynq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.316326.xyz/Article/details/gtzxjgbhjr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtckwcrudb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtjofnilid.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gogol.net.cn/Article/details/gtnmfgfzvu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gtgnbqyozv.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtkrpdlnmv.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtqdegiovi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zdqjudy.top/Article/details/gtqlivnasi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sufxvd.cn/Article/details/gtsjesstnj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gtggzozpxr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtwaluqkvq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gtkkbbzdrq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpmahovph.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gaohongyu789.top/Article/details/gtwqmtuxoo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xylfe.cn/Article/details/gtvkqjwywh.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtseiqtgmm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.redwolf501.top/Article/details/gtifqytczc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.aizwys.cn/Article/details/gtbcyrudsy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gtxtfjndqs.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtzhiasyvk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yanxiufei.cn/Article/details/gtrkltmaau.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtudtxgizc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtnsbtccke.html

Go:   if x == nil {}
来源：http://dali.jiagoushi.top/Article/details/gtwyrbzfvl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gtddxpwvio.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gthcdfwsja.html

[P07] 防抖与节流
来源：http://dali.wangdashe.top/Article/details/gtiszyxncc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtubymdirx.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gtfnzxebpd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnxqiwzd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtftbhabhg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.bjfxy.top/Article/details/gtzbuisqxa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtdyurzczm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtowmykegu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuxming.cn/Article/details/gtbqkmvjcm.html

[P08] 处理浮点精度问题
来源：http://dali.c1oappe.top/Article/details/gtzjjevxxo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gteqpwfoar.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.andypj.xyz/Article/details/gttoyutlys.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbunpwukx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtklsibslb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gzhubu.top/Article/details/gthgulxtfg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtxhgtlubj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gzhubu.top/Article/details/gtjwsnyhbi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtlezfhjcr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxibsayfo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gtbtslnteg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthhwtmcca.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gtjggbcsdv.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtvqjszeqi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjiafzam.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxjalrkb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtordpfmuo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj202588.top/Article/details/gtoukjczwh.html

);
来源：http://dali.yj202588.top/Article/details/gtyqllessh.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtlkwropus.html

CREATE TABLE orders (
来源：http://dali.chenzaomai.com/Article/details/gtdfiolnxd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuxming.cn/Article/details/gtpgmwltnd.html

user_id INT NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtkavzfdxz.html

amount DECIMAL(10, 2),
来源：http://dali.c1oappe.top/Article/details/gtgadddesh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gttbxuxpil.html

);
来源：http://dali.andypj.xyz/Article/details/gtizvckfbx.html

[Q03] 增加列
来源：http://dali.jqgufenzy.top/Article/details/gtlymxhapg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gtjbosbkmq.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtqosbrnps.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtjprqnnpc.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gtmsombmjd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.chenlongwang.top/Article/details/gtobbhdiux.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtnrixzpai.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xziqi.cn/Article/details/gtedyeehkb.html

[Q07] 删除表
来源：http://dali.birdmap.top/Article/details/gticjehqmz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dianchejie.cn/Article/details/gtftbvvbtz.html

[Q08] 创建普通索引
来源：http://dali.svipenyu.cn/Article/details/gtkhuxgkos.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhongyouzk.top/Article/details/gtekjtkkko.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangtech.top/Article/details/gthzegyovq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258.top/Article/details/gtnpaikuiu.html

[Q10] 插入单行
来源：http://dali.zhongyouzk.top/Article/details/gtlxtehcjf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtprqlwahb.html

[Q11] 一次插入多行
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkuhlnoa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.redwolf501.top/Article/details/gtjfxaltnh.html

[Q12] 插入后取自增 ID
来源：http://dali.yuxming.cn/Article/details/gtnhclfwpw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtvibgucww.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jiagoushi.top/Article/details/gtosdpnney.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtdcvifgow.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtyhuqemmc.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtxajuzxsx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gthobddyuy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gtgcrplxdq.html

[Q15] 查询全部
来源：http://dali.tian-w.cn/Article/details/gtnxxdzzba.html

SELECT * FROM users;
来源：http://dali.ybcxt.top/Article/details/gttcrmfram.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtcqffinti.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gthbayrpss.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibzwysjs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yangfankeji.com/Article/details/gtyhwevaxy.html

[Q18] 模糊匹配
来源：http://dali.yj20258.top/Article/details/gtcmwiwjcl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zycfv.cn/Article/details/gtgvdflsrm.html

[Q19] 范围查询
来源：http://dali.xuanzx.com/Article/details/gtzggpxblt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yvedp.cn/Article/details/gtdlbzriiv.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gttuasbqbk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sysykeji.top/Article/details/gttwzzbclg.html

[Q21] 空值判断
来源：http://dali.pycfn.com/Article/details/gtiyepqfiq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ppjwa.cn/Article/details/gtblfkdrcv.html

[Q22] 排序
来源：http://dali.wangdashe.top/Article/details/gtkmwnuouj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.birdmap.top/Article/details/gtsdwfqoiv.html

[Q23] 分页
来源：http://dali.c1oappe.top/Article/details/gtiakdgcbb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hysaishi.cn/Article/details/gtliowcxqh.html

[Q24] 去重
来源：http://dali.aizwys.cn/Article/details/gtdeuoblny.html

SELECT DISTINCT city FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzvnaflr.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtkszgwbro.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zycfv.cn/Article/details/gtgjzecftz.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtdbcznxja.html

SELECT COUNT(*) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtuxnzaliy.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtetxoxyge.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtijkmedfm.html

[Q28] 求和与平均
来源：http://dali.meibo888.top/Article/details/gtgbtvwpeo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtqrldmhzk.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtsxwbebyo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtddhnmpnu.html

[Q30] 分组统计
来源：http://dali.jiagoushi.top/Article/details/gtyhczkoux.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtlfwryupk.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtahdvxchn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.meibo888.top/Article/details/gtgeuuopwk.html

[Q32] 分组拼接字符串
来源：http://dali.316326.xyz/Article/details/gtdsyobjhy.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gttjlaqrmw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258888.top/Article/details/gticpaigdv.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtkkkaxujl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gtwfmqfyiv.html

[Q34] 每组取第一条
来源：http://dali.jlsjyb.cn/Article/details/gtnpypfmko.html

SELECT * FROM (
来源：http://dali.hfpthk.cn/Article/details/gtilpvuuim.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jyoumei.cn/Article/details/gtmsanzwrq.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gttulswdoh.html

[Q35] 内连接
来源：http://dali.zhongyouzk.top/Article/details/gtrhuyxpeh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtcdbhrvnw.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gtefzlafrc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gtiqwjcrof.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtittqsdbi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gttpapgyuw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtconvyvas.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjabwnopo.html

[Q39] 自连接（查上下级）
来源：http://dali.jqgufenzy.top/Article/details/gtvubmmyvr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.haohaochexian.top/Article/details/gtwesfaqto.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhiwuduotai.top/Article/details/gtndgrgkfk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.haohaochexian.top/Article/details/gtygmnxxwy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtspdszyhj.html

[Q41] 多表连接
来源：http://dali.xylfe.cn/Article/details/gtfcvpmwlp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sxryk.cn/Article/details/gthsqkzknn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhengqikj.top/Article/details/gtddwrxlwb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.guannengcc.top/Article/details/gtyfhdbmce.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtvfksadee.html

SELECT u.name, o.amount FROM users u
来源：http://dali.feifeiyinyue.top/Article/details/gtcdkiwijk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtyyyhtqht.html

[Q43] 标量子查询
来源：http://dali.mhx1999.top/Article/details/gtzamssufv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtdcuacwst.html

[Q44] IN 子查询
来源：http://dali.hywenlv.cn/Article/details/gtdjmisrub.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.shuidangran.top/Article/details/gtakwjeolt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhixingplan.top/Article/details/gtcvukmzzr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.dashuyun.cn/Article/details/gtlkbwxyfv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtnzrmshdd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gtfaewsmhl.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gthuqpvhsl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtntushukn.html

[Q48] CTE 公用表表达式
来源：http://dali.xziqi.cn/Article/details/gtiwjoemqk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtfpoaaxpg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.haohaochexian.top/Article/details/gtiztyhuim.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gthmqejvtz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtlkgjjcyi.html

[Q50] 批量更新
来源：http://dali.svipenyu.cn/Article/details/gtrxpajzkc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnxiangtu.top/Article/details/gtdqrmzibg.html

[Q51] 用子查询更新
来源：http://dali.guannengcc.top/Article/details/gtkkbjzrqf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtdzfkzuxy.html

[Q52] 删除指定行
来源：http://dali.jinqigufen.top/Article/details/gtkyneeycj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtdnrvpexf.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtupculbic.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daria6918.cn/Article/details/gtvxixxcca.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtgrrilstd.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gtxbszkymb.html

[Q55] 排名（并列占位）
来源：http://dali.svipenyu.cn/Article/details/gtqiousnsf.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtbugeyoqo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cucudq.cn/Article/details/gtizshrlzo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dashuyun.cn/Article/details/gtiffiwxpw.html

[Q57] 行号
来源：http://dali.316326.xyz/Article/details/gtwzwzyvgz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.smart0.xyz/Article/details/gtnccwwcjg.html

[Q58] 累计求和
来源：http://dali.yongpay.top/Article/details/gtjterqkny.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtsxjeefoe.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gthjbchwec.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtjvlnypjp.html

[Q60] 取上一行 / 下一行
来源：http://dali.jiagoushi.top/Article/details/gtbhimawcu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jyoumei.cn/Article/details/gtdlausewm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtjrrmfifk.html

[Q61] 移动平均
来源：http://dali.jianghu66.top/Article/details/gtyiufhxwb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtkpmjofrt.html

[Q62] 分组占比
来源：http://dali.gzhubu.top/Article/details/gtplgiszqs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtipilicwp.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtybqjjoci.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhiwuduotai.top/Article/details/gtegagpxur.html

[Q64] 提交事务
来源：http://dali.hnqzz.top/Article/details/gtkqhuhunp.html

COMMIT;
来源：http://dali.yangfankeji.com/Article/details/gtqiogmywa.html

[Q65] 回滚事务
来源：http://dali.jqgufenzy.top/Article/details/gtjirqngos.html

ROLLBACK;
来源：http://dali.zhengqikj.top/Article/details/gtyahwiolj.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtwhwouykl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.svipenyu.cn/Article/details/gtqwqvoknz.html

[Q67] 设置隔离级别
来源：http://dali.jinqigufen.top/Article/details/gtvgzupxiq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gtufpmtnsm.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtcetlhpzf.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtlixipnrj.html

ROLLBACK TO sp1;
来源：http://dali.zdqjudy.top/Article/details/gtrkfyfdtq.html

[Q69] 查看执行计划
来源：http://dali.nanxuanxn.top/Article/details/gtubbqppdc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyyiefben.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gteinddqey.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtlpzzepdh.html

[Q71] 查看建表语句
来源：http://dali.snrcjt.cn/Article/details/gtvhuhzkqo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtsycnpben.html

[Q72] 查看索引
来源：http://dali.nanxinkj.top/Article/details/gtwgpiclga.html

SHOW INDEX FROM users;
来源：http://dali.smart0.xyz/Article/details/gtyqsryqtn.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gtwyfllper.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtaeankhad.html

[Q74] 强制使用索引
来源：http://dali.xuetiantiany.cn/Article/details/gtsuqdsulg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gthawoffhu.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtptbjxbsl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtbyldwncf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtockixjqa.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gtkazfcxqq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtpnpsceyd.html

[Q77] 时间加减
来源：http://dali.0kj1m.cn/Article/details/gtbtmyetgq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gtwhgxvfhk.html


<!-- 参考信息 -->