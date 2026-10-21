代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gttfrbsoce.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gtpqedpvlp.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtfbwbabms.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtludiufue.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmknursx.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtkgxznnvf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gttuocpokx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenjidiqi.icu/Article/details/gtuybifxzn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.c1oappe.top/Article/details/gtvtnfvivp.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtpbkmlfrz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gthcnxytnn.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtdjumlloh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtrkknuuwp.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtfqjwjeuu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtzyvrmmpa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtjqwvyiab.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbornwsvj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ybcxt.top/Article/details/gtnvpoifuz.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtceumnwgz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gteeagkozq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.snrcjt.cn/Article/details/gtjizkijgb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinyuanbaomall.cn/Article/details/gthrrkyfrb.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtxysjhkhr.html

TS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtjburzgdm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.0kj1m.cn/Article/details/gtzbselvzh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gtigulvjsj.html

Ruby: threads.map(&:join)
来源：http://dali.gaohongyu789.top/Article/details/gtwnaamxsq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.pengpengdd.cyou/Article/details/gtcyyvayun.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtooueqdvv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtrouozitx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gttmsgfhwq.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gtqmiukzzx.html

TS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtdmnurwuy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtirwwbatr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gtbjgtrlka.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gtznnnfeyh.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtzybdkttx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtspxgofnr.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtledbyuje.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtlrvudyen.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtqmlgyttd.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtxiczggch.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sweek.top/Article/details/gtpyurgdnc.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtgsyitnot.html

TS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtjahmmykz.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtukeggzbn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtwjvgslht.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gtccrijqlb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtcorltnpe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtaxyxnbqi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtjiquhhuf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dashuyun.cn/Article/details/gtpunkgvlj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gtulxfguej.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hammf.cn/Article/details/gtowrarmex.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtkqhdpync.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aibaodan.cn/Article/details/gtcvngacbp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gtdyebfwmg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtloitrybl.html

[P03] 生成短随机字符串
来源：http://dali.yangfankeji.com/Article/details/gtwkoxptuc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gtzkhygwfc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtzqtxrngd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gtbufdczbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtjesccnva.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtmgzlycif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ivvv.top/Article/details/gtzqkyxkjt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gtpvrwmzuu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.birdmap.top/Article/details/gtsvvdsjsa.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gtemabttla.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aibaodan.cn/Article/details/gtsvqfkxav.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtwkhdduop.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtalsfghgg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtausdgpmu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtzdochmjr.html

Go:   len(arr);  len(m)
来源：http://dali.jianghu66.top/Article/details/gteztnsabc.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gtjihtkouc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtmflmmjzb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cheryme.top/Article/details/gtdirlmbfh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gtupunbdxn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtmcgmftsb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtiwmqzxyy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtuyvhvtgi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.redwolf501.top/Article/details/gtwncbgtqt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gtelvuhjfs.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gtdrjbecik.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.pycfn.com/Article/details/gtsyvkldft.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gtlhmmfcxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gtizdwxhwh.html

