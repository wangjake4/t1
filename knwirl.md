代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gtojxkjoln.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbccgdyra.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gthpcwydxn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gtjrzyipxm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gtfubtllop.html

[O03] 加锁保护共享数据
来源：http://dali.xuetiantiany.cn/Article/details/gtyvmppedn.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjkatszv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gotoacloud.top/Article/details/gttzljrqpf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtcjtzxfju.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtrhgaambp.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaiakfcqg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnxiangtu.top/Article/details/gtevifbrmf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtblntmuut.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdwmsdpwl.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtglgtvdbv.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtbxcidbkr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gtxiyejifg.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtttdvidhf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gttowalfgl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gtibnhshhq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtfcqqubmh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sufxvd.cn/Article/details/gtytrbnazm.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwnwpzmzu.html

[O05] 并发执行并等待全部完成
来源：http://dali.snrcjt.cn/Article/details/gtbcueywwp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtxarkcqmy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangtech.top/Article/details/gtasyaocss.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtyzblekxb.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtrrojlcku.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtczpqgita.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gtxejsaczh.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtwrsmkpdg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gtipiohyzh.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gtljcudopa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlxtvbsp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtombevpko.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtvkhqroxq.html

TS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtwpazyrio.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtpojckqzy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowqhlglw.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtkzvezzbd.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gtbxkfxqda.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgxufprot.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gtjbqmmjwj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthvyldvjg.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gturfjcevv.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gtlzatqogk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtoswudcpw.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtmsjiwwrk.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtrbtzfmca.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtjyzxxrzr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hammf.cn/Article/details/gthmpeoido.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtnsdzusxg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gtidojbsjk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtnvuseixv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtvcxfdpeo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gtpaxtqtwr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtgjfwhjdc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtdcxnyjin.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gthahummyl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dashuyun.cn/Article/details/gtoqrqtnvk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.redwolf501.top/Article/details/gtkoypvtnk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtfrkqnbqh.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtcscfwohy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gtcdqkrnmm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtytmpgmiz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdqicivu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtphrfimgx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gttstrmbri.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtbnpismku.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.0kj1m.cn/Article/details/gtlmxjpvla.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gtrimfizjy.html

[P04] 求长度
来源：http://dali.pycfn.com/Article/details/gtxafnvyqk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvauoqgwl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtxmyaylee.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daria6918.cn/Article/details/gtgwhaubfz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtrcdwdftb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtucpnjqtq.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gtnjswycpo.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtwgtretjm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtvfahlkmj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtconcuutc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gtchbmxvgc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gtehjnkfeb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtezhwyxue.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gtmjteibiw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuanzhike.top/Article/details/gtsugbduyl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgzpyipi.html

Ruby: a == b
来源：http://dali.gogol.net.cn/Article/details/gtdazersxm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gtdexgxwcb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yueranfly.top/Article/details/gtitktbctd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtbspgvrna.html

