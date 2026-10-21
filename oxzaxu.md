代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.dianchejie.cn/Article/details/gtpkutrilr.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtgelvhkhr.html

Ruby: Thread.new { f }
来源：http://dali.mhx1999.top/Article/details/gtxveyquhj.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtdnwwtzic.html

[O02] 使用线程池
来源：http://dali.andypj.xyz/Article/details/gterelhqkn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gtylzwtlpz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ppjwa.cn/Article/details/gtgqvdldhg.html

JS:   // worker_threads 线程池
来源：http://dali.aizwys.cn/Article/details/gtbtwssarr.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtkwtbbjeg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yongpay.top/Article/details/gtsxbwchni.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtebfhpzsf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdieodlzv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmeejllh.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddlfroii.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gtdxeamdle.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gthxtqeotj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtkuigcoqu.html

TS:   // 同 JS
来源：http://dali.zhixingplan.top/Article/details/gtldycdrdy.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtjtepiqdj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtknpelrjf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtrxqycbyq.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtciigqokq.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtbuopvhjt.html

Py:   async def f():⏎    await g()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskpshbtl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gaohongyu789.top/Article/details/gtaskjompj.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtzcnwolnz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gtbsrfbizf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gttlufrnpj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtmyhpotay.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtvsnufhmy.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtguusbgai.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtsqpuutmv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtsmpnadtc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.wangshuangyany.cn/Article/details/gtggrqyauq.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtaqiekrju.html

TS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gtagyyhfvj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtcxmakrwe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtaqlwjhgp.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtzerujikj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gtisgkcydt.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gteykgcwup.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtunzbgddt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gtvlntxsvr.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtkxlvggqe.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gteejvnqth.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcewnhbf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gttgowvwpj.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gtuvwyzxkg.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtahtcxbqc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtqbvqddgt.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtphfprvpc.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtdezxsmeg.html

[P01] 生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtnevdhxym.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtgxeaezgl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtjqggopnr.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtdgfiqdpq.html

TS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtsinxknqp.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gtrxgawioc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtbzcqwkml.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gtblaaiocg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtnvpschdv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtmxhanwaz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtettrfiju.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gteocnbdnq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtgwvnwykf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtjifsbboe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cheryme.top/Article/details/gtzddicvlj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtnfwoveiv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtskdcsllg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gtbqjqmyvd.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtazqvkzyc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnqzz.top/Article/details/gtksnahzhy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gtekgbxemk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtohxzhqdo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtlzvixuor.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gtecsnwtgo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtsumszikd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtaecwpbjo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gtilkrvbis.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gtydqaudbx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ivvv.top/Article/details/gtuqibdldz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtfoqxvrlq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gtexhyachy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gttdrscqyx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtxbahmrnn.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtjcyfrocu.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtvjnrzffk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtbtrdzfpv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gtpsiagjpn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gtpqmxposf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtscrwxwum.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtvcpopibu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gterajgthr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtckgzwnvo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtrivwglab.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gthwgcomzn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtsghqaoxo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gtjlhfxlvh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cheryme.top/Article/details/gtnadezocm.html

PHP:  if (empty($x)) {}
来源：http://dali.smart0.xyz/Article/details/gtjtmpqxsj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fzhhl.top/Article/details/gtlvpsitlt.html

TS:   if (x == null) {}
来源：http://dali.ydzc1.top/Article/details/gtdhahpyej.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtevanqmsf.html

Go:   if x == nil {}
来源：http://dali.sufxvd.cn/Article/details/gtirztfcfz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.bjfxy.top/Article/details/gtentfkhla.html

C#:   if (x is null) {}
来源：http://dali.redwolf501.top/Article/details/gtbszbnxgk.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gtfavsapvd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.smart0.xyz/Article/details/gtafisboma.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtcpztexew.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtgqtiqrzi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtzjhmquca.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtavcjebwa.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtcgrbcedf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.quarkkingdee.top/Article/details/gteesoawdx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cashguo.top/Article/details/gtyykdysly.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtanuzwzpk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.0kj1m.cn/Article/details/gteruwcarw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gtzzebmvkm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtwpnfghpj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtzfqyigra.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj20258888.top/Article/details/gtaktefdmv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.gzhubu.top/Article/details/gttzplmqng.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtyvyrzhyv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hfpthk.cn/Article/details/gtccujijpi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzeoxonly.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gttsmqzwah.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gttpzhjtft.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gteljuhvks.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtnyiwzram.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtyxiapnit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtfbudwafq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gthtvvzlwx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.meibo888.top/Article/details/gtbtrmtqnc.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuunkvof.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtccrpwzxu.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtzqixsfgh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gtrajwleek.html

