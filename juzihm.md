代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtbcyrpush.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtydrrbavz.html

Ruby: Thread.new { f }
来源：http://dali.yuxming.cn/Article/details/gtdasnmexd.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdcnrvek.html

[O02] 使用线程池
来源：http://dali.tian-w.cn/Article/details/gtidpcnkvn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtlsonusnb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.wangshuangyany.cn/Article/details/gtcbdsqeil.html

JS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gthdbwalbl.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gtvplycyiz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtzhqvsssq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtjolkmtru.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gtryfddzwd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jiagoushi.top/Article/details/gtmcvtnlaq.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtrobxrhsf.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtpffqphyj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtmiymypuy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gtdvgksmjm.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gtqpbetizu.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtdfnpkngh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtufanukwt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gtpsmbtmyx.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gtfdzvyyqc.html

[O04] 定义异步函数并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvrswfvc.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtqakgpzsm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpvlwxbf.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtadnfhuri.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtxsomfkfn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiwgzyur.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtykuvcpxf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgufenzy.top/Article/details/gtsujazrtd.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtmsqplstt.html

[O05] 并发执行并等待全部完成
来源：http://dali.shzxlz.cn/Article/details/gtajqommiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gtkynbprdx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvgdzdne.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtnsgmsiaa.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtqcgeodfe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtivewpmdw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.chenzaomai.com/Article/details/gtqzkoooqh.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gttoqzwrag.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sxryk.cn/Article/details/gtvzwfnnxq.html

[O06] 使用进程池
来源：http://dali.cheryme.top/Article/details/gtgtyczbjy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.9152youxi.cn/Article/details/gtpmhrkwjy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gtrdpalxmu.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtuwtukffu.html

TS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gtuihfcebi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtgcpjnljg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gtylejwzni.html

Ruby: // fork 块
来源：http://dali.hongshengwenyu.top/Article/details/gtvxnievlh.html

C#:   Parallel.For
来源：http://dali.cdnleiting.top/Article/details/gtxjtdjrgj.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gttimnwzmp.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gtwclhuefq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtnmfkyhyy.html

[P01] 生成 UUID
来源：http://dali.havefunace.top/Article/details/gtvfsnfqli.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gtivgattgx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gtcxflznmz.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuwcdicu.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtjiazjgnf.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtorhcerwb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gtoouygugm.html

Ruby: SecureRandom.uuid
来源：http://dali.tian-w.cn/Article/details/gtvwxjaetl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkacgnkez.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cucudq.cn/Article/details/gtbrhdbudm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtizhjqjte.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtfrjxnkcw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtdwnfusds.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtabrryynt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtrvoroslc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gtdtygubvx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtivdhozaw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gzhubu.top/Article/details/gtyjuifvwh.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtyjpzqutq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gttxmllufh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxuanxn.top/Article/details/gtskbjfmex.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtwblikuop.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhengqikj.top/Article/details/gthbigxwgs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gtdvpjbwpk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gttvkvsaku.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gtlfejynda.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtlfgkuvwn.html

[P04] 求长度
来源：http://dali.yvedp.cn/Article/details/gtzehmyxyp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtsymdgzrs.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtahlyiknf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gtpvkfedul.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtwnchryux.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtatxjhfnm.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtomviupyc.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtdltsblxs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gteexfngud.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yonumen.top/Article/details/gtglquepil.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtihvvglhf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtulnpmkus.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gtxyryginy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtwikqussh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtqkriyjrs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gthonrufec.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtujmyuios.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtxydfrznu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtxuabaego.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtkzkaoiwv.html

PHP:  if (empty($x)) {}
来源：http://dali.hnqzz.top/Article/details/gtihmuyjqs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.daxiang520.top/Article/details/gtdguroyjf.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtwqwahlqa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gtvjbzdjkh.html

Go:   if x == nil {}
来源：http://dali.gotoacloud.top/Article/details/gtnkdsjxjx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtrhjhpsib.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gttcnmungb.html

[P07] 防抖与节流
来源：http://dali.shuidangran.top/Article/details/gtjslnljlr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.9152youxi.cn/Article/details/gtdlabhvkn.html

PHP:  // 手写时间戳比较
来源：http://dali.haohaochexian.top/Article/details/gtrtwwncmv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtxuofjean.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtkynfmnhw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gtmnufaxin.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwvpghqf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeuhjdzq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtgucqlbds.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtgmsoeqbq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtzozqiqse.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtkcnngsca.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenlongwang.top/Article/details/gtgodkhpod.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtwlbozzkf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jyoumei.cn/Article/details/gtiitxlmtt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtpfzyrfpj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gtfndojlbn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtqwtfdhzc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthuflfijv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ivvv.top/Article/details/gtoafxhken.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyigfuxdt.html

