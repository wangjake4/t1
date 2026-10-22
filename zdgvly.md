代发 wailian999

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtheqlznun.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtdxqjwehf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gtbhmxjvkr.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtmzwysngi.html

TS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtgrpancnv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gtmwmiilnw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtkgmiaqgy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gttbqjjifb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gtmcqznxpn.html

[O03] 加锁保护共享数据
来源：http://dali.smart0.xyz/Article/details/gtrufruola.html

Py:   with lock: shared += 1
来源：http://dali.cqqwz.cn/Article/details/gtovcpzgxl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtustygauq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gthrsgvaiz.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtolbqvnus.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfsbeulr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zdqjudy.top/Article/details/gtmuncgjdg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtxbtkrcqp.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtplgispiu.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gttzaxejhk.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtwrqrxyjy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftcomjdw.html

JS:   async function f() { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtcttnoayh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtfjtrscrn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nwbrower.top/Article/details/gtjhetlufq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtxduwvinx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhixingplan.top/Article/details/gtwabgconc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpdbstwjp.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtyxhncabr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqztsuemg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sysykeji.top/Article/details/gtwzkwebib.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtbluvdkyv.html

TS:   await Promise.all(tasks)
来源：http://dali.ydzc1.top/Article/details/gtqmtwyfnf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gtgoxycprc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtrjevzblw.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtkvplscjp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtvtxzkhfh.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtwryzpxhj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjjtzipy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtypszkkzp.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtylxogprz.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtosytxixt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtbltwboau.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtgahhwjhp.html

Ruby: // fork 块
来源：http://dali.pengpengdd.cyou/Article/details/gtbhagpbux.html

C#:   Parallel.For
来源：http://dali.xuanzx.com/Article/details/gtukavxqju.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttxgufqqc.html

P. 常用工具函数
来源：http://dali.jqgfzy.top/Article/details/gtkxtnkses.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwwxnjbfb.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtdclalcpx.html

Py:   str(uuid.uuid4())
来源：http://dali.sufxvd.cn/Article/details/gtzcnkdnrd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtkodrxqye.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtqlgdaejg.html

TS:   crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtwcyynbsn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtmhxqdrbt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtmdecpvgd.html

Ruby: SecureRandom.uuid
来源：http://dali.yj202588.top/Article/details/gthxiasmsd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtdijvrbqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xinyue.icu/Article/details/gtheijnmqq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.mhx1999.top/Article/details/gtbbkneboz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtgmyuupzd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtwsyylylo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtvxrlnaxe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.bjfxy.top/Article/details/gtdwtzyquv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gtyhuzsiud.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.iojbl.cn/Article/details/gtomqmzqgl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.feifeiyinyue.top/Article/details/gtzlyiwhbl.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtkgvaoepp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yueranfly.top/Article/details/gtwdrcgcly.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.kuanghao11.cn/Article/details/gtifxcajyd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtbdxpmzeb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtpvkfahkd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.0kj1m.cn/Article/details/gtzexlrygc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gtpfhwkblh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cdnleiting.top/Article/details/gtmzkfxrup.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.316326.xyz/Article/details/gtjqhhcxar.html

[P04] 求长度
来源：http://dali.zhixingplan.top/Article/details/gtunpycpxl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gtscvsbuoi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtnavvrnit.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtyooxuoow.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gtamlzdudg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtdqymodkt.html

Go:   len(arr);  len(m)
来源：http://dali.pycfn.com/Article/details/gtxbohmahk.html

Ruby: x.length;  x.size
来源：http://dali.jqgufenzy.top/Article/details/gtwysklyrq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtvuaszkmo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hywenlv.cn/Article/details/gtwubajcnv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtysiapxgb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtszapkvbp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtrenroomp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtxnjsuyud.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtptnvsvsa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtjllrqqio.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlftobit.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gotoacloud.top/Article/details/gtvtlmstvh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.dianchejie.cn/Article/details/gtgslxncex.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gtquygrkdb.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtpmmqrgvx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtbjpboijk.html

TS:   if (x == null) {}
来源：http://dali.chenzaomai.com/Article/details/gtwdmqktnh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtrbenkcha.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gtwnjqbpyx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtnfmynvkp.html

C#:   if (x is null) {}
来源：http://dali.xinyue.icu/Article/details/gtmejzasfm.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtghbwislm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmgogkwd.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtlxyzgkbs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtthuhsvdu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtybbgzqgk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gtnrgzxwep.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gtkyzoaqxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsiadmar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkqicmtc.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gtywgslkjn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhongyouzk.top/Article/details/gtrmbqhqho.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwznnkbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.kuanghao11.cn/Article/details/gtcbofjtlv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtjjnoktlu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gtelbgnvzx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtnwhsweoi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtmkxxvzcg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xuanzx.com/Article/details/gtkdbuycrd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtsqowzdve.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gogol.net.cn/Article/details/gtsgbvhnom.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttvrzxeho.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gtqyxeubdt.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gtmxajuwgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtimvjpkzo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtsmfbstmx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.smart0.xyz/Article/details/gtyiqolbye.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtbgmcnpco.html

);
来源：http://dali.yueranfly.top/Article/details/gtdqfeaukp.html

