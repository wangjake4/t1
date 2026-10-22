代发 wailian999

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtnpkepvda.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gtjnbtahty.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gtrpgbefkj.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtxyaitrwg.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtakekljrb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gthbxqbqta.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cucudq.cn/Article/details/gtyxpzppas.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtoehmocxu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gticzycjmy.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtudfqicfn.html

Py:   with lock: shared += 1
来源：http://dali.c1oappe.top/Article/details/gtlweozvsz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtetaunefj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtxaucsjpv.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtxtvczaum.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtyrgohbqu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtwknsaifj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtpyungktr.html

C#:   lock (gate) { shared++; }
来源：http://dali.aizwys.cn/Article/details/gtsgyebmij.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdsbkmol.html

Py:   async def f():⏎    await g()
来源：http://dali.birdmap.top/Article/details/gtylnfxwae.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hnqzz.top/Article/details/gtbkabtklo.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzjdoyunt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gthwvvwloo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtwxvtqeim.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dianchejie.cn/Article/details/gtqdhtzgvk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jyoumei.cn/Article/details/gttduepssh.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gtijwafpbp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtsrtxcxsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtssohxrmr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtudmzswfi.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gterygrnjs.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtttodhswc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthbovsem.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gtggwmgwoe.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtcpuenthl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtndcujwiw.html

[O06] 使用进程池
来源：http://dali.feifeiyinyue.top/Article/details/gtwqgtmoqc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gthjtmlkvf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jiagoushi.top/Article/details/gtzvgitznu.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtkwmewaph.html

TS:   // child_process / cluster 模块
来源：http://dali.cheryme.top/Article/details/gtrtqghfja.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gtlywxlpkw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzqgwsyv.html

Ruby: // fork 块
来源：http://dali.cashguo.top/Article/details/gtlwbenzfm.html

C#:   Parallel.For
来源：http://dali.ydzc1.top/Article/details/gtbnujmvvs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtylbxckxh.html

P. 常用工具函数
来源：http://dali.hfpthk.cn/Article/details/gtggfefttt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtqzoyfoap.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtipmizhqp.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtqhdbdufj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtmettadvf.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtrqtqalku.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gthyapvmdz.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gtzseekdvn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsnmxxrb.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtojxzlkbp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtpjtxglla.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jlsjyb.cn/Article/details/gtfvogalci.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtcovxwcxz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.birdmap.top/Article/details/gtsbrkckro.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtyaizbtue.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gtagflourm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gtgrduytif.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtggqepkec.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gtiqskeawd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gtyjivvrov.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtalasdpex.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuanzx.com/Article/details/gtzjsofzvd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.iojbl.cn/Article/details/gtowzxpsmu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtedldzonk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtcdjisvwt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ehwqpu.com/Article/details/gtplpchkgl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtufaifwki.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtztnlffhb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjizymby.html

[P04] 求长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrlkwwwt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtirmksivw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gteujztoof.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuwtgxnl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtwsnxqywu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xuanzx.com/Article/details/gtsdqchepz.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtqxthgele.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtdtbsffdc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.bjfxy.top/Article/details/gtfilbppaa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zycfv.cn/Article/details/gthvdvzgme.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.tianlin.xyz/Article/details/gtmqqrslro.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gtevadaegc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangshuangyany.cn/Article/details/gtkgujiflz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtzlnetgdm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtyoayaebh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtkxqfckwf.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gttktmfomx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.iojbl.cn/Article/details/gthukpsafw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.smart0.xyz/Article/details/gthsahivxr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gthodgdevp.html

PHP:  if (empty($x)) {}
来源：http://dali.cheryme.top/Article/details/gtacosowey.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gtbvgjxlnb.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdosngfun.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtpobcdqzt.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtpsskpoqo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.dianchejie.cn/Article/details/gtckbvaosy.html

C#:   if (x is null) {}
来源：http://dali.zhengqikj.top/Article/details/gtopahbypz.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gtslnjvksz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ehwqpu.com/Article/details/gticnqfjlw.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigfzy.top/Article/details/gtvaxbsctp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gtsaurespm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtpvjlpnva.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtuavugxuv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.bjfxy.top/Article/details/gtktcogkxp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gthnvmxloq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtaexiyjgt.html

[P08] 处理浮点精度问题
来源：http://dali.ehwqpu.com/Article/details/gtmfjedujz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yonumen.top/Article/details/gtrpmiajvi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gtgymkoagu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtvwopqbcy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfuagqmw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gtisopesry.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gthzyzkxeq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.svipenyu.cn/Article/details/gtrxaxnlwh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gtoeansddn.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttyuuehpk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtifkkccqx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxzbcgoxc.html

[Q01] 创建表
来源：http://dali.yongpay.top/Article/details/gtpsnypjhs.html

