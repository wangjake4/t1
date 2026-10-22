代发 wailian999

TS:   // worker_threads 线程池
来源：http://dali.nanxinkj.top/Article/details/gt2jqfkdphz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2uqbvrjfj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gt2skaicmzx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gt2wsxnfmzw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2uhqbpcto.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gt2ifmjpdbz.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gt2arbxtqnw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gt2hykkhijo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2irhzdahe.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2kgwtbgmh.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2lwfijpvs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udndnklr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnxiangtu.top/Article/details/gt2fpvabntv.html

C#:   lock (gate) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gt2jagmgadg.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gt2lriisctj.html

Py:   async def f():⏎    await g()
来源：http://dali.gzhubu.top/Article/details/gt2jrvkmpoa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhongyouzk.top/Article/details/gt2ncqdnncs.html

JS:   async function f() { await g(); }
来源：http://dali.xylfe.cn/Article/details/gt2hcnneppd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2cwqlwtad.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sufxvd.cn/Article/details/gt2cdxcuofd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuxming.cn/Article/details/gt2yyywqldm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2qkxcldul.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gt2bufmlfnz.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gt2xenhkfgi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gt2bavfpyfy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jlsjyb.cn/Article/details/gt2wqkcwlbx.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2djphvvwu.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gt2skllmmqp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gt2ppebabfz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gt2njfohzzj.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gt2eozcgznl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gt2bjkobpnv.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2qcyjyowl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gt2puousunp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gt2izewwepz.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2idgwtodr.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2gyovmigf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenlongwang.top/Article/details/gt2dtdngxbn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj20258888.top/Article/details/gt2vntnismj.html

Ruby: // fork 块
来源：http://dali.yj20258888.top/Article/details/gt2ykhfmcow.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gt2rjinjkjx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2svwxsyjw.html

P. 常用工具函数
来源：http://dali.9152youxi.cn/Article/details/gt2sngtedrb.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqcrsxza.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gt2rudpchqa.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gt2ffhgbgfp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gt2zhwlvxab.html

JS:   crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gt2tbixsxfj.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2dozjbmpj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gt2enmgdziw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.daxiang520.top/Article/details/gt2gaqdaqbk.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gt2wfixdofo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sufxvd.cn/Article/details/gt2vlyxyjch.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uktziilp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gt2ehenijhv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gt2wistxuac.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2iribeuvi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gt2ugnussnr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2uxmubzsl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cashguo.top/Article/details/gt2xocfohic.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yvedp.cn/Article/details/gt2ioykcgoq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yangfankeji.com/Article/details/gt2guaggvjy.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2wqwqpqmu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gt2uecenprh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zdqjudy.top/Article/details/gt2wnarhuik.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2exwqsrml.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2jyljizow.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gt2peocljqr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2otjxrjim.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2eszyfvaa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xziqi.cn/Article/details/gt2wgobdpmd.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gt2sqpsdlnf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gt2cnjndcfg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2yiucvosx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gt2knhuxuah.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2jebmddva.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gt2vdnsrhrh.html

Go:   len(arr);  len(m)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rtjmdadr.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gt2blamybzh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tian-w.cn/Article/details/gt2xugfrxhb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gt2xpcteeta.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ybcxt.top/Article/details/gt2vcegiosh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.havefunace.top/Article/details/gt2qchzmczt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gt2thdtmwre.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gt2chikdejv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gt2tvobhguo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2kwqfhweg.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gt2duuamily.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gt2mzwnfdcc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yangfankeji.com/Article/details/gt2kzhndrsv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ydzcwqsy.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vifygpoa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yongpay.top/Article/details/gt2emhtwxat.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2pemletyl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2ljylnjfp.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gt2quldeaay.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gt2dqunasdj.html

C#:   if (x is null) {}
来源：http://dali.zycfv.cn/Article/details/gt2pgbquexu.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gt2wampfoxh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbkljchq.html

