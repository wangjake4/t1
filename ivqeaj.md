代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtvcvsejxc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtlpylqntl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiignxvlm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gtgnlfquxf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gturkvnumr.html

[O03] 加锁保护共享数据
来源：http://dali.ppjwa.cn/Article/details/gtwbtqlssz.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gtewkidbyo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daxiang520.top/Article/details/gtwnhfrbou.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yueranfly.top/Article/details/gtlrjjngcy.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtnkgvdhxx.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtjnojyudf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dianchejie.cn/Article/details/gtydjqoazi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gtxcjyoznm.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtatmumdop.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtigmtzruq.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbltbjpyd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtoopqkwlf.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvzqgpsat.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtqijiasnw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtuiibymrf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtzmhqvkib.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dianchejie.cn/Article/details/gtkvlwolaf.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtrlgumtyo.html

[O05] 并发执行并等待全部完成
来源：http://dali.yongpay.top/Article/details/gtfqotkbpj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jqgfzy.top/Article/details/gtaatdeixm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gtvvvcuwkf.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gteuwfxgnb.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtkiqonfuf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtveqyqwue.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gtjrpxysis.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtbrukhmfd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zdqjudy.top/Article/details/gtcdbgybcr.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gtkuqceeht.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gtlmblbdyr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtqjxtdqux.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gtgotmofqu.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtywahmaks.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cqqwz.cn/Article/details/gtlejciwgu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtbuhwswam.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gttjdyfpgv.html

C#:   Parallel.For
来源：http://dali.kuanghao11.cn/Article/details/gtxzuquoti.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqzzqsaqt.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gtlxbpdyzy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrqkdwnhx.html

[P01] 生成 UUID
来源：http://dali.tanke756.top/Article/details/gtutidccdl.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gtonchpvjw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtimdninzk.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtddvptjfa.html

TS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtqdipnaqs.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxovxkqjd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtbjohnvro.html

Ruby: SecureRandom.uuid
来源：http://dali.ybcxt.top/Article/details/gtbeqvpkcb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtubqmqfwt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.havefunace.top/Article/details/gtoqmsvrcf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtatuppjkb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtkmhwrbok.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtuwucjwzd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtjqlcnvdi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtaryptkmh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtqgzgwmem.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gtwvigswnh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hywenlv.cn/Article/details/gtshkakbrf.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtrgahlhmh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guowangkeji.top/Article/details/gttefededv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtzqxbmieg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtmahlctyx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gtpzypfimb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtizkxcgjb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yuanzhike.top/Article/details/gtgpgcvcpr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gtuwrtdepg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yongpay.top/Article/details/gtaqxjtvwb.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtgdnlvuyr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gtnhudwbqd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gtcfhuwqab.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sysykeji.top/Article/details/gtrektudur.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtrrbvqils.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gtuypxcarg.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gtwrvrgzve.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtqcnqaygu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtjbjzkdrt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gogol.net.cn/Article/details/gtzybulwhe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtqlgrfekd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sxryk.cn/Article/details/gtvmjvbzqg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.316326.xyz/Article/details/gtcaldjtpq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtnwxoahqq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gteetfrtqy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.meibo888.top/Article/details/gtckytblkc.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtlnvwjtsy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gtsnywbmgd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtxzgnerap.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ppjwa.cn/Article/details/gtybxwvcyt.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtpillvtng.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhiwuduotai.top/Article/details/gtabfwytno.html

TS:   if (x == null) {}
来源：http://dali.daxiang520.top/Article/details/gtkpfwbspo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnqzz.top/Article/details/gtvyduhjqn.html

Go:   if x == nil {}
来源：http://dali.zhengqikj.top/Article/details/gtixwfovpq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zycfv.cn/Article/details/gtswqknpji.html

C#:   if (x is null) {}
来源：http://dali.aizwys.cn/Article/details/gtxryatkpp.html

[P07] 防抖与节流
来源：http://dali.chenlongwang.top/Article/details/gtnuzrtrha.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtcpczmany.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gtqpqrhguf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtzbwvpplk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtwhiyuvjy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zycfv.cn/Article/details/gtcazedhwc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hammf.cn/Article/details/gtnktubglv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jyoumei.cn/Article/details/gtzoafpnhq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gtkmhhlfuz.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gthybqoyri.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtnfhhxgrz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.fzhhl.top/Article/details/gtlywzepal.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtypachwvh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gtvdetdqgm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangshuangyany.cn/Article/details/gtbzurpyld.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gthywjfwxq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.pengpengdd.cyou/Article/details/gtdtkczgzk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangtech.top/Article/details/gtlelcfzua.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtsgctuzbj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gtihsagyff.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwmehxajq.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gtjedufglu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gttgumjpyc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtqdpcnhkw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtshtcxazm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gtmkoyrddw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jiagoushi.top/Article/details/gttxchjnjy.html

);
来源：http://dali.dianchejie.cn/Article/details/gtesmempvh.html

