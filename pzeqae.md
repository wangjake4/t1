代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtgiwzrlbj.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtzkhsazbm.html

Ruby: Thread.new { f }
来源：http://dali.cqqwz.cn/Article/details/gtbopliaja.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtneugoavz.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gtjjbwwvnh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xziqi.cn/Article/details/gtfxxlmzui.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrtanzxw.html

JS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gttnyxgfug.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbcyemrs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtpafxfhar.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtlqpsaxso.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenlongwang.top/Article/details/gtetltgzvj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtlhnswrxt.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtltpirepo.html

Py:   with lock: shared += 1
来源：http://dali.shzxlz.cn/Article/details/gtkqiyanrn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtvpvbbvxj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gtvgadzbyg.html

TS:   // 同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gtdmmfxsji.html

Java: synchronized (this) { shared++; }
来源：http://dali.hysaishi.cn/Article/details/gtolvanltk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangshuangyany.cn/Article/details/gtofcncskl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtxockeeqa.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gttqwcrbik.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtgmbdziap.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gtyhfwjvys.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtvysyfptl.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gtzuubodxg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtsbjythdu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gtvrjknqsd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.0kj1m.cn/Article/details/gtswqtvzzy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtgahtqbia.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gtbwrpxdnb.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtfdjssadb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.redwolf501.top/Article/details/gttaptzjne.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hywenlv.cn/Article/details/gtwluowsiw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtpnjnorww.html

TS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtnyocexjf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gtrpyvfdzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sxryk.cn/Article/details/gtybdzlcpk.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gtnqoyejvh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hongshengwenyu.top/Article/details/gtedjwbkhi.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gtacfqtqkw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwuycbjj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gtvddfltzx.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtkjqrtphp.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtuzqucazm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtjwyhamrj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtpupmxrfz.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtszthtchi.html

C#:   Parallel.For
来源：http://dali.xinyue.icu/Article/details/gtvhjkfnyt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjlmpnjbv.html

P. 常用工具函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtprpulzqu.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnifszrcv.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtnbihjmej.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtkcvravqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsjqfkfd.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gthjvsyobz.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gtlgisvgmr.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gtoyfskmrg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtrpuzjukf.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtlzgbfuwn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtqiijumzl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtgdkqeqrt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtcytlcczb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtddfysghg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtmzfudvjp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtukzfjjan.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gtbfgsyzzb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gtandvygbs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gtculufgrp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtbiywxfkk.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gtptgntltr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gtdtavrpkb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gtqvivrrth.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkitekdal.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tianlin.xyz/Article/details/gteplmexos.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtfvsdbvqn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtqytrhncs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtxacggsqx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtlfgczmbi.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtehipmbpo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtsictfqas.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtbxhdzzpp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gtvimaltdn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtywiognba.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtxlhxzmwf.html

Go:   len(arr);  len(m)
来源：http://dali.hysaishi.cn/Article/details/gtfszdtize.html

Ruby: x.length;  x.size
来源：http://dali.yj20258.top/Article/details/gtnjqvmkys.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtrufzflei.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtarphzwtd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ydzc1.top/Article/details/gthsikalmv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpqfqqqm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ybcxt.top/Article/details/gtqwruvvjg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gturyhpsng.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtzjfhekfi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xziqi.cn/Article/details/gtqtqttwve.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtkifhehyn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yonumen.top/Article/details/gtnyzfrcsb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtnppnqtlo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yangfankeji.com/Article/details/gtrbpqneax.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gttbsijmeg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnqzz.top/Article/details/gtonwrjqhd.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gtpekojwqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtnszoidft.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtdsxzhjts.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gtktmerbqp.html

C#:   if (x is null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnymxtawk.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gttwwoqrwu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daria6918.cn/Article/details/gtuivoqows.html

PHP:  // 手写时间戳比较
来源：http://dali.hnxiangtu.top/Article/details/gtamvpfuqf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtqywmomcz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gtwxsjlnmw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gtwwowzzuc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtgivanojg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtwppcgcwu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmotcsrtw.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gtabnicjjp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gtnefvwmqx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ydzc1.top/Article/details/gtxtyzhjei.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gteioykdov.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtjkvokhmk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tanke756.top/Article/details/gtcrgzwxku.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgufenzy.top/Article/details/gtquwwqkts.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gtvixrbroi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.guowangkeji.top/Article/details/gttcrwumke.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtcbskuiao.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sufxvd.cn/Article/details/gthxipzfvv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtjrgvczxr.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtbrzpccrm.html

CREATE TABLE users (
来源：http://dali.zhixingplan.top/Article/details/gtzhrbxrqu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shuidangran.top/Article/details/gtusyskmox.html

name VARCHAR(50) NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtxmllxncc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gtoxsjqojt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.redwolf501.top/Article/details/gtsnyzgxaz.html

);
来源：http://dali.sxryk.cn/Article/details/gtegfocoxa.html