PHP:  // 手写时间戳比较
来源：http://dali.cqqwz.cn/Article/details/gt2jpcivfwa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2faxibdkp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gt2xrkojgus.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.fengsongda.top/Article/details/gt2gittawbx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jlsjyb.cn/Article/details/gt2drlvlkvs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gt2prbzcdak.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sufxvd.cn/Article/details/gt2qbrmgdoe.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gt2pxdslfnf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2klknyhtr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gt2acqggzzo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tanke756.top/Article/details/gt2ljvvbdiv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vksaqoae.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gt2zxksomcx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gt2dqjanace.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2decbdovy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwppnqxk.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eozlehbq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sysykeji.top/Article/details/gt2xkchhuop.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zvcutfzj.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gt2fqsfihfu.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gt2cyawlwsv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gt2ewudhdns.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olxgfkfb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hywenlv.cn/Article/details/gt2mcnugrrp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gt2vpjjharz.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxhvdgdd.html

[Q02] 创建带外键的表
来源：http://dali.yangfankeji.com/Article/details/gt2cqvtttgn.html

CREATE TABLE orders (
来源：http://dali.yuxming.cn/Article/details/gt2oiqtqltt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2rrdfloep.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtxdtdd.html

amount DECIMAL(10, 2),
来源：http://dali.xziqi.cn/Article/details/gt2twwmdcnd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gt2kfwoeqbs.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpipbnod.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gt2fwnylpkv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenzaomai.com/Article/details/gt2pcugohap.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zadzmsxx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vnirasxb.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gt2avdvvhcu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xziqi.cn/Article/details/gt2rmxxutly.html

[Q06] 删除列
来源：http://dali.yj20258888.top/Article/details/gt2wjwzvjcf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.andypj.xyz/Article/details/gt2gjzbccry.html

[Q07] 删除表
来源：http://dali.havefunace.top/Article/details/gt2xzitroxo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.tianlin.xyz/Article/details/gt2ravlttlz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2iohkjvpo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2sakklcdu.html

[Q09] 创建唯一索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2iblcmdnp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shzxlz.cn/Article/details/gt2cubmxfky.html

[Q10] 插入单行
来源：http://dali.sxryk.cn/Article/details/gt2amtgdekh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2fupltmri.html

[Q11] 一次插入多行
来源：http://dali.daxiang520.top/Article/details/gt2rpfeeosv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2dpvavpkx.html

[Q12] 插入后取自增 ID
来源：http://dali.pycfn.com/Article/details/gt2pfpsylsy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.iojbl.cn/Article/details/gt2qnwspwux.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.feifeiyinyue.top/Article/details/gt2ownxkcjx.html

[Q13] 忽略重复插入
来源：http://dali.sweek.top/Article/details/gt2zazmdqjr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2mubmcbna.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gt2dtjynoyo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sxryk.cn/Article/details/gt2mbsemkgc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.havefunace.top/Article/details/gt2bzlurkvl.html

[Q15] 查询全部
来源：http://dali.xuetiantiany.cn/Article/details/gt2sknhjokn.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gt2nhjynvgu.html

[Q16] 查询指定列
来源：http://dali.xziqi.cn/Article/details/gt2lsvbwyng.html

SELECT id, name FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2wlibvezo.html

[Q17] 条件查询
来源：http://dali.cqqwz.cn/Article/details/gt2jyjmaddn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shzxlz.cn/Article/details/gt2pkutmlmb.html

[Q18] 模糊匹配
来源：http://dali.zhengqikj.top/Article/details/gt2apybbpgu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.9152youxi.cn/Article/details/gt2smiahpok.html

[Q19] 范围查询
来源：http://dali.daria6918.cn/Article/details/gt2ythkokgu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhengqikj.top/Article/details/gt2vmkijyte.html

[Q20] IN 列表
来源：http://dali.xuanzx.com/Article/details/gt2evjvnadb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tianlin.xyz/Article/details/gt2hfplqouh.html

[Q21] 空值判断
来源：http://dali.hnxiangtu.top/Article/details/gt2wngitycu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gt2qvzgejdj.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gt2kpjurwpv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gt2qyghfmoz.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2suthajmf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hszvktmp.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gt2mbecrknc.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2guuapetb.html

[Q25] 只取前 N 条
来源：http://dali.wangdashe.top/Article/details/gt2llcfjnss.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.iojbl.cn/Article/details/gt2cjjcxjkt.html

[Q26] 计数
来源：http://dali.kuanghao11.cn/Article/details/gt2eteqxfmh.html

SELECT COUNT(*) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2cevpncum.html

[Q27] 条件计数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqhqntue.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2fzruuyhj.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gt2tgujvkqf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gt2oiqufgol.html

[Q29] 最大最小值
来源：http://dali.sxryk.cn/Article/details/gt2kligzrez.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2vywyqsla.html

[Q30] 分组统计
来源：http://dali.yanxiufei.cn/Article/details/gt2aowqkgoy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gt2qascrynv.html

[Q31] 分组后过滤
来源：http://dali.yj20258888.top/Article/details/gt2hyixhwpb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2perrrmut.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gt2hyrydfrl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gt2iidifdyl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgufenzy.top/Article/details/gt2ywfnsbgy.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2kxwtkysn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nanxuanxn.top/Article/details/gt2ljckqefn.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndkkivlx.html

SELECT * FROM (
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqbohybm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj202588.top/Article/details/gt2qlpfwxvo.html

) t WHERE rn = 1;
来源：http://dali.yangfankeji.com/Article/details/gt2rmyrcmsz.html

[Q35] 内连接
来源：http://dali.gaohongyu789.top/Article/details/gt2udztvdvp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsnukxwl.html

[Q36] 左连接
来源：http://dali.guannengcc.top/Article/details/gt2ofichknk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sxryk.cn/Article/details/gt2iaurncvk.html

[Q37] 右连接
来源：http://dali.ydzc1.top/Article/details/gt2qnvamvor.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhongyouzk.top/Article/details/gt2dhhvcxpi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.c1oappe.top/Article/details/gt2yrpgijxg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gt2bhpkafzf.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gt2pfoduxko.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gt2qpukotiq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangshuangyany.cn/Article/details/gt2vaodiano.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqqqsxni.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.shzxlz.cn/Article/details/gt2vgewecnc.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gt2nhvpyofj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gt2mchgkska.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gt2suxzidxs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258888.top/Article/details/gt2wgqgtzkd.html

[Q42] 连接条件附加过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvevweku.html

SELECT u.name, o.amount FROM users u
来源：http://dali.iojbl.cn/Article/details/gt2neawnend.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gt2pknhiyyp.html

[Q43] 标量子查询
来源：http://dali.xylfe.cn/Article/details/gt2jncacqtn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gt2nherpwgu.html

[Q44] IN 子查询
来源：http://dali.gzhubu.top/Article/details/gt2lrkxlfnd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.kuanghao11.cn/Article/details/gt2exhprpve.html

[Q45] EXISTS 判断存在
来源：http://dali.gaohongyu789.top/Article/details/gt2fjdizrll.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2varwvisv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xinyue.icu/Article/details/gt2gthnswar.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gt2eebuejsi.html

[Q47] 与平均值比较
来源：http://dali.haohaochexian.top/Article/details/gt2ryiyeiqy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pifaylco.html

[Q48] CTE 公用表表达式
来源：http://dali.ppjwa.cn/Article/details/gt2nlkjaznk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.fzhhl.top/Article/details/gt2tqklxngn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhiwuduotai.top/Article/details/gt2klpvqcfe.html

[Q49] 更新单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lybumzox.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.gzhubu.top/Article/details/gt2fvisbueq.html

[Q50] 批量更新
来源：http://dali.sufxvd.cn/Article/details/gt2qsrlhshn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hysaishi.cn/Article/details/gt2eknlifyl.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gt2fgbncpoc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jlsjyb.cn/Article/details/gt2qmhxxqhi.html

[Q52] 删除指定行
来源：http://dali.jqgfzy.top/Article/details/gt2pqybobop.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tianlin.xyz/Article/details/gt2ijmymbmd.html

[Q53] 按条件删除
来源：http://dali.cucudq.cn/Article/details/gt2txbudmic.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.nanxuanxn.top/Article/details/gt2smyvxhyx.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gt2ogalkiao.html

TRUNCATE TABLE logs;
来源：http://dali.0kj1m.cn/Article/details/gt2neyflydr.html

[Q55] 排名（并列占位）
来源：http://dali.hysaishi.cn/Article/details/gt2lsszhrir.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gt2taqclabd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jqgfzy.top/Article/details/gt2hvvdrihy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twnvhfzd.html

[Q57] 行号
来源：http://dali.shzxlz.cn/Article/details/gt2ezfvucfv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2gqombkeu.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gt2zladrzhu.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2xfvtijuc.html

[Q59] 分组内累计
来源：http://dali.9152youxi.cn/Article/details/gt2gtnstjfz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2mqdaings.html

[Q60] 取上一行 / 下一行
来源：http://dali.yanxiufei.cn/Article/details/gt2qhiiyhcy.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.meibo888.top/Article/details/gt2qsgvrktd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gt2rfgaudvl.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gt2yakmdpqr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gt2sybkyoib.html

[Q62] 分组占比
来源：http://dali.yanxiufei.cn/Article/details/gt2nsfonjdp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cheryme.top/Article/details/gt2ajeecgxy.html

[Q63] 开启事务
来源：http://dali.316326.xyz/Article/details/gt2nxioetxd.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.iojbl.cn/Article/details/gt2btrsxvve.html

[Q64] 提交事务
来源：http://dali.cheryme.top/Article/details/gt2ogilnass.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gt2wbsfdrmq.html

[Q65] 回滚事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2jagmefvx.html

ROLLBACK;
来源：http://dali.cqqwz.cn/Article/details/gt2lmkyfxap.html

[Q66] 行锁查询
来源：http://dali.vqdsnc.cn/Article/details/gt2eaxokimo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gt2gkichqjl.html

[Q67] 设置隔离级别
来源：http://dali.ybcxt.top/Article/details/gt2ogybrezr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gt2nqjkgbmf.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2fmxsdthg.html

SAVEPOINT sp1;
来源：http://dali.yvedp.cn/Article/details/gt2zvvijwbe.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rdddjjcp.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gt2oymgzhoq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gt2kpeggcls.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2bpjaycsn.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gt2qapgelli.html

[Q71] 查看建表语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2kueoakmq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aizwys.cn/Article/details/gt2ylfzyytk.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gt2bqvlnyst.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2jqerjdet.html

[Q73] 查看表状态
来源：http://dali.sxryk.cn/Article/details/gt2egwwohzx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2tqfybxfm.html

[Q74] 强制使用索引
来源：http://dali.fzhhl.top/Article/details/gt2krmnkzxc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2wqefppgb.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2abnohqjn.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ydzc1.top/Article/details/gt2nhkgykex.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.aizwys.cn/Article/details/gt2msclrxcb.html

[Q76] 按天统计
来源：http://dali.daxiang520.top/Article/details/gt2ezlbqncr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.316326.xyz/Article/details/gt2axvdxfqs.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gt2kkmysjes.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.bjfxy.top/Article/details/gt2pucuyvyw.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gt2pqpvjcqz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rprccgrk.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gt2lfatiicq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.vqdsnc.cn/Article/details/gt2buwnrplu.html


<!-- 参考信息 -->