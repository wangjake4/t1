代发 wailian999

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gt2rlayzxcd.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2dbwdtqyl.html

Py:   with lock: shared += 1
来源：http://dali.xylfe.cn/Article/details/gt2nmcmtbmi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gt2xenvhvyg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gt2fvkxjscq.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2uozcxrxz.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2guldnokz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gt2sbarqaaw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gt2kukocawy.html

C#:   lock (gate) { shared++; }
来源：http://dali.yueranfly.top/Article/details/gt2xopeffca.html

[O04] 定义异步函数并等待
来源：http://dali.jqgfzy.top/Article/details/gt2yhhisfix.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghmhvhhr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2csszhrvw.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2oxbarfkf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2kvstvwio.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnqzz.top/Article/details/gt2amayhzts.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gt2helryiyf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gt2viahjkes.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gt2yvevwaki.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gt2ujtfktci.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2tejtlzjr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cqqwz.cn/Article/details/gt2dbjkfypt.html

JS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gt2bbqxqbhz.html

TS:   await Promise.all(tasks)
来源：http://dali.daxiang520.top/Article/details/gt2hieuepeh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gt2skioihzn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2dvqdbtpf.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2zvwhuxxf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2qjlfzmzm.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gt2spaweepg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gt2frnyskwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yongpay.top/Article/details/gt2npssynho.html

JS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldwggdlf.html

TS:   // child_process / cluster 模块
来源：http://dali.hysaishi.cn/Article/details/gt2fypgwddi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2msppgptk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gt2hnsxtegm.html

Ruby: // fork 块
来源：http://dali.chenlongwang.top/Article/details/gt2pnmkgnfa.html

C#:   Parallel.For
来源：http://dali.shuidangran.top/Article/details/gt2ugypiakx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2zyijkttc.html

P. 常用工具函数
来源：http://dali.zycfv.cn/Article/details/gt2ctcocbcu.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2xyfrmxal.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gt2tqcgfkri.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2qfnmrfnw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2nezimllj.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gt2arqffyah.html

TS:   crypto.randomUUID()
来源：http://dali.ydzc1.top/Article/details/gt2qduqlyzb.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangdashe.top/Article/details/gt2eszkyvmu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtvqgouj.html

Ruby: SecureRandom.uuid
来源：http://dali.kuanghao11.cn/Article/details/gt2wxvamiai.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gt2nzcugilb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqqnerta.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzmueifa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gt2wzldfngw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.sysykeji.top/Article/details/gt2pkaafxdk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gt2tjcejltl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.snrcjt.cn/Article/details/gt2xsnpjrwa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xinyue.icu/Article/details/gt2jgpmxlrk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gt2tpvfzsal.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2uvevabjm.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nwcsnpgk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.c1oappe.top/Article/details/gt2davswwsu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2wmtxcrcf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2iphqrclg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gt2mrvvxtkj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gt2vuxopapu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gt2mhinplwk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.daria6918.cn/Article/details/gt2nhbbdqhp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2huuexlsn.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2fkkqgtdo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2strmfxuc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2puacrppa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhixingplan.top/Article/details/gt2uvtujjzb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gt2pwhnrjxs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhoulong.xyz/Article/details/gt2vacpgwwl.html

Go:   len(arr);  len(m)
来源：http://dali.fengsongda.top/Article/details/gt2wglxxwmz.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2ujyzryco.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gt2zaqalwfo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ybcxt.top/Article/details/gt2domtvwnt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gkxphaus.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gt2iiixyblj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cheryme.top/Article/details/gt2odlycncj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2gvfipdao.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gt2nzgjooke.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsigkajz.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2vlqfcikt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gzhubu.top/Article/details/gt2wimjgwrz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gt2dcpmpjpy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.vqdsnc.cn/Article/details/gt2deonkzsf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmprqbu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gt2cywqpxut.html