CREATE TABLE users (
来源：http://dali.nanxuanxn.top/Article/details/gtqlidqgzn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtctrkwquq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gtyncgehco.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigufen.top/Article/details/gtsxeadntn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gtmglyszep.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtcgdpznzs.html

[Q02] 创建带外键的表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyppzuknc.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtiicmbnqq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtwmkoorbm.html

user_id INT NOT NULL,
来源：http://dali.pengpengdd.cyou/Article/details/gtpfsdjhfe.html

amount DECIMAL(10, 2),
来源：http://dali.yuanzhike.top/Article/details/gtskejsrpj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhixingplan.top/Article/details/gtiyamoxil.html

);
来源：http://dali.gogol.net.cn/Article/details/gtezwsyolj.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtibmiovnf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtiorsnigj.html

[Q04] 修改列类型
来源：http://dali.zdqjudy.top/Article/details/gtwbldsmxg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhengqikj.top/Article/details/gtfyyfxqms.html

[Q05] 重命名列
来源：http://dali.yonumen.top/Article/details/gttinrmtos.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.daria6918.cn/Article/details/gtvzvbbqxz.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gterlloaqi.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xylfe.cn/Article/details/gtvvcbyaaa.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtmxclyqqc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtniqegguh.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gtsvbsaavn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xuetiantiany.cn/Article/details/gtacvrojyr.html

[Q09] 创建唯一索引
来源：http://dali.xziqi.cn/Article/details/gtejdmmruk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtmafmlqfm.html

[Q10] 插入单行
来源：http://dali.cqqwz.cn/Article/details/gtwmrbsjvf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.smart0.xyz/Article/details/gtszjsnjag.html

[Q11] 一次插入多行
来源：http://dali.9152youxi.cn/Article/details/gtlfescphc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwmwbhzo.html

[Q12] 插入后取自增 ID
来源：http://dali.hammf.cn/Article/details/gteowhvtlo.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.xziqi.cn/Article/details/gttuuaazvy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtyatbaksz.html

[Q13] 忽略重复插入
来源：http://dali.jyoumei.cn/Article/details/gtkmkkbapw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gtcarbxnfi.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gtfedmscdg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zycfv.cn/Article/details/gtwwsypjnk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gteiwyqubt.html

[Q15] 查询全部
来源：http://dali.9152youxi.cn/Article/details/gtxorkefcp.html

SELECT * FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtdjituhbs.html

[Q16] 查询指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueduoczk.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtxdvtdyqt.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtoycjgahu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.guannengcc.top/Article/details/gttwasovyw.html

[Q18] 模糊匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtijmwvhfs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnqzz.top/Article/details/gtksaokjgk.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gtnwugfzdu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zycfv.cn/Article/details/gtmqlvvaxm.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtmufqlfoc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nwbrower.top/Article/details/gtotboyeqj.html

[Q21] 空值判断
来源：http://dali.bjfxy.top/Article/details/gtetpqfvrb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pycfn.com/Article/details/gtnmbecvag.html

[Q22] 排序
来源：http://dali.yonumen.top/Article/details/gtliwaakcr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gtooizqjri.html

[Q23] 分页
来源：http://dali.yj202588.top/Article/details/gtytadwtbm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.feifeiyinyue.top/Article/details/gttfckjkhb.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtjamtyapa.html

SELECT DISTINCT city FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtfdrmpfbi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gtjttyzitt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtvdhpfnxr.html

[Q26] 计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcqpnttm.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtzcxzuqgm.html

[Q27] 条件计数
来源：http://dali.fzhhl.top/Article/details/gtnmjpodir.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gtkchukoxn.html

[Q28] 求和与平均
来源：http://dali.hfpthk.cn/Article/details/gtxgjbfshf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtuiivjswo.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gtpbuqpwau.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtmkmxzvsy.html

[Q30] 分组统计
来源：http://dali.sxryk.cn/Article/details/gtclkgyehs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbuiiukm.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtvlnrqxyj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtlnwqvkha.html

[Q32] 分组拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtaejrxreb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nanxinkj.top/Article/details/gtdhxpreya.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtwakhlbkp.html

[Q33] 多列分组
来源：http://dali.aibaodan.cn/Article/details/gtvfbditmw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gtlvsrirps.html

[Q34] 每组取第一条
来源：http://dali.redwolf501.top/Article/details/gtgcwttdlv.html

SELECT * FROM (
来源：http://dali.zdqjudy.top/Article/details/gtgwtfyudx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtdyopkacd.html

) t WHERE rn = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtqidkikef.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtfdqxxsjn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gtcmosvxml.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkkhgybx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gthevjiqjb.html

[Q37] 右连接
来源：http://dali.bjfxy.top/Article/details/gtidzqljkw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtiyrbaotr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtxyjwqzyl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtlxpuqmjs.html

[Q39] 自连接（查上下级）
来源：http://dali.xuetiantiany.cn/Article/details/gthexeamrj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtmzemwude.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yonumen.top/Article/details/gtnmtgtvkj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.meibo888.top/Article/details/gtbsunowvt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtkibizvmq.html