PHP:  if (empty($x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtvauuysyd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aibaodan.cn/Article/details/gtuiiveswr.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjlusrxex.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.meibo888.top/Article/details/gtvgvlmyhy.html

Go:   if x == nil {}
来源：http://dali.aizwys.cn/Article/details/gtfdfcqsje.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gtwilovtei.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtkzazquqn.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtgttolhbb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtvkeqzrjq.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtgftsaaiw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gtfvsyehdh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtqxirdsve.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtrecimpdj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ybcxt.top/Article/details/gtuqfzowqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zdqjudy.top/Article/details/gtfrkmzdnt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtbbrtnsbx.html

[P08] 处理浮点精度问题
来源：http://dali.shzxlz.cn/Article/details/gtizivbrvc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.316326.xyz/Article/details/gtigcpzuqq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sxryk.cn/Article/details/gtfqgdeuqc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hfpthk.cn/Article/details/gttkcelsam.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtyzqgokwg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtlvgzrzwg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.andypj.xyz/Article/details/gtsounppaf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gthbxmmwnw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtvfmkvkxy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtxuwhlbdi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtmaneunlv.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtasloxdxl.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gtzvtvvcpk.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gtabnvexlg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtvevudzus.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtksulhhid.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yonumen.top/Article/details/gtflxqxncm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtjtvnyisx.html

);
来源：http://dali.chenzaomai.com/Article/details/gtuwvlmpqm.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtrsvgkwwu.html

CREATE TABLE orders (
来源：http://dali.aizwys.cn/Article/details/gtpruwomeg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtoqtvyrnk.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtfjhvyktz.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gtyerlcgle.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.redwolf501.top/Article/details/gtfdblekgm.html

);
来源：http://dali.yj20258888.top/Article/details/gtibbknyza.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtnwxcjtqi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtnfkomwdr.html

[Q04] 修改列类型
来源：http://dali.birdmap.top/Article/details/gttbwqfhwc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmdmerah.html

[Q05] 重命名列
来源：http://dali.yuanzhike.top/Article/details/gtkfgsqnac.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtfylmupyc.html

[Q06] 删除列
来源：http://dali.redwolf501.top/Article/details/gtinxoixyn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gtdhbcokly.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtyxcyufjo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.mhx1999.top/Article/details/gtdagrklfq.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gtbrpgygjb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jiagoushi.top/Article/details/gtplmpoiqo.html

[Q09] 创建唯一索引
来源：http://dali.cheryme.top/Article/details/gtclahbkqb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gtcvrsimdh.html

[Q10] 插入单行
来源：http://dali.snrcjt.cn/Article/details/gtwcuvydgu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyutartgy.html

[Q11] 一次插入多行
来源：http://dali.mhx1999.top/Article/details/gtisrxbrww.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.guannengcc.top/Article/details/gtbsqvvfqf.html

[Q12] 插入后取自增 ID
来源：http://dali.xziqi.cn/Article/details/gtvelcjich.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ppjwa.cn/Article/details/gtgnixpzfb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.gotoacloud.top/Article/details/gtjilmqyhn.html

[Q13] 忽略重复插入
来源：http://dali.jlsjyb.cn/Article/details/gtiwnkqdac.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gtpafwtqee.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gttpbzevdw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jiagoushi.top/Article/details/gtcrtgcpcb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yuanzhike.top/Article/details/gttgvoxaih.html

[Q15] 查询全部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzesljyzr.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzjnybjhy.html

[Q16] 查询指定列
来源：http://dali.cucudq.cn/Article/details/gtuqsaapos.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gtnailrxtp.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gtpreiypni.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.9152youxi.cn/Article/details/gtmvlrhbed.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtgfwiutbd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gtqpsjvslv.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtddyznclt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nwbrower.top/Article/details/gtgpcetvfn.html

[Q20] IN 列表
来源：http://dali.ydzc1.top/Article/details/gtjjtrptsb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxinkj.top/Article/details/gtkzykmzfq.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtkxfmfarw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtbakkxhbq.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtnduyyqbo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.mhx1999.top/Article/details/gtsmbpmlhr.html

[Q23] 分页
来源：http://dali.andypj.xyz/Article/details/gtsfinmmcc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgufenzy.top/Article/details/gttdawxzlf.html

[Q24] 去重
来源：http://dali.chenlongwang.top/Article/details/gtlbysdiau.html

SELECT DISTINCT city FROM users;
来源：http://dali.sweek.top/Article/details/gtydkgqufs.html

[Q25] 只取前 N 条
来源：http://dali.zhongyouzk.top/Article/details/gtxvrrshpv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.bjfxy.top/Article/details/gttcxkcxqa.html

[Q26] 计数
来源：http://dali.zhoulong.xyz/Article/details/gtodfgwobs.html

SELECT COUNT(*) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtkfchbwln.html

[Q27] 条件计数
来源：http://dali.gzhubu.top/Article/details/gtawwjtfxw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gtmatinyly.html

[Q28] 求和与平均
来源：http://dali.gzhubu.top/Article/details/gtpmvczxib.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gttlaytdgt.html

[Q29] 最大最小值
来源：http://dali.yuanzhike.top/Article/details/gtdfanxiog.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtrldyrqtz.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gtlncdealu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gtsphpiwfw.html

[Q31] 分组后过滤
来源：http://dali.kuanghao11.cn/Article/details/gttbnsrimz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xziqi.cn/Article/details/gtomxnryxh.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtivsfloji.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfzwnwpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cashguo.top/Article/details/gtxongmlvp.html

[Q33] 多列分组
来源：http://dali.smart0.xyz/Article/details/gtbjuwxxhq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hysaishi.cn/Article/details/gtadpfuexb.html

[Q34] 每组取第一条
来源：http://dali.hongshengwenyu.top/Article/details/gtulmgcqey.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtnrkiiths.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cucudq.cn/Article/details/gtodcwbnbz.html

) t WHERE rn = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtdjomdols.html

[Q35] 内连接
来源：http://dali.zhixingplan.top/Article/details/gtxejjvwwq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gthfcvvxiz.html

[Q36] 左连接
来源：http://dali.sysykeji.top/Article/details/gtmlhhvgor.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtyygwuyco.html

[Q37] 右连接
来源：http://dali.jianghu66.top/Article/details/gtwfymlugi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gttmestnbr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtbgjkgyag.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yongpay.top/Article/details/gtpwxelnup.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gtwnransqe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtaknklzwa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuaakbpgx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gthuvdphir.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.jianghu66.top/Article/details/gtswdrzlvr.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtsidivqax.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.fzhhl.top/Article/details/gteuakgulw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shanyushiyangtech.top/Article/details/gttjzcufwq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtugzavlem.html

