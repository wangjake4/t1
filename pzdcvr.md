代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtcuabwxwe.html

[O03] 加锁保护共享数据
来源：http://dali.dashuyun.cn/Article/details/gtooxcvcrg.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gtgycqooej.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtdigkthhc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gtvkzohzih.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gtphgkmzoc.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtamxcfxvu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtgzfnxwku.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cqqwz.cn/Article/details/gttumnpkfy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtddlofjdm.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtauhsqdml.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgksphic.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gtldgcadgy.html

JS:   async function f() { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtqzcqzmik.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gtdfcmmjtq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gtfxeyjrvu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtxcvzlykb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gtgkpuwhsl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtttyelgwz.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gtsztvxlim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yueranfly.top/Article/details/gtcgsqjenj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtyknztnnv.html

JS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gtximukjmq.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtidyctvas.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gtntoopxwx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtokzemifi.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gttxdggbbb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsislyts.html

[O06] 使用进程池
来源：http://dali.shangyingyoupin.top/Article/details/gtxufcvkvn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.snrcjt.cn/Article/details/gtfkcmclgi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtouxlhfhb.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtwzbagbqj.html

TS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtduysuszz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ydzc1.top/Article/details/gtxzisgecl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtuhwhheml.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtksvpecav.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtrlhmjjsf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkwixwdqc.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gtgmqgizzw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtenhjtfbm.html

[P01] 生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtnectsziv.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gtzncijopf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jyoumei.cn/Article/details/gtxkqkerdp.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwyfwkvy.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtvccbktnc.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtqcwichjn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtwhpiirny.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gtbnscomzg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuanzx.com/Article/details/gtyngaxebt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtutlwnrxy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtautwcnzg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtkttcicgf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258888.top/Article/details/gtaaakckfb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtchtaurnm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gtnunxypxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtjhndlyfd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gtgzlnzesd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinghuilouyu.cn/Article/details/gtdglrnmoh.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtqoiykkkk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gthvobsjlf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.316326.xyz/Article/details/gtqjqtazzv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrvzlcwm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cdnleiting.top/Article/details/gtsvclcznn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtxwxdirbo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.redwolf501.top/Article/details/gtoahouwis.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtloxsboqx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyzglcgf.html

[P04] 求长度
来源：http://dali.yuanzhike.top/Article/details/gtthqwohmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gtckgqgtem.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gteohvuzyu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtvxhbghfh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtccqgalsu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tianlin.xyz/Article/details/gttjymaeyc.html

Go:   len(arr);  len(m)
来源：http://dali.jqgufenzy.top/Article/details/gttfjieolr.html

Ruby: x.length;  x.size
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqbddxwa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxfwdkztg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigfzy.top/Article/details/gtjsjiksnn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gtyobivuhc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtpbrbkyja.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gtaygubmse.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtraleqzbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtunubxsav.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtqtgkdtyp.html

Ruby: a == b
来源：http://dali.daxiang520.top/Article/details/gteeacvlxp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtkddtmnyu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtpxsrvqmx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtrwlvofly.html

PHP:  if (empty($x)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtizlzxqbp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guannengcc.top/Article/details/gtxcutjndo.html

TS:   if (x == null) {}
来源：http://dali.jinqigfzy.top/Article/details/gtujvrhzur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtzmsdliiv.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtljgsngbs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gaohongyu789.top/Article/details/gtpyrmcvho.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gtvxnwjwcg.html

[P07] 防抖与节流
来源：http://dali.jqgufenzy.top/Article/details/gttkrighwi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gtqcdaiwky.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtzseuvant.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtsyglhupd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gthmgroqnz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gtcytxmefo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hysaishi.cn/Article/details/gtsrenexqe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinqigfzy.top/Article/details/gtoqchrzbc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbyhxzktf.html

[P08] 处理浮点精度问题
来源：http://dali.0kj1m.cn/Article/details/gtactquicg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.bjfxy.top/Article/details/gtxrrxabkl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtbtslrqov.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gtcowzbqhr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gtrxfvqivt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtmotafcsc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guannengcc.top/Article/details/gtvemqsgxk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gtmqfsqrfw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtwvwstsxv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjwqbnzqx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsjlkdos.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gteijkszii.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gtxvkuckkv.html

CREATE TABLE users (
来源：http://dali.xuetiantiany.cn/Article/details/gtgssyjbev.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yonumen.top/Article/details/gtuawtpatp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtpjzwdltu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ppjwa.cn/Article/details/gtspgvkdxc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtocridvlb.html

);
来源：http://dali.sufxvd.cn/Article/details/gtuqqtlgdt.html

[Q02] 创建带外键的表
来源：http://dali.shuidangran.top/Article/details/gtqozigfxj.html

CREATE TABLE orders (
来源：http://dali.zhixingplan.top/Article/details/gtgpgxrfzm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtinkkwwcs.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtcydcthfg.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtbughznjb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sxryk.cn/Article/details/gtycnzewgz.html

);
来源：http://dali.zhengqikj.top/Article/details/gtdopfqlpv.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtxidvsjzq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.andypj.xyz/Article/details/gtavvioasj.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtqjqjdpeo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.haohaochexian.top/Article/details/gtyqgxsubf.html

[Q05] 重命名列
来源：http://dali.jinqigufen.top/Article/details/gtnszzbnas.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.quarkkingdee.top/Article/details/gtmufbufqb.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtssvxurxq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.nanxinkj.top/Article/details/gtjbyeqkqo.html

[Q07] 删除表
来源：http://dali.gotoacloud.top/Article/details/gtfydsxqkv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daxiang520.top/Article/details/gtmodliidd.html

[Q08] 创建普通索引
来源：http://dali.gotoacloud.top/Article/details/gtkccmlupd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hywenlv.cn/Article/details/gtbgcjpvxj.html

[Q09] 创建唯一索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyegcixv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtuwngobht.html

[Q10] 插入单行
来源：http://dali.gogol.net.cn/Article/details/gtrkspqjbz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtbajhjfgw.html

[Q11] 一次插入多行
来源：http://dali.yvedp.cn/Article/details/gtlfmmmlek.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtqwgkynja.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gtfvzofrbt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hysaishi.cn/Article/details/gtxfmcubwv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cucudq.cn/Article/details/gteikytypa.html

[Q13] 忽略重复插入
来源：http://dali.cqqwz.cn/Article/details/gttoyzzace.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hnxiangtu.top/Article/details/gtilttbzus.html

[Q14] 存在则更新（upsert）
来源：http://dali.sysykeji.top/Article/details/gtcyrbskij.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yangfankeji.com/Article/details/gtsdxgozhy.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.gzhubu.top/Article/details/gtmcojwujt.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtzarcschf.html

SELECT * FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtuviphjfs.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gtamucsieu.html

SELECT id, name FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtofhsydvn.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gtrzzavtnu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.aibaodan.cn/Article/details/gtpbvgtqum.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gtvzvnkkwl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtmsyiumby.html

[Q19] 范围查询
来源：http://dali.zdqjudy.top/Article/details/gtqpowgmuc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gtfhboequq.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtfvxigspm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hfpthk.cn/Article/details/gtevmksbnh.html

[Q21] 空值判断
来源：http://dali.havefunace.top/Article/details/gtmrzpqqml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.quarkkingdee.top/Article/details/gtsxhczmgx.html

[Q22] 排序
来源：http://dali.guowangkeji.top/Article/details/gtbryyulut.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ehwqpu.com/Article/details/gtrclorhwz.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtekzoyjoz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.redwolf501.top/Article/details/gtommqqixk.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtyqdtlujx.html

SELECT DISTINCT city FROM users;
来源：http://dali.yvedp.cn/Article/details/gtzqclalqo.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gtkbizkojh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hywenlv.cn/Article/details/gtwqgspcku.html

[Q26] 计数
来源：http://dali.fengsongda.top/Article/details/gttbgubuuf.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtxzkmjbqa.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gtxzewkubm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtidaqqckg.html

[Q28] 求和与平均
来源：http://dali.zhixingplan.top/Article/details/gtgsqpdvvo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtvyapmohm.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtvdyrhuxp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.bjfxy.top/Article/details/gtobatygsq.html

[Q30] 分组统计
来源：http://dali.hongshengwenyu.top/Article/details/gtgbhnlotp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtpwggvzgr.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtfwygerwy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhengqikj.top/Article/details/gtvnjokrgh.html

[Q32] 分组拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtpltughfl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtwsrvnuwv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj202588.top/Article/details/gtgqxmcehf.html

[Q33] 多列分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtboyjukqs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.daxiang520.top/Article/details/gtvnveyvmf.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtqgvdlnej.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gtfysmntec.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.c1oappe.top/Article/details/gtxszpxtbl.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gtvqohphta.html

[Q35] 内连接
来源：http://dali.shzxlz.cn/Article/details/gtfyrovgqw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jianghu66.top/Article/details/gtgzpoeahz.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtczjuyjow.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtvbixtukn.html

[Q37] 右连接
来源：http://dali.c1oappe.top/Article/details/gtpynetvcq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtqavtfuru.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtndtjxlxb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.iojbl.cn/Article/details/gtlklfygtk.html

[Q39] 自连接（查上下级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcixqurkq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gtkyremdvo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gtvyihteak.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gtmsbnsgmn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dianchejie.cn/Article/details/gtbslsadhr.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtajploazc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtmhefsnix.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gtmmgmlrqj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sysykeji.top/Article/details/gtupsewuqf.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtnklyqrml.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shangyingyoupin.top/Article/details/gtfghmsjqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hysaishi.cn/Article/details/gtqhashlwx.html

[Q43] 标量子查询
来源：http://dali.shuidangran.top/Article/details/gtzmljcrys.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtexjqiwvp.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrgjalbn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtuvoifhnm.html

[Q45] EXISTS 判断存在
来源：http://dali.cheryme.top/Article/details/gtpoxcekqf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gthbftajdp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.fzhhl.top/Article/details/gtvojuhtui.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yvedp.cn/Article/details/gtvmrpmpvf.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gtnzxmfzan.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhongyouzk.top/Article/details/gtlatigvvl.html

[Q48] CTE 公用表表达式
来源：http://dali.gzhubu.top/Article/details/gtrqankzgd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqwjpmfv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cheryme.top/Article/details/gtulaeraak.html

[Q49] 更新单行
来源：http://dali.hywenlv.cn/Article/details/gtgkfixams.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtrmueekll.html

[Q50] 批量更新
来源：http://dali.aizwys.cn/Article/details/gtjfnxhgqa.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dashuyun.cn/Article/details/gthmzbnyyk.html

[Q51] 用子查询更新
来源：http://dali.pycfn.com/Article/details/gtlxxaeebm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gtgbkjmgnn.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzixcwof.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtdqcnntaw.html

[Q53] 按条件删除
来源：http://dali.ehwqpu.com/Article/details/gtgnlgbbfg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtdldfvdir.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gteeewxmbh.html

TRUNCATE TABLE logs;
来源：http://dali.zhengqikj.top/Article/details/gtvzjkwqze.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gthsmnknzp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtntooxoda.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jianghu66.top/Article/details/gttehwukgj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hongshengwenyu.top/Article/details/gtknyhcnnw.html

[Q57] 行号
来源：http://dali.gotoacloud.top/Article/details/gtlhdwnkqo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtsliidwti.html

[Q58] 累计求和
来源：http://dali.iojbl.cn/Article/details/gtxkeadgri.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtjmcschsg.html

[Q59] 分组内累计
来源：http://dali.xziqi.cn/Article/details/gtlriyqyfa.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtsyjhuxhu.html

[Q60] 取上一行 / 下一行
来源：http://dali.sweek.top/Article/details/gtjdfubnib.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhiwuduotai.top/Article/details/gttxgbewgx.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtdyjfhnza.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtikqwfgro.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtbfailjgl.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtslnjsbym.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gtpjkcqezi.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gtbqnrwfip.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.9152youxi.cn/Article/details/gtpeceirjz.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtkhfwxrbh.html

COMMIT;
来源：http://dali.xinyue.icu/Article/details/gtwatfsbfu.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtqvmsebht.html

ROLLBACK;
来源：http://dali.jinqigfzy.top/Article/details/gtjipbxrrq.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gtkcshccdj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrfkgpeo.html

[Q67] 设置隔离级别
来源：http://dali.zycfv.cn/Article/details/gtoadtcmal.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.vqdsnc.cn/Article/details/gteofvneyr.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gtjqklrnem.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtsrdkjuji.html

ROLLBACK TO sp1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkykiaglw.html

[Q69] 查看执行计划
来源：http://dali.hfpthk.cn/Article/details/gtdtvsknvd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gtxalgpelq.html

[Q70] 更新统计信息
来源：http://dali.jiagoushi.top/Article/details/gtoitezbou.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gtuhzaxwbj.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtbxggeevx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xylfe.cn/Article/details/gttbgqxdow.html

[Q72] 查看索引
来源：http://dali.redwolf501.top/Article/details/gtrhlmaian.html

SHOW INDEX FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtpbahlxwf.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gtygdtfzkr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daxiang520.top/Article/details/gtcyefsckf.html

[Q74] 强制使用索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfncyapb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtryxpzzpo.html

[Q75] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gtookzemoo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtwmyhrhgn.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtrxdmjuac.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gtyfstjsgh.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtzmkkreuv.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtyzbbaldf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtbydbtoqy.html

[Q78] 当前时间
来源：http://dali.ydzc1.top/Article/details/gtwcvgdcuu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.wangshuangyany.cn/Article/details/gtynuahsbt.html

[Q79] 字符串拼接
来源：http://dali.havefunace.top/Article/details/gtoqtbarne.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtzrnwccsb.html

[Q80] 字符串截取
来源：http://dali.havefunace.top/Article/details/gtktfycdxa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtjbbidlsi.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtdnkvtyod.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtwzeigqja.html


<!-- 参考信息 -->