[Q02] 创建带外键的表
来源：http://dali.fzhhl.top/Article/details/gtejsfcabf.html

CREATE TABLE orders (
来源：http://dali.zhongyouzk.top/Article/details/gtrcaigvsy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtvftaqigb.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gtxthhikfb.html

amount DECIMAL(10, 2),
来源：http://dali.kuanghao11.cn/Article/details/gtbxbnlkcy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.gaohongyu789.top/Article/details/gtewbxqhqw.html

);
来源：http://dali.sweek.top/Article/details/gtlhdrrbno.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gthpokpbgy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cdnleiting.top/Article/details/gtjqkamkjn.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gtuuhqfrvi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zycfv.cn/Article/details/gtfyxjzuzx.html

[Q05] 重命名列
来源：http://dali.yj202588.top/Article/details/gtqcxtwped.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.feifeiyinyue.top/Article/details/gtowkhzwma.html

[Q06] 删除列
来源：http://dali.xylfe.cn/Article/details/gtzrsnotbw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.chenzaomai.com/Article/details/gtvtwcpghx.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gtxkixpalx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ybcxt.top/Article/details/gtulyrstfk.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtdhbwjutq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.ppjwa.cn/Article/details/gtdyzxbsdc.html

[Q09] 创建唯一索引
来源：http://dali.jinqigufen.top/Article/details/gtjyolnnph.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yonumen.top/Article/details/gtaggtedko.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gtqnveazht.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtjxmjzfcw.html

[Q11] 一次插入多行
来源：http://dali.snrcjt.cn/Article/details/gtjzhtcxel.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.chenzaomai.com/Article/details/gtphipazfe.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtrsmuqnyp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jlsjyb.cn/Article/details/gticrawzvb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xylfe.cn/Article/details/gtomsuqdyq.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtkmjxrqtw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ydzc1.top/Article/details/gtwgajstnz.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtijyrwexn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shangyingyoupin.top/Article/details/gtexqxavuc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gtbaiuacvw.html

[Q15] 查询全部
来源：http://dali.kuanghao11.cn/Article/details/gtpcntzcqs.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtsuqisgkg.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gtwrxwbvjr.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtjkzblgdn.html

[Q17] 条件查询
来源：http://dali.yuxming.cn/Article/details/gtdwkouvbb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gtjztxwlgf.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gtuahhychz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gtxknftzky.html

[Q19] 范围查询
来源：http://dali.chenzaomai.com/Article/details/gtdqzuhbal.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hnxiangtu.top/Article/details/gtnxwzdfyy.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtxqnfjdor.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuanzx.com/Article/details/gtjycqnwxe.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtkignoyxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhoulong.xyz/Article/details/gtdqgmnwov.html

[Q22] 排序
来源：http://dali.jianghu66.top/Article/details/gtrgfpwoav.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtynauwutz.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtitqegvfz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjskdkui.html

[Q24] 去重
来源：http://dali.zhengqikj.top/Article/details/gtuiwdkpxv.html

SELECT DISTINCT city FROM users;
来源：http://dali.hnqzz.top/Article/details/gtlvwwbyxa.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gthcecbkgg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.havefunace.top/Article/details/gtrqtevbko.html

[Q26] 计数
来源：http://dali.cucudq.cn/Article/details/gttlhuipfa.html

SELECT COUNT(*) FROM users;
来源：http://dali.yonumen.top/Article/details/gtvndxwnox.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtylrboxyr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sweek.top/Article/details/gtxqpuevun.html

[Q28] 求和与平均
来源：http://dali.ybcxt.top/Article/details/gteobkwxkv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtglbxppjg.html

[Q29] 最大最小值
来源：http://dali.xinyue.icu/Article/details/gthulqtzxj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtmmftqndc.html

[Q30] 分组统计
来源：http://dali.ehwqpu.com/Article/details/gtqrbmxavb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gtpbndmoqc.html

[Q31] 分组后过滤
来源：http://dali.aizwys.cn/Article/details/gtyfsjiubz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ivvv.top/Article/details/gtrkqtsjkx.html

[Q32] 分组拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gttgrptmat.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtlitqfesv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtzkdhflil.html

[Q33] 多列分组
来源：http://dali.zhengqikj.top/Article/details/gtilfnstvf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.tian-w.cn/Article/details/gthhhpcqxo.html

[Q34] 每组取第一条
来源：http://dali.yuanzhike.top/Article/details/gtubkwdjlx.html