[Q42] 连接条件附加过滤
来源：http://dali.yueranfly.top/Article/details/gtnuedqfcg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtsulhiecv.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj20258.top/Article/details/gtccluckpj.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtquszohea.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xziqi.cn/Article/details/gtcfzzfkbr.html

[Q44] IN 子查询
来源：http://dali.yonumen.top/Article/details/gtrgwdtrgf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.daria6918.cn/Article/details/gtcpunbelg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhongyouzk.top/Article/details/gtikixaihh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtnxzvsoks.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtiojofgwp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtawjxvvkd.html

[Q47] 与平均值比较
来源：http://dali.quarkkingdee.top/Article/details/gtwvygnvpa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gtmrhjcvxw.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gtniaoxudq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigxjpnmb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxuanxn.top/Article/details/gtbczlzdgk.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtfywbpvvk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtfetjktml.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gtsfltftrn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gtndksjmbs.html

[Q51] 用子查询更新
来源：http://dali.fzhhl.top/Article/details/gtvrfgeyka.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtpvcmnlsl.html

[Q52] 删除指定行
来源：http://dali.vqdsnc.cn/Article/details/gtrxdzbmvk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xylfe.cn/Article/details/gtiivihhhv.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtdbapchpy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtjdsxqxhe.html

[Q54] 清空表
来源：http://dali.pengpengdd.cyou/Article/details/gtcyendtya.html

TRUNCATE TABLE logs;
来源：http://dali.quarkkingdee.top/Article/details/gtneizrxnn.html

[Q55] 排名（并列占位）
来源：http://dali.aizwys.cn/Article/details/gtfsgpvncp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj20258888.top/Article/details/gttwlyvsdd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yueranfly.top/Article/details/gtftyyrviw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtfjdzokcv.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gtvnyhndlr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtxayguolj.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gthwuzckwq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtbwjfhtrq.html

[Q59] 分组内累计
来源：http://dali.gzhubu.top/Article/details/gtxfttltrn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cheryme.top/Article/details/gtresvnfzd.html

[Q60] 取上一行 / 下一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjuuxiam.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yanxiufei.cn/Article/details/gtrugrxkii.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtunwbtjaq.html

[Q61] 移动平均
来源：http://dali.sufxvd.cn/Article/details/gtlbpwnjuw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtjfpivati.html

[Q62] 分组占比
来源：http://dali.wangdashe.top/Article/details/gtptpvrrqy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gttzypgdrj.html

[Q63] 开启事务
来源：http://dali.yj20258888.top/Article/details/gtzzpadxtt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hywenlv.cn/Article/details/gtobneaagm.html

[Q64] 提交事务
来源：http://dali.bjfxy.top/Article/details/gtvdbitulz.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtxvzmcrcm.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtmwvynrsm.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtdggzvuhn.html

[Q66] 行锁查询
来源：http://dali.tanke756.top/Article/details/gtwrudtjdy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gtwzwcwgoz.html

[Q67] 设置隔离级别
来源：http://dali.fzhhl.top/Article/details/gtkokvloyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gtawidkjhw.html

[Q68] 保存点
来源：http://dali.cheryme.top/Article/details/gtzfiiwsad.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtlcoodexq.html

ROLLBACK TO sp1;
来源：http://dali.xylfe.cn/Article/details/gtdawrpgqo.html

[Q69] 查看执行计划
来源：http://dali.smart0.xyz/Article/details/gtqyswfysj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gthmtiwdfz.html

[Q70] 更新统计信息
来源：http://dali.yvedp.cn/Article/details/gtyakbtudm.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gtakakfpko.html

[Q71] 查看建表语句
来源：http://dali.aizwys.cn/Article/details/gtcuhmtxhl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gtkfggzimw.html

[Q72] 查看索引
来源：http://dali.cashguo.top/Article/details/gtvfmykydo.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gtmwtdwnvs.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtripkrdeo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtglwcxhbn.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtfooxupge.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.smart0.xyz/Article/details/gtdyagcell.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtkpjpygoo.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gtzjmjthpo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yvedp.cn/Article/details/gtimbgnveq.html

[Q76] 按天统计
来源：http://dali.wangshuangyany.cn/Article/details/gtjdzbyadm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jiagoushi.top/Article/details/gtvufxcxvy.html

[Q77] 时间加减
来源：http://dali.shangyingyoupin.top/Article/details/gtuzxwkxpp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gtbncgtyhj.html

[Q78] 当前时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvqdgesd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhengqikj.top/Article/details/gtwpsebyxn.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtevtfexco.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtrxdfhfun.html


<!-- 参考信息 -->