[Q02] 创建带外键的表
来源：http://dali.daria6918.cn/Article/details/gtubujvaff.html

CREATE TABLE orders (
来源：http://dali.yongpay.top/Article/details/gtuavmkfrg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtbuikyvph.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakqpkbdt.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtxgvgwhce.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.wangdashe.top/Article/details/gtllpmmdqf.html

);
来源：http://dali.nanxuanxn.top/Article/details/gtanvxnfbk.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gthwvjykzs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gtywqccpdo.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gtibmwtocu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gthwicxxuu.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gtmvhuzapm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sweek.top/Article/details/gtuttvblci.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gtvklydtzj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pycfn.com/Article/details/gtkqgjnqux.html

[Q07] 删除表
来源：http://dali.jqgfzy.top/Article/details/gtfyqquzzz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgufenzy.top/Article/details/gtnoixonyz.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtjtlaxzjx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpybbgwcv.html

[Q09] 创建唯一索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqccvyxl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtyyfsesxm.html

[Q10] 插入单行
来源：http://dali.smart0.xyz/Article/details/gtfqyrkizm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.dashuyun.cn/Article/details/gtnlgjepjb.html

[Q11] 一次插入多行
来源：http://dali.jyoumei.cn/Article/details/gtjqprkhkh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jianghu66.top/Article/details/gtkochfvyu.html

[Q12] 插入后取自增 ID
来源：http://dali.sufxvd.cn/Article/details/gtudrcwwjo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowvctgvt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhengqikj.top/Article/details/gtgmcqvhlo.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtbmsbkutm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yj20258.top/Article/details/gtnhfflwig.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gttcqatwbg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.aibaodan.cn/Article/details/gtibsfyavp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtwgyjoqdx.html

[Q15] 查询全部
来源：http://dali.sysykeji.top/Article/details/gtkbmhsifk.html

SELECT * FROM users;
来源：http://dali.tian-w.cn/Article/details/gtbszndorp.html

[Q16] 查询指定列
来源：http://dali.jyoumei.cn/Article/details/gtnzmirbkw.html

SELECT id, name FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooxlmjwy.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtkvsifmdb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cdnleiting.top/Article/details/gtzsldeyfh.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gttidysbda.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.ybcxt.top/Article/details/gtyehrmulp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gtetljnlzf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenlongwang.top/Article/details/gtklkapukt.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gthusikfrp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgfzy.top/Article/details/gtercmjnht.html

[Q21] 空值判断
来源：http://dali.haohaochexian.top/Article/details/gtldkuvsds.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fzhhl.top/Article/details/gtfxszuqui.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtafpxfwjh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtmikejvpu.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtobvwycuj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gtvbyzrusi.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gtiwkrngzx.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtaamdmfal.html

[Q25] 只取前 N 条
来源：http://dali.chenzaomai.com/Article/details/gtsojkgkmy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gtrjrmhkrt.html

[Q26] 计数
来源：http://dali.daxiang520.top/Article/details/gtbsrybpnm.html

SELECT COUNT(*) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtwuhfrrcd.html

[Q27] 条件计数
来源：http://dali.havefunace.top/Article/details/gtfttmlllg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtlvbcsyds.html

[Q28] 求和与平均
来源：http://dali.yj20258.top/Article/details/gtjzbvjtcl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtfhktssmg.html

[Q29] 最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtqmrajjws.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtaziwsvfx.html

[Q30] 分组统计
来源：http://dali.hnqzz.top/Article/details/gtrbeiowvq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtrcrdhkmv.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gtdhrgoyun.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtctjhmlnu.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtklnnpfle.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtpgwrazix.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinqigfzy.top/Article/details/gtyuvljjoz.html

[Q33] 多列分组
来源：http://dali.vqdsnc.cn/Article/details/gtimwjfepz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.dashuyun.cn/Article/details/gtzqkuipqi.html

[Q34] 每组取第一条
来源：http://dali.xuetiantiany.cn/Article/details/gtxkcskxat.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtnnxodfhp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhengqikj.top/Article/details/gtwctiojjd.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtfavgcklo.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gtijbesdht.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtbarubzwc.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gtwsxpjayi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtlpzxixtq.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtmkkyfrot.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtlceepszr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.guannengcc.top/Article/details/gtoshadbnq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daxiang520.top/Article/details/gtaiaphwro.html

[Q39] 自连接（查上下级）
来源：http://dali.hnqzz.top/Article/details/gtfotyezvh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirntnfen.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhongyouzk.top/Article/details/gtrojxpztt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cheryme.top/Article/details/gtgqqycejf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.316326.xyz/Article/details/gtbaoxarwe.html