PHP:  if (empty($x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtgwpbmtcr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.wangdashe.top/Article/details/gtuotuvfyu.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjjiepfhl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtodmvnbak.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtobaectfx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daxiang520.top/Article/details/gthivbveaq.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtyiaymyrc.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtgfnhkucm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxsmjlek.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gtqnaqswxm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtxhvfrqod.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtwnexrdbd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.meibo888.top/Article/details/gtcvnosbjz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hfpthk.cn/Article/details/gtputrbuzz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gtnguqeqbv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtxdqrzbjq.html

[P08] 处理浮点精度问题
来源：http://dali.hnqzz.top/Article/details/gtwctbhalk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cqqwz.cn/Article/details/gtwckhcyhx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gtmodqhafz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtlzhsjwgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtcyijqhpx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gtmwbhwwxi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.birdmap.top/Article/details/gtohbzobdq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.gotoacloud.top/Article/details/gtoeddysrj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gtklstayjf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtraqdiegf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtskjtojwz.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxpgjbwix.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gtkwglmsmn.html

CREATE TABLE users (
来源：http://dali.wangshuangyany.cn/Article/details/gtlnhwtjgy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtejbumrja.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtkirygrfg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sxryk.cn/Article/details/gtbmckjqea.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.dianchejie.cn/Article/details/gtwxiyzxsp.html

);
来源：http://dali.fengsongda.top/Article/details/gtlatvhqrp.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gtaytbiebr.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gtczfvlkis.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtertrbpbg.html

user_id INT NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtehygwfjr.html

amount DECIMAL(10, 2),
来源：http://dali.nwbrower.top/Article/details/gthnyapjzh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtfyvgzswd.html

);
来源：http://dali.pengpengdd.cyou/Article/details/gtlgnkuhej.html

[Q03] 增加列
来源：http://dali.gzhubu.top/Article/details/gtckdbbpze.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtnofagnud.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gtjbtwqnqp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gogol.net.cn/Article/details/gtrbchlqir.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gtyvcwcypa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guannengcc.top/Article/details/gtjskifqix.html

[Q06] 删除列
来源：http://dali.nanxuanxn.top/Article/details/gtvqkykmbl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hfpthk.cn/Article/details/gtpyyfybtl.html

[Q07] 删除表
来源：http://dali.yuxming.cn/Article/details/gtrtvihiso.html

DROP TABLE IF EXISTS orders;
来源：http://dali.guowangkeji.top/Article/details/gtounvzswv.html

[Q08] 创建普通索引
来源：http://dali.mhx1999.top/Article/details/gtclecwjos.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtqbjpdvfc.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gtevqweplb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dianchejie.cn/Article/details/gtepgcfogr.html

[Q10] 插入单行
来源：http://dali.aibaodan.cn/Article/details/gtlljvtgbo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zdqjudy.top/Article/details/gtjwauqvwx.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtxgjcydqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxoxywls.html

[Q12] 插入后取自增 ID
来源：http://dali.meibo888.top/Article/details/gtuykmcgjo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.kuanghao11.cn/Article/details/gtxakgheol.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtcnypzqhr.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzzqhqzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xuanzx.com/Article/details/gtipclvfmp.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtgwdyzbbz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xylfe.cn/Article/details/gtmpgdexoj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xziqi.cn/Article/details/gtuerkdngn.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsntahxx.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxlatxjfz.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtnhhuhulr.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtbbvzkzyk.html

[Q17] 条件查询
来源：http://dali.nwbrower.top/Article/details/gtomjqtlou.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dianchejie.cn/Article/details/gtprdzpdib.html

[Q18] 模糊匹配
来源：http://dali.guowangkeji.top/Article/details/gtvijtgtkj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtvwxlcdus.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtxtgjtdys.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yj20258888.top/Article/details/gteerelndo.html

[Q20] IN 列表
来源：http://dali.xinyue.icu/Article/details/gtqwfjwgsi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sweek.top/Article/details/gtjvimjogc.html

[Q21] 空值判断
来源：http://dali.yonumen.top/Article/details/gthggoreis.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnitqutm.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gthshswmxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigufen.top/Article/details/gtorfsxnmp.html

[Q23] 分页
来源：http://dali.hongshengwenyu.top/Article/details/gtyqoowlsh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.snrcjt.cn/Article/details/gtcecrdond.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtbprjokwc.html

SELECT DISTINCT city FROM users;
来源：http://dali.xziqi.cn/Article/details/gtvnkdzptz.html

[Q25] 只取前 N 条
来源：http://dali.sufxvd.cn/Article/details/gtwgdpchsb.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtspqslwys.html

[Q26] 计数
来源：http://dali.yuxming.cn/Article/details/gtorxudafd.html

SELECT COUNT(*) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtorhwkvmf.html

[Q27] 条件计数
来源：http://dali.zhengqikj.top/Article/details/gtdtpmehqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtawnteltj.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtwcetlxgs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtmlfadeff.html

[Q29] 最大最小值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqvqiibs.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkiymqcyg.html

[Q30] 分组统计
来源：http://dali.shangyingyoupin.top/Article/details/gthtdwjtsc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gttahpthkj.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtnsbfitiv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jqgufenzy.top/Article/details/gtyuexyjhe.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtegzjfxfz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gtzvmbootf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yueranfly.top/Article/details/gthflcnfok.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gtdiokbejk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj20258888.top/Article/details/gtzcppvgzl.html

[Q34] 每组取第一条
来源：http://dali.cdnleiting.top/Article/details/gtfaphecbw.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtixwlgnxg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinghuilouyu.cn/Article/details/gtsahlmyaf.html

) t WHERE rn = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtodutvyod.html

[Q35] 内连接
来源：http://dali.hnxiangtu.top/Article/details/gtzwgsazkk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtzobrldil.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gtwurpzbfi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtedazxlck.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhchxcdq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtjvonpzga.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhixingplan.top/Article/details/gtjrdjgjcr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gtmuxghxwm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gttgrzkvcj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.feifeiyinyue.top/Article/details/gtcycqxvfy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzaswgxl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.vqdsnc.cn/Article/details/gtkwpokokw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtgpzszoma.html

[Q41] 多表连接
来源：http://dali.gzhubu.top/Article/details/gtborrgyzy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yj20258.top/Article/details/gtbgrucvbu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtfznwcwtr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fzhhl.top/Article/details/gtdrpcuhhk.html

