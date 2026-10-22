代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxjzoxap.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gt2xjfnoeuh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gt2jqpnimbi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xinyue.icu/Article/details/gt2jnlmohxs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2xaqehctt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daxiang520.top/Article/details/gt2gvbvayfz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2hteoxrxs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gt2rvxotumd.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfxewanp.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gt2nedkcgkc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nkhswgdt.html

[O01] 启动一个线程
来源：http://dali.pengpengdd.cyou/Article/details/gt2wporpghr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gzhubu.top/Article/details/gt2poibowqc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gt2dlzjzslj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2ajlkzsmi.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2wqhwsyya.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2oztzcupd.html

Go:   go f()
来源：http://dali.jqgfzy.top/Article/details/gt2uiwyqsmm.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gt2thvpxnrk.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnshyraq.html

[O02] 使用线程池
来源：http://dali.wangdashe.top/Article/details/gt2viwxjdju.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gt2tkrcrniu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hnqzz.top/Article/details/gt2nqgjkgam.html

JS:   // worker_threads 线程池
来源：http://dali.snrcjt.cn/Article/details/gt2keljlefl.html

TS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2ublamyym.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.haohaochexian.top/Article/details/gt2dqciknim.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gt2myzqjubi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfmvnzbr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gt2djciwhlf.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gt2gktoyeok.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gt2qyqpvbsr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gt2uvkwrzvg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2cwvphcmk.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gt2zblgffay.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gt2iiaahxdl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gt2mbutsojk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2sqqgikrm.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2tndklrbf.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2yyvydkqi.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gt2onjqsxjg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmwswpeb.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gt2hjquuyrb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.iojbl.cn/Article/details/gt2utkjesuu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xziqi.cn/Article/details/gt2mcnftvze.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gt2bkyppadp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2yhfvmxzd.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gt2dtnwpqze.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2ixmnhrbg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qtyspztz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2svsoyuxc.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2uljghuvs.html

TS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atzcjtsw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phspqmvd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gt2bhkwydby.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2qybxoypq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yonumen.top/Article/details/gt2likvyusv.html

[O06] 使用进程池
来源：http://dali.zhixingplan.top/Article/details/gt2vkkuvybf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gt2dpkqbtdt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gt2axmjajzu.html

JS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2vkppoyfc.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2gfkbitot.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pflqaabv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daria6918.cn/Article/details/gt2usvrunky.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gt2vkmwgnsi.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2wuixvkcu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2lkwhxwna.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gt2xgvxmckk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2cogauopy.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gt2ahrigoxl.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gt2ejnmjawy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xziqi.cn/Article/details/gt2xelhstcr.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2lasbittq.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfnqkbit.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rkqkinci.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gt2hqcyzykg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfkpmt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.kuanghao11.cn/Article/details/gt2wctisxnk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gotoacloud.top/Article/details/gt2vmqmjmkw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gt2psfecknw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenzaomai.com/Article/details/gt2huvufmry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gt2urrhmwac.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gt2llecjkkj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.daria6918.cn/Article/details/gt2vucyuzad.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gt2tqvhoqfk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gt2kgekyhap.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gt2eybkciyf.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gt2kmyseayi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gt2baewuwop.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.meibo888.top/Article/details/gt2mqdrnwcv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gt2mgxxhpsj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gt2ejxzgyxk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2gguqrmcs.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.dianchejie.cn/Article/details/gt2vnhidmtq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gt2esywahvr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gt2ctjhxprv.html

[P04] 求长度
来源：http://dali.gogol.net.cn/Article/details/gt2azohmlui.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2dqxaybgl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2ezrubbcd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2fmlzwvct.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2hkzvdtne.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2ehfukxlg.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gt2brkpmnfw.html

Ruby: x.length;  x.size
来源：http://dali.xuanzx.com/Article/details/gt2ppspjash.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2wtwzcnrx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2jiodgmlx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.daxiang520.top/Article/details/gt2phbnincw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gt2kjyrtldh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2tekwmiba.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmhifagu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxjyzznl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.fengsongda.top/Article/details/gt2wkwdszxv.html

Ruby: a == b
来源：http://dali.zhengqikj.top/Article/details/gt2hpsxgrbp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ytokssgs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gt2abnybqdv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ivvv.top/Article/details/gt2wktgcmhd.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2exoqrfno.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhoulong.xyz/Article/details/gt2azgqtcnb.html