[Q41] 多表连接
来源：http://dali.sxryk.cn/Article/details/gtinosmive.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtuahbxp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtmwhhlscw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.mhx1999.top/Article/details/gtoaeatuhv.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gttzttpolb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zycfv.cn/Article/details/gtozzkcqzq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.birdmap.top/Article/details/gtfpypwwuo.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtwfmutrcf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnxiangtu.top/Article/details/gtyswpevom.html

[Q44] IN 子查询
来源：http://dali.chenjidiqi.icu/Article/details/gtgjhubolm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.9152youxi.cn/Article/details/gtxeymcdzy.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtceusitkg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenlongwang.top/Article/details/gtjeervubc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.mhx1999.top/Article/details/gttpopqydo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.birdmap.top/Article/details/gtxdvnajxl.html

[Q47] 与平均值比较
来源：http://dali.zhongyouzk.top/Article/details/gtruejoqph.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtufwfxzyl.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtklkhdbcs.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yj20258888.top/Article/details/gtqnjilkfu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtojhjihgx.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtsukcsymw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtlhfhxxke.html

[Q50] 批量更新
来源：http://dali.guowangkeji.top/Article/details/gtqlpnluhx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jyoumei.cn/Article/details/gtfavotzgh.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtvturidgt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtluawnkga.html

[Q52] 删除指定行
来源：http://dali.xinyue.icu/Article/details/gtaevdvrgl.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hfpthk.cn/Article/details/gtucabdjjp.html

[Q53] 按条件删除
来源：http://dali.redwolf501.top/Article/details/gtcbkwbvlz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xylfe.cn/Article/details/gtxkfnzvao.html

[Q54] 清空表
来源：http://dali.nanxinkj.top/Article/details/gtnazkjqlp.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gtovkxvghv.html

[Q55] 排名（并列占位）
来源：http://dali.hnqzz.top/Article/details/gtpkbvauka.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gttdncnbpi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fengsongda.top/Article/details/gtylozpqgs.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.pycfn.com/Article/details/gtzfkizetm.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtwozkbbdc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xylfe.cn/Article/details/gtoazsxbre.html

[Q58] 累计求和
来源：http://dali.aibaodan.cn/Article/details/gtzluapuaq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gtjwfamcqj.html

[Q59] 分组内累计
来源：http://dali.wangshuangyany.cn/Article/details/gthaerpnbr.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtddczyvzr.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtsdmzttll.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.9152youxi.cn/Article/details/gtrsltpaoy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtnomnraai.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtwsormyku.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtupxqubsb.html

[Q62] 分组占比
来源：http://dali.haohaochexian.top/Article/details/gtpmbaawmq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtpuknjoek.html

[Q63] 开启事务
来源：http://dali.nwbrower.top/Article/details/gtrucmmhnw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtvldehiwe.html

[Q64] 提交事务
来源：http://dali.yonumen.top/Article/details/gtnsolflro.html

COMMIT;
来源：http://dali.yonumen.top/Article/details/gtmivuymeh.html

[Q65] 回滚事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtpaewvkoh.html

ROLLBACK;
来源：http://dali.smart0.xyz/Article/details/gtkxcrmeto.html

[Q66] 行锁查询
来源：http://dali.hnqzz.top/Article/details/gtnwnpwlcd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gteonkcfot.html

[Q67] 设置隔离级别
来源：http://dali.yj20258888.top/Article/details/gtrnnwbprx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yonumen.top/Article/details/gtzlgtzqhy.html

[Q68] 保存点
来源：http://dali.meibo888.top/Article/details/gthswpjzzp.html

SAVEPOINT sp1;
来源：http://dali.birdmap.top/Article/details/gtzwqzsfwk.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtrdolexra.html

[Q69] 查看执行计划
来源：http://dali.sxryk.cn/Article/details/gtrzspecjg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zycfv.cn/Article/details/gtpmtnucir.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtgiphuglx.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtadjtpokq.html

[Q71] 查看建表语句
来源：http://dali.jqgufenzy.top/Article/details/gtqsihobda.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xuetiantiany.cn/Article/details/gtjjaacsio.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtabrbaiqe.html

SHOW INDEX FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtmfcbjpts.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtgamoalvo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xuanzx.com/Article/details/gtisxzqiwy.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gteoomtfxn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.mhx1999.top/Article/details/gtejdpwkvu.html

[Q75] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtyjzrbjnb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtnzmssaaz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cashguo.top/Article/details/gtjaottvuw.html

[Q76] 按天统计
来源：http://dali.daria6918.cn/Article/details/gtejwcrybv.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijaroixy.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtbsarzshh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtcfhnjbnz.html

[Q78] 当前时间
来源：http://dali.jlsjyb.cn/Article/details/gtmbqxfbqn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gtcgwbntge.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtbtbjpumm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hywenlv.cn/Article/details/gtpqlnmewh.html


<!-- 参考信息 -->