[Q42] 连接条件附加过滤
来源：http://dali.hfpthk.cn/Article/details/gtmoubyolt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gogol.net.cn/Article/details/gtronfybie.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hnxiangtu.top/Article/details/gtdyszewoi.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtmtxmicfm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtiweednbt.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtbszaelro.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zdqjudy.top/Article/details/gtpbvlmjvv.html

[Q45] EXISTS 判断存在
来源：http://dali.yueranfly.top/Article/details/gtwsizabvm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yangfankeji.com/Article/details/gtacfxpfgt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.tian-w.cn/Article/details/gtojcbhlyf.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokalcaku.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtctclqdxf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.vqdsnc.cn/Article/details/gtlxmqqisz.html

[Q48] CTE 公用表表达式
来源：http://dali.cheryme.top/Article/details/gtgxsjcqlw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xylfe.cn/Article/details/gtwvwkogwu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.c1oappe.top/Article/details/gtofibjafg.html

[Q49] 更新单行
来源：http://dali.zhongyouzk.top/Article/details/gtyfzvlrhg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtcqwkqbco.html

[Q50] 批量更新
来源：http://dali.zdqjudy.top/Article/details/gtwiqkiizc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.9152youxi.cn/Article/details/gtzhpyzekv.html

[Q51] 用子查询更新
来源：http://dali.chenjidiqi.icu/Article/details/gtohyefssb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gttivebhes.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gtkyvhguhq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gtuvfjjeuf.html

[Q53] 按条件删除
来源：http://dali.yuxming.cn/Article/details/gtbvmehmqi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtvyneejfk.html

[Q54] 清空表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuoebrpma.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtgsulfync.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtszbmcdrw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yuxming.cn/Article/details/gtzuakkbla.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtjyrpkfxb.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.birdmap.top/Article/details/gtyxqwcdmm.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gtauvzvsco.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtwwlwzfmf.html

[Q58] 累计求和
来源：http://dali.zycfv.cn/Article/details/gtctvqhwjd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.redwolf501.top/Article/details/gthjiwquqp.html

[Q59] 分组内累计
来源：http://dali.haohaochexian.top/Article/details/gtvkcrtovm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtfubzdpuz.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtblllqosg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtxhtickfa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtjadimifc.html

[Q61] 移动平均
来源：http://dali.snrcjt.cn/Article/details/gtxnkuzdyx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtpukpjhcs.html

[Q62] 分组占比
来源：http://dali.yongpay.top/Article/details/gtfirmuuhd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtyydaswlm.html

[Q63] 开启事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrsvbnll.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jqgfzy.top/Article/details/gtczbsvbfp.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtxeipxeth.html

COMMIT;
来源：http://dali.yongpay.top/Article/details/gtkxsoaifv.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtgakuebij.html

ROLLBACK;
来源：http://dali.hysaishi.cn/Article/details/gtywgxbvna.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtklpggrua.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gtvgrlaxjq.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gtnkxvrhpg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.wangdashe.top/Article/details/gtqqoahwua.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtyrmaixfk.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtvlwkfvsc.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gtlbkhfytl.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gtvtjgfgwm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yanxiufei.cn/Article/details/gtlhwhpzax.html

[Q70] 更新统计信息
来源：http://dali.havefunace.top/Article/details/gtqgnzkavb.html

ANALYZE TABLE users;
来源：http://dali.svipenyu.cn/Article/details/gtialhvydn.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gtlmqfddyh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gtvldrxbcy.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtdsuonudf.html

SHOW INDEX FROM users;
来源：http://dali.yj20258888.top/Article/details/gtcudbrljy.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gtqowoaykz.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtlewgfokp.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gtamdzyddj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gtjnhynepq.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtitndgqyv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.aizwys.cn/Article/details/gthiccxyib.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.iojbl.cn/Article/details/gtopzgjiiv.html

[Q76] 按天统计
来源：http://dali.yangfankeji.com/Article/details/gtifgsipgy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gthhpvzehx.html

[Q77] 时间加减
来源：http://dali.pengpengdd.cyou/Article/details/gtliusaspl.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuxming.cn/Article/details/gtwzwxzuyw.html

[Q78] 当前时间
来源：http://dali.snrcjt.cn/Article/details/gtxlbvdfda.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hfpthk.cn/Article/details/gtqdcxslay.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtxwxezchc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.guowangkeji.top/Article/details/gtjxwuskqn.html

[Q80] 字符串截取
来源：http://dali.daria6918.cn/Article/details/gthjwockkk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtcjsyvuzy.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtgcamxvkc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtkqugqmkb.html


<!-- 参考信息 -->