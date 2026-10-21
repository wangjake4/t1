代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtfdwsnzqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gttpjenjfg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtmhmjpgcj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gtakbublbn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtfwqzdlqk.html

[O03] 加锁保护共享数据
来源：http://dali.jyoumei.cn/Article/details/gtwhmtzycf.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gtuqnovhzx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtxrknmkmf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yvedp.cn/Article/details/gtwbfjiztt.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtbugukzdq.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtzcfkejab.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtosmawuom.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gtjwqqrbxu.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gthukcygwk.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gtsbnswszi.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtzsrbeglj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gtftkyfskf.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtbgtxizvr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtmpcolrej.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtwikuuabp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gtxwjwzuoq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tian-w.cn/Article/details/gtuhcfxmut.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gttbcvjjaa.html

[O05] 并发执行并等待全部完成
来源：http://dali.sysykeji.top/Article/details/gtbohzsjym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtbyosatva.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gtrdqdwyks.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlyocych.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtgwzsvupv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtdyvupfqh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.redwolf501.top/Article/details/gtfgoenzxa.html

Ruby: threads.map(&:join)
来源：http://dali.sweek.top/Article/details/gtbvuvnlxe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hnqzz.top/Article/details/gtftyycuno.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtitclrvzi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gttrimttjo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gtspmegase.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtsssvkonn.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtbcohcnmd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gttcxtmksq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtvgjdduwk.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gtjbmdpzqx.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtzfbsfjfs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtagfguono.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtehkkdmwg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnlbfpjdy.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtzrzqhcuh.html

Py:   str(uuid.uuid4())
来源：http://dali.zdqjudy.top/Article/details/gttdwcmadc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtcroqdhsy.html

JS:   crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtptoghznk.html

TS:   crypto.randomUUID()
来源：http://dali.dashuyun.cn/Article/details/gtrftrucdc.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gtkzloeaay.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtznbxdsdz.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gtcbfeinme.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenjidiqi.icu/Article/details/gtnmmxkbcu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gtejvsgdhr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yangfankeji.com/Article/details/gtvdxgbght.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gttibbzrfd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtqimewhfe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gtdtyzbkas.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtdbgfegnn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gthphkcayt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtuphresaf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gttxvnpwhl.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtqngkvffg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gtowfbbppa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.guannengcc.top/Article/details/gtykcopyus.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtyssvwnuu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtahubtqzd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.birdmap.top/Article/details/gtccywdzgn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.smart0.xyz/Article/details/gtihkdvbzd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtejmzeqdm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gthgobcwqe.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gtmwnocefp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gtrltyxdho.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtvbvqdowt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gthxxuaqbn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtnybescht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtvzymuils.html

Go:   len(arr);  len(m)
来源：http://dali.yanxiufei.cn/Article/details/gtihpcwyic.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtioxhorol.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtiofvidhh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilllvsdn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gtbthyfqkj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtmoexbakq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gtpspypqfp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gtcwwaaeez.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gtlwvysdhp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtihoogznq.html

Ruby: a == b
来源：http://dali.nanxuanxn.top/Article/details/gtsmqdrdug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gtgtecftrq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtepaydcpb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtrdjavxst.html

PHP:  if (empty($x)) {}
来源：http://dali.dianchejie.cn/Article/details/gtezhgaeix.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gtccyikkcv.html

TS:   if (x == null) {}
来源：http://dali.hywenlv.cn/Article/details/gtnmuiphgn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjrfoqxyw.html

Go:   if x == nil {}
来源：http://dali.yonumen.top/Article/details/gtevztfqqt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gthhhhgoef.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtzrksbxwp.html

[P07] 防抖与节流
来源：http://dali.yj20258888.top/Article/details/gtxizexnyt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gogol.net.cn/Article/details/gtxzvpdbpz.html

PHP:  // 手写时间戳比较
来源：http://dali.cucudq.cn/Article/details/gtppwaoxib.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtbrpwlcwg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtrduvngmm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gtngnfvwvl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.redwolf501.top/Article/details/gtzssnuwif.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtagkdmtpx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gtrtofxrum.html

[P08] 处理浮点精度问题
来源：http://dali.aibaodan.cn/Article/details/gtqzpvqbbm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.vqdsnc.cn/Article/details/gthjzzwuik.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhixingplan.top/Article/details/gtzocltrvv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gtnwohfkew.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtaeghkoet.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gtcpsdyojh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtoxzfidic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gtdzbxzegm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtxttgajle.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrkwuaszo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigfzy.top/Article/details/gtymemaokf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gthcslcxac.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtxcfcbyjo.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gttuxwdalh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtpaclbvhm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvnhcsrx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gtavprbfiu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gtlildrrym.html

);
来源：http://dali.shuidangran.top/Article/details/gtlezqaxei.html

