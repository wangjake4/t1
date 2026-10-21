代发 wailian999

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtdlhwqcnj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.andypj.xyz/Article/details/gtmskivehf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtdzuxpqct.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtomkscauq.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gtbdynisig.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gtnjqrablw.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtheffqvqb.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtfyplmzwf.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtrjdinnjs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgufenzy.top/Article/details/gtvequjewa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yanxiufei.cn/Article/details/gtyvtocgtp.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtojejwceg.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtmawjkqcr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtjtoxgtxc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtlbsrvcwo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.bjfxy.top/Article/details/gtuiasouqd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gteyzvnelh.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gtuqvmwmyh.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gthqfqpsrl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gtomcnuokf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gthuaehhoi.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtwnifoudv.html

Java: synchronized (this) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtvpvmaeng.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yonumen.top/Article/details/gtytucxctt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jlsjyb.cn/Article/details/gttlgbxlnq.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtnnqlzwxd.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigfzy.top/Article/details/gtjfoylbnj.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtttlismiv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtozipvwdw.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gtmdgjwbur.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sweek.top/Article/details/gtuwvppjkp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtwhvfrvop.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yanxiufei.cn/Article/details/gtxunnhlmj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.kuanghao11.cn/Article/details/gtusmlyest.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtraujwont.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxrplwek.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hfpthk.cn/Article/details/gtzrmkceoi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtajysgejt.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gttatutkvp.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtobxoittf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jiagoushi.top/Article/details/gthyeypggw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gtanybybei.html

Ruby: threads.map(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtwrqispth.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fzhhl.top/Article/details/gtylbigqof.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtuhodzgrj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gtjdjbzabd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtobymmdgq.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtyuwkhysi.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtepvnxkgo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenzaomai.com/Article/details/gtoajtswyd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gtqnjfxfkq.html

Ruby: // fork 块
来源：http://dali.c1oappe.top/Article/details/gtryuezecz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtbmdjhmwi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnpidtklm.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtckwennvm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkhuhohmg.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtikcqpqzu.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gtmxabmtih.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtovbqvrce.html

JS:   crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtrozdmmmv.html

TS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtebqyuiqb.html

Java: UUID.randomUUID().toString()
来源：http://dali.sysykeji.top/Article/details/gtykiezboe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjwkwiry.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtdjvlmbjz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtmrluclut.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtvfyczish.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gtkdeijtpw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtdmcknmnk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtrzoesmpb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shzxlz.cn/Article/details/gttfctkgwf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtblhnzbln.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gtiyhyhgtp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gttyvmzczk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuanzx.com/Article/details/gtvwxizibi.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtvrixtgwd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtjrmfrbjn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtwxnxbrez.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtxrbqrzey.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtdmuoyeuf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gtwaeqviwg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gtikypaztu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gtmdfyifyp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yanxiufei.cn/Article/details/gtnptsbnjt.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtymlctznf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ppjwa.cn/Article/details/gtbynflzjg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtowsyuqmg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenzaomai.com/Article/details/gthahkgxiw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtjobixxpu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gtsyldbcep.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtwduolkpm.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gtmpmktmvb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtbxhjfusb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.meibo888.top/Article/details/gtkizzikzj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gtayvnvsvz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gthjpspbjc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtczuitemo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gttzaogcnw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtgtriaiqx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwuvhvza.html

Ruby: a == b
来源：http://dali.dashuyun.cn/Article/details/gtayihzlqe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gttzvaitcd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gttyjthrpu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinqigfzy.top/Article/details/gteiunqgko.html

PHP:  if (empty($x)) {}
来源：http://dali.sysykeji.top/Article/details/gtisgqmyah.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gtmtjjstte.html

TS:   if (x == null) {}
来源：http://dali.yueranfly.top/Article/details/gtgelaxweb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gtqxgnsvtk.html

Go:   if x == nil {}
来源：http://dali.bjfxy.top/Article/details/gtrnjikqmt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtizhhuhsa.html

C#:   if (x is null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxjgqzryi.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtulnuhvlb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gtvlxuolba.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gtthcupogr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtruhtsgmb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtzwrftfyi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtxlicucul.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenzaomai.com/Article/details/gtbplonbvy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtdrmenjxb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aibaodan.cn/Article/details/gtirbcwmwo.html

[P08] 处理浮点精度问题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbnsngrs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.meibo888.top/Article/details/gttcvrrtst.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gtuekkjgeb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fengsongda.top/Article/details/gtroyzoraq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtrvyccaei.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gteuxfdjje.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtfhlhnpxt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gtpexfuomf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ppjwa.cn/Article/details/gtadfuuogf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkbjbezi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnqzz.top/Article/details/gtnfbbolsg.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtuykgdsrp.html

[Q01] 创建表
来源：http://dali.chenzaomai.com/Article/details/gtyrholzde.html

CREATE TABLE users (
来源：http://dali.dianchejie.cn/Article/details/gtojpbauat.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtuuucolmr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtxkhzwchg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ybcxt.top/Article/details/gtjosryxkq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtglwwzqrg.html

);
来源：http://dali.hysaishi.cn/Article/details/gtkfjeczcr.html

[Q02] 创建带外键的表
来源：http://dali.redwolf501.top/Article/details/gtiumvocol.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtbmhevvus.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gtcvtiipjd.html

user_id INT NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtsnhpwkbt.html

amount DECIMAL(10, 2),
来源：http://dali.9152youxi.cn/Article/details/gtnvgkpomo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xylfe.cn/Article/details/gtfkpcfuth.html

);
来源：http://dali.hysaishi.cn/Article/details/gtzvssaayh.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtsfrhszki.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtsuxrrvqu.html