user_id INT NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gthnnacpmw.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtncumdofw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.chenlongwang.top/Article/details/gtefyqnftd.html

);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgjrxjdw.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gtlwshqiyv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtqnuyuhii.html

[Q04] 修改列类型
来源：http://dali.zhixingplan.top/Article/details/gthstudaer.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtqyovvcai.html

[Q05] 重命名列
来源：http://dali.cheryme.top/Article/details/gteuldruta.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pycfn.com/Article/details/gtkhdubtce.html

[Q06] 删除列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwaegffn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtsvskwuii.html

[Q07] 删除表
来源：http://dali.daria6918.cn/Article/details/gtixnnfttv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258.top/Article/details/gtnxcjkbnl.html

[Q08] 创建普通索引
来源：http://dali.iojbl.cn/Article/details/gtqzozcbxh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtiyjqrkcq.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gttbqocprk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtixpodyfr.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gtqrahigqk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturkktuut.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gtwfbpigal.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gttusffyoq.html

[Q12] 插入后取自增 ID
来源：http://dali.haohaochexian.top/Article/details/gtnamjirol.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gaohongyu789.top/Article/details/gtqxrywahi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gtcbzljwdm.html

[Q13] 忽略重复插入
来源：http://dali.yj20258.top/Article/details/gtswbrqpll.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxinkj.top/Article/details/gtcigvvrqj.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtcjtswaza.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gtnwxxqizd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.vqdsnc.cn/Article/details/gtyhzsyocw.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtibiuisvx.html

SELECT * FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtqycrnpkj.html

[Q16] 查询指定列
来源：http://dali.cdnleiting.top/Article/details/gtmgxfsfoq.html

SELECT id, name FROM users;
来源：http://dali.xziqi.cn/Article/details/gtedqgyasa.html

[Q17] 条件查询
来源：http://dali.9152youxi.cn/Article/details/gttdlghqbp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtrgofcvcj.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtbvofgwak.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xylfe.cn/Article/details/gtretolsrc.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtxplcsryp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.andypj.xyz/Article/details/gtccaxjkif.html

[Q20] IN 列表
来源：http://dali.cucudq.cn/Article/details/gtftofvhzx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxigiwxor.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtoqscgqat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hammf.cn/Article/details/gtvqdjfonz.html

[Q22] 排序
来源：http://dali.zhixingplan.top/Article/details/gtldblrvbj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cheryme.top/Article/details/gtnzaveqsf.html

[Q23] 分页
来源：http://dali.shanyushiyangtech.top/Article/details/gtztswmuqb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gtxhmzsxlr.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtljmzsyvs.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtbghvrnog.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtynsnlxgo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtenxzusci.html

[Q26] 计数
来源：http://dali.xuanzx.com/Article/details/gtwiwjymdf.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtwphfujkq.html

[Q27] 条件计数
来源：http://dali.yongpay.top/Article/details/gthowunxpr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtupshsxdn.html

[Q28] 求和与平均
来源：http://dali.fengsongda.top/Article/details/gthysgvxhf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtrxswtjkv.html

[Q29] 最大最小值
来源：http://dali.yueranfly.top/Article/details/gtwlzlovha.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtbmaefeqt.html

[Q30] 分组统计
来源：http://dali.jqgfzy.top/Article/details/gtogjcmive.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.aibaodan.cn/Article/details/gtoxrccyba.html

[Q31] 分组后过滤
来源：http://dali.mhx1999.top/Article/details/gtqezarypd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtorilxpry.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtdxlwixal.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtzftwfiha.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtacrozjpk.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gtbartkzwx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xylfe.cn/Article/details/gthlcuejjr.html

[Q34] 每组取第一条
来源：http://dali.wangshuangyany.cn/Article/details/gtlrtuoufr.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtdqthhjpy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.meibo888.top/Article/details/gtlkedudqp.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtlmgbzqgs.html

