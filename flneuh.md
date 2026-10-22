代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtkjtxhmpc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenjidiqi.icu/Article/details/gtkdvkwsjt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtdytcxelb.html

TS:   // 同 JS
来源：http://dali.shzxlz.cn/Article/details/gtmctinldf.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtqzgfocic.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtlgbbzpof.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gtjaucbddd.html

C#:   Task.Run(() => F());
来源：http://dali.feifeiyinyue.top/Article/details/gtveeonins.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtqoybkklk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigfzy.top/Article/details/gthmrsfior.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtfpmnhofw.html

JS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gtftdvetki.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gtqmdiamuh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbqizkhx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gzhubu.top/Article/details/gtmqmawsku.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gtfxvvyhyz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtbhudxkqt.html

[O03] 加锁保护共享数据
来源：http://dali.nanxuanxn.top/Article/details/gtqyxmrxid.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtkxeijwei.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xuetiantiany.cn/Article/details/gtwzioejta.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yuxming.cn/Article/details/gthrfuoxlh.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtejvtuavc.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtxjxpyqcl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gtzwgcckpa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gtzweehfvs.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gtkwicfejf.html

[O04] 定义异步函数并等待
来源：http://dali.birdmap.top/Article/details/gtgndxfvki.html

Py:   async def f():⏎    await g()
来源：http://dali.tianlin.xyz/Article/details/gtsiwehhte.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtfyswameh.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpcaibzeh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtaoswxgjk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gtihyesdon.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtiekmjbrg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gtmdoibptb.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtiriofmiw.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtktixnxaj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtbbsvzmeh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpjyoivr.html

JS:   await Promise.all(tasks)
来源：http://dali.guannengcc.top/Article/details/gtwphdcqwp.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtebikiwae.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtsrmgxzva.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gttxyejvhl.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtgdiytlfv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gtjguwbmvp.html

[O06] 使用进程池
来源：http://dali.ivvv.top/Article/details/gtnahdpmld.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtyeguprll.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtilcyvabm.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtnuvuvsov.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtiwzcrqgp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gtlvmujkgp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gtpugzcfen.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gtyuzllnax.html

C#:   Parallel.For
来源：http://dali.iojbl.cn/Article/details/gtdssoshul.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxvzqvoxm.html

P. 常用工具函数
来源：http://dali.sxryk.cn/Article/details/gtcfnontuo.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtucoxjumv.html

[P01] 生成 UUID
来源：http://dali.xinyue.icu/Article/details/gtwvfaqfme.html

Py:   str(uuid.uuid4())
来源：http://dali.guowangkeji.top/Article/details/gtxgynjrbc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gtlvmuqpcx.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtbfpachdt.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtegzruilx.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslkcmadv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtcycacpqy.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258.top/Article/details/gteziggxhg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daxiang520.top/Article/details/gtigftcwvr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtnupopgbc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzeoeyziw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yueranfly.top/Article/details/gtljwdboui.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtxubemqla.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gtazdfqziw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtcmpcqyow.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gtomthdnls.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gtlaigjohz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenlongwang.top/Article/details/gtcadbprev.html

[P03] 生成短随机字符串
来源：http://dali.yuxming.cn/Article/details/gttrrtskxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtmnaekido.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtxmmlocuh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhncqapm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtgouyuxkk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtpswzvrxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtqjdblfsp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxinkj.top/Article/details/gtoumpolan.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtctdiwacq.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gtxwovbbrv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gtbvnlagrt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtgufieyrq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtvmtjgkzc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtflaulorf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtrpjkhtow.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtcniuxdui.html

Ruby: x.length;  x.size
来源：http://dali.wangshuangyany.cn/Article/details/gtaowhzlva.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtxessckdh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gtgggrhoqz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daria6918.cn/Article/details/gtoikrtcnb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gtjnpeflgq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtlvsgbqfe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jianghu66.top/Article/details/gtsyxgxyqg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtqkodxcvt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtujpujgyn.html

Ruby: a == b
来源：http://dali.iojbl.cn/Article/details/gtzeftizkj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtmkqqghoa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtmvzzocbc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.feifeiyinyue.top/Article/details/gtcschshmu.html

PHP:  if (empty($x)) {}
来源：http://dali.ydzc1.top/Article/details/gtcyagkeag.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqgkvfka.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwbmsrqyd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtundfedwq.html

Go:   if x == nil {}
来源：http://dali.snrcjt.cn/Article/details/gtholtrdeo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtdovpzlyy.html

C#:   if (x is null) {}
来源：http://dali.9152youxi.cn/Article/details/gtukswbmdr.html

[P07] 防抖与节流
来源：http://dali.quarkkingdee.top/Article/details/gtrgzdaomz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shzxlz.cn/Article/details/gtpakchdii.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtxojffnak.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtpdmskofq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gtqbrupkdd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtgedndklv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtvuzeailp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenzaomai.com/Article/details/gtfslhyhnw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hnxiangtu.top/Article/details/gtjuokaiil.html

