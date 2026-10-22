代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gtniyxucas.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtakqwrzbl.html

Ruby: Thread.new { f }
来源：http://dali.ehwqpu.com/Article/details/gthyvaqugz.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gttatrflxm.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gttofxwonm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtpibzhaxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtxdihgacq.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtexfaxyeb.html

TS:   // worker_threads 线程池
来源：http://dali.tian-w.cn/Article/details/gtapnofimb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gttpyjudml.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.c1oappe.top/Article/details/gtsqvoeyey.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cqqwz.cn/Article/details/gtzpahxsbo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtruzxgznv.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gtntqhnqgm.html

Py:   with lock: shared += 1
来源：http://dali.xziqi.cn/Article/details/gtcfkyffdk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gtcvjqeisv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtxekmhced.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtpopszwlm.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gthecjvtxg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gttsgykzgh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gtbqmmfbbr.html

C#:   lock (gate) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtrdkslwfz.html

[O04] 定义异步函数并等待
来源：http://dali.9152youxi.cn/Article/details/gtfdeovkwf.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gtunilgvqc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shuidangran.top/Article/details/gtyoxgvmau.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtmitmireg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtzyilnauv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtapoxdtki.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ivvv.top/Article/details/gtbtbhzeaw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gtycptzdvy.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqnmftks.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtvawsbrhh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.9152youxi.cn/Article/details/gtlgzsjwgv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtbybesqbo.html

JS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtezdurnlq.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtyqzlwgsk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelxwknzz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtiyiitnjl.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtillivkox.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtmkzrhdre.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtbwvxccel.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.meibo888.top/Article/details/gtjvzhzpyj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gthnimfmyk.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtdfxfrjlg.html

TS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtbeyibppw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtkvbdpqsu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtfnlbcjsb.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtcchopbbt.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtvvzwpmsr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfjukehlw.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtkxenvszt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtakudbdnj.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gthivtgedn.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgfzy.top/Article/details/gtyrjhtxfv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gthlbfdbtv.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtlxxookwu.html

TS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtxufkorio.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenlongwang.top/Article/details/gtdnvdeujy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gtzloytjdp.html

Ruby: SecureRandom.uuid
来源：http://dali.nwbrower.top/Article/details/gtrgqkvquo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtnzcgmmyc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtjrbbsurc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gteazbskir.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtxhxaelkc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtnaafxddd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gtdootwbdr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpaxtmmv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.snrcjt.cn/Article/details/gtelsdewjc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbayxukbb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtbsrsdtpo.html

[P03] 生成短随机字符串
来源：http://dali.jqgfzy.top/Article/details/gtrulwsksv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtaxehoiep.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gtaqacmgpb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvriwtoux.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtcqnkrgon.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenzaomai.com/Article/details/gtoayqjpnz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtaacqgczp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtfoimikko.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sysykeji.top/Article/details/gtcjisstdu.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtkyutabck.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtbwnxgnxz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtzzrqwoht.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtwzujvrrj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtndobvjnk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aizwys.cn/Article/details/gtvovngcdd.html

Go:   len(arr);  len(m)
来源：http://dali.0kj1m.cn/Article/details/gthehzqdgr.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gttdriqztq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtnapurntt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtbcovvevm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtlzxvfvzr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jiagoushi.top/Article/details/gtttsnnvno.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.haohaochexian.top/Article/details/gtommurjnr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtszpzxxyk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtbtflnhgg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yueranfly.top/Article/details/gtcjkpcpmk.html

Ruby: a == b
来源：http://dali.gzhubu.top/Article/details/gtolombrlt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbphouje.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xinyue.icu/Article/details/gtylrqyqpt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gtwiwuawfs.html

PHP:  if (empty($x)) {}
来源：http://dali.yangfankeji.com/Article/details/gtsbqiuadr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gtgoqqhmzv.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gteqgmyacw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtjjkctpkd.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gtpobqeuyr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtertejybt.html

C#:   if (x is null) {}
来源：http://dali.ybcxt.top/Article/details/gtfjjdniqi.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtucjrdeii.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtyewopiud.html

PHP:  // 手写时间戳比较
来源：http://dali.svipenyu.cn/Article/details/gtqqfekcfc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtedefhbtv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtigzxehsp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gtrswzodfr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinghuilouyu.cn/Article/details/gtuggjfzpy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtjsikobrk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuanzx.com/Article/details/gtekyagvaf.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtbgatpzzc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtluupxbbe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gtufdqgyen.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.wangdashe.top/Article/details/gtwvvgwfgb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlccohbc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtrwepmdlz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigfzy.top/Article/details/gthlwazcbt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtpyfigmmm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtptxageuj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtmehihtrl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gtvltnndzg.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjltssykh.html

