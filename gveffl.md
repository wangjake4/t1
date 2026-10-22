代发 wailian999

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigufen.top/Article/details/gt2cscevgtf.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gt2czxdtibj.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2cotdutpn.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gt2koxewdfv.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gt2awdctbuk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2tbwmbhoy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gt2civikluv.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2tqksgzhg.html

TS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gt2zwqhknow.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhongyouzk.top/Article/details/gt2qccsadfe.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gt2bkjknqql.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gt2keogjioy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gt2buhsnopq.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2flusjceq.html

Py:   with lock: shared += 1
来源：http://dali.hnxiangtu.top/Article/details/gt2glxekspm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gt2zwrcxbsp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gt2wokrzsfe.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2uxtzehkh.html

Java: synchronized (this) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gt2xecvskqc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gt2eybsowwj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guannengcc.top/Article/details/gt2frhyxwex.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gt2gljvzamm.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gt2rtzpdryy.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jclmnbci.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.kuanghao11.cn/Article/details/gt2xduuqgwz.html

JS:   async function f() { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2xmkgjusz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tgmuzgjs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gt2xuvmkgbm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2txqkffhn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.dashuyun.cn/Article/details/gt2nyzvxbci.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgcdjost.html

[O05] 并发执行并等待全部完成
来源：http://dali.xylfe.cn/Article/details/gt2vdytxwdh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2dpcanixg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2pfrfpksc.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2hmhwhrah.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2yncxvzxh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gt2oyyoniei.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gt2enzqbldw.html

Ruby: threads.map(&:join)
来源：http://dali.jiagoushi.top/Article/details/gt2nsdpoqkd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gt2timsqyzz.html

[O06] 使用进程池
来源：http://dali.aibaodan.cn/Article/details/gt2znaqvozm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjeemufy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gt2dlknilme.html

JS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gt2dhxrfjqa.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2wggpbbwf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gt2wkcuqeju.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gt2hcxsfbzn.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gt2ctxwkwqs.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gt2qlwbmtks.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2qwngsiat.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2lqqmkbfh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2zgrdmujo.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2jpthvkov.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gt2ubwelrvz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gt2ryewajll.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iejrhmra.html

TS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2nutatbnp.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njrulygv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2wqvnyfaq.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gt2rpkumyvl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2hzwlsukg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gt2ooqtboge.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jyoumei.cn/Article/details/gt2quhodgxo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ivvv.top/Article/details/gt2ijedzepl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2kidibagw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tianlin.xyz/Article/details/gt2mqoccbnm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2pgljhdfh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmreqysx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gt2kavqslsj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj20258888.top/Article/details/gt2iqeuzlge.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gt2toshabbk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xylfe.cn/Article/details/gt2gnbpsicu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gt2xkqezjvi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2vhhmtztb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gt2rzashgmq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuxming.cn/Article/details/gt2srqvkcmc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gt2nuxalgvf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gt2tahuqqbv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pycfn.com/Article/details/gt2vsbnxyip.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gt2dddnqhlp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gt2znhhzbzc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2pdrspovp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2jexpldds.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybyygboo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2xhpwhoff.html

Go:   len(arr);  len(m)
来源：http://dali.ivvv.top/Article/details/gt2oujvmspl.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wztlvhiq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2lcsdrtou.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fzhhl.top/Article/details/gt2kyuaprvz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xylfe.cn/Article/details/gt2gtxmjzci.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gt2oglxhvrb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2gayycrcv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2lwznzmsp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2odpnouli.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2xakxuzeh.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gt2aogwoior.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2nqmtvmpe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oheuodyo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gt2uummegua.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2xcgovuci.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bqaixzck.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2adhqwifb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuxming.cn/Article/details/gt2ykngikgo.html

Go:   if x == nil {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2smcriagl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2qexyoorq.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gt2cssjqotb.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfcshahw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gt2duboqdht.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2yuxbjpit.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gt2beqgckcs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fzhhl.top/Article/details/gt2qrgmyyif.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ezlwirhx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gt2opvyvesi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cheryme.top/Article/details/gt2fedxdkyg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gt2kzassesf.html

[P08] 处理浮点精度问题
来源：http://dali.yuxming.cn/Article/details/gt2rcsdsuvm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gt2dnjkdkoh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hammf.cn/Article/details/gt2tugpepwg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzypoumi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gt2mltnndon.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gt2orkuisum.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gt2cbgujhim.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jiagoushi.top/Article/details/gt2tzobnxxp.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gt2ofsslggk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rvgitmjk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gt2dasvoudl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2yytmiycp.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2opfyskvr.html

CREATE TABLE users (
来源：http://dali.sxryk.cn/Article/details/gt2ctzrlimg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2vcukbrpc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2vhacknjb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xuetiantiany.cn/Article/details/gt2juehjjgi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.haohaochexian.top/Article/details/gt2hugbsaxc.html

);
来源：http://dali.cucudq.cn/Article/details/gt2rtmmkcqu.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gt2vkfpqchr.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gt2aadywsfk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gt2ukdhpdkf.html

user_id INT NOT NULL,
来源：http://dali.shzxlz.cn/Article/details/gt2xzztlsks.html

amount DECIMAL(10, 2),
来源：http://dali.yongpay.top/Article/details/gt2rvehqofp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gt2yxnninna.html

);
来源：http://dali.guannengcc.top/Article/details/gt2gszwihvk.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gt2qgrhqjbr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.iojbl.cn/Article/details/gt2tkpkttrt.html

[Q04] 修改列类型
来源：http://dali.ydzc1.top/Article/details/gt2sdjhgsiq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hnxiangtu.top/Article/details/gt2xvciezen.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gt2wyytejgc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2gwyzruim.html

[Q06] 删除列
来源：http://dali.tanke756.top/Article/details/gt2kuhwsigp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.pengpengdd.cyou/Article/details/gt2eybwbcka.html

[Q07] 删除表
来源：http://dali.ppjwa.cn/Article/details/gt2gstykbmy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.aizwys.cn/Article/details/gt2xifngkcm.html

[Q08] 创建普通索引
来源：http://dali.yonumen.top/Article/details/gt2ugyucndu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.fengsongda.top/Article/details/gt2selhsmuc.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gt2whzybzff.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.daxiang520.top/Article/details/gt2nmreabyr.html

[Q10] 插入单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijhjmupj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chdmrsqg.html

[Q11] 一次插入多行
来源：http://dali.zhongyouzk.top/Article/details/gt2csffwzxh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.havefunace.top/Article/details/gt2onawxsoa.html

[Q12] 插入后取自增 ID
来源：http://dali.ivvv.top/Article/details/gt2amxqbkdw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.aibaodan.cn/Article/details/gt2sahrtnad.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gt2dicyckii.html

[Q13] 忽略重复插入
来源：http://dali.cheryme.top/Article/details/gt2fkiwofbd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2hblwdlul.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2rqyjzaep.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tanke756.top/Article/details/gt2aikbzlhw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgufenzy.top/Article/details/gt2yjzrowrp.html

[Q15] 查询全部
来源：http://dali.ybcxt.top/Article/details/gt2lpauncwt.html

SELECT * FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2apojbyvy.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2xaayoqnd.html

SELECT id, name FROM users;
来源：http://dali.cashguo.top/Article/details/gt2itzhzsxu.html

[Q17] 条件查询
来源：http://dali.aibaodan.cn/Article/details/gt2miazqijf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gt2tqqettsg.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gt2aluztrdi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2inhzadmk.html

[Q19] 范围查询
来源：http://dali.andypj.xyz/Article/details/gt2npgdxhct.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ggspknxd.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gt2xudcfmcx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nusfimld.html

[Q21] 空值判断
来源：http://dali.xylfe.cn/Article/details/gt2hujadqhc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2cliafscf.html

[Q22] 排序
来源：http://dali.jinqigufen.top/Article/details/gt2wiborigm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.redwolf501.top/Article/details/gt2qgpawteb.html

[Q23] 分页
来源：http://dali.yangfankeji.com/Article/details/gt2vjyihegb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gt2uqiopwqy.html

[Q24] 去重
来源：http://dali.nwbrower.top/Article/details/gt2rsqubpil.html

SELECT DISTINCT city FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ruhxyace.html

[Q25] 只取前 N 条
来源：http://dali.cqqwz.cn/Article/details/gt2ohitrtkn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gt2pexqczvp.html

[Q26] 计数
来源：http://dali.tian-w.cn/Article/details/gt2wvlzpsld.html

SELECT COUNT(*) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2qgfeqdwb.html

[Q27] 条件计数
来源：http://dali.hywenlv.cn/Article/details/gt2scnpsyxt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2flbuerqp.html

[Q28] 求和与平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxofakqo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2sxwjowtl.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2rnxiaajm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sweek.top/Article/details/gt2brclyzrw.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gt2iqmsttzm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zdrzxgyq.html

[Q31] 分组后过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2pstpdovv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gt2ejntjndf.html

[Q32] 分组拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gt2zoxfpkhl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2fcbouina.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gt2sszcbhgh.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2jhqjfylp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.smart0.xyz/Article/details/gt2pckrnymg.html

[Q34] 每组取第一条
来源：http://dali.meibo888.top/Article/details/gt2qlrpgqpa.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gt2wxpbdgwg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfbksdve.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gt2fzmdqqdh.html

[Q35] 内连接
来源：http://dali.yueranfly.top/Article/details/gt2hztsfold.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2vmlpoarc.html

[Q36] 左连接
来源：http://dali.cheryme.top/Article/details/gt2qxjzyfar.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2momndiuu.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gt2bmwalpeb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sufxvd.cn/Article/details/gt2ocuhnjut.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.aizwys.cn/Article/details/gt2rvlvumbe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.daria6918.cn/Article/details/gt2enyoauhv.html

[Q39] 自连接（查上下级）
来源：http://dali.fzhhl.top/Article/details/gt2ceimxhfi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gt2fwpbddkz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yvedp.cn/Article/details/gt2mmmnyxuu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gt2kpzglirk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nwbrower.top/Article/details/gt2qpqhlyqz.html

[Q41] 多表连接
来源：http://dali.aibaodan.cn/Article/details/gt2pborxutc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2osimtqet.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gt2owhxdebg.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pcgqshdu.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2lueklxwo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gt2astqnvch.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aoywchut.html

[Q43] 标量子查询
来源：http://dali.fengsongda.top/Article/details/gt2nbjtmabk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2qnecxiwx.html

[Q44] IN 子查询
来源：http://dali.yuxming.cn/Article/details/gt2hukxlyoj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqdlidrz.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttuqepcm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.snrcjt.cn/Article/details/gt2ldddvevf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenzaomai.com/Article/details/gt2lohpxyeo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258888.top/Article/details/gt2luoixcub.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gt2xvwiljzz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cucudq.cn/Article/details/gt2fcvumzbd.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gt2wbbairrl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yvedp.cn/Article/details/gt2ldwimtmg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcarmtxv.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzbvojie.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zycfv.cn/Article/details/gt2vhnxvjib.html

[Q50] 批量更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2iltkyhms.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gt2nqpxocuv.html

[Q51] 用子查询更新
来源：http://dali.xylfe.cn/Article/details/gt2utuspcjh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sfmcimnj.html

[Q52] 删除指定行
来源：http://dali.tianlin.xyz/Article/details/gt2jsnrowkh.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2hjmlaqhk.html

[Q53] 按条件删除
来源：http://dali.birdmap.top/Article/details/gt2btbijtmq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2izxzqlyj.html

[Q54] 清空表
来源：http://dali.daxiang520.top/Article/details/gt2dqyohmtx.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gt2uscwrxpb.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhljrbzj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.pycfn.com/Article/details/gt2ivpqjtbv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ehwqpu.com/Article/details/gt2kqkckjiu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gt2aboxrmyp.html

[Q57] 行号
来源：http://dali.hongshengwenyu.top/Article/details/gt2igeofgai.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2dwpquzqc.html

[Q58] 累计求和
来源：http://dali.tanke756.top/Article/details/gt2pwunndoj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gt2nyumbvvs.html

[Q59] 分组内累计
来源：http://dali.andypj.xyz/Article/details/gt2ybyygkyu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2qmvlgkco.html

[Q60] 取上一行 / 下一行
来源：http://dali.cashguo.top/Article/details/gt2hbcwkjda.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.sysykeji.top/Article/details/gt2lojekaje.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2yqikfpbi.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gt2vmlksrak.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfhrkhy.html

[Q62] 分组占比
来源：http://dali.yangfankeji.com/Article/details/gt2zjvsbzjs.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gt2kjgbntex.html

[Q63] 开启事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2oanpcnrf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cdnleiting.top/Article/details/gt2muynmeor.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2wbidynmm.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2pnznmpoz.html

[Q65] 回滚事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2rajxypwa.html

ROLLBACK;
来源：http://dali.ivvv.top/Article/details/gt2lingzzfd.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gt2ellcdrbp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cashguo.top/Article/details/gt2lmkdhsgw.html

[Q67] 设置隔离级别
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghcbqwbi.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.dashuyun.cn/Article/details/gt2ncfqxafv.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moffwcpf.html

SAVEPOINT sp1;
来源：http://dali.andypj.xyz/Article/details/gt2qthxoywd.html

ROLLBACK TO sp1;
来源：http://dali.yj202588.top/Article/details/gt2nrpldtib.html

[Q69] 查看执行计划
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuhamwpg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgfzy.top/Article/details/gt2qqwbmuno.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gt2gbepczpo.html

ANALYZE TABLE users;
来源：http://dali.sweek.top/Article/details/gt2wntunjya.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gt2itgvppnc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.vqdsnc.cn/Article/details/gt2wwmdhdno.html

[Q72] 查看索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjaphdhy.html

SHOW INDEX FROM users;
来源：http://dali.xinyue.icu/Article/details/gt2xhbhnarr.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gt2diqsbzrt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2tgzdtcex.html

[Q74] 强制使用索引
来源：http://dali.gogol.net.cn/Article/details/gt2dxcckxiy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hammf.cn/Article/details/gt2ghervciw.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gt2sulzsqbn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gt2roiiaxrj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daria6918.cn/Article/details/gt2fewzwnax.html


<!-- 参考信息 -->