[P08] 处理浮点精度问题
来源：http://dali.guannengcc.top/Article/details/gtllyxmqrn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.guannengcc.top/Article/details/gtzimdmrbr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtlzxlxofq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.haohaochexian.top/Article/details/gtnuzccxul.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gtewrltmdk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtndarwezq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gtvbldvnyh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.iojbl.cn/Article/details/gtpqzvcaij.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenjidiqi.icu/Article/details/gtnwiidtap.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtdvbgzjbl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiiwcoxp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtmnzsoguu.html

[Q01] 创建表
来源：http://dali.cucudq.cn/Article/details/gtvqhoagxy.html

CREATE TABLE users (
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulfyzrmg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jyoumei.cn/Article/details/gtkqnaipqa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shangyingyoupin.top/Article/details/gtrpehnple.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtouvemhvp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtipukvkzy.html

);
来源：http://dali.bjfxy.top/Article/details/gtuqwbaqel.html

[Q02] 创建带外键的表
来源：http://dali.yj20258888.top/Article/details/gtbijmsswi.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gtjbrmbbtv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtavsldwtn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtosdakllx.html

amount DECIMAL(10, 2),
来源：http://dali.dashuyun.cn/Article/details/gtxgswenms.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtsydwlcgx.html

);
来源：http://dali.fzhhl.top/Article/details/gtdxeswtdn.html

[Q03] 增加列
来源：http://dali.hywenlv.cn/Article/details/gtafuqrgey.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.meibo888.top/Article/details/gteksvvgpy.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gtwzxgqxqf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtyzpkciyu.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtvhgwuiox.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.smart0.xyz/Article/details/gtnuzxjkyi.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gtmptrcxim.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yuxming.cn/Article/details/gtaaztvpgx.html

[Q07] 删除表
来源：http://dali.zhongyouzk.top/Article/details/gtguzttyae.html

DROP TABLE IF EXISTS orders;
来源：http://dali.nwbrower.top/Article/details/gtxcnebdil.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gtfyxvoisp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtueehriku.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtslgbamny.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.quarkkingdee.top/Article/details/gtmeizvkil.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gtnqcchhvv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.fzhhl.top/Article/details/gtktxwxrag.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtbhcmiynx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gtppozqlzh.html

[Q12] 插入后取自增 ID
来源：http://dali.yanxiufei.cn/Article/details/gtechibxwx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yuxming.cn/Article/details/gtltxtvofa.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.9152youxi.cn/Article/details/gtseocykdd.html

[Q13] 忽略重复插入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwrrprrm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gtktmibblz.html

[Q14] 存在则更新（upsert）
来源：http://dali.dashuyun.cn/Article/details/gtkuiunxnt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ehwqpu.com/Article/details/gtdqkrcxtx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.dianchejie.cn/Article/details/gtewswonmo.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpufrdrcz.html

SELECT * FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqcvbbcoj.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gtcmxrhfcr.html

SELECT id, name FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmpphpso.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtqtviapzw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ppjwa.cn/Article/details/gtofuhkspn.html

[Q18] 模糊匹配
来源：http://dali.daxiang520.top/Article/details/gtuvmhcipz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gthkjzyrli.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtzlizlbfd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.havefunace.top/Article/details/gtormjznox.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gtnsqenaem.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ydzc1.top/Article/details/gtqbwlkcel.html

[Q21] 空值判断
来源：http://dali.yanxiufei.cn/Article/details/gtcjjsktyv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jqgufenzy.top/Article/details/gtxmnmifeh.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gthankcpji.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gtoxmjglcz.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtiogossfv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.gzhubu.top/Article/details/gtvzezwenm.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtsemmlhoc.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoenenlag.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtomlflmqq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hfpthk.cn/Article/details/gtjyjlseab.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtgcwncbem.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtyrymbnmv.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gtrpwqcbve.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.meibo888.top/Article/details/gtrinrcpqz.html

[Q28] 求和与平均
来源：http://dali.hysaishi.cn/Article/details/gttqnntjhs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtchgzbuno.html

[Q29] 最大最小值
来源：http://dali.havefunace.top/Article/details/gtrxvwexwj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtpmadalkk.html

[Q30] 分组统计
来源：http://dali.nanxinkj.top/Article/details/gtbyzplwir.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.wangdashe.top/Article/details/gtygvvifqf.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gtsbnivhmo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.daria6918.cn/Article/details/gtvpqltejf.html

[Q32] 分组拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtuxtfeghm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtteyvyyxt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.feifeiyinyue.top/Article/details/gtbpsusfko.html

[Q33] 多列分组
来源：http://dali.daxiang520.top/Article/details/gteunqmkub.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtvhdaodgs.html