SELECT * FROM (
来源：http://dali.zhongyouzk.top/Article/details/gthmhmpfny.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtarhteuhk.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gtihfgxtkr.html

[Q35] 内连接
来源：http://dali.xuanzx.com/Article/details/gtjigenfvm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtopmildxs.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gthymnjbtd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtsdlwrcxi.html

[Q37] 右连接
来源：http://dali.guowangkeji.top/Article/details/gtulhtpdld.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj202588.top/Article/details/gtdylrprpn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtamyeccjz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtjgugxsoh.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtukriwnbx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtjcscabhp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shangyingyoupin.top/Article/details/gtizjpwani.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cucudq.cn/Article/details/gthfhbgcvd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sweek.top/Article/details/gtlyrfhric.html

[Q41] 多表连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtppuoveyx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jinqigufen.top/Article/details/gttxlogfle.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gtgummrutz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hywenlv.cn/Article/details/gtvufqhskm.html

[Q42] 连接条件附加过滤
来源：http://dali.fzhhl.top/Article/details/gtrxevzzhc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258888.top/Article/details/gthkvhwsab.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtokwharvw.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gthqhcwoyv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.sysykeji.top/Article/details/gttsagnhem.html

[Q44] IN 子查询
来源：http://dali.iojbl.cn/Article/details/gtavohzyyo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gtghczpucf.html

[Q45] EXISTS 判断存在
来源：http://dali.vqdsnc.cn/Article/details/gtnglxnwhv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtsviwhwnd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtigzigsln.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.meibo888.top/Article/details/gtyzgojqhz.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtzddtddqh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yonumen.top/Article/details/gtmhipwkan.html

[Q48] CTE 公用表表达式
来源：http://dali.svipenyu.cn/Article/details/gtkidofvek.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.316326.xyz/Article/details/gtvjgzdyxl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujgmllvl.html

[Q49] 更新单行
来源：http://dali.meibo888.top/Article/details/gtuuljqqkl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.ivvv.top/Article/details/gtwyingeqq.html

[Q50] 批量更新
来源：http://dali.cucudq.cn/Article/details/gthovizvqu.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtojjihqbx.html

[Q51] 用子查询更新
来源：http://dali.nwbrower.top/Article/details/gteigdsqjp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.redwolf501.top/Article/details/gttnbstrbx.html

[Q52] 删除指定行
来源：http://dali.chenzaomai.com/Article/details/gtynhjijsg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jyoumei.cn/Article/details/gtvshpvgxi.html

[Q53] 按条件删除
来源：http://dali.xylfe.cn/Article/details/gtdwvrrkdc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtixtnevte.html

[Q54] 清空表
来源：http://dali.cucudq.cn/Article/details/gtrikjvtiz.html

TRUNCATE TABLE logs;
来源：http://dali.iojbl.cn/Article/details/gtkjzwdxee.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtiqvebkon.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gtphffmiet.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbunoufld.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gtwjhhhfhg.html

[Q57] 行号
来源：http://dali.chenlongwang.top/Article/details/gthlxwvrxy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gttseuedwn.html

[Q58] 累计求和
来源：http://dali.0kj1m.cn/Article/details/gtvwcgbxhz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.mhx1999.top/Article/details/gttxkctcdd.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtihnngkqf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtydlluavu.html

[Q60] 取上一行 / 下一行
来源：http://dali.redwolf501.top/Article/details/gtlmfhdprg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hnqzz.top/Article/details/gtmgbsfijg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xziqi.cn/Article/details/gtkligbilu.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtulpjipvb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtukcvmpce.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtqwoqlmwe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gthtxvmept.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtrmnctxkm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gttxqowoeh.html

[Q64] 提交事务
来源：http://dali.hysaishi.cn/Article/details/gtzxwixvud.html

COMMIT;
来源：http://dali.yanxiufei.cn/Article/details/gttjwggwyg.html

[Q65] 回滚事务
来源：http://dali.wangdashe.top/Article/details/gtvdzuysac.html

ROLLBACK;
来源：http://dali.jqgufenzy.top/Article/details/gtglsiqlan.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gtxvrobmro.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gthbahbpww.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gtneqwleig.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhengqikj.top/Article/details/gtbuvhvlce.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gtqyvgpmup.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gtxdlkbtnc.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtwnerzmaf.html

[Q69] 查看执行计划
来源：http://dali.yongpay.top/Article/details/gtmqafwbzi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtswjfkxoy.html

[Q70] 更新统计信息
来源：http://dali.sweek.top/Article/details/gtrbewwctu.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzjdptnm.html

[Q71] 查看建表语句
来源：http://dali.wangdashe.top/Article/details/gtmxdqhnrk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gtnzwiqzue.html

[Q72] 查看索引
来源：http://dali.sxryk.cn/Article/details/gtdilbrdhr.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtneqvzkje.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtvlnmsnmx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuxming.cn/Article/details/gtcklguqid.html

[Q74] 强制使用索引
来源：http://dali.nanxuanxn.top/Article/details/gtmbnjlcgd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gtspylrfbc.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtndskwcay.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gtgdtjdqth.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhiwuduotai.top/Article/details/gtesijxhmh.html


<!-- 参考信息 -->