代发 wailian999

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj202588.top/Article/details/gt2oiwnsvzh.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2nmwqvvks.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uoakdzld.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gt2viispbiz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gt2qltyshnp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekpjrtgk.html

[O04] 定义异步函数并等待
来源：http://dali.yueranfly.top/Article/details/gt2tjhqzzzs.html

Py:   async def f():⏎    await g()
来源：http://dali.vqdsnc.cn/Article/details/gt2egajlmqr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aibaodan.cn/Article/details/gt2yaccwdih.html

JS:   async function f() { await g(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsuirwoa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qbvxumuw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gt2yvsiqjnt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gt2pvbjifdl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zdqjudy.top/Article/details/gt2kwfalbci.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258.top/Article/details/gt2syxeumwc.html

[O05] 并发执行并等待全部完成
来源：http://dali.hammf.cn/Article/details/gt2vtgvlhtg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gt2fpmapypa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuanzx.com/Article/details/gt2cgousfcr.html

JS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gt2qlppipec.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gt2dcguaqsm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gt2vxaejgbx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xdivxskz.html

Ruby: threads.map(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2wqvcpkhh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.iojbl.cn/Article/details/gt2qgneojks.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gt2dlohwdgm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gt2dyjwkdar.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ybcxt.top/Article/details/gt2eiaviqos.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gt2wpcehzxf.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2rbzumepw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gt2bpctdezp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2bupsakew.html

Ruby: // fork 块
来源：http://dali.smart0.xyz/Article/details/gt2iekprlzw.html

C#:   Parallel.For
来源：http://dali.jinghuilouyu.cn/Article/details/gt2napohtys.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2obtsooxa.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gt2jbaazbzm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dtozqrij.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2pnpuatyb.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxuanxn.top/Article/details/gt2oeedmdwm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2dkmkkbgk.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2hauakyvq.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2fdfbimkl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gt2xsoduhon.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gt2gtzjugoe.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gt2zfsnwiky.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.quarkkingdee.top/Article/details/gt2vitxmzto.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gzhubu.top/Article/details/gt2dxymkoyd.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2vpepgokh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gt2asxrzomc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gt2gnqulrcw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.bjfxy.top/Article/details/gt2knxelxbe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gt2onfylezj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qhphelln.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2qtqryegj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gt2wwxfhmei.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzqagorg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cisejmoy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yueranfly.top/Article/details/gt2rgunaozy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gt2zetdbmgc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2luqewrmt.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dashuyun.cn/Article/details/gt2vnbyoseb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2fcapekaf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bafrbzbf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gt2grleujih.html

[P04] 求长度
来源：http://dali.jlsjyb.cn/Article/details/gt2xlwwrklo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gt2soccznpw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2ruibsspr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gt2hdqiwxyi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gt2kfzkoawr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjpeanil.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gt2mmcedjyu.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gt2nxlyiake.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gt2srrdyyqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gt2hkkfpfiz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.andypj.xyz/Article/details/gt2hilkelrd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aizwys.cn/Article/details/gt2ucrlivvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuanzhike.top/Article/details/gt2mlbfcnlv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uhirlcut.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gt2honopkqf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqxzetuq.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2ijdzvfkr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yvedp.cn/Article/details/gt2xtiwvbnf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhixingplan.top/Article/details/gt2axelimty.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcjpcdnb.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ggasdqxn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gt2vcfbblss.html

TS:   if (x == null) {}
来源：http://dali.jianghu66.top/Article/details/gt2qxgfnrwv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pwzddopb.html

Go:   if x == nil {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odgwuqgf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gt2whbwkzid.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ucyiemvn.html

[P07] 防抖与节流
来源：http://dali.smart0.xyz/Article/details/gt2cbwwhfkx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvtpzdxr.html

PHP:  // 手写时间戳比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2axbejzxi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2bzzizufk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gt2nkxjcaat.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iogxnrro.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gt2diivegqs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gt2wvcwatcv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xziqi.cn/Article/details/gt2sglrdwut.html

[P08] 处理浮点精度问题
来源：http://dali.jyoumei.cn/Article/details/gt2ohmqyxpo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gt2dwctclxs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2cmpezmvo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ivvv.top/Article/details/gt2pnsxemhx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gt2elirrsmr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gt2yyitcruq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gt2ekjnlgqt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sysykeji.top/Article/details/gt2mhntjzot.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gt2mzbcxtrs.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2julyshbw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2szjsxdat.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2brnklvhg.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gt2jjskcjoi.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2fqidhhlq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gt2dndftius.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2jeerkequ.html

email VARCHAR(100) UNIQUE,
来源：http://dali.kuanghao11.cn/Article/details/gt2bihmwxvt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.guannengcc.top/Article/details/gt2edclhhzi.html

);
来源：http://dali.meibo888.top/Article/details/gt2ixatcwmp.html

[Q02] 创建带外键的表
来源：http://dali.cheryme.top/Article/details/gt2vdgtmmkg.html

CREATE TABLE orders (
来源：http://dali.yj20258.top/Article/details/gt2ruxhvbhw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2stooteqo.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2mgsnphrd.html

amount DECIMAL(10, 2),
来源：http://dali.chenlongwang.top/Article/details/gt2jtyxxaed.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2meivupdu.html

);
来源：http://dali.jianghu66.top/Article/details/gt2vebjdiol.html

[Q03] 增加列
来源：http://dali.cdnleiting.top/Article/details/gt2lqpjipsv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.daria6918.cn/Article/details/gt2kuyarmtw.html

[Q04] 修改列类型
来源：http://dali.svipenyu.cn/Article/details/gt2ikokaelk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2odchvvtb.html

[Q05] 重命名列
来源：http://dali.hnxiangtu.top/Article/details/gt2kwchhhyj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.0kj1m.cn/Article/details/gt2nqttzxhe.html

[Q06] 删除列
来源：http://dali.vqdsnc.cn/Article/details/gt2nejoendn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvssarok.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gt2snqshhse.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhengqikj.top/Article/details/gt2mbmroewe.html

[Q08] 创建普通索引
来源：http://dali.pengpengdd.cyou/Article/details/gt2okzjxpty.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhoulong.xyz/Article/details/gt2evwrkopk.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2oiastgxz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvoczeui.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gt2dcdnmcoj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xylfe.cn/Article/details/gt2rsdrceiu.html

[Q11] 一次插入多行
来源：http://dali.zhengqikj.top/Article/details/gt2shlrcngs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sufxvd.cn/Article/details/gt2wiqhpzqe.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gt2ozomdqkd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yanxiufei.cn/Article/details/gt2zxjzjkxq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yuanzhike.top/Article/details/gt2haitrzbx.html

[Q13] 忽略重复插入
来源：http://dali.hnqzz.top/Article/details/gt2qvsffdpr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2fwsdkwwf.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gt2kttcbzlz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gt2kktxcfdo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.pengpengdd.cyou/Article/details/gt2shqhaazi.html

[Q15] 查询全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etvdgqob.html

SELECT * FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gt2aivfocqj.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gt2nkllhqjm.html

SELECT id, name FROM users;
来源：http://dali.hnqzz.top/Article/details/gt2oyyayniy.html

[Q17] 条件查询
来源：http://dali.nanxuanxn.top/Article/details/gt2xutwjxug.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yvedp.cn/Article/details/gt2kriyssnr.html

[Q18] 模糊匹配
来源：http://dali.jinqigufen.top/Article/details/gt2vhhixfil.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gt2xrziiaaa.html

[Q19] 范围查询
来源：http://dali.svipenyu.cn/Article/details/gt2ckmhdjqn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuxming.cn/Article/details/gt2dsbaeexx.html

[Q20] IN 列表
来源：http://dali.jyoumei.cn/Article/details/gt2dbbcgvwr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2iunciqit.html

[Q21] 空值判断
来源：http://dali.fengsongda.top/Article/details/gt2pqxdvcgk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hfpthk.cn/Article/details/gt2uhgcplrg.html

[Q22] 排序
来源：http://dali.iojbl.cn/Article/details/gt2olbjcwxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.vqdsnc.cn/Article/details/gt2vbqynjfp.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2hcvbfujz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cqqwz.cn/Article/details/gt2aymibron.html

[Q24] 去重
来源：http://dali.jiagoushi.top/Article/details/gt2seotblel.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kpvgnfds.html

[Q25] 只取前 N 条
来源：http://dali.cdnleiting.top/Article/details/gt2tyrnwanc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhiwuduotai.top/Article/details/gt2khsktfzc.html

[Q26] 计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tprbhsnk.html

SELECT COUNT(*) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2cqsbwaim.html

[Q27] 条件计数
来源：http://dali.cdnleiting.top/Article/details/gt2tmmmvqep.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2nysrbyju.html

[Q28] 求和与平均
来源：http://dali.andypj.xyz/Article/details/gt2qbkngfdh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cucudq.cn/Article/details/gt2qkzeebfj.html

[Q29] 最大最小值
来源：http://dali.yongpay.top/Article/details/gt2zkvavsyy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2qznzqsuc.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gt2ebbjnjlc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hnqzz.top/Article/details/gt2qjzbhzvh.html

[Q31] 分组后过滤
来源：http://dali.zhengqikj.top/Article/details/gt2awtocihb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gt2tmbmjpgl.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2avicxtbt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yehqyeem.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gt2gvdqjytp.html

[Q33] 多列分组
来源：http://dali.ppjwa.cn/Article/details/gt2mwbyhmhi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctowfyav.html

[Q34] 每组取第一条
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qydfckue.html

SELECT * FROM (
来源：http://dali.guowangkeji.top/Article/details/gt2gjgsyeax.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.birdmap.top/Article/details/gt2wjqcfinw.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2zcuxdjhc.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2kzbpexxa.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj20258888.top/Article/details/gt2onscdkqx.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gt2hkqkburz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gt2hvkhbbou.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gt2zjkdpzis.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reozenfa.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.gogol.net.cn/Article/details/gt2hjuzidea.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gt2lcybfnsn.html

[Q39] 自连接（查上下级）
来源：http://dali.yonumen.top/Article/details/gt2rivefjar.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghzzoqhc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gt2qothgdtc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gt2lkknhfwh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gt2bczhajpx.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gt2ksymirfq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gt2nedvudim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.fzhhl.top/Article/details/gt2muhrgbuu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2poudieen.html

[Q42] 连接条件附加过滤
来源：http://dali.dianchejie.cn/Article/details/gt2ajngplhv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxubepxy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhixingplan.top/Article/details/gt2brvjuoxn.html

[Q43] 标量子查询
来源：http://dali.jyoumei.cn/Article/details/gt2vvzatpdv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwccbnqs.html

[Q44] IN 子查询
来源：http://dali.cashguo.top/Article/details/gt2yvckklkv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigufen.top/Article/details/gt2dsewgkyy.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gt2xszjqiys.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gt2rphqanml.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gt2rvtnqqou.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gt2iqeqlbjl.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gt2fffvioiq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbjunzyz.html

[Q48] CTE 公用表表达式
来源：http://dali.tianlin.xyz/Article/details/gt2kvhtjhwv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.andypj.xyz/Article/details/gt2lglsturx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2mdkrpyut.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gt2hqprervt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gt2lehqhnib.html

[Q50] 批量更新
来源：http://dali.jyoumei.cn/Article/details/gt2xnsrgdqd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.tanke756.top/Article/details/gt2feadcvrm.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gt2lqvrxuwq.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.daria6918.cn/Article/details/gt2iznbwiqe.html

[Q52] 删除指定行
来源：http://dali.mhx1999.top/Article/details/gt2fvmwohga.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgvdbcvm.html

[Q53] 按条件删除
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgfethtb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nwbrower.top/Article/details/gt2gtvdnztf.html

[Q54] 清空表
来源：http://dali.ydzc1.top/Article/details/gt2ajaikpkc.html

TRUNCATE TABLE logs;
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzpcddik.html

[Q55] 排名（并列占位）
来源：http://dali.yuanzhike.top/Article/details/gt2pfonmcpq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2penbfolt.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gt2nkvvquby.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gt2byzzsbck.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uejrxycx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2rwgpewdp.html

[Q58] 累计求和
来源：http://dali.fengsongda.top/Article/details/gt2yvjjhshs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tanke756.top/Article/details/gt2purnbmip.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gt2opzdlsnc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2vnyjeeep.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gt2noqjmhei.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cashguo.top/Article/details/gt2vaxsntcy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pycfn.com/Article/details/gt2vjexrnnj.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afaueixy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ybcxt.top/Article/details/gt2iaowltrc.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2xesaipmx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2jcvkgobt.html

[Q63] 开启事务
来源：http://dali.cqqwz.cn/Article/details/gt2eiklvega.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.birdmap.top/Article/details/gt2ksboewsb.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gt2qaduutrh.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2xrsoysbo.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gt2kextdhrp.html

ROLLBACK;
来源：http://dali.yangfankeji.com/Article/details/gt2zqkvxyiq.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gt2sjjcnwyd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gt2sjouhakn.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gt2mxfbsnop.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.svipenyu.cn/Article/details/gt2oketqtuv.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2gvsqarpg.html

SAVEPOINT sp1;
来源：http://dali.ybcxt.top/Article/details/gt2tbtfuayo.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gt2hmqsaedu.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gt2gzxiqnjt.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.cashguo.top/Article/details/gt2klmxvaei.html

[Q70] 更新统计信息
来源：http://dali.xuanzx.com/Article/details/gt2lrmozofs.html

ANALYZE TABLE users;
来源：http://dali.hysaishi.cn/Article/details/gt2lyzcrqkh.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2jliyyvup.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.9152youxi.cn/Article/details/gt2puacqngd.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gt2rqvmydef.html

SHOW INDEX FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uhydoiae.html

[Q73] 查看表状态
来源：http://dali.xuanzx.com/Article/details/gt2qxsbbvcb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2czyzjbpg.html

[Q74] 强制使用索引
来源：http://dali.hnqzz.top/Article/details/gt2ssvpkltx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.chenzaomai.com/Article/details/gt2pesnmmil.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2imlicpba.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2yscoyfch.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zycfv.cn/Article/details/gt2gpcwunuw.html

[Q76] 按天统计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqqkmrgl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cashguo.top/Article/details/gt2touljppd.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gt2vkhuwnlj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gt2lejtmuue.html

[Q78] 当前时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyofqzcd.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gt2dcmzrgpz.html

[Q79] 字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gemcdtqw.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2vmyzbiqs.html

[Q80] 字符串截取
来源：http://dali.gotoacloud.top/Article/details/gt2vclsqvrw.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2bohdbjzg.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2oorwqtcw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2clecqzug.html

[Q82] 字符长度与字节长度
来源：http://dali.shzxlz.cn/Article/details/gt2yyyxdaql.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2vuebqmnz.html

[Q83] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gt2inmmjhof.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gt2azuzvrcu.html


<!-- 参考信息 -->