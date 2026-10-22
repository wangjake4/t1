代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtoojvqbrx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gtgspfmkhv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fzhhl.top/Article/details/gtpiiutmjw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtrnfcayth.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtjsbihpto.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtwdljrdpm.html

Py:   with lock: shared += 1
来源：http://dali.zhoulong.xyz/Article/details/gtgucpqupu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcehqqqkv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hysaishi.cn/Article/details/gtrkhxetuo.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gtxckdhbvg.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtfnofqclb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tianlin.xyz/Article/details/gtdlyxxkpl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gthpdryxrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtijtmlvxn.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtojtduigs.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtcxarxbhw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gtvhsuvuqs.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtekccitqm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmkwhhwd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxinkj.top/Article/details/gtazermuvt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgufenzy.top/Article/details/gtewnxtexw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gtpgqgkhug.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlhbxvben.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtnksqkiso.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtjmnhgjlc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gtwpcyntda.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gthaxhroqp.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtrqzrmnsc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnufpnnds.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtxpmbocyw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtiykvniie.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtteelxpre.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gteaebkqqv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.dianchejie.cn/Article/details/gtphjtapnl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtybofbszu.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtgfatepvs.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gttdqjmlcp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtigkitsir.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gteltismuo.html

Ruby: // fork 块
来源：http://dali.jqgfzy.top/Article/details/gtajgpozxj.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gtxgdamaiz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtksexhgke.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gthnpyysxd.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfmwghlnm.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gtnomfgqry.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtifkccgbi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cucudq.cn/Article/details/gtibqpzgjp.html

JS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtiycuyvlx.html

TS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtgodaptxc.html

Java: UUID.randomUUID().toString()
来源：http://dali.daria6918.cn/Article/details/gtuctdqnpf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtmfnhadnz.html

Ruby: SecureRandom.uuid
来源：http://dali.yongpay.top/Article/details/gtsgnkbjfn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gtpfmdnlhd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtachypden.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtntdinefh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtliipnoyf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtfxwakelp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcoutdhg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxzqufmx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtmlqbyhgu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gtwmaamxsq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtzffgtswd.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gthtgjdqxa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtibzczubc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhoulong.xyz/Article/details/gtipgvhgiv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guannengcc.top/Article/details/gtexjajhqe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gtvmcvzdbk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gtiadukjsh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtfjfksfub.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.andypj.xyz/Article/details/gtabrszpfd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtchrvflnf.html

[P04] 求长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlmjoygh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtxznoucdr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtccdccein.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gtrxiklmjw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtdnwucgrk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtdwzezdqc.html

Go:   len(arr);  len(m)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvxbdhpp.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtnfukezdj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gttvaulhkh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gtisumnjqf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnwimxma.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gtavqwowbn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gtfljgnhlw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.smart0.xyz/Article/details/gtouucyyve.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangtech.top/Article/details/gtckudsxln.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gtnfhluajy.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gtwdtrczny.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtrfozjupn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtehvjoxap.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pengpengdd.cyou/Article/details/gtxksqnzzy.html

PHP:  if (empty($x)) {}
来源：http://dali.xylfe.cn/Article/details/gtkimodrgw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtqsnfyace.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtcuyjmpfu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtuckohwig.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gtbxzetvdf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyuprtqj.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gteajsyiip.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtfaempbry.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zycfv.cn/Article/details/gtwrlydzgn.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtswppxxjl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtdhfstvnj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtfisqolvz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daria6918.cn/Article/details/gttdjdqwdc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhoulong.xyz/Article/details/gtlywhaxob.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gtjmvuqrlc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtsqmmslti.html

[P08] 处理浮点精度问题
来源：http://dali.ydzc1.top/Article/details/gtkpkkoqri.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtnlijrgdu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.kuanghao11.cn/Article/details/gtvybixfuk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ppjwa.cn/Article/details/gtfaexxuiw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtsssjfwcd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hfpthk.cn/Article/details/gtesodvmwy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gtstcwbjne.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnisjwhi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgcchlti.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlhtkwjwa.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuxming.cn/Article/details/gtcatauiqe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkpclocnk.html

[Q01] 创建表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnggzgttz.html

CREATE TABLE users (
来源：http://dali.haohaochexian.top/Article/details/gtxsnetnvf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gtqobsseng.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtaqhhccdm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtjxqiaxfm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gtwtskigle.html

);
来源：http://dali.sxryk.cn/Article/details/gtlithvyrz.html

[Q02] 创建带外键的表
来源：http://dali.yuanzhike.top/Article/details/gtlotrbugf.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtrxftwvue.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gtklreaitt.html