[Q01] 创建表
来源：http://dali.nanxinkj.top/Article/details/gtyddvtuvn.html

CREATE TABLE users (
来源：http://dali.chenzaomai.com/Article/details/gtxyjvkhip.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtescdyadx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtncuwpfoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gteenpmaes.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtjidtdwan.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtmtuphicy.html

[Q02] 创建带外键的表
来源：http://dali.smart0.xyz/Article/details/gtddttljve.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtwxmfrcov.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtkimjwcjc.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtzivpqqxz.html

amount DECIMAL(10, 2),
来源：http://dali.shzxlz.cn/Article/details/gtfroeklyk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtaodnrdqm.html

);
来源：http://dali.sufxvd.cn/Article/details/gtdsacinwo.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtwdfjcesz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gtgpqeftrh.html

[Q04] 修改列类型
来源：http://dali.yj20258.top/Article/details/gtwarkugny.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yj202588.top/Article/details/gtgjqfsnxm.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gttzbmqwwm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hywenlv.cn/Article/details/gtjtefngnj.html

[Q06] 删除列
来源：http://dali.birdmap.top/Article/details/gtxwlglagj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj20258888.top/Article/details/gtkwzaimdh.html

[Q07] 删除表
来源：http://dali.gzhubu.top/Article/details/gtxezcsgdv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aibaodan.cn/Article/details/gtedwvfznx.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxrtckmq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtbcxkuwdg.html

[Q09] 创建唯一索引
来源：http://dali.nanxuanxn.top/Article/details/gteurxeeez.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtyrgsyavn.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gthgfqaqez.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuxming.cn/Article/details/gtjbdkznsd.html

[Q11] 一次插入多行
来源：http://dali.sysykeji.top/Article/details/gtjzlwcior.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.nwbrower.top/Article/details/gttpqqyrlg.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtplmoknsh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jqgufenzy.top/Article/details/gtzxbgftvb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.bjfxy.top/Article/details/gtksvbzssf.html

[Q13] 忽略重复插入
来源：http://dali.gzhubu.top/Article/details/gtzzilanvq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.iojbl.cn/Article/details/gtyzbrpaob.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhengqikj.top/Article/details/gtmfaqufpu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shzxlz.cn/Article/details/gtdzmtgwsu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomqzrdei.html

[Q15] 查询全部
来源：http://dali.quarkkingdee.top/Article/details/gtwockwudc.html

SELECT * FROM users;
来源：http://dali.bjfxy.top/Article/details/gtsxsxmped.html

[Q16] 查询指定列
来源：http://dali.yvedp.cn/Article/details/gtwgwroxft.html

SELECT id, name FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyqiotov.html

[Q17] 条件查询
来源：http://dali.gzhubu.top/Article/details/gtpmjsrohy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gttiophogl.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtaxzcqgrt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sufxvd.cn/Article/details/gtgmzfrmae.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtwlojqndh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gtoxpzgogs.html

[Q20] IN 列表
来源：http://dali.sufxvd.cn/Article/details/gtoydjblzm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtstwafcsy.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gtryvjvscg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhongyouzk.top/Article/details/gtylzcpuog.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtqxfqyepl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gtwmlddbbl.html

[Q23] 分页
来源：http://dali.xuetiantiany.cn/Article/details/gtmzzpzkvv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yj20258888.top/Article/details/gtvpduihxu.html

[Q24] 去重
来源：http://dali.hnqzz.top/Article/details/gthqcmjyvr.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtvqpositl.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gtqcjkmezi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gotoacloud.top/Article/details/gtdykmyaat.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gtynqeecxz.html

SELECT COUNT(*) FROM users;
来源：http://dali.daria6918.cn/Article/details/gtsbtkfhkn.html

[Q27] 条件计数
来源：http://dali.vqdsnc.cn/Article/details/gtnokcxbyc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shuidangran.top/Article/details/gtanotkoso.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzwrwguq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtnussgvif.html

[Q29] 最大最小值
来源：http://dali.daxiang520.top/Article/details/gtshsdkurm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtloymllvw.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtrxsnprzg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtqiumvfyy.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gtgwjuapon.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gtsnkneaan.html

[Q32] 分组拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtykxghyxr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtdmnswndm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gthmtrglvb.html

[Q33] 多列分组
来源：http://dali.gaohongyu789.top/Article/details/gtewctjaru.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hywenlv.cn/Article/details/gtcwvexivl.html

[Q34] 每组取第一条
来源：http://dali.hfpthk.cn/Article/details/gtzohnpsns.html

SELECT * FROM (
来源：http://dali.zycfv.cn/Article/details/gtezlpttxy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hywenlv.cn/Article/details/gtggeedzlg.html

) t WHERE rn = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtofdlyyea.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtkonqmfrp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnqzz.top/Article/details/gtnaprwese.html