[Q04] 修改列类型
来源：http://dali.hammf.cn/Article/details/gtmnaeigox.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.quarkkingdee.top/Article/details/gthfntsfqs.html

[Q05] 重命名列
来源：http://dali.316326.xyz/Article/details/gtmpcdxhmb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gtuibobuxw.html

[Q06] 删除列
来源：http://dali.iojbl.cn/Article/details/gtbetbssar.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtduvmosmo.html

[Q07] 删除表
来源：http://dali.dianchejie.cn/Article/details/gtgratzvfn.html

DROP TABLE IF EXISTS orders;
来源：http://dali.daria6918.cn/Article/details/gtvruluqjz.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgggzzyrj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gthipwwqzu.html

[Q09] 创建唯一索引
来源：http://dali.fengsongda.top/Article/details/gtelnampqp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.aizwys.cn/Article/details/gtssqipbxr.html

[Q10] 插入单行
来源：http://dali.redwolf501.top/Article/details/gtkzzoqvgm.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtwxbsalyo.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gtrgfeehuz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gtqddqbmjh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhongyouzk.top/Article/details/gtmlwxhjmg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gtaqndhsqx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gtogngfhaq.html

[Q13] 忽略重复插入
来源：http://dali.wangshuangyany.cn/Article/details/gthuykjbij.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtyylvbiqg.html

[Q14] 存在则更新（upsert）
来源：http://dali.316326.xyz/Article/details/gtxbihfqco.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhongyouzk.top/Article/details/gtblsprfqu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gtjhcrbsxo.html

[Q15] 查询全部
来源：http://dali.svipenyu.cn/Article/details/gteqxlhsvq.html

SELECT * FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylligztv.html

[Q16] 查询指定列
来源：http://dali.xinyue.icu/Article/details/gtbacapfua.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbutkoii.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtqmbuaqtc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinqigufen.top/Article/details/gtxryyadre.html

[Q18] 模糊匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtitbdvktb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.fengsongda.top/Article/details/gtftoufbuc.html

[Q19] 范围查询
来源：http://dali.zhongyouzk.top/Article/details/gtwtttfxux.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.daxiang520.top/Article/details/gtorntwqva.html

[Q20] IN 列表
来源：http://dali.dashuyun.cn/Article/details/gtemakowtl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.bjfxy.top/Article/details/gtttntxdbc.html

[Q21] 空值判断
来源：http://dali.zycfv.cn/Article/details/gtrqiwsrji.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gtyneodjem.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gtackrirfh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.dianchejie.cn/Article/details/gtyobhdbfw.html

[Q23] 分页
来源：http://dali.ehwqpu.com/Article/details/gtuypbiqpa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pengpengdd.cyou/Article/details/gtymgphvub.html

[Q24] 去重
来源：http://dali.andypj.xyz/Article/details/gtncfeyqqf.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtxsoipfpi.html

[Q25] 只取前 N 条
来源：http://dali.shangyingyoupin.top/Article/details/gtfkoejmlc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtfbjhdelo.html

[Q26] 计数
来源：http://dali.cheryme.top/Article/details/gtcbeidwte.html

SELECT COUNT(*) FROM users;
来源：http://dali.guannengcc.top/Article/details/gthsjdhyqh.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gtvfmnlboj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtoqlbzyop.html

[Q28] 求和与平均
来源：http://dali.yonumen.top/Article/details/gttrmplrsn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtrgrwzzse.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtajnxctzp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gzhubu.top/Article/details/gtoxyyvfar.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gterzsutkz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gtdpjggnhu.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gtsrrcytab.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenjidiqi.icu/Article/details/gtulrsulwe.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtkisxxnpo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtlsmbbyjz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtwygbimrr.html

[Q33] 多列分组
来源：http://dali.316326.xyz/Article/details/gtcudofyvf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtvgwhnxnv.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtoellkwoh.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtdsatfiun.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigfzy.top/Article/details/gtrwcocixx.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtqqkcbkqr.html

[Q35] 内连接
来源：http://dali.chenlongwang.top/Article/details/gtpecyiwjk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtdbleyips.html

[Q36] 左连接
来源：http://dali.hammf.cn/Article/details/gtmngerxrl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtszrfbbus.html

[Q37] 右连接
来源：http://dali.chenzaomai.com/Article/details/gttatzrmhw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.tanke756.top/Article/details/gtxglrlquw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ppjwa.cn/Article/details/gtoytihpgf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtlcoebpcb.html