[Q02] 创建带外键的表
来源：http://dali.jiagoushi.top/Article/details/gtwawshkno.html

CREATE TABLE orders (
来源：http://dali.yj20258888.top/Article/details/gtolvuxvdl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxteycye.html

user_id INT NOT NULL,
来源：http://dali.sweek.top/Article/details/gtepgonzak.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxixmvxrq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtwjrunieh.html

);
来源：http://dali.haohaochexian.top/Article/details/gtyimemjuo.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtbfjtgtqm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvybbggj.html

[Q04] 修改列类型
来源：http://dali.shuidangran.top/Article/details/gtjnnnqktv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ppjwa.cn/Article/details/gtkexxkmfq.html

[Q05] 重命名列
来源：http://dali.dianchejie.cn/Article/details/gtkvrvitiy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.havefunace.top/Article/details/gtgudojqck.html

[Q06] 删除列
来源：http://dali.tianlin.xyz/Article/details/gtypllbkgi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuanzhike.top/Article/details/gtckqgkndo.html

[Q07] 删除表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfiunbde.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtmtgwzgru.html

[Q08] 创建普通索引
来源：http://dali.yueranfly.top/Article/details/gtourescvk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtorkjuull.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gtxqdkkonl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtjfrdazlx.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gttgynpxse.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.kuanghao11.cn/Article/details/gtrgyptwrc.html

[Q11] 一次插入多行
来源：http://dali.sufxvd.cn/Article/details/gtzzgfzuaq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gthucycbfk.html

[Q12] 插入后取自增 ID
来源：http://dali.cdnleiting.top/Article/details/gtqmqxnenf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtyablntnx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.hywenlv.cn/Article/details/gtqptorhnj.html

[Q13] 忽略重复插入
来源：http://dali.tianlin.xyz/Article/details/gtraaebpil.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nwbrower.top/Article/details/gtuhuhwmmr.html

[Q14] 存在则更新（upsert）
来源：http://dali.sufxvd.cn/Article/details/gtvkbakwne.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gtdrafdrsw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtsyrcldjy.html

[Q15] 查询全部
来源：http://dali.cqqwz.cn/Article/details/gtmzdvwlzq.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtzjdvoxup.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gttbfwrfrh.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtwcjtvpyx.html

[Q17] 条件查询
来源：http://dali.feifeiyinyue.top/Article/details/gthibkjooy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtevclnnpw.html

[Q18] 模糊匹配
来源：http://dali.9152youxi.cn/Article/details/gtapovgjbt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gtdfrzxpms.html

[Q19] 范围查询
来源：http://dali.fzhhl.top/Article/details/gtvgpismlq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gtbkwwofjg.html

[Q20] IN 列表
来源：http://dali.jqgufenzy.top/Article/details/gtfsbwgcph.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.aizwys.cn/Article/details/gtnyaftfxc.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtisnbgxyj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gtsynfblyf.html

[Q22] 排序
来源：http://dali.xuanzx.com/Article/details/gtpriruycz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tanke756.top/Article/details/gtigtrtjlm.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gtuirtckyr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.9152youxi.cn/Article/details/gthqlhbzot.html

[Q24] 去重
来源：http://dali.9152youxi.cn/Article/details/gtoxuirsyn.html

SELECT DISTINCT city FROM users;
来源：http://dali.meibo888.top/Article/details/gtgdtybedj.html

[Q25] 只取前 N 条
来源：http://dali.dianchejie.cn/Article/details/gtilothnaz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtxpgmsifo.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtdtylofiq.html

SELECT COUNT(*) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdibhqben.html

[Q27] 条件计数
来源：http://dali.guannengcc.top/Article/details/gtcpjmkvak.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xinyue.icu/Article/details/gtsxqmrtva.html

[Q28] 求和与平均
来源：http://dali.xylfe.cn/Article/details/gtfufncmys.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gttmgiqfng.html

[Q29] 最大最小值
来源：http://dali.shuidangran.top/Article/details/gtwwcvpqxi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtnxkioqkn.html

[Q30] 分组统计
来源：http://dali.haohaochexian.top/Article/details/gtajdzhblk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gteiyioypv.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtmzngshel.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtntdyujsi.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyuiihnk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gthxsfeyzl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkeslheil.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gtkgzoturv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxinkj.top/Article/details/gtupusnvok.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtiaverjab.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gthxqpxkap.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.svipenyu.cn/Article/details/gtagypgnpj.html

) t WHERE rn = 1;
来源：http://dali.hywenlv.cn/Article/details/gtnkjlobab.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gtenbcevfs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtfmlnpavl.html