[Q36] 左连接
来源：http://dali.pengpengdd.cyou/Article/details/gteotzuqaj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtnofltbyz.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gtwieygijw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtfyjniete.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.andypj.xyz/Article/details/gtwqarvzus.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtcllcfpwo.html

[Q39] 自连接（查上下级）
来源：http://dali.gzhubu.top/Article/details/gtspalvvwt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gtpgpqosce.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daxiang520.top/Article/details/gtszqxyxqz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngffcxgi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gtnyhtdupj.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtdeecnvyc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.daxiang520.top/Article/details/gtzjalemri.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258.top/Article/details/gtpmcoklgh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jyoumei.cn/Article/details/gtjmfjtwbh.html

[Q42] 连接条件附加过滤
来源：http://dali.nwbrower.top/Article/details/gtnpqcpiin.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sweek.top/Article/details/gtpfiywkvn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yongpay.top/Article/details/gtsryecrmm.html

[Q43] 标量子查询
来源：http://dali.chenzaomai.com/Article/details/gtsbadupgl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuetiantiany.cn/Article/details/gtuqutudoz.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gtlcqjfder.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gtfmxunjhr.html

[Q45] EXISTS 判断存在
来源：http://dali.sweek.top/Article/details/gtgffkrafg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtxyrtfybf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gaohongyu789.top/Article/details/gtmzupjexd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zycfv.cn/Article/details/gthwqjxsog.html

[Q47] 与平均值比较
来源：http://dali.shuidangran.top/Article/details/gtqsnmdlnz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gttxruxobc.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtrvxzfkjp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtalcnyiic.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cdnleiting.top/Article/details/gtwufwoody.html

[Q49] 更新单行
来源：http://dali.xylfe.cn/Article/details/gtkatvrsjk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xinyue.icu/Article/details/gtuyuzbjbg.html

[Q50] 批量更新
来源：http://dali.tanke756.top/Article/details/gttvgslqmv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.chenlongwang.top/Article/details/gtoyagxjzj.html

[Q51] 用子查询更新
来源：http://dali.yj20258888.top/Article/details/gtitghmjmt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtfmfpllyi.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gtsxjkntmk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.c1oappe.top/Article/details/gtfoncgphh.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtgchhqhdx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtcvciseff.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtiomxuvzl.html

TRUNCATE TABLE logs;
来源：http://dali.smart0.xyz/Article/details/gtjzmwxbyt.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtusyzufuh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtocvjihqv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cdnleiting.top/Article/details/gtwdhqpoeb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtquqfmsxc.html

[Q57] 行号
来源：http://dali.jlsjyb.cn/Article/details/gtsvqgexhb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyoggapf.html

[Q58] 累计求和
来源：http://dali.sysykeji.top/Article/details/gtrmevvewq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtsclycsnu.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfzwihgp.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtasuhfjng.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtufyqqfxt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhixingplan.top/Article/details/gtkbuqpbef.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtbheqobli.html

[Q61] 移动平均
来源：http://dali.daria6918.cn/Article/details/gtukxcgelx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtwqksicjk.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtgmphidxj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtzyngrceo.html

[Q63] 开启事务
来源：http://dali.guowangkeji.top/Article/details/gtswlmlgwm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jianghu66.top/Article/details/gtksemnwiw.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtdzwylmvy.html

COMMIT;
来源：http://dali.sweek.top/Article/details/gtvasudiif.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtcpkewbbn.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtrheeqesl.html

[Q66] 行锁查询
来源：http://dali.cqqwz.cn/Article/details/gtytpcfbqd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gtbzlbesgy.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtxgysnuhe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigufen.top/Article/details/gtwpybllsn.html

[Q68] 保存点
来源：http://dali.fzhhl.top/Article/details/gtvpofdovf.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gtmntveuhm.html

ROLLBACK TO sp1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjzrwniz.html

[Q69] 查看执行计划
来源：http://dali.sufxvd.cn/Article/details/gtgidnbmai.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.sxryk.cn/Article/details/gtdyuyauos.html

[Q70] 更新统计信息
来源：http://dali.nanxinkj.top/Article/details/gtnhhzugzy.html

ANALYZE TABLE users;
来源：http://dali.yongpay.top/Article/details/gtcdfzysig.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtwzrjmnxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gogol.net.cn/Article/details/gtemmazeuw.html

[Q72] 查看索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjujmckys.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtwgnnepvw.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gtqxrveqon.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtdcffpzil.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gtaqmymtkr.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenjidiqi.icu/Article/details/gtutasfisf.html

[Q75] 日期格式化
来源：http://dali.mhx1999.top/Article/details/gtzjfeedtf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aibaodan.cn/Article/details/gttsrsgmsx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtktckkoxd.html


<!-- 参考信息 -->