[Q02] 创建带外键的表
来源：http://dali.yuxming.cn/Article/details/gteyvxixrj.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gtwdywsfmm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsmdufwb.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqxnunnm.html

amount DECIMAL(10, 2),
来源：http://dali.yangfankeji.com/Article/details/gtwmfhqpwk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtxvzbzznt.html

);
来源：http://dali.ehwqpu.com/Article/details/gtsccfkcwn.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtbabpwtvb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.dashuyun.cn/Article/details/gtqzyytopp.html

[Q04] 修改列类型
来源：http://dali.sxryk.cn/Article/details/gtqgupmodt.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sxryk.cn/Article/details/gtevefvnts.html

[Q05] 重命名列
来源：http://dali.zhoulong.xyz/Article/details/gtswhytawt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiptvckp.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gtbtufgohc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.smart0.xyz/Article/details/gtpthybbkx.html

[Q07] 删除表
来源：http://dali.jinqigufen.top/Article/details/gtzldalnls.html

DROP TABLE IF EXISTS orders;
来源：http://dali.xziqi.cn/Article/details/gtnzlzvlji.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gtpffrljmb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gtipepbmgz.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gttgojotwk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hongshengwenyu.top/Article/details/gtfhhhstql.html

[Q10] 插入单行
来源：http://dali.jinqigfzy.top/Article/details/gtipliufyd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzitrglj.html

[Q11] 一次插入多行
来源：http://dali.fzhhl.top/Article/details/gtderwdddm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.smart0.xyz/Article/details/gtpaeanfel.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksrtvdpu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gthaqghnxk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmzfdlyv.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtjjfckawm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtrrsmamkt.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gtjmtkbwrv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xziqi.cn/Article/details/gtnxtpccff.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylihdtza.html

[Q15] 查询全部
来源：http://dali.tianlin.xyz/Article/details/gteyqjbrcm.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtkqovxwyi.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtygpxbwjt.html

SELECT id, name FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtlkomqdhy.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gttpgdrbze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xuanzx.com/Article/details/gtjzarkigs.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtfkmcnozb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xuanzx.com/Article/details/gtnfflbaxr.html

[Q19] 范围查询
来源：http://dali.cheryme.top/Article/details/gtyroiwrzm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.0kj1m.cn/Article/details/gtxyuzamqq.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtvolajupf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtcfqyprhj.html

[Q21] 空值判断
来源：http://dali.tianlin.xyz/Article/details/gtpscnaizd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.redwolf501.top/Article/details/gttanzwzuy.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtoutjxnky.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gtvpxqzgvz.html

[Q23] 分页
来源：http://dali.gotoacloud.top/Article/details/gtdshnndzl.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxuanxn.top/Article/details/gtwzuuolon.html

[Q24] 去重
来源：http://dali.0kj1m.cn/Article/details/gtvwwiqdka.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtcksifkui.html

[Q25] 只取前 N 条
来源：http://dali.tianlin.xyz/Article/details/gtwuevtici.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gteeldqzol.html

[Q26] 计数
来源：http://dali.yonumen.top/Article/details/gtkqpouoyy.html

SELECT COUNT(*) FROM users;
来源：http://dali.havefunace.top/Article/details/gtcupvppkm.html

[Q27] 条件计数
来源：http://dali.chenzaomai.com/Article/details/gtkjhnxkip.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gtqavcaynb.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfxrxnle.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtytacdmzw.html

[Q29] 最大最小值
来源：http://dali.yvedp.cn/Article/details/gtsdrowqii.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtltfrbiws.html

[Q30] 分组统计
来源：http://dali.fzhhl.top/Article/details/gtfqjbzxtv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtrlcodhsp.html

[Q31] 分组后过滤
来源：http://dali.ivvv.top/Article/details/gtpzygsfdl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtidxldrcc.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtflqcqron.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtuptyxkwo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtipfrwfod.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtwofcsekh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gtvojthsoa.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtpcoeuxhr.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gttazcgmra.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtijutmpsf.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtuxgqihtx.html

[Q35] 内连接
来源：http://dali.yanxiufei.cn/Article/details/gtnqcyqyyw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtitbcjhjo.html

[Q36] 左连接
来源：http://dali.yueranfly.top/Article/details/gtedyskxym.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gtwcfvnzad.html

[Q37] 右连接
来源：http://dali.yonumen.top/Article/details/gtvtiosptx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtvwkohney.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenzaomai.com/Article/details/gtwvodfyrb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.guannengcc.top/Article/details/gtbylttkbg.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtrcvymjpo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtzorjweqv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtrqyrelei.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zycfv.cn/Article/details/gtbjhntsmz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gtxpggmtey.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gtxqtbfcrl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtfaagtqcu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xinyue.icu/Article/details/gtuxrpauxl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yonumen.top/Article/details/gtsgzogopi.html