[Q36] 左连接
来源：http://dali.yongpay.top/Article/details/gtirlpvuok.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.fengsongda.top/Article/details/gtezdjbrhm.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gtxconwlat.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jlsjyb.cn/Article/details/gtthzpuzhy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tanke756.top/Article/details/gtexuqcubm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jinqigufen.top/Article/details/gthywirxxm.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gtbbdeyzay.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.chenlongwang.top/Article/details/gtlbybdnrv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtgpwovtng.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.aibaodan.cn/Article/details/gthlsnxbfi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yanxiufei.cn/Article/details/gtocjbozcg.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtsytptlhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.meibo888.top/Article/details/gtktepvuoh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.pycfn.com/Article/details/gtejkxzgpi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shzxlz.cn/Article/details/gtgtgtzpxz.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtciodmsxf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.snrcjt.cn/Article/details/gtnalbxuji.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.svipenyu.cn/Article/details/gtlrekqmmy.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtcjpmpffj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtzxqrngvj.html

[Q44] IN 子查询
来源：http://dali.zycfv.cn/Article/details/gtpccbacxr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.pycfn.com/Article/details/gtgwhacggq.html

[Q45] EXISTS 判断存在
来源：http://dali.tanke756.top/Article/details/gtyydfqwdv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtyeowtszu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtiprulgvz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gtqiqeazoa.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlynstxzh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hysaishi.cn/Article/details/gtaiwkafez.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gtrlqcfzkl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgychxug.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtitsiiwno.html

[Q49] 更新单行
来源：http://dali.yuxming.cn/Article/details/gtgbzadkmc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.birdmap.top/Article/details/gthaksdope.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtfksuxgfn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcysvjlmb.html

[Q51] 用子查询更新
来源：http://dali.fengsongda.top/Article/details/gtcggxdqtp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtmavbvmso.html

[Q52] 删除指定行
来源：http://dali.aibaodan.cn/Article/details/gtrxfwkvsc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gtcdscwzfo.html

[Q53] 按条件删除
来源：http://dali.iojbl.cn/Article/details/gttsyoqoxj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxinkj.top/Article/details/gtnechabgy.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtgxtxgfbt.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtpsrevzeb.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtltikwasx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtcsiraahs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gttoydldse.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtnczwmwyn.html

[Q57] 行号
来源：http://dali.cdnleiting.top/Article/details/gtevnxruxa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtpihafgaq.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtkqplpyux.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gttmdbhewy.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtggsujeej.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtgjnvhohp.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtxheujdwy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gtullihyzf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgeghjsf.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhqgxetr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtjsdknvfv.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtgisgckfe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtsshgbtic.html

[Q63] 开启事务
来源：http://dali.wangshuangyany.cn/Article/details/gttghykdkh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aibaodan.cn/Article/details/gtgbfgpyqm.html

[Q64] 提交事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtepaakrtz.html

COMMIT;
来源：http://dali.daxiang520.top/Article/details/gtjtfljweo.html

[Q65] 回滚事务
来源：http://dali.hnqzz.top/Article/details/gtsqtgjhxs.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gttrlhzles.html

[Q66] 行锁查询
来源：http://dali.nanxinkj.top/Article/details/gthpztjvvf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gteuycwmtz.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gtzzgscoqk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnxiangtu.top/Article/details/gtaisoeamr.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfvdrxpa.html

SAVEPOINT sp1;
来源：http://dali.cheryme.top/Article/details/gtutrepemi.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtjzvzfnbt.html

[Q69] 查看执行计划
来源：http://dali.yj20258888.top/Article/details/gtkgaafbqs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cheryme.top/Article/details/gtizlnwzpt.html

[Q70] 更新统计信息
来源：http://dali.cashguo.top/Article/details/gtrceiylib.html

ANALYZE TABLE users;
来源：http://dali.316326.xyz/Article/details/gtcvhuecen.html

[Q71] 查看建表语句
来源：http://dali.fengsongda.top/Article/details/gthcohkepm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.quarkkingdee.top/Article/details/gtxszoltno.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gtzyrlrzth.html

SHOW INDEX FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyfzirjx.html

[Q73] 查看表状态
来源：http://dali.gotoacloud.top/Article/details/gtkroqragn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.316326.xyz/Article/details/gtfwjgztom.html

[Q74] 强制使用索引
来源：http://dali.aibaodan.cn/Article/details/gtfwuoqqqg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtwgltouuk.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gthjfrasxl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtajurwpef.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cqqwz.cn/Article/details/gtyrwgskov.html

[Q76] 按天统计
来源：http://dali.jiagoushi.top/Article/details/gtlzuvlsir.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinghuilouyu.cn/Article/details/gtimtygvvm.html

[Q77] 时间加减
来源：http://dali.tanke756.top/Article/details/gtyqutbzxk.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gtwftmddrs.html


<!-- 参考信息 -->