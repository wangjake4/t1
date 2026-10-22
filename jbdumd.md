代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2bxulpisp.html

[O03] 加锁保护共享数据
来源：http://dali.shzxlz.cn/Article/details/gt2szgosfnp.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gt2mvlukrjp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gt2epxjwfka.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gt2vmlafnnq.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2poadxgri.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2kksfzuqs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2ilcswsqw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2rokhkxnm.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gt2fqcauqxx.html

[O04] 定义异步函数并等待
来源：http://dali.sxryk.cn/Article/details/gt2rqjcxcvz.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gt2icskywbn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eoronjnb.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mflilkvz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2xxqkgbcs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2egnirkej.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gt2atbtpcqm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gt2tggksqbc.html

C#:   async Task F() { await G(); }
来源：http://dali.sysykeji.top/Article/details/gt2nhwjvyve.html

[O05] 并发执行并等待全部完成
来源：http://dali.gaohongyu789.top/Article/details/gt2fvnvctte.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gt2wbavwjbx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gt2pkjjgzat.html

JS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2omupkyhv.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2bpxpjyjk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gt2jaqqmdbs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehdbftto.html

Ruby: threads.map(&:join)
来源：http://dali.yvedp.cn/Article/details/gt2ueqdiikt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gt2wzcffmyf.html

[O06] 使用进程池
来源：http://dali.smart0.xyz/Article/details/gt2npsehrbm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gt2vmtnwrgn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfrjlfny.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxxhseby.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrusghsb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2ygwyslgu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxinkj.top/Article/details/gt2eikyexjo.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gt2mgbrlgbo.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gt2wipjcdyr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2obullksj.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2bmsqzexr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2nwdvnstv.html

[P01] 生成 UUID
来源：http://dali.ppjwa.cn/Article/details/gt2ylyztgqb.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gt2baivhkgx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gt2uwsjdckd.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gt2iwzwyugf.html

TS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2yuxytbok.html

Java: UUID.randomUUID().toString()
来源：http://dali.birdmap.top/Article/details/gt2bzcxfiec.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2spzietzb.html

Ruby: SecureRandom.uuid
来源：http://dali.gogol.net.cn/Article/details/gt2kbjoukzq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iuoiyfvd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2yduvjmde.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nwbrower.top/Article/details/gt2fzcuecss.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.9152youxi.cn/Article/details/gt2bvjirawr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrjbxafl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gt2cdswtgnj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.9152youxi.cn/Article/details/gt2vzitejmc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gt2lhbhoile.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gt2odiqnvmv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ybcxt.top/Article/details/gt2ahubrcjj.html

[P03] 生成短随机字符串
来源：http://dali.gzhubu.top/Article/details/gt2hnqvikqb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gt2hkkvsfpr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hfpthk.cn/Article/details/gt2cqnzbbzk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2lxaerfyx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj202588.top/Article/details/gt2gitkbujx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.316326.xyz/Article/details/gt2fekvoxwg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qpxajhtn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gt2rgoezyvu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojyeojac.html

[P04] 求长度
来源：http://dali.daxiang520.top/Article/details/gt2ggueqipj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbtxxxnc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2nyxdpoaz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2fpfujucv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gt2lryvelhf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guannengcc.top/Article/details/gt2ikjizref.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gt2giygzwii.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gt2txlwnhgd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.redwolf501.top/Article/details/gt2bhhcpuya.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gt2ifauulhx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2gtcextnc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gt2fpmuwsdc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gt2zvxcrolg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2eqarsyjh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2gmwgrpod.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cqqwz.cn/Article/details/gt2awwlfbmh.html

Ruby: a == b
来源：http://dali.yangfankeji.com/Article/details/gt2lbjmtiug.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gt2iyrvtneg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gt2nstgtvrn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gt2cnldqkfi.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2bxetdfod.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2oyklilio.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gt2hpbrrsek.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gt2djzipdby.html