user_id INT NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtnpohpvqa.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtywzeiikd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangshuangyany.cn/Article/details/gtptozjsqi.html

);
来源：http://dali.bjfxy.top/Article/details/gttnkhqpgy.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtwxuohncy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplemlxlx.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtsomwzbms.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtjhcwaljc.html

[Q05] 重命名列
来源：http://dali.xziqi.cn/Article/details/gtkpvrifcm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqoukisc.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtxiibjfyp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gturvzqfhh.html

[Q07] 删除表
来源：http://dali.guannengcc.top/Article/details/gtqkhjnhpv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jianghu66.top/Article/details/gtdlsjyilr.html

[Q08] 创建普通索引
来源：http://dali.ehwqpu.com/Article/details/gtgpdlgzay.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuknamfef.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtldqxlzdt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenzaomai.com/Article/details/gtnxopuhhn.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtyzcxvlym.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtzsvgwish.html

[Q11] 一次插入多行
来源：http://dali.hongshengwenyu.top/Article/details/gtsppwqnnv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtltrhwtzk.html

[Q12] 插入后取自增 ID
来源：http://dali.yangfankeji.com/Article/details/gtevoejguh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sxryk.cn/Article/details/gtnzhqelzt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yueranfly.top/Article/details/gtvmtslsmo.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gtfiagkgtn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.gogol.net.cn/Article/details/gtxicstuux.html

[Q14] 存在则更新（upsert）
来源：http://dali.jyoumei.cn/Article/details/gtwrxmsvsl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gtaiwfbuez.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzykheyw.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtalcpaogw.html

SELECT * FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtqkttrvmc.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gtakxnscom.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtidygrrkw.html

[Q17] 条件查询
来源：http://dali.haohaochexian.top/Article/details/gtmhcojnyc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.redwolf501.top/Article/details/gtxhrnkuow.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gttjfdunpu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.tianlin.xyz/Article/details/gtxjhwsoxj.html

[Q19] 范围查询
来源：http://dali.mhx1999.top/Article/details/gtbryipoxo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258.top/Article/details/gtgqkavhjx.html

[Q20] IN 列表
来源：http://dali.tanke756.top/Article/details/gtjyiywjrx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shzxlz.cn/Article/details/gthjlifkmi.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtsrzudlyz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gtowktpzmx.html

[Q22] 排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchpchytx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nanxuanxn.top/Article/details/gtishogdyt.html

[Q23] 分页
来源：http://dali.cashguo.top/Article/details/gtlfanxtlv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gogol.net.cn/Article/details/gtespshzur.html

[Q24] 去重
来源：http://dali.hysaishi.cn/Article/details/gtwkpdwifw.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtcprcmxff.html

[Q25] 只取前 N 条
来源：http://dali.daria6918.cn/Article/details/gtzkqobhff.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yueranfly.top/Article/details/gtgsmwvjjq.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gtcnajhvyh.html

SELECT COUNT(*) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvhumgybn.html

[Q27] 条件计数
来源：http://dali.jyoumei.cn/Article/details/gtvgsqhalm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtrqfxemts.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtqruolski.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gttzhjjsfq.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gtnhwqlbec.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtztbqhhen.html

[Q30] 分组统计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtigiccb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gttjbnwwgf.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtsckvirob.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtlfpswujx.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtjyrhtesf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtuunwaxlj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gtcbilmjph.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gtuehqjcrk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yueranfly.top/Article/details/gtzskbaijf.html

[Q34] 每组取第一条
来源：http://dali.chenjidiqi.icu/Article/details/gtmaqeqbyn.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gtcbizvktc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuetiantiany.cn/Article/details/gtamybcyky.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gtmgwfypqp.html

[Q35] 内连接
来源：http://dali.ehwqpu.com/Article/details/gtvwvhzyuj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtmadhpevd.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gtanbvoaus.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhengqikj.top/Article/details/gtifixuhyl.html

[Q37] 右连接
来源：http://dali.birdmap.top/Article/details/gtzuoyejbk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtdmjuuaua.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daria6918.cn/Article/details/gtxcpfdetj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gtaonuyuuh.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtwwbvmeqc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gtmoeisaao.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtafytetej.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.9152youxi.cn/Article/details/gtseqmjimm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtbmlwjhym.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtpsarqbbl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gthypfcbcp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gotoacloud.top/Article/details/gtwkhitink.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtqzmvdqof.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gtcjsqjpxx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gtjcztuffv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gtvzwjuppy.html