[Q01] 创建表
来源：http://dali.cashguo.top/Article/details/gtzkcapodl.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtobyylkta.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yangfankeji.com/Article/details/gttaltvjqh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gtiamevfcq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtoszumcbg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gttphemtqc.html

);
来源：http://dali.9152youxi.cn/Article/details/gtazsbbsyh.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtflftirmm.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gtfilsmxmn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtvtntoife.html

user_id INT NOT NULL,
来源：http://dali.snrcjt.cn/Article/details/gttyjplnko.html

amount DECIMAL(10, 2),
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnocblch.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtnkzarvzf.html

);
来源：http://dali.daxiang520.top/Article/details/gtibdxfwdy.html

[Q03] 增加列
来源：http://dali.jianghu66.top/Article/details/gtwxadbaas.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtjuluvmqi.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtzyxtlktl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.havefunace.top/Article/details/gtptjxzdgc.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gtsbnosten.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtnitwgplh.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gtlmyiegax.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.guannengcc.top/Article/details/gtwzffcibx.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtpfitbejt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.andypj.xyz/Article/details/gtrdoewrtb.html

[Q08] 创建普通索引
来源：http://dali.hnqzz.top/Article/details/gtemzwkozy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yvedp.cn/Article/details/gtmnuekacb.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gturakwqrb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.meibo888.top/Article/details/gtzqjqdycw.html

[Q10] 插入单行
来源：http://dali.zhoulong.xyz/Article/details/gtntmsipah.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtaonguswf.html

[Q11] 一次插入多行
来源：http://dali.chenlongwang.top/Article/details/gtdkggcnps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangdashe.top/Article/details/gtmuerqahz.html

[Q12] 插入后取自增 ID
来源：http://dali.yj202588.top/Article/details/gtwwxbnafp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrcpvvwz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zdqjudy.top/Article/details/gttbscixgd.html

[Q13] 忽略重复插入
来源：http://dali.pengpengdd.cyou/Article/details/gtjbecdtno.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gtaovadfol.html

[Q14] 存在则更新（upsert）
来源：http://dali.shuidangran.top/Article/details/gttfyudccm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gtwacewbqx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ehwqpu.com/Article/details/gtobmeutep.html

[Q15] 查询全部
来源：http://dali.wangdashe.top/Article/details/gtpvwggeih.html

SELECT * FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbzqchzuj.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtbukomdgc.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtobhrwtom.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtqmtgjepi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yj20258.top/Article/details/gtkdgavzqc.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gtipbhfxoi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtixdbkyat.html

[Q19] 范围查询
来源：http://dali.tianlin.xyz/Article/details/gtfxcoaumy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.c1oappe.top/Article/details/gtgywuasyx.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtymbfwukz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gtlaaafcyl.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gtpsrmhzbi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yj20258.top/Article/details/gtxjyappoy.html

[Q22] 排序
来源：http://dali.pengpengdd.cyou/Article/details/gtslzenuki.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gaohongyu789.top/Article/details/gtnmshyzzi.html

[Q23] 分页
来源：http://dali.kuanghao11.cn/Article/details/gtxekvbzpr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nanxinkj.top/Article/details/gtafhbltxi.html

[Q24] 去重
来源：http://dali.yj202588.top/Article/details/gtzlpiaohg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtqofoijji.html

[Q25] 只取前 N 条
来源：http://dali.gogol.net.cn/Article/details/gttnaugjxe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gtyjbktomz.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gttpgqngvw.html

SELECT COUNT(*) FROM users;
来源：http://dali.cashguo.top/Article/details/gtgthrqssv.html

[Q27] 条件计数
来源：http://dali.guowangkeji.top/Article/details/gtnihhenir.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj202588.top/Article/details/gtvwdkgdcm.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtxwepugxr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtbyfrpjgn.html

[Q29] 最大最小值
来源：http://dali.yj202588.top/Article/details/gtvuwilsnv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtemdpckgj.html

[Q30] 分组统计
来源：http://dali.jqgufenzy.top/Article/details/gtbvnbalrr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtogvnobhn.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtoflmxvvj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtynhnmign.html

[Q32] 分组拼接字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtluvzpbip.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtzgfjhquq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtyfjkqkrl.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gtxrfxulpc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sysykeji.top/Article/details/gtooieqspr.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtetwfnxvf.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtngbpsyuz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gtrdyqvbba.html

) t WHERE rn = 1;
来源：http://dali.gogol.net.cn/Article/details/gtntzhxfeq.html