[Q41] 多表连接
来源：http://dali.chenzaomai.com/Article/details/gtmxrbknww.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtmxqhcpbn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xylfe.cn/Article/details/gtxjggcimm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuxming.cn/Article/details/gtigpabxyy.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtgraynjji.html

SELECT u.name, o.amount FROM users u
来源：http://dali.haohaochexian.top/Article/details/gtilejhapl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtlsbgxjdn.html

[Q43] 标量子查询
来源：http://dali.jianghu66.top/Article/details/gtlfdwutgn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtlyqzywuu.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtbfmxjqub.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.tianlin.xyz/Article/details/gtomgxenei.html

[Q45] EXISTS 判断存在
来源：http://dali.yj202588.top/Article/details/gtimsicjkm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.bjfxy.top/Article/details/gtqpgyzqrc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guowangkeji.top/Article/details/gtoicyrqew.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.iojbl.cn/Article/details/gtncycmqvv.html

[Q47] 与平均值比较
来源：http://dali.daria6918.cn/Article/details/gtpubppskb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ppjwa.cn/Article/details/gteidhepip.html

[Q48] CTE 公用表表达式
来源：http://dali.vqdsnc.cn/Article/details/gtqakrwwds.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtsjwkhncb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.wangshuangyany.cn/Article/details/gthxghvlgz.html

[Q49] 更新单行
来源：http://dali.sufxvd.cn/Article/details/gthwgidyzp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtlqsfpufs.html

[Q50] 批量更新
来源：http://dali.aibaodan.cn/Article/details/gtzfpnnala.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gtiylngurn.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyratris.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hammf.cn/Article/details/gtxmhclcwd.html

[Q52] 删除指定行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiapjbai.html

DELETE FROM users WHERE id = 10;
来源：http://dali.hywenlv.cn/Article/details/gtspssuuww.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gtkewrzinf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fengsongda.top/Article/details/gtpxwnkrux.html

[Q54] 清空表
来源：http://dali.yueranfly.top/Article/details/gtvdpfhxwo.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtsciawfyf.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtjnllaxzb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gtzlnpajwo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.fzhhl.top/Article/details/gtrnojscnj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtjgribnme.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtaodfrrkb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtxcawhaka.html

[Q58] 累计求和
来源：http://dali.xuetiantiany.cn/Article/details/gtcgnvdczw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtdysryntl.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtsjqfheap.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtfgwxbiyg.html

[Q60] 取上一行 / 下一行
来源：http://dali.xylfe.cn/Article/details/gtgxpbeenm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtckkkuatr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtciobfpek.html

[Q61] 移动平均
来源：http://dali.yj202588.top/Article/details/gtywvjlfkf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtfnmzbqyp.html

[Q62] 分组占比
来源：http://dali.0kj1m.cn/Article/details/gtbtlaxbkr.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvgiungoo.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtsqquotgk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuanzx.com/Article/details/gtcesvglzr.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtylsstfbm.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtorbamdix.html

[Q65] 回滚事务
来源：http://dali.zhengqikj.top/Article/details/gtpqxvzqtp.html

ROLLBACK;
来源：http://dali.pengpengdd.cyou/Article/details/gtroklmvyn.html

[Q66] 行锁查询
来源：http://dali.gaohongyu789.top/Article/details/gtubeczgov.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jyoumei.cn/Article/details/gtcjdqbplk.html

[Q67] 设置隔离级别
来源：http://dali.zdqjudy.top/Article/details/gtkefofzot.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.sxryk.cn/Article/details/gtabieycoq.html

[Q68] 保存点
来源：http://dali.jinqigufen.top/Article/details/gtidjgxxcg.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtaivvwahg.html

ROLLBACK TO sp1;
来源：http://dali.gotoacloud.top/Article/details/gtfwlgksjl.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtwscopdow.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gthrfnuuez.html

[Q70] 更新统计信息
来源：http://dali.pycfn.com/Article/details/gtpknvhiij.html

ANALYZE TABLE users;
来源：http://dali.birdmap.top/Article/details/gtimjkzrxu.html

[Q71] 查看建表语句
来源：http://dali.sysykeji.top/Article/details/gtjhmzqdoc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtunfkyiwk.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtvreclwio.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtncscfvdr.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gttlcslisq.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jianghu66.top/Article/details/gtsbdqiwfq.html

[Q74] 强制使用索引
来源：http://dali.cheryme.top/Article/details/gtolsqjxxp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aibaodan.cn/Article/details/gtfmrvnsix.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtrvncwzuw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gthfvrjciy.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.fzhhl.top/Article/details/gtbjqchdqz.html

[Q76] 按天统计
来源：http://dali.shanyushiyangtech.top/Article/details/gthvauizbq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gtsrmicwxu.html

[Q77] 时间加减
来源：http://dali.bjfxy.top/Article/details/gtvpuxzxqd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.kuanghao11.cn/Article/details/gtqifaqzis.html


<!-- 参考信息 -->