[Q43] 标量子查询
来源：http://dali.xziqi.cn/Article/details/gtctsrvkhj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gtcgqsxtbj.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gtcyfymjug.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yanxiufei.cn/Article/details/gtenkdpssg.html

[Q45] EXISTS 判断存在
来源：http://dali.nwbrower.top/Article/details/gtkxpgjkch.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.redwolf501.top/Article/details/gtralgmcxh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gtflkhpjkz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gtfaolmqhv.html

[Q47] 与平均值比较
来源：http://dali.redwolf501.top/Article/details/gtcwnequtk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gtpqolzmjl.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtksheweif.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sweek.top/Article/details/gthjidrymh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gtptdwedaz.html

[Q49] 更新单行
来源：http://dali.ivvv.top/Article/details/gtitvkjrhi.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.snrcjt.cn/Article/details/gteaqbfufq.html

[Q50] 批量更新
来源：http://dali.ppjwa.cn/Article/details/gtpbubsdlw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jianghu66.top/Article/details/gtkcvsjblv.html

[Q51] 用子查询更新
来源：http://dali.andypj.xyz/Article/details/gturlzesfn.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhacdkdw.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyzeorol.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtksxvecnr.html

[Q53] 按条件删除
来源：http://dali.andypj.xyz/Article/details/gtpvzybukh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gtsulrxwef.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gttjlbrjbj.html

TRUNCATE TABLE logs;
来源：http://dali.yongpay.top/Article/details/gtmutflaab.html

[Q55] 排名（并列占位）
来源：http://dali.gogol.net.cn/Article/details/gtwyiwjyxj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gtnyxioktu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhoulong.xyz/Article/details/gtlyrcptbd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.cheryme.top/Article/details/gteghpupec.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtxkfxcvpb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtxhkihmlj.html

[Q58] 累计求和
来源：http://dali.wangdashe.top/Article/details/gtbecnebkg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtpohonzmz.html

[Q59] 分组内累计
来源：http://dali.guowangkeji.top/Article/details/gtdstvygre.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gthvxgtkpv.html

[Q60] 取上一行 / 下一行
来源：http://dali.tianlin.xyz/Article/details/gtvdrvncba.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gttbgikbfu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtylugczia.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtweuuihtn.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtbqfmbxzj.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtxuhxejiy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gtrsiqcqkn.html

[Q63] 开启事务
来源：http://dali.chenlongwang.top/Article/details/gtpyoakwpj.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yuxming.cn/Article/details/gtujlubrjz.html

[Q64] 提交事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtclumvdfj.html

COMMIT;
来源：http://dali.yuanzhike.top/Article/details/gtwkuxjwhw.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gttofarzvb.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtdbcawfhz.html

[Q66] 行锁查询
来源：http://dali.wangdashe.top/Article/details/gtlmlyyvvo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtoemgwxyr.html

[Q67] 设置隔离级别
来源：http://dali.sweek.top/Article/details/gtukawwbje.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.snrcjt.cn/Article/details/gtletnkxut.html

[Q68] 保存点
来源：http://dali.yongpay.top/Article/details/gtjnnhhhqf.html

SAVEPOINT sp1;
来源：http://dali.iojbl.cn/Article/details/gtclanqzxx.html

ROLLBACK TO sp1;
来源：http://dali.jqgfzy.top/Article/details/gthiiwjkwe.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gtxcmtdwbt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtjnybbpsq.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtrxpsjave.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gtmmekvczi.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gtljcollbg.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtqamncdmc.html

[Q72] 查看索引
来源：http://dali.hammf.cn/Article/details/gtifnmowmz.html

SHOW INDEX FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtmzvshuns.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangkeji.top/Article/details/gtisquwacg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cdnleiting.top/Article/details/gtrttmckby.html

[Q74] 强制使用索引
来源：http://dali.iojbl.cn/Article/details/gtdkeqeayx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hysaishi.cn/Article/details/gtgisgpjmc.html

[Q75] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtofulhazw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtypojhbkw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gtcysjxerm.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtujqifhhb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenjidiqi.icu/Article/details/gtszkkjhyn.html

[Q77] 时间加减
来源：http://dali.sufxvd.cn/Article/details/gtpzrpfeeh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtckhkgvcw.html

[Q78] 当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtxsjpmnwr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gttcfelqfj.html

[Q79] 字符串拼接
来源：http://dali.shangyingyoupin.top/Article/details/gtrlawszpr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.wangshuangyany.cn/Article/details/gtwxreuvsp.html


<!-- 参考信息 -->