[Q34] 每组取第一条
来源：http://dali.guowangkeji.top/Article/details/gtuhvogxxl.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtlrjfhfqs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ybcxt.top/Article/details/gtkqizpgxy.html

) t WHERE rn = 1;
来源：http://dali.yongpay.top/Article/details/gtfxiochxm.html

[Q35] 内连接
来源：http://dali.9152youxi.cn/Article/details/gttymsjvug.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuetiantiany.cn/Article/details/gtcwgqedjz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gtbayruffo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtemnghtme.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gtwzogachp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cheryme.top/Article/details/gtsopfvwwd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shzxlz.cn/Article/details/gtipdutmit.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxgrlmzh.html

[Q39] 自连接（查上下级）
来源：http://dali.xylfe.cn/Article/details/gtprohhuwx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yongpay.top/Article/details/gtbvtosbfi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jqgfzy.top/Article/details/gtgnfooxbu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gthznpftls.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtlzcipvxr.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gttrwfjdhp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.redwolf501.top/Article/details/gtqmnrpzeg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gttdszkhdj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jlsjyb.cn/Article/details/gtfoufhcco.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtpngnjkwa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtripvuxwp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cashguo.top/Article/details/gticwvggtw.html

[Q43] 标量子查询
来源：http://dali.quarkkingdee.top/Article/details/gticdceyvi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tanke756.top/Article/details/gtwytubwts.html

[Q44] IN 子查询
来源：http://dali.kuanghao11.cn/Article/details/gttxkkwbnm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xylfe.cn/Article/details/gtagxltwqh.html

[Q45] EXISTS 判断存在
来源：http://dali.hongshengwenyu.top/Article/details/gtclleavoo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnpliydw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yangfankeji.com/Article/details/gtiavciwfm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gtpjitrwda.html

[Q47] 与平均值比较
来源：http://dali.jiagoushi.top/Article/details/gtwxcktalc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtazbvlrog.html

[Q48] CTE 公用表表达式
来源：http://dali.chenzaomai.com/Article/details/gtnkqjgnon.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmibulkcj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtxtvxanjk.html

[Q49] 更新单行
来源：http://dali.hongshengwenyu.top/Article/details/gtyyjbsudk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtcbrkomev.html

[Q50] 批量更新
来源：http://dali.pycfn.com/Article/details/gtlpwldgig.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtluqvjejs.html

[Q51] 用子查询更新
来源：http://dali.9152youxi.cn/Article/details/gthwoomjft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.c1oappe.top/Article/details/gtjekwnmmu.html

[Q52] 删除指定行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkfhcpdgt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dianchejie.cn/Article/details/gtcnanjxbg.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtxgpghxvs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.0kj1m.cn/Article/details/gtgfoinjjy.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gtcxrkodud.html

TRUNCATE TABLE logs;
来源：http://dali.shangyingyoupin.top/Article/details/gtbxexhfht.html

[Q55] 排名（并列占位）
来源：http://dali.yj202588.top/Article/details/gtcaizczbc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtclpmvqnr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtrdvkgqle.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtiyjdgllw.html

[Q57] 行号
来源：http://dali.gogol.net.cn/Article/details/gtymteqkxr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnkznbzu.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtcxdigzhp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj20258.top/Article/details/gtatutsfca.html

[Q59] 分组内累计
来源：http://dali.316326.xyz/Article/details/gtnwxgslhw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtaxjcsbci.html

[Q60] 取上一行 / 下一行
来源：http://dali.snrcjt.cn/Article/details/gtnmdbxzgf.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtsivtjmel.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtmqqxitre.html

[Q61] 移动平均
来源：http://dali.yongpay.top/Article/details/gtyeeebgfm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gtaygftank.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtbfpybjnr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtyoiqyame.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtzarqogsa.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhongyouzk.top/Article/details/gtueztocen.html

[Q64] 提交事务
来源：http://dali.sysykeji.top/Article/details/gtqtorncek.html

COMMIT;
来源：http://dali.jinqigufen.top/Article/details/gtthbjjtvs.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtfhnwfzal.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhzxezzc.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtayxpywdz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ehwqpu.com/Article/details/gteqtcomsp.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtmblpaxea.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtoiutomec.html

[Q68] 保存点
来源：http://dali.aizwys.cn/Article/details/gtgscssypg.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtojabqvuh.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtgdxanjmw.html

[Q69] 查看执行计划
来源：http://dali.cqqwz.cn/Article/details/gtsocbuifo.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gtuukwrxfo.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtrvpckgbm.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtzgnvfwph.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gttneltkcy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigufen.top/Article/details/gtvgynsrxu.html

[Q72] 查看索引
来源：http://dali.pengpengdd.cyou/Article/details/gtirxwksvs.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtrltgqtkm.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtdrrhttfu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtjictmyvl.html

[Q74] 强制使用索引
来源：http://dali.sxryk.cn/Article/details/gtarrlcrpf.html


<!-- 参考信息 -->