TS:   if (x == null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2okefhvua.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2mlfjhzwb.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gt2nssloyat.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gt2pajayufx.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gt2glsbinwd.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqybmype.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gt2oofwoyxr.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gt2daxpyrkn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gt2vockdbsj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gt2cbmxdpcz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuanzx.com/Article/details/gt2xbavknqf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gt2obhzgzwp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ybcxt.top/Article/details/gt2yrghiebi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2rasqhvqd.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gt2pcievmkx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jqgfzy.top/Article/details/gt2qfbzdyro.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gt2eajgxqkw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xuanzx.com/Article/details/gt2fgetugdo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.sweek.top/Article/details/gt2hhnfyjgx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2fprppcwf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2nfiggedi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cucudq.cn/Article/details/gt2acclyoqd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ydzc1.top/Article/details/gt2qwgjbsyu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2gwvvrzwi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gt2zyntojaq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2iulkoupx.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gt2tgrcuekt.html

CREATE TABLE users (
来源：http://dali.shzxlz.cn/Article/details/gt2opoqjwfa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gt2nclsasfj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgyfzequ.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj202588.top/Article/details/gt2ihsfncdr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.c1oappe.top/Article/details/gt2konystoh.html

);
来源：http://dali.gogol.net.cn/Article/details/gt2jwxancvu.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gt2ejetflsn.html

CREATE TABLE orders (
来源：http://dali.cucudq.cn/Article/details/gt2afeocayq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2yjcermox.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gt2tgjwjkbi.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2othlxggb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yuanzhike.top/Article/details/gt2oygeyzng.html

);
来源：http://dali.meibo888.top/Article/details/gt2epvvmfeo.html

[Q03] 增加列
来源：http://dali.chenlongwang.top/Article/details/gt2vavaumhl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gt2kzfnqnmy.html

[Q04] 修改列类型
来源：http://dali.yangfankeji.com/Article/details/gt2edhvelij.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gt2jvblqfee.html

[Q05] 重命名列
来源：http://dali.zhixingplan.top/Article/details/gt2paquoloc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yueranfly.top/Article/details/gt2jglrhoec.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gt2vkwbbffk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhixingplan.top/Article/details/gt2njwitrel.html

[Q07] 删除表
来源：http://dali.xylfe.cn/Article/details/gt2vvpiyeuu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qijdtbum.html

[Q08] 创建普通索引
来源：http://dali.0kj1m.cn/Article/details/gt2kbugdktu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2stihmesp.html

[Q09] 创建唯一索引
来源：http://dali.dashuyun.cn/Article/details/gt2ofpdblcy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.sxryk.cn/Article/details/gt2daaorwsj.html

[Q10] 插入单行
来源：http://dali.svipenyu.cn/Article/details/gt2hnbxcvbt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2ncvjnphz.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gt2nvgtlzbr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2arjnmzkv.html

[Q12] 插入后取自增 ID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vsfcmzfz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gt2fwutwzah.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yj20258888.top/Article/details/gt2fzdgyeib.html

[Q13] 忽略重复插入
来源：http://dali.hfpthk.cn/Article/details/gt2pkroxnvk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guannengcc.top/Article/details/gt2ekuccqel.html

[Q14] 存在则更新（upsert）
来源：http://dali.yj20258.top/Article/details/gt2eqkzpxto.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.wangdashe.top/Article/details/gt2wtcdlpko.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gt2zbiylqen.html

[Q15] 查询全部
来源：http://dali.jinqigufen.top/Article/details/gt2tpmcpldl.html

SELECT * FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2lqwdidip.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gt2cazmvkoq.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ocdnddfh.html

[Q17] 条件查询
来源：http://dali.gogol.net.cn/Article/details/gt2xobvbeaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.iojbl.cn/Article/details/gt2gjtbktgf.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gt2gfbdeftu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cqqwz.cn/Article/details/gt2zqulofln.html

[Q19] 范围查询
来源：http://dali.9152youxi.cn/Article/details/gt2nvmfkuwj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hywenlv.cn/Article/details/gt2faautcny.html

[Q20] IN 列表
来源：http://dali.chenlongwang.top/Article/details/gt2ttdrfvxo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.wangdashe.top/Article/details/gt2mhhsfqet.html

[Q21] 空值判断
来源：http://dali.cheryme.top/Article/details/gt2nyskccrl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gt2hblkztsm.html

[Q22] 排序
来源：http://dali.ppjwa.cn/Article/details/gt2ukpbssse.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yonumen.top/Article/details/gt2jpllqeqi.html

[Q23] 分页
来源：http://dali.tanke756.top/Article/details/gt2senakkox.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fzhhl.top/Article/details/gt2poqnsgxh.html

[Q24] 去重
来源：http://dali.redwolf501.top/Article/details/gt2jmtyfpzc.html

SELECT DISTINCT city FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2fcaammqm.html

[Q25] 只取前 N 条
来源：http://dali.zdqjudy.top/Article/details/gt2jijmztzv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.smart0.xyz/Article/details/gt2prcsseai.html

[Q26] 计数
来源：http://dali.nanxuanxn.top/Article/details/gt2iaurqiyr.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2wmhbblci.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gt2ezkqqsmf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2huytyzkl.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xhhvqrvy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gt2hvwhkzsu.html

[Q29] 最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2jrcbuidb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2hswuchar.html

[Q30] 分组统计
来源：http://dali.yj20258.top/Article/details/gt2qgxyeimm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.guowangkeji.top/Article/details/gt2rxxjvdnv.html

[Q31] 分组后过滤
来源：http://dali.hysaishi.cn/Article/details/gt2afoexeyf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj202588.top/Article/details/gt2buirfqht.html

[Q32] 分组拼接字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2fbnjnigm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gt2bmjpcgxo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gt2xryekrff.html

[Q33] 多列分组
来源：http://dali.zdqjudy.top/Article/details/gt2lsvpstvv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jianghu66.top/Article/details/gt2zxfawhas.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2iyvgpbaw.html

SELECT * FROM (
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxdfeoif.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nanxinkj.top/Article/details/gt2cqsdcher.html

) t WHERE rn = 1;
来源：http://dali.fzhhl.top/Article/details/gt2annvbaxq.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gt2nkqrrkvt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gt2jfnivgce.html

[Q36] 左连接
来源：http://dali.ybcxt.top/Article/details/gt2nnnwpgbt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cheryme.top/Article/details/gt2upjsaoqy.html

[Q37] 右连接
来源：http://dali.hnxiangtu.top/Article/details/gt2uaqhcpwz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuanzx.com/Article/details/gt2qarlrlrm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gt2tgdwlkjk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gt2lkqgbqqr.html

[Q39] 自连接（查上下级）
来源：http://dali.ehwqpu.com/Article/details/gt2pvowging.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gt2ycqtiazf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpkipnbx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gt2sjeifxuh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.andypj.xyz/Article/details/gt2kquikioz.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2zcxjhkhf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwjtgpth.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgfzy.top/Article/details/gt2lcmdcbrv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.c1oappe.top/Article/details/gt2mmbhqnaz.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2dovhdlor.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhixingplan.top/Article/details/gt2oibfvkyd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gt2uzdnsfwc.html

[Q43] 标量子查询
来源：http://dali.vqdsnc.cn/Article/details/gt2idbpzsef.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.hnqzz.top/Article/details/gt2vymhffbx.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gt2hrrmxsve.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.meibo888.top/Article/details/gt2bobqcraj.html

[Q45] EXISTS 判断存在
来源：http://dali.daxiang520.top/Article/details/gt2fjsgxfvd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gt2qfeytynv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yueranfly.top/Article/details/gt2oltqoiie.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gt2wgdrntdo.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2jklnamjr.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gt2zdvspcxs.html

[Q48] CTE 公用表表达式
来源：http://dali.sufxvd.cn/Article/details/gt2opywzkyb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2ypivoudu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajhvblyx.html

[Q49] 更新单行
来源：http://dali.pycfn.com/Article/details/gt2srvvvbty.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gt2wsdtjlaf.html

[Q50] 批量更新
来源：http://dali.shangyingyoupin.top/Article/details/gt2nssdxpkw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fengsongda.top/Article/details/gt2fpmbhksq.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gt2yjtmtjvr.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.fengsongda.top/Article/details/gt2dfmatjti.html

[Q52] 删除指定行
来源：http://dali.tanke756.top/Article/details/gt2gnbpvffu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgshjxht.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gt2smjbfqpf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gt2vyalroag.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gt2qitarudl.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gt2dpjpqmmv.html

[Q55] 排名（并列占位）
来源：http://dali.jianghu66.top/Article/details/gt2daqadgfs.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2gedqtmjj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhengqikj.top/Article/details/gt2azamqrlf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.dianchejie.cn/Article/details/gt2msfyeatb.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2tszmovon.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gt2jbncfmwp.html

[Q58] 累计求和
来源：http://dali.shuidangran.top/Article/details/gt2xmlcueec.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yvedp.cn/Article/details/gt2kxloecku.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gt2snzjxbxz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gt2bssvfupv.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gt2kfbwxigb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zycfv.cn/Article/details/gt2sdscnpuy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gt2mupmyvff.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gt2fgrlvrua.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2bykniiif.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2mjkngjsp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gt2wiyzwirl.html

[Q63] 开启事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkbihvrc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ppjwa.cn/Article/details/gt2ahexlhko.html

[Q64] 提交事务
来源：http://dali.jqgufenzy.top/Article/details/gt2vfyvcxrg.html

COMMIT;
来源：http://dali.cashguo.top/Article/details/gt2ndwekcpd.html

[Q65] 回滚事务
来源：http://dali.cucudq.cn/Article/details/gt2zyujbzpp.html

ROLLBACK;
来源：http://dali.daria6918.cn/Article/details/gt2qirsnviu.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lthovayo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2kstrposu.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gt2alepevww.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gt2twomxmhr.html

[Q68] 保存点
来源：http://dali.yueranfly.top/Article/details/gt2gtifwqwk.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gt2enogcfwn.html


<!-- 参考信息 -->