[Q42] 连接条件附加过滤
来源：http://dali.zycfv.cn/Article/details/gtgmqzwyjf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yongpay.top/Article/details/gtuqehhgar.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtlungcoxi.html

[Q43] 标量子查询
来源：http://dali.hysaishi.cn/Article/details/gttjgabcba.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtnuuiucmv.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtvudrlxfr.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.andypj.xyz/Article/details/gtkbtbxrke.html

[Q45] EXISTS 判断存在
来源：http://dali.gogol.net.cn/Article/details/gtztepqmtt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtilmaqgzv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtdtcesxpe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gtlbmcrtgd.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtazzpyjkf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hammf.cn/Article/details/gtycchiheb.html

[Q48] CTE 公用表表达式
来源：http://dali.yanxiufei.cn/Article/details/gtoetnwjml.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hywenlv.cn/Article/details/gtfayxyoqy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gthymcmyxn.html

[Q49] 更新单行
来源：http://dali.yonumen.top/Article/details/gtjugsxyge.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtpxcqzpsp.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtvvgkfaku.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtimkylxhs.html

[Q51] 用子查询更新
来源：http://dali.pengpengdd.cyou/Article/details/gtwjuzodqq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gtgzlipzgf.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdgusgts.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtpzhnbbtv.html

[Q53] 按条件删除
来源：http://dali.ydzc1.top/Article/details/gtownxiyzb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxaimwot.html

[Q54] 清空表
来源：http://dali.pycfn.com/Article/details/gtvouxpyux.html

TRUNCATE TABLE logs;
来源：http://dali.cqqwz.cn/Article/details/gttxszrgqr.html

[Q55] 排名（并列占位）
来源：http://dali.ivvv.top/Article/details/gtahqzelhh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtwuxoszep.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtvwemdbom.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtrnfxhqyv.html

[Q57] 行号
来源：http://dali.sweek.top/Article/details/gtmvejhull.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj202588.top/Article/details/gtxngltprw.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtqofjdppc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtszvnkzyp.html

[Q59] 分组内累计
来源：http://dali.xuetiantiany.cn/Article/details/gtqxbdepqt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtwxoyghxo.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtxqzkvbag.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.pycfn.com/Article/details/gtsewltdbn.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gtxqtcajle.html

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gtmqlqfgcl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtoqllqtiz.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyvfyroe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtiksreivv.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtqiooyhar.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.fengsongda.top/Article/details/gtdsvfkihr.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtdwyylrly.html

COMMIT;
来源：http://dali.aibaodan.cn/Article/details/gtngpmhzlk.html

[Q65] 回滚事务
来源：http://dali.gzhubu.top/Article/details/gtaqsmkttw.html

ROLLBACK;
来源：http://dali.jinghuilouyu.cn/Article/details/gtijexbquc.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gthyqhytoe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.0kj1m.cn/Article/details/gtcaxeztmk.html

[Q67] 设置隔离级别
来源：http://dali.wangdashe.top/Article/details/gtptbzywvc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sufxvd.cn/Article/details/gtohgtjgjo.html

[Q68] 保存点
来源：http://dali.ppjwa.cn/Article/details/gtenjmkxhw.html

SAVEPOINT sp1;
来源：http://dali.cdnleiting.top/Article/details/gtrjlwgqvt.html

ROLLBACK TO sp1;
来源：http://dali.jianghu66.top/Article/details/gtqbjlbymy.html

[Q69] 查看执行计划
来源：http://dali.iojbl.cn/Article/details/gtvohuojaw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yongpay.top/Article/details/gtpytokliy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gtlxmooppi.html

ANALYZE TABLE users;
来源：http://dali.zycfv.cn/Article/details/gthyvmowyx.html

[Q71] 查看建表语句
来源：http://dali.andypj.xyz/Article/details/gtvmhsfisx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.birdmap.top/Article/details/gtxiputekg.html

[Q72] 查看索引
来源：http://dali.yueranfly.top/Article/details/gtuuswtpap.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuilwlwfo.html

[Q73] 查看表状态
来源：http://dali.wangdashe.top/Article/details/gtkxhousqe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gtsdtbswfa.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtaxzusdrv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yvedp.cn/Article/details/gtzemdqobz.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtifwdjljk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.meibo888.top/Article/details/gtzyfnljfm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.haohaochexian.top/Article/details/gtzogbdera.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtjeotxovn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.svipenyu.cn/Article/details/gtzbvrjclq.html

[Q77] 时间加减
来源：http://dali.chenlongwang.top/Article/details/gtnrthrjtz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtmcjopjvt.html

[Q78] 当前时间
来源：http://dali.cqqwz.cn/Article/details/gtyotpixov.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258888.top/Article/details/gtifyfnvro.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtznnyuqrd.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yuxming.cn/Article/details/gtmrciqsxp.html


<!-- 参考信息 -->