[Q35] 内连接
来源：http://dali.shangyingyoupin.top/Article/details/gtvmgnvztx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gttsunzaum.html

[Q36] 左连接
来源：http://dali.iojbl.cn/Article/details/gteqsktxhz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangdashe.top/Article/details/gthseealqy.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gtltsjmuzt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gtceibsuvv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shuidangran.top/Article/details/gtymjhirpn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gtdatnuzkq.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gthmvfnymn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtkoeakzju.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtmkvztolq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhengqikj.top/Article/details/gtlvcstsin.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sysykeji.top/Article/details/gtwmhvmbtm.html

[Q41] 多表连接
来源：http://dali.ehwqpu.com/Article/details/gthgaaceem.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtemmraijs.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtjuriqnst.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtvrjaxihj.html

[Q42] 连接条件附加过滤
来源：http://dali.nanxinkj.top/Article/details/gtouopoorn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtwhmbnoqh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtdpgjlnll.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtfkwbgcrb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhoulong.xyz/Article/details/gtirpfldwt.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtxydnadjx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nwbrower.top/Article/details/gtdwzqzwab.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtooeqoryt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtfbimcqoa.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtkuuymyot.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gtrzkjbjci.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjmajyeo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fzhhl.top/Article/details/gtibfsiclc.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxinkj.top/Article/details/gtedkrdtgc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.kuanghao11.cn/Article/details/gtsuhlyurf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoltayrkr.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtgrmhrqaw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sufxvd.cn/Article/details/gtglpyeuxz.html

[Q50] 批量更新
来源：http://dali.yvedp.cn/Article/details/gtqiosarhs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gtzcuzousx.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtqmlglwyr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gticjbwogu.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtwnuvwgjy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gtndycutzs.html

[Q53] 按条件删除
来源：http://dali.dashuyun.cn/Article/details/gtazndmdvt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtxjwvogzx.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gtjqmjmoza.html

TRUNCATE TABLE logs;
来源：http://dali.ydzc1.top/Article/details/gtjzzhvqek.html

[Q55] 排名（并列占位）
来源：http://dali.xuanzx.com/Article/details/gtjilyyafu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtlngvdkyt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gthnugcgsq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yonumen.top/Article/details/gtpplqtvne.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gtonbkxpms.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gtkfldozky.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtdqybldzo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gtpbxqnrgg.html

[Q59] 分组内累计
来源：http://dali.pycfn.com/Article/details/gtlllmpzby.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gteqxxpsvh.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenzaomai.com/Article/details/gtaqythdyi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gtcmbfqgcu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gtjreebgjj.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtmfefyoig.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtbayuxoyq.html

[Q62] 分组占比
来源：http://dali.yuxming.cn/Article/details/gttqcqjibm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtdattasgn.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtkbcxbmju.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtwstadkbb.html

[Q64] 提交事务
来源：http://dali.zhiwuduotai.top/Article/details/gtbdunhflj.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gttlrecicx.html

[Q65] 回滚事务
来源：http://dali.xinyue.icu/Article/details/gtwslmegyd.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gteqbffuxi.html

[Q66] 行锁查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrmbyxhn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtckzueywi.html

[Q67] 设置隔离级别
来源：http://dali.hnxiangtu.top/Article/details/gtobofkxyk.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhongyouzk.top/Article/details/gtbzuvolqv.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gtnkaagkap.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gtzxmahuzo.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtloslhswo.html

[Q69] 查看执行计划
来源：http://dali.pengpengdd.cyou/Article/details/gtgmwomayl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtgfaysbop.html

[Q70] 更新统计信息
来源：http://dali.guowangkeji.top/Article/details/gtrlifbztg.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtvszblvyf.html

[Q71] 查看建表语句
来源：http://dali.sufxvd.cn/Article/details/gtnkucluqp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.pycfn.com/Article/details/gttzqqdhbp.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmucukcn.html

SHOW INDEX FROM users;
来源：http://dali.sxryk.cn/Article/details/gthxnsnkxs.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtncgakbdt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.kuanghao11.cn/Article/details/gtfkjgsiti.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtpyhhowre.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtczqfmicu.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtrznklsjs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgjulqad.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hnxiangtu.top/Article/details/gtqblwglsq.html


<!-- 参考信息 -->