TS:   if (x == null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kuuplmjk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2njvrjexd.html

Go:   if x == nil {}
来源：http://dali.guowangkeji.top/Article/details/gt2yyhcgfha.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2umikrlog.html

C#:   if (x is null) {}
来源：http://dali.birdmap.top/Article/details/gt2jhffwrnw.html

[P07] 防抖与节流
来源：http://dali.daxiang520.top/Article/details/gt2hhyqnqcr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.mhx1999.top/Article/details/gt2eumcfejc.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gt2chptvmbe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gt2jmnimupm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gt2qrpoqlpf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gt2igonoyjo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aibaodan.cn/Article/details/gt2ninzjpnz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gt2slxsvrhz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gt2zfsdyzpv.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gt2rgptzakl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cdnleiting.top/Article/details/gt2banarrni.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jiagoushi.top/Article/details/gt2cylxdexk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfpthecn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2btxnwzxu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigufen.top/Article/details/gt2bfuxycvn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hammf.cn/Article/details/gt2cragdsko.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fzhhl.top/Article/details/gt2jvzmdkvh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gt2wujrthxr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2suvyximc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wrwagjum.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bnajmptt.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2xoesnzow.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gt2qbugzsgz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guannengcc.top/Article/details/gt2nigqgfpv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gzhubu.top/Article/details/gt2aqccobkd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vomubojv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gt2ufsdscrc.html

);
来源：http://dali.jinqigufen.top/Article/details/gt2hpyanmrc.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gt2nycuwbwi.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2whjsuiir.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gt2ukznlozn.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2hhqqmcja.html

amount DECIMAL(10, 2),
来源：http://dali.yanxiufei.cn/Article/details/gt2mpurmxct.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnqzz.top/Article/details/gt2qgtusfjg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2awjboixu.html

[Q03] 增加列
来源：http://dali.svipenyu.cn/Article/details/gt2tagtlupo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shzxlz.cn/Article/details/gt2vahjhthz.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltnqulqc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gt2zcbihadh.html

[Q05] 重命名列
来源：http://dali.snrcjt.cn/Article/details/gt2xxyprnwh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gt2bvpclclk.html

[Q06] 删除列
来源：http://dali.yj202588.top/Article/details/gt2ajuprgmk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.iojbl.cn/Article/details/gt2wkbpqtyn.html

[Q07] 删除表
来源：http://dali.yonumen.top/Article/details/gt2cawibber.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gt2gipxgfdd.html

[Q08] 创建普通索引
来源：http://dali.jlsjyb.cn/Article/details/gt2nhaoloao.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gt2rvvziroa.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gt2mdxxhawg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2ksfengqz.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gt2qedicnth.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.vqdsnc.cn/Article/details/gt2htluguzi.html

[Q11] 一次插入多行
来源：http://dali.hammf.cn/Article/details/gt2qmwqvstg.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.9152youxi.cn/Article/details/gt2euaroycl.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gt2dazgxfvv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yj202588.top/Article/details/gt2qqpvrkap.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnxjwwqc.html

[Q13] 忽略重复插入
来源：http://dali.guowangkeji.top/Article/details/gt2ecmwvcoq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.bjfxy.top/Article/details/gt2itbgmjue.html

[Q14] 存在则更新（upsert）
来源：http://dali.xylfe.cn/Article/details/gt2ocmcndcx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.chenjidiqi.icu/Article/details/gt2ymhnpcry.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.guannengcc.top/Article/details/gt2tlhmhcgf.html

[Q15] 查询全部
来源：http://dali.jyoumei.cn/Article/details/gt2xrwescha.html

SELECT * FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gt2vaolgpjm.html

[Q16] 查询指定列
来源：http://dali.hongshengwenyu.top/Article/details/gt2ubknvvav.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2sqhagycg.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gt2mtkqwcas.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhongyouzk.top/Article/details/gt2vyetcbai.html

[Q18] 模糊匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekmzswnl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.guannengcc.top/Article/details/gt2jpjaalcj.html

[Q19] 范围查询
来源：http://dali.chenjidiqi.icu/Article/details/gt2mtqzimdv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gt2yzdlxjbj.html

[Q20] IN 列表
来源：http://dali.guowangkeji.top/Article/details/gt2dxsjuwyz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tian-w.cn/Article/details/gt2ttwcsuhr.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2itzidtpu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.andypj.xyz/Article/details/gt2zgdiiibq.html

[Q22] 排序
来源：http://dali.cashguo.top/Article/details/gt2gfgltuvn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jqgfzy.top/Article/details/gt2oszgnwbe.html

[Q23] 分页
来源：http://dali.0kj1m.cn/Article/details/gt2fsgnssfv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yuxming.cn/Article/details/gt2yqxfcxng.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2gcbzsctu.html

SELECT DISTINCT city FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2xxreiste.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2oycxlzrl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ppjwa.cn/Article/details/gt2xskwmgev.html

[Q26] 计数
来源：http://dali.haohaochexian.top/Article/details/gt2jbfoldjz.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gt2akewnmxq.html

[Q27] 条件计数
来源：http://dali.daxiang520.top/Article/details/gt2udtffnlf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.birdmap.top/Article/details/gt2adibsqzd.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dujcornn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2owfkkwuv.html

[Q29] 最大最小值
来源：http://dali.snrcjt.cn/Article/details/gt2jltkynom.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aizwys.cn/Article/details/gt2ssvatssp.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gt2lajjnrud.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gt2agzlvrxc.html

[Q31] 分组后过滤
来源：http://dali.pengpengdd.cyou/Article/details/gt2iweezfxw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gogol.net.cn/Article/details/gt2kpufhwxy.html

[Q32] 分组拼接字符串
来源：http://dali.yj202588.top/Article/details/gt2qjrhydoe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2exxtmlgm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.havefunace.top/Article/details/gt2ognpwttj.html

[Q33] 多列分组
来源：http://dali.nanxinkj.top/Article/details/gt2ygungyvn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gt2ydmfqofc.html

[Q34] 每组取第一条
来源：http://dali.yj20258.top/Article/details/gt2izzbwsfa.html

SELECT * FROM (
来源：http://dali.zhoulong.xyz/Article/details/gt2vequufwc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gt2uuwdgrkw.html

) t WHERE rn = 1;
来源：http://dali.redwolf501.top/Article/details/gt2edpefbji.html

[Q35] 内连接
来源：http://dali.nwbrower.top/Article/details/gt2euuavahi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gt2rsorrtcb.html

[Q36] 左连接
来源：http://dali.yj20258888.top/Article/details/gt2xuxktwrk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gt2iivcqieb.html

[Q37] 右连接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnqiibna.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hammf.cn/Article/details/gt2vetfwbpo.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhkcsqqf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ydzc1.top/Article/details/gt2dalwjpex.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycyndaxz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnxiangtu.top/Article/details/gt2mtxqvvst.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2gsiontjm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.smart0.xyz/Article/details/gt2orpryqkn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gzhubu.top/Article/details/gt2kupvrcsf.html

[Q41] 多表连接
来源：http://dali.hnqzz.top/Article/details/gt2kcnfrvud.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnogjmjz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gzhubu.top/Article/details/gt2zrquokmx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gt2lllmawgo.html

[Q42] 连接条件附加过滤
来源：http://dali.hysaishi.cn/Article/details/gt2rruvdrtm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.aibaodan.cn/Article/details/gt2xlzpqpqm.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aizwys.cn/Article/details/gt2iwtvnkqh.html

[Q43] 标量子查询
来源：http://dali.sysykeji.top/Article/details/gt2amedtabb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuxming.cn/Article/details/gt2nhgcuauo.html

[Q44] IN 子查询
来源：http://dali.c1oappe.top/Article/details/gt2ugmscbjq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sweek.top/Article/details/gt2khklglub.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2dwpjbxgo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2fomicolh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.quarkkingdee.top/Article/details/gt2qxlylqer.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gt2zscmrhus.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gt2yemrzyul.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gt2dvgouopc.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gt2toxdbfzv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gt2nbxetxzz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hcrjtqwt.html

[Q49] 更新单行
来源：http://dali.tian-w.cn/Article/details/gt2eqwfqsyq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gt2yegvlsdz.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gt2zxkwjgkc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gt2xcyowvds.html

[Q51] 用子查询更新
来源：http://dali.ehwqpu.com/Article/details/gt2lqmdfowp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxktbahd.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gt2zxivnmpp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2wmnzrkwm.html

[Q53] 按条件删除
来源：http://dali.zycfv.cn/Article/details/gt2lvslvzjw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jinqigufen.top/Article/details/gt2qpelnory.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gt2qcxgmepm.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gt2mbyghwvh.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gt2iusgonux.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gt2mdnstnjs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgufenzy.top/Article/details/gt2jbtmtnsv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxeusebs.html

[Q57] 行号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jkqcsyoi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2hxcrhlkf.html

[Q58] 累计求和
来源：http://dali.svipenyu.cn/Article/details/gt2yerwalyh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xinyue.icu/Article/details/gt2nzlbktub.html

[Q59] 分组内累计
来源：http://dali.hnxiangtu.top/Article/details/gt2vazxaggq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gt2ktomxloz.html

[Q60] 取上一行 / 下一行
来源：http://dali.ydzc1.top/Article/details/gt2zggmfxqt.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhengqikj.top/Article/details/gt2hzkymyqz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinqigufen.top/Article/details/gt2wrqbpstr.html

[Q61] 移动平均
来源：http://dali.haohaochexian.top/Article/details/gt2agtogmbh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gt2jkkdbfma.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gt2qjkfeuvk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2ypvbxdnd.html

[Q63] 开启事务
来源：http://dali.jqgfzy.top/Article/details/gt2jrmnrufk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gt2bcmufqqc.html

[Q64] 提交事务
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmdfotlp.html

COMMIT;
来源：http://dali.vqdsnc.cn/Article/details/gt2bdybtyur.html

[Q65] 回滚事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2majaheso.html

ROLLBACK;
来源：http://dali.haohaochexian.top/Article/details/gt2koomsinm.html

[Q66] 行锁查询
来源：http://dali.tian-w.cn/Article/details/gt2gfwvbcmk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuanzhike.top/Article/details/gt2bigqbpub.html

[Q67] 设置隔离级别
来源：http://dali.gzhubu.top/Article/details/gt2zgppetdb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.iojbl.cn/Article/details/gt2jcknlreq.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlqemfrb.html

SAVEPOINT sp1;
来源：http://dali.c1oappe.top/Article/details/gt2vruiqqod.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2aejeyhhs.html

[Q69] 查看执行计划
来源：http://dali.meibo888.top/Article/details/gt2nysrehrl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jlsjyb.cn/Article/details/gt2uosisrcn.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gt2lclpcmjr.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gt2tzcyhqwc.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gt2bxsgurjb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gt2qsdpmpnk.html

[Q72] 查看索引
来源：http://dali.nwbrower.top/Article/details/gt2zfekfofo.html

SHOW INDEX FROM users;
来源：http://dali.havefunace.top/Article/details/gt2mmfkqibq.html

[Q73] 查看表状态
来源：http://dali.smart0.xyz/Article/details/gt2dtzdwpem.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gt2umvuxetd.html

[Q74] 强制使用索引
来源：http://dali.havefunace.top/Article/details/gt2kftxnwsk.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ppjwa.cn/Article/details/gt2hgubravx.html

[Q75] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2jycoxdur.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2yydcbgqj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gt2kachbxks.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ogygzlvn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gt2ckulvcdr.html

[Q77] 时间加减
来源：http://dali.ehwqpu.com/Article/details/gt2hmfnuhhv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fzhhl.top/Article/details/gt2annsjkfg.html

[Q78] 当前时间
来源：http://dali.hnxiangtu.top/Article/details/gt2ljrvazyt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gt2ilsciiqf.html

[Q79] 字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gt2tykujhhu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dashuyun.cn/Article/details/gt2odutbyfz.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gt2jgkcdwgz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2vstdaiqx.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbkigkam.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2qworoilj.html


<!-- 参考信息 -->