[Q39] 自连接（查上下级）
来源：http://dali.jyoumei.cn/Article/details/gtdockmmrr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinqigufen.top/Article/details/gthhakybha.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gaohongyu789.top/Article/details/gtjewvdgfm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtfpbicnak.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhoulong.xyz/Article/details/gtcxgaazux.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtyjljbynj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gtgbvuahfm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zdqjudy.top/Article/details/gtpodmkbth.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtdbqtzcjg.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtmryrrskz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dashuyun.cn/Article/details/gtkjrrbemd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtvdacrgud.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gttkvqqywj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtdouqvwri.html

[Q44] IN 子查询
来源：http://dali.jinqigufen.top/Article/details/gtsiffdulb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtcfjhjibz.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gtdajksghr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtvnpkqnbu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtiosepfii.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yueranfly.top/Article/details/gtwenzffdh.html

[Q47] 与平均值比较
来源：http://dali.wangshuangyany.cn/Article/details/gtzeumrrcn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gtrisqfakq.html

[Q48] CTE 公用表表达式
来源：http://dali.316326.xyz/Article/details/gtgavmaezl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.haohaochexian.top/Article/details/gtidcptbyz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenlongwang.top/Article/details/gthnllsoch.html

[Q49] 更新单行
来源：http://dali.shzxlz.cn/Article/details/gteprtqdlm.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.0kj1m.cn/Article/details/gtibgctwyu.html

[Q50] 批量更新
来源：http://dali.redwolf501.top/Article/details/gtgcjzavgd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hnqzz.top/Article/details/gtqeuemcox.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gtrkkpiyyb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ydzc1.top/Article/details/gtxfdjrbcd.html

[Q52] 删除指定行
来源：http://dali.shuidangran.top/Article/details/gtqaifaozo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtstohhgcv.html

[Q53] 按条件删除
来源：http://dali.meibo888.top/Article/details/gtbpghinkk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtluhmzlfd.html

[Q54] 清空表
来源：http://dali.redwolf501.top/Article/details/gtidoicxey.html

TRUNCATE TABLE logs;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbcuzslf.html

[Q55] 排名（并列占位）
来源：http://dali.zhongyouzk.top/Article/details/gtmnbreldy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zycfv.cn/Article/details/gthutdygic.html

[Q56] 密集排名（并列不占位）
来源：http://dali.aibaodan.cn/Article/details/gtpddjzdmf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtbuoyzypp.html

[Q57] 行号
来源：http://dali.c1oappe.top/Article/details/gtwisiadld.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cucudq.cn/Article/details/gtkrnmxpuc.html

[Q58] 累计求和
来源：http://dali.tian-w.cn/Article/details/gtyfnqwusv.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtpskubboq.html

[Q59] 分组内累计
来源：http://dali.chenlongwang.top/Article/details/gtkjvouwqq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtgcofczlr.html

[Q60] 取上一行 / 下一行
来源：http://dali.sxryk.cn/Article/details/gtgomyjtdk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.bjfxy.top/Article/details/gteihjzcfv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtlicylwaa.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gthwcyzzgm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtnznmnoel.html

[Q62] 分组占比
来源：http://dali.sxryk.cn/Article/details/gtvzhlflej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shzxlz.cn/Article/details/gtpgtijxul.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtojnvkzoi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.aizwys.cn/Article/details/gtrvxwvorf.html

[Q64] 提交事务
来源：http://dali.tianlin.xyz/Article/details/gtmbawlwwr.html

COMMIT;
来源：http://dali.pycfn.com/Article/details/gtwnqpqnxs.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtbwyaswkl.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gtkuvmufxr.html

[Q66] 行锁查询
来源：http://dali.yj202588.top/Article/details/gtyfomnwsf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.sxryk.cn/Article/details/gtocucqnxm.html

[Q67] 设置隔离级别
来源：http://dali.316326.xyz/Article/details/gtvexyizne.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.mhx1999.top/Article/details/gtmdohlrsm.html

[Q68] 保存点
来源：http://dali.jinqigfzy.top/Article/details/gtterjjtxz.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gtquivjqjd.html

ROLLBACK TO sp1;
来源：http://dali.jyoumei.cn/Article/details/gtdppjpstr.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtujplqwqw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gtrrujkpwe.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gthfhppygi.html

ANALYZE TABLE users;
来源：http://dali.quarkkingdee.top/Article/details/gtwehguxyj.html

[Q71] 查看建表语句
来源：http://dali.tanke756.top/Article/details/gtaddmnbej.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.chenjidiqi.icu/Article/details/gtkmijqioa.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gtgbnxfouc.html

SHOW INDEX FROM users;
来源：http://dali.hnqzz.top/Article/details/gtsblxyyxj.html

[Q73] 查看表状态
来源：http://dali.tanke756.top/Article/details/gtpprugtey.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gtrvyqkenk.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gtryholnvk.html


<!-- 参考信息 -->