[Q35] 内连接
来源：http://dali.haohaochexian.top/Article/details/gtjisolrbq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtgtklliiy.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtakeiozxd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtchbphqqq.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtxisezurv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cdnleiting.top/Article/details/gthoydtzxg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenlongwang.top/Article/details/gtppclgwhk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.vqdsnc.cn/Article/details/gtnfgzroyp.html

[Q39] 自连接（查上下级）
来源：http://dali.fengsongda.top/Article/details/gtmweywgej.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shzxlz.cn/Article/details/gthpnhlfou.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.smart0.xyz/Article/details/gtcbdzfodh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtzaocgwtt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gthfnclsuh.html

[Q41] 多表连接
来源：http://dali.sufxvd.cn/Article/details/gtiayqxpqe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cheryme.top/Article/details/gtwcayhhkq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xuetiantiany.cn/Article/details/gtfbzcwhwh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtnkigubag.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtbxpoeszb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gzhubu.top/Article/details/gtkfwkjjhc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhoulong.xyz/Article/details/gtogefizrn.html

[Q43] 标量子查询
来源：http://dali.yonumen.top/Article/details/gtrasmjmah.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtnlhckfpm.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtugipqkyz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jianghu66.top/Article/details/gtxrbyecmm.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtpeoenxex.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daxiang520.top/Article/details/gtaxrlgqll.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtdtfjlfir.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtdacpafvh.html

[Q47] 与平均值比较
来源：http://dali.tian-w.cn/Article/details/gtkiwqasdj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gtsoewzksj.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtkkkcslem.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenjidiqi.icu/Article/details/gtzkievbbt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hammf.cn/Article/details/gtnordfdph.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gtpapqhsjp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtauhwyuby.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gthfglqrcg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tian-w.cn/Article/details/gtmrkpkgsq.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtzjmhonbr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshkthkhn.html

[Q52] 删除指定行
来源：http://dali.yonumen.top/Article/details/gtwwlpbuli.html

DELETE FROM users WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtsowfyihd.html

[Q53] 按条件删除
来源：http://dali.daxiang520.top/Article/details/gtbwgthpbl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gtjqhtivkm.html

[Q54] 清空表
来源：http://dali.meibo888.top/Article/details/gtxivvapsx.html

TRUNCATE TABLE logs;
来源：http://dali.ehwqpu.com/Article/details/gteflrqntr.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtikkjqyhz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xuanzx.com/Article/details/gtgreymbhv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ybcxt.top/Article/details/gtpuysojxj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtudbboaqk.html

[Q57] 行号
来源：http://dali.pycfn.com/Article/details/gtjztlyhrj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtqnlctyky.html

[Q58] 累计求和
来源：http://dali.zhiwuduotai.top/Article/details/gtksaircia.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtxqusghti.html

[Q59] 分组内累计
来源：http://dali.zhengqikj.top/Article/details/gtosjrgbxy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtbbzmsqix.html

[Q60] 取上一行 / 下一行
来源：http://dali.hongshengwenyu.top/Article/details/gtvyythqwc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gtdqemwsoz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtxbhrhxkc.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gtwfyvsjpm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cashguo.top/Article/details/gteckqtlos.html

[Q62] 分组占比
来源：http://dali.yuanzhike.top/Article/details/gtwsareyqu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtiouskfgf.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtmurahcmo.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hammf.cn/Article/details/gtoxzniljp.html

[Q64] 提交事务
来源：http://dali.jqgfzy.top/Article/details/gtzmebosxr.html

COMMIT;
来源：http://dali.zhoulong.xyz/Article/details/gtatocigrf.html

[Q65] 回滚事务
来源：http://dali.yuxming.cn/Article/details/gtxzqfhqnt.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtroesjtvw.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtysdhkbxr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtqzgrqlhz.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gtordhtvuq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yueranfly.top/Article/details/gtudcaiswh.html

[Q68] 保存点
来源：http://dali.chenlongwang.top/Article/details/gtchyqmdcy.html

SAVEPOINT sp1;
来源：http://dali.vqdsnc.cn/Article/details/gtwydcxwsr.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtiebpuowx.html

[Q69] 查看执行计划
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzmnuqrq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtjrxlxbpp.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtcxxtvnmx.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtphmiyliz.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtrczzoozd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yueranfly.top/Article/details/gtmrkwmety.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtcikuxtbc.html

SHOW INDEX FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtjoyvnrnh.html

[Q73] 查看表状态
来源：http://dali.yuxming.cn/Article/details/gttrltggor.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtthsdmybr.html

[Q74] 强制使用索引
来源：http://dali.ehwqpu.com/Article/details/gtfvclyyvd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuanzx.com/Article/details/gttnfjpskb.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtnbndwdat.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtjnbzxcpg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnukhtoi.html


<!-- 参考信息 -->