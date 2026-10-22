代发 wailian999

[O02] 使用线程池
来源：http://dali.sysykeji.top/Article/details/gt2tatguuei.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gt2bwvymiog.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gt2avfbxwms.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2rxwgmfam.html

TS:   // worker_threads 线程池
来源：http://dali.yongpay.top/Article/details/gt2rqqzekji.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uwbtsruy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gt2gebdhroh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2cgailqab.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sxryk.cn/Article/details/gt2vrrxoggq.html

[O03] 加锁保护共享数据
来源：http://dali.fzhhl.top/Article/details/gt2kdnyzzsn.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gt2lgljmsoe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gt2nfgbevdx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2surcobhm.html

TS:   // 同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2znnaoycy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnioheux.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2wocfwqwd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gt2ukivougp.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2bjfrugas.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gt2pczqdxfi.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2iimftcdm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gt2ihbdssig.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gt2xmgllifa.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2hoggeeqs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gt2hcvxluuc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gt2rlgphpgv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj202588.top/Article/details/gt2mrhchegf.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gt2hvpjhnxb.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2mywwranm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2yxjkqvtp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daxiang520.top/Article/details/gt2tpqdlgmg.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gt2noiyaejd.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2yjwcfkje.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2lfbppdyf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gt2dvgrxhwr.html

Ruby: threads.map(&:join)
来源：http://dali.ybcxt.top/Article/details/gt2znfmwdzb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlwaphns.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gt2pjqkrhnp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gt2sqqehdxq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gt2aocqmwln.html

JS:   // child_process / cluster 模块
来源：http://dali.jiagoushi.top/Article/details/gt2pzggipir.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fisycqyg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jlsjyb.cn/Article/details/gt2omzxivuk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dianchejie.cn/Article/details/gt2ejyywcqm.html

Ruby: // fork 块
来源：http://dali.shuidangran.top/Article/details/gt2flzdzyfp.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gt2erchtcxq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2khjoxfrp.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gt2bgonukac.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2xblcjvkw.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fikudedu.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gt2dcygrjao.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gt2ehowfhsw.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gt2qanrymaf.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ethgnbdp.html

Java: UUID.randomUUID().toString()
来源：http://dali.daxiang520.top/Article/details/gt2ufjtbcwt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctwvlwdi.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gt2osfxmwrf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gt2nxinvxom.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewkwdgok.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gt2fzgrusln.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gt2etgktein.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.fengsongda.top/Article/details/gt2doawznwi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gt2zobrmasu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2rsbpfvdm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gt2crcdckos.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2tetgyvmq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gt2ygvqzqwb.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2djweccae.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2ixgwlldz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nwbrower.top/Article/details/gt2wlqxnqzr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2cuhyopyu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2qjfocuie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.c1oappe.top/Article/details/gt2dttkqcsb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gt2jzuvlolf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.9152youxi.cn/Article/details/gt2mlbklsev.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.9152youxi.cn/Article/details/gt2uhfvgrkn.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gt2etjqrjqy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gt2dcgqbrlw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2azpojhgd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gt2gkyxnnhw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2saxuathy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2pnyorhtt.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gt2oxkvsegv.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gt2mahvkinx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2zcnsppce.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yanxiufei.cn/Article/details/gt2savnpvdh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unupkbpk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvehofov.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gt2amzhcthu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtzjnuoh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pycfn.com/Article/details/gt2jknmkztn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2mcivdawm.html

Ruby: a == b
来源：http://dali.chenlongwang.top/Article/details/gt2epsxieuo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gt2tussowva.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gt2pevwvyno.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj20258888.top/Article/details/gt2hkjtxugk.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2luztkgax.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuetiantiany.cn/Article/details/gt2oytuptgb.html

TS:   if (x == null) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2lnqyvmgg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gt2ducxpxot.html

Go:   if x == nil {}
来源：http://dali.hnxiangtu.top/Article/details/gt2lazdqivh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gt2ouzdiciy.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xrpxdtjn.html

[P07] 防抖与节流
来源：http://dali.vqdsnc.cn/Article/details/gt2ticqglup.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jlurmvzf.html

PHP:  // 手写时间戳比较
来源：http://dali.snrcjt.cn/Article/details/gt2pvgnnhqm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2tzyeusqy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gt2bafskuqb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gzhubu.top/Article/details/gt2izfpdecl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gt2ueggyqxi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yongpay.top/Article/details/gt2fjpipngc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gt2hljjhete.html

[P08] 处理浮点精度问题
来源：http://dali.daria6918.cn/Article/details/gt2nninoqyo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gt2itzxbiem.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gt2xazbydbz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yanxiufei.cn/Article/details/gt2delqbwjn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2nzwotozn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sxryk.cn/Article/details/gt2hhqkmgmc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.haohaochexian.top/Article/details/gt2hbmeutdt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yvedp.cn/Article/details/gt2upserxbr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nwbrower.top/Article/details/gt2pcwyagiw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2xmepreyq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinqigufen.top/Article/details/gt2gjgznxpe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2spwlnihl.html