Go:   if x == nil {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnynupbh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gt2dohwmifz.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2oeofxain.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gt2vgfrvntw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gt2frfnotnq.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gt2rtggaeyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2edstunad.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2kxvtctld.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcfpvsvv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gt2ayszmmau.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangdashe.top/Article/details/gt2cfobgktz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2zusfihgb.html

[P08] 处理浮点精度问题
来源：http://dali.snrcjt.cn/Article/details/gt2xxtubiwx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yanxiufei.cn/Article/details/gt2nvzrfpyl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jyoumei.cn/Article/details/gt2jrdpsyyz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2ehkgrqcr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2mvjdimao.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzbtesur.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gt2aczoklbw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xylfe.cn/Article/details/gt2ekuuvnne.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.9152youxi.cn/Article/details/gt2owvfagxl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ooxnbgrn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adtbzhun.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvxcdpuh.html

[Q01] 创建表
来源：http://dali.yvedp.cn/Article/details/gt2dikhjjcu.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gt2ojlfbjxu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2mviijbjf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuanzx.com/Article/details/gt2lpxszbbp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcyubin.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gt2gavlweef.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2vofmxryb.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gt2bpbmswam.html

CREATE TABLE orders (
来源：http://dali.zhoulong.xyz/Article/details/gt2lwbzckji.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jlsjyb.cn/Article/details/gt2xvbpjvkc.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2btofrahs.html

amount DECIMAL(10, 2),
来源：http://dali.zhixingplan.top/Article/details/gt2zeuagaby.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gt2maafdcza.html

);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbkijzin.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gt2hyuagfei.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gt2oxiaoatq.html

[Q04] 修改列类型
来源：http://dali.shzxlz.cn/Article/details/gt2vdwhlqlj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sufxvd.cn/Article/details/gt2lgydhnqq.html

[Q05] 重命名列
来源：http://dali.zycfv.cn/Article/details/gt2atreibll.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dianchejie.cn/Article/details/gt2vwhrjiig.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gt2drositwa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gt2izccgkfl.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gt2dxctmvbg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gt2xdveefnh.html

[Q08] 创建普通索引
来源：http://dali.hnxiangtu.top/Article/details/gt2oiemplck.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wujtzexw.html

[Q09] 创建唯一索引
来源：http://dali.gogol.net.cn/Article/details/gt2zhewyicf.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gt2acgmoezf.html

[Q10] 插入单行
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifscecel.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2qofysxos.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gt2unhvwzfx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2lubseuok.html

[Q12] 插入后取自增 ID
来源：http://dali.ppjwa.cn/Article/details/gt2xufjtiol.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gt2vsouvhwc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cashguo.top/Article/details/gt2qrdgebwx.html

[Q13] 忽略重复插入
来源：http://dali.cashguo.top/Article/details/gt2qawnujkp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.chenlongwang.top/Article/details/gt2wffxohty.html

[Q14] 存在则更新（upsert）
来源：http://dali.aizwys.cn/Article/details/gt2bjkpsrma.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.tianlin.xyz/Article/details/gt2sapdyytd.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gt2clkfkiil.html

[Q15] 查询全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aptqbvtm.html

SELECT * FROM users;
来源：http://dali.yuxming.cn/Article/details/gt2gqjcveed.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxyhuzlc.html

SELECT id, name FROM users;
来源：http://dali.gotoacloud.top/Article/details/gt2oezbcmiw.html

[Q17] 条件查询
来源：http://dali.dianchejie.cn/Article/details/gt2wwmdezaq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gt2pyhivrag.html

[Q18] 模糊匹配
来源：http://dali.tianlin.xyz/Article/details/gt2ucdermqx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bymtsrru.html

[Q19] 范围查询
来源：http://dali.hnqzz.top/Article/details/gt2yuzgiszm.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ydzc1.top/Article/details/gt2rxsazbgv.html

[Q20] IN 列表
来源：http://dali.yj20258.top/Article/details/gt2szugngvq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2bmcznctr.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gt2nxxynubl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nwbrower.top/Article/details/gt2pajespkn.html

[Q22] 排序
来源：http://dali.ehwqpu.com/Article/details/gt2tdbnnalx.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yanxiufei.cn/Article/details/gt2fsxgwzsk.html

[Q23] 分页
来源：http://dali.chenzaomai.com/Article/details/gt2egkamlfh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wfmgmkhp.html

[Q24] 去重
来源：http://dali.xylfe.cn/Article/details/gt2hzlcigpo.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxobtwjb.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gt2kaozjwhc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.9152youxi.cn/Article/details/gt2dqlvcmef.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gt2hsbfqfvj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2ancjkxms.html

[Q27] 条件计数
来源：http://dali.yuanzhike.top/Article/details/gt2flbftgug.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2izuykkkb.html

[Q28] 求和与平均
来源：http://dali.haohaochexian.top/Article/details/gt2hxmkxqza.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2shaiskxc.html

[Q29] 最大最小值
来源：http://dali.9152youxi.cn/Article/details/gt2ictifxuw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2afxtkaxa.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gt2kqaoyyde.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2mtyahkju.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gt2lwljxhbg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gotoacloud.top/Article/details/gt2ubjdifpa.html

[Q32] 分组拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncntqllv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2hndoawbi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.nwbrower.top/Article/details/gt2hmairgss.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gt2ogfouadi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ybcxt.top/Article/details/gt2fvxnagjf.html

[Q34] 每组取第一条
来源：http://dali.dashuyun.cn/Article/details/gt2ibgvboby.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gt2xwnfijsi.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.ydzc1.top/Article/details/gt2yemoodru.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2xuwohweq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hepcuefd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2wsigpvyk.html

[Q36] 左连接
来源：http://dali.zhixingplan.top/Article/details/gt2rqylyzsq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2oozrwriu.html

[Q37] 右连接
来源：http://dali.wangshuangyany.cn/Article/details/gt2vkrybgem.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ivvv.top/Article/details/gt2ushuzxch.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xylfe.cn/Article/details/gt2idogrpup.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj20258.top/Article/details/gt2ghqalebu.html

[Q39] 自连接（查上下级）
来源：http://dali.tanke756.top/Article/details/gt2smxtpjmp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yanxiufei.cn/Article/details/gt2razsngpq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zycfv.cn/Article/details/gt2jnyticji.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gt2kluwynwe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.aizwys.cn/Article/details/gt2mmoaiiks.html

[Q41] 多表连接
来源：http://dali.yj20258.top/Article/details/gt2gkbdluiy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.tanke756.top/Article/details/gt2uzveqfqo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gt2ktxdkucz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hysaishi.cn/Article/details/gt2ytoqkbwa.html

[Q42] 连接条件附加过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2mbsbwfss.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gt2jghuilzw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gt2qpzldyei.html

[Q43] 标量子查询
来源：http://dali.ybcxt.top/Article/details/gt2hxkexkxf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.chenlongwang.top/Article/details/gt2wjcskpir.html

[Q44] IN 子查询
来源：http://dali.quarkkingdee.top/Article/details/gt2ycelewlh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.gogol.net.cn/Article/details/gt2ptefwiln.html

[Q45] EXISTS 判断存在
来源：http://dali.yuanzhike.top/Article/details/gt2gojtnjaw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gt2vcaioawu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gt2rovaeqpb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhongyouzk.top/Article/details/gt2nkgsrsim.html

[Q47] 与平均值比较
来源：http://dali.jlsjyb.cn/Article/details/gt2cajjnbiy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.c1oappe.top/Article/details/gt2wejylpjg.html

[Q48] CTE 公用表表达式
来源：http://dali.0kj1m.cn/Article/details/gt2seihjxqf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgfzy.top/Article/details/gt2gwfvnxfo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuanzx.com/Article/details/gt2seuicwpk.html

[Q49] 更新单行
来源：http://dali.guowangkeji.top/Article/details/gt2bjxqwhkn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhixingplan.top/Article/details/gt2ukrigxjy.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gt2ecanxvyh.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ppjwa.cn/Article/details/gt2aqvufpig.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lekjuwxh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hnxiangtu.top/Article/details/gt2zuhgackk.html

[Q52] 删除指定行
来源：http://dali.ivvv.top/Article/details/gt2xlvbdasq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2uwpxtgap.html

[Q53] 按条件删除
来源：http://dali.yueranfly.top/Article/details/gt2dteorosp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gt2ikzcbwax.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gt2xdfheuys.html

TRUNCATE TABLE logs;
来源：http://dali.hammf.cn/Article/details/gt2qizunouv.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gt2hogbrhob.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yj202588.top/Article/details/gt2iposmqld.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gt2bgpnhnhy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gt2gsfqrzus.html

[Q57] 行号
来源：http://dali.zhoulong.xyz/Article/details/gt2qxcrnlqr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pycfn.com/Article/details/gt2djzdnrkw.html

[Q58] 累计求和
来源：http://dali.sxryk.cn/Article/details/gt2mbogwwox.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2pbmsdjqp.html

[Q59] 分组内累计
来源：http://dali.c1oappe.top/Article/details/gt2uvifnjeg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2tumxdies.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2hfcqsgqc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guowangkeji.top/Article/details/gt2cxarlccd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2jveevukp.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2ymfcfjrb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gt2fsqdqvoe.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gt2xbtlbnqa.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2civibioe.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gt2pqwlcsge.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sweek.top/Article/details/gt2momlspwb.html

[Q64] 提交事务
来源：http://dali.shzxlz.cn/Article/details/gt2zassgasg.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xszkkvat.html

[Q65] 回滚事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbcmhlzs.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gt2anacegac.html

[Q66] 行锁查询
来源：http://dali.ehwqpu.com/Article/details/gt2zxmduycw.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gt2oyyepjlv.html

[Q67] 设置隔离级别
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxnwtcyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tianlin.xyz/Article/details/gt2vucxwtip.html

[Q68] 保存点
来源：http://dali.chenzaomai.com/Article/details/gt2ylkehmlc.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gt2alhboprw.html

ROLLBACK TO sp1;
来源：http://dali.daria6918.cn/Article/details/gt2swnobmqw.html

[Q69] 查看执行计划
来源：http://dali.gzhubu.top/Article/details/gt2mtznuwta.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.andypj.xyz/Article/details/gt2dhlwynob.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gt2vquumune.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gt2xqpjcvch.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2hqyqkzxt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2shzerbjf.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gt2zwhgswcf.html

SHOW INDEX FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2fsmscmls.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gt2jonrzxkt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gt2zclgkkke.html

[Q74] 强制使用索引
来源：http://dali.316326.xyz/Article/details/gt2ypogqora.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kytgylme.html

[Q75] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gt2pfmaprbl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2amxjodrh.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.hywenlv.cn/Article/details/gt2ngbxyezf.html

[Q76] 按天统计
来源：http://dali.shzxlz.cn/Article/details/gt2pujuwtao.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tian-w.cn/Article/details/gt2juatwqlr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dsixjjkx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.0kj1m.cn/Article/details/gt2zbbjtijb.html

[Q78] 当前时间
来源：http://dali.yuanzhike.top/Article/details/gt2vrlwaieq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sxryk.cn/Article/details/gt2ykcyjmmk.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oumlasya.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.snrcjt.cn/Article/details/gt2ukchryez.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2hvrtgeiu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtrlunot.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzfqaxf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2qsiwsqzo.html


<!-- 参考信息 -->