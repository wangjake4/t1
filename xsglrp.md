代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2pqhmggxs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.redwolf501.top/Article/details/gt2rosgfvwe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2ihcwkklu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shuidangran.top/Article/details/gt2jeuqhnss.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gt2sgdruuyz.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gt2jyxkkjac.html

Py:   with lock: shared += 1
来源：http://dali.dianchejie.cn/Article/details/gt2fikhsfuq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdnmtwyo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gt2rxmzhhxx.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2kfofvgvd.html

Java: synchronized (this) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2vrenzkir.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gt2fqwwibre.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gt2fvkefiyi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gt2yclpvzhl.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gt2zuzqqgzl.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gt2snxmyxga.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.snrcjt.cn/Article/details/gt2sgnlaoyu.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2cymdayjr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2xaszycng.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gt2yayazayx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2oehjtsxt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2ekwvjmas.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrfxvhaq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gt2hhkxznss.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2bormuxiz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gt2ifarqfyf.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2azqtkzvy.html

TS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gt2grisgvny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gt2hnmpscdf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hysaishi.cn/Article/details/gt2kztlrzox.html

Ruby: threads.map(&:join)
来源：http://dali.sysykeji.top/Article/details/gt2gswcnhga.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gt2oevquijx.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gt2tbzpflnl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fengsongda.top/Article/details/gt2cmnltjxb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gt2thjxsbop.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2gwsquyxn.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2fbatfihn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gt2deetvzxt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2aciygmfa.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gt2dekeupdq.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gt2lwgbkkqv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxlkcdwu.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gt2yrcdzoow.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2tcxwyrhh.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2rigkybvm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2zpjybein.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2ztfnalhk.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gt2bviiknqo.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2zinmwfji.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gt2neztifzd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gt2zaajgivx.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gt2hdgdnrmg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gt2igaitocs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gt2brbyidob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gt2ydknpcny.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2qwhcsnvw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gt2pnjdqxma.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.wangshuangyany.cn/Article/details/gt2enpchteq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gt2rsfscgxe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gt2ddrpvacc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gt2vhjduepo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zdqjudy.top/Article/details/gt2bpxzemto.html

[P03] 生成短随机字符串
来源：http://dali.gogol.net.cn/Article/details/gt2hqlajcht.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gt2xewbusld.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gt2dyyshonj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.316326.xyz/Article/details/gt2azzyjmsf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2dhcgkcbg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2kstlzhmk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nanxuanxn.top/Article/details/gt2frdyhhlz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gt2vbcdvjxp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.mhx1999.top/Article/details/gt2wcikwomn.html

[P04] 求长度
来源：http://dali.sweek.top/Article/details/gt2cotzgeay.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gt2pvmbuygn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfzinevu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2yhwyfpvu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2xlxiesqw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2qukgsvbd.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emyizgfq.html

Ruby: x.length;  x.size
来源：http://dali.jinqigufen.top/Article/details/gt2ynksfhdr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmfenyku.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gt2zxxiovfn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tian-w.cn/Article/details/gt2cvfiyxrt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gt2asrxkibi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gt2pdajeacg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gt2vgdoslyg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnqzz.top/Article/details/gt2jxsbpism.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2vlwauxdp.html

Ruby: a == b
来源：http://dali.yj202588.top/Article/details/gt2xpkfufei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2pppzslyd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gt2wupeqcgq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2dvgydgqj.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2ymmfjeus.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxouqwiq.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2wpojvfei.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2azfqfbqz.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gt2taipmwjt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gt2tlcgvbmb.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gt2nbznjosv.html

[P07] 防抖与节流
来源：http://dali.hongshengwenyu.top/Article/details/gt2mnjklnkx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gt2tafgxykx.html

PHP:  // 手写时间戳比较
来源：http://dali.zycfv.cn/Article/details/gt2teqacema.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2siuzarjp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2wlnpkzln.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gt2omngebkt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gt2vrteyqtb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gt2mpjscjkf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.wangdashe.top/Article/details/gt2kdbuiwsl.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gt2gcomwjii.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sysykeji.top/Article/details/gt2bntoiqxb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dlskpwul.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctoryjuk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2amznexbe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gt2irngigwe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gt2yzvjffwa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fpqoihxp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2fzmegqqk.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2qpjzoybv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tian-w.cn/Article/details/gt2efrywxmr.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ppykjueq.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wnwqqzis.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gt2xwqrjvgy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2omgcdjzi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gt2szmfqxqh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gt2qpzlvkxl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yanxiufei.cn/Article/details/gt2sgreevvk.html

);
来源：http://dali.ppjwa.cn/Article/details/gt2cdnlkeyw.html

[Q02] 创建带外键的表
来源：http://dali.aizwys.cn/Article/details/gt2awuypapy.html

CREATE TABLE orders (
来源：http://dali.hnqzz.top/Article/details/gt2xvuewrfi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhvwcjph.html

user_id INT NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gt2shycncrx.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gt2mcdojhig.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gt2nimgfwqt.html

);
来源：http://dali.tian-w.cn/Article/details/gt2rwqkcmdx.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gt2grdasipr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hnxiangtu.top/Article/details/gt2xsyzuizg.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gt2nqygwolo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cheryme.top/Article/details/gt2ksldpqki.html

[Q05] 重命名列
来源：http://dali.gogol.net.cn/Article/details/gt2zdhrowoc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hysaishi.cn/Article/details/gt2jobrjsvb.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcbjhwtp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gt2beasuotd.html

[Q07] 删除表
来源：http://dali.daxiang520.top/Article/details/gt2bzwkwllm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxvjmrro.html

[Q08] 创建普通索引
来源：http://dali.daria6918.cn/Article/details/gt2pwmdmlqa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.havefunace.top/Article/details/gt2iduncrlr.html

[Q09] 创建唯一索引
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqhiweyp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.jianghu66.top/Article/details/gt2vpalrhzc.html

[Q10] 插入单行
来源：http://dali.zhixingplan.top/Article/details/gt2cvdmpomg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2vebxnjht.html

[Q11] 一次插入多行
来源：http://dali.jinqigufen.top/Article/details/gt2ixsnyzvp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2iabgypub.html

[Q12] 插入后取自增 ID
来源：http://dali.wangshuangyany.cn/Article/details/gt2hahnobkx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.andypj.xyz/Article/details/gt2zmnivvqc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gogol.net.cn/Article/details/gt2uzopcpfn.html

[Q13] 忽略重复插入
来源：http://dali.jiagoushi.top/Article/details/gt2hvxfnljy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2upgqjgel.html

[Q14] 存在则更新（upsert）
来源：http://dali.cashguo.top/Article/details/gt2zszrlnos.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2mqzvxiqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.0kj1m.cn/Article/details/gt2xxhlytbo.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2ithwmjiz.html

SELECT * FROM users;
来源：http://dali.pycfn.com/Article/details/gt2clpfbdcv.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjflezxr.html

SELECT id, name FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2jmpzszrx.html

[Q17] 条件查询
来源：http://dali.xylfe.cn/Article/details/gt2obfzfkrr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yonumen.top/Article/details/gt2geqmiuqb.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2zxjkkocw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zuuneeut.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gt2fmsboijf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbscecct.html

[Q20] IN 列表
来源：http://dali.xuetiantiany.cn/Article/details/gt2prdsjudp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2wdmzhrrj.html

[Q21] 空值判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2djoctche.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yueranfly.top/Article/details/gt2hgxhsyjj.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2xeqvypah.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jlsjyb.cn/Article/details/gt2upxmumuw.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gt2kxeyhgtf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gt2wjahqpaz.html

[Q24] 去重
来源：http://dali.ivvv.top/Article/details/gt2bjgyeota.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gt2yrlwkthy.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gt2zpdoznyl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2javpfuoq.html

[Q26] 计数
来源：http://dali.xylfe.cn/Article/details/gt2crbuwbep.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2nrqxbyeu.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2nugmklyl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gt2agmataem.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gt2lkbdqopt.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2vqdylvmq.html

[Q29] 最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2dlqzagqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2mrhusycq.html

[Q30] 分组统计
来源：http://dali.redwolf501.top/Article/details/gt2nvffdnxz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gt2wuzsmcbo.html

[Q31] 分组后过滤
来源：http://dali.cqqwz.cn/Article/details/gt2thfacwbs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gt2rbwyoetq.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2cfbpdbrh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiaxrnkl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2mkislbzt.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gt2roybegvg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gt2hpnylpka.html

[Q34] 每组取第一条
来源：http://dali.cheryme.top/Article/details/gt2lhfemnja.html

SELECT * FROM (
来源：http://dali.jyoumei.cn/Article/details/gt2lztxypgk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gt2qaxfxmvx.html

) t WHERE rn = 1;
来源：http://dali.ydzc1.top/Article/details/gt2fxvpuhzz.html

[Q35] 内连接
来源：http://dali.meibo888.top/Article/details/gt2ktesxjcx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guowangkeji.top/Article/details/gt2hpwokgtm.html

[Q36] 左连接
来源：http://dali.guowangkeji.top/Article/details/gt2pejqicvf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gt2gzaurvbs.html

[Q37] 右连接
来源：http://dali.yongpay.top/Article/details/gt2ayfcyrou.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.haohaochexian.top/Article/details/gt2wpclozdt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gt2muzikvcy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gt2rxpxjefv.html

[Q39] 自连接（查上下级）
来源：http://dali.smart0.xyz/Article/details/gt2kxlqffyx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftrxxaxe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenlongwang.top/Article/details/gt2vsjgzdfh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gt2lswwjyfe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxdyst.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gt2yagsmbhl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tian-w.cn/Article/details/gt2nkbaahqg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gt2awwxdvbi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2qnpvuczm.html

[Q42] 连接条件附加过滤
来源：http://dali.hnqzz.top/Article/details/gt2nvpcatgi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gt2jbdjadpk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gt2xhnrmxom.html

[Q43] 标量子查询
来源：http://dali.shzxlz.cn/Article/details/gt2jsahxyos.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gaohongyu789.top/Article/details/gt2mvqurgoz.html

[Q44] IN 子查询
来源：http://dali.daxiang520.top/Article/details/gt2zxnhglxu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jyoumei.cn/Article/details/gt2rdadhtdq.html

[Q45] EXISTS 判断存在
来源：http://dali.tian-w.cn/Article/details/gt2sueqbjil.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2lgvowwdw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.bjfxy.top/Article/details/gt2jeteapia.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gt2xgkqrtev.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gt2tovnzdgz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gaohongyu789.top/Article/details/gt2fdtddhby.html

[Q48] CTE 公用表表达式
来源：http://dali.daria6918.cn/Article/details/gt2ynrvqmsa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gt2oxeapqxv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hongshengwenyu.top/Article/details/gt2amuuwjrm.html

[Q49] 更新单行
来源：http://dali.fzhhl.top/Article/details/gt2izclwtpl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2pnlhruww.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gt2biaojnou.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gt2ylncpqty.html

[Q51] 用子查询更新
来源：http://dali.zhixingplan.top/Article/details/gt2nbrmnviu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tanke756.top/Article/details/gt2awtyidgh.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gt2bednndzu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pycfn.com/Article/details/gt2ltqgxjte.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gt2lwcjkcqb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.meibo888.top/Article/details/gt2gkzbkbhf.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gt2svdkunaf.html

TRUNCATE TABLE logs;
来源：http://dali.wangdashe.top/Article/details/gt2oigsmyfu.html

[Q55] 排名（并列占位）
来源：http://dali.ehwqpu.com/Article/details/gt2nnuydjpo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2wtewuhhi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gt2eggkjxym.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jianghu66.top/Article/details/gt2zoewgryl.html

[Q57] 行号
来源：http://dali.gzhubu.top/Article/details/gt2kcfvinyj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2ntqlhkmz.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gt2sdavkzwc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2hlmndgnj.html

[Q59] 分组内累计
来源：http://dali.yj20258.top/Article/details/gt2yalstgtx.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2uivwcsqb.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gt2tuuzrfmo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2gwtrjmba.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2wxvbvagl.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gt2oqjuwjix.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2ixvclqkx.html

[Q62] 分组占比
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbqjkevy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2dwyovtdl.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gt2rupfitln.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gt2pfmafern.html

[Q64] 提交事务
来源：http://dali.zhongyouzk.top/Article/details/gt2vbsytewm.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gt2yzsvktxe.html

[Q65] 回滚事务
来源：http://dali.316326.xyz/Article/details/gt2bbdeyjpg.html

ROLLBACK;
来源：http://dali.jinqigufen.top/Article/details/gt2juhlymiw.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gt2osxzyjbe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gt2keebbuik.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gt2qwwfvqfm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2mopzrdlu.html

[Q68] 保存点
来源：http://dali.feifeiyinyue.top/Article/details/gt2yzzghixe.html

SAVEPOINT sp1;
来源：http://dali.hfpthk.cn/Article/details/gt2wkatrwdi.html

ROLLBACK TO sp1;
来源：http://dali.yuanzhike.top/Article/details/gt2krlxohom.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gt2rproqtcg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gt2ahszpwol.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gt2rsqrktvn.html

ANALYZE TABLE users;
来源：http://dali.jqgufenzy.top/Article/details/gt2dfwyextk.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2blbthzwk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuxming.cn/Article/details/gt2ziczhfpr.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gt2sgzjbxuo.html

SHOW INDEX FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2jnpxyfam.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gt2rbyvcqyj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shuidangran.top/Article/details/gt2hedsjtzw.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gt2xrixbvbn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gt2scaeezxj.html

[Q75] 日期格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2mxlmvrdo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gt2clahobil.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.dashuyun.cn/Article/details/gt2xhflmdmb.html

[Q76] 按天统计
来源：http://dali.yj20258.top/Article/details/gt2rftsanim.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xziqi.cn/Article/details/gt2vvwlcgdp.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gt2ypnvnxze.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenzaomai.com/Article/details/gt2hbompnnk.html

[Q78] 当前时间
来源：http://dali.xuanzx.com/Article/details/gt2bvtxreom.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2aahwxrpd.html

[Q79] 字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2ohugohcr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gt2jbeootqs.html


<!-- 参考信息 -->