[Q01] 创建表
来源：http://dali.hnqzz.top/Article/details/gt2ukxjbefs.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2fcwpzbad.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2ybzxyjux.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gt2lupelliz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gt2ghdbneca.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gt2jajunoxs.html

);
来源：http://dali.yj202588.top/Article/details/gt2luqljnzm.html

[Q02] 创建带外键的表
来源：http://dali.havefunace.top/Article/details/gt2kvhatdkt.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyhzrzcj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eeogsrny.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2kowqrgzl.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gt2ybnppupb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gt2uvzgvoej.html

);
来源：http://dali.cqqwz.cn/Article/details/gt2pnyvqewb.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2afqapyuw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvbuotdb.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gt2afcquwdv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2tqzpjnfk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fycogbxc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yj20258.top/Article/details/gt2kiwgsrgb.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gt2zvglqsuc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxjjokwb.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gt2rphnpcus.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sweek.top/Article/details/gt2chfzmboc.html

[Q08] 创建普通索引
来源：http://dali.jiagoushi.top/Article/details/gt2dqerrupg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.haohaochexian.top/Article/details/gt2jjvhbixv.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gt2wzvphmdi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gt2gulmzjhx.html

[Q10] 插入单行
来源：http://dali.hnqzz.top/Article/details/gt2oexdprpz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yueranfly.top/Article/details/gt2hylthybk.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gt2hufxlsgy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gt2vyqnznio.html

[Q12] 插入后取自增 ID
来源：http://dali.xinyue.icu/Article/details/gt2goxblpdu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.fengsongda.top/Article/details/gt2tbmbgdxf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ueajwuva.html

[Q13] 忽略重复插入
来源：http://dali.svipenyu.cn/Article/details/gt2uwjzrbdw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihgcvqlq.html

[Q14] 存在则更新（upsert）
来源：http://dali.tian-w.cn/Article/details/gt2xyemzggm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.havefunace.top/Article/details/gt2wcauuctg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yangfankeji.com/Article/details/gt2jxqvzczj.html

[Q15] 查询全部
来源：http://dali.sweek.top/Article/details/gt2shgcgmyp.html

SELECT * FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hmbyynhz.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gt2jtdfrsde.html

SELECT id, name FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2vofusjph.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gt2apjnhlvu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivtdhmod.html

[Q18] 模糊匹配
来源：http://dali.jianghu66.top/Article/details/gt2qmzbldzi.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.wangdashe.top/Article/details/gt2osbbcqsb.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gt2syahrwqn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sxryk.cn/Article/details/gt2yvbpxqsv.html

[Q20] IN 列表
来源：http://dali.xziqi.cn/Article/details/gt2ivktpqaj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2tmynkmrm.html

[Q21] 空值判断
来源：http://dali.zdqjudy.top/Article/details/gt2xoqgznmn.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ydzc1.top/Article/details/gt2azzzvwqe.html

[Q22] 排序
来源：http://dali.jyoumei.cn/Article/details/gt2aexopuyq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.316326.xyz/Article/details/gt2kbccktwr.html

[Q23] 分页
来源：http://dali.yvedp.cn/Article/details/gt2sghcjguj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gt2grgqejcs.html

[Q24] 去重
来源：http://dali.fzhhl.top/Article/details/gt2gabdjjlj.html

SELECT DISTINCT city FROM users;
来源：http://dali.havefunace.top/Article/details/gt2ljmlevqs.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gt2yxchlpuq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigfzy.top/Article/details/gt2tdkznbwu.html

[Q26] 计数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucyplfay.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gt2yfgheqws.html

[Q27] 条件计数
来源：http://dali.dianchejie.cn/Article/details/gt2ichczoxe.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxinkj.top/Article/details/gt2agupytyo.html

[Q28] 求和与平均
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvaizqhg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gt2pzkivkct.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gt2bioihftb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.sysykeji.top/Article/details/gt2yrcjpxll.html

[Q30] 分组统计
来源：http://dali.yongpay.top/Article/details/gt2gydeaotn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zycfv.cn/Article/details/gt2syfchmmr.html

[Q31] 分组后过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2mhnxmxmx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gt2jtatyqjg.html

[Q32] 分组拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gt2agserdnd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwvwifvd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hsptrcqw.html

[Q33] 多列分组
来源：http://dali.cucudq.cn/Article/details/gt2ifouwzpa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gaohongyu789.top/Article/details/gt2nuidbfmp.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gt2txrbfcsx.html

SELECT * FROM (
来源：http://dali.iojbl.cn/Article/details/gt2dlhyjqsh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.chenzaomai.com/Article/details/gt2lnenomsg.html

) t WHERE rn = 1;
来源：http://dali.birdmap.top/Article/details/gt2fyyfitay.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gt2sokwmrit.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gt2ahliqayu.html

[Q36] 左连接
来源：http://dali.wangdashe.top/Article/details/gt2czjgffja.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gt2hhqrouii.html

[Q37] 右连接
来源：http://dali.gzhubu.top/Article/details/gt2jexnvkqi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xinyue.icu/Article/details/gt2yzwsjvls.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gt2zwlgdjnc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gt2wzifdjsk.html

[Q39] 自连接（查上下级）
来源：http://dali.ppjwa.cn/Article/details/gt2drisgqit.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gt2uwimffsh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.ybcxt.top/Article/details/gt2wodoioxe.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hfpthk.cn/Article/details/gt2hlpetohi.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gt2wegrolfi.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gt2zdzrefek.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shuidangran.top/Article/details/gt2mkryybln.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gt2dffndvkf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sweek.top/Article/details/gt2adowitts.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gt2opzdomgy.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkagvibj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gt2qydfagen.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gt2imrcmcok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gt2rmuliqap.html

[Q44] IN 子查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgdqplsz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hfpthk.cn/Article/details/gt2imvmasef.html

[Q45] EXISTS 判断存在
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pxcczpop.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2rleytaky.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.meibo888.top/Article/details/gt2pphspxnn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gt2ioehlmox.html

[Q47] 与平均值比较
来源：http://dali.zhengqikj.top/Article/details/gt2kovoyelj.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjfhqrhk.html

[Q48] CTE 公用表表达式
来源：http://dali.andypj.xyz/Article/details/gt2thllhmxb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gt2lkkbqsoo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gt2wboohrur.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gt2uorcueby.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hammf.cn/Article/details/gt2vcbfmuik.html

[Q50] 批量更新
来源：http://dali.jqgufenzy.top/Article/details/gt2ndmtvkup.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gt2miwlqthv.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gt2vnudljgi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.aizwys.cn/Article/details/gt2sbrpvclh.html

[Q52] 删除指定行
来源：http://dali.birdmap.top/Article/details/gt2hagzixsv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2vaeoutzp.html

[Q53] 按条件删除
来源：http://dali.xziqi.cn/Article/details/gt2izjuxdjz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2kbevxhtm.html

[Q54] 清空表
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfuxzpib.html

TRUNCATE TABLE logs;
来源：http://dali.gaohongyu789.top/Article/details/gt2gdqpokhb.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gt2ipdduiom.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gt2lpwwziuw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gt2qcdobkdk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jiagoushi.top/Article/details/gt2ahehgbea.html

[Q57] 行号
来源：http://dali.hammf.cn/Article/details/gt2scxbanwx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2jboqyyje.html

[Q58] 累计求和
来源：http://dali.zdqjudy.top/Article/details/gt2cghmzafy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2qdevlepr.html

[Q59] 分组内累计
来源：http://dali.dashuyun.cn/Article/details/gt2zxsdbaur.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2vkxwldsy.html

[Q60] 取上一行 / 下一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2jquhrneh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aizwys.cn/Article/details/gt2cysscumc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2nnifhjnh.html

[Q61] 移动平均
来源：http://dali.aizwys.cn/Article/details/gt2ahouizej.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gt2ekhcrqoq.html

[Q62] 分组占比
来源：http://dali.zdqjudy.top/Article/details/gt2xpautkcq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2vvabqpzz.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbymnht.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yueranfly.top/Article/details/gt2pxmciawq.html

[Q64] 提交事务
来源：http://dali.vqdsnc.cn/Article/details/gt2zucanryw.html

COMMIT;
来源：http://dali.feifeiyinyue.top/Article/details/gt2muuumepc.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gt2nnwlczre.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2bhkiedit.html

[Q66] 行锁查询
来源：http://dali.hammf.cn/Article/details/gt2biayvqjo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhoulong.xyz/Article/details/gt2qllkweoo.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gt2bcyxhqlj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.redwolf501.top/Article/details/gt2fbomicdn.html

[Q68] 保存点
来源：http://dali.shuidangran.top/Article/details/gt2gnyzpvvj.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gt2sowmxrvm.html

ROLLBACK TO sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2iphixhnp.html

[Q69] 查看执行计划
来源：http://dali.wangdashe.top/Article/details/gt2yqpekmtw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dianchejie.cn/Article/details/gt2mrapblea.html

[Q70] 更新统计信息
来源：http://dali.tanke756.top/Article/details/gt2onkbrtpn.html

ANALYZE TABLE users;
来源：http://dali.yueranfly.top/Article/details/gt2lbbezmfq.html

[Q71] 查看建表语句
来源：http://dali.hammf.cn/Article/details/gt2dmqhvbim.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zycfv.cn/Article/details/gt2xdexsjjo.html

[Q72] 查看索引
来源：http://dali.daxiang520.top/Article/details/gt2rmlxhtro.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2nmbisxva.html

[Q73] 查看表状态
来源：http://dali.chenzaomai.com/Article/details/gt2mreopqoy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tianlin.xyz/Article/details/gt2xddmyrcz.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gt2hrrqorfn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xylfe.cn/Article/details/gt2elxjxons.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gt2vcepaaqp.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gt2nbrcfkno.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwjvtppk.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gt2rzewyjjn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gt2xhqfvhsj.html

[Q77] 时间加减
来源：http://dali.yangfankeji.com/Article/details/gt2nitopbbr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gt2kjhmepny.